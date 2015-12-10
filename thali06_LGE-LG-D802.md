#### Test 506502784dae475_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1938): fetch service done; releasing wakelock
I/ConfigFetchService( 1938): stopping self
,W/GAV2    ( 4100): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  964): Killing 3374:com.google.android.music:main/u0a107 (adj 15): empty #17
F/ActivityManager(  964): Service ServiceRecord{431f47f8 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{432766d8 3374:com.google.android.music:main/u0a107} not same as in map: null
D/dalvikvm( 1938): GC_CONCURRENT freed 1583K, 26% free 18381K/24832K, paused 1ms+9ms, total 35ms
F/ActivityManager(  964): Service ServiceRecord{431ec340 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{432766d8 3374:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{430d1c58 u0 com.android.settings/.UsbSettings t2}
D/ChimeraCfgMgr( 1938): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1938): Module APK com.google.android.play.games already loaded
D/AndroidRuntime( 4142): 
D/AndroidRuntime( 4142): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4142): CheckJNI is OFF
D/dalvikvm( 4142): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4142): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4142): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4142): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4142): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4142): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4142): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4142): failed to load memtrack module: -2
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1938): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/AndroidRuntime( 4142): Calling main entry com.android.commands.am.Am
I/ActivityManager(  964): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4142
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
D/PermissionCache(  273): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (214 us)
V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{430d1c58 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  964): resumeTopActivityLocked: Pausing null
V/ActivityManager(  964): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  964): startService SlideAside
D/ActivityManager(  964): setFocusedStack: mFocusedStack=ActivityStack{4318d2c0 stackId=1, 2 tasks}
W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/Icing   ( 1938): Loaded CLD2 Version V2.0 - 20141016
D/AndroidRuntime( 4142): Shutting down VM
D/UsbSettingsControl( 2539): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2539): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/ActivityManager(  964): allPausedActivitiesComplete: r=ActivityRecord{430d1c58 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{430d1c58 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
D/dalvikvm( 4142): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+1ms, total 5ms
I/SlideAside( 3542): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/ActivityManager(  964): resumeTopActivityLocked: Restarting ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  964): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4164 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3542): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3542): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  964): Moving to RESUMED: ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4164): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4164): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4164): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Icing   ( 1938): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
V/WebViewChromium( 4164): Binding Chromium to the background looper Looper (main, tid 1) {4282b180}
I/chromium( 4164): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4164): Initializing chromium process, renderers=0
W/chromium( 4164): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4164): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4164): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4164): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4164): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4164): Remote Branch: 
I/Adreno-EGL( 4164): Local Patches: 
I/Adreno-EGL( 4164): Reconstruct Branch: 
I/dalvikvm( 4164): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4164): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4164): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4164): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4164): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4164): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4164): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4164): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4164): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4164): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4164): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4164): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4164): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4164): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4164): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4164): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4164): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4164): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4164): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4164): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
W/BaseRuntimeLoader( 4164): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4164): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4164): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4164): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/OpenGLRenderer( 4164): Enabling debug mode 0
W/AwContents( 4164): nativeOnDraw failed; clearing to background color.
W/AwContents( 4164): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  964): IME STATUS OFF
I/ActivityManager(  964): Displayed com.test.thalitest/.MainActivity: +388ms
I/ActivityManager( 4164): Timeline: Activity_idle id: android.os.BinderProxy@4282c950 time:116819
D/JsMessageQueue( 4164): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4164): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42830a30
D/dalvikvm( 4164): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x42830a30
D/jxcore_app_log( 4164): JniHelper::setJavaVM(0x416f8838), pthread_self() = 1630885712
D/JX-Cordova( 4164): jxcore cordova android initializing
I/dalvikvm( 4164): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 4164): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4164): VFY: replacing opcode 0x6e at 0x0045
I/ActivityManager(  964): Timeline: Activity_windows_visible id: ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3} time:117188
D/ActivityManager(  964): no-history finish of ActivityRecord{430d1c58 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  964): Finishing activity token=Token{43313a48 ActivityRecord{430d1c58 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
D/UsbSettings( 2539): [AUTORUN] onStop()
V/ActivityManager(  964): Moving to FINISHING: ActivityRecord{430d1c58 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{430d1c58 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{430d1c58 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/dalvikvm( 4164): GC_CONCURRENT freed 2773K, 12% free 21879K/24832K, paused 3ms+1ms, total 45ms
,D/dalvikvm( 4164): WAIT_FOR_CONCURRENT_GC blocked 18ms
,D/dalvikvm( 4164): GC_FOR_ALLOC freed 189K, 12% free 21879K/24832K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4164): Grow heap (frag case) to 23.631MB for 95956-byte allocation
,D/dalvikvm( 4164): GC_FOR_ALLOC freed 206K, 13% free 21888K/24928K, paused 22ms, total 23ms
,I/dalvikvm-heap( 4164): Grow heap (frag case) to 23.685MB for 143930-byte allocation
,D/dalvikvm( 4164): GC_FOR_ALLOC freed 253K, 13% free 21935K/25072K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4164): Grow heap (frag case) to 23.800MB for 215890-byte allocation
,D/dalvikvm( 4164): GC_FOR_ALLOC freed 366K, 13% free 22008K/25284K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4164): Grow heap (frag case) to 23.974MB for 323830-byte allocation
,D/dalvikvm( 4164): GC_FOR_ALLOC freed 564K, 14% free 22129K/25604K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4164): Grow heap (frag case) to 24.247MB for 485740-byte allocation
,D/dalvikvm( 4164): GC_FOR_ALLOC freed 859K, 15% free 22304K/26080K, paused 23ms, total 23ms
,D/dalvikvm( 4164): GC_FOR_ALLOC freed 1275K, 14% free 22560K/26080K, paused 23ms, total 24ms
,I/dalvikvm-heap( 4164): Grow heap (frag case) to 25.248MB for 1092904-byte allocation
,D/dalvikvm( 4164): GC_CONCURRENT freed 1819K, 16% free 22952K/27148K, paused 2ms+4ms, total 39ms
,D/dalvikvm( 4164): GC_FOR_ALLOC freed 207K, 16% free 22895K/27148K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4164): Grow heap (frag case) to 26.096MB for 1639352-byte allocation
,D/dalvikvm( 4164): GC_CONCURRENT freed 1587K, 19% free 23451K/28752K, paused 2ms+1ms, total 29ms
,D/dalvikvm( 4164): GC_FOR_ALLOC freed 1445K, 19% free 23541K/28752K, paused 28ms, total 28ms
,I/dalvikvm-heap( 4164): Grow heap (frag case) to 27.507MB for 2459024-byte allocation
,D/dalvikvm( 4164): GC_CONCURRENT freed 232K, 17% free 25880K/31156K, paused 2ms+7ms, total 40ms
,D/dalvikvm( 4164): GC_FOR_ALLOC freed 4356K, 22% free 24503K/31156K, paused 29ms, total 29ms
,I/dalvikvm-heap( 4164): Grow heap (frag case) to 29.620MB for 3688532-byte allocation
,D/dalvikvm( 4164): GC_CONCURRENT freed 2799K, 27% free 25527K/34760K, paused 2ms+3ms, total 33ms
,D/dalvikvm( 4164): GC_FOR_ALLOC freed 738K, 27% free 25453K/34760K, paused 23ms, total 23ms
,W/jxcore-log( 4164): Initializing JXcore engine
,W/jxcore-log( 4164): JXcore engine is ready
,D/dalvikvm( 4164): GC_CONCURRENT freed 363K, 20% free 28062K/34760K, paused 2ms+1ms, total 25ms
,D/dalvikvm( 4164): WAIT_FOR_CONCURRENT_GC blocked 15ms
,W/jxcore-log( 4164): Starting JXcore engine
,W/jxcore-log( 4164): Platform android
W/jxcore-log( 4164): 
,W/jxcore-log( 4164): Process ARCH arm
W/jxcore-log( 4164): 
,I/jxcore-log( 4164): JXcore Cordova bridge is ready!
I/jxcore-log( 4164): 
,W/jxcore-log( 4164): JXcore engine is started
,I/chromium( 4164): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4164): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4164): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4164): Toggling radios to true
I/jxcore-log( 4164): 
D/BluetoothManagerService(  964): Message: 20
,D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@448bcb78:true
D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  964): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  964): Message: 1
,D/BluetoothManagerService(  964): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  964): New client listening to asynchronous messages
,D/WifiService(  964): setWifiEnabled: true pid=4164, uid=10304
E/WifiService(  964): Invoking mWifiStateMachine.setWifiEnabled
,I/WifiService(  964): setWifiEnabled startWifiDelaySendMsg true
,D/BluetoothAdapterService( 1205): REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothAdapterService(1116062656)( 1205): onCreate
,D/BluetoothManagerService(  964): Message: 20
D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4485d6f0:true
,D/BluetoothAdapterState( 1205): make
I/bluedroid( 1205): init ready=0
D/bt-btif ( 1205): in initialized:0
D/bt-btif ( 1205): root, p->name:Bluedroid, child/value:0x6063a910, bytes:160
D/bt-btif ( 1205): p->used:0, type:0, p->flag:0
,I/BluetoothAdapterState( 1205): Entering OffState
,I/bte_conf( 1205): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
W/BT_PROF ( 1205): set profile trace flags 0x0
,D/BTIF_CORE( 1205): [BTUI] lge_load_bluetooth_address
,D/btif_config_util( 1205): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
D/bt-btif ( 1205):  [BTUI] Load_abtddress
D/bt-btif ( 1205): PERSIST_BDADDR_PROPERTY is  34:FC:EF:9D:93:0B
D/bt-btif ( 1205): Got prior random BDA 34:FC:EF:9D:93:0B
D/lge_bdaddr_loader( 4215): [BTUI] bdaddr_loader ::: START
D/lge_bdaddr_loader( 4215): [BTUI] bluetooth_load_bdaddress
,D/lge_bdaddr_loader( 4215): [BTUI] bdaddr to set in property : 34:FC:EF:9D:93:0B
,E/lge_bdaddr_loader( 4215): [BTUI] bluetooth_load_bdaddress : OK => 34:FC:EF:9D:93:0B
,D/lge_bdaddr_loader( 4215): [BTUI] bdaddr_loader ::: END
,D/WifiStateMachine(  964): setting operational mode to 1
D/WifiStateMachine(  964): handleMessage: E msg.what=131083
,D/WifiStateMachine(  964): processMsg: InitialState
,E/WifiHW  (  964): Wifi MAC Address = 34:fc:ef:de:0a:e2
,I/jxcore-log( 4164): Radios toggled
I/jxcore-log( 4164): 
,E/WifiHW  (  964): wifi_check_config compare "cur_etheraddr=34:fc:ef:de:0a:e2
E/WifiHW  (  964): ": cur_etheraddr=34:fc:ef:de:0a:e2
,D/SoftapController(  270): Softap fwReload - Ok
D/WifiService(  964): disconnect pid=4164, uid=10304
D/WifiService(  964): reconnect pid=4164, uid=10304
,D/CommandListener(  270): Setting iface cfg
,D/CommandListener(  270): Trying to bring down wlan0
,D/WifiMonitor(  964): WifiMonitorSingleton gotten
,I/bluedroid( 1205): get_profile_interface socket
I/bt-btif ( 1205): btif_get_adapter_property 2
,I/bt-btif ( 1205): btif_get_adapter_property 1
D/BluetoothAdapterService(1116062656)( 1205): onBind
I/GKI_LINUX( 1205): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
D/bt-btif ( 1205): btif task starting
D/bt-btif ( 1205): btif_associate_evt: notify ASSOCIATE_JVM
I/bt-btif ( 1205): HAL bt_hal_cbacks->thread_evt_cb
,I/bt-btif ( 1205): execute storage request event : 3
D/bt-btif ( 1205): btif_storage_get_adapter_property property->type:2 
D/BluetoothManagerService(  964): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
I/bt-btif ( 1205): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  964): Message: 40
,D/BluetoothManagerService(  964): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
I/bt-btif ( 1205): execute storage request event : 3
D/bt-btif ( 1205): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1205): in, bd addr:, prop type:1, len:512
I/bt-btif ( 1205): HAL bt_hal_cbacks->adapter_properties_cb
,I/bluedroid( 1205): config_hci_snoop_log
D/BluetoothManagerService(  964): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  964): Broadcasting onBluetoothServiceUp() to 8 receivers.
,D/BluetoothManagerService(  964): Bluetooth Adapter name changed to Thali Test's G2
,D/BluetoothManagerService(  964): Stored Bluetooth name: Thali Test's G2
,D/dalvikvm( 1205): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,D/BluetoothAdapterService(1116062656)( 1205): Enable called with quiet mode status =  false
,D/BluetoothAdapterState( 1205): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
I/BluetoothAdapterState( 1205): Bluetooth adapter state changed: 10-> 11
,D/BluetoothAdapterService( 1205): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  964): Message: 60
,D/BluetoothManagerService(  964): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  964): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothAdapterService(1116062656)( 1205): processStart()
,D/LGBluetoothAPIService( 1154): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapterService(1116062656)( 1205): processStart(): Make Bond State Machine
,D/BluetoothBondStateMachine( 1205): make
,D/BluetoothAdapterService( 1205): setAdapterService(): set to: null
D/BluetoothAdapterService( 1205): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4285c3c0
D/LGBluetoothServiceAdapter( 1205): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 1205): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4285c3c0
,D/LGBluetoothServiceAdapter( 1205): [BTUI] check adapter is available - true : set adapter available.
,D/LGBluetoothSettingsDBObserver( 1205): [BTUI] register observer for LG device name DB
,E/BluetoothAdapterService( 1205): File transfer profiels supported!!
,I/BluetoothBondStateMachine( 1205): StableState(): Entering Off State
,W/BluetoothAdapterService( 1205): Starting service com.broadcom.bt.service.hfp.BrcmHeadsetService
D/BluetoothHeadset(  964): Proxy object connected
D/BluetoothHeadset( 1449): Proxy object connected
D/BluetoothHeadset( 1449): Proxy object connected
D/BluetoothHeadset( 1449): Proxy object connected
E/BluetoothAdapterService( 1205): File transfer profiels supported!!
D/BrcmHeadsetService( 1205): Received start request. Starting profile...
I/Brcm_BluetoothHeadsetServiceJni( 1205): classInitNative: succeeds
D/HeadsetStateMachine( 1205): make
,W/BluetoothAdapterService( 1205): Starting service com.android.bluetooth.a2dp.A2dpService
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/LGBluetoothHeadsetServiceJni( 1205): classInitNative: succeeds
,D/LGBluetoothHfpAdapter( 1205): Version 1.5
D/LGBluetoothXmlHandler( 2539): dvice configuraion start
,D/LGBluetoothXmlHandler( 2539): startDocument!
D/LGBluetoothXmlHandler( 2539): startElement - elet = Device
D/LGBluetoothXmlHandler( 2539): startElement - elet = OLDHELP
D/LGBluetoothXmlHandler( 2539): startElement - elet = OLDHELP
D/LGBluetoothXmlHandler( 2539): startElement - elet = OPPDIRECTORYBLUETOOTH
D/LGBluetoothXmlHandler( 2539): startElement - elet = OPP_DIRECTORY_BLUETOOTH
D/LGBluetoothXmlHandler( 2539): endDocument!
E/BluetoothAdapterService( 1205): File transfer profiels supported!!
I/bluedroid( 1205): get_profile_interface handsfree
I/bt-btif ( 1205): btif_hf_get_interface
I/bt-btif ( 1205): init
D/bt-btif ( 1205): btif_enable_service: current services:0x40
,W/BluetoothAdapterService( 1205): Starting service com.android.bluetooth.hid.HidService
V/AudioPolicyService(  276): getOutput()
V/AudioPolicyManagerBase(  276): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerBase(  276): getOutput() returns output 2
,V/AudioSystem( 1205): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  276): registerClient() client 0xb81daa78, pid 1205
V/AudioFlinger(  276): sendIoConfigEvent() num events 1 event 0, param 0
V/AudioFlinger(  276): sendIoConfigEvent() num events 1 event 0, param 0
V/AudioFlinger(  276): thread 0xb2731008 type 0 TID 738 waking up
V/AudioFlinger(  276): thread 0xb25c6008 type 0 TID 1001 waking up
V/AudioFlinger(  276): acquireWakeLock_l() AudioOut_2 status 0
,V/AudioFlinger(  276): processConfigEvents() remaining events 1
V/AudioFlinger(  276): acquireWakeLock_l() AudioOut_3 status 0
V/AudioFlinger(  276): processConfigEvents() remaining events 1
V/AudioFlinger(  276): PlaybackThread::audioConfigChanged_l, thread 0xb2731008, event 0, param 0
V/AudioSystem(  276): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  276): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  964): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  964): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  276): PlaybackThread::audioConfigChanged_l, thread 0xb25c6008, event 0, param 0
V/AudioSystem(  276): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem(  276): ioConfigChanged() opening already existing output! 3
V/AudioFlinger(  276): acquireWakeLock_l() AudioOut_2 status 0
V/AudioSystem( 1205): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1205): ioConfigChanged() new output samplingRate 48000, format 1 channel mask 0x3 frameCount 960 latency 160
V/AudioSystem( 1449): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1205): getSamplingRate() streamType 8, output 2, sampling rate 48000
V/AudioTrack( 1205): sampleRate 0, channelMask 0x1, format 1
V/AudioTrack( 1205): streamType 8
V/AudioTrack( 1205): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyService(  276): checkPlayCondition().. streamType = 8
V/AudioPolicyManagerBase(  276): checkPlayCondition()... stream = 8, bResult = 0
,V/AudioSystem( 1449): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1601): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1601): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  964): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1205): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1205): ioConfigChanged() new output samplingRate 48000, format 1 channel mask 0x3 frameCount 960 latency 50
V/AudioFlinger(  276): acquireWakeLock_l() AudioOut_3 status 0
,V/AudioSystem(  964): ioConfigChanged() opening already existing output! 3
V/AudioSystem( 1449): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1601): ioConfigChanged() event 0, ioHandle 3
V/AudioTrack( 1205): set() checkPlaycondition!!!! streamType 8 return NO_INIT.
V/AudioSystem( 1601): ioConfigChanged() opening already existing output! 3
,V/AudioSystem( 1449): ioConfigChanged() opening already existing output! 3
,D/BluetoothAdapterService( 1205): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4285c3c0
D/HeadsetStateMachine( 1205): Enter Disconnected: -2
E/BluetoothAdapterService( 1205): File transfer profiels supported!!
D/HeadsetPhoneState( 1205): [BTUI] listenForPhoneState : start = false
,D/LGBluetoothHfpManager( 1205): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetStateMachine( 1205): [BTUI] change sampling rate to 8000 when device is disconnected
D/BluetoothAdapterService( 1205): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4285c3c0
,E/AudioSystem( 1205): AudioSystem::setParameters()...keyValue bt_samplerate=8000
V/AudioFlinger(  276): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1205
V/SRS_Proc(  276): ParamSet string: bt_samplerate=8000
D/audio_hw_primary(  276): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  276): voice_set_parameters: enter: bt_samplerate=8000
V/voice   (  276): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  276): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  276): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  276): adev_set_parameters: exit with code(-2)
,D/BluetoothA2dp(  964): Proxy object connected
D/A2dpService( 1205): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 1205): classInitNative: succeeds
,D/A2dpStateMachine( 1205): make
,W/BluetoothAdapterService( 1205): Starting service com.android.bluetooth.hdp.HealthService
,E/BluetoothAdapterService( 1205): File transfer profiels supported!!
,I/bluedroid( 1205): get_profile_interface a2dp
I/bt-btif ( 1205): btif_av_get_interface
I/bt-btif ( 1205): init
,I/bt-btif ( 1205): ## A2DP START MEDIA TASK ##
,W/BluetoothAdapterService( 1205): Starting service com.android.bluetooth.pan.PanService
I/GKI_LINUX( 1205): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/bt-btif ( 1205): UIPC_Init
I/bt-btif ( 1205): ### uipc_main_init ###
,D/bt-btif ( 1205): UIPC_Open : ch_id 0, p_cback 60ac8b25
I/bt-btif ( 1205): SETUP CHANNEL SERVER 0
I/bt-btif ( 1205): create_server_socket /data/misc/bluedroid/.a2dp_ctrl
I/bt-btif ( 1205): created socket fd 69
I/bt-btif ( 1205): ADD SERVER FD TO ACTIVE SET 69
I/bt-btif ( 1205): UIPC SEND WAKE UP
I/bt-btif ( 1205): ## A2DP MEDIA TASK STARTED ##
,E/bt-btif ( 1205): warning : media task started media_task_refcnt 1 
D/bt-btif ( 1205): btif_enable_service: current services:0x48
D/bt-btif ( 1205): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
I/bt-btif ( 1205): ## ON A2DP IDLE ##
,D/bt-btif ( 1205): UIPC_Close : ch_id 1
I/bt-btif ( 1205): CHANNEL 1 ALREADY CLOSED
I/LGBluetoothA2dpServiceJni( 1205): classInitNative: succeeds
,I/LGBluetoothA2dpAdapter( 1205): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/BluetoothAVRCP1.3ServiceJni( 1205): classInitNativeAVRCP
D/A2dpStateMachine( 1205): Enter Disconnected: -2
E/BluetoothAdapterService( 1205): File transfer profiels supported!!
,V/Avrcp   ( 1205): make
,W/BluetoothAdapterService( 1205): Starting service com.android.bluetooth.map.BluetoothMapService
,D/LGBluetoothAvrcpManager( 1205): [BTUI] initAvcrpManager
,E/BluetoothAdapterService( 1205): File transfer profiels supported!!
D/WifiStateMachine(  964): setWifiState: enabling
W/BluetoothAdapterService( 1205): Starting service com.android.bluetooth.gatt.GattService
,E/WifiStateMachine(  964): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  964): useWiFiOffloading() : false
E/WifiStateMachine(  964): CONFIG_LGE_WLAN_PATH : true
D/WifiStateMachine(  964): Supplicant start successful
D/WifiMonitor(  964): WifiMonitorSingleton gotten
D/WifiMonitor(  964): startMonitoring(wlan0) with mConnected = false
D/WifiMonitor(  964): connecting to supplicant
,I/WifiServiceExtension(  964): WIFI_STATE_CHANGED_ACTION [2]
,V/WfdStateTracker( 1154): WfdStateTracker handleDirectStateChangedEvent: 1
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
,E/Parcel  (  605): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/LGBluetoothAvrcpManager( 1205): [BTUI] initPlayStatus() : isMusicActive = false
,D/LGBluetoothAvrcpAdapter( 1205): [BTUI] Use LG AVRCP : init jni
I/BluetoothAVRCP1.3ServiceJni( 1205): initNativeAVRCP
I/bluedroid( 1205): get_profile_interface avrcp
I/bt-btif ( 1205): btif_rc_get_interface
I/bt-btif ( 1205): ## init ##
,D/BluetoothAdapterService( 1205): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4285c3c0
,V/BluetoothPbapReceiver( 1205): PbapReceiver onReceive 
,E/BluetoothAdapterService( 1205): File transfer profiels supported!!
,V/BluetoothPbapReceiver( 1205): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 1205): ***********state = 11
,W/BluetoothAdapterService( 1205): Starting service com.broadcom.bt.service.sap.SapService
D/wpa_supplicant( 4233): wpa_supplicant v2.1-devel-4.4.2
D/wpa_supplicant( 4233): random: Invalid entropy file /data/misc/wifi/entropy.bin
D/wpa_supplicant( 4233): random: Trying to read entropy from /dev/random
,D/wpa_supplicant( 4233): Get randomness: len=20 entropy=0
,D/wpa_supplicant( 4233): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=0)
D/wpa_supplicant( 4233): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 4233): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4233): Successfully initialized wpa_supplicant
D/wpa_supplicant( 4233): Override interface parameter: ctrl_interface ('(null)' -> '/data/misc/wifi/sockets')
D/wpa_supplicant( 4233): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface '/data/misc/wifi/sockets' bridge 'N/A'
D/wpa_supplicant( 4233): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4233): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/HeadsetStateMachine( 1205): Proxy object connected
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 4233): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4233): disable_scan_offload=1
D/wpa_supplicant( 4233): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4233): update_config=1
D/wpa_supplicant( 4233): device_name='g2_open_com'
D/wpa_supplicant( 4233): manufacturer='LGE'
D/wpa_supplicant( 4233): model_name='LG-D802'
D/wpa_supplicant( 4233): model_number='LG-D802'
D/wpa_supplicant( 4233): serial_number='022678fb504e29b0'
D/wpa_supplicant( 4233): config_methods='physical_display virtual_push_button keypad'
D/wpa_supplicant( 4233): p2p_disabled=1
D/wpa_supplicant( 4233): p2p_no_group_iface=1
D/wpa_supplicant( 4233): Line: 15 - start of a new network block
D/wpa_supplicant( 4233): ssid - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 4233): PSK (ASCII passphrase) - hexdump(len=10): [REMOVED]
D/wpa_supplicant( 4233): key_mgmt: 0x2
D/wpa_supplicant( 4233): priority=1 (0x1)
I/BluetoothHidServiceJni( 1205): classInitNative: succeeds
E/BluetoothAdapterService( 1205): File transfer profiels supported!!
W/BluetoothAdapterService( 1205): Starting service com.broadcom.bt.service.ftp.FTPService
D/HidService( 1205): Received start request. Starting profile...
I/bluedroid( 1205): get_profile_interface hidhost
I/bt-btif ( 1205): btif_hh_get_interface
I/bt-btif ( 1205): init
D/bt-btif ( 1205): btif_enable_service: current services:0x100048
D/BluetoothAdapterService( 1205): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4285c3c0
D/BluetoothAdapterService(1116062656)( 1205): Message: 1
D/BluetoothAdapterService(1116062656)( 1205): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1205): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.hfp.BrcmHeadsetService, state = 12, doUpdate = true
D/HeadsetStateMachine( 1205): Disconnected process message: 10
D/HeadsetPhoneState( 1205): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 1205): Disconnected process message: 11
D/BluetoothPermissionRequest( 2539): onReceive
D/BluetoothAdapterService( 1205): Profile still not running:com.broadcom.bt.service.sap.SapService
I/BluetoothHealthServiceJni( 1205): classInitNative: succeeds
D/HealthService( 1205): Received start request. Starting profile...
D/dalvikvm( 1205): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
I/bluedroid( 1205): get_profile_interface health
I/bt-btif ( 1205): btif_hl_get_interface
I/bt-btif ( 1205): init
D/bt-btif ( 1205): Process name (droid.bluetooth)
D/bt-btif ( 1205): btif_hl_soc_thread_init
D/bt-btif ( 1205): create_thread: entered
D/bt-btif ( 1205): create_thread: thread created successfully
I/LGBluetoothHealthServiceJni( 1205): classInitNative: succeeds
D/BluetoothAdapterService( 1205): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4285c3c0
I/BluetoothPanServiceJni( 1205): classInitNative(L105): succeeds
D/BluetoothPan(  964): BluetoothPAN Proxy object connected
D/PanService( 1205): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1205): initializeNative(L110): pan
I/bluedroid( 1205): get_profile_interface pan
D/bt-btif ( 1205): stack_initialized = 0, btpan_cb.enabled:0
D/BluetoothTethering(  964): got CMD_CHANNEL_HALF_CONNECTED
D/BluetoothAdapterService( 1205): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4285c3c0
I/BluetoothAdapterState( 1205): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/BluetoothAdapterService( 1205): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4285c3c0
I/LGBluetoothMapAdapter( 1205): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 1205): BluetoothMapBinder()
D/bt-btif ( 1205): entered btif_hl_select_thread
D/bt-btif ( 1205): btif_hl_select_wakeup_init
D/bt-btif ( 1205): btif_hl_s,elect_wakeup_init signal_fds[0]=79 signal_fds[1]=80
D/bt-btif ( 1205): max_s=79 
D/bt-btif ( 1205): set curr_set = org_set 
D/BluetoothMapService( 1205): Received start request. Starting profile...
D/BluetoothMapService( 1205): start()
D/BluetoothManagerService(  964): Message: 20
D/BluetoothAdapterService( 1205): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4285c3c0
D/BluetoothManagerService(  964): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4491d068:true
I/BtGatt.JNI( 1205): classInitNative(L685): classInitNative: Success!
D/BtGatt.DebugUtils( 1205): handleDebugAction() action=null
D/BtGatt.GattService( 1205): Received start request. Starting profile...
D/BtGatt.GattService( 1205): start()
I/bluedroid( 1205): get_profile_interface gatt
D/BluetoothAdapterService( 1205): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4285c3c0
D/BluetoothAdapterService(1116062656)( 1205): Message: 1
D/BluetoothAdapterService(1116062656)( 1205): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1205): onProfileServiceStateChange: serviceName=com.android.bluetooth.a2dp.A2dpService, state = 12, doUpdate = true
D/LGBluetoothResetSettingReceiver( 2539): [BTUI] Loading JNI Library
D/BluetoothAdapterService( 1205): Profile still not running:com.broadcom.bt.service.sap.SapService
E/BluetoothSettings_JNI( 2539): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
D/LGBluetoothResetSettingReceiver( 2539): return without doing reset settings.
I/BluetoothSAPServiceJni( 1205): classInitNative(L170): succeeds
D/SapService( 1205): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1205): initializeNative(L175): sap
I/bluedroid( 1205): get_profile_interface sap
I/bt-btif ( 1205): btif_sc_get_interface
I/bt-btif ( 1205): init
D/bt-btif ( 1205): btif_enable_service: current services:0x120048
I/LGBluetoothSapAdapter( 1205): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1205): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 1205): [BTUI] initSapManager
D/LgeBluetoothSimManager( 1449): [BTUI] SAP_ENABLE_EVT
D/BluetoothAdapterService( 1205): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4285c3c0
D/BluetoothAdapterService(1116062656)( 1205): Message: 1
D/BluetoothAdapterService(1116062656)( 1205): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1205): onProfileServiceStateChange: serviceName=com.android.bluetooth.hid.HidService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1205): Profile still not running:com.broadcom.bt.service.sap.SapService
V/BluetoothFTPServiceJni( 1205): classInitNative
I/BluetoothFTPServiceJni( 1205): classInitNative(L271): succeeds
D/BluetoothAdapterService( 1205): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4285c3c0
D/BluetoothFTPService( 1205): BluetoothFtpBinder()
D/**BluetoothFTPService( 1205): Received start request. Starting profile...
V/BluetoothFTPService( 1205): FTP-Server Service start
D/wpa_supplicant( 4233): PSK (from passphrase) - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 4233): Priority group 1
D/wpa_supplicant( 4233):    id=0 ssid='NG700'
D/wpa_supplicant( 4233): Reading configuration file '/system/etc/wifi/wpa_supplicant_overlay.conf'
D/BluetoothFTPServiceJni( 1205): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1205): get_profile_interface ftp
I/bt-btif ( 1205): btif_fts_get_interface
I/bt-btif ( 1205): init
D/bt-btif ( 1205): btif_enable_service: current services:0x120148
D/BluetoothFTPServiceJni( 1205): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1205): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4285c3c0
D/BluetoothAdapterService(1116062656)( 1205): Message: 1
D/BluetoothAdapterService(1116062656)( 1205): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1205): onProfileServiceStateChange: serviceName=com.android.blueto,oth.hdp.HealthService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1205): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116062656)( 1205): Message: 1
D/BluetoothAdapterService(1116062656)( 1205): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1205): onProfileServiceStateChange: serviceName=com.android.bluetooth.pan.PanService, state = 12, doUpdate = true
D/wpa_supplicant( 4233): disable_scan_offload=1
D/wpa_supplicant( 4233): Priority group 1
D/wpa_supplicant( 4233):    id=0 ssid='NG700'
I/wpa_supplicant( 4233): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4233): nl80211: RFKILL status not available
D/wpa_supplicant( 4233): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 4233): nl80211: TDLS supported
D/wpa_supplicant( 4233): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4233): nl80211: Enable multi-channel concurrent (driver advertised support)
I/wpa_supplicant( 4233): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/wpa_supplicant( 4233): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4233): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4233): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 4233): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8db6590
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8db6590
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8db6590
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8db6590
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8db6590
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8db6590
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8db6590
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8db6590
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8db6590
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8db6590
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8db6590
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=2): 0a 11
D/BluetoothAdapterService( 1205): Profile still not running:com.broadcom.bt.service.sap.SapService
V/BluetoothMapService( 1205): Handler(): got msg=1
D/BluetoothAdapterService(1116062656)( 1205): Message: 1
D/BluetoothAdapterService(1116062656)( 1205): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1205): onProfileServiceStateChange: serviceName=com.android.bluetooth.map.BluetoothMapService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1205): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116062656)( 1205): Message: 1
D/BluetoothAdapterService(1116062656)( 1205): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1205): onProfileServiceStateChange: serviceName=com.android.bluetooth.gatt.GattService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1205): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116062656)( 1205): Message: 1
D/BluetoothAdapterService(1116062656)( 1205): MESSAGE_PROFILE_SERVICE_STATE_,CHANGED
D/BluetoothAdapterService( 1205): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.sap.SapService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1205): Profile still not running:com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(1116062656)( 1205): Message: 1
D/BluetoothAdapterService(1116062656)( 1205): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1205): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.ftp.FTPService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1205): All profile services started.
D/BluetoothAdapterState( 1205): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1205): enable 1
I/bt-btif ( 1205): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1205): VERSION G2-AFBT-440-21_MI_00.02_OPP10 (BTE: BCM1200_PI_10.3.20.55)
I/GKI_LINUX( 1205): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 1205): init
I/bt_vendor( 1205): init
I/bt_vnd_conf( 1205): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 1205): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt-btif ( 1205): libbt-hci init returns 0
I/bt_hci_bdroid( 1205): bt_hc_worker_thread started
I/ActivityManager(  964): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4248 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/HyLog   ( 4248): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4248): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4248): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/AuthorizationBluetoothService( 1526): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  964): Killing 3027:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  964): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4260 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4260): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4260): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4260): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/PCSuite ( 4260): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  964): Killing 3822:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:rfkill, action:3
,I/bt_userial_vendor( 1205): userial vendor open: opening /dev/ttyHS99
D/bt_userial_vendor( 1205): userial_vendor_open():UART is setup
,I/bt_userial_vendor( 1205): device fd = 84 open
,D/bt_hwcfg( 1205): Chipset BCM4335A0
,D/bt_hwcfg( 1205): Target name = [BCM4335A0]
D/bt_hwcfg( 1205): Target name = [BCM4335]
I/bt_hwcfg( 1205): Found patchfile: /system/bin//BCM4335B0_002.001.006.0191.0201_ORC.hcd
,I/bt_hwcfg( 1205): Applying 4335 AXI BRIDGE patch...
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/bt_hwcfg( 1205): bt vendor lib: set UART baud 4000000
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  964): Killing 3217:com.android.mms/u0a35 (adj 15): empty #17
,D/CountryDetector(  964): No listener is left
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
,I/LocationManagerService(  964): remove 430d14c0
,D/LocationManagerService(  964): provider request: passive ProviderRequest[ON interval=0]
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/bt_hwcfg( 1205): Releasing 4335 AXI BRIDGE lock
,D/wpa_supplicant( 4233): netlink: Operstate: linkmode=1, operstate=5
,D/wpa_supplicant( 4233): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4233): nl80211: Use Multi channel concurrency
,D/wpa_supplicant( 4233): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4233): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4233): nl80211: 2457-2482 @ 20 MHz
D/wpa_supplicant( 4233): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4233): nl80211: 5170-5250 @ 40 MHz
D/wpa_supplicant( 4233): nl80211: 5735-5835 @ 40 MHz
,D/wpa_supplicant( 4233): nl80211: Added 802.11b mode based on 802.11g information
,D/Tethering(  964): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/libc    (  270): _dns_getaddrinfo: iptype =0
D/libc    (  270): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/Tethering(  964): sendTetherStateChangedBroadcast 1, 0, 0
D/UsbSettingsReceiver( 2539): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 2539): [AUTORUN] sys.usb.config = boot,adb
D/UsbSettingsReceiver( 2539): [AUTORUN] sys.usb.state = boot,adb
D/UsbSettingsReceiver( 2539): [AUTORUN] persist.sys.usb.config = boot,adb
,D/UsbSettingsReceiver( 2539): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,I/Config  ( 2539): getOperator() : OPEN
D/UsbSettingsControl( 2539): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 2539): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 2539): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 2539): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 2539): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 2539): [AUTORUN] onReceive() : TetherState Changed=wlan0
,D/UsbSettingsControl( 2539): [AUTORUN] setTetherStatus() : status=false
,D/wpa_supplicant( 4233): wlan0: Own MAC address: 34:fc:ef:de:0a:e2
,D/wpa_supplicant( 4233): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4233): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4233): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4233): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4233): wlan0: RSN: flushing PMKID list in the driver
,D/wpa_supplicant( 4233): nl80211: Flush PMKIDs
,D/wpa_supplicant( 4233): wlan0: Setting scan request: 0 sec 100000 usec
,D/wpa_supplicant( 4233): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4233): TDLS: Driver uses internal link setup
D/wpa_supplicant( 4233): WPS: Set UUID for interface wlan0
,D/wpa_supplicant( 4233): WPS: UUID based on MAC address - hexdump(len=16): 4d 54 bb 4b f9 ab 59 64 88 e9 60 e7 bf 13 d1 db
D/wpa_supplicant( 4233): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4233): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4233): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4233): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4233): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4233): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4233): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4233): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4233): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4233): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4233): Using existing control interface directory.
I/wpa_supplicant( 4233): 0xb8db5cc8 HY init priv-sock 18 p2p_disabled: 0 path: /data/misc/wifi/sockets/wlan0 name:/data/misc/wifi/sockets/wlan0 ctrl_interface: /data/misc/wifi/sockets, ifname: wlan0
I/wpa_supplicant( 4233): [ITEC] ASSIGN CALL BACK A4 5
I/wpa_supplicant( 4233): [ITEC] ASSIGN CALL BACK A1 6
D/wpa_supplicant( 4233): lge_eap_carrier_var_init
D/wpa_supplicant( 4233): realm format : @wlan.mnc<MNC>.mcc<MCC>.3gppnetwork.org 
D/wpa_supplicant( 4233): wlan0: Added interface wlan0
D/wpa_supplicant( 4233): wlan0: State: DISCONNECTED -> DISCONNECTED
,D/wpa_supplicant( 4233): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4233): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4233): Override interface parameter: ctrl_interface ('(null)' -> '/data/misc/wifi/sockets')
D/wpa_supplicant( 4233): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface '/data/misc/wifi/sockets' bridge 'N/A'
D/wpa_supplicant( 4233): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4233): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4233): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4233): driver_param='use_p2p_group_interface=1use_multi_chan_concurrent=1'
D/wpa_supplicant( 4233): update_config=1
D/wpa_supplicant( 4233): device_name='Thali Test's G2'
D/wpa_supplicant( 4233): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4233): p2p_ssid_postfix='-Thali Test's G2'
D/wpa_supplicant( 4233): persistent_reconnect=1
,D/wpa_supplicant( 4233): Reading configuration file '/system/etc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4233): update_config=1
D/wpa_supplicant( 4233): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4233): driver_param='use_p2p_group_interface=1 use_multi_chan_concurrent=1'
D/wpa_supplicant( 4233): eapol_version=1
D/wpa_supplicant( 4233): ap_scan=1
,D/wpa_supplicant( 4233): fast_reauth=1
D/wpa_supplicant( 4233): p2p_disabled=0
D/wpa_supplicant( 4233): p2p_no_group_iface=0
I/wpa_supplicant( 4233): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4233): nl80211: RFKILL status not available
D/wpa_supplicant( 4233): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 4233): nl80211: TDLS supported
D/wpa_supplicant( 4233): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4233): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4233): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4233): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4233): nl80211: Set mode ifindex 22 iftype 2 (STATION)
D/wpa_supplicant( 4233): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8dc5c28
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8dc5c28
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8dc5c28
,D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8dc5c28
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8dc5c28
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8dc5c28
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8dc5c28
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8dc5c28
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8dc5c28
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8dc5c28
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8dc5c28
,D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=2): 0a 11
,D/wpa_supplicant( 4233): netlink: Operstate: linkmode=1, operstate=5
D/wpa_supplicant( 4233): nl80211: driver param='use_p2p_group_interface=1use_multi_chan_concurrent=1'
D/wpa_supplicant( 4233): nl80211: Use separate P2P group interface
,D/wpa_supplicant( 4233): nl80211: Use Multi channel concurrency
D/wpa_supplicant( 4233): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4233): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4233): nl80211: 2457-2482 @ 20 MHz
D/wpa_supplicant( 4233): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4233): nl80211: 5170-5250 @ 40 MHz
D/wpa_supplicant( 4233): nl80211: 5735-5835 @ 40 MHz
,D/wpa_supplicant( 4233): nl80211: Added 802.11b mode based on 802.11g information
,D/wpa_supplicant( 4233): p2p0: Own MAC address: 36:fc:ef:de:0a:e2
,D/wpa_supplicant( 4233): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4233): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4233): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4233): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4233): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 4233): nl80211: Flush PMKIDs
,D/wpa_supplicant( 4233): p2p0: State: DISCONNECTED -> INACTIVE
,I/bt_hwcfg( 1205): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 1205): Settlement delay -- 100 ms
,I/GAV2    ( 4100): Thread[GAThread,5,main]: No campaign data found.
,D/wpa_supplicant( 4233): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4233): TDLS: Driver uses internal link setup
D/wpa_supplicant( 4233): WPS: Set UUID for interface p2p0
,D/wpa_supplicant( 4233): WPS: UUID from the first interface - hexdump(len=16): 4d 54 bb 4b f9 ab 59 64 88 e9 60 e7 bf 13 d1 db
D/wpa_supplicant( 4233): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4233): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4233): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4233): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4233): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4233): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4233): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4233): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4233): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4233): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4233): Using existing control interface directory.
I/wpa_supplicant( 4233): 0xb8dc5098 HY init priv-sock 23 p2p_disabled: 0 path: /data/misc/wifi/sockets/p2p0 name:/data/misc/wifi/sockets/p2p0 ctrl_interface: /data/misc/wifi/sockets, ifname: p2p0
I/wpa_supplicant( 4233): [ITEC] ASSIGN CALL BACK A4 5
I/wpa_supplicant( 4233): [ITEC] ASSIGN CALL BACK A1 6
I/wpa_supplicant( 4233): [ITEC] sizeof wpa_ssid: 544 / wpa_config: 504 / wpa_supplicant: 1456 / wpa_global: 208 in module
I/wpa_supplicant( 4233): [ITEC] Open WIFLUS socket interface - START
I/wpa_supplicant( 4233): [ITEC] SHARED LIBRARY INITIALIZED Ver: ITEC-LIB-VER-0.98 Tested @: JB44 Build Date Oct 16 2013 19:28:22
I/wpa_supplicant( 4233): [ITEC] USE NON-INET
I/wpa_supplicant( 4233): [ITEC] Open WIFLUS socket interface - DONE 24
,I/wpa_supplicant( 4233): HY wiflus comm channel initialized
D/wpa_supplicant( 4233): P2P: Own listen channel: 11
I/wpa_supplicant( 4233): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/wpa_supplicant( 4233): P2P: Random operating channel: 81:6
D/wpa_supplicant( 4233): P2P: Add operating class 81
D/wpa_supplicant( 4233): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 4233): P2P: Add operating class 115
,D/wpa_supplicant( 4233): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 4233): P2P: wpas_p2p_pre_check_prefered_channel() - Invalid parameter. Just Initialized
D/wpa_supplicant( 4233): p2p0: Added interface p2p0
D/wpa_supplicant( 4233): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4233): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 4233): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4233): random: Got 20/20 bytes from /dev/random
,D/wpa_supplicant( 4233): Get randomness: len=20 entropy=0
D/wpa_supplicant( 4233): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
,D/wpa_supplicant( 4233): CTRL_IFACE monitor attached - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4233): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4233): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4233): nl80211: if_removed already cleared - ignore event
,D/wpa_supplicant( 4233): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4233): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4233): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4233): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4233): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4233): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4233): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4233): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 4233): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  964): transitionTo: destState=SupplicantStartingState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  964): invokeExitMethods: InitialState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=1
,D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine(  964): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131144
D/WifiStateMachine(  964): processMsg: SupplicantStartingState
D/WifiStateMachine(  964): deferMessage: msg=131144
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131085
D/WifiStateMachine(  964): processMsg: SupplicantStartingState
D/WifiStateMachine(  964): deferMessage: msg=131085
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131149
D/WifiStateMachine(  964): processMsg: SupplicantStartingState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): setSuspendOptimizations: 2 true
D/WifiStateMachine(  964): mSuspendOptNeedsDisabled 0
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131145
D/WifiStateMachine(  964): processMsg: SupplicantStartingState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131146
D/WifiStateMachine(  964): processMsg: SupplicantStartingState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131101
D/WifiStateMachine(  964): processMsg: SupplicantStartingState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=147457
D/WifiStateMachine(  964): processMsg: SupplicantStartingState
D/WifiStateMachine(  964): Supplicant connection established
,D/WifiNative-wlan0(  964): doString: DRIVER MACADDR
D/wpa_supplicant( 4233): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4233): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 4233): wlan0: nl80211: scan request
,D/wpa_supplicant( 4233): nl80211: Scan SSID - hexdump(len=0): [NULL]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/wpa_supplicant( 4233): Scan requested (ret=0) - scan timeout 10 seconds
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=14): 44 52 49 56 45 52 20 4d 41 43 41 44 44 52
D/wpa_supplicant( 4233): wlan0: Control interface command 'DRIVER MACADDR'
D/wpa_supplicant( 4233): nl80211: Event message available
D/wpa_supplicant( 4233): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 4233): wlan0: nl80211: Scan trigger
D/WifiNative-wlan0(  964):    returned Macaddr = 34:fc:ef:de:0a:e2
D/WifiStateMachine(  964): MAC Addr from driver = 34:fc:ef:de:0a:e2
D/WifiStateMachine(  964): setWifiState: enabled
,D/WifiOffDelayIfNotUsed(  964): setPowerSaveActivated(false)
D/WifiActivationWhileCharging(  964): unregister : we don't need to unregister
E/WifiStateMachine(  964): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  964): useWiFiOffloading() : false
E/WifiStateMachine(  964): CONFIG_LGE_WLAN_PATH : true
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiConfigStore(  964): Loading config and enabling all networks
,D/WifiNative-wlan0(  964): doString: LIST_NETWORKS
,D/WfdService( 1154): Waiting for WifiP2p enabling
,I/WifiServiceExtension(  964): WIFI_STATE_CHANGED_ACTION [3]
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=13): 4c 49 53 54 5f 4e 45 54 57 4f 52 4b 53
,D/wpa_supplicant( 4233): wlan0: Control interface command 'LIST_NETWORKS'
D/WifiNative-wlan0(  964):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  964): 0	NG700	any	
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 ssid
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=18): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 73 69 64
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 bssid
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 62 73 73 69 64
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
,D/wpa_supplicant( 4233): CTRL_IFACE: Failed to get network variable 'bssid'
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 priority
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 69 6f 72 69 74 79
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='priority'
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 scan_ssid
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=23): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 63 61 6e 5f 73 73 69 64
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 wep_tx_keyidx
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=27): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 74 78 5f 6b 65 79 69 64 78
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
,D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 wep_key0
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 30
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 4233): CTRL_IFACE: Failed to get network variable 'wep_key0'
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 wep_key1
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 31
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
D/wpa_supplicant( 4233): CTRL_IFACE: Failed to get network variable 'wep_key1'
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 wep_key2
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 32
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
D/wpa_supplicant( 4233): CTRL_IFACE: Failed to get network variable 'wep_key2'
,D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 wep_key3
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 33
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
D/wpa_supplicant( 4233): CTRL_IFACE: Failed to get network variable 'wep_key3'
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 psk
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=17): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 73 6b
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='psk'
D/wpa_supplicant( 4233): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 proto
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 6f 74 6f
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 proto'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='proto'
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 key_mgmt
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 6b 65 79 5f 6d 67 6d 74
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
,D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 auth_alg
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 61 75 74 68 5f 61 6c 67
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 pairwise
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 61 69 72 77 69 73 65
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
,I/WifiServiceExtension(  964): batteryPsActivateMsgHandler : state:0 event:3
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 group
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 67 72 6f 75 70
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 group'
,D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='group'
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 eap
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=17): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 61 70
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='eap'
D/wpa_supplicant( 4233): CTRL_IFACE: Failed to get network variable 'eap'
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 phase2
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 68 61 73 65 32
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
,D/wpa_supplicant( 4233): CTRL_IFACE: Failed to get network variable 'phase2'
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 identity
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 69 64 65 6e 74 69 74 79
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='identity'
,D/wpa_supplicant( 4233): CTRL_IFACE: Failed to get network variable 'identity'
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 anonymous_identity
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=32): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 61 6e 6f 6e 79 6d 6f 75 73 5f 69 64 65 6e 74 69 74 79
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
D/wpa_supplicant( 4233): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
,D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 password
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 61 73 73 77 6f 72 64
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='password'
D/wpa_supplicant( 4233): CTRL_IFACE: Failed to get network variable 'password'
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 client_cert
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=25): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 63 6c 69 65 6e 74 5f 63 65 72 74
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
,D/wpa_supplicant( 4233): CTRL_IFACE: Failed to get network variable 'client_cert'
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 ca_cert
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=21): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 63 61 5f 63 65 72 74
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
D/wpa_supplicant( 4233): CTRL_IFACE: Failed to get network variable 'ca_cert'
E/Parcel  (  605): Reading a NULL string not supported here.
,E/Parcel  (  605): Reading a NULL string not supported here.
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 subject_match
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=27): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 75 62 6a 65 63 74 5f 6d 61 74 63 68
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
D/wpa_supplicant( 4233): CTRL_IFACE: Failed to get network variable 'subject_match'
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 engine
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 6e 67 69 6e 65
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 engine'
,D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 engine_id
D/PCSuite ( 4260): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=23): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 6e 67 69 6e 65 5f 69 64
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
D/wpa_supplicant( 4233): CTRL_IFACE: Failed to get network variable 'engine_id'
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 key_id
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 6b 65 79 5f 69 64
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
D/wpa_supplicant( 4233): CTRL_IFACE: Failed to get network variable 'key_id'
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 phase1
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 68 61 73 65 31
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 phase1'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='phase1'
,D/wpa_supplicant( 4233): CTRL_IFACE: Failed to get network variable 'phase1'
D/WifiConfigStore(  964): ***WAPI : not WAPI
D/WifiNative-wlan0(  964): doString: GET_NETWORK 0 private_key
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=25): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 69 76 61 74 65 5f 6b 65 79
D/wpa_supplicant( 4233): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 4233): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
D/wpa_supplicant( 4233): CTRL_IFACE: Failed to get network variable 'private_key'
,E/WifiConfigStore(  964): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/WifiNative-wlan0(  964): doBoolean: SET device_name g2_open_com
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=27): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 67 32 5f 6f 70 65 6e 5f 63 6f 6d
D/wpa_supplicant( 4233): wlan0: Control interface command 'SET device_name g2_open_com'
D/wpa_supplicant( 4233): CTRL_IFACE SET 'device_name'='g2_open_com'
,D/wpa_supplicant( 4233): device_name='g2_open_com'
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: SET manufacturer LGE
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=20): 53 45 54 20 6d 61 6e 75 66 61 63 74 75 72 65 72 20 4c 47 45
D/wpa_supplicant( 4233): wlan0: Control interface command 'SET manufacturer LGE'
D/wpa_supplicant( 4233): CTRL_IFACE SET 'manufacturer'='LGE'
D/wpa_supplicant( 4233): manufacturer='LGE'
,D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: SET model_name LG-D802
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=22): 53 45 54 20 6d 6f 64 65 6c 5f 6e 61 6d 65 20 4c 47 2d 44 38 30 32
D/wpa_supplicant( 4233): wlan0: Control interface command 'SET model_name LG-D802'
D/wpa_supplicant( 4233): CTRL_IFACE SET 'model_name'='LG-D802'
D/wpa_supplicant( 4233): model_name='LG-D802'
,D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: SET model_number LG-D802
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=24): 53 45 54 20 6d 6f 64 65 6c 5f 6e 75 6d 62 65 72 20 4c 47 2d 44 38 30 32
D/wpa_supplicant( 4233): wlan0: Control interface command 'SET model_number LG-D802'
D/wpa_supplicant( 4233): CTRL_IFACE SET 'model_number'='LG-D802'
,D/wpa_supplicant( 4233): model_number='LG-D802'
D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doBoolean: SET serial_number 022678fb504e29b0
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=34): 53 45 54 20 73 65 72 69 61 6c 5f 6e 75 6d 62 65 72 20 30 32 32 36 37 38 66 62 35 30 34 65 32 39 ...
D/wpa_supplicant( 4233): wlan0: Control interface command 'SET serial_number 022678fb504e29b0'
D/wpa_supplicant( 4233): CTRL_IFACE SET 'serial_number'='022678fb504e29b0'
D/wpa_supplicant( 4233): serial_number='022678fb504e29b0'
,D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: SET config_methods physical_display virtual_push_button keypad
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 70 68 79 73 69 63 61 6c 5f 64 69 73 70 ...
D/wpa_supplicant( 4233): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button keypad'
D/wpa_supplicant( 4233): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button keypad'
,D/wpa_supplicant( 4233): config_methods='physical_display virtual_push_button keypad'
D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doBoolean: SET device_type 10-0050F204-5
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 4233): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 4233): CTRL_IFACE SET 'device_type'='10-0050F204-5'
,D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): transitionTo: destState=DriverStartedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=3,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  964): invokeExitMethods: SupplicantStartingState
,D/WifiStateMachine(  964): moveTempStackToStateStack: i=2,j=1
D/WifiStateMachine(  964): moveTempStackToStateStack: i=1,j=2
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=3
,D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=3,startingIndex=1,Top=DriverStartedState
D/WifiStateMachine(  964): invokeEnterMethods: SupplicantStartedState
,D/WifiNative-wlan0(  964): doBoolean: SCAN_INTERVAL 15
W/Settings( 3275): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=16): 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c 20 31 35
D/wpa_supplicant( 4233): wlan0: Control interface command 'SCAN_INTERVAL 15'
,D/wpa_supplicant( 4233): wlan0: Setting scan interval: 15 sec
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): invokeEnterMethods: DriverStartedStateExt
,D/WifiStateMachine(  964): invokeEnterMethods: DriverStartedState
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXSCAN-STOP
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=22): 44 52 49 56 45 52 20 42 54 43 4f 45 58 53 43 41 4e 2d 53 54 4f 50
D/wpa_supplicant( 4233): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
,D/wpa_supplicant( 4233): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): setDetailed state, old =IDLE and new state=DISCONNECTED
,D/WifiNative-wlan0(  964): doBoolean: DRIVER RXFILTER-STOP
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=20): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 4f 50
D/wpa_supplicant( 4233): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
,D/wpa_supplicant( 4233): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: DRIVER RXFILTER-REMOVE 3
D/LGDMClient( 2784): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 52 45 4d 4f 56 45 20 33
D/wpa_supplicant( 4233): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 3'
,D/wpa_supplicant( 4233): wpa_driver_nl80211_driver_cmd  len = 0, 0
,D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: DRIVER RXFILTER-START
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=21): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 41 52 54
D/wpa_supplicant( 4233): wlan0: Control interface command 'DRIVER RXFILTER-START'
,D/wpa_supplicant( 4233): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER RXFILTER-STOP
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=20): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 4f 50
D/wpa_supplicant( 4233): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 4233): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: DRIVER RXFILTER-REMOVE 2
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 52 45 4d 4f 56 45 20 32
D/wpa_supplicant( 4233): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 4233): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: DRIVER RXFILTER-START
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=21): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 41 52 54
D/wpa_supplicant( 4233): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 4233): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): Attempting to reconnect to wifi network ..
D/WifiNative-wlan0(  964): doBoolean: RECONNECT
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 4233): wlan0: Control interface command 'RECONNECT'
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doString: STATUS
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 4233): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  964):    returned wpa_state=SCANNING
D/WifiNative-wlan0(  964): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  964): address=34:fc:ef:de:0a:e2
D/WifiStateMachine(  964): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  964): handleScreenStateChanged: true
D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 4233): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 4233): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4233): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  964):    returned true
,D/WifiP2pService(  964): P2pDisabledState{ when=-2ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/LGDMClient( 2784): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
D/CommandListener(  270): Setting iface cfg
,D/CommandListener(  270): Trying to bring up p2p0
,D/WifiMonitor(  964): WifiMonitorSingleton gotten
D/WifiStateMachine(  964): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine(  964): moveDeferredMessageAtFrontOfQueue; what=131144
,D/WifiMonitor(  964): startMonitoring(p2p0) with mConnected = true
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
,D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=DriverStartedStateExt
D/WifiStateMachine(  964): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=DisconnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ConnectModeState
,D/WifiStateMachine(  964): invokeEnterMethods: DisconnectedState
D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=131144
,V/WfdStateTracker( 1154): WfdStateTracker handleDirectStateChangedEvent: 2
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): handleMessage: X
,D/WifiStateMachine(  964): handleMessage: E msg.what=131085
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): processMsg: DriverStartedState
I/ActivityManager(  964): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4298 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiP2pService(  964): P2pEnablingState
D/WifiP2pService(  964): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2p socket connection successful
D/WifiP2pService(  964): P2pEnabledState
,D/WifiP2pService(  964): sending p2p connection changed broadcast
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=132106
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  964): setWifiDualbandAPConnection band : 1
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=21): 44 55 41 4c 42 41 4e 44 5f 41 50 5f 43 4f 4e 4e 45 43 54 20 31
D/wpa_supplicant( 4233): wlan0: Control interface command 'DUALBAND_AP_CONNECT 1'
E/wpa_supplicant( 4233): nWIFIDualbandAPConnection: 1
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=132096
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  964): set CMD_DISCONNECT_RSSI_LVL : -100
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=24): 44 49 53 43 4f 4e 4e 45 43 54 5f 52 53 53 49 5f 4c 56 4c 20 2d 31 30 30
D/wpa_supplicant( 4233): wlan0: Control interface command 'DISCONNECT_RSSI_LVL -100'
E/wpa_supplicant( 4233): disconnect_rssi_lvl: -100
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =SCANNING and new state=SCANNING
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131154
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131127
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131158
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiNative-p2p0(  964): doBoolean: SET persistent_reconnect 1
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/wpa_supplicant( 4233): p2p0: Control interface command 'SET persistent_reconnect 1'
D/wpa_supplicant( 4233): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4233): persistent_reconnect=1
D/wpa_supplicant( 4233): P2P: New SSID postfix: -Thali Test's G2
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  964): handleMessage: X
D/WifiNative-p2p0(  964):    returned true
D/WifiStateMachine(  964): handleMessage: E msg.what=143371
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): handleMessage: X
D/WifiNative-p2p0(  9,64): doBoolean: SET device_name Thali Test's G2
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=31): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 54 68 61 6c 69 20 54 65 73 74 27 73 20 47 32
D/wpa_supplicant( 4233): p2p0: Control interface command 'SET device_name Thali Test's G2'
D/wpa_supplicant( 4233): CTRL_IFACE SET 'device_name'='Thali Test's G2'
D/wpa_supplicant( 4233): device_name='Thali Test's G2'
D/WifiNative-p2p0(  964):    returned true
D/WifiServiceExtension(  964): postfix byte check : 15
D/WifiNative-p2p0(  964): doBoolean: SET p2p_ssid_postfix -Thali Test's G2
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=37): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 54 68 61 6c 69 20 54 65 73 74 ...
D/wpa_supplicant( 4233): p2p0: Control interface command 'SET p2p_ssid_postfix -Thali Test's G2'
D/wpa_supplicant( 4233): CTRL_IFACE SET 'p2p_ssid_postfix'='-Thali Test's G2'
D/wpa_supplicant( 4233): p2p_ssid_postfix='-Thali Test's G2'
D/wpa_supplicant( 4233): P2P: New SSID postfix: -Thali Test's G2
D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: SET device_type 10-0050F204-5
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 4233): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 4233): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 4233): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 4233): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4233): config_methods='virtual_push_button physical_display keypad'
D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_SET conc_pref sta
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=21): 50 32 50 5f 53 45 54 20 63 6f 6e 63 5f 70 72 65 66 20 73 74 61
D/wpa_supplicant( 4233): p2p0: Control interface command 'P2P_SET conc_pref sta'
D/wpa_supplicant( 4233): Single channel concurrency preference: sta
D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doString: STATUS
D/wpa_supplicant( 4233): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/WifiNative-p2p0(  964):    returned p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-p2p0(  964): p2p_state=IDLE
D/WifiNative-p2p0(  964): wifi_display=1
D/WifiNative-p2p0(  964): ifname=p2p0
D/WifiNative-p2p0(  964): address=36:fc:ef:de:0a:e2
D/WifiNative-p2p0(  964): ifname=wlan0
D/WifiNative-p2p0(  964): address=34:fc:ef:de:0a:e2
D/WifiNative-p2p0(  964): doBoolean: P2P_FLUSH
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=9): 50 32 50 5f 46 4c 55 53 48
D/wpa_supplicant( 4233): p2p0: Control interface command 'P2P_FLUSH'
D/wpa_supplicant( 4233): P2P: Stopping find
D/wpa_supplicant( 4233): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 4233): P2P: State IDLE -> IDLE
D/wpa_supplicant( 4233): wpa_driver_set_ap_wps_p2p_ie: Entry
I/WfdStateTracker( 1154): handleP2pThisDeviceChanged
D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doBoolean: P2P_SERVICE_FLUSH
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=17): 50 32 50 5f 53 45 52 56 49 43 45 5f 46 4c 55 53 48
D/wpa_supplicant( 4233): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
D/WifiNative-p2p0(  964):    returned true
D/WifiNative-p2p0(  964): doString: LIST_NETWORKS
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=13): 4c 49 53 54 5f 4e 45 54 57 4f 52 4b 53
D/wpa_supplicant( 4233): p2p0: Control interface command 'LIST_NETWORKS'
I/bt_hwcfg( 1205): bt vendor lib: set UART baud 4000000
D/HyLog   ( 4298): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4298): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4298): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/bt_hwcfg( 1205): Setting local bd addr to 34:FC:EF:9D:93:0B
D/WifiNative-p2p0(  964):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  964): doBoolean: SAVE_CONFIG
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 4233): p2p0: Control interface command 'SAVE_CONFIG'
D/wpa_supplicant( 4233): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf.tmp'
D/WifiP2pService(  964): [LGE_P2P] initializeP2pSettings() check postfix
D/WifiP2pService(  964): before postfix = Thali Test's G2
D/WifiP2pService(  964): after postfix = Thali Test's G2
D/WifiP2pService(  964): DeviceAddress: 36:fc:ef:de:0a:e2
D/wpa_supplicant( 4233): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
D/wpa_supplicant( 4233): CTRL_IFACE: SAVE_CONFIG - Configuration updated
D/LGDMSGCM( 4298): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/WifiNative-p2p0(  964):    returned true
I/bt_hwcfg( 1205): vendor lib fwcfg completed
I/bt-btif ( 1205): HC preload_cb 0 [0:SUCCESS 1:FAIL]
I/        ( 1205): BTE_InitTraceLevels -- TRC_HCI
I/        ( 1205): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 1205): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 1205): BTE_InitTraceLevels -- TRC_OBEX
I/        ( 1205): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 1205): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 1205): BTE_InitTraceLevels -- TRC_A2D
I/        ( 1205): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 1205): BTE_InitTraceLevels -- TRC_BTM
I/        ( 1205): BTE_InitTraceLevels -- TRC_GAP
I/        ( 1205): BTE_InitTraceLevels -- TRC_PAN
I/        ( 1205): BTE_InitTraceLevels -- TRC_SAP
I/        ( 1205): BTE_InitTraceLevels -- TRC_SDP
I/        ( 1205): BTE_InitTraceLevels -- TRC_GATT
I/        ( 1205): BTE_InitTraceLevels -- TRC_SMP
I/        ( 1205): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 1205): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 1205): BTE_InitTraceLevels -- TRC_PROTOCOL
D/bt-btif ( 1205): btif_task(): received trigger stack init event, state: 1, radio_ref_count: 1, is_radio_req 0, dut_mode: 0
D/bt-btif ( 1205): btif_dm_load_ble_local_keys BLE ER key loaded
D/bt-btif ( 1205): btif_dm_load_ble_local_keys BLE ID keys loaded
I/bt-btif ( 1205): bta_dm_sm_execute event:0x0
I/bt-btif ( 1205): bta_sys_sm_execute state:0, event:0x0
I/bt-btif ( 1205): bta_sys_hw_api_enable for 0, active modules 0x0001
I/bt-btif ( 1205): bta_sys_sm_execute state:1, event:0x1
I/bt-btif ( 1205): bta_sys_hw_evt_enabled for 0
,E/WifiServiceExtension(  964): No p2p device connected
D/WifiP2pService(  964): sending p2p persistent groups changed broadcast
D/WifiP2pService(  964): InactiveState
D/WifiP2pService(  964): InactiveState{ when=-29ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=-29ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): DefaultState{ when=-29ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): InactiveState{ when=-29ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/WifiP2pService(  964): P2pEnabledState{ when=-30ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): DefaultState{ when=-30ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/bt-btif ( 1205):  bta_sys_hw_btm_cback was called with parameter: 0
I/bt-btif ( 1205): bta_sys_sm_execute state:1, event:0x2
D/bt-btif ( 1205):  bta_sys_hw_evt_stack_enabled!notify the callers
D/bt-btif ( 1205):  bta_dm_sys_hw_cback with event: 1
D/bt-btif ( 1205): ##################################
D/bt-btif ( 1205): bta_dm_co_ble_load_local_keys:  Load local keys if any are persisted
D/bt-btif ( 1205): ##################################
D/bt-btif ( 1205): btif_dm_get_ble_local_keys  *p_key_mask=0x03
E/bt-btm  ( 1205): BTM_SecRegister:p_cb_info->p_le_callback == 0x60b1d4c5 
I/bt-smp  ( 1205): SMP_Register state=0
E/bt-btm  ( 1205): BTM_SecRegister: btm_cb.api.p_le_callback = 0x60b1d4c5 
D/bt-btif ( 1205): bta_gattc_register state 0
D/bt-btif ( 1205): bta_gattc_enable
I/bt-att  ( 1205): GATT_Register
D/bt-att  ( 1205): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 1205): allocated gatt_if=3
D/bt-btif ( 1205): bta_dm_gattc_callback event = 0
D/bt-btif ( 1205): BTA_GATTC_REG_EVT client_if = 3
I/bt-att  ( 1205): GATT_StartIf gatt_if=3
D/bt-att  ( 1205): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 1205): gatt_find_the_connected_bda found=0 found_idx=7
I/ActivityManager(  964): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4316 uid=10101 gids={50101, 1028, 1015, 3003}
I/ActivityManager(  964): Killing 3275:com.google.android.talk/u0a77 (adj 15): empty #17
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4316): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4316): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4316): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Wireless_Storage( 4316): CONNECT : WIFI_P2P_STATE_CHANGED_ACTION
V/[BNRBootReceiver]( 4069): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 4069): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,I/ActivityManager(  964): Killing 4011:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
,I/ConfigService( 1526): onDestroy
,I/bt-btif ( 1205): btif_dm_upstreams_cback  ev: BTA_DM_ENABLE_EVT
D/bt-btif ( 1205): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1205): in, bd addr:, prop type:1, len:249
,I/bt-btif ( 1205): bta_dm_sm_execute event:0x2
D/bt-btif ( 1205): BTA is generating EIR
D/bt-sdp  ( 1205): SDP_CreateRecord ok, num_records:3
I/bt-btif ( 1205): Adding UUID=0x110C into EIR
D/bt-btif ( 1205): Adding UUID=0x110C into EIR
D/bt-btif ( 1205): BTA is generating EIR
I/bt-btif ( 1205): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00001000
D/bt-btif ( 1205): nsc_mask: 0x6
D/bt-btif ( 1205): bta_av_co_audio_init
D/bt-btif ( 1205): bta_av_co_audio_init: 0
D/bt-btif ( 1205): audio[0] av_handle: 1 codec_type: 0
D/bt-btif ( 1205): bta_av_co_audio_init
D/bt-btif ( 1205): bta_av_co_audio_init: 1
,D/bt-btif ( 1205): BTIF_APTX_CODEC_ID:6
D/bt-btif ( 1205): audio[1] av_handle: 2 codec_type: 255
D/bt-sdp  ( 1205): SDP_CreateRecord ok, num_records:4
I/bt-a2d  ( 1205): A2D_AddRecord uuid: 110a
I/bt-btif ( 1205): Adding UUID=0x110A into EIR
D/bt-btif ( 1205): BTA is generating EIR
I/bt-btif ( 1205): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00001400
I/bt-btif ( 1205): rc_acp_handle:0 idx:1
D/bt-btif ( 1205): rc_acp_handle:0 idx:1
D/bt-btif ( 1205): create 0, role: 1, shdl:0, rc_handle:0, lidx:3, status:0x10
D/bt-btif ( 1205): reg_audio: 0x1
E/bt-btif ( 1205): bta_ag_scb_alloc 1
D/bt-btif ( 1205): in add:1
I/bt-btif ( 1205): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-sdp  ( 1205): SDP_CreateRecord ok, num_records:5
D/bt-btif ( 1205): bta_ag_add_record uuid: 1112
I/bt-btif ( 1205): Adding UUID=0x1112 into EIR
D/bt-btif ( 1205): BTA is generating EIR
I/bt-btif ( 1205): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00011400
D/bt-sdp  ( 1205): SDP_CreateRecord ok, num_records:6
D/bt-btif ( 1205): bta_ag_add_record uuid: 111f
I/bt-btif ( 1205): Adding UUID=0x111F into EIR
D/bt-btif ( 1205): BTA is generating EIR
I/bt-btif ( 1205): bta_dm_eir_update_uuid UUID bit mask=0x00000000 04011400
D/bt-btif ( 1205): bta_fts_api_enable srm:1
D/bt-btif ( 1205): bta_fts_api_enable srm:1
D/bt-btif ( 1205): Remote device:00:f4:6f:30:e0:6c, size:18
D/bt-sdp  ( 1205): SDP_CreateRecord ok, num_records:7
I/bt-btif ( 1205): Adding UUID=0x1106 into EIR
D/bt-btif ( 1205): Remote device:f8:95:c7:87:3c:51, size:18
D/bt-btif ( 1205): Remote device:f8:95:c
I/bt-btif ( 1205): Remote device:e0:db:10:1f:c9:5e, size:18
D/bt-btif ( 1205): FTS:  SDP Registered (handle 0x00010006)
D/bt-btif ( 1205): FTS:  SDP Registered (handle 0x00010006)
I/bt-btif ( 1205): bta_fts_ci_resume status:1
D/bt-sdp  ( 1205): SDP_CreateRecord ok, num_records:8
I/bt-btif ( 1205): Remote device:b0:c5:59:3f:7
D/bt-btif ( 1205): BTA is generating EIR
D/bt-btif ( 1205): Remote device:14:b4:84:21:3b:49, size:18
D/bt-btif ( 1205): Remote device:14:b4:8
D/bt-btif ( 1205): bta_dm_eir_update_uuid UUID bit mask=0x0
I/bt-btif ( 1205): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04011440
D/bt-btif ( 1205): Remote device:58:3f:54:73:64:c0, size:18
D/bt-btif ( 1205): Remote device:58:3f:
D/bt-btif ( 1205): Remote device:10:d3:8a:fb:85:d4, size:18
D/bt-btif ( 1205): Remote device:b4:ce:f6:ab:a4:6a, size:18
I/bt-btif ( 1205): bta_dm_sm_execute event:0x9
D/bt-btif ( 1205): bta_dm_sm_execute event:0x9
D/bt-btif ( 1205): Remote device:f8:cf:c5:d9:
D/bt-btif ( 1205): GATT_Register
I/bt-att  ( 1205): GATT_Register
D/bt-att  ( 1205): Remote device:08:ec:a9:50:76:84820415442]
D/bt-btif ( 1205): allocated gatt_if=4
I/bt-att  ( 1205): allocated gatt_if=4
D/bt-btif ( 1205): bta_hh_gattc_callback event = 0
D/bt-btif ( 1205): bta_hh_gattc_callback event = 0
I/bt-att  ( 1205): Remote device:44:80:eb
D/bt-btif ( 1205): Remote device:44:80:eb:7b:5a:05, size:18
D/bt-att  ( 1205): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 1205): gatt_find_the_connected_bda found=0 found_idx=7
D/bt-btif ( 1205): Remote device:50:2e:6c:ac:21:50, size:18
D/bt-btif ( 1205): Remote device:7c:f9:0e:37:96:ab, size:18
D/bt-btif ( 1205): Remote device:f4:f1:e1:5c:3b:e2, size:18
D/bt-btif ( 1205): Remote device:34:fc:ef:11:ae:67, size:18
D/bt-btif ( 1205): Remote device:f8:95:c7:87:85:54, size:18
D/bt-btif ( 1205): Remote device:7c:f9:0e:34:8a:a0, size:18
D/bt-btif ( 1205): Remote device:e0:db:10:14:e2:c0, size:18
D/bt-btif ( 1205): Remote device:34:fc:ef:11:b1:66, size:18
D/bt-btif ( 1205): Remote device:90:e7:c4:f6:69:77, size:18
D/bt-btif ( 1205): Remote device:90:e7:c4:3c:62:6a, size:18
D/bt-btif ( 1205): Remote device:58:2a:f7:ed:96:be, size:18
D/bt-btif ( 1205): Remote device:38:94:96:b5:06:dc, size:18
I/bt-btif ( 1205): Remote device:, size:128
D/bt-btif ( 1205): Remote device:, size:128
E/bt-btif ( 1205): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
E/bt-btif ( 1205): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
D/bt-btif ( 1205): out
D/bt-btif ( 1205): btif_storage_get_adapter_property property->type:2 
D/bt-btif ( 1205): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1205): in, bd addr:, prop type:1, len:249
I/bt-btif ( 1205): btif_storage_load_bonded_devices  BT_PROPERTY_DEVICE_MODE
D/bt-btif ( 1205): btif_storage_get_adapter_property property->type:16 
D/bt-btif ( 1205): in, bd addr:, prop type:16, len:4
E/bt-btif ( 1205): Unknow prop type:16
I/bt-btif ( 1205): btif_dm_get_adapter_property: type=0x10
D/bt-btif ( 1205): btif_dm_get_adapter_property btif_device_mode 0
D/bt-btif ( 1205): btif_storage_get_adapter_property property->type:9 
D/bt-btif ( 1205): in, bd addr:, prop type:9, len:4
D/bt-btif ( 1205): btif_storage_get_adapter_property property->type:3 
E/bt-btif ( 1205): btif_storage_get_adapter_property service_mask:0x120148
D/bt-btif ( 1205): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1205): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1205): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1205): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1205): btif_storage_get_adapter_property property->type:3 devicemode 0
I/bt-btif ( 1205): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  964): Bluetooth Adapter name changed to Thali Test's G2
D/BluetoothManagerService(  964): Stored Bluetooth name: Thali Test's G2
E/BluetoothAdapterProperties( 1205): Property change not handled in Java land:16
I/bt-btif ( 1205): btif_storage_load_bonded_devices: 2 bonded devices found
D/bt-btif ( 1205): in, bd addr:00:f4:6f:30:e0:6c, prop type:1, len:249
D/bt-btif ( 1205): in, bd addr:00:f4:6f:30:e0:6c, prop type:10, len:249
,D/bt-btif ( 1205): in, bd addr:00:f4:6f:30:e0:6c, prop type:4, len:4
D/bt-btif ( 1205): in, bd addr:00:f4:6f:30:e0:6c, prop type:5, len:4
D/bt-btif ( 1205): in, bd addr:00:f4:6f:30:e0:6c, prop type:3, len:512
,I/bt-btif ( 1205): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 1205): devicePropertyChangedCallback: bdDevice: 00:F4:6F:30:E0:6C, value is empty for type: 10
I/LGRemoteDevicePropertySetting( 1205): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1205): [BTUI] Get BRCM HeadsetService
D/bt-btif ( 1205): in, bd addr:38:94:96:b5:06:dc, prop type:1, len:249
D/bt-btif ( 1205): in, bd addr:38:94:96:b5:06:dc, prop type:10, len:249
D/bt-btif ( 1205): in, bd addr:38:94:96:b5:06:dc, prop type:4, len:4
D/bt-btif ( 1205): in, bd addr:38:94:96:b5:06:dc, prop type:5, len:4
D/bt-btif ( 1205): in, bd addr:38:94:96:b5:06:dc, prop type:3, len:512
I/bt-btif ( 1205): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 1205): devicePropertyChangedCallback: bdDevice: 38:94:96:B5:06:DC, value is empty for type: 10
I/LGRemoteDevicePropertySetting( 1205): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1205): [BTUI] Get BRCM HeadsetService
D/bt-btif ( 1205): btif_enable_bluetooth_evt: status 0, local bd [34:fc:ef:9d:93:0b]
I/bt-btif ( 1205): HC lib lpm enable=1 return 0
E/bt_hwcfg( 1205): hw_sco_config...
I/bt-btif ( 1205): BTA_BrcmInit
E/bt_hwcfg( 1205): SCO PCM configure {0, 4, 0, 0, 0}
E/bt-gki  ( 1205): ### ERROR: incorrect Process context BTIF called function btu_start_timer() ###
,D/IOP_DB_BT( 1205): db_open: file /etc/bluetooth/iop_bt.db
D/IOP_DB_BT( 1205): db_open: db_open : handle 1623239212l, read 7547 bytes onto local cache
,D/IOP_DB_BT( 1205): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 1205): db_query: result 1
I/        ( 1205): iop_db_open: iop_db_open status 0
D/bt-btif ( 1205): btsock initializing...
D/bt-btif ( 1205): in initialized:1
D/bt-btif ( 1205): ts[7].used:1
D/bt-btif ( 1205): ts[6].used:0
D/bt-btif ( 1205): alloc_thread_slot ret:6
D/bt-btif ( 1205): h:6, cmd_fdr:87, cmd_fdw:88
D/bt-btif ( 1205): h:6, thread id:1626396136
I/bt-btif ( 1205): BTA_JvEnable
D/bt-btif ( 1205): btsock successfully initialized
D/bt-btif ( 1205): jv_dm_cback: event:0, slot id:0
D/bt-btif ( 1205): unhandled event:0, slot id:0
D/bt-btif ( 1205): jni_initialized = 1, btpan_cb.enabled:0
D/bt-btif ( 1205): Enabling PAN....
D/bt-btif ( 1205): local_role:3
D/bt-btif ( 1205): btpan_role:0x3
I/bte_conf( 1205): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bt-btif ( 1205): bta_pan_co_init
D/bt-sdp  ( 1205): SDP_CreateRecord ok, num_records:9
I/bt-btif ( 1205): Adding UUID=0x1116 into EIR
D/bt-btif ( 1205): BTA is generating EIR
I/bt-btif ( 1205): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04051440
I/bt-btif ( 1205): Adding UUID=0x1115 into EIR
D/bt-btif ( 1205): BTA is generating EIR
I/bt-btif ( 1205): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1205): Adding UUID=0x1116 into EIR
D/bt-btif ( 1205): BTA is generating EIR
I/bt-btif ( 1205): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1205): Removing UUID=0x1117 from EIR
D/bt-btif ( 1205): BTA is generating EIR
I/bt-btif ( 1205): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1205): Adding UUID=0x1115 into EIR
D/bt-btif ( 1205): BTA is generating EIR
,I/bt-btif ( 1205): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1205): HC lpm_result_cb 1
I/bte_conf( 1205): [1] primary_record=1 vendor_id=0x00C4 vendor_id_source=0x0001 product_id=0x13A1 version=0x1000
I/bte_conf( 1205): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bt-btif ( 1205): bta_dm_sm_execute event:0x31
D/bt-sdp  ( 1205): SDP_CreateRecord ok, num_records:10
I/bt-btif ( 1205): Adding UUID=0x1200 into EIR
D/bt-btif ( 1205): BTA is generating EIR
I/bt-btif ( 1205): bta_dm_eir_update_uuid UUID bit mask=0x00000084 04071440
I/bt-btif ( 1205): bte did registered::handle: 0x10009, bta status: 0 (0==OK)
I/bte_conf( 1205): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,D/bt-btif ( 1205): btif_dm_load_local_oob prop_oob = 3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/bt-btif ( 1205): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothServiceJni( 1205): adapter_state_change_callback: Status is: 1
D/bt-btif ( 1205): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/bt-btif ( 1205): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
D/bt-btif ( 1205): btif_av_state_idle_handler devicemode: 0
D/bt-btif ( 1205): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
D/bt-btif ( 1205): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 1205): btif_fts_upstreams_evt: event=BTA_FTS_ENABLE_EVT
D/BluetoothAdapterState( 1205): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
I/bt-btif ( 1205): File Transfer: Enable Complete
I/bt-btif ( 1205): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 1205): operation_cmpl_callback(L192):  oper:3 status:0
D/BluetoothAdapterProperties( 1205): ScanMode =  20
I/BluetoothFTPService( 1205): onFtpServerEnabled: /storage
D/bt-btif ( 1205): btif_sc_upstreams_evt: event=BTA_SC_ENABLE_EVT
D/bt-btif ( 1205): btif_hh_upstreams_evt: event=BTA_HH_ENABLE_EVT
D/bt-btif ( 1205): btif_hh_upstreams_evt: BTA_HH_ENABLE_EVT: status =0
D/bt-btif ( 1205): btif_hh_upstreams_evt--Loading added devices
D/bt-btif ( 1205): Remote device:00:f4:6f:30:e0:6c, size:18
D/bt-btif ( 1205): Remote device:f8:95:c7:87:3c:51, size:18
D/bt-btif ( 1205): Remote device:e0:db:10:1f:c9:5e, size:18
D/bt-btif ( 1205): Remote device:b0:c5:59:3f:75:69, size:18
D/bt-btif ( 1205): Remote device:14:b4:84:21:3b:49, size:18
D/bt-btif ( 1205): Remote device:80:01:84:8a:b3:68, size:18
D/bt-btif ( 1205): Remote device:58:3f:54:73:64:c0, size:18
D/bt-btif ( 1205): Remote device:10:d3:8a:fb:85:d4, size:18
D/bt-btif ( 1205): Remote device:b4:ce:f6:ab:a4:6a, size:18
D/bt-btif ( 1205): Remote device:08:ec:a9:50:75:41, size:18
D/bt-btif ( 1205): Remote device:f8:cf:c5:d9:e5:61, size:18
D/bt-btif ( 1205): Remote device:08:ec:a9:50:76:27, size:18
D/bt-btif ( 1205): Remote device:7c:f9:0e:51:18:22, size:18
D/bt-btif ( 1205): Remote device:44:80:eb:7b:5a:05, size:18
D/bt-btif ( 1205): Remote device:50:2e:6c:ac:21:50, size:18
D/bt-btif ( 1205): Remote device:7c:f9:0e:37:96:ab, size:18
D/bt-btif ( 1205): Remote device:f4:f1:e1:5c:3b:e2, size:18
D/bt-btif ( 1205): Remote device:34:fc:ef:11:ae:67, size:18
D/bt-btif ( 1205): Remote device:f8:95:c7:87:85:54, size:18
D/bt-btif ( 1205): Remote device:7c:f9:0e:34:8a:a0, size:18
D/bt-btif ( 1205): Remote device:e0:db:10:14:e2:c0, size:18
D/bt-btif ( 1205): Remote device:34:fc:ef:11:b1:66, size:18
D/bt-btif ( 1205): Remote device:90:e7:c4:f6:69:77, size:18
D/bt-btif ( 1205): Remote device:90:e7:c4:3c:62:6a, size:18
D/bt-btif ( 1205): Remote device:58:2a:f7:ed:96:be, size:18
D/bt-btif ( 1205): Remote device:38:94:96:b5:06:dc, size:18
D/bt-btif ( 1205): Remote device:, size:18
E/bt-btif ( 1205): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
D/bt-btif ( 1205): BTA_PAN_ENABLE_EVT
D/bt-btif ( 1205): bta_pan_role:0x5
D/BluetoothPanServiceJni( 1205): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/BluetoothAdapterProperties( 1205): State =  11
D/BluetoothAdapterProperties( 1205): mDiscoverableTimeout =  120
I/bt-btif ( 1205): btif_set_adapter_property type: 7, len 4, 0x428c4d48
I/bt-btif ( 1205): set property scan mode : 1
I/bt-btif ( 1205): bta_dm_sm_execute event:0x3
I/bt-btif ( 1205): bta_dm_sm_execute event:0x3
I/bt-btif ( 1205): btif_set_adapter_property type: 9, len 4, 0x428c4da0
I/bt-btif ( 1205): btif_set_adapter_property type: 9
I/bt-btif ( 1205): type: 7, len 4, 0x6063b07e
D/bt-btif ( 1205): in, bd addr:, prop type:7, len:4
I/bt-btif ( 1205): btif_in_storage_request_copy_cb
I/bt-btif ( 1205): btif_in_storage_request_copy_cb
I/bt-btif ( 1205): execute storage request event : 2
I/bt-btif ( 1205): type: 9, len 4, 0x6063b0ca
D/bt-btif ( 1205): in, bd addr:, prop type:9, ,len:4
I/bt-btif ( 1205): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterState( 1205): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 1205): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  964): Message: 60
V/BluetoothAdapterService( 1205): startPbapService
D/BluetoothManagerService(  964): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  964): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothPan(  964): onBluetoothStateChange(on) call bindService
D/BluetoothHeadset( 1449): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1449): onBluetoothStateChange: up=true
D/BluetoothA2dp(  964): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1449): onBluetoothStateChange: up=true
D/BluetoothHeadset(  964): onBluetoothStateChange: up=true
D/BluetoothManagerService(  964): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
,D/BluetoothManagerService(  964): Bluetooth State Change Intent: 11 -> 12
,I/BluetoothAdapterState( 1205): Entering On State
D/BluetoothManagerService(  964): Message: 40
,D/BluetoothManagerService(  964): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,W/ContextImpl(  964): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:192 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:510 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1164 
D/LGBluetoothAPIService( 1154): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothServiceAdapter( 1205): [BTUI] OnState
D/LGBluetoothAPIService( 1154): Message: 1
D/LGBluetoothAPIService( 1154): MESSAGE_BOOT_COMPLETED
D/LGBluetoothServiceAdapter( 1205): [BTUI]         global_name: Thali Test's G2
D/LGBluetoothServiceAdapter( 1205): [BTUI]         local_name: Thali Test's G2
D/bt_h4   ( 1205): vendor lib postload completed
I/bt-btif ( 1205): HC postload_cb 0
D/BluetoothAdapterService(1116062656)( 1205): Get Bonded Devices being called
D/BluetoothAdapterService(1116062656)( 1205): Quiet mode Enabled = false
D/BluetoothAdapterService(1116062656)( 1205): Initiate auto connection on BT on...
D/BluetoothAdapterService( 1205): [BTUI] autoConnect() : not allowed
I/LGBluetoothAPIService( 1154): [BTUI] LGBluetoothAPIService Binding Success
D/BluetoothAdapterService( 1205): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4285c3c0
V/BluetoothPbapService( 1205): Pbap Service onCreate
V/BluetoothPbapService( 1205): Starting PBAP service
D/LGBluetoothPbapAdapter( 1205): [BTUI] getInstance : create
V/BluetoothPbapService( 1205): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1205): state: 12
D/BluetoothMapService( 1205): onReceive
D/BluetoothMapService( 1205): STATE_ON
D/LGBluetoothAPIServer( 1205): [BTUI] onCreate()
D/LGBluetoothAPIServer( 1205): [BTUI] onBind()
V/BluetoothPbapService( 1205): Handler(): got msg=1
D/LGBluetoothAPIService( 1154): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1154): Message: 100
D/LGBluetoothAPIService( 1154): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothPbapService( 1205): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 1205): Pbap Service initSocket
V/BluetoothMapService( 1205): Handler(): got msg=1
D/BluetoothMapService( 1205): Map Service startRfcommSocketListener
D/BluetoothMapService( 1205): Map Service initSocket
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 1205): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1205): SOCK FLAG = 1 ***********************
D/bt-btif ( 1205): btsock_rfc_listen, service_name:OBEX Phonebook Access Server
D/bt-btif ( 1205): BTA_JvCreateRecordByUser:OBEX Phonebook Access Server
I/bt-btif ( 1205): BTA_JvCreateRecordByUser
D/bt-btif ( 1205): jv_dm_cback: event:11, slot id:1
D/bt-btif ( 1205): name:OBEX Phonebook Access Server, scn:19
D/bt-btif ( 1205): add_pbap_sdd:scn 19, service name OBEX Phonebook Access Server
D/bt-sdp  ( 1205): SDP_CreateRecord ok, num_records:11
I/bt-btif ( 1205): Adding UUID=0x112F into EIR
D/bt-btif ( 1205): BTA is generating EIR
I/bt-btif ( 1205): bta_dm_eir_update_uuid UUID bit mask=0x00000094 04071440
D/bt-btif ( 1205): PBS:  SDP Registered (handle 0x0001000a)
I/bt-btif ( 1205): BTA_JvRfcommStartServer
D/bt-btif ( 1205): bta_jv_rfcomm_start_server: sec id in use:0, rfc_cb in use:0
D/bt-btif ( 1205): bta_jv_alloc_rfc_cb port_handle:6 handle:0x81
D/LGBluetoothServiceAdapter( 1205): [BTUI] createSocketChannel FD=90 mFd=0
V/BluetoothPbapService( 1205): Succeed to create listening socket 
,V/BluetoothPbapService( 1205): Accepting socket connection...
,W/BluetoothAdapter( 1205): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1205): SOCK FLAG = 1 ***********************
D/bt-btif ( 1205): btsock_rfc_listen, service_name:MAP SMS/MMS
D/bt-btif ( 1205): BTA_JvCreateRecordByUser:MAP SMS/MMS
I/bt-btif ( 1205): BTA_JvCreateRecordByUser
D/bt-btif ( 1205): jv_dm_cback: event:11, slot id:2
D/bt-btif ( 1205): name:MAP SMS/MMS, scn:6
D/bt-btif ( 1205): add_maps_sdd:scn 6, service name MAP SMS/MMS
D/bt-sdp  ( 1205): SDP_CreateRecord ok, num_records:12
I/bt-btif ( 1205): Adding UUID=0x1132 into EIR
D/bt-btif ( 1205): BTA is generating EIR
I/bt-btif ( 1205): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04071440
D/bt-btif ( 1205): MAPSS:  SDP Registered (handle 0x0001000b)
I/bt-btif ( 1205): BTA_JvRfcommStartServer
D/bt-btif ( 1205): bta_jv_rfcomm_start_server: sec id in use:1, rfc_cb in use:1
,D/bt-btif ( 1205): bta_jv_alloc_rfc_cb port_handle:7 handle:0x82
D/LGBluetoothServiceAdapter( 1205): [BTUI] createSocketChannel FD=92 mFd=90
V/BluetoothMapService( 1205): Succeed to create listening socket 
,D/BluetoothMapService( 1205): Accepting socket connection...
,W/ContextImpl( 2539): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:156 com.android.settings.bluetooth.DockEventReceiver.onReceive:123 
V/BluetoothPbapReceiver( 1205): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1205): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1205): ***********state = 12
,D/LocalBluetoothProfileManager( 2539): Adding local A2DP profile
,D/BluetoothManagerService(  964): Message: 30
,D/LocalBluetoothProfileManager( 2539): Adding local HEADSET profile
,D/BluetoothManagerService(  964): Message: 30
,D/BluetoothManagerService(  964): Message: 30
W/ContextImpl( 2539): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1207 
W/ContextImpl( 2539): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1204 
,D/BluetoothManagerService(  964): Message: 30
W/ContextImpl( 2539): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1210 
W/ContextImpl( 2539): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1213 
,D/dalvikvm(  964): GC_EXPLICIT freed 22869K, 49% free 29007K/56760K, paused 2ms+7ms, total 124ms
,D/LocalBluetoothProfileManager( 2539): Adding local MAP profile
,D/BluetoothMap( 2539): Create BluetoothMap proxy object
,D/BluetoothManagerService(  964): Message: 30
,D/BluetoothManagerService(  964): Message: 30
W/ContextImpl( 2539): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1219 
,V/BluetoothPbapService( 1205): Pbap Service onBind
,D/LocalBluetoothProfileManager( 2539): LocalBluetoothProfileManager construction complete
,D/LGBluetoothUserBindClient( 2539): [BTUI] initUserBindClient
W/ContextImpl( 2539): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:72 
,W/ContextImpl( 2539): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 2539): finishStartingService: stopping service
D/BluetoothA2dp( 2539): Proxy object connected
D/A2dpProfile( 2539): Bluetooth service connected
D/BluetoothHeadset( 2539): Proxy object connected
D/HeadsetProfile( 2539): Bluetooth service connected
D/BluetoothInputDevice( 2539): Proxy object connected
D/HidProfile( 2539): Bluetooth service connected
D/BluetoothPan( 2539): BluetoothPAN Proxy object connected
D/PanProfile( 2539): Bluetooth service connected
D/BluetoothMap( 2539): Proxy object connected
D/MapProfile( 2539): Bluetooth service connected
D/BluetoothMap( 2539): getConnectedDevices()
V/BluetoothMapService( 1205): getConnectedDevices()
D/BluetoothPbap( 2539): Proxy object connected
D/PbapServerProfile( 2539): Bluetooth service connected
D/LGBluetoothUserBindClient( 2539): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 2539): onReceive
D/LGBluetoothFeatureConfig( 2539): isPrivacyLogsEnabled : true
E/LGBluetoothUtils( 2539): [BTUI] FileNotFoundException: readPropertyjava.io.FileNotFoundException: /data/misc/bluedroid/bluetooth_property.conf: open failed: ENOENT (No such file or directory)
D/LGBluetoothResetSettingReceiver( 2539): return without doing reset settings.
V/BluetoothOppReceiver( 1205): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 1205): [BTUI] startOppService()
V/BluetoothOppManager( 1205): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 1205): isPrivacyLogsEnabled : true
V/BtOppService( 1205): onCreate
,D/LGBluetoothOppAdapter( 1205): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,V/BluetoothOppNotification( 1205): send message
,V/BtOppService( 1205): Starting RfcommListener
,D/BluetoothOppPreference( 1205): Dumping Names:  
D/BluetoothOppPreference( 1205): {}
D/BluetoothOppPreference( 1205): Dumping Channels:  
,D/BluetoothOppPreference( 1205): {}
,V/BtOppService( 1205): onStartCommand
,V/BtOppService( 1205): Deleted complete outbound shares, number =  0
V/BtOppService( 1205): pendingUpdate is true keepUpdateThread is false sListenStarted is true
V/BluetoothOppProvider( 1205): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,V/BluetoothOppNotification( 1205): new notify threadi!
,V/BtOppService( 1205): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 1205): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BluetoothOppNotification( 1205): send delay message
,V/BtOppService( 1205): start RfcommListener
,V/BluetoothOppProvider( 1205): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1205): created cursor android.database.sqlite.SQLiteCursor@428f6618 on behalf of 
,V/BluetoothOppProvider( 1205): created cursor android.database.sqlite.SQLiteCursor@428f80f8 on behalf of 
V/BtOppService( 1205): RfcommListener started
V/BtOppService( 1205): ContentObserver received notification
,V/BtOppService( 1205): ContentObserver received notification
,V/BtOppRfcommListener( 1205): Starting RFCOMM listener....
V/BluetoothOppNotification( 1205): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 1205): created cursor android.database.sqlite.SQLiteCursor@428f7760 on behalf of 
,D/BluetoothManagerService(  964): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 1205): getBluetoothService() called with no BluetoothManagerCallback
D/AuthorizationBluetoothService( 1526): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1526): Proximity feature is not enabled.
,E/BluetoothServiceJni( 1205): SOCK FLAG = 0 ***********************
D/bt-btif ( 1205): btsock_rfc_listen, service_name:OBEX Object Push
D/bt-btif ( 1205): BTA_JvCreateRecordByUser:OBEX Object Push
I/bt-btif ( 1205): BTA_JvCreateRecordByUser
D/bt-btif ( 1205): jv_dm_cback: event:11, slot id:3
D/bt-btif ( 1205): name:OBEX Object Push, scn:12
D/bt-btif ( 1205): scn 12, service name OBEX Object Push
D/bt-sdp  ( 1205): SDP_CreateRecord ok, num_records:13
I/bt-btif ( 1205): Adding UUID=0x1105 into EIR
D/bt-btif ( 1205): BTA is generating EIR
I/bt-btif ( 1205): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04071460
I/bt-btif ( 1205): BTA_JvRfcommStartServer
D/bt-btif ( 1205): bta_jv_rfcomm_start_server: sec id in use:2, rfc_cb in use:2
D/bt-btif ( 1205): bta_jv_alloc_rfc_cb port_handle:8 handle:0x83
,V/BtOppService( 1205): pendingUpdate is true keepUpdateThread is false sListenStarted is true
D/LGBluetoothServiceAdapter( 1205): [BTUI] createSocketChannel FD=97 mFd=92
V/BluetoothOppProvider( 1205): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BtOppRfcommListener( 1205): Started RFCOMM listener....
I/BtOppRfcommListener( 1205): Accept thread started.
,V/BtOppRfcommListener( 1205): Accepting connection...
,V/BluetoothOppProvider( 1205): created cursor android.database.sqlite.SQLiteCursor@428fb7c0 on behalf of 
,V/BluetoothOppProvider( 1205): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppNotification( 1205): update too frequent, put in queue
V/BtOppService( 1205): pendingUpdate is false keepUpdateThread is false sListenStarted is true
,V/BluetoothOppProvider( 1205): created cursor android.database.sqlite.SQLiteCursor@428fd7b0 on behalf of 
,V/BluetoothOppNotification( 1205): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 1205): outbound notification was removed.
,V/BluetoothOppProvider( 1205): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1205): created cursor android.database.sqlite.SQLiteCursor@428ff808 on behalf of 
,V/BluetoothOppNotification( 1205): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 1205): inbound notification was removed.
,V/BluetoothOppProvider( 1205): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1205): created cursor android.database.sqlite.SQLiteCursor@42900ef0 on behalf of 
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 4233): EAPOL: disable timer tick
D/wpa_supplicant( 4233): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4233): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 4233): EAPOL: disable timer tick
D/wpa_supplicant( 4233): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4233): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,E/ThermalEngine(  293): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,V/BluetoothOppNotification( 1205): new notify threadi!
,V/BluetoothOppNotification( 1205): send delay message
,V/BluetoothOppProvider( 1205): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1205): created cursor android.database.sqlite.SQLiteCursor@42902980 on behalf of 
,V/BluetoothOppNotification( 1205): mUpdateCompleteNotification = true
,V/BluetoothOppProvider( 1205): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1205): created cursor android.database.sqlite.SQLiteCursor@429045b8 on behalf of 
,V/BluetoothOppNotification( 1205): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 1205): outbound notification was removed.
,V/BluetoothOppProvider( 1205): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1205): created cursor android.database.sqlite.SQLiteCursor@42906148 on behalf of 
,V/BluetoothOppNotification( 1205): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 1205): inbound notification was removed.
,V/BluetoothOppProvider( 1205): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1205): created cursor android.database.sqlite.SQLiteCursor@429076f0 on behalf of 
,V/AudioFlinger(  276): releaseWakeLock_l() AudioOut_2
,V/AudioFlinger(  276): thread 0xb2731008 type 0 TID 738 going to sleep
,V/AudioFlinger(  276): releaseWakeLock_l() AudioOut_3
,V/AudioFlinger(  276): thread 0xb25c6008 type 0 TID 1001 going to sleep
,D/wpa_supplicant( 4233): nl80211: Event message available
D/wpa_supplicant( 4233): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
D/wpa_supplicant( 4233): wlan0: nl80211: New scan results available
D/wpa_supplicant( 4233): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 4233): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 4233): nl80211: Survey data missing
D/wpa_supplicant( 4233): wlan0: BSS: Start scan result update 1
D/wpa_supplicant( 4233): wlan0: BSS: Add new id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4233): wlan0: BSS: Add new id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4233): wlan0: BSS: Add new id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4233): wlan0: BSS: Add new id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4233): wlan0: BSS: Add new id 4 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698'
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4233): wlan0: BSS: Add new id 5 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4233): wlan0: BSS: Add new id 6 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025'
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4233): wlan0: BSS: Add new id 7 BSSID 44:e9:dd:10:c0:ab SSID 'FunBox2-C0AB'
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4233): wlan0: BSS: Add new id 8 BSSID 44:e9:dd:10:c0:ad SSID 'Darmowe_Orange_WiFi'
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4233): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 4233): wlan0: New scan results available
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 4233): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4233): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4233): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 4233): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 4233): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 4233): WPS: AP 44:e9:dd:10:c0:ab type 0 added
D/wpa_supplicant( 4233): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0,
D/wpa_supplicant( 4233): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4233): WPS: AP[2] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4233): WPS: AP[3] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4233): WPS: AP[4] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4233): WPS: AP[5] 44:e9:dd:10:c0:ab type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4233): wlan0: Selecting BSS from priority group 1,
D/wpa_supplicant( 4233): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-50 wps
D/wpa_supplicant( 4233): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 4233): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-58 wps
,D/wpa_supplicant( 4233): wlan0:    selected based on RSN IE
D/wpa_supplicant( 4233): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 4233): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4233): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4233): wlan0: [MDM] lg_mdm_auto_connect_policy 0
,D/wpa_supplicant( 4233): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4233): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4233): wlan0: [MDM] lg mdm allow/disallow auto connect is not set ,
D/wpa_supplicant( 4233): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8db75a8  current_ssid=0x0
,D/wpa_supplicant( 4233): wlan0: Selected network is configured to use SIM (sim=1 aka=1) - initialize PCSC,
E/wpa_supplicant( 4233): USIM:  scard_init function
,D/wpa_supplicant( 4233): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING,
D/wpa_supplicant( 4233): wpa_supplicant_check_mdm_ac_policy policy: 0,
D/wpa_supplicant( 4233): wlan0: [MDM] lg_mdm_auto_connect_policy 0,
D/wpa_supplicant( 4233): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
,D/wpa_supplicant( 4233): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
D/wpa_supplicant( 4233): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 4233): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00,
,D/wpa_supplicant( 4233): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 4233): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4233): TDLS: TDLS is allowed in the target BSS,
I/wpa_supplicant( 4233): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
D/wpa_supplicant( 4233): wlan0: Cancelling scan request
D/wpa_supplicant( 4233): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4233): wlan0: WPA: clearing own WPA/RSN IE
,D/wpa_supplicant( 4233): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 4233): RSN: PMKSA cache search - network_ctx=0xb8db75a8 try_opportunistic=0
D/wpa_supplicant( 4233): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4233): RSN: No PMKSA cache entry found
D/wpa_supplicant( 4233): wlan0: RSN: using IEEE 802.11i/D9.0
,D/wpa_supplicant( 4233): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 4233): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 4233): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4233): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 4233): wlan0: WPA: using PTK CCMP
,D/wpa_supplicant( 4233): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 4233): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
,D/wpa_supplicant( 4233): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 4233): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
D/wpa_supplicant( 4233): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 4233): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4233): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 4233): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 4233): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4233): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 4233): nl80211: Unsubscribe mgmt frames handle 0xb8db6590 (mode change)
D/wpa_supplicant( 4233): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8db6590
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8db6590
,D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8db6590
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8db6590
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=2): 04 0c
,D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8db6590
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8db6590
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8db6590,
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8db6590
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8db6590
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=1): 06
,D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8db6590
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4233): nl80211: Register frame type=0xd0 nl_handle=0xb8db6590
D/wpa_supplicant( 4233): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 4233): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 4233):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4233):   * freq=2412
,D/wpa_supplicant( 4233):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 4233):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4233):   * Auth Type 0
D/wpa_supplicant( 4233):   * WPA Versions 0x2
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 1 c0:ff:d4:d3:aa:48]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 2 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 38:f8:89:11:e9:11]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 64:7c:34:12:7f:81]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 a0:c5:62:7a:49:97]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 9e:93:4e:3e:ba:c5]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 44:e9:dd:10:c0:ab]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 44:e9:dd:10:c0:ad]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
W/WifiMonitor(  964): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=],
D/WifiStateMachine(  964): handleMessage: E msg.what=147461
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  964): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 4233): nl80211: Connect request send successfully
D/wpa_supplicant( 4233): wlan0: Setting authentication timeout: 10 sec 0 usec,
D/wpa_supplicant( 4233): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4233): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4233): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4233): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4233): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4233): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4233): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 4233): EAPOL: Supplicant port status: Unauthorized,
D/wpa_supplicant( 4233): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4233): RSN: Ignored PMKID candidate without preauth flag
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 4233): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 4233): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 4233): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4233): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
,D/WifiStateMachine(  964): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
,D/wpa_supplicant( 4233): nl80211: Event message available
D/wpa_supplicant( 4233): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4233): nl80211: Connect event
D/wpa_supplicant( 4233): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4233): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4233): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 4233): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 4233): wlan0: Association info event
D/wpa_supplicant( 4233): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 4233): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 4233): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4233): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 4233): wlan0: freq=2412 MHz
D/wpa_supplicant( 4233): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4233): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4233): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4233): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4233): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4233): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 4233): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 4233): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 4233): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4233): scard is not null..
D/wpa_supplicant( 4233): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 4233): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 4233): TDLS: Remove peers on association
D/wpa_supplicant( 4233): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4233): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4233): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4233): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4233): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4233): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4233): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4233): EAPOL: Supplicant port status: Unauthorized
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 4233): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4233): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4233): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4233): EAPOL: enable timer tick
D/wpa_supplicant( 4233): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4233): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4233): wlan0: Cancelling scan request
D/wpa_supplicant( 4233): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
,D/wpa_supplicant( 4233): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4233): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/WifiMonitor(  964): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
D/wpa_supplicant( 4233): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4233): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4233): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
W/WifiMonitor(  964): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 4233): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4233): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4233): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4233): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=CONNECTING,
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
,D/wpa_supplicant( 4233): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4233): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 49 02 d9 ca 52 e4 10 db 66 66 84 ee 47 d3 8e ...
D/wpa_supplicant( 4233): wlan0: Setting authentication timeout: 10 sec 0 usec
,D/wpa_supplicant( 4233): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 4233): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 4233): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 4233): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 4233):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 4233):   key_nonce - hexdump(len=32): 49 02 d9 ca 52 e4 10 db 66 66 84 ee 47 d3 8e 5f e1 a4 b6 30 a0 13 bf 8b e3 3e 94 06 23 6b 4e df
D/wpa_supplicant( 4233):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4233):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4233):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4233):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4233): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 49 02 d9 ca 52 e4 10 db 66 66 84 ee 47 d3 8e ...
D/wpa_supplicant( 4233): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4233): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 4233): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 4233): Get randomness: len=32 entropy=10
,D/wpa_supplicant( 4233): WPA: Renewed SNonce - hexdump(len=32): 0f 1e db 73 f8 ae 78 94 56 ed 5f 33 c8 a2 d6 4b ce 46 e9 10 4d 86 fd a5 f4 d0 f4 b6 91 0c 80 3f
D/wpa_supplicant( 4233): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4233): WPA: Nonce1 - hexdump(len=32): 0f 1e db 73 f8 ae 78 94 56 ed 5f 33 c8 a2 d6 4b ce 46 e9 10 4d 86 fd a5 f4 d0 f4 b6 91 0c 80 3f
D/wpa_supplicant( 4233): WPA: Nonce2 - hexdump(len=32): 49 02 d9 ca 52 e4 10 db 66 66 84 ee 47 d3 8e 5f e1 a4 b6 30 a0 13 bf 8b e3 3e 94 06 23 6b 4e df
D/wpa_supplicant( 4233): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 4233): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 4233): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4233): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
,D/wpa_supplicant( 4233): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 4233): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4233): WPA: Derived Key MIC - hexdump(len=16): 80 d5 b0 ce 5e 27 19 b0 65 fd 69 a4 90 a2 43 e3
D/wpa_supplicant( 4233): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 0f 1e db 73 f8 ae 78 94 56 ed 5f 33 c8 a2 d6 ...
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
D/wpa_supplicant( 4233): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4233): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 49 02 d9 ca 52 e4 10 db 66 66 84 ee 47 d3 8e ...
D/wpa_supplicant( 4233): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 4233): wlan0:   EAPOL-Key type=2
,D/wpa_supplicant( 4233): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 4233): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 4233):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 4233):   key_nonce - hexdump(len=32): 49 02 d9 ca 52 e4 10 db 66 66 84 ee 47 d3 8e 5f e1 a4 b6 30 a0 13 bf 8b e3 3e 94 06 23 6b 4e df
D/wpa_supplicant( 4233):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4233):   key_rsc - hexdump(len=8): 7f 01 00 00 00 00 00 00
D/wpa_supplicant( 4233):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4233):   key_mic - hexdump(len=16): 52 b6 6a b3 b4 0c c8 92 c7 f5 80 eb 69 52 dd 0d
D/wpa_supplicant( 4233): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 49 02 d9 ca 52 e4 10 db 66 66 84 ee 47 d3 8e ...
D/wpa_supplicant( 4233): RSN: encrypted key data - hexdump(len=56): 59 10 9a 6b fb 64 ea 50 01 97 01 d9 3a 12 66 64 cc c6 c6 b3 36 2c 11 e3 a4 7b f0 c0 50 8e 73 d7 ...
D/wpa_supplicant( 4233): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 4233): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4233): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 4233): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 01 00 9f 9f ...
D/wpa_supplicant( 4233): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4233): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 4233): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 4233): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4233): WPA: Derived Key MIC - hexdump(len=16): fd 62 21 1f 51 5b 8f 6d 6d b1 ba 0c 3d a8 a4 10
D/wpa_supplicant( 4233): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 4233): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 4233): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb8db6c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 4233):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4233): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4233): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4233): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
,D/wpa_supplicant( 4233): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4233): wlan0: WPA: Installing GTK to the driver (keyidx=1 tx=0 len=16)
D/wpa_supplicant( 4233): WPA: RSC - hexdump(len=6): 7f 01 00 00 00 00
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 4233): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6f6c03a key_idx=1 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 4233):    broadcast key
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  964): processMsg: ConnectModeState
,D/WifiStateMachine(  964): handleMessage: X
I/wpa_supplicant( 4233): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4233): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 4233): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4233): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiMonitor(  964): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4233): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4233): netlink: Operstate: linkmode=-1, operstate=6
W/WifiMonitor(  964): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
D/WifiStateMachine(  964): processMsg: DisconnectedState
D/wpa_supplicant( 4233): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4233): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4233): EAPOL: External notification - portValid=1
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/wpa_supplicant( 4233): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4233): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4233): EAPOL: SUPP_BE entering state SUCCESS
D/WifiStateMachine(  964): Network connection established
,D/WifiNative-wlan0(  964): doString: STATUS
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 4233): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4233): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4233): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4233): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4233): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4233): EAPOL authentication completed successfully
D/wpa_supplicant( 4233): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4233): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4233): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 4233): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 4233): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  964): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  964):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  964): ssid=NG700
D/WifiNative-wlan0(  964): id=0
D/WifiNative-wlan0(  964): mode=station
D/WifiNative-wlan0(  964): pairwise_cipher=CCMP
D/WifiNative-wlan0(  964): group_cipher=CCMP
D/WifiNative-wlan0(  964): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  964): wpa_state=COMPLETED
D/WifiNative-wlan0(  964): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  964): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  964): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServiceExtension(  964): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  964): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
,E/Parcel  (  605): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  964): transitionTo: destState=ObtainingIpState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  964): invokeExitMethods: DisconnectedState
E/Parcel  (  605): Reading a NULL string not supported here.
,E/Parcel  (  605): Reading a NULL string not supported here.
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,D/WifiStateMachine(  964): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  964): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine(  964): invokeEnterMethods: ObtainingIpState
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiService(  964): New client listening to asynchronous messages
,D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/DhcpStateMachine(  964): StoppedState
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/DhcpStateMachine(  964): StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): ObtainingIpState{ when=-38ms what=147462 obj=android.net.wifi.StateChangeResult@431b4b50 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  964): WaitBeforeStartState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147462
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-37ms what=147462 obj=android.net.wifi.StateChangeResult@430bc888 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=147459
,D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-36ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ObtainingIpState
,D/WifiStateMachine(  964): ObtainingIpState{ when=-20ms what=131155 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4233): wlan0: Control interface command 'SIGNAL_POLL'
,I/ActivityManager(  964): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4372 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
D/wpa_supplicant( 4233): nl80211: survey data missing!
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=196612
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 4233): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/HyLog   ( 4372): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4372): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4372): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QRemote ( 4372): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
D/QRemote ( 4372): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4372): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4372): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 4372): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/QRemote ( 4372): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
D/QRemote ( 4372): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
D/QRemote ( 4372): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 4372): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/ActivityManager(  964): Killing 4047:com.google.android.partnersetup/u0a9 (adj 15): empty #17
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
D/wpa_supplicant( 4233): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 false
D/WifiNative-wlan0(  964): doBoolean: SET ps 0
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 4233): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 4233): CTRL_IFACE SET 'ps'='0'
D/wpa_supplicant( 4233): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 4233): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 4233): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  964): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 4233): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 4233): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  964):    returned null
E/WifiStateMachine(  964): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  964): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
D/DhcpStateMachine(  964): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
D/WifiStateMachine(  964): handleMessage: X
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432a5b08 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@432a5b08 target=com.android.internal.util.StateMachine$SmHandler }
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/DhcpStateMachine(  964): DHCP request on wlan0
D/LgDhcpStateMachineHelper(  964): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  964): addressUpdated: 192.168.1.121/24 on wlan0 flags 128 scope 0
D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=0 what=131212 obj=192.168.1.121/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
D/WifiStateMachine(  964): processMsg: DefaultState
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): handleMessage: X
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/DhcpStateMachine(  964): DHCP succeeded on wlan0
D/LgDhcpStateMachineHelper(  964): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  964): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  964): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.121
V/LgDhcpStateMachineHelper(  964): Add DhcpResults: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
V/DhcpStateMachine(  964): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  964): bShouldSendDhcpAction Result: true
D/WifiStateMachine(  964): handleMessage: E msg.what=196613
D/WifiStateMachine(  964): processMsg: ObtainingIpState
D/WifiStateMachine(  964): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  964): doBoolean: SET ps 1
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 4233): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 4233): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4233): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/DhcpStateMachine(  964): DHCP Start/Renew wake lock is released.
D/DhcpStateMachine(  964): RunningState
D/WifiNative-wlan0(  964):    returned true
D/WifiNative-wlan0(  964): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 4233): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 4233): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  964):    returned true
D/WifiStateMachine(  964): DHCP successful
D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  964): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
D/WifiStateMachine(  964): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  964): VerifyingLinkState enter
D/WifiStateMachine(  964): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
D/WifiP2pService(  964): InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  964): P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  964): handleMessage: X
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  964): send additional Connectivity Action
D/WifiStateMachine(  964): handleMessage: E msg.what=135190
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
D/WifiStateMachine(  964): processMsg: VerifyingLinkState
E/Parcel  (  605): Reading a NULL string not supported here.
D/WifiStateMachine(  964): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  964): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  964): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): CaptivePortalCheckState enter
D/WifiStateMachine(  964): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
W/WifiStateTracker(  964): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  964): 
W/WifiStateTracker(  964):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  964):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/WifiStateMachine(  964): handleMessage: X
D/libc    (  270): _dns_getaddrinfo: iptype =0
D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=0 connState=2
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  964): handleMessage: E msg.what=131092
D/WifiStateMachine(  964): processMsg: CaptivePortalCheckState
D/WifiStateMachine(  964): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
D/QcConnectivityService(  964): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): handleInetConditionChange: no active default network - ignore
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/WifiStateMachine(  964): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
D/WifiStateMachine(  964): transitionTo: destState=ConnectedState
D/WifiStateMachine(  964): handleMessage: new destination call exit/enter
D/WifiStateMachine(  964): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  964): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  964): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  964): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  964): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/KeyguardUpdateMonitor( 1140): received broadcast android.net.wifi.STATE_CHANGE
V/WfdStateTracker( 1154): handleWifiStateChangedEvent: 1
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  964): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/RemoteControlStatusBar( 1140): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/WifiOffDelayIfNotUsed(  964): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/QRemote ( 4372): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
E/ActivityThread(  964): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  964): handleConnectivityChange: preConnState=2 connState=1
V/        (  270): RouteController
I/QRemote ( 4372): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
V/        (  270): RouteController
D/QRemote ( 4372): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
I/QRemote ( 4372): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/        (  270): RouteController
V/        (  270): RouteController
I/PCSuite ( 4260): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
D/PCSuite ( 4260): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
D/QRemote ( 4372): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
V/        (  270): RouteController
D/QRemote ( 4372): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
V/        (  270): RouteController
I/QRemote ( 4372): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
I/QRemote ( 4372): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
V/        (  270): RouteController
V/        (  270): RouteController
V/        (  270): RouteController
D/libc    (  270): _dns_getaddrinfo: iptype =1
D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/QCNEA   (  605): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  605): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  605): |CAC| updateNetCfgInfo
V/QCNEA   (  605): |CAC| *********************************************
V/QCNEA   (  605): |CAC|                   Netconfig               
V/QCNEA   (  605): |CAC| *********************************************
V/QCNEA   (  605): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  605): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  605): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  605): |CAC| 	NetConfig: ip4        =192.168.1.121
V/QCNEA   (  605): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  605): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  605): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  605): |CAC| *********************************************
D/QCNEA   (  605): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  605): |CAC| net type = 1
V/QCNEA   (  605): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  605): |CAC| Received ssid= NG700
V/QCNEA   (  605): |CAC| 	ssid           =NG700
V/QCNEA   (  605): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  605): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  605): |CAC| *********************************************
D/QCNEA   (  605): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  605): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  605): |CAC| dispatchNetCfg: updating:0xb7f768dc
D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
D/libc    (  270): _dns_getaddrinfo: iptype =1
D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/libc    (  270): _dns_getaddrinfo: iptype =1
D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/wpa_supplicant( 4233): EAPOL: startWhen --> 0
,D/wpa_supplicant( 4233): EAPOL: disable timer tick
,D/GpsLocationProvider(  964): NTP server returned: 1449751062842 (Thu Dec 10 13:37:42 CET 2015) reference: 124321 certainty: 29 system time offset: -443
E/LocSvc_afw(  964): V/Entering int loc_inject_time(GpsUtcTime, int64_t, int) line 446 
E/LocSvc_eng(  964): I/===> int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int) line 1910 
,E/LocSvc_eng(  964): V/time: 1449751062842
E/LocSvc_eng(  964):   timeReference: 124321
E/LocSvc_eng(  964):   uncertainty: 29
E/LocSvc_utils_q(  964): D/msg_q_snd: Sending message with handle = 0x65F7C6F8
E/LocSvc_utils_ll(  964): D/linked_list_add: Adding to list data_obj = 0x65F7C6F8
E/LocSvc_utils_q(  964): D/msg_q_snd: Finished Sending message with handle = 0x65F7C6F8
E/LocSvc_eng(  964): V/Exiting int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int) line 1917 0
E/LocSvc_afw(  964): V/Exiting int loc_inject_time(GpsUtcTime, int64_t, int) line 452 0
E/LocSvc_utils_ll(  964): D/linked_list_remove: Removing from list
E/LocSvc_utils_q(  964): D/msg_q_rcv: Received message 0x65F7C6F8 rv = 0
E/LocSvc_eng(  964): V/time: 1449751062842
E/LocSvc_eng(  964):   timeReference: 124321
E/LocSvc_eng(  964):   uncertainty: 29
E/LocSvc_ApiV02(  964): V/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):436]: uncertainty = 29
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 56, req_id 56 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 56
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=56, len = 16
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 56, len = 16
,E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_UTC_TIME_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 45, status = 0
,E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=56 buf_len=7 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 56 size = 4
,E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 56 is a resp size = 4
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_UTC_TIME_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 56, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 56 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 56 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 56 size = 4
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 4 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_MsgTask(  964): D/MsgTask::loop() 26 listening ...
,E/LocSvc_utils_q(  964): D/msg_q_rcv: Waiting on message
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  964): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  964): handleMessage: E msg.what=131212
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
D/WifiStateMachine(  964): processMsg: SupplicantStartedState
,D/WifiStateMachine(  964): processMsg: DefaultState
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/WifiStateMachine(  964): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  964): send additional Connectivity Action
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
D/QcConnectivityService(  964): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/dalvikvm(  964): Jit: resizing JitTable from 8192 to 16384
,D/WifiStateMachine(  964): handleMessage: X
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,D/LocSvc_java(  964): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  964): ignore wifi update if we are not in OPENING or CLOSING
D/QcConnectivityService(  964): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  964):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  964): Exception while trying to add src route: java.lang.NullPointerException
,D/GpsLocationProvider(  964): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/Nat464Xlat(  964): requiresClat: netType=1, hasIPv4Address=true
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/GpsLocationProvider(  964): calling native_inject_xtra_data
,E/LocSvc_afw(  964): V/Entering int loc_xtra_inject_data(char*, int) line 858 
E/LocSvc_eng(  964): V/length: 58777
E/LocSvc_eng(  964):   data: 0x65e93008
E/LocSvc_utils_q(  964): D/msg_q_snd: Sending message with handle = 0x65E45C50
E/LocSvc_utils_ll(  964): D/linked_list_add: Adding to list data_obj = 0x65E45C50
E/LocSvc_utils_q(  964): D/msg_q_snd: Finished Sending message with handle = 0x65E45C50
E/LocSvc_utils_ll(  964): D/linked_list_remove: Removing from list
E/LocSvc_utils_q(  964): D/msg_q_rcv: Received message 0x65E45C50 rv = 0
E/LocSvc_eng(  964): V/length: 58777
E/LocSvc_eng(  964):   data: 0x65e93008
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1018]: xtra size = 58777
,E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 1/58, len = 1024, total injected = 0
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_afw(  964): V/Exiting int loc_xtra_inject_data(char*, int) line 861 0
,E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 46, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 1024
,E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 2/58, len = 1024, total injected = 1024
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 47, status = 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 2048
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 3/58, len = 1024, total injected = 2048
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 48, status = 0
,E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 3072
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 4/58, len = 1024, total injected = 3072
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 49, status = 0
,E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 4096
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 5/58, len = 1024, total injected = 4096
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 50, status = 0
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 5120
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 6/58, len = 1024, total injected = 5120
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 51, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 6144
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 7/58, len = 1024, total injected = 6144
,E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 52, status = 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
,E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 7168
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 8/58, len = 1024, total injected = 7168
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 53, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
,E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 8192
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 9/58, len = 1024, total injected = 8192
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 54, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 9216
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 10/58, len = 1024, total injected = 9216
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 55, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 10240
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 11/58, len = 1024, total injected = 10240
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 56, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 11264
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 12/58, len = 1024, total injected = 11264
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 57, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 12288
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 13/58, len = 1024, total injected = 12288
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 58, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 13312
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 14/58, len = 1024, total injected = 13312
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 59, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 14336
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 15/58, len = 1024, total injected = 14336
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 60, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 15360
,E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 16/58, len = 1024, total injected = 15360
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 61, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 16384
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 17/58, len = 1024, total injected = 16384
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 62, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 17408
,E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 18/58, len = 1024, total injected = 17408
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 63, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
,E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 18432
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 19/58, len = 1024, total injected = 18432
,E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 64, status = 0
,E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 19456
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 20/58, len = 1024, total injected = 19456
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 65, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
,E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 20480
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 21/58, len = 1024, total injected = 20480
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 66, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 21504
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 22/58, len = 1024, total injected = 21504
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 67, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 22528
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 23/58, len = 1024, total injected = 22528
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 68, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 23552
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 24/58, len = 1024, total injected = 23552
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 69, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 24576
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 25/58, len = 1024, total injected = 24576
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 70, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 25600
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 26/58, len = 1024, total injected = 25600
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 71, status = 0
,E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
,E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 26624
,E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 27/58, len = 1024, total injected = 26624
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
,E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 72, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
,E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 27648
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 28/58, len = 1024, total injected = 27648
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 73, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 28672
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 29/58, len = 1024, total injected = 28672
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 ,
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 74, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 29696
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 30/58, len = 1024, total injected = 29696
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  964): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 75, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 30720
,E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 31/58, len = 1024, total injected = 30720
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 76, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
,E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 31744
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 32/58, len = 1024, total injected = 31744
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
,E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 77, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 32768
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 33/58, len = 1024, total injected = 32768
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 78, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 33792
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 34/58, len = 1024, total injected = 33792
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 79, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 34816
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 35/58, len = 1024, total injected = 34816
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
,E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 80, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 35840
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 36/58, len = 1024, total injected = 35840
,E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 81, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 36864
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 37/58, len = 1024, total injected = 36864
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 82, status = 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 37888
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 38/58, len = 1024, total injected = 37888
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
,E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 83, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 38912
,E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 39/58, len = 1024, total injected = 38912
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 84, status = 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
,E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 39936
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 40/58, len = 1024, total injected = 39936
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 85, status = 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 40960
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 41/58, len = 1024, total injected = 40960
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 86, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 41984
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 42/58, len = 1024, total injected = 41984
,E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 87, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 43008
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 43/58, len = 1024, total injected = 43008
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 88, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 44032
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 44/58, len = 1024, total injected = 44032
,E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 89, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
,E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 45056
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 45/58, len = 1024, total injected = 45056
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 90, status = 0
,E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 46080
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 46/58, len = 1024, total injected = 46080
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 91, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 47104
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 47/58, len = 1024, total injected = 47104
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 92, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 48128
,E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 48/58, len = 1024, total injected = 48128
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 93, status = 0
,E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 49152
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 49/58, len = 1024, total injected = 49152
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 94, status = 0
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 50176
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 50/58, len = 1024, total injected = 50176
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 95, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
,E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 51200
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 51/58, len = 1024, total injected = 51200
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 96, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 52224
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 52/58, len = 1024, total injected = 52224
,E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 97, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 53248
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 53/58, len = 1024, total injected = 53248
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 98, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 54272
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 54/58, len = 1024, total injected = 54272
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 99, status = 0
,E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 55296
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 55/58, len = 1024, total injected = 55296
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 100, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 56320
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 56/58, len = 1024, total injected = 56320
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 101, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 57344
E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 57/58, len = 1024, total injected = 57344
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 102, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 58368
,E/LocSvc_ApiV02(  964): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 58/58, len = 409, total injected = 58368
E/LocSvc_api_v02(  964): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  964): V/loc_sync_select_ind:356]: client handle 0x65f0f5a0, ind_id 53, req_id 53 
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.465927 Y: -0.404144 Z: 9.760086 
E/LocSvc_api_v02(  964): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  964): V/validateRequest:1915]: reqId=53, len = 1044
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.465927 .y:-0.404144 .z:9.760086
E/LocSvc_api_v02(  964): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  964): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
E/LocSvc_api_v02(  964): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  964): V/convertQmiResponseToLocStatus:681]: result = 0, error = 103, status = 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.463425 Y: -0.413132 Z: 9.743515 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.463425 .y:-0.413132 .z:9.743515
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,E/LocSvc_api_v02(  964): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x65f0f5a0
,E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  964): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  964): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x65f0f5a0, resp id = 53, client cookie ptr = 0x65f0cb48
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:165]: received indication, handle = 0x65f0f5a0 ind_id = 53 
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  964): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  964): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  964): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  964): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  964): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 58777
E/LocSvc_MsgTask(  964): D/MsgTask::loop() 27 listening ...
,E/LocSvc_utils_q(  964): D/msg_q_rcv: Waiting on message
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4164): Test app app.js loaded
I/jxcore-log( 4164): 
,I/chromium( 4164): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Choreographer( 4164): Skipped 395 frames!  The application may be doing too much work on its main thread.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4233): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4233): nl80211: survey data missing!
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
D/WifiStateMachine(  964): handleMessage: X
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=-9ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,W/        (  964): Unable to set rtc to 1449751065: Invalid argument
,D/        (  964): Setting time of day to sec=1449751065
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): NoActiveNetworkState{ when=-1ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,I/SecureClockService( 1154): Intent.ACTION_TIME_CHANGED 
,D/QCNEA   (  605): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_SET
D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_SET, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449751065776, nextTick: 14251, mDrawingTime: 6
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449751065776, nextTick: 14256, mDrawingTime: 0
,I/MusicWidget( 2103): intentReceiver onReceive() action::android.intent.action.TIME_SET
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/MusicWidget( 2103): beingMusicWidget_4x2() result::false
I/MusicWidget( 2103): beingMusicWidget_Lock() result::false
D/WeatherService( 1870): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 13:37:45
I/MusicWidget( 2103): beingMusicWidget_Quick() result::false
D/WeatherService( 1870): 2 : requestRefreshAppWidget, isUpdateStart : false
I/MusicWidget( 2103): beingMusicWidget_4x1() result::true
I/MusicWidget( 2103): performViewUpdater handleMessage() msg.what::0
I/[LGHome]LGCalendarIcon( 1489): [LGCalendarIcon.java:188:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 10
I/MusicWidget( 2103): beingMusicWidget_4x1() result::true
I/MusicWidget( 2103): performUpdate()_4x1
D/UpdateThreadPoolManager( 1870): 2 : This is isUpdating : false
D/WeatherService( 1870): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1870): 2 : buildUpdate, appWidgetId: 1
I/NetworkStateForAutoUpdateMonitor( 3662): [onReceive] BroadcastReceiver onReceive
I/NetworkStateForAutoUpdateMonitor( 3662): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
D/WeatherReflect( 1870): 2 : Map key string is -2
I/NetworkStateForAutoUpdateMonitor( 3662): [onReceive] connect :true
I/NetworkStateForAutoUpdateMonitor( 3662): [onReceive] request level :IDLE....
I/[LGHome]LGCalendarIcon( 1489): [LGCalendarIcon.java:188:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 10
I/MusicWidget( 2103): status::mounted
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/AppUp4:CustModeStarterReceiver( 3662): onReceive
I/MusicWidget( 2103): defaultAppWidget()_4x1
I/MusicWidget( 2103): 4x1_currentTheme :: com.lge.launcher2.theme.optimus
I/MusicWidget( 2103): setDefaultViewLayoutId()_4x1
D/lim     ( 1870): 2 : time = 13:37
I/WeatherReflect( 1870): Model Name : LG-D802
D/WeatherTheme( 1870): 2 : Different view - status_min_formatted : 36 != 37
D/WeatherTheme( 1870): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1870): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1870): 2 : Fixed theme : optimus
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/AppUp4:CustFacade( 3662): Context : android.app.ReceiverRestrictedContext@42842328
D/WeatherTheme( 1870): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
D/AppUp4:CustFacade( 3662): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3662): isOpenOperator : true
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/WeatherService( 1870): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 13:37:45
D/AppUp4:CustFacade( 3662): isPhone : true
I/LicenseContentProvider( 2906): start selecting data
D/SIMObserver( 2906): simInfo1
I/MusicWidget( 2103): appWidgetViewUpdate()_4x1
I/MusicWidget( 2103): linkButtons()_4x1
I/AppUp4:EulaManager( 3662): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3662): begin check event
I/AppUp4:CustModeStarterReceiver( 3662): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 3662): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 3662): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 3662): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 3662): handleAsync isTriedOnce : false
E/AppUp4:CustModeStarterReceiver( 3662): handleAsyncCustNotification do not startCustService
D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,I/ActivityManager(  964): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4516 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/MusicWidget( 2103): pushUpdate()_4x1
,I/MusicWidget( 2103): performViewUpdater handleMessage() msg.what::3
,I/MusicWidget( 2103): beingMusicWidget_Quick() result::false
,D/HyLog   ( 4516): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4516): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4516): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  964): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4534 uid=10063 gids={50063, 3003, 1028, 1015}
,V/DownloadManager( 4516): DownloadService onCreate
,D/EAS     ( 4083): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4083): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4083): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,I/DownloadManager( 4516): in removeSpuriousFiles
D/HyLog   ( 4534): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4534): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4534): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/DownloadManager( 4516): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4516): created cursor android.database.sqlite.SQLiteCursor@42875878 on behalf of 4516
I/DownloadManager( 4516): in trimDatabase
V/DownloadManager( 4516): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4516): created cursor android.database.sqlite.SQLiteCursor@42877290 on behalf of 4516
,V/DownloadManager( 4516): DownloadService onStartCommand
,V/DownloadManager( 4516): DownloadService onStartCommand
,V/DownloadManager( 4516): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,I/ActivityManager(  964): Start proc com.android.mms for broadcast com.android.mms/.transaction.LgeMiscReceiver: pid=4553 uid=10035 gids={50035, 3003, 1028, 1015, 1023, 4002, 3002}
W/linker  ( 4083): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4083): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4083): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4083): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
I/dalvikvm( 4083): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
V/DownloadManager( 4516): created cursor android.database.sqlite.SQLiteCursor@4287a318 on behalf of 4516
D/HtmlEditor( 4083): register_HtmlEditor, Success
D/HtmlEditor( 4083): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4083): register_HtmlEditorTimer, Success
D/HtmlEditor( 4083): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4083): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4083): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4083): register_HtmlEditorFont, Success
D/HtmlEditor( 4083): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4083): register_HtmlEditorDrawText, Success
D/HtmlEditor( 4083): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HyLog   ( 4553): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4553): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4553): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/DownloadManager( 4516): DownloadService onDestroy
D/HtmlEditor( 4083): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4083): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4083): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 4083): JNI_OnLoad Success
I/HubEmail( 4083): JNI_OnLoad()
I/HubEmail( 4083): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4083): registerNatives()
I/HubEmail( 4083): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4083): registerNativeMethods()
I/HubEmail( 4083): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
W/Settings( 4083): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ConversationSkinProvider( 4553): skin provider oncreate
,I/MusicWidget( 2103): performViewUpdater handleMessage() msg.what::1
,I/MusicWidget( 2103): beingMusicWidget_4x2() result::false
,I/MusicWidget( 2103): beingMusicWidget_Lock() result::false
,D/DelayedSyncController( 4534): Delaying sync.
,E/[MMS]   ( 4553): MmsSettings: [LGE] MmsSettings.initializeMmsSettings()
,W/BaseRuntimeLoader( 4553): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4553): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4553): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4553): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/[MMS]   ( 4553): MmsSettings: [LGE]loadXMLSettings() ++++++++++ >> Load default:false
I/[MMS]   ( 4553): MmsSettings: [LGE]loadXMLSettings() SIM(current) information
I/[MMS]   ( 4553): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
,E/[MMS]   ( 4553): MmsSettings: [LGE]loadXMLSettings() [Build] Country:EU, Operator:OPEN
,D/[MMS]   ( 4553): MmsSettings: loadxmlstring=open_eu_mms_config
,D/[MMS]   ( 4553): MmsSettings: Matching Xml Data file name = 2131034168
,E/Auth.Api.Credentials( 1938): [CredentialSyncAdapter] Unknown sync event.
,W/DriveInitializer( 1938): Background init thread started
I/ActivityManager(  964): Killing 3686:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
,D/[MMS]   ( 4553): MmsSettings: [LGE]parseDTMF() file doesn't exist
D/[MMS]   ( 4553): MmsSettings: [LGE]setDefaultDTMFVolume() set default DTMF value
E/[MMS]   ( 4553): MmsSettings: [LGE]loadXMLSettings(): Check current items.
D/[MMS]   ( 4553): MmsSettings: [LGE]---------------------------------------->
,D/[MMS]   ( 4553): MmsSettings: [LGE]   sms_dr = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   cb_on = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   sms_concat = [5]
D/[MMS]   ( 4553): MmsSettings: [LGE]   sms_char = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_dr_r = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_dr_a = [1]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_rr_r = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_rr_a = [1]
D/[MMS]   ( 4553): MmsSettings: [LGE]   auto_retr = [1]
D/[MMS]   ( 4553): MmsSettings: [LGE]   auto_retr_r = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_priority = [1]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_validity = [6]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_creation = [2]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_size = [300]
D/[MMS]   ( 4553): MmsSettings: [LGE]   slide_dur = [5]
D/[MMS]   ( 4553): MmsSettings: [LGE]   recv_adv = [1]
D/[MMS]   ( 4553): MmsSettings: [LGE]   push_on = [1]
D/[MMS]   ( 4553): MmsSettings: [LGE]   del_old = [1]
,D/[MMS]   ( 4553): MmsSettings: [LGE]   sms_limit = [500]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_limit = [50]
D/[MMS]   ( 4553): MmsSettings: [LGE]   max_editor_num = [2000]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_slide_num = [10]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_recipient_num = [20]
D/[MMS]   ( 4553): MmsSettings: [LGE]   attachement_storage = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   send_msg_enter_key = [1]
D/[MMS]   ( 4553): MmsSettings: [LGE]   spam_setting = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   anonymous_spam_setting = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_recipient_length = [64]
D/[MMS]   ( 4553): MmsSettings: [LGE]   sms_recipient_length = [20]
D/[MMS]   ( 4553): MmsSettings: [LGE]   recv_adv_invisible = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_creation_invisible = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_dr_r_invisible = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_dr_a_invisible = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_rr_r_invisible = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_rr_a_invisible = [0]
,D/[MMS]   ( 4553): MmsSettings: [LGE]   auto_retr_r_invisible = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_validity_invisible = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_priority_invisible = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   sms_char_invisible = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   sms_dr_invisible = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   sms_validity_invisible = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   discard_visible = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_pending_in_wifi_use = [1]
D/[MMS]   ( 4553): MmsSettings: [LGE]   attach_location = [1]
D/[MMS]   ( 4553): MmsSettings: [LGE]   custom_extract_ui = [1]
D/[MMS]   ( 4553): MmsSettings: [LGE]   msg_list_data_seperator = [1]
D/[MMS]   ( 4553): MmsSettings: [LGE]   animation_effect = [1]
D/[MMS]   ( 4553): MmsSettings: [LGE]   inline_msg_item = [1]
D/[MMS]   ( 4553): MmsSettings: [LGE]   display_as_slide_layout = [1]
D/[MMS]   ( 4553): MmsSettings: [LGE]   one_bubble = [1]
D/[MMS]   ( 4553): MmsSettings: [LGE]   hide_sync_header_update = [1]
D/[MMS]   ( 4553): MmsSettings: [LGE]   recipient_cc_bcc = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   ciq_on = [0]
,D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_enabled_when_data_disabled = [1]
D/[MMS]   ( 4553): MmsSettings: [LGE]   two_finger_flick = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   kr_skt_feature_set = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   kr_kt_feature_set = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   kr_lgu_feature_set = [0]
,D/[MMS]   ( 4553): MmsSettings: [LGE]   docomo_message_setting = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   docomo_sim_card_set = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   docomo_nexti_phonebook_set = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   docomo_function_validity_period = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   docomo_led_button_blink = [0]
,D/[MMS]   ( 4553): MmsSettings: [LGE]   docomo_dtmf_setting = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   china_feature_set = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   media_resolution_restrict_off = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   attachment_save_in_slidesheow = [0]
,D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_max_video_resolution = [320x240]
D/[MMS]   ( 4553): MmsSettings: [LGE]   email_over_sms = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   email_over_sms_gateway_num = [0]
W/DriveInitializer( 1938): Awaiting to be initialized
,D/[MMS]   ( 4553): MmsSettings: [LGE]   addr_len_check = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   message_poster = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   sticky_note = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   wificalling_feature_set = [0]
,D/[MMS]   ( 4553): MmsSettings: [LGE]   online_album = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   online_album_dest_num = [000]
D/[MMS]   ( 4553): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   voice_mail = [0]
,D/[MMS]   ( 4553): MmsSettings: [LGE]   smsc_readonly = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   latin_america_fdn_check = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   sms_sent_time_mode = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   fdn_gprs_check = [0]
,D/[MMS]   ( 4553): MmsSettings: [LGE]   reply_to_virtual_smsc = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   save_to_draft = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_signature = [0]
D/[MMS]   ( 4553): MmsSettings: [LGE]   mms_callback = [0]
,D/[MMS]   ( 4553): MmsSettings: [LGE]   message_counters_key = [0]
,E/[MMS]   ( 4553): MmsSettings: [LGE]loadXMLSettings(): Check prefMmsConfig.
,I/[MMS]   ( 4553): MmsSettings: [LGE]loadXMLSettings() Phone(saved) information
I/[MMS]   ( 4553): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 4553): MmsSettings: [LGE]loadXMLSettings(): SIM is NOT changed!!!
,E/[MMS]   ( 4553): MmsSettings: [LGE]loadXMLSettings(): SIM is not ready!!!
,D/MmsConfig( 4553): [LGE] setForceSmsGsmAlphabet_SystemProperties.set: 0
,I/[MMS]   ( 4553): MmsConfig: [LGE]getUaString=LG-D802 LG-Android-MMS-V4.0/1.2
,I/LGDrmService( 4553): _DRM_ServiceGet() : Bind lgdrm service
,E/Diag_Lib(  281): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  281): qmi_init:  Created client handle b7d1f9d8
,E/Diag_Lib(  281): qmi_client [281] 7: sending 848 bytes on fd = 16
,E/Diag_Lib(  281): qmi_client [281] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  281): Sending signal ...... to read cmd data 
E/Diag_Lib(  281): qmi error code.........:0
E/Diag_Lib(  281): qmi sys error code.........:0
D/DRM_Adap(  281): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  281): Setting the api flag to : 1
,E/Diag_Lib(  281): qmi_client [281] 7: sending 47 bytes on fd = 16
,E/Diag_Lib(  281): qmi_client [281] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  281):  API Flag .............. 1 
E/Diag_Lib(  281):  Message ID ............... 37 
E/Diag_Lib(  281): qmi_service_release called, user_handle=20200
E/Diag_Lib(  281): qmi_free_srvc_data : ENTRY
,E/Diag_Lib(  281): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  281): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  281): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  281): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  281): qmi_service_delete_client_txns : EXIT
,E/Diag_Lib(  281): qmi_free_srvc_data : ENTRY
,E/Diag_Lib(  281): qmi_client [281] 7: sending 848 bytes on fd = 16
,E/Diag_Lib(  281): qmi_client [281] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  281): Sending signal ...... to read cmd data 
E/Diag_Lib(  281): qmi error code.........:0
E/Diag_Lib(  281): qmi sys error code.........:0
D/DRM_Adap(  281): drmLibGetIMEI: success getting IMEI
,D/LGDRM   (  281): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
E/Diag_Lib(  281): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  281): qmi_init:  Created client handle b7d1f9f0
E/Diag_Lib(  281): qmi_client [281] 7: sending 848 bytes on fd = 16
,E/Diag_Lib(  281): qmi_client [281] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  281): Sending signal ...... to read cmd data 
E/Diag_Lib(  281): qmi error code.........:0
E/Diag_Lib(  281): qmi sys error code.........:0
D/DRM_Adap(  281): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  281): Setting the api flag to : 1
,E/Diag_Lib(  281): qmi_client [281] 7: sending 47 bytes on fd = 16
,E/Diag_Lib(  281): qmi_client [281] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  281):  API Flag .............. 1 
E/Diag_Lib(  281):  Message ID ............... 37 
E/Diag_Lib(  281): qmi_service_release called, user_handle=20200
E/Diag_Lib(  281): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  281): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  281): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  281): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  281): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  281): qmi_service_delete_client_txns : EXIT
E/Diag_Lib(  281): qmi_free_srvc_data : ENTRY
,E/Diag_Lib(  281): qmi_client [281] 7: sending 848 bytes on fd = 16
,E/Diag_Lib(  281): qmi_client [281] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  281): Sending signal ...... to read cmd data 
E/Diag_Lib(  281): qmi error code.........:0
E/Diag_Lib(  281): qmi sys error code.........:0
D/DRM_Adap(  281): drmLibGetIMEI: success getting IMEI
D/LGDRM   (  281): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
I/DrmWrapper( 4553): isDrmV1 =true
,V/DrmWrapper( 4553): isDrmV2 =false
V/MmsConfig( 4553): [isMmsEnabledWhenDataDisabled]value=1
,V/MmsConfigStaticVar( 4553): [setMmsEnabledWhenDataDisabled]enabled=true
,W/DriveInitializer( 1938): Background init thread ended
,V/MmsConfigStaticVar( 4553): [setMmsEnabledWhenDataRoamingDisabled]enabled=false
,D/CmasFeatures( 4553): [init]CMAS features are initialized for US country. Returning.
,V/Contact ( 4553): Contact init()_Create new insatnce
,D/dalvikvm( 1938): GC_CONCURRENT freed 1208K, 23% free 19222K/24832K, paused 2ms+3ms, total 39ms
,I/MessagingNotification( 4553): registerLEDObserver
,I/MessagingNotification( 4553): registerLEDObserver REGISTER
,V/MmsConfig( 4553): [getMPDNSupport]is_KrDevice:false is_Mpdn:false is_Roaming:false networkOperator:
D/CountryDetector(  964): The first listener is added
,E/ActivityThread( 4553): Failed to find provider info for com.lge.ims.provider.uc
I/LOG_TAG ( 4553): registerContactDBChangeObserver
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/dalvikvm(  964): GC_EXPLICIT freed 2107K, 49% free 28987K/56760K, paused 3ms+7ms, total 89ms
I/LgeMiscReceiver( 4553): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4553): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4553): networkInfo.isConnected() = false
,D/LocationManagerService(  964): getProviders()=[passive, gps]
,D/LocationManagerService(  964): request 44c94798 passive Request[POWER_NONE passive fastest=0] from android(1000)
,D/LocationManagerService(  964): provider request: passive ProviderRequest[ON interval=0]
I/ActivityManager(  964): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4605 uid=10052 gids={50052, 3003}
,V/LGRssiData( 4553): [loadRssi] File not exist 
V/LGRssiData( 4553): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4553): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 4553): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4553): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4553): [getValue] FEATURE key : vzw_roaming_state, value : null
I/ActivityManager(  964): Killing 4100:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
,D/HyLog   ( 4605): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4605): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4605): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 4605): [loadRssi] File not exist 
V/LGRssiData( 4605): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4605): [loadFeatureFromXml] *** start feature loading from xml
,W/BaseRuntimeLoader( 4605): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4605): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4605): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4605): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 4605): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4605): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4605): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/MobileConnectivityChangeReceiver( 4605): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4605): onReceive CONNECTIVITY_CHANGE networkType=1
,E/PhoneMonitor( 4605): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4605): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
,I/ActivityManager(  964): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4619 uid=10066 gids={50066, 4002, 3003, 1028}
,I/CheckinService( 1938): Checking schedule, now: 1449751066358 next: 1449748717008
,I/CheckinService( 1938): active receiver: enabled
,D/dalvikvm(  274): GC_EXPLICIT freed 46K, 34% free 16472K/24832K, paused 1ms+1ms, total 17ms
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
,I/CheckinService( 1938): Preparing to send checkin request
,I/EventLogService( 1938): Accumulating logs since 1449750289118
,D/DelayedSyncController( 4534): Delaying sync.
D/HyLog   ( 4619): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4619): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4619): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
,D/DrmBroadcastReceiver( 4619): Receive CONNECTIVITY_ACTION
,D/LGDMClient( 2784): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4298): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2784): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
I/ActivityManager(  964): Killing 3741:com.android.vending/u0a50 (adj 15): empty #17
,W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2784): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
I/NFS     ( 4316): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4316): CONNECT : WIFI_CONNECT
,D/dalvikvm( 1526): GC_EXPLICIT freed 252K, 29% free 17810K/24832K, paused 1ms+3ms, total 28ms
,E/LGDMClient( 2784): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
I/ActivityManager(  964): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4637 uid=10104 gids={50104, 3003, 1028, 1015}
,D/LGDMClient( 2784): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2784): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2784): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  964): Killing 1832:com.google.android.gms.wearable/u0a6 (adj 15): empty #17
,D/HyLog   ( 4637): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4637): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4637): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
,W/GAV2    ( 4637): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/CheckinRequestBuilder( 1938): Checkin reason type: 8 attempt count: 1
D/WifiService(  964): New client listening to asynchronous messages
E/ActivityThread( 1938): Failed to find provider info for com.google.android.wearable.settings
,V/WebViewChromium( 4637): Binding Chromium to the main looper Looper (main, tid 1) {4282b6b8}
,I/chromium( 4637): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4637): Initializing chromium process, renderers=0
,W/chromium( 4637): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4637): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4637): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4637): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4637): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4637): Remote Branch: 
I/Adreno-EGL( 4637): Local Patches: 
I/Adreno-EGL( 4637): Reconstruct Branch: 
,I/NSApplication( 4637): Starting up...
,W/BaseRuntimeLoader( 1938): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1938): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 1938): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1938): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/ActivityManager(  964): Killing 4069:com.lge.bnr/1000 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/iu.SyncManager( 1938): SYNC; picasa accounts
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,D/NetworkLogImpl( 1938): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1938): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,I/iu.UploadsManager( 1938): num queued entries: 0
,I/iu.UploadsManager( 1938): num updated entries: 0
,I/iu.SyncManager( 1938): NEXT; no task
,W/CheckinRequestBuilder( 1938): awaiting user notification for token
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,I/ActivityManager(  964): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=4680 uid=10010 gids={50010, 3003, 1028, 4002}
,D/Tethering(  964): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
D/NotificationService(  964): updateLightListLocked :r=null, action=2
,D/HyLog   ( 4680): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4680): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4680): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,E/OpenGL ES Test( 4680): getCurrentLocale == en_US
,E/OpenGL ES Test( 4680): localeFound retString == en_US
E/OpenGL ES Test( 4680): getCurrentLocale == en_US
E/OpenGL ES Test( 4680): localeFound retString == en_US
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/ALBootInit( 4680): ====action==>android.intent.action.TIME_SET
,D/ALBootInit( 4680): Alarm ALBootInit: TIME_SET
,D/Alarms  ( 4680): [setNextAlert] start
,D/Alarms  ( 4680): [setNextAlert] (1)
,D/Alarms  ( 4680):  minTime  = 0
,D/Alarms  ( 4680):  -- OK multi -- 0
E/jeny.kim( 4680): [setNextAlert] setNextAlert  temp_Alarmlink + 
,E/jeny.kim( 4680): [setNextAlert]setNextAlert temp_AlarmLinkText + 
,D/Alarms  ( 4680): setStatusBarIcon : false
,I/ActivityManager(  964): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4695 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
D/Alarms  ( 4680): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,D/WorldClockReceiver( 4680): ====action==>android.intent.action.TIME_SET
E/OpenGL ES Test( 4680): getCurrentLocale == en_US
E/OpenGL ES Test( 4680): localeFound retString == en_US
E/OpenGL ES Test( 4680): getCurrentLocale == en_US
,E/OpenGL ES Test( 4680): localeFound retString == en_US
E/OpenGL ES Test( 4680): getCurrentLocale == en_US
E/OpenGL ES Test( 4680): localeFound retString == en_US
E/OpenGL ES Test( 4680): getCurrentLocale == en_US
,E/OpenGL ES Test( 4680): localeFound retString == en_US
D/HyLog   ( 4695): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4695): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4695): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,E/OpenGL ES Test( 4680): isExistDatabase = false
,W/dalvikvm( 4695): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4695): VFY: replacing opcode 0x60 at 0x000b
,I/CommonUtil( 4680): BUILD Country: EU
E/OpenGL ES Test( 4680): loadMapCityData() -- S
E/OpenGL ES Test( 4680): getCurrentLocale == en_US
E/OpenGL ES Test( 4680): localeFound retString == en_US
E/OpenGL ES Test( 4680): getCurrentLocale == en_US
E/OpenGL ES Test( 4680): localeFound retString == en_US
D/dalvikvm( 4695): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4695): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4695): VFY: replacing opcode 0x62 at 0x005e
,I/MultiDex( 4695): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4695): install
,I/MultiDex( 4695): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4695): loading existing secondary dex files
,I/MultiDex( 4695): load found 3 secondary dex files
,I/MultiDex( 4695): install done
,E/OpenGL ES Test( 4680): loadMapCityData() - While S
,D/dalvikvm( 4695): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4695): VFY: unable to resolve instance field 61
,D/dalvikvm( 4695): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4695): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4695): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4695): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4695): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4695): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4695): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4695): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4695): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4695): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42834330
D/dalvikvm( 4695): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42834330
,D/dalvikvm( 4695): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42834330, skipping init
,D/dalvikvm( 4695): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42834330
D/dalvikvm( 4695): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42834330
,V/JNIHelp ( 4695): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,E/OpenGL ES Test( 4680): loadMapCityData() - While E
E/OpenGL ES Test( 4680): loadMapCityData() -- E
D/dalvikvm( 4695): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x42834330
,E/OpenGL ES Test( 4680): getCurrentLocale == en_US
E/OpenGL ES Test( 4680): localeFound retString == en_US
D/dalvikvm( 4695): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x42834330
E/OpenGL ES Test( 4680): getCurrentLocale == en_US
E/OpenGL ES Test( 4680): localeFound retString == en_US
D/dalvikvm( 4695): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x42834330
,D/dalvikvm( 4695): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x42834330
,E/OpenGL ES Test( 4680): [updateWidgetDST] backup_cityInfoList is null >>>>
,I/ActivityManager(  964): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=4712 uid=10015 gids={50015, 3003, 1028, 1015}
,D/GCM     ( 1526): Connected
I/ActivityManager(  964): Killing 4248:com.lge.settings.easy/1000 (adj 15): empty #17
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/HyLog   ( 4712): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4712): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4712): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ProviderInstaller( 4695): Installed default security provider GmsCore_OpenSSL
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/GCM     ( 1526): Message class com.google.f.a.a.p
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/Config  ( 4712): LGCalendar ver.4.2.6
I/Config  ( 4712): start check model
,I/Config  ( 4712): start check native_ca
,E/Config  ( 4712): [setCountryAndOperator] Operator=OPEN, Country=EU
I/dalvikvm( 4695): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4695): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4695): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4695): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4695): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4695): VFY: replacing opcode 0x6e at 0x0201
,D/WVCdm   (  276): Instantiating CDM.
,I/WVCdm   (  276): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  276): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
,D/QSEECOMAPI: (  276): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  276): App is not loaded in QSEE
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
,D/CalendarWidget( 4712): Agenda AppWidgetService got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory }
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
,I/InitNotificationRingtoneService( 4712): Start InitializeAlertRingtoneService.onHandleIntent
,D/QSEECOMAPI: (  276): Loaded image: APP id = 2
D/DrmWidevineDash(  276): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2043000
,E/DrmWidevineDash(  276): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb2043000
,I/ActivityManager(  964): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4740 uid=10016 gids={50016, 3003, 1028, 1015}
,D/DrmWidevineDash(  276): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  276): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  276): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  276): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  276): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
D/HyLog   ( 4740): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4740): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4740): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/InitNotificationRingtoneService( 4712): internal content query returns 1 results.
,I/InitNotificationRingtoneService( 4712): Found default schedule notification : Schedule.ogg(id:42)
D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
,I/InitNotificationRingtoneService( 4712): set default noti to content://media/internal/audio/media/42
,I/InitNotificationRingtoneService( 4712): End InitializeAlertRingtoneService.onHandleIntent
,D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
,D/WVCdm   (  276): PrepareKeyRequest: nonce=1534961923
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,I/CalendarProvider2( 4740): Created com.android.providers.calendar.CalendarAlarmManager@4284dbd8(com.android.providers.calendar.CalendarProvider2@42844b40)
,D/dalvikvm( 4695): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a2dbd0
D/dalvikvm( 4695): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a2dbd0
,D/dalvikvm( 4695): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a2dbd0, skipping init
,I/ActivityManager(  964): Start proc com.lge.task for broadcast com.lge.task/.widget.TasksWidgetProvider: pid=4757 uid=10043 gids={50043, 3003, 1028, 1015}
,I/ActivityManager(  964): Killing 4260:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4757): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4757): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4757): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,E/TASKS   ( 4757): init() PortStorageManger PRIMARY_STORAGE_PATH :/storage/emulated/0
,D/TASKS_APP_WIDGET( 4757): onReceive() #################################################
,I/TASKS   ( 4757): getCurrentThemeInfo START #############################
,I/TASKS   ( 4757): com.lge.launcher2.theme.optimus
I/TASKS   ( 4757): com.lge.task
I/TASKS   ( 4757): getCurrentThemeInfo END #############################
I/TASKS   ( 4757): loadThemeResources packageName : com.lge.task
,I/TASKS   ( 4757): loadLocalResId #############################
,D/TASKS_APP_WIDGET( 4757): intentAction : android.intent.action.TIME_SET
,W/Settings( 4695): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
I/ActivityManager(  964): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4774 uid=10122 gids={50122}
I/ActivityManager(  964): Killing 4372:com.lge.qremote/u0a96 (adj 15): empty #17
,D/HyLog   ( 4774): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4774): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4774): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm( 4774): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x42837048, skipping init
,D/TimeService( 4774): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449751067284
D/        ( 4774): TimeServiceNative: User Time to be set is 1449751067284
D/QC-time-services( 4774): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4774): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4774): Lib:time_genoff_operation: pargs->ts_val = 1449751067284
D/QC-time-services( 4774): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  614): Daemon: Connection accepted:time_genoff
D/QC-time-services(  614): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449751067284
D/QC-time-services(  614): Daemon:genoff_opr: Base = 2, val = 1449751067284, operation = 0
D/QC-time-services(  614): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/17/70 0:22:39
D/QC-time-services(  614): Daemon:Value read from RTC seconds = 9159759000
D/QC-time-services(  614): Daemon:new time 1449751067284 
D/QC-time-services(  614): Daemon: delta 1440591308284 genoff 1440591308284 
D/QC-time-services(  614): Daemon:genoff_persistent_update: Writing genoff = 1440591308284 to memory
D/QC-time-services(  614): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  614): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/dalvikvm( 4695): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,D/QC-time-services(  614): Updating the TOD offset
D/QC-time-services(  614): Daemon:genoff_persistent_update: Writing genoff = 1440591308284 to memory
D/QC-time-services(  614): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  614): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  614): Daemon:Update to modem bit set
D/QC-time-services(  614): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  614): Daemon: Base = 2, Value being sent to MODEM = 1133786267284
,E/QC-time-services( 4774): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  614): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  614): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
I/ActivityManager(  964): Killing 2906:com.lge.eula/1000 (adj 15): empty #17
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
,I/ActivityThread( 3662): Removing dead content provider:android.content.ContentProviderProxy@4287e5f0
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4787): DexOpt: load 5ms, verify+opt 3ms, 128132 bytes
I/NetworkStateForAutoUpdateMonitor( 3662): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3662): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3662): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3662): [onReceive] request level :IDLE....
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiController(  964): battery changed pluggedType: 2
D/HeadsetStateMachine( 1205): Disconnected process message: 10
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/AppUp4:CustModeStarterReceiver( 3662): onReceive
D/AppUp4:CustFacade( 3662): Context : android.app.ReceiverRestrictedContext@42842328
D/AppUp4:CustFacade( 3662): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3662): isOpenOperator : true
D/AppUp4:CustFacade( 3662): isPhone : true
,D/dalvikvm( 4695): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4695): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 0ms, rewrite 76ms
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,I/Adreno-EGL( 4695): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4695): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4695): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4695): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4695): Remote Branch: 
I/Adreno-EGL( 4695): Local Patches: 
I/Adreno-EGL( 4695): Reconstruct Branch: 
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/ActivityManager(  964): Start proc com.lge.eula for content provider com.lge.eula/.databases.LicenseContentProvider: pid=4791 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,D/HyLog   ( 4791): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4791): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4791): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1205): Disconnected process message: 10
,D/WifiController(  964): battery changed pluggedType: 2
D/dalvikvm(  964): GC_EXPLICIT freed 1023K, 49% free 29329K/56760K, paused 3ms+8ms, total 100ms
I/LicenseContentProvider( 4791): start selecting data
W/BaseRuntimeLoader( 4791): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4791): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
W/BaseRuntimeLoader( 4791): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4791): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 292 plugged : true isCharging : false
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1205): Disconnected process message: 10
,D/SIMObserver( 4791): simInfo1
,D/WifiController(  964): battery changed pluggedType: 2
I/Adreno-EGL( 4695): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4695): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4695): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4695): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4695): Remote Branch: 
I/Adreno-EGL( 4695): Local Patches: 
I/Adreno-EGL( 4695): Reconstruct Branch: 
,I/AppUp4:EulaManager( 3662): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 3662): begin check event
,I/AppUp4:CustModeStarterReceiver( 3662): Event For GoodConnectivity, noConnectivity : false, but skip! 
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,V/DownloadManager( 4516): DownloadService onCreate
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/EAS     ( 4083): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
D/EAS     ( 4083): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,I/DownloadManager( 4516): in removeSpuriousFiles
,V/DownloadManager( 4516): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4516): DownloadService onStartCommand
V/DownloadManager( 4516): created cursor android.database.sqlite.SQLiteCursor@42883f58 on behalf of 4516
,V/DownloadManager( 4516): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
I/DownloadManager( 4516): in trimDatabase
,V/DownloadManager( 4516): created cursor android.database.sqlite.SQLiteCursor@42885d50 on behalf of 4516
V/DownloadManager( 4516): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4553): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4553): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4553): networkInfo.isConnected() = true
,D/PhoneState( 4553): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4605): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4605): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4516): DownloadService onDestroy
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/DrmBroadcastReceiver( 4619): Receive CONNECTIVITY_ACTION
D/DrmBroadcastReceiver( 4619): 1  network is available. Sync DRM Time with NTP
,W/Settings( 4083): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4516): created cursor android.database.sqlite.SQLiteCursor@42887568 on behalf of 4516
,D/LGDMClient( 2784): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,V/DrmService( 4619): Service onCreate
,D/DrmService( 4619): Received new request = 2
,D/LGDMSGCM( 4298): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
I/DrmSntpClient( 4619): Start Sync process
,D/DrmSntpClient( 4619): Server : 0
,D/LGDMClient( 2784): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/LGDMClient( 2784): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/DataScheduler( 4619): isDataSchedulerEnabled():false
,W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
D/libc    (  270): _dns_getaddrinfo: iptype =1
D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
E/LGDMClient( 2784): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
D/LGDMClient( 2784): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2784): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
I/LGDMClient( 2784): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/Adreno-EGL( 4695): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4695): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4695): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4695): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4695): Remote Branch: 
I/Adreno-EGL( 4695): Local Patches: 
I/Adreno-EGL( 4695): Reconstruct Branch: 
I/NFS     ( 4316): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4316): CONNECT : WIFI_CONNECT
,D/dalvikvm( 3720): GC_FOR_ALLOC freed 761K, 16% free 20922K/24832K, paused 15ms, total 15ms
,I/dalvikvm-heap( 3720): Grow heap (frag case) to 26.515MB for 4099024-byte allocation
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,I/NetworkStateForAutoUpdateMonitor( 3662): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 3662): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 3662): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 3662): [onReceive] request level :IDLE....
D/dalvikvm( 3720): GC_CONCURRENT freed 38K, 14% free 24891K/28836K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 3720): WAIT_FOR_CONCURRENT_GC blocked 21ms
,I/AppUp4:CustModeStarterReceiver( 3662): onReceive
D/AppUp4:CustFacade( 3662): Context : android.app.ReceiverRestrictedContext@42842328
D/AppUp4:CustFacade( 3662): isCustomizationCompleted : false
D/AppUp4:CustFacade( 3662): isOpenOperator : true
,D/AppUp4:CustFacade( 3662): isPhone : true
,I/LicenseContentProvider( 4791): start selecting data
,I/LGDrmService( 4619): _DRM_ServiceGet() : Bind lgdrm service
I/LGDRM   (  281): [DRM] SET TIME : YR=2015, MON=12, DAY=10
I/LGDRM   (  281): [DRM] SET TIME : HR=12, MIN=37, SEC=46
,D/SIMObserver( 4791): simInfo1
,I/dalvikvm-heap( 3720): Grow heap (frag case) to 30.390MB for 4099024-byte allocation
,I/AppUp4:EulaManager( 3662): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 3662): begin check event
,I/AppUp4:CustModeStarterReceiver( 3662): Event For GoodConnectivity, noConnectivity : false, but skip! 
I/DrmSntpClient( 4619): Synched
D/DrmService( 4619): Completed !! request = 2
,D/DrmService( 4619): Request count = 0
,V/DrmService( 4619): Service onDestroy
,V/DownloadManager( 4516): DownloadService onCreate
,I/DownloadManager( 4516): in removeSpuriousFiles
V/DownloadManager( 4516): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 4083): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4083): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4516): created cursor android.database.sqlite.SQLiteCursor@4288b028 on behalf of 4516
,I/DownloadManager( 4516): in trimDatabase
,V/DownloadManager( 4516): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4553): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4553): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4553): networkInfo.isConnected() = true
,D/PhoneState( 4553): setPdpRejectCasuse : false
,W/Settings( 4083): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/MobileConnectivityChangeReceiver( 4605): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/dalvikvm( 3720): GC_CONCURRENT freed 2K, 13% free 28892K/32840K, paused 3ms+1ms, total 17ms
,D/MobileConnectivityChangeReceiver( 4605): onReceive CONNECTIVITY_CHANGE networkType=1
,V/DownloadManager( 4516): created cursor android.database.sqlite.SQLiteCursor@4288c9e0 on behalf of 4516
,V/DownloadManager( 4516): DownloadService onStartCommand
,V/DownloadManager( 4516): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4516): created cursor android.database.sqlite.SQLiteCursor@4288eb50 on behalf of 4516
,D/LGDMClient( 2784): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4298): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2784): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,W/ContextImpl( 4298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
V/DownloadManager( 4516): DownloadService onDestroy
I/NFS     ( 4316): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4316): CONNECT : WIFI_CONNECT
I/LGDMClient( 2784): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2784): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2784): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
D/LGDMClient( 2784): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received.
,I/LGDMClient( 2784): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
W/ActivityThread(  964): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
I/ActivityManager(  964): Killing 3701:com.android.gallery3d/u0a27 (adj 15): empty #17
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/dalvikvm( 3720): GC_FOR_ALLOC freed 7K, 13% free 28892K/32840K, paused 25ms, total 25ms
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
,I/dalvikvm-heap( 3720): Grow heap (frag case) to 34.297MB for 4099024-byte allocation
,D/WeatherAncestor( 1870): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:37:47
,D/UpdateThreadPoolManager( 1870): 2 : This is isUpdating : false
,D/Weather_cast( 1870): 2 : Request from alarm is Canceled
,D/WeatherAncestor( 1870): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 13:37:47
D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/WeatherService( 1870): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
,D/WeatherQuickCover( 1870): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1870): 2 : Utils getTopActivity com.lge.launcher2 / false
,D/Weather.Utils( 1870): 2 : Utils getTopActivity com.lge.easyhome / false
,D/WeatherService( 1870): 2 : shouldTimeTickRegistered : false
I/ActivityManager(  964): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4821 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,D/HyLog   ( 4821): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4821): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4821): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/WifiServiceExtension(  964): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  964): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,I/Babel   ( 4821): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4821): MmsConfig.loadMmsSettings
,I/MediaCodecList( 4821): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 4821): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 4821): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 4821): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,I/Babel   ( 4821): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 4821): MmsConfig.loadFromDatabase
,W/BaseRuntimeLoader( 4821): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4821): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4821): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4821): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/Babel   ( 4821): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4821): MmsConfig.loadFromResources
,E/Babel   ( 4821): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4821): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 4821): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 4821): [loadRssi] File not exist 
,V/LGRssiData( 4821): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4821): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 4821): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4821): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4821): [getValue] FEATURE key : vzw_roaming_state, value : null
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1154): usb Uevent not necessary.
,D/GCM     ( 1526): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AuthorizationBluetoothService( 1526): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
E/AuthorizationBluetoothService( 1526): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1938): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 292 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1205): Disconnected process message: 10
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/WifiController(  964): battery changed pluggedType: 2
,I/ActivityManager(  964): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4848 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 291 plugged : true isCharging : false
D/HeadsetStateMachine( 1205): Disconnected process message: 10
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
D/WifiController(  964): battery changed pluggedType: 2
,D/CalendarWidget( 4712): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 4712): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
,D/LocationInitializer( 1938): Restart initialization of location
D/TASKS_APP_WIDGET( 4757): onReceive() #################################################
,I/TASKS   ( 4757): getCurrentThemeInfo START #############################
I/TASKS   ( 4757): com.lge.launcher2.theme.optimus
I/TASKS   ( 4757): com.lge.task
I/TASKS   ( 4757): getCurrentThemeInfo END #############################
I/TASKS   ( 4757): loadThemeResources packageName : com.lge.task
,I/TASKS   ( 4757): loadLocalResId #############################
,D/TASKS_APP_WIDGET( 4757): intentAction : com.lge.task.APPWIDGET_UPDATE
,D/HyLog   ( 4848): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4848): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/CalendarWidget( 4712): Agenda AppWidgetService init broadcastReceiver
D/CalendarWidget( 4712): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
,D/HyLog   ( 4848): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/dalvikvm( 4848): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4848): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 4848): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4848): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4848): VFY: replacing opcode 0x62 at 0x005e
I/WVCdm   (  276): CdmEngine::OpenSession
,D/DrmWidevineDash(  276): calling OEMCrypto_OpenSession...
I/MultiDex( 4848): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4848): install
,I/MultiDex( 4848): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4848): loading existing secondary dex files
D/DrmWidevineDash(  276): OEMCrypto_OpenSession SID = 1
D/DrmWidevineDash(  276): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  276): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  276): CdmEngine::GenerateKeyRequest
D/DrmWidevineDash(  276): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,I/MultiDex( 4848): load found 3 secondary dex files
,I/MultiDex( 4848): install done
,D/DrmWidevineDash(  276): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GetDeviceID...
,D/dalvikvm( 4848): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4848): VFY: unable to resolve instance field 61
,D/dalvikvm( 4848): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4848): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4848): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4848): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 4848): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4848): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4848): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4848): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4848): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4848): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4283b678
,D/dalvikvm( 4848): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4283b678
,D/dalvikvm( 4848): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4283b678, skipping init
,D/dalvikvm( 4848): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4283b678
D/dalvikvm( 4848): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4283b678
,V/JNIHelp ( 4848): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
D/DrmWidevineDash(  276): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  276): PrepareKeyRequest: nonce=284492536
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  276): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4233): wlan0: Control interface command 'SIGNAL_POLL'
,D/dalvikvm( 4848): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4283b678
D/dalvikvm( 4848): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4283b678
D/dalvikvm( 4848): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4283b678
,D/dalvikvm( 4848): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4283b678
,D/wpa_supplicant( 4233): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
E/Parcel  (  605): Reading a NULL string not supported here.
,E/Parcel  (  605): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/ProviderInstaller( 4848): Installed default security provider GmsCore_OpenSSL
,D/GCM     ( 1526): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1526): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1526): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1938): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/DrmWidevineDash(  276): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  276): CdmEngine::CloseSession
,D/DrmWidevineDash(  276): calling OEMCrypto_CloseSession. SID = 1
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,D/DrmWidevineDash(  276): OEMCrypto_CloseSession returns 0
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/LocationInitializer( 1938): Restart initialization of location
,I/dalvikvm( 4848): Could not find method android.os.UserManager.getUserProfiles, referenced from method com.google.android.gms.wearable.service.n.a
W/dalvikvm( 4848): VFY: unable to resolve virtual method 1402: Landroid/os/UserManager;.getUserProfiles ()Ljava/util/List;
,D/dalvikvm( 4848): VFY: replacing opcode 0x6e at 0x003f
,D/WearableService( 4848): callingUid 10006, callindPid: 4848
E/dalvikvm( 4848): Could not find class 'android.telecom.TelecomManager', referenced from method com.google.android.gms.wearable.service.y.a
W/dalvikvm( 4848): VFY: unable to resolve check-cast 869 (Landroid/telecom/TelecomManager;) in Lcom/google/android/gms/wearable/service/y;
,D/dalvikvm( 4848): VFY: replacing opcode 0x1f at 0x0054
,W/dalvikvm( 4848): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,E/Babel   ( 4821): UserRecoverableAuthException.
,I/CheckinRequestBuilder( 1938): Classify the device as Phone.
E/Babel   ( 4821): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4821): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4821): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4821): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4821): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4821): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4821): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4821): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4821): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4821): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4821): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
,E/Babel   ( 4821): Error getting auth token
,E/Babel   ( 4821): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4821): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4821): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4821): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4821): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4821): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4821): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4821): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4821): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4821): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
,E/Babel   ( 4821): Account registration failedRedacted-21
I/dalvikvm( 4848): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4848): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4848): VFY: replacing opcode 0x6e at 0x000d
,E/Babel   ( 4821): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4821): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4821): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4821): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4821): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4821): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4821): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4821): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4821): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
I/Babel   ( 4821): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 4821): Account sign in complete with state 106account: Redacted-21
I/dalvikvm( 4848): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4848): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4848): VFY: replacing opcode 0x6e at 0x0201
,E/MDM     ( 1424): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1424): [87] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  964): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  964): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/CalendarProvider2( 4740): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4740): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 4712): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 4712): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/CalendarWidget( 4712): Agenda AppWidgetService got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory }
,D/AlertService( 4712): Beginning updateAlertNotification
,D/AlertService( 4712): No fired or scheduled alerts
,I/ActivityManager(  964): Killing 4680:com.lge.clock/u0a10 (adj 15): empty #17
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
D/CalendarWidget( 4712): Agenda AppWidgetService init broadcastReceiver
D/CalendarWidget( 4712): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,E/Babel   ( 4821): Unexpected exception while authenticating.
,E/Babel   ( 4821): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4821): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4821): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4821): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4821): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4821): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4821): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4821): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4821): 	at java.lang.Thread.run(Thread.java:841)
D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x43303410: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinTask( 1938): Sending checkin request (11651 bytes)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinRequestBuilder( 1938): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1938): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1526): GC_EXPLICIT freed 1163K, 29% free 17806K/24832K, paused 2ms+6ms, total 47ms
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/NotificationService(  964): updateLightListLocked :r=NotificationRecord(0x43240e78: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/CheckinRequestBuilder( 1938): awaiting user notification for token
D/NotificationService(  964): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/CheckinRequestBuilder( 1938): Classify the device as Phone.
,I/CheckinTask( 1938): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
I/CheckinService( 1938): Checking schedule, now: 1449751069263 next: 1450328465259
,I/CheckinService( 1938): active receiver: disabled
,I/CheckinService( 1938): Checking schedule, now: 1449751069297 next: 1450328465259
,I/CheckinService( 1938): active receiver: disabled
,D/GCM     ( 1526): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  964): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=4905 uid=10050 gids={50050, 3003, 1028, 1015}
,D/dalvikvm(  274): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 2ms+9ms, total 61ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/HyLog   ( 4905): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4905): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4905): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 36ms
,D/dalvikvm(  274): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 17ms
,I/dalvikvm( 4905): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
,W/dalvikvm( 4905): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4905): VFY: replacing opcode 0x6e at 0x000b
,D/Finsky  ( 4905): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/dalvikvm( 4905): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
,W/dalvikvm( 4905): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4905): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 4905): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4905): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4905): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4905): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 4905): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4905): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4905): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4905): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4905): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4905): VFY: replacing opcode 0x6e at 0x011e
,I/dalvikvm( 4905): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4905): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
D/dalvikvm( 4905): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 4905): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4905): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 4905): VFY: replacing opcode 0x6e at 0x029a
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/dalvikvm( 4905): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4905): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
,D/dalvikvm( 4905): VFY: replacing opcode 0x6e at 0x001a
,V/DownloadManager( 4516): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4516): created cursor android.database.sqlite.SQLiteCursor@42893ca8 on behalf of 4905
E/BatteryObserver( 1154): usb Uevent not necessary.
,I/dalvikvm( 4905): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
,W/dalvikvm( 4905): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
,D/dalvikvm( 4905): VFY: replacing opcode 0x6e at 0x0049
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 4905): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4905): [1] 2.run: Finished loading 1 libraries.
,D/Finsky  ( 4905): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/Finsky  ( 4905): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/dalvikvm( 4905): Total arena pages for JIT: 11
,I/dalvikvm( 4905): Total arena pages for JIT: 12
I/dalvikvm( 4905): Total arena pages for JIT: 13
,I/dalvikvm( 4905): Total arena pages for JIT: 14
,D/Finsky  ( 4905): [423] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4905): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  964): Killing 4774:com.qualcomm.timeservice/u0a122 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/Finsky  ( 4905): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/dalvikvm( 4905): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4905): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4905): VFY: replacing opcode 0x62 at 0x0037
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4233): wlan0: Control interface command 'SIGNAL_POLL'
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 4233): nl80211: survey data missing!
,D/WifiStateMachine(  964): handleMessage: X
,D/dalvikvm(  964): GC_EXPLICIT freed 2095K, 49% free 29497K/56760K, paused 6ms+9ms, total 167ms
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4905): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4905): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GLSUser ( 1526): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1526): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1526): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1526): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1526): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1526): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4905): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4905): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4905): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4905): [1] DailyHygiene.reschedule: Scheduling new run in 31 minutes (failures=2)
,D/DeviceConnectionService( 1424): client connected with version: 7571000
,I/GAV2    ( 4637): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/ActivityManager(  964): Killing 4791:com.lge.eula/1000 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityThread( 3662): Removing dead content provider:android.content.ContentProviderProxy@428960d8
,I/ActivityManager(  964): Killing 3662:com.lge.appbox.client/u0a11 (adj 15): empty #17
,I/ActivityManager(  964): Killing 4083:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  964): Killing 4553:com.android.mms/u0a35 (adj 15): empty #17
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 2 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Top activity resumed ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
,D/CountryDetector(  964): No listener is left
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/LocationManagerService(  964): remove 44c94798
,D/LocationManagerService(  964): provider request: passive ProviderRequest[ON interval=0]
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4233): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4233): nl80211: survey data missing!
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  605): Reading a NULL string not supported here.
,E/Parcel  (  605): Reading a NULL string not supported here.
,D/WifiStateMachine(  964): handleMessage: X
,D/CaptivePortalTracker(  964): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/QcConnectivityService(  964): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/libc    (  270): _dns_getaddrinfo: iptype =1
D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/CaptivePortalTracker(  964): Checking http://216.58.209.46/generate_204
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,D/CaptivePortalTracker(  964): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  964): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  964): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  964): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  964): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/PowerManagerService(  964): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  964): [updateScreenState] screen on = false
,D/KnockOnPowerController(  964): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  964): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  964): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  964): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  964): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
,I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8398 usec
D/KnockOnPowerController(  964): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  964): hal_acquire_resources
,I/qcom_sensors_hal(  964): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  964): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  964): hal_sam_activate: Activating sensor handle 35
,V/qcom_sensors_hal(  964): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  964): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  964): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
D/qcom_sensors_hal(  964): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  964): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.480438 Y: -0.412506 Z: 9.741135 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.480438 .y:-0.412506 .z:9.741135
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/Sensors (  583): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.478775 Y: -0.404266 Z: 9.739120 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.478775 .y:-0.404266 .z:9.739120
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
V/qcom_sensors_hal(  964): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  964): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  964): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/KnockOnPowerController(  964): proximity onSensorChanged : proximity = 1
,D/KnockOnPowerController(  964): proximitySensorChanged  positive = true
,I/KnockOnPowerController(  964): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.482285 Y: -0.400909 Z: 9.749741 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.482285 .y:-0.400909 .z:9.749741
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.474731 Y: -0.404236 Z: 9.756393 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.474731 .y:-0.404236 .z:9.756393
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.463776 Y: -0.403961 Z: 9.746155 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.463776 .y:-0.403961 .z:9.746155
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  964): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5010 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.478897 Y: -0.403610 Z: 9.743973 
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.478897 .y:-0.403610 .z:9.743973
,D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
,D/administrator(  964): Handling package changes for user 0
,E/SlideAside( 3542): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/SlideAside( 3542): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.talk
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
,E/SlideAside( 3542): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3542): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
,V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.483475 Y: -0.406372 Z: 9.766739 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.483475 .y:-0.406372 .z:9.766739
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
,I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/InputReader(  964): Reconfiguring input devices.  changes=0x00000010
D/SurfaceFlinger(  273): Screen released, type=0 flinger=0xb7f5c450
D/qdhwcomposer(  273): hwc_blank: Blanking display: 0
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/administrator(  964): Handling package changes for user 0
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,V/KeyguardServiceDelegate(  964): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43219608)
D/KeyguardViewMediator( 1140): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1140): notifyScreenOnLocked
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  964):   Scheme: "sms"
D/WifiStateMachine(  964): handleScreenStateChanged: true
D/WifiStateMachine(  964): handleMessage: E msg.what=131154
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiNative-wlan0(  964): doString: SIGNAL_POLL
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 4233): wlan0: Control interface command 'SIGNAL_POLL'
D/WifiServiceExtension(  964): sendKtScanInterval  mRtspPlay : false
E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=on
V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=on, calling pid 964
D/WifiOffDelayIfNotUsed(  964): stopMonitoring
V/SRS_Proc(  276): ParamSet string: screen_state=on
D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=on
V/voice   (  276): voice_set_parameters: enter: screen_state=on
V/voice   (  276): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  276): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  276): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1154): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{43255650 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
,D/wpa_supplicant( 4233): nl80211: survey data missing!
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  964):   Scheme: "smsto"
E/SlideAside( 3542): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 3542): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
D/EmotionalLed( 1154): enqueuing start. mLedList.size()=2
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=3
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/EmotionalLed( 1154): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131127
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131158
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=132097
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  964): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 4233): wlan0: Control interface command 'KT_SCAN_INTERVAL'
D/wpa_supplicant( 4233): initialize kt scan interval and do scan state=9
D/WifiStateMachine(  964): handleMessage: X
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  964):   Scheme: "mms"
E/Parcel  (  605): Reading a NULL string not supported here.
,E/Parcel  (  605): Reading a NULL string not supported here.
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "sms"
,I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "smsto"
,I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mms"
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,I/PackageManager(  964):   Action: "android.intent.action.SENDTO"
I/PackageManager(  964):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  964):   Scheme: "mmsto"
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
I/PackageManager(  964): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,V/GmsNetworkLocationProvi( 1424): DISABLE
,I/GCoreNlp( 1424): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/LocationProviderProxy(  964): applying state to connected service
,D/LocationProviderProxy(  964): applying state to connected service
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1154): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/qdlights( 1154): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 249, B = 249
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,D/qdlights( 1154): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1154): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1154): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1154): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1154): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 219, B = 219
,D/qdhwcomposer(  273): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  964): Excessive delay in blankDisplay() while turning screen off: 411ms
D/qdlights( 1154): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 213, B = 213
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/HyLog   ( 5010): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5010): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5010): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/KeyguardViewMediator( 1140): handleNotifyScreenOn
D/KeyguardViewManager( 1140): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  964): **** SHOWN CALLED ****
D/qdlights( 1154): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 207, B = 207
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,I/WindowManager(  964): No lock screen! windowToken=null
E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
I/AppUp4  ( 5010):  AppBoxContentProvider onCreate
W/AppUp4  ( 5010):  [AppBoxDatabaseHelper] construct
D/qdlights( 1154): set_light_notifications: 2,ff00c9c9,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 201, B = 201
I/AppUp4  ( 5010):  setFingerPrint start
I/AppUp4  ( 5010):  newfinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
I/AppUp4  ( 5010):  beforefinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
I/AppUp4  ( 5010):  beforefinger == newfinger no write in DB
D/AppUp4:AppBoxApplication( 5010): AppBoxApplication onCreate()
D/AppBoxBlacklist( 5010): ConfigFile is not exist. /cust/config/appmanager.cfg
D/qdlights( 1154): set_light_notifications: 2,ff00c3c3,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1154): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1154): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1154): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 177, B = 177
,D/GlobalAccess( 1140): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1140): changeTargets() succeeded. size: 20
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449751077147, nextTick: 2883, mDrawingTime: 3
,D/qdlights( 1154): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1154): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 165, B = 165
D/PackageParser( 5010): Added overlay pkg for /system/apps/bootup/LGTaskManager.apk
,D/qdlights( 1154): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 159, B = 159
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449751077173, nextTick: 2860, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=4
,D/qdlights( 1154): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 153, B = 153
D/WeatherService( 1870): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:37:57
,D/WeatherService( 1870): 2 : ACTION screen on
,D/WeatherService( 1870): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1870): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:37:57
,D/qdlights( 1154): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 147, B = 147
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
,E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
,D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
D/qdlights( 1154): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 141, B = 141
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_ON
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_ON
,D/qdlights( 1154): set_light_notifications: 2,ff008787,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 135, B = 135
D/KeyguardViewMediator( 1140): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1140): notifyScreenOffLocked
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  964): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  964): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  964): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
,D/KeyguardViewMediator( 1140): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/qdlights( 1154): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 129, B = 129
D/qcom_sensors_hal(  964): hal_acquire_resources
D/qcom_sensors_hal(  964): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  964): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=1000
V/ActivityManager(  964): Moving to PAUSING: ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3}
I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
V/ActivityManager(  964): Moving to PAUSED: ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  964): Moving to STOPPING: ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3} (stop requested)
V/ActivityManager(  964): Moving to DESTROYING: ActivityRecord{430d1c58 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,D/UsbSettings( 2539): [AUTORUN] onDestroy() : getDefaultFunction =boot
,I/LGImmersionVibrator(  964): Vibrator off
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  964): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  964): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  964): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
D/WifiStateMachine(  964): handleScreenStateChanged: false
D/WifiStateMachine(  964): handleMessage: E msg.what=131154
V/qcom_sensors_hal(  964): hal_process_report_ind: X: -0.464371 Y: -0.398499 Z: 9.745926 
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.464371 .y:-0.398499 .z:9.745926
D/qcom_sensors_hal(  964): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  964): hal_wait_for_response: timeout=0
D/KeyguardViewMediator( 1140): handleNotifyScreenOff
D/WifiStateMachine(  964): processMsg: ConnectedState
D/KeyguardViewManager( 1140): onScreenTurnedOff()
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): handleMessage: X
D/WifiStateMachine(  964): handleMessage: E msg.what=131158
D/WifiStateMachine(  964): processMsg: ConnectedState
D/WifiStateMachine(  964): processMsg: L2ConnectedState
D/WifiStateMachine(  964): processMsg: ConnectModeState
D/WifiStateMachine(  964): processMsg: DriverStartedState
D/WifiStateMachine(  964): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  964): doBoolean: DRIVER SETSUSPENDMODE 1
,V/UsbSettings( 2539): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/qcom_sensors_hal(  964): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  964): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  964): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  964): hal_smgr_report_delete: Rcvd success response from request
,V/UsbSettings( 2539): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
D/wpa_supplicant( 4233): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 4233): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
E/AudioSystem(  964): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  276): setParameters(): io 0, keyvalue screen_state=off, calling pid 964
V/SRS_Proc(  276): ParamSet string: screen_state=off
D/audio_hw_primary(  276): adev_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: enter: screen_state=off
V/voice   (  276): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  276): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  276): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  276): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  276): adev_set_parameters: exit with code(-2)
,V/UsbSettings( 2539): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
D/qdlights( 1154): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 123, B = 123
V/ActivityManager(  964): Moving to STOPPED: ActivityRecord{44debdf0 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/WifiController(  964): CMD_SCREEN_OFF 
D/WifiController(  964): shouldWifiStayAwake TRUE
D/PackageParser( 5010): Added overlay pkg for /system/apps/bootup/LGHome_Theme_Marshmallow.apk
,D/wpa_supplicant( 4233): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  964):    returned true
,D/WifiStateMachine(  964): handleMessage: X
D/AppUp4:Utils( 5010): [getPackageName] uri : package:com.google.android.talk
D/AppUp4  ( 5010): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 5010): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.talk
,I/AppUp4:CustModeStarterReceiver( 5010): onReceive
,E/CliptrayService( 1154): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/EmotionalLed( 1154): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/VolumeVibrator( 1154): clear
D/qdlights( 1154): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 117, B = 117
D/AppUp4:CustFacade( 5010): Context : android.app.ReceiverRestrictedContext@42842410
D/AppUp4:CustFacade( 5010): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5010): isOpenOperator : true
,D/AppUp4:CustFacade( 5010): isPhone : true
V/ActivityManager(  964): Moving to DESTROYED: ActivityRecord{430d1c58 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/qdlights( 1154): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 111, B = 111
,D/NativeNfcBrcmPowerMode( 1474): setPowerMode; state=2
,I/ActivityManager(  964): Start proc com.lge.eula for content provider com.lge.eula/.databases.LicenseContentProvider: pid=5068 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/[LGHome]EVENT( 1489): [Launcher.java:1567:onReceive()]Screen Off
D/qdlights( 1154): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 105, B = 105
,V/TelephonyAutoProfiling(  964): [getValue] FEATURE key : trf_based_vzw, value : null
,D/BubblePopupHelper( 1140): isShowingBubblePopup : false
D/qdlights( 1154): set_light_notifications: 2,ff006363,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 99, B = 99
E/Parcel  (  605): Reading a NULL string not supported here.
D/BubblePopupHelper( 1140): isShowingBubblePopup : false
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
E/Parcel  (  605): Reading a NULL string not supported here.
,D/WeatherService( 1870): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:37:57
D/WeatherService( 1870): 2 : ACTION screen off
,D/WeatherService( 1870): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:37:57
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 5
D/HyLog   ( 5068): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5068): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5068): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/GsmSST  ( 1449): Emergency Service
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1449): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1474): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
D/qdlights( 1154): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 93, B = 93
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
,D/NfcService( 1474): NFC-C OFF
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_OFF
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1462): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1154): set_light_notifications: 2,ff005757,10,0,2
D/qdlights( 1154): [Current] = 255, R = 0, G = 87, B = 87
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  964): ACTION_SCREEN_OFF
,D/qdlights( 1154): set_light_notifications: 2,ff005151,10,0,2
I/LicenseContentProvider( 5068): start selecting data
,D/qdlights( 1154): [Current] = 255, R = 0, G = 81, B = 81
,W/BaseRuntimeLoader( 5068): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5068): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5068): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5068): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/SIMObserver( 5068): simInfo1
,D/qdlights( 1154): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 75, B = 75
,I/AppUp4:EulaManager( 5010): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 5010): begin check event
D/AppUp4:Utils( 5010): [getPackageName] uri : package:com.google.android.talk
I/AppUp4:CustModeStarterReceiver( 5010): Event For Nothing, skip.
D/qdlights( 1154): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1154): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1154): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 57, B = 57
I/ActivityManager(  964): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5088 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  964): Killing 4534:com.android.chrome/u0a63 (adj 15): empty #17
I/ActivityManager(  964): Killing 4605:com.google.android.setupwizard/u0a52 (adj 15): empty #18
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 1 tasks}
,D/qdlights( 1154): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 51, B = 51
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/qdlights( 1154): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 45, B = 45
D/HyLog   ( 5088): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5088): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5088): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/qdlights( 1154): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1154): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1154): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 27, B = 27
,I/SystemConfig( 5088): BUILD Country: EU
,I/SystemConfig( 5088): BUILD Operator: OPEN
D/qdlights( 1154): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 21, B = 21
I/ActivityManager(  964): Killing 4619:com.lge.drmservice/u0a66 (adj 15): empty #17
,D/qdlights( 1154): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1154): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1154): set_light_notifications: 0,0,0,0,3
I/ActivityManager(  964): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5102 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/EmotionalLed( 1154): updateLightsLocked() start. mLedList.size=2
,D/qdlights( 1154): set_light_notifications: 1,ff00ff00,500,2000,1
,I/SystemConfig( 5088): systemFeature RCS result false
,D/SystemConfig( 5088): refreshRcsSupport() :false
I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 1 tasks}
D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5102): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5102): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5102): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  964): Killing 4298:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/IcingCorporaProvider( 2616): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
,I/ActivityManager(  964): resumeTopActivitiesLocked(): target Stack:ActivityStack{4318d2c0 stackId=1, 1 tasks}
,D/ActivityManager(  964): resumeTopActivityLocked: Going to sleep and all paused
,D/PackageBroadcastService( 1938): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,D/dalvikvm( 3720): GC_CONCURRENT freed 9K, 10% free 33214K/36844K, paused 2ms+3ms, total 37ms
,D/AppUp4:Utils( 5010): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 5010): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 5010): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/PeopleContactsSync( 1938): CP2 sync disabled
,I/AppUp4:CustModeStarterReceiver( 5010): onReceive
,D/AppUp4:CustFacade( 5010): Context : android.app.ReceiverRestrictedContext@42842410
D/AppUp4:CustFacade( 5010): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5010): isOpenOperator : true
,D/AppUp4:CustFacade( 5010): isPhone : true
,I/LicenseContentProvider( 5068): start selecting data
,D/SIMObserver( 5068): simInfo1
,I/AppUp4:EulaManager( 5010): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 5010): begin check event
D/AppUp4:Utils( 5010): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 5010): Event For Nothing, skip.
,I/IcingCorporaProvider( 2616): UpdateCorporaTask done [took 88 ms] updated apps [took 88 ms] 
,I/Sensors (  583): sns_pwr.c(320):releasing wakelock
,I/IcingCorporaProvider( 2616): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 1938): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,D/WeatherAncestor( 1870): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:37:57
,I/PackageBroadcastService( 1938): Null package name or gms related package.  Ignoreing.
,D/UpdateThreadPoolManager( 1870): 2 : This is isUpdating : false
,D/WeatherAncestor( 1870): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:37:57
,D/WeatherService( 1870): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1870): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1870): 2 : shouldTimeTickRegistered : false
,I/ActivityManager(  964): Delaying start of: ServiceRecord{442db780 u0 com.google.android.gms/.wearable.service.WearableControlService}
D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,I/Icing   ( 1938): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1938): GC_CONCURRENT freed 1738K, 22% free 19477K/24832K, paused 5ms+9ms, total 62ms
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2616): UpdateCorporaTask done [took 366 ms] updated apps [took 366 ms] 
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  964): handleMessage: E msg.what=131155
,D/WifiStateMachine(  964): processMsg: ConnectedState
,D/WifiStateMachine(  964): processMsg: L2ConnectedState
,D/WifiStateMachine(  964): handleMessage: X
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449751080036, nextTick: 59993, mDrawingTime: 2
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449751080048, nextTick: 59964, mDrawingTime: 7
,E/ThermalEngine(  293): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1140): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1140): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1140): OMADM Lock is OFF
,D/KeyguardViewMediator( 1140): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1140): doKeyguard is called, but is not locked.
,I/GAV4    ( 4821): Thread[GAThread,5,main]: No campaign data found.
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449751085268341659; DSPS: 4954767; Offset: 1449750934060852646
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  964): GC_EXPLICIT freed 2570K, 48% free 29713K/56760K, paused 6ms+15ms, total 211ms
,I/VacuumService( 1526): Vacuum at: now=1449751096380 tag=VacuumService
,I/GoogleURLConnFactory( 1526): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1526): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1526): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1526): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1526): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1526): No account for auth token provided
,D/Finsky  ( 4905): [423] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4905): [1] 5.onFinished: Installation state replication succeeded.
,D/libc    (  270): _dns_getaddrinfo: iptype =1
,D/libc    (  270): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1526): GC_CONCURRENT freed 1800K, 28% free 18001K/24832K, paused 3ms+3ms, total 38ms
,W/Uploader( 1526): No account for auth token provided
,W/Uploader( 1526):  no longer exists, so no auth token.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/Uploader( 1526): No account for auth token provided
,W/Uploader( 1526): No account for auth token provided
,W/Uploader( 1526): No account for auth token provided
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449751105270501964; DSPS: 5610198; Offset: 1449750934060846203
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1154): usb Uevent not necessary.
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  265): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  964): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1140): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 290 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1140): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1205): Disconnected process message: 10
,W/Settings(  964): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  964): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449751125272875238; DSPS: 6265635; Offset: 1449750934060869623
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449751140029, nextTick: 59999, mDrawingTime: 4
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449751140047, nextTick: 59958, mDrawingTime: 10
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449751145275207782; DSPS: 6921072; Offset: 1449750934060852314
,I/rmt_storage(  617): rmt_storage_connect_cb: clnt_h=0x7 conn_h=0xb80fb178
I/rmt_storage(  617): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: R/W request received
,I/rmt_storage(  617): wakelock acquired: 1, error no: 42
,I/rmt_storage(  617): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1206931736)
,I/rmt_storage(  617): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: Bytes written = 1572864
I/rmt_storage(  617): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  617): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1206931736) wakelock released: 1, error no: 0
I/rmt_storage(  617): 
I/rmt_storage(  617): rmt_storage_disconnect_cb: clnt_h=0x0x7 conn_h=0x0xb80fb178
,E/Diag_Lib(  700): [IMS_FATAL]| 2912 | 710 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449751165277982773; DSPS: 7576523; Offset: 1449750934060850205
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449751185280991934; DSPS: 8231981; Offset: 1449750934060868643
,D/KeyguardUpdateMonitor( 1140): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1140): handleTimeUpdate
,D/KeyguardModel( 1140): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449751200042, nextTick: 59965, mDrawingTime: 12
,D/Clock   ( 1140): Clock updated, drawingStartTime : 1449751200056, nextTick: 59972, mDrawingTime: 3
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449751205282518228; DSPS: 8887391; Offset: 1449750934060869059
,D/qcom_sensors_hal(  964): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  964): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  964): hal_ts_offset_is: Apps: 1449751225284941658; DSPS: 9542831; Offset: 1449750934060851082

```
