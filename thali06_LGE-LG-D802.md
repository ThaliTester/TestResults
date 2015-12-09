#### Test 506502789252e15_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/BaseAppContext( 1939): Using Auth Proxy for data requests.
W/BaseAppContext( 1939): Using Auth Proxy for data requests.
I/dalvikvm( 1939): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1939): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1939): VFY: replacing opcode 0x6e at 0x000e
--------- beginning of /dev/log/system
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/DataScheduler( 1939): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1939): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1939): fetch service done; releasing wakelock
I/ConfigFetchService( 1939): stopping self
W/BaseAppContext( 1939): Using Auth Proxy for data requests.
W/BaseAppContext( 1939): Using Auth Proxy for data requests.
W/BaseAppContext( 1939): Using Auth Proxy for data requests.
W/GAV2    ( 4094): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager(  957): Killing 3340:com.google.android.music:main/u0a107 (adj 15): empty #17
W/BaseAppContext( 1939): Using Auth Proxy for data requests.
F/ActivityManager(  957): Service ServiceRecord{432ed2b0 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{431d16a8 3340:com.google.android.music:main/u0a107} not same as in map: null
F/ActivityManager(  957): Service ServiceRecord{430bcf00 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{431d16a8 3340:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 1 tasks}
D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{4291f618 u0 com.android.settings/.UsbSettings t2}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/dalvikvm( 1939): GC_CONCURRENT freed 1554K, 26% free 18423K/24832K, paused 3ms+6ms, total 47ms
D/ChimeraCfgMgr( 1939): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1939): Module APK com.google.android.play.games already loaded
I/Icing   ( 1939): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1939): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1939): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/BatteryObserver( 1151): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AndroidRuntime( 4158): 
D/AndroidRuntime( 4158): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4158): CheckJNI is OFF
D/dalvikvm( 4158): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4158): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4158): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4158): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4158): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4158): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4158): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4158): failed to load memtrack module: -2
D/AndroidRuntime( 4158): Calling main entry com.android.commands.am.Am
I/ActivityManager(  957): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4158
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (124 us)
V/ActivityManager(  957): Moving to PAUSING: ActivityRecord{4291f618 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  957): resumeTopActivityLocked: Pausing null
V/ActivityManager(  957): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  957): startService SlideAside
W/ContextImpl(  957): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  957): setFocusedStack: mFocusedStack=ActivityStack{4335db18 stackId=1, 2 tasks}
D/UsbSettingsControl( 2556): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2556): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4158): Shutting down VM
I/SlideAside( 3518): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4158): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
D/ActivityManager(  957): allPausedActivitiesComplete: r=ActivityRecord{4291f618 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  957): Moving to PAUSED: ActivityRecord{4291f618 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
D/ActivityManager(  957): resumeTopActivityLocked: Restarting ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
I/ActivityManager(  957): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4175 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3518): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3518): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
V/ActivityManager(  957): Moving to RESUMED: ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/HyLog   ( 4175): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4175): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4175): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4175): Binding Chromium to the background looper Looper (main, tid 1) {42875180}
I/chromium( 4175): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4175): Initializing chromium process, renderers=0
W/chromium( 4175): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4175): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4175): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4175): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4175): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4175): Remote Branch: 
I/Adreno-EGL( 4175): Local Patches: 
I/Adreno-EGL( 4175): Reconstruct Branch: 
I/dalvikvm( 4175): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4175): VFY: unable to resolve virtual method 218: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4175): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4175): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4175): VFY: unable to resolve virtual method 213: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4175): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4175): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4175): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4175): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4175): VFY: unable to resolve virtual method 271: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4175): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4175): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4175): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4175): VFY: unable to resolve virtual method 229: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4175): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4175): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4175): VFY: unable to resolve virtual method 234: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4175): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4175): CordovaWebView is running on device made by: LGE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1151): usb Uevent not necessary.
D/dalvikvm( 4175): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/BaseRuntimeLoader( 4175): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4175): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4175): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4175): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4175): Enabling debug mode 0
,W/AwContents( 4175): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  957): Displayed com.test.thalitest/.MainActivity: +378ms
,W/AwContents( 4175): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  957): IME STATUS OFF
,I/ActivityManager( 4175): Timeline: Activity_idle id: android.os.BinderProxy@42876950 time:107769
,D/JsMessageQueue( 4175): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4175): Trying to load lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4287aa30
,D/dalvikvm( 4175): Added shared lib /data/app-lib/com.test.thalitest-2/libjxcore.so 0x4287aa30
,D/jxcore_app_log( 4175): JniHelper::setJavaVM(0x41738838), pthread_self() = 1632208568
,D/JX-Cordova( 4175): jxcore cordova android initializing
,I/dalvikvm( 4175): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.ConnectionHelper.isBleAdvertisingSupported
W/dalvikvm( 4175): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4175): VFY: replacing opcode 0x6e at 0x0045
,I/ActivityManager(  957): Timeline: Activity_windows_visible id: ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3} time:108138
D/ActivityManager(  957): no-history finish of ActivityRecord{4291f618 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  957): Finishing activity token=Token{4334da48 ActivityRecord{4291f618 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  957): Moving to FINISHING: ActivityRecord{4291f618 u0 com.android.settings/.UsbSettings t2 f}
,D/UsbSettings( 2556): [AUTORUN] onStop()
D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  957): Moving to STOPPING: ActivityRecord{4291f618 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,V/ActivityManager(  957): Moving to STOPPED: ActivityRecord{4291f618 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/dalvikvm( 4175): GC_CONCURRENT freed 2784K, 13% free 21831K/24832K, paused 1ms+1ms, total 47ms
,D/dalvikvm( 4175): WAIT_FOR_CONCURRENT_GC blocked 17ms
,D/dalvikvm( 4175): GC_FOR_ALLOC freed 112K, 13% free 21832K/24832K, paused 22ms, total 22ms
,D/dalvikvm( 4175): GC_FOR_ALLOC freed 118K, 12% free 21863K/24832K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4175): Grow heap (frag case) to 23.616MB for 95956-byte allocation
,D/dalvikvm( 4175): GC_FOR_ALLOC freed 191K, 13% free 21887K/24928K, paused 23ms, total 23ms
,D/dalvikvm( 4175): GC_FOR_ALLOC freed 254K, 13% free 21934K/24928K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4175): Grow heap (frag case) to 23.799MB for 215890-byte allocation
,D/dalvikvm( 4175): GC_FOR_ALLOC freed 366K, 13% free 22007K/25140K, paused 23ms, total 23ms
,I/dalvikvm-heap( 4175): Grow heap (frag case) to 23.974MB for 323830-byte allocation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4175): GC_FOR_ALLOC freed 564K, 14% free 22128K/25460K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4175): Grow heap (frag case) to 24.247MB for 485740-byte allocation
,D/dalvikvm( 4175): GC_FOR_ALLOC freed 859K, 15% free 22304K/25936K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4175): Grow heap (frag case) to 24.649MB for 728606-byte allocation
,D/dalvikvm( 4175): GC_FOR_ALLOC freed 1275K, 16% free 22560K/26648K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4175): Grow heap (frag case) to 25.247MB for 1092904-byte allocation
,D/dalvikvm( 4175): GC_CONCURRENT freed 1915K, 18% free 22965K/27716K, paused 1ms+6ms, total 47ms
,D/dalvikvm( 4175): GC_CONCURRENT freed 1683K, 16% free 23449K/27716K, paused 2ms+2ms, total 27ms
,D/dalvikvm( 4175): WAIT_FOR_CONCURRENT_GC blocked 8ms
,D/dalvikvm( 4175): GC_FOR_ALLOC freed 1459K, 16% free 23541K/27716K, paused 25ms, total 25ms
,I/dalvikvm-heap( 4175): Grow heap (frag case) to 27.507MB for 2459024-byte allocation
,D/dalvikvm( 4175): GC_CONCURRENT freed 233K, 15% free 25881K/30120K, paused 2ms+3ms, total 28ms
,D/dalvikvm( 4175): GC_FOR_ALLOC freed 4360K, 19% free 24503K/30120K, paused 30ms, total 30ms
,I/dalvikvm-heap( 4175): Grow heap (frag case) to 29.620MB for 3688532-byte allocation
,D/dalvikvm( 4175): GC_CONCURRENT freed 416K, 17% free 28054K/33724K, paused 2ms+4ms, total 48ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4175): GC_FOR_ALLOC freed 3065K, 25% free 25513K/33724K, paused 25ms, total 25ms
,W/jxcore-log( 4175): Initializing JXcore engine
,W/jxcore-log( 4175): JXcore engine is ready
,D/dalvikvm( 4175): GC_CONCURRENT freed 428K, 17% free 28090K/33724K, paused 2ms+1ms, total 26ms
,D/dalvikvm( 4175): WAIT_FOR_CONCURRENT_GC blocked 21ms
,W/jxcore-log( 4175): Starting JXcore engine
,W/jxcore-log( 4175): Platform android
W/jxcore-log( 4175): 
,W/jxcore-log( 4175): Process ARCH arm
W/jxcore-log( 4175): 
,I/dalvikvm(  957): Jit: resizing JitTable from 8192 to 16384
,I/ActivityManager(  957): Killing 2128:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,I/jxcore-log( 4175): JXcore Cordova bridge is ready!
I/jxcore-log( 4175): 
,W/jxcore-log( 4175): JXcore engine is started
,I/chromium( 4175): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4175): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4175): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/jxcore-log( 4175): Toggling radios to true
I/jxcore-log( 4175): 
,D/BluetoothManagerService(  957): Message: 20
D/BluetoothManagerService(  957): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43d9d170:true
D/BluetoothManagerService(  957): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  957): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  957): Message: 1
,D/BluetoothManagerService(  957): MESSAGE_ENABLE: mBluetooth = null
,D/WifiService(  957): New client listening to asynchronous messages
,D/WifiService(  957): setWifiEnabled: true pid=4175, uid=10304
E/WifiService(  957): Invoking mWifiStateMachine.setWifiEnabled
,I/WifiService(  957): setWifiEnabled startWifiDelaySendMsg true
,D/BluetoothAdapterService( 1213): REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothAdapterService(1116324896)( 1213): onCreate
,I/GAV2    ( 4094): Thread[GAThread,5,main]: No campaign data found.
D/BluetoothManagerService(  957): Message: 20
D/BluetoothAdapterState( 1213): make
,D/BluetoothManagerService(  957): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44d2b778:true
I/bluedroid( 1213): init ready=0
,D/bt-btif ( 1213): in initialized:0
D/bt-btif ( 1213): root, p->name:Bluedroid, child/value:0x6066dca8, bytes:160
I/BluetoothAdapterState( 1213): Entering OffState
,D/bt-btif ( 1213): p->used:0, type:0, p->flag:0
,I/bte_conf( 1213): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
W/BT_PROF ( 1213): set profile trace flags 0x0
,D/BTIF_CORE( 1213): [BTUI] lge_load_bluetooth_address
,D/bt-btif ( 1213):  [BTUI] Load_abtddress
D/btif_config_util( 1213): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
D/bt-btif ( 1213): PERSIST_BDADDR_PROPERTY is  34:FC:EF:9D:93:0B
,D/bt-btif ( 1213): Got prior random BDA 34:FC:EF:9D:93:0B
,D/lge_bdaddr_loader( 4228): [BTUI] bdaddr_loader ::: START
,D/lge_bdaddr_loader( 4228): [BTUI] bluetooth_load_bdaddress
,D/lge_bdaddr_loader( 4228): [BTUI] bdaddr to set in property : 34:FC:EF:9D:93:0B
,E/lge_bdaddr_loader( 4228): [BTUI] bluetooth_load_bdaddress : OK => 34:FC:EF:9D:93:0B
,D/lge_bdaddr_loader( 4228): [BTUI] bdaddr_loader ::: END
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1151): usb Uevent not necessary.
,D/WifiStateMachine(  957): setting operational mode to 1
D/WifiStateMachine(  957): handleMessage: E msg.what=131083
,D/WifiStateMachine(  957): processMsg: InitialState
,I/jxcore-log( 4175): Radios toggled
I/jxcore-log( 4175): 
,E/WifiHW  (  957): Wifi MAC Address = 34:fc:ef:de:0a:e2
,E/WifiHW  (  957): wifi_check_config compare "cur_etheraddr=34:fc:ef:de:0a:e2
E/WifiHW  (  957): ": cur_etheraddr=34:fc:ef:de:0a:e2
D/WifiService(  957): disconnect pid=4175, uid=10304
,D/WifiService(  957): reconnect pid=4175, uid=10304
D/SoftapController(  264): Softap fwReload - Ok
D/CommandListener(  264): Setting iface cfg
,D/CommandListener(  264): Trying to bring down wlan0
,D/WifiMonitor(  957): WifiMonitorSingleton gotten
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  957): setWifiState: enabling
,E/WifiStateMachine(  957): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  957): useWiFiOffloading() : false
E/WifiStateMachine(  957): CONFIG_LGE_WLAN_PATH : true
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,V/WfdStateTracker( 1151): WfdStateTracker handleDirectStateChangedEvent: 1
D/WifiStateMachine(  957): Supplicant start successful
D/WifiMonitor(  957): WifiMonitorSingleton gotten
D/WifiMonitor(  957): startMonitoring(wlan0) with mConnected = false
,D/WifiMonitor(  957): connecting to supplicant
,I/WifiServiceExtension(  957): WIFI_STATE_CHANGED_ACTION [2]
I/ActivityManager(  957): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4233 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/wpa_supplicant( 4232): wpa_supplicant v2.1-devel-4.4.2
D/wpa_supplicant( 4232): random: Added entropy from /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4232): random: Trying to read entropy from /dev/random
D/wpa_supplicant( 4232): Get randomness: len=20 entropy=1
D/wpa_supplicant( 4232): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
D/wpa_supplicant( 4232): Global control interface '@android:wpa_wlan0'
D/wpa_supplicant( 4232): Using Android control socket 'wpa_wlan0'
I/wpa_supplicant( 4232): Successfully initialized wpa_supplicant
D/wpa_supplicant( 4232): Override interface parameter: ctrl_interface ('(null)' -> '/data/misc/wifi/sockets')
D/wpa_supplicant( 4232): Initializing interface 'wlan0' conf '/data/misc/wifi/wpa_supplicant.conf' driver 'nl80211' ctrl_interface '/data/misc/wifi/sockets' bridge 'N/A'
D/wpa_supplicant( 4232): Configuration file '/data/misc/wifi/wpa_supplicant.conf' -> '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4232): Reading configuration file '/data/misc/wifi/wpa_supplicant.conf'
D/wpa_supplicant( 4232): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4232): disable_scan_offload=1
D/wpa_supplicant( 4232): driver_param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4232): update_config=1
D/wpa_supplicant( 4232): device_name='g2_open_com'
D/wpa_supplicant( 4232): manufacturer='LGE'
D/wpa_supplicant( 4232): model_name='LG-D802'
D/wpa_supplicant( 4232): model_number='LG-D802'
D/wpa_supplicant( 4232): serial_number='022678fb504e29b0'
D/wpa_supplicant( 4232): config_methods='physical_display virtual_push_button keypad'
D/wpa_supplicant( 4232): p2p_disabled=1
D/wpa_supplicant( 4232): p2p_no_group_iface=1
D/wpa_supplicant( 4232): Line: 15 - start of a new network block
D/wpa_supplicant( 4232): ssid - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 4232): PSK (ASCII passphrase) - hexdump(len=10): [REMOVED]
D/wpa_supplicant( 4232): key_mgmt: 0x2
D/wpa_supplicant( 4232): priority=1 (0x1)
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
D/dalvikvm(  268): GC_EXPLICIT freed 45K, 34% free 16472K/24832K, paused 0ms+2ms, total 23ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 13ms
,D/wpa_supplicant( 4232): PSK (from passphrase) - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 4232): Priority group 1
D/wpa_supplicant( 4232):    id=0 ssid='NG700'
,D/wpa_supplicant( 4232): Reading configuration file '/system/etc/wifi/wpa_supplicant_overlay.conf'
I/bluedroid( 1213): get_profile_interface socket
I/bt-btif ( 1213): btif_get_adapter_property 2
,I/bt-btif ( 1213): btif_get_adapter_property 1
D/wpa_supplicant( 4232): disable_scan_offload=1
D/wpa_supplicant( 4232): Priority group 1
D/wpa_supplicant( 4232):    id=0 ssid='NG700'
I/wpa_supplicant( 4232): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4232): nl80211: RFKILL status not available
D/wpa_supplicant( 4232): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 4232): nl80211: TDLS supported
D/wpa_supplicant( 4232): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4232): nl80211: Enable multi-channel concurrent (driver advertised support)
I/wpa_supplicant( 4232): [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
D/wpa_supplicant( 4232): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4232): nl80211: interface wlan0 in phy phy0
D/wpa_supplicant( 4232): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 4232): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8a35590
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a35590
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a35590
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a35590
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a35590
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a35590
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a35590
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a35590
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a35590
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a35590
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a35590
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=2): 0a 11
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+1ms, total 22ms
,D/BluetoothAdapterService(1116324896)( 1213): onBind
D/BluetoothManagerService(  957): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  957): Message: 40
D/BluetoothManagerService(  957): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 1213): config_hci_snoop_log
D/BluetoothManagerService(  957): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  957): Broadcasting onBluetoothServiceUp() to 8 receivers.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/GKI_LINUX( 1213): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
D/bt-btif ( 1213): btif task starting
D/bt-btif ( 1213): btif_associate_evt: notify ASSOCIATE_JVM
I/bt-btif ( 1213): HAL bt_hal_cbacks->thread_evt_cb
I/bt-btif ( 1213): execute storage request event : 3
D/bt-btif ( 1213): btif_storage_get_adapter_property property->type:2 
I/bt-btif ( 1213): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btif ( 1213): execute storage request event : 3
D/bt-btif ( 1213): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1213): in, bd addr:, prop type:1, len:512
I/bt-btif ( 1213): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  957): Bluetooth Adapter name changed to Thali Test's G2
D/BluetoothManagerService(  957): Stored Bluetooth name: Thali Test's G2
,D/HyLog   ( 4233): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4233): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4233): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm( 1213): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
D/BluetoothAdapterService(1116324896)( 1213): Enable called with quiet mode status =  false
D/PCSuite ( 4233): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/BluetoothAdapterState( 1213): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
I/BluetoothAdapterState( 1213): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 1213): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  957): Message: 60
D/BluetoothManagerService(  957): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
D/BluetoothManagerService(  957): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothAdapterService(1116324896)( 1213): processStart()
I/ActivityManager(  957): Killing 3809:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,D/LGBluetoothAPIService( 1151): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/LGBluetoothXmlHandler( 2556): dvice configuraion start
D/LGBluetoothXmlHandler( 2556): startDocument!
D/LGBluetoothXmlHandler( 2556): startElement - elet = Device
,D/LGBluetoothXmlHandler( 2556): startElement - elet = OLDHELP
D/LGBluetoothXmlHandler( 2556): startElement - elet = OLDHELP
D/LGBluetoothXmlHandler( 2556): startElement - elet = OPPDIRECTORYBLUETOOTH
D/LGBluetoothXmlHandler( 2556): startElement - elet = OPP_DIRECTORY_BLUETOOTH
,D/LGBluetoothXmlHandler( 2556): endDocument!
,D/BluetoothAdapterService(1116324896)( 1213): processStart(): Make Bond State Machine
,D/BluetoothBondStateMachine( 1213): make
D/BluetoothAdapterService( 1213): setAdapterService(): set to: null
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
,D/LGBluetoothServiceAdapter( 1213): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
D/LGBluetoothServiceAdapter( 1213): [BTUI] check adapter is available - true : set adapter available.
,D/LGBluetoothSettingsDBObserver( 1213): [BTUI] register observer for LG device name DB
,I/BluetoothBondStateMachine( 1213): StableState(): Entering Off State
,V/BluetoothPbapReceiver( 1213): PbapReceiver onReceive 
,V/BluetoothPbapReceiver( 1213): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 1213): ***********state = 11
,E/BluetoothAdapterService( 1213): File transfer profiels supported!!
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
W/BluetoothAdapterService( 1213): Starting service com.broadcom.bt.service.hfp.BrcmHeadsetService
D/BluetoothHeadset(  957): Proxy object connected
D/BluetoothHeadset( 1447): Proxy object connected
D/BluetoothHeadset( 1447): Proxy object connected
D/BluetoothHeadset( 1447): Proxy object connected
D/BrcmHeadsetService( 1213): Received start request. Starting profile...
I/Brcm_BluetoothHeadsetServiceJni( 1213): classInitNative: succeeds
E/BluetoothAdapterService( 1213): File transfer profiels supported!!
D/HeadsetStateMachine( 1213): make
W/BluetoothAdapterService( 1213): Starting service com.android.bluetooth.a2dp.A2dpService
E/BluetoothAdapterService( 1213): File transfer profiels supported!!
W/BluetoothAdapterService( 1213): Starting service com.android.bluetooth.hid.HidService
D/BluetoothPermissionRequest( 2556): onReceive
E/BluetoothAdapterService( 1213): File transfer profiels supported!!
I/LGBluetoothHeadsetServiceJni( 1213): classInitNative: succeeds
D/LGBluetoothHfpAdapter( 1213): Version 1.5
W/BluetoothAdapterService( 1213): Starting service com.android.bluetooth.hdp.HealthService
I/bluedroid( 1213): get_profile_interface handsfree
I/bt-btif ( 1213): btif_hf_get_interface
I/bt-btif ( 1213): init
D/bt-btif ( 1213): btif_enable_service: current services:0x40
E/BluetoothAdapterService( 1213): File transfer profiels supported!!
V/AudioPolicyService(  271): getOutput()
V/AudioPolicyManagerBase(  271): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerBase(  271): getOutput() returns output 2
V/AudioSystem( 1213): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
V/AudioFlinger(  271): registerClient() client 0xb8f84570, pid 1213
V/AudioFlinger(  271): sendIoConfigEvent() num events 1 event 0, param 0
V/AudioFlinger(  271): thread 0xb26f4008 type 0 TID 938 waking up
V/AudioFlinger(  271): sendIoConfigEvent() num events 1 event 0, param 0
V/AudioFlinger(  271): thread 0xb2589008 type 0 TID 998 waking up
W/BluetoothAdapterService( 1213): Starting service com.android.bluetooth.pan.PanService
V/AudioFlinger(  271): acquireWakeLock_l() AudioOut_2 status 0
V/AudioFlinger(  271): processConfigEvents() remaining events 1
V/AudioFlinger(  271): acquireWakeLock_l() AudioOut_3 status 0
V/AudioFlinger(  271): processConfigEvents() remaining events 1
V/AudioFlinger(  271): PlaybackThread::audioConfigChanged_l, thread 0xb26f4008, event 0, param 0
V/AudioSystem(  271): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  271): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1447): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1447): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  271): PlaybackThread::audioConfigChanged_l, thread 0xb2589008, event 0, param 0
V/AudioSystem(  271): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem(  271): ioConfigChanged() opening already existing output! 3
V/AudioFlinger(  271): acquireWakeLock_l() AudioOut_3 status 0
V/AudioFlinger(  271): acquireWakeLock_l() AudioOut_2 status 0
V/AudioSystem( 1213): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1597): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1597): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  957): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  957): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  957): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem(  957): ioConfigChanged() opening already existing output! 3
V/AudioSystem( 1447): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1213): ioConfigChanged() new output samplingRate 48000, format 1 channel mask 0x3 frameCount 960 latency 160
V/AudioSystem( 1213): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1213): ioConfigChanged() new output samplingRate 48000, format 1 channel mask 0x3 frameCount 960 latenc,y 50
V/AudioSystem( 1213): getSamplingRate() streamType 8, output 2, sampling rate 48000
V/AudioTrack( 1213): sampleRate 0, channelMask 0x1, format 1
V/AudioTrack( 1213): streamType 8
V/AudioTrack( 1213): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioSystem( 1597): ioConfigChanged() event 0, ioHandle 3
V/AudioPolicyService(  271): checkPlayCondition().. streamType = 8
V/AudioPolicyManagerBase(  271): checkPlayCondition()... stream = 8, bResult = 0
V/AudioTrack( 1213): set() checkPlaycondition!!!! streamType 8 return NO_INIT.
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
D/HeadsetStateMachine( 1213): Enter Disconnected: -2
D/HeadsetPhoneState( 1213): [BTUI] listenForPhoneState : start = false
V/AudioSystem( 1597): ioConfigChanged() opening already existing output! 3
V/AudioSystem( 1447): ioConfigChanged() opening already existing output! 3
D/LGBluetoothHfpManager( 1213): [BTUI] listenForMultiSimPhoneState : start = false
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
D/HeadsetStateMachine( 1213): [BTUI] change sampling rate to 8000 when device is disconnected
D/BluetoothA2dp(  957): Proxy object connected
E/AudioSystem( 1213): AudioSystem::setParameters()...keyValue bt_samplerate=8000
E/BluetoothAdapterService( 1213): File transfer profiels supported!!
V/AudioFlinger(  271): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1213
V/SRS_Proc(  271): ParamSet string: bt_samplerate=8000
D/audio_hw_primary(  271): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  271): voice_set_parameters: enter: bt_samplerate=8000
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
D/A2dpService( 1213): Received start request. Starting profile...
V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
I/BluetoothA2dpServiceJni( 1213): classInitNative: succeeds
D/A2dpStateMachine( 1213): make
W/BluetoothAdapterService( 1213): Starting service com.android.bluetooth.map.BluetoothMapService
I/bluedroid( 1213): get_profile_interface a2dp
I/bt-btif ( 1213): btif_av_get_interface
I/bt-btif ( 1213): init
I/bt-btif ( 1213): ## A2DP START MEDIA TASK ##
I/GKI_LINUX( 1213): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/bt-btif ( 1213): UIPC_Init
I/bt-btif ( 1213): ### uipc_main_init ###
D/bt-btif ( 1213): UIPC_Open : ch_id 0, p_cback 60b07b25
I/bt-btif ( 1213): SETUP CHANNEL SERVER 0
I/bt-btif ( 1213): create_server_socket /data/misc/bluedroid/.a2dp_ctrl
I/bt-btif ( 1213): created socket fd 69
I/bt-btif ( 1213): ADD SERVER FD TO ACTIVE SET 69
I/bt-btif ( 1213): UIPC SEND WAKE UP
I/bt-btif ( 1213): ## A2DP MEDIA TASK STARTED ##
E/bt-btif ( 1213): warning : media task started media_task_refcnt 1 
D/bt-btif ( 1213): btif_enable_service: current services:0x48
D/bt-btif ( 1213): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
I/bt-btif ( 1213): ## ON A2DP IDLE ##
D/bt-btif ( 1213): UIPC_Close : ch_id 1
I/bt-btif ( 1213): CHANNEL 1 ALREADY CLOSED
I/LGBluetoothA2dpServiceJni( 1213): classInitNative: succeeds
E/BluetoothAdapterService( 1213): File transfer profiels supported!!
I/LGBluetoothA2dpAdapter( 1213): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
D/A2dpStateMachine( 1213): Enter Disconnected: -2
I/BluetoothAVRCP1.3ServiceJni( 1213): classInitNativeAVRCP
V/Avrcp   ( 1213): make
W/BluetoothAdapterService( 1213): Starting service com.android.bluetooth.gatt.GattService
E/BluetoothAdapterService( 1213): File transfer profiels supported!!
W/BluetoothAdapterService( 1213): Starting service com.broadcom.bt.service.sap.SapService
D/BluetoothManagerService(  957): Message: 20
D/BluetoothManagerService(  957): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@448dac10:true
D/LGBluetoothAvrcpManager( 1213): [BTUI] initAvcrpManager
E/BluetoothAdapterService( 1213): File transfer profiels supported!!
W/BluetoothAdapterService( 1213): Starting service com.broadcom.bt.service.ftp.FTPService
D/LGBluetoothResetSettingReceiver( 2556): [BTUI] Loading JNI Library
D/dalvikvm( 1213): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
D/LGBluetoothAvrcpManager( 1213): [BTUI] initPlayStatus() : isMusicActive = false
D/LGBluetoothAvrcpAdapter( 1213): [BTUI] Use LG AVRCP : init jni
I/BluetoothAVRCP1.3ServiceJni( 1213): initNativeAVRCP
I/bluedroid( 1213): get_profile_interface avrcp
I/bt-btif ( 1213): btif_rc_get_interface
I/bt-btif ( 1213): ## init ##
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
I/BluetoothHidServiceJni( 1213): classInitNative: succeeds
D/HidService( 1213): Received start request. Starting profile...
I/bluedroid( 1213): get_profile_interface hidhost
I/bt-btif ( 1213): btif_hh_get_interface
I/bt-btif ( 1213): init
D/bt-btif ( 1213): btif_enable_service: current services:0x100048
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
I/BluetoothHealthServiceJni( 1213): classInitNative: succeeds
D/HealthService( 1213): Received start request. Starting profile...
I/bluedroid( 1213): get_profile_interface health
I/bt-btif ( 1213): btif_hl_get_interface
I/bt-btif ( 1213): init
D/bt-btif ( 1213): Process name (droid.bluetooth)
D/bt-btif ( 1213): btif_hl_soc_thread_init
D/bt-btif ( 1213): create_thread: entered
D/bt-btif ( 1213): create_thread: thread created successfully
I/LGBluetoothHealthServiceJni( 1213): classInitNative: succeeds
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
D/HeadsetStateMachine( 1213): Proxy object connected
I/BluetoothPanServiceJni( 1213): classInitNative(L105): succeeds
D/BluetoothPan(  957): BluetoothPAN Proxy object connected
D/PanService( 1213): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1213): initializeNative(L110): pan
I/bluedroid( 1213): get_profile_interface pan
D/bt-btif ( 1213): stack_initialized = 0, btpan_cb.enabled:0
I/BluetoothAdapterState( 1213): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/bt-btif ( 1213): entered btif_hl_select_thread
D/bt-btif ( 1213): btif_hl_select_wakeup_init
D/bt-btif ( 1213): btif_hl_select_wakeup_init signal_fds[0]=79 signal_fds[1]=80
D/bt-btif ( 1213): max_s=79 
D/bt-btif ( 1213): set curr_set = org_set 
E/BluetoothSettings_JNI( 2556): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
D/BluetoothTethering(  957): got CMD_CHANNEL_HALF_CONNECTED
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
D/BluetoothAdapterService(1116324896)( 1213): Message: 1
D/BluetoothAdapterService(1116324896)( 1213): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1213): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.hfp.BrcmHeadsetService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1213): Profile still not running:com.broadcom.bt.service.sap.SapService
D/LGBluetoothResetSettingReceiver( 2556): return without doing reset settings.
D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/HeadsetPhoneState( 1213): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 1213): Disconnected process message: 11
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
I/LGBluetoothMapAdapter( 1213): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 1213): BluetoothMapBinder()
D/BluetoothMapService( 1213): Received start request. Starting profile...
D/BluetoothMapService( 1213): start()
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
I/BtGatt.JNI( 1213): classInitNative(L685): classInitNative: Success!
D/BtGatt.DebugUtils( 1213): handleDebugAction() action=null
D/BtGatt.GattService( 1213): Received start request. Starting profile...
D/BtGatt.GattService( 1213): start()
I/bluedroid( 1213): get_profile_interface gatt
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
I/BluetoothSAPServiceJni( 1213): classInitNative(L170): succeeds
D/SapService( 1213): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1213): initializeNative(L175): sap
I/bluedroid( 1213): get_profile_interface sap
I/bt-btif ( 1213): btif_sc_get_interface
I/bt-btif ( 1213): init
D/bt-btif ( 1213): btif_enable_service: current services:0x120048
I/LGBluetoothSapAdapter( 1213): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1213): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 1213): [BTUI] initSapManager
D/LgeBluetoothSimManager( 1447): [BTUI] SAP_ENABLE_EVT
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
V/BluetoothFTPServiceJni( 1213): classInitNative
I/BluetoothFTPServiceJni( 1213): classInitNative(L271): succeeds
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
D/BluetoothFTPService( 1213): BluetoothFtpBinder()
D/**BluetoothFTPService( 1213): Received start request. Starting profile...
V/BluetoothFTPService( 1213): FTP-Server Service start
D/BluetoothFTPServiceJni( 1213): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1213): get_profile_interface ftp
I/bt-btif ( 1213): btif_fts_get_interface
I/bt-btif ( 1213): init
D/bt-btif ( 1213): btif_enable_service: current services:0x120148
D/BluetoothFTPServiceJni( 1213): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
D/BluetoothAdapterService(1116324896)( 1213): Message: 1
D/BluetoothAdapterService(1116324896)( 1213): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1213): onProfileServiceStateChange: serviceName=com.android.bluetooth.a2dp.A2dpService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1213): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116324896)( 1213): Message: 1
D/BluetoothAdapterService(1116324896)( 1213): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1213): onProfileServiceStateChange: serviceName=com.android.bluetooth.hid.HidService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1213): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116324896)( 1213): Message: 1
D/BluetoothAdapterService(1116324896)( 1213): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1213): onProfileServiceStateChange: serviceName=com.android.bluetooth.hdp.HealthService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1213): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116324896)( 1213): Message: 1
D/BluetoothAdapterService(1116324896)( 1213): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1213): onProfileServiceStateChange: serviceName=com.android.bluetooth.pan.PanService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1213): Profile still not running:com.broadcom.bt.service.sap.SapService
V/BluetoothMapService( 1213): Handler(): got msg=1
D/BluetoothAdapterService(1116324896)( 1213): Message: 1
D/BluetoothAdapterService(1116324896)( 1213): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1213): onProfileServiceStateChange: serviceName=com.android.bluetooth.map.BluetoothMapService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1213): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116324896)( 1213): Message: 1
D/BluetoothAdapterService(1116324896)( 1213): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1213): onProfileServiceStateChange: serviceName=com.android.bluetooth.gatt.GattService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1213): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116324896)( 1213): Message: 1
D/BluetoothAdapterService(1116324896)( 1213): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1213): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.sap.SapService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1213): Profile still not running:com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(1116324896)( 1213): Message: 1
D/BluetoothAdapterService(1116324896)( 1213): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1213): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.ftp.FTPService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1213): All profile services started.
D/BluetoothAdapterState( 1213): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1213): enable 1
I/bt-btif ( 1213): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1213): VERSION G2-AFBT-440-21_MI_00.02_OPP10 (BTE: BCM1200_PI_10.3.20.55)
I/GKI_LINUX( 1213): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
I/bt_hci_bdroid( 1213): init
I/bt_vendor( 1213): init
I/bt_vnd_conf( 1213): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 1213): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt-btif ( 1213): libbt-hci init returns 0
I/bt_hci_bdroid( 1213): bt_hc_worker_thread started
I/ActivityManager(  957): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4277 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/HyLog   ( 4277): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4277): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4277): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/AuthorizationBluetoothService( 1545): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  957): Killing 3175:com.android.mms/u0a35 (adj 15): empty #17
I/LocationManagerService(  957): remove 430bbac8
D/LocationManagerService(  957): provider request: passive ProviderRequest[ON interval=0]
,I/ConfigService( 1545): onDestroy
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:rfkill, action:3
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
D/CountryDetector(  957): No listener is left
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1151): usb Uevent not necessary.
,I/bt_userial_vendor( 1213): userial vendor open: opening /dev/ttyHS99
D/bt_userial_vendor( 1213): userial_vendor_open():UART is setup
,I/bt_userial_vendor( 1213): device fd = 84 open
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1137): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/WifiController(  957): battery changed pluggedType: 2
,D/bt_hwcfg( 1213): Chipset BCM4335A0
,D/bt_hwcfg( 1213): Target name = [BCM4335A0]
D/bt_hwcfg( 1213): Target name = [BCM4335]
I/bt_hwcfg( 1213): Found patchfile: /system/bin//BCM4335B0_002.001.006.0191.0201_ORC.hcd
,I/bt_hwcfg( 1213): Applying 4335 AXI BRIDGE patch...
,I/bt_hwcfg( 1213): bt vendor lib: set UART baud 4000000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/wpa_supplicant( 4232): netlink: Operstate: linkmode=1, operstate=5
,D/wpa_supplicant( 4232): nl80211: driver param='use_multi_chan_concurrent=1'
D/wpa_supplicant( 4232): nl80211: Use Multi channel concurrency
D/wpa_supplicant( 4232): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4232): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4232): nl80211: 2457-2482 @ 20 MHz
D/wpa_supplicant( 4232): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4232): nl80211: 5170-5250 @ 40 MHz
D/wpa_supplicant( 4232): nl80211: 5735-5835 @ 40 MHz
,D/wpa_supplicant( 4232): nl80211: Added 802.11b mode based on 802.11g information
,D/Tethering(  957): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering(  957): sendTetherStateChangedBroadcast 1, 0, 0
D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/UsbSettingsReceiver( 2556): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,I/bt_hwcfg( 1213): Releasing 4335 AXI BRIDGE lock
D/wpa_supplicant( 4232): wlan0: Own MAC address: 34:fc:ef:de:0a:e2
D/wpa_supplicant( 4232): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4232): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4232): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4232): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4232): wlan0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 4232): nl80211: Flush PMKIDs
,D/wpa_supplicant( 4232): wlan0: Setting scan request: 0 sec 100000 usec
D/UsbSettingsReceiver( 2556): [AUTORUN] sys.usb.config = boot,adb
D/UsbSettingsReceiver( 2556): [AUTORUN] sys.usb.state = boot,adb
,D/UsbSettingsReceiver( 2556): [AUTORUN] persist.sys.usb.config = boot,adb
D/UsbSettingsReceiver( 2556): [AUTORUN] onReceive() : app userid = 0, current userid = 0
,I/Config  ( 2556): getOperator() : OPEN
D/UsbSettingsControl( 2556): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 2556): [AUTORUN] onReceive() : availableList=[wlan0]
D/UsbSettingsReceiver( 2556): [AUTORUN] onReceive() : activeList=[]
,D/UsbSettingsReceiver( 2556): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 2556): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsReceiver( 2556): [AUTORUN] onReceive() : TetherState Changed=wlan0
,D/UsbSettingsControl( 2556): [AUTORUN] setTetherStatus() : status=false
,D/wpa_supplicant( 4232): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4232): TDLS: Driver uses internal link setup
D/wpa_supplicant( 4232): WPS: Set UUID for interface wlan0
,D/wpa_supplicant( 4232): WPS: UUID based on MAC address - hexdump(len=16): 4d 54 bb 4b f9 ab 59 64 88 e9 60 e7 bf 13 d1 db
,D/wpa_supplicant( 4232): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4232): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4232): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4232): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4232): Using existing control interface directory.
I/wpa_supplicant( 4232): 0xb8a34cc8 HY init priv-sock 18 p2p_disabled: 0 path: /data/misc/wifi/sockets/wlan0 name:/data/misc/wifi/sockets/wlan0 ctrl_interface: /data/misc/wifi/sockets, ifname: wlan0
I/wpa_supplicant( 4232): [ITEC] ASSIGN CALL BACK A4 5
I/wpa_supplicant( 4232): [ITEC] ASSIGN CALL BACK A1 6
D/wpa_supplicant( 4232): lge_eap_carrier_var_init
D/wpa_supplicant( 4232): realm format : @wlan.mnc<MNC>.mcc<MCC>.3gppnetwork.org 
D/wpa_supplicant( 4232): wlan0: Added interface wlan0
D/wpa_supplicant( 4232): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4232): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 4232): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4232): Override interface parameter: ctrl_interface ('(null)' -> '/data/misc/wifi/sockets')
D/wpa_supplicant( 4232): Initializing interface 'p2p0' conf '/data/misc/wifi/p2p_supplicant.conf' driver 'nl80211' ctrl_interface '/data/misc/wifi/sockets' bridge 'N/A'
D/wpa_supplicant( 4232): Configuration file '/data/misc/wifi/p2p_supplicant.conf' -> '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4232): Reading configuration file '/data/misc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4232): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4232): driver_param='use_p2p_group_interface=1use_multi_chan_concurrent=1'
D/wpa_supplicant( 4232): update_config=1
D/wpa_supplicant( 4232): device_name='Thali Test's G2'
D/wpa_supplicant( 4232): config_methods='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4232): p2p_ssid_postfix='-Thali Test's G2'
,D/wpa_supplicant( 4232): persistent_reconnect=1
,D/wpa_supplicant( 4232): Reading configuration file '/system/etc/wifi/p2p_supplicant.conf'
D/wpa_supplicant( 4232): update_config=1
D/wpa_supplicant( 4232): ctrl_interface='/data/misc/wifi/sockets'
D/wpa_supplicant( 4232): driver_param='use_p2p_group_interface=1 use_multi_chan_concurrent=1'
D/wpa_supplicant( 4232): eapol_version=1
D/wpa_supplicant( 4232): ap_scan=1
,D/wpa_supplicant( 4232): fast_reauth=1
D/wpa_supplicant( 4232): p2p_disabled=0
D/wpa_supplicant( 4232): p2p_no_group_iface=0
I/wpa_supplicant( 4232): rfkill: Cannot open RFKILL control device
D/wpa_supplicant( 4232): nl80211: RFKILL status not available
D/wpa_supplicant( 4232): nl80211: Using driver-based off-channel TX
D/wpa_supplicant( 4232): nl80211: TDLS supported
D/wpa_supplicant( 4232): nl80211: Use separate P2P group interface (driver advertised support)
D/wpa_supplicant( 4232): nl80211: Enable multi-channel concurrent (driver advertised support)
D/wpa_supplicant( 4232): nl80211: Driver is new enough to support monitor-less mode
D/wpa_supplicant( 4232): nl80211: interface p2p0 in phy phy0
D/wpa_supplicant( 4232): nl80211: Set mode ifindex 22 iftype 2 (STATION)
D/wpa_supplicant( 4232): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8a44c28
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a44c28
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a44c28
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a44c28
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a44c28
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a44c28
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a44c28
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a44c28
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a44c28
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a44c28
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a44c28
,D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 4232): netlink: Operstate: linkmode=1, operstate=5
D/wpa_supplicant( 4232): nl80211: driver param='use_p2p_group_interface=1use_multi_chan_concurrent=1'
D/wpa_supplicant( 4232): nl80211: Use separate P2P group interface
D/wpa_supplicant( 4232): nl80211: Use Multi channel concurrency
D/wpa_supplicant( 4232): nl80211: Regulatory information - country=00
D/wpa_supplicant( 4232): nl80211: 2402-2472 @ 40 MHz
D/wpa_supplicant( 4232): nl80211: 2457-2482 @ 20 MHz
D/wpa_supplicant( 4232): nl80211: 2474-2494 @ 20 MHz
D/wpa_supplicant( 4232): nl80211: 5170-5250 @ 40 MHz
D/wpa_supplicant( 4232): nl80211: 5735-5835 @ 40 MHz
,D/wpa_supplicant( 4232): nl80211: Added 802.11b mode based on 802.11g information
,D/wpa_supplicant( 4232): p2p0: Own MAC address: 36:fc:ef:de:0a:e2
D/wpa_supplicant( 4232): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4232): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4232): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4232): wpa_driver_nl80211_set_key: ifindex=22 (p2p0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4232): p2p0: RSN: flushing PMKID list in the driver
D/wpa_supplicant( 4232): nl80211: Flush PMKIDs
,D/wpa_supplicant( 4232): p2p0: State: DISCONNECTED -> INACTIVE
,D/wpa_supplicant( 4232): TDLS: TDLS operation supported by driver
D/wpa_supplicant( 4232): TDLS: Driver uses internal link setup
D/wpa_supplicant( 4232): WPS: Set UUID for interface p2p0
D/wpa_supplicant( 4232): WPS: UUID from the first interface - hexdump(len=16): 4d 54 bb 4b f9 ab 59 64 88 e9 60 e7 bf 13 d1 db
D/wpa_supplicant( 4232): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4232): EAPOL: KEY_RX entering state NO_KEY_RECEIVE
D/wpa_supplicant( 4232): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4232): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4232): Using existing control interface directory.
I/wpa_supplicant( 4232): 0xb8a44098 HY init priv-sock 23 p2p_disabled: 0 path: /data/misc/wifi/sockets/p2p0 name:/data/misc/wifi/sockets/p2p0 ctrl_interface: /data/misc/wifi/sockets, ifname: p2p0
I/wpa_supplicant( 4232): [ITEC] ASSIGN CALL BACK A4 5
I/wpa_supplicant( 4232): [ITEC] ASSIGN CALL BACK A1 6
I/wpa_supplicant( 4232): [ITEC] sizeof wpa_ssid: 544 / wpa_config: 504 / wpa_supplicant: 1456 / wpa_global: 208 in module
I/wpa_supplicant( 4232): [ITEC] Open WIFLUS socket interface - START
I/wpa_supplicant( 4232): [ITEC] SHARED LIBRARY INITIALIZED Ver: ITEC-LIB-VER-0.98 Tested @: JB44 Build Date Oct 16 2013 19:28:22
I/wpa_supplicant( 4232): [ITEC] USE NON-INET
I/wpa_supplicant( 4232): [ITEC] Open WIFLUS socket interface - DONE 24
I/wpa_supplicant( 4232): HY wiflus comm channel initialized
D/wpa_supplicant( 4232): P2P: Own listen channel: 6
I/wpa_supplicant( 4232): [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
D/wpa_supplicant( 4232): P2P: Random operating channel: 81:6
D/wpa_supplicant( 4232): P2P: Add operating class 81
D/wpa_supplicant( 4232): P2P: Channels - hexdump(len=13): 01 02 03 04 05 06 07 08 09 0a 0b 0c 0d
D/wpa_supplicant( 4232): P2P: Add operating class 115
,D/wpa_supplicant( 4232): P2P: Channels - hexdump(len=4): 24 28 2c 30
D/wpa_supplicant( 4232): P2P: wpas_p2p_pre_check_prefered_channel() - Invalid parameter. Just Initialized
D/wpa_supplicant( 4232): p2p0: Added interface p2p0
D/wpa_supplicant( 4232): p2p0: State: INACTIVE -> DISCONNECTED
D/wpa_supplicant( 4232): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
,D/wpa_supplicant( 4232): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4232): random: Got 20/20 bytes from /dev/random
,D/wpa_supplicant( 4232): Get randomness: len=20 entropy=0
D/wpa_supplicant( 4232): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
,D/wpa_supplicant( 4232): CTRL_IFACE monitor attached - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4232): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4232): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4232): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4232): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4232): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4232): RTM_NEWLINK: operstate=0 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/wpa_supplicant( 4232): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
D/wpa_supplicant( 4232): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4232): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4232): RTM_NEWLINK, IFLA_IFNAME: Interface 'p2p0' added
,D/wpa_supplicant( 4232): nl80211: if_removed already cleared - ignore event
,I/bt_hwcfg( 1213): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 1213): Settlement delay -- 100 ms
D/wpa_supplicant( 4232): wlan0: State: DISCONNECTED -> SCANNING
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): wlan0: Starting AP scan for wildcard SSID
D/wpa_supplicant( 4232): wlan0: nl80211: scan request
,D/wpa_supplicant( 4232): nl80211: Scan SSID - hexdump(len=0): [NULL]
D/WifiStateMachine(  957): transitionTo: destState=SupplicantStartingState
,D/WifiStateMachine(  957): handleMessage: new destination call exit/enter
D/WifiStateMachine(  957): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  957): invokeExitMethods: InitialState
D/wpa_supplicant( 4232): Scan requested (ret=0) - scan timeout 10 seconds
D/wpa_supplicant( 4232): nl80211: Event message available
D/wpa_supplicant( 4232): nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
,D/wpa_supplicant( 4232): wlan0: nl80211: Scan trigger
D/WifiStateMachine(  957): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine(  957): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStartingState
D/WifiStateMachine(  957): invokeEnterMethods: SupplicantStartingState
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=131144
D/WifiStateMachine(  957): processMsg: SupplicantStartingState
D/WifiStateMachine(  957): deferMessage: msg=131144
D/WifiStateMachine(  957): handleMessage: X
,D/WifiStateMachine(  957): handleMessage: E msg.what=131085
D/WifiStateMachine(  957): processMsg: SupplicantStartingState
D/WifiStateMachine(  957): deferMessage: msg=131085
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=131149
D/WifiStateMachine(  957): processMsg: SupplicantStartingState
D/WifiStateMachine(  957): processMsg: DefaultState
D/WifiStateMachine(  957): setSuspendOptimizations: 2 true
D/WifiStateMachine(  957): mSuspendOptNeedsDisabled 0
D/WifiStateMachine(  957): handleMessage: X
,D/WifiStateMachine(  957): handleMessage: E msg.what=131145
D/WifiStateMachine(  957): processMsg: SupplicantStartingState
D/WifiStateMachine(  957): processMsg: DefaultState
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=131146
D/WifiStateMachine(  957): processMsg: SupplicantStartingState
D/WifiStateMachine(  957): processMsg: DefaultState
,D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=131101
D/WifiStateMachine(  957): processMsg: SupplicantStartingState
,D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  957): processMsg: DefaultState
,D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=147457
D/WifiStateMachine(  957): processMsg: SupplicantStartingState
,D/WifiStateMachine(  957): Supplicant connection established
,D/WifiNative-wlan0(  957): doString: DRIVER MACADDR
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=14): 44 52 49 56 45 52 20 4d 41 43 41 44 44 52
,D/wpa_supplicant( 4232): wlan0: Control interface command 'DRIVER MACADDR'
,D/WifiNative-wlan0(  957):    returned Macaddr = 34:fc:ef:de:0a:e2
,D/WifiStateMachine(  957): MAC Addr from driver = 34:fc:ef:de:0a:e2
D/WifiStateMachine(  957): setWifiState: enabled
,D/WifiOffDelayIfNotUsed(  957): setPowerSaveActivated(false)
,W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiActivationWhileCharging(  957): unregister : we don't need to unregister
,E/WifiStateMachine(  957): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  957): useWiFiOffloading() : false
E/WifiStateMachine(  957): CONFIG_LGE_WLAN_PATH : true
,I/WifiServiceExtension(  957): WIFI_STATE_CHANGED_ACTION [3]
,D/WfdService( 1151): Waiting for WifiP2p enabling
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,I/WifiServiceExtension(  957): batteryPsActivateMsgHandler : state:0 event:3
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
,E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
,E/Parcel  (  511): Reading a NULL string not supported here.
,D/WifiConfigStore(  957): Loading config and enabling all networks
,D/WifiNative-wlan0(  957): doString: LIST_NETWORKS
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=13): 4c 49 53 54 5f 4e 45 54 57 4f 52 4b 53
,D/wpa_supplicant( 4232): wlan0: Control interface command 'LIST_NETWORKS'
,D/WifiNative-wlan0(  957):    returned network id / ssid / bssid / flags
D/WifiNative-wlan0(  957): 0	NG700	any	
,D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 ssid
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=18): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 73 69 64
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 ssid'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='ssid'
,D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 bssid
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 62 73 73 69 64
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 bssid'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='bssid'
D/wpa_supplicant( 4232): CTRL_IFACE: Failed to get network variable 'bssid'
,D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 priority
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 69 6f 72 69 74 79
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 priority'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='priority'
,D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 scan_ssid
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=23): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 63 61 6e 5f 73 73 69 64
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 scan_ssid'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='scan_ssid'
,D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 wep_tx_keyidx
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=27): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 74 78 5f 6b 65 79 69 64 78
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 wep_tx_keyidx'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='wep_tx_keyidx'
,D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 wep_key0
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 30
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 wep_key0'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='wep_key0'
D/wpa_supplicant( 4232): CTRL_IFACE: Failed to get network variable 'wep_key0'
,D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 wep_key1
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 31
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 wep_key1'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='wep_key1'
,D/wpa_supplicant( 4232): CTRL_IFACE: Failed to get network variable 'wep_key1'
D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 wep_key2
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 32
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 wep_key2'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='wep_key2'
,D/wpa_supplicant( 4232): CTRL_IFACE: Failed to get network variable 'wep_key2'
D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 wep_key3
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 77 65 70 5f 6b 65 79 33
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 wep_key3'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='wep_key3'
,D/wpa_supplicant( 4232): CTRL_IFACE: Failed to get network variable 'wep_key3'
D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 psk
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=17): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 73 6b
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 psk'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='psk'
,D/wpa_supplicant( 4232): Do not allow key_data field to be exposed
D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 proto
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 6f 74 6f
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 proto'
,D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='proto'
D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 key_mgmt
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 6b 65 79 5f 6d 67 6d 74
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 key_mgmt'
,D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='key_mgmt'
D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 auth_alg
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 61 75 74 68 5f 61 6c 67
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 auth_alg'
,D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='auth_alg'
D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 pairwise
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 61 69 72 77 69 73 65
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 pairwise'
,D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='pairwise'
,D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 group
,D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=19): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 67 72 6f 75 70
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 group'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='group'
D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 eap
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=17): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 61 70
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 eap'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='eap'
,D/wpa_supplicant( 4232): CTRL_IFACE: Failed to get network variable 'eap'
D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 phase2
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 68 61 73 65 32
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 phase2'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='phase2'
,D/wpa_supplicant( 4232): CTRL_IFACE: Failed to get network variable 'phase2'
D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 identity
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 69 64 65 6e 74 69 74 79
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 identity'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='identity'
,D/wpa_supplicant( 4232): CTRL_IFACE: Failed to get network variable 'identity'
D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 anonymous_identity
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=32): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 61 6e 6f 6e 79 6d 6f 75 73 5f 69 64 65 6e 74 69 74 79
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 anonymous_identity'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='anonymous_identity'
,D/wpa_supplicant( 4232): CTRL_IFACE: Failed to get network variable 'anonymous_identity'
D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 password
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=22): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 61 73 73 77 6f 72 64
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 password'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='password'
,D/wpa_supplicant( 4232): CTRL_IFACE: Failed to get network variable 'password'
D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 client_cert
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=25): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 63 6c 69 65 6e 74 5f 63 65 72 74
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 client_cert'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='client_cert'
,D/wpa_supplicant( 4232): CTRL_IFACE: Failed to get network variable 'client_cert'
D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 ca_cert
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=21): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 63 61 5f 63 65 72 74
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 ca_cert'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='ca_cert'
,D/wpa_supplicant( 4232): CTRL_IFACE: Failed to get network variable 'ca_cert'
D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 subject_match
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=27): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 73 75 62 6a 65 63 74 5f 6d 61 74 63 68
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 subject_match'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='subject_match'
,D/wpa_supplicant( 4232): CTRL_IFACE: Failed to get network variable 'subject_match'
,D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 engine
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 6e 67 69 6e 65
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 engine'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='engine'
D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 engine_id
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=23): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 65 6e 67 69 6e 65 5f 69 64
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 engine_id'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='engine_id'
,D/wpa_supplicant( 4232): CTRL_IFACE: Failed to get network variable 'engine_id'
D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 key_id
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 6b 65 79 5f 69 64
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 key_id'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='key_id'
,D/wpa_supplicant( 4232): CTRL_IFACE: Failed to get network variable 'key_id'
D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 phase1
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=20): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 68 61 73 65 31
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 phase1'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='phase1'
,D/wpa_supplicant( 4232): CTRL_IFACE: Failed to get network variable 'phase1'
D/WifiConfigStore(  957): ***WAPI : not WAPI
D/WifiNative-wlan0(  957): doString: GET_NETWORK 0 private_key
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=25): 47 45 54 5f 4e 45 54 57 4f 52 4b 20 30 20 70 72 69 76 61 74 65 5f 6b 65 79
D/wpa_supplicant( 4232): wlan0: Control interface command 'GET_NETWORK 0 private_key'
D/wpa_supplicant( 4232): CTRL_IFACE: GET_NETWORK id=0 name='private_key'
,D/wpa_supplicant( 4232): CTRL_IFACE: Failed to get network variable 'private_key'
,E/WifiConfigStore(  957): Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,D/PCSuite ( 4233): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/WifiNative-wlan0(  957): doBoolean: SET device_name g2_open_com
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=27): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 67 32 5f 6f 70 65 6e 5f 63 6f 6d
D/wpa_supplicant( 4232): wlan0: Control interface command 'SET device_name g2_open_com'
D/wpa_supplicant( 4232): CTRL_IFACE SET 'device_name'='g2_open_com'
,D/wpa_supplicant( 4232): device_name='g2_open_com'
D/WifiNative-wlan0(  957):    returned true
,D/WifiNative-wlan0(  957): doBoolean: SET manufacturer LGE
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=20): 53 45 54 20 6d 61 6e 75 66 61 63 74 75 72 65 72 20 4c 47 45
D/wpa_supplicant( 4232): wlan0: Control interface command 'SET manufacturer LGE'
D/wpa_supplicant( 4232): CTRL_IFACE SET 'manufacturer'='LGE'
,D/wpa_supplicant( 4232): manufacturer='LGE'
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiNative-wlan0(  957):    returned true
,D/WifiNative-wlan0(  957): doBoolean: SET model_name LG-D802
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=22): 53 45 54 20 6d 6f 64 65 6c 5f 6e 61 6d 65 20 4c 47 2d 44 38 30 32
D/wpa_supplicant( 4232): wlan0: Control interface command 'SET model_name LG-D802'
D/wpa_supplicant( 4232): CTRL_IFACE SET 'model_name'='LG-D802'
,D/wpa_supplicant( 4232): model_name='LG-D802'
D/WifiNative-wlan0(  957):    returned true
,D/WifiNative-wlan0(  957): doBoolean: SET model_number LG-D802
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=24): 53 45 54 20 6d 6f 64 65 6c 5f 6e 75 6d 62 65 72 20 4c 47 2d 44 38 30 32
D/wpa_supplicant( 4232): wlan0: Control interface command 'SET model_number LG-D802'
D/wpa_supplicant( 4232): CTRL_IFACE SET 'model_number'='LG-D802'
,D/wpa_supplicant( 4232): model_number='LG-D802'
D/WifiNative-wlan0(  957):    returned true
,D/WifiNative-wlan0(  957): doBoolean: SET serial_number 022678fb504e29b0
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=34): 53 45 54 20 73 65 72 69 61 6c 5f 6e 75 6d 62 65 72 20 30 32 32 36 37 38 66 62 35 30 34 65 32 39 ...
D/wpa_supplicant( 4232): wlan0: Control interface command 'SET serial_number 022678fb504e29b0'
D/wpa_supplicant( 4232): CTRL_IFACE SET 'serial_number'='022678fb504e29b0'
,D/wpa_supplicant( 4232): serial_number='022678fb504e29b0'
D/WifiNative-wlan0(  957):    returned true
,D/WifiNative-wlan0(  957): doBoolean: SET config_methods physical_display virtual_push_button keypad
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 70 68 79 73 69 63 61 6c 5f 64 69 73 70 ...
D/wpa_supplicant( 4232): wlan0: Control interface command 'SET config_methods physical_display virtual_push_button keypad'
D/wpa_supplicant( 4232): CTRL_IFACE SET 'config_methods'='physical_display virtual_push_button keypad'
,D/wpa_supplicant( 4232): config_methods='physical_display virtual_push_button keypad'
D/WifiNative-wlan0(  957):    returned true
,D/WifiNative-wlan0(  957): doBoolean: SET device_type 10-0050F204-5
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 4232): wlan0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 4232): CTRL_IFACE SET 'device_type'='10-0050F204-5'
,D/WifiNative-wlan0(  957):    returned true
D/WifiStateMachine(  957): transitionTo: destState=DriverStartedState
,D/WifiStateMachine(  957): handleMessage: new destination call exit/enter
D/WifiStateMachine(  957): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=3,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  957): invokeExitMethods: SupplicantStartingState
D/WifiStateMachine(  957): moveTempStackToStateStack: i=2,j=1
,D/WifiStateMachine(  957): moveTempStackToStateStack: i=1,j=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  957): moveTempStackToStateStack: i=0,j=3
D/WifiStateMachine(  957): moveTempStackToStateStack: X mStateStackTop=3,startingIndex=1,Top=DriverStartedState
D/WifiStateMachine(  957): invokeEnterMethods: SupplicantStartedState
D/WifiNative-wlan0(  957): doBoolean: SCAN_INTERVAL 15
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=16): 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c 20 31 35
D/wpa_supplicant( 4232): wlan0: Control interface command 'SCAN_INTERVAL 15'
D/wpa_supplicant( 4232): wlan0: Setting scan interval: 15 sec
W/Settings( 3242): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiNative-wlan0(  957):    returned true
D/WifiStateMachine(  957): invokeEnterMethods: DriverStartedStateExt
D/LGDMClient( 2797): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/WifiStateMachine(  957): invokeEnterMethods: DriverStartedState
D/WifiNative-wlan0(  957): doBoolean: DRIVER BTCOEXSCAN-STOP
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=22): 44 52 49 56 45 52 20 42 54 43 4f 45 58 53 43 41 4e 2d 53 54 4f 50
D/wpa_supplicant( 4232): wlan0: Control interface command 'DRIVER BTCOEXSCAN-STOP'
D/wpa_supplicant( 4232): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  957):    returned true
D/WifiStateMachine(  957): setDetailed state, old =IDLE and new state=DISCONNECTED
D/WifiNative-wlan0(  957): doBoolean: DRIVER RXFILTER-STOP
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=20): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 4f 50
D/wpa_supplicant( 4232): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 4232): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  957):    returned true
D/WifiNative-wlan0(  957): doBoolean: DRIVER RXFILTER-REMOVE 3
D/LGDMClient( 2797): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 52 45 4d 4f 56 45 20 33
D/wpa_supplicant( 4232): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 3'
D/wpa_supplicant( 4232): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  957):    returned true
D/WifiNative-wlan0(  957): doBoolean: DRIVER RXFILTER-START
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=21): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 41 52 54
D/wpa_supplicant( 4232): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 4232): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  957):    returned true
D/WifiNative-wlan0(  957): doBoolean: DRIVER RXFILTER-STOP
I/bt_hwcfg( 1213): bt vendor lib: set UART baud 4000000
I/bt_hwcfg( 1213): Setting local bd addr to 34:FC:EF:9D:93:0B
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=20): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 4f 50
D/wpa_supplicant( 4232): wlan0: Control interface command 'DRIVER RXFILTER-STOP'
D/wpa_supplicant( 4232): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  957):    returned true
D/WifiNative-wlan0(  957): doBoolean: DRIVER RXFILTER-REMOVE 2
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 52 45 4d 4f 56 45 20 32
D/wpa_supplicant( 4232): wlan0: Control interface command 'DRIVER RXFILTER-REMOVE 2'
D/wpa_supplicant( 4232): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  957):    returned true
D/WifiNative-wlan0(  957): doBoolean: DRIVER RXFILTER-START
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=21): 44 52 49 56 45 52 20 52 58 46 49 4c 54 45 52 2d 53 54 41 52 54
D/wpa_supplicant( 4232): wlan0: Control interface command 'DRIVER RXFILTER-START'
D/wpa_supplicant( 4232): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/WifiNative-wlan0(  957):    ,returned true
D/WifiStateMachine(  957): Attempting to reconnect to wifi network ..
D/WifiNative-wlan0(  957): doBoolean: RECONNECT
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=9): 52 45 43 4f 4e 4e 45 43 54
D/wpa_supplicant( 4232): wlan0: Control interface command 'RECONNECT'
D/WifiNative-wlan0(  957):    returned true
D/WifiNative-wlan0(  957): doString: STATUS
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 4232): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
D/WifiNative-wlan0(  957):    returned wpa_state=SCANNING
D/WifiNative-wlan0(  957): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  957): address=34:fc:ef:de:0a:e2
D/WifiStateMachine(  957): transitionTo: destState=DisconnectedState
D/WifiStateMachine(  957): handleScreenStateChanged: true
D/WifiNative-wlan0(  957): doBoolean: SET ps 1
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 4232): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 4232): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4232): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  957):    returned true
D/WifiP2pService(  957): P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  957): moveDeferredMessageAtFrontOfQueue; what=131085
D/WifiStateMachine(  957): moveDeferredMessageAtFrontOfQueue; what=131144
D/WifiStateMachine(  957): handleMessage: new destination call exit/enter
D/WifiStateMachine(  957): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=DriverStartedState,active=true,parent=DriverStartedStateExt
D/WifiStateMachine(  957): moveTempStackToStateStack: i=1,j=4
D/WifiStateMachine(  957): moveTempStackToStateStack: i=0,j=5
D/WifiStateMachine(  957): moveTempStackToStateStack: X mStateStackTop=5,startingIndex=4,Top=DisconnectedState
D/CommandListener(  264): Setting iface cfg
D/CommandListener(  264): Trying to bring up p2p0
D/WifiStateMachine(  957): invokeEnterMethods: ConnectModeState
,D/WifiStateMachine(  957): invokeEnterMethods: DisconnectedState
D/WifiMonitor(  957): WifiMonitorSingleton gotten
D/WifiStateMachine(  957): handleMessage: X
D/WifiMonitor(  957): startMonitoring(p2p0) with mConnected = true
D/WifiStateMachine(  957): handleMessage: E msg.what=131144
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=131085
,D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): processMsg: DriverStartedState
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=147462
D/WifiStateMachine(  957): processMsg: DisconnectedState
,D/WifiStateMachine(  957): setDetailed state, old =DISCONNECTED and new state=SCANNING
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=132106
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): processMsg: DriverStartedState
D/WifiStateMachine(  957): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  957): setWifiDualbandAPConnection band : 1
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=21): 44 55 41 4c 42 41 4e 44 5f 41 50 5f 43 4f 4e 4e 45 43 54 20 31
D/wpa_supplicant( 4232): wlan0: Control interface command 'DUALBAND_AP_CONNECT 1'
E/wpa_supplicant( 4232): nWIFIDualbandAPConnection: 1
,V/WfdStateTracker( 1151): WfdStateTracker handleDirectStateChangedEvent: 2
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=132096
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): processMsg: DriverStartedState
D/WifiStateMachine(  957): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  957): set CMD_DISCONNECT_RSSI_LVL : -100
D/WifiNative-p2p0(  957): doBoolean: SET persistent_reconnect 1
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=24): 44 49 53 43 4f 4e 4e 45 43 54 5f 52 53 53 49 5f 4c 56 4c 20 2d 31 30 30
D/wpa_supplicant( 4232): wlan0: Control interface command 'DISCONNECT_RSSI_LVL -100'
E/wpa_supplicant( 4232): disconnect_rssi_lvl: -100
D/WifiStateMachine(  957): handleMessage: X
,D/WifiStateMachine(  957): handleMessage: E msg.what=147462
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): setDetailed state, old =SCANNING and new state=SCANNING
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=131154
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
I/ActivityManager(  957): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4312 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/WifiP2pService(  957): P2pEnablingState
D/WifiP2pService(  957): P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  957): P2p socket connection successful
D/WifiP2pService(  957): P2pEnabledState
,D/WifiP2pService(  957): sending p2p connection changed broadcast
D/WifiStateMachine(  957): processMsg: DriverStartedState
D/WifiStateMachine(  957): processMsg: DriverStartedStateExt
D/WifiStateMachine(  957): processMsg: SupplicantStartedState
D/WifiStateMachine(  957): processMsg: DefaultState
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=131127
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=131158
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=26): 53 45 54 20 70 65 72 73 69 73 74 65 6e 74 5f 72 65 63 6f 6e 6e 65 63 74 20 31
D/wpa_supplicant( 4232): p2p0: Control interface command 'SET persistent_reconnect 1'
D/wpa_supplicant( 4232): CTRL_IFACE SET 'persistent_reconnect'='1'
D/wpa_supplicant( 4232): persistent_reconnect=1
D/wpa_supplicant( 4232): P2P: New SSID postfix: -Thali Test's G2
D/WifiStateMachine(  957): processMsg: DriverStartedState
D/WifiStateMachine(  957): setSuspendOptimizationsNative: 4 false
D/WifiStateMachine(  957): handleMessage: X
D/WifiNative-p2p0(  957):    returned true
D/WifiStateMachine(  957): handleMessage: E msg.what=143371
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiNative-p2p0(  957): doBoolean: SET device_name Thali Test's G2
D/WifiStateMachine(  957): processMsg: DriverStartedState
I/bt_hwcfg( 1213): vendor lib fwcfg completed
I/bt-btif ( 1213): HC preload_cb 0 [0:SUCCESS 1:FAIL]
D/WifiStateMachine(  957): processMsg: DriverStartedStateExt
D/WifiStateMachine(  957): processMsg: SupplicantStartedState
D/WifiStateMachine(  957): processMsg: DefaultState
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=31): 53 45 54 20 64 65 76 69 63 65 5f 6e 61 6d 65 20 54 68 61 6c 69 20 54 65 73 74 27 73 20 47 32
D/wpa_supplicant( 4232): p2p0: Control interface command 'SET device_name Thali Test's G2'
D/wpa_supplicant( 4232): CTRL_IFACE SET 'device_name'='Thali Test's G2'
D/wpa_supplicant( 4232): device_name='Thali Test's G2'
D/WifiStateMachine(  957): handleMessage: X
I/        ( 1213): BTE_InitTraceLevels -- TRC_HCI
I/        ( 1213): BTE_InitTraceLevels -- TRC_L2CAP
I/        ( 1213): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 1213): BTE_InitTraceLevels -- TRC_OBEX
D/WifiNative-p2p0(  957):    returned true
I/        ( 1213): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 1213): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 1213): BTE_InitTraceLevels -- TRC_A2D
I/        ( 1213): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 1213): BTE_InitTraceLevels -- TRC_BTM
I/        ( 1213): BTE_InitTraceLevels -- TRC_GAP
I/        ( 1213): BTE_InitTraceLevels -- TRC_PAN
I/        ( 1213): BTE_InitTraceLevels -- TRC_SAP
I/        ( 1213): BTE_InitTraceLevels -- TRC_SDP
I/        ( 1213): BTE_InitTraceLevels -- TRC_GATT
I/        ( 1213): BTE_InitTraceLevels -- TRC_SMP
I/        ( 1213): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 1213): BTE_InitTraceLevels -- TRC_BTIF
D/WifiServiceExtension(  957): postfix byte check : 15
I/        ( 1213): BTE_InitTraceLevels -- TRC_PROTOCOL
D/WifiNative-p2p0(  957): doBoolean: SET p2p_ssid_postfix -Thali Test's G2
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=37): 53 45 54 20 70 32 70 5f 73 73 69 64 5f 70 6f 73 74 66 69 78 20 2d 54 68 61 6c 69 20 54 65 73 74 ...
D/wpa_supplicant( 4232): p2p0: Control interface command 'SET p2p_ssid_postfix -Thali Test's G2'
D/wpa_supplicant( 4232): CTRL_IFACE SET 'p2p_ssid_postfix'='-Thali Test's G2'
D/wpa_supplicant( 4232): p2p_ssid_postfix='-Thali Test's G2'
D/wpa_supplicant( 4232): P2P: New SSID postfix: -Thali Test's G2
D/bt-btif ( 1213): btif_task(): received trigger stack init event, state: 1, radio_ref_count: 1, is_radio_req 0, dut_mode: 0
D/bt-btif ( 1213): btif,_dm_load_ble_local_keys BLE ER key loaded
D/bt-btif ( 1213): btif_dm_load_ble_local_keys BLE ID keys loaded
I/bt-btif ( 1213): bta_dm_sm_execute event:0x0
I/bt-btif ( 1213): bta_sys_sm_execute state:0, event:0x0
I/bt-btif ( 1213): bta_sys_hw_api_enable for 0, active modules 0x0001
I/bt-btif ( 1213): bta_sys_sm_execute state:1, event:0x1
I/bt-btif ( 1213): bta_sys_hw_evt_enabled for 0
D/WifiNative-p2p0(  957):    returned true
D/WifiNative-p2p0(  957): doBoolean: SET device_type 10-0050F204-5
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=29): 53 45 54 20 64 65 76 69 63 65 5f 74 79 70 65 20 31 30 2d 30 30 35 30 46 32 30 34 2d 35
D/wpa_supplicant( 4232): p2p0: Control interface command 'SET device_type 10-0050F204-5'
D/wpa_supplicant( 4232): CTRL_IFACE SET 'device_type'='10-0050F204-5'
D/WifiNative-p2p0(  957):    returned true
D/WifiNative-p2p0(  957): doBoolean: SET config_methods virtual_push_button physical_display keypad
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=62): 53 45 54 20 63 6f 6e 66 69 67 5f 6d 65 74 68 6f 64 73 20 76 69 72 74 75 61 6c 5f 70 75 73 68 5f ...
D/wpa_supplicant( 4232): p2p0: Control interface command 'SET config_methods virtual_push_button physical_display keypad'
D/wpa_supplicant( 4232): CTRL_IFACE SET 'config_methods'='virtual_push_button physical_display keypad'
D/wpa_supplicant( 4232): config_methods='virtual_push_button physical_display keypad'
D/WifiNative-p2p0(  957):    returned true
D/WifiNative-p2p0(  957): doBoolean: P2P_SET conc_pref sta
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=21): 50 32 50 5f 53 45 54 20 63 6f 6e 63 5f 70 72 65 66 20 73 74 61
D/wpa_supplicant( 4232): p2p0: Control interface command 'P2P_SET conc_pref sta'
D/wpa_supplicant( 4232): Single channel concurrency preference: sta
D/WifiNative-p2p0(  957):    returned true
D/WifiNative-p2p0(  957): doString: STATUS
,D/wpa_supplicant( 4232): RX global ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/WifiNative-p2p0(  957):    returned p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-p2p0(  957): p2p_state=IDLE
D/WifiNative-p2p0(  957): wifi_display=1
D/WifiNative-p2p0(  957): ifname=p2p0
D/WifiNative-p2p0(  957): address=36:fc:ef:de:0a:e2
D/WifiNative-p2p0(  957): ifname=wlan0
D/WifiNative-p2p0(  957): address=34:fc:ef:de:0a:e2
,D/WifiNative-p2p0(  957): doBoolean: P2P_FLUSH
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=9): 50 32 50 5f 46 4c 55 53 48
D/wpa_supplicant( 4232): p2p0: Control interface command 'P2P_FLUSH'
D/wpa_supplicant( 4232): P2P: Stopping find
D/wpa_supplicant( 4232): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 4232): P2P: State IDLE -> IDLE
D/wpa_supplicant( 4232): wpa_driver_set_ap_wps_p2p_ie: Entry
D/WifiNative-p2p0(  957):    returned true
D/WifiNative-p2p0(  957): doBoolean: P2P_SERVICE_FLUSH
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=17): 50 32 50 5f 53 45 52 56 49 43 45 5f 46 4c 55 53 48
D/wpa_supplicant( 4232): p2p0: Control interface command 'P2P_SERVICE_FLUSH'
D/WifiNative-p2p0(  957):    returned true
,D/WifiNative-p2p0(  957): doString: LIST_NETWORKS
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=13): 4c 49 53 54 5f 4e 45 54 57 4f 52 4b 53
D/wpa_supplicant( 4232): p2p0: Control interface command 'LIST_NETWORKS'
D/WifiNative-p2p0(  957):    returned network id / ssid / bssid / flags
D/WifiNative-p2p0(  957): doBoolean: SAVE_CONFIG
I/WfdStateTracker( 1151): handleP2pThisDeviceChanged
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=11): 53 41 56 45 5f 43 4f 4e 46 49 47
D/wpa_supplicant( 4232): p2p0: Control interface command 'SAVE_CONFIG'
,D/wpa_supplicant( 4232): Writing configuration file '/data/misc/wifi/p2p_supplicant.conf.tmp'
D/WifiP2pService(  957): [LGE_P2P] initializeP2pSettings() check postfix
D/WifiP2pService(  957): before postfix = Thali Test's G2
D/WifiP2pService(  957): after postfix = Thali Test's G2
D/WifiP2pService(  957): DeviceAddress: 36:fc:ef:de:0a:e2
D/wpa_supplicant( 4232): Configuration file '/data/misc/wifi/p2p_supplicant.conf' written successfully
,D/wpa_supplicant( 4232): CTRL_IFACE: SAVE_CONFIG - Configuration updated
,D/WifiNative-p2p0(  957):    returned true
,E/WifiServiceExtension(  957): No p2p device connected
D/WifiP2pService(  957): sending p2p persistent groups changed broadcast
D/WifiP2pService(  957): InactiveState
D/WifiP2pService(  957): InactiveState{ when=-11ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  957): P2pEnabledState{ when=-11ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  957): DefaultState{ when=-11ms what=139287 arg2=1 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  957): InactiveState{ when=-11ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  957): P2pEnabledState{ when=-11ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  957): DefaultState{ when=-11ms what=139283 arg2=2 target=com.android.internal.util.StateMachine$SmHandler }
D/bt-btif ( 1213):  bta_sys_hw_btm_cback was called with parameter: 0
I/bt-btif ( 1213): bta_sys_sm_execute state:1, event:0x2
D/bt-btif ( 1213):  bta_sys_hw_evt_stack_enabled!notify the callers
D/bt-btif ( 1213):  bta_dm_sys_hw_cback with event: 1
D/bt-btif ( 1213): ##################################
D/bt-btif ( 1213): bta_dm_co_ble_load_local_keys:  Load local keys if any are persisted
D/bt-btif ( 1213): ##################################
D/bt-btif ( 1213): btif_dm_get_ble_local_keys  *p_key_mask=0x03
E/bt-btm  ( 1213): BTM_SecRegister:p_cb_info->p_le_callback == 0x60b5c4c5 
I/bt-smp  ( 1213): SMP_Register state=0
E/bt-btm  ( 1213): BTM_SecRegister: btm_cb.api.p_le_callback = 0x60b5c4c5 
D/bt-btif ( 1213): bta_gattc_register state 0
D/bt-btif ( 1213): bta_gattc_enable
I/bt-att  ( 1213): GATT_Register
D/bt-att  ( 1213): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 1213): allocated gatt_if=3
D/bt-btif ( 1213): bta_dm_gattc_callback event = 0
D/bt-btif ( 1213): BTA_GATTC_REG_EVT client_if = 3
I/bt-att  ( 1213): GATT_StartIf gatt_if=3
D/bt-att  ( 1213): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 1213): gatt_find_the_connected_bda found=0 found_idx=7
D/HyLog   ( 4312): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4312): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4312): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 4312): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.wifi.supplicant.CONNECTION_CHANGE
W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/ActivityManager(  957): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4328 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  957): Killing 3242:com.google.android.talk/u0a77 (adj 15): empty #17
,D/HyLog   ( 4328): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4328): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4328): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,I/Wireless_Storage( 4328): CONNECT : WIFI_P2P_STATE_CHANGED_ACTION
V/[BNRBootReceiver]( 4061): boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,D/BNRAndroBeam( 4061): [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,I/ActivityManager(  957): Killing 4005:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,I/bt-btif ( 1213): btif_dm_upstreams_cback  ev: BTA_DM_ENABLE_EVT
,D/bt-btif ( 1213): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1213): in, bd addr:, prop type:1, len:249
I/bt-btif ( 1213): bta_dm_sm_execute event:0x2
D/bt-btif ( 1213): BTA is generating EIR
D/bt-sdp  ( 1213): SDP_CreateRecord ok, num_records:3
I/bt-btif ( 1213): Adding UUID=0x110C into EIR
D/bt-btif ( 1213): BTA is generating EIR
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00001000
D/bt-btif ( 1213): nsc_mask: 0x6
D/bt-btif ( 1213): bta_av_co_audio_init
D/bt-btif ( 1213): bta_av_co_audio_init: 0
D/bt-btif ( 1213): audio[0] av_handle: 1 codec_type: 0
D/bt-btif ( 1213): bta_av_co_audio_init
D/bt-btif ( 1213): bta_av_co_audio_init: 1
D/bt-btif ( 1213): BTIF_APTX_CODEC_ID:6
D/bt-btif ( 1213): audio[1] av_handle: 2 codec_type: 255
,D/bt-sdp  ( 1213): SDP_CreateRecord ok, num_records:4
I/bt-a2d  ( 1213): getAccess buffer->st_uid:1000 buff
D/bt-btif ( 1213): getAccess buffer->st_uid:1000 buffer->st_gid:1028
I/bt-btif ( 1213): Adding UUID=0x110A into EIR
D/bt-btif ( 1213): BTA is generating EIR
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00001400
I/bt-btif ( 1213): FTP SERVER enabled with Root Path [/storage]
E/bt-btif ( 1213): Calling BTA_HhEnable
D/bt-btif ( 1213): Calling BTA_HhEnable
D/bt-btif ( 1213): in add:1
D/bt-btif ( 1213): create 0, role: 1, shdl:0, rc_handle:0, lidx:3, status:0x10
D/bt-btif ( 1213): reg_audio: 0x1
D/bt-btif ( 1213): reg_audio: 0x1
D/bt-btif ( 1213): Remote device:f8:95:c7:87:3c:51, size:18
D/bt-btif ( 1213): bta_ag_scb_alloc 1
D/bt-btif ( 1213): bta_ag_scb_alloc 1
I/bt-btif ( 1213): Remote device:b0:c5:59:3f:75:69, size:18
D/bt-btif ( 1213): Remote device:b0:c5:59:3f:75:69, size:18
D/bt-sdp  ( 1213): Remote device:14:b4:84:21:3b:49, s
D/bt-btif ( 1213): bta_ag_add_record uuid: 1112
,D/bt-btif ( 1213): bta_ag_add_record uuid: 1112
I/bt-btif ( 1213): Remote device:80:01:84:8a:b
D/bt-btif ( 1213): Remote device:80:01:84:8a:b3:68, size:18
D/bt-btif ( 1213): BTA is generating EIR
I/bt-btif ( 1213): Remote device:58:3f:54:73:64:c0, size:18
D/bt-sdp  ( 1213): SDP_CreateRecord ok, num_records:6
D/bt-btif ( 1213): SDP_CreateRecord ok, num_records:6
D/bt-btif ( 1213): bta_ag_add_record uuid: 111f
D/bt-btif ( 1213): Remote device:10:d3:8a:fb:85:d4, size:18
I/bt-btif ( 1213): Adding UUID=0x111F into EIR
D/bt-btif ( 1213): BTA is generating EIR
D/bt-btif ( 1213): BTA is generating EIR
D/bt-btif ( 1213): Remote device:08:ec:a9:50:75:41, size:18
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000000 04011400
D/bt-btif ( 1213): Remote device:f8:cf:c5:d9:e5:61, size:18
D/bt-btif ( 1213): Remote device:08:ec:a9:50:76:27, size:18
D/bt-btif ( 1213): bta_fts_api_enable srm:1
D/bt-btif ( 1213): Remote device:7c:f9:0e:51:18:22, size:18
D/bt-btif ( 1213): Remote device:44:80:eb:7b:5a:05, size:18
D/bt-btif ( 1213): SDP_CreateRecord ok, num_records:7
D/bt-sdp  ( 1213): SDP_CreateRecord ok, num_records:7
D/bt-btif ( 1213): Remote device:7c:f9:0e:37:96:ab, size:18
,D/bt-btif ( 1213): Remote device:f4:f1:e1:5c:3b:e2, size:18
I/bt-btif ( 1213): Remote device:f4:f1:e1:5c:3b:e2, size:18
D/bt-btif ( 1213): BTA is generating EIR
D/bt-btif ( 1213): BTA is generating EIR
I/bt-btif ( 1213): Remote device:f8:95:c7:87:85:54, size:18
D/bt-btif ( 1213): FTS:  SDP Registered (handle 0x00010006)
D/bt-btif ( 1213): Remote device:7c:f9:0e:34:8a:a0, size:18
I/bt-btif ( 1213): bta_fts_ci_resume status:1
D/bt-sdp  ( 1213): SDP_CreateRecord ok, num_records:8
,I/bt-btif ( 1213): Adding UUID=0x112D into EIR
D/bt-btif ( 1213): BTA is generating EIR
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04011440
D/bt-btif ( 1213): bte_sap_evt: event=0
D/bt-btif ( 1213): bte_sap_evt: event=0
D/bt-btif ( 1213): Remote device:e0:db:10:14:e2:c0, size:18
D/bt-btif ( 1213): Remote device:34:fc:ef:11:b1:66, size:18
D/bt-btif ( 1213): Remote device:90:e7:c4:f6:69:77, size:18
D/bt-btif ( 1213): bta_gattc_register state 2
I/bt-att  ( 1213): Remote device
D/bt-att  ( 1213): UUID=[0x0000454c205245564f20484820415442]
,I/bt-att  ( 1213): allocated gatt_if=4
D/bt-btif ( 1213): bta_hh_gattc_callback event = 0
I/bt-att  ( 1213): GATT_StartIf gatt_if=4
D/bt-att  ( 1213): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 1213): gatt_find_the_connected_bda found=0 found_idx=7
D/bt-btif ( 1213): gatt_find_the_connected_bda found=0 foun
D/bt-btif ( 1213): Remote device:58:2a:f7:ed:96:be, size:18
D/bt-btif ( 1213): Remote device:38:94:96:b5:06:dc, size:18
D/bt-btif ( 1213): bta_dm_sm_execute event:
I/bt-btif ( 1213): ## btif_config_getevent:0x9
E/bt-btif ( 1213): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
,E/bt-btif ( 1213): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
D/bt-btif ( 1213): out
D/bt-btif ( 1213): btif_storage_get_adapter_property property->type:2 
D/bt-btif ( 1213): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1213): in, bd addr:, prop type:1, len:249
I/bt-btif ( 1213): btif_storage_load_bonded_devices  BT_PROPERTY_DEVICE_MODE
D/bt-btif ( 1213): btif_storage_get_adapter_property property->type:16 
D/bt-btif ( 1213): in, bd addr:, prop type:16, len:4
E/bt-btif ( 1213): Unknow prop type:16
I/bt-btif ( 1213): btif_dm_get_adapter_property: type=0x10
,D/bt-btif ( 1213): btif_dm_get_adapter_property btif_device_mode 0
D/bt-btif ( 1213): btif_storage_get_adapter_property property->type:9 
D/bt-btif ( 1213): in, bd addr:, prop type:9, len:4
D/bt-btif ( 1213): btif_storage_get_adapter_property property->type:3 
E/bt-btif ( 1213): btif_storage_get_adapter_property service_mask:0x120148
D/bt-btif ( 1213): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1213): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1213): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1213): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1213): btif_storage_get_adapter_property property->type:3 devicemode 0
,I/bt-btif ( 1213): HAL bt_hal_cbacks->adapter_properties_cb
E/BluetoothAdapterProperties( 1213): Property change not handled in Java land:16
I/bt-btif ( 1213): btif_storage_load_bonded_devices: 1 bonded devices found
D/bt-btif ( 1213): in, bd addr:38:94:96:b5:06:dc, prop type:1, len:249
D/bt-btif ( 1213): in, bd addr:38:94:96:b5:06:dc, prop type:10, len:249
D/bt-btif ( 1213): in, bd addr:38:94:96:b5:06:dc, prop type:4, len:4
D/bt-btif ( 1213): in, bd addr:38:94:96:b5:06:dc, prop type:5, len:4
D/bt-btif ( 1213): in, bd addr:38:94:96:b5:06:dc, prop type:3, len:512,
I/bt-btif ( 1213): HAL bt_hal_cbacks->remote_device_properties_cb
E/BluetoothRemoteDevices( 1213): devicePropertyChangedCallback: bdDevice: 38:94:96:B5:06:DC, value is empty for type: 10
D/BluetoothManagerService(  957): Bluetooth Adapter name changed to Thali Test's G2
,D/BluetoothManagerService(  957): Stored Bluetooth name: Thali Test's G2
I/LGRemoteDevicePropertySetting( 1213): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1213): [BTUI] Get BRCM HeadsetService
D/bt-btif ( 1213): btif_enable_bluetooth_evt: status 0, local bd [34:fc:ef:9d:93:0b]
,I/bt-btif ( 1213): HC lib lpm enable=1 return 0
I/bt-btif ( 1213): BTA_BrcmInit
D/IOP_DB_BT( 1213): db_open: file /etc/bluetooth/iop_bt.db
E/bt_hwcfg( 1213): hw_sco_config...
,E/bt_hwcfg( 1213): SCO PCM configure {0, 4, 0, 0, 0}
D/IOP_DB_BT( 1213): db_open: db_open : handle 1623497260l, read 7547 bytes onto local cache
D/IOP_DB_BT( 1213): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 1213): db_query: result 1
I/        ( 1213): iop_db_open: iop_db_open status 0
D/bt-btif ( 1213): btsock initializing...
D/bt-btif ( 1213): in initialized:1
D/bt-btif ( 1213): ts[7].used:1
D/bt-btif ( 1213): ts[6].used:0
D/bt-btif ( 1213): alloc_thread_slot ret:6
D/bt-btif ( 1213): h:6, cmd_fdr:87, cmd_fdw:88
D/bt-btif ( 1213): h:6, thread id:1626646000
,I/bt-btif ( 1213): HC lpm_result_cb 1
I/bt-btif ( 1213): BTA_JvEnable
D/bt-btif ( 1213): btsock successfully initialized
D/bt-btif ( 1213): jni_initialized = 1, btpan_cb.enabled:0
D/bt-btif ( 1213): Enabling PAN....
D/bt-btif ( 1213): local_role:3
D/bt-btif ( 1213): btpan_role:0x3
I/bte_conf( 1213): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/bt-btif ( 1213): jv_dm_cback: event:0, slot id:0
D/bt-btif ( 1213): unhandled event:0, slot id:0
I/bt-btif ( 1213): bta_pan_co_init
D/bt-sdp  ( 1213): SDP_CreateRecord ok, num_records:9
I/bt-btif ( 1213): Adding UUID=0x1116 into EIR
D/bt-btif ( 1213): BTA is generating EIR
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04051440
I/bt-btif ( 1213): Adding UUID=0x1115 into EIR
D/bt-btif ( 1213): BTA is generating EIR
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1213): Adding UUID=0x1116 into EIR
D/bt-btif ( 1213): BTA is generating EIR
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1213): Removing UUID=0x1117 from EIR
D/bt-btif ( 1213): BTA is generating EIR
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1213): Adding UUID=0x1115 into EIR
D/bt-btif ( 1213): BTA is generating EIR
,I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bte_conf( 1213): [1] primary_record=1 vendor_id=0x00C4 vendor_id_source=0x0001 product_id=0x13A1 version=0x1000
I/bte_conf( 1213): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bt-btif ( 1213): bta_dm_sm_execute event:0x31
D/bt-sdp  ( 1213): SDP_CreateRecord ok, num_records:10
I/bt-btif ( 1213): Adding UUID=0x1200 into EIR
D/bt-btif ( 1213): BTA is generating EIR
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000084 04071440
I/bt-btif ( 1213): bte did registered::handle: 0x10009, bta status: 0 (0==OK)
I/bte_conf( 1213): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/bt-btif ( 1213): btif_dm_load_local_oob prop_oob = 3
I/bt-btif ( 1213): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothServiceJni( 1213): adapter_state_change_callback: Status is: 1
D/bt-btif ( 1213): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/bt-btif ( 1213): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
D/bt-btif ( 1213): btif_av_state_idle_handler devicemode: 0
D/bt-btif ( 1213): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
D/bt-btif ( 1213): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 1213): btif_fts_upstreams_evt: event=BTA_FTS_ENABLE_EVT
I/bt-btif ( 1213): File Transfer: Enable Complete
I/bt-btif ( 1213): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 1213): operation_cmpl_callback(L192):  oper:3 status:0
I/BluetoothFTPService( 1213): onFtpServerEnabled: /storage
D/bt-btif ( 1213): btif_sc_upstreams_evt: event=BTA_SC_ENABLE_EVT
D/bt-btif ( 1213): btif_hh_upstreams_evt: event=BTA_HH_ENABLE_EVT
D/bt-btif ( 1213): btif_hh_upstreams_evt: BTA_HH_ENABLE_EVT: status =0
D/bt-btif ( 1213): btif_hh_upstreams_evt--Loading added devices
D/bt-btif ( 1213): Remote device:00:f4:6f:30:e0:6c, size:18
D/bt-btif ( 1213): Remote device:f8:95:c7:87:3c:51, size:18
D/bt-btif ( 1213): Remote device:e0:db:10:1f:c9:5e, size:18
D/bt-btif ( 1213): Remote device:b0:c5:59:3f:75:69, size:18
D/bt-btif ( 1213): Remote device:14:b4:84:21:3b:49, size:18
D/bt-btif ( 1213): Remote device:80:01:84:8a:b3:68, size:18
D/bt-btif ( 1213): Remote device:58:3f:54:73:64:c0, size:18
D/bt-btif ( 1213): Remote device:10:d3:8a:fb:85:d4, size:18
D/bt-btif ( 1213): Remote device:b4:ce:f6:ab:a4:6a, size:18
D/bt-btif ( 1213): Remote device:08:ec:a9:50:75:41, size:18
D/bt-btif ( 1213): Remote device:f8:cf:c5:d9:e5:61, size:18
D/bt-btif ( 1213): Remote device:08:ec:a9:50:76:27, size:18
D/bt-btif ( 1213): Remote device:7c:f9:0e:51:18:22, size:18
D/bt-btif ( 1213): Remote device:44:80:eb:7b:5a:05, size:18
D/bt-btif ( 1213): Remote device:50:2e:6c:ac:21:50, size:18
D/bt-btif ( 1213): Remote device:7c:f9:0e:37:96:ab, size:18
D/bt-btif ( 1213): Remote device:f4:f1:e1:5c:3b:e2, size:18
D/bt-btif ( 1213): Remote device:34:fc:ef:11:ae:67, size:18
D/bt-btif ( 1213): Remote device:f8:95:c7:87:85:54, size:18
D/bt-btif ( 1213): Remote device:7c:f9:0e:34:8a:a0, size:18
D/bt-btif ( 1213): Remote device:e0:db:10:14:e2:c0, size:18
D/bt-btif ( 1213): Remote device:34:fc:ef:11:b1:66, size:18
D/bt-btif ( 1213): Remote device:90:e7:c4:f6:69:77, size:18
D/bt-btif ( 1213): Remote device:90:e7:c4:3c:62:6a, size:18
D/bt-btif ( 1213): Remote device:58:2a:f7:ed:96:be, size:18
D/bt-btif ( 1213): Remote device:38:94:96:b5:06:dc, size:18
D/bt-btif ( 1213): Remote device:, size:18
E/bt-btif ( 1213): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
D/bt-btif ( 1213): BTA_PAN_ENABLE_EVT
D/bt-btif ( 1213): bta_pan_role:0x5
D/BluetoothPanServiceJni( 1213): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
D/BluetoothAdapterState( 1213): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 1213): ScanMode =  20
D/BluetoothAdapterProperties( 1213): State =  11
D/BluetoothAdapterProperties( 1213): mDiscoverableTimeout =  120
I/bt-btif ( 1213): btif_s,et_adapter_property type: 7, len 4, 0x428fe780
I/bt-btif ( 1213): set property scan mode : 1
I/bt-btif ( 1213): btif_in_storage_request_copy_cb
I/bt-btif ( 1213): bta_dm_sm_execute event:0x3
I/bt-btif ( 1213): btif_set_adapter_property type: 9, len 4, 0x428fe7d8
I/bt-btif ( 1213): btif_in_storage_request_copy_cb
I/BluetoothAdapterState( 1213): Bluetooth adapter state changed: 11-> 12
D/BluetoothAdapterService( 1213): Broadcasting updateAdapterState() to 1 receivers.
V/BluetoothAdapterService( 1213): startPbapService
D/BluetoothManagerService(  957): Message: 60
D/BluetoothManagerService(  957): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  957): Broadcasting onBluetoothStateChange(true) to 6 receivers.
D/BluetoothPan(  957): onBluetoothStateChange(on) call bindService
I/bt-btif ( 1213): execute storage request event : 2
I/bt-btif ( 1213): type: 7, len 4, 0x60ab203a
D/bt-btif ( 1213): in, bd addr:, prop type:7, len:4
I/bt-btif ( 1213): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothHeadset(  957): onBluetoothStateChange: up=true
I/bt-btif ( 1213): execute storage request event : 2
I/bt-btif ( 1213): type: 9, len 4, 0x60ab2086
D/bt-btif ( 1213): in, bd addr:, prop type:9, len:4
I/bt-btif ( 1213): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothHeadset( 1447): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1447): onBluetoothStateChange: up=true
D/BluetoothA2dp(  957): onBluetoothStateChange: up=true
D/BluetoothHeadset( 1447): onBluetoothStateChange: up=true
,D/BluetoothManagerService(  957): Bluetooth State Change Intent: 11 -> 12
,D/LGBluetoothAPIService( 1151): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,W/ContextImpl(  957): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:192 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:510 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1164 
I/BluetoothAdapterState( 1213): Entering On State
D/LGBluetoothServiceAdapter( 1213): [BTUI] OnState
D/LGBluetoothServiceAdapter( 1213): [BTUI]         global_name: Thali Test's G2
D/LGBluetoothServiceAdapter( 1213): [BTUI]         local_name: Thali Test's G2
D/BluetoothAdapterService(1116324896)( 1213): Get Bonded Devices being called
D/LGBluetoothAPIService( 1151): Message: 1
D/LGBluetoothAPIService( 1151): MESSAGE_BOOT_COMPLETED
D/BluetoothAdapterService(1116324896)( 1213): Quiet mode Enabled = false
D/BluetoothAdapterService(1116324896)( 1213): Initiate auto connection on BT on...
,D/BluetoothAdapterService( 1213): [BTUI] autoConnect() : not allowed
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
I/LGBluetoothAPIService( 1151): [BTUI] LGBluetoothAPIService Binding Success
V/BluetoothPbapService( 1213): Pbap Service onCreate
,V/BluetoothPbapService( 1213): Starting PBAP service
,D/LGBluetoothPbapAdapter( 1213): [BTUI] getInstance : create
V/BluetoothPbapService( 1213): action: android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapService( 1213): state: 12
,W/ContextImpl( 2556): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:156 com.android.settings.bluetooth.DockEventReceiver.onReceive:123 
D/BluetoothMapService( 1213): onReceive
D/BluetoothManagerService(  957): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothMapService( 1213): STATE_ON
D/BluetoothManagerService(  957): Message: 40
D/BluetoothManagerService(  957): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/LGBluetoothAPIServer( 1213): [BTUI] onCreate()
D/LGBluetoothAPIServer( 1213): [BTUI] onBind()
V/BluetoothPbapReceiver( 1213): PbapReceiver onReceive 
D/LGBluetoothAPIService( 1151): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
V/BluetoothPbapReceiver( 1213): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1151): Message: 100
D/LGBluetoothAPIService( 1151): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothPbapReceiver( 1213): ***********state = 12
V/BluetoothPbapService( 1213): Handler(): got msg=1
V/BluetoothPbapService( 1213): Pbap Service startRfcommSocketListener
V/BluetoothPbapService( 1213): Pbap Service initSocket
V/BluetoothMapService( 1213): Handler(): got msg=1
D/BluetoothMapService( 1213): Map Service startRfcommSocketListener
D/BluetoothMapService( 1213): Map Service initSocket
D/LocalBluetoothProfileManager( 2556): Adding local A2DP profile
,D/BluetoothManagerService(  957): Message: 30
D/bt_h4   ( 1213): vendor lib postload completed
I/bt-btif ( 1213): HC postload_cb 0
,D/BluetoothManagerService(  957): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothManagerService(  957): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,W/BluetoothAdapter( 1213): getBluetoothService() called with no BluetoothManagerCallback
,W/ContextImpl( 2556): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1207 
D/LocalBluetoothProfileManager( 2556): Adding local HEADSET profile
E/BluetoothServiceJni( 1213): SOCK FLAG = 1 ***********************
D/bt-btif ( 1213): btsock_rfc_listen, service_name:MAP SMS/MMS
D/bt-btif ( 1213): BTA_JvCreateRecordByUser:MAP SMS/MMS
I/bt-btif ( 1213): BTA_JvCreateRecordByUser
D/bt-btif ( 1213): jv_dm_cback: event:11, slot id:1
D/bt-btif ( 1213): name:MAP SMS/MMS, scn:6
D/LGBluetoothServiceAdapter( 1213): [BTUI] createSocketChannel FD=90 mFd=0
D/bt-btif ( 1213): add_maps_sdd:scn 6, service name MAP SMS/MMS
D/bt-sdp  ( 1213): SDP_CreateRecord ok, num_records:11
W/BluetoothAdapter( 1213): getBluetoothService() called with no BluetoothManagerCallback
I/bt-btif ( 1213): Adding UUID=0x1132 into EIR
D/bt-btif ( 1213): BTA is generating EIR
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000484 04071440
D/bt-btif ( 1213): MAPSS:  SDP Registered (handle 0x0001000a)
I/bt-btif ( 1213): BTA_JvRfcommStartServer
D/bt-btif ( 1213): bta_jv_rfcomm_start_server: sec id in use:0, rfc_cb in use:0
D/bt-btif ( 1213): bta_jv_alloc_rfc_cb port_handle:6 handle:0x81
V/BluetoothMapService( 1213): Succeed to create listening socket 
D/BluetoothMapService( 1213): Accepting socket connection...
D/BluetoothManagerService(  957): Message: 30
E/BluetoothServiceJni( 1213): SOCK FLAG = 1 ***********************
D/bt-btif ( 1213): btsock_rfc_listen, service_name:OBEX Phonebook Access Server
D/bt-btif ( 1213): BTA_JvCreateRecordByUser:OBEX Phonebook Access Server
I/bt-btif ( 1213): BTA_JvCreateRecordByUser
D/bt-btif ( 1213): jv_dm_cback: event:11, slot id:2
D/bt-btif ( 1213): name:OBEX Phonebook Access Server, scn:19
D/bt-btif ( 1213): add_pbap_sdd:scn 19, service name OBEX Phonebook Access Server
D/bt-sdp  ( 1213): SDP_CreateRecord ok, num_records:12
I/bt-btif ( 1213): Adding UUID=0x112F into EIR
D/bt-btif ( 1213): BTA is generating EIR
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04071440
D/bt-btif ( 1213): PBS:  SDP Registered (handle 0x0001000b)
I/bt-btif ( 1213): BTA_JvRfcommStartServer
D/bt-btif ( 1213): bta_jv_rfcomm_start_server: sec id in use:1, rfc_cb in use:1
D/bt-btif ( 1213): bta_jv_alloc_rfc_cb port_handle:7 handle:0x82
D/LGBluetoothServiceAdapter( 1213): [BTUI] createSocketChannel FD=92 mFd=90
V/BluetoothPbapService( 1213): Succeed to create listening socket 
,V/BluetoothPbapService( 1213): Accepting socket connection...
,D/BluetoothManagerService(  957): Message: 30
,D/BluetoothManagerService(  957): Message: 30
W/ContextImpl( 2556): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1204 
W/ContextImpl( 2556): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1210 
,W/ContextImpl( 2556): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1213 
D/LocalBluetoothProfileManager( 2556): Adding local MAP profile
D/BluetoothMap( 2556): Create BluetoothMap proxy object
,D/BluetoothManagerService(  957): Message: 30
,D/BluetoothManagerService(  957): Message: 30
,D/LocalBluetoothProfileManager( 2556): LocalBluetoothProfileManager construction complete
,V/BluetoothPbapService( 1213): Pbap Service onBind
W/ContextImpl( 2556): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1219 
W/ContextImpl( 2556): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:72 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1137): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/dalvikvm(  957): GC_EXPLICIT freed 22763K, 49% free 28996K/56776K, paused 2ms+7ms, total 128ms
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1213): Disconnected process message: 10
,D/LGBluetoothUserBindClient( 2556): [BTUI] initUserBindClient
D/WifiController(  957): battery changed pluggedType: 2
,W/ContextImpl( 2556): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/DockEventReceiver( 2556): finishStartingService: stopping service
D/BluetoothA2dp( 2556): Proxy object connected
D/A2dpProfile( 2556): Bluetooth service connected
D/BluetoothHeadset( 2556): Proxy object connected
D/HeadsetProfile( 2556): Bluetooth service connected
D/BluetoothInputDevice( 2556): Proxy object connected
D/HidProfile( 2556): Bluetooth service connected
D/BluetoothPan( 2556): BluetoothPAN Proxy object connected
D/PanProfile( 2556): Bluetooth service connected
D/BluetoothMap( 2556): Proxy object connected
D/MapProfile( 2556): Bluetooth service connected
D/BluetoothMap( 2556): getConnectedDevices()
V/BluetoothMapService( 1213): getConnectedDevices()
D/BluetoothPbap( 2556): Proxy object connected
D/PbapServerProfile( 2556): Bluetooth service connected
D/LGBluetoothUserBindClient( 2556): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 2556): onReceive
D/LGBluetoothFeatureConfig( 2556): isPrivacyLogsEnabled : true
E/LGBluetoothUtils( 2556): [BTUI] FileNotFoundException: readPropertyjava.io.FileNotFoundException: /data/misc/bluedroid/bluetooth_property.conf: open failed: ENOENT (No such file or directory)
D/LGBluetoothResetSettingReceiver( 2556): return without doing reset settings.
V/BluetoothOppReceiver( 1213): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 1213): [BTUI] startOppService()
,V/BluetoothOppManager( 1213): restoreApplicationData! falsefalsenullnull
,D/LGBluetoothFeatureConfig( 1213): isPrivacyLogsEnabled : true
V/BtOppService( 1213): onCreate
,D/LGBluetoothOppAdapter( 1213): [BTUI] getInstance : create [LGBluetoothOppAdapter]
,V/BluetoothOppNotification( 1213): send message
,V/BtOppService( 1213): Starting RfcommListener
D/BluetoothOppPreference( 1213): Dumping Names:  
D/BluetoothOppPreference( 1213): {}
D/BluetoothOppPreference( 1213): Dumping Channels:  
,D/BluetoothOppPreference( 1213): {}
,V/BtOppService( 1213): onStartCommand
,V/BtOppService( 1213): pendingUpdate is true keepUpdateThread is false sListenStarted is true
,V/BluetoothOppNotification( 1213): new notify threadi!
,V/BluetoothOppNotification( 1213): send delay message
,V/BtOppService( 1213): start RfcommListener
,V/BtOppService( 1213): RfcommListener started
,V/BtOppRfcommListener( 1213): Starting RFCOMM listener....
,V/BluetoothOppProvider( 1213): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/BluetoothManagerService(  957): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,V/BtOppService( 1213): ContentObserver received notification
,V/BtOppService( 1213): Deleted complete outbound shares, number =  0
,V/BluetoothOppProvider( 1213): created cursor android.database.sqlite.SQLiteCursor@4292f6c0 on behalf of 
V/BtOppService( 1213): ContentObserver received notification
V/BtOppService( 1213): Deleted complete inbound failed shares, number = 0
V/BluetoothOppProvider( 1213): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,W/BluetoothAdapter( 1213): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1213): SOCK FLAG = 0 ***********************
D/bt-btif ( 1213): btsock_rfc_listen, service_name:OBEX Object Push
D/bt-btif ( 1213): BTA_JvCreateRecordByUser:OBEX Object Push
I/bt-btif ( 1213): BTA_JvCreateRecordByUser
D/bt-btif ( 1213): jv_dm_cback: event:11, slot id:3
D/bt-btif ( 1213): name:OBEX Object Push, scn:12
D/bt-btif ( 1213): scn 12, service name OBEX Object Push
D/bt-sdp  ( 1213): SDP_CreateRecord ok, num_records:13
,D/LGBluetoothServiceAdapter( 1213): [BTUI] createSocketChannel FD=96 mFd=92
I/bt-btif ( 1213): Adding UUID=0x1105 into EIR
D/bt-btif ( 1213): BTA is generating EIR
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04071460
I/bt-btif ( 1213): BTA_JvRfcommStartServer
D/bt-btif ( 1213): bta_jv_rfcomm_start_server: sec id in use:2, rfc_cb in use:2
D/bt-btif ( 1213): bta_jv_alloc_rfc_cb port_handle:8 handle:0x83
D/AuthorizationBluetoothService( 1545): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
V/BtOppRfcommListener( 1213): Started RFCOMM listener....
I/BtOppRfcommListener( 1213): Accept thread started.
V/BtOppRfcommListener( 1213): Accepting connection...
,E/AuthorizationBluetoothService( 1545): Proximity feature is not enabled.
,V/BluetoothOppProvider( 1213): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1213): created cursor android.database.sqlite.SQLiteCursor@42933b60 on behalf of 
,V/BtOppService( 1213): pendingUpdate is true keepUpdateThread is false sListenStarted is true
,V/BluetoothOppProvider( 1213): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1213): created cursor android.database.sqlite.SQLiteCursor@429355a0 on behalf of 
,V/BluetoothOppProvider( 1213): created cursor android.database.sqlite.SQLiteCursor@429341c8 on behalf of 
V/BluetoothOppNotification( 1213): mUpdateCompleteNotification = true
,V/BluetoothOppNotification( 1213): update too frequent, put in queue
V/BtOppService( 1213): pendingUpdate is false keepUpdateThread is false sListenStarted is true
,V/BluetoothOppProvider( 1213): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1213): created cursor android.database.sqlite.SQLiteCursor@42937e40 on behalf of 
,V/BluetoothOppNotification( 1213): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 1213): outbound notification was removed.
,V/BluetoothOppProvider( 1213): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1213): created cursor android.database.sqlite.SQLiteCursor@42939bb8 on behalf of 
,V/BluetoothOppNotification( 1213): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 1213): inbound notification was removed.
,V/BluetoothOppProvider( 1213): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1213): created cursor android.database.sqlite.SQLiteCursor@4293b2a0 on behalf of 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 4232): EAPOL: disable timer tick
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4232): EAPOL: disable timer tick
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.451279 Y: -0.388351 Z: 9.748215 
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.451279 .y:-0.388351 .z:9.748215
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.466736 Y: -0.390244 Z: 9.742050 
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.466736 .y:-0.390244 .z:9.742050
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,D/WifiController(  957): battery changed pluggedType: 2
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1137): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1213): Disconnected process message: 10
,D/WifiController(  957): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1137): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1213): Disconnected process message: 10
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/BluetoothOppNotification( 1213): new notify threadi!
,V/BluetoothOppNotification( 1213): send delay message
,V/BluetoothOppProvider( 1213): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1213): created cursor android.database.sqlite.SQLiteCursor@4293daf0 on behalf of 
,V/BluetoothOppNotification( 1213): mUpdateCompleteNotification = true
,V/BluetoothOppProvider( 1213): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1213): created cursor android.database.sqlite.SQLiteCursor@4293f728 on behalf of 
,V/BluetoothOppNotification( 1213): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 1213): outbound notification was removed.
,V/BluetoothOppProvider( 1213): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1213): created cursor android.database.sqlite.SQLiteCursor@429412b8 on behalf of 
,V/BluetoothOppNotification( 1213): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 1213): inbound notification was removed.
,V/BluetoothOppProvider( 1213): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1213): created cursor android.database.sqlite.SQLiteCursor@42942860 on behalf of 
,V/AudioFlinger(  271): releaseWakeLock_l() AudioOut_2
,V/AudioFlinger(  271): releaseWakeLock_l() AudioOut_3
,V/AudioFlinger(  271): thread 0xb2589008 type 0 TID 998 going to sleep
,V/AudioFlinger(  271): thread 0xb26f4008 type 0 TID 938 going to sleep
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  957): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1137): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1213): Disconnected process message: 10
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/wpa_supplicant( 4232): nl80211: Event message available
D/wpa_supplicant( 4232): nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
,D/wpa_supplicant( 4232): wlan0: nl80211: New scan results available
D/wpa_supplicant( 4232): wlan0: Event SCAN_RESULTS (3) received
D/wpa_supplicant( 4232): nl80211: Received scan results (9 BSSes)
D/wpa_supplicant( 4232): nl80211: Survey data missing
D/wpa_supplicant( 4232): wlan0: BSS: Start scan result update 1
D/wpa_supplicant( 4232): wlan0: BSS: Add new id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g'
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): wlan0: BSS: Add new id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700'
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): wlan0: BSS: Add new id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC'
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): wlan0: BSS: Add new id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos'
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): wlan0: BSS: Add new id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600'
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): wlan0: BSS: Add new id 5 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698'
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 4232): wlan0: BSS: Add new id 6 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free'
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): wlan0: BSS: Add new id 7 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025'
,D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): wlan0: BSS: Add new id 8 BSSID 0c:bd:51:2b:c1:25 SSID 'PLAY-ONLINE_1167',
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): BSS: last_scan_res_used=9/32 last_scan_full=0
D/wpa_supplicant( 4232): wlan0: New scan results available
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): WPS: AP c0:ff:d4:d3:aa:4a type 0 added
D/wpa_supplicant( 4232): WPS: AP c0:ff:d4:d3:aa:48 type 0 added
D/wpa_supplicant( 4232): WPS: AP a0:c5:62:7a:49:97 type 0 added
D/wpa_supplicant( 4232): WPS: AP 64:7c:34:12:7f:81 type 0 added
D/wpa_supplicant( 4232): WPS: AP 9e:93:4e:3e:ba:c5 type 1 added
D/wpa_supplicant( 4232): WPS: AP 0c:bd:51:2b:c1:25 type 0 added
,D/wpa_supplicant( 4232): WPS: AP[0] c0:ff:d4:d3:aa:4a type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4232): WPS: AP[1] c0:ff:d4:d3:aa:48 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4232): WPS: AP[2] a0:c5:62:7a:49:97 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4232): WPS: AP[3] 64:7c:34:12:7f:81 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4232): WPS: AP[4] 9e:93:4e:3e:ba:c5 type=1 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4232): WPS: AP[5] 0c:bd:51:2b:c1:25 type=0 tries=0 last_attempt=-1 sec ago blacklist=0
D/wpa_supplicant( 4232): wlan0: Selecting BSS from priority group 1
D/wpa_supplicant( 4232): wlan0: 0: c0:ff:d4:d3:aa:4a ssid='NG7005g' wpa_ie_len=0 rsn_ie_len=20 caps=0x511 level=-52 wps
,D/wpa_supplicant( 4232): wlan0:    skip - SSID mismatch
D/wpa_supplicant( 4232): wlan0: 1: c0:ff:d4:d3:aa:48 ssid='NG700' wpa_ie_len=0 rsn_ie_len=20 caps=0x431 level=-55 wps
D/wpa_supplicant( 4232): wlan0:    selected based on RSN IE
D/wpa_supplicant( 4232): wlan0:    selected BSS c0:ff:d4:d3:aa:48 ssid='NG700'
D/wpa_supplicant( 4232): wpa_supplicant_check_mdm_ac_policy policy: 0,
,D/wpa_supplicant( 4232): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4232): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4232): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4232): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4232): wlan0: [MDM] lg mdm allow/disallow auto connect is not set 
D/wpa_supplicant( 4232): wlan0: Considering connect request: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING  ssid=0xb8a365a8  current_ssid=0x0
,D/wpa_supplicant( 4232): wlan0: Selected network is configured to use SIM (sim=1 aka=1) - initialize PCSC
E/wpa_supplicant( 4232): USIM:  scard_init function
D/wpa_supplicant( 4232): wlan0: [Events.c:1455]Request association: reassociate: 0  selected: c0:ff:d4:d3:aa:48  bssid: 00:00:00:00:00:00  pending: 00:00:00:00:00:00  wpa_state: SCANNING
D/wpa_supplicant( 4232): wpa_supplicant_check_mdm_ac_policy policy: 0
D/wpa_supplicant( 4232): wlan0: [MDM] lg_mdm_auto_connect_policy 0
D/wpa_supplicant( 4232): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=7): 00 05 4e 47 37 30 30
D/wpa_supplicant( 4232): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 03 01 01
,D/wpa_supplicant( 4232): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=3): 2a 01 00
D/wpa_supplicant( 4232): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4232): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 4232): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4232): TDLS: TDLS is allowed in the target BSS
I/wpa_supplicant( 4232): Trying to associate with c0:ff:d4:d3:aa:48 (SSID='NG700' freq=2412 MHz)
,D/wpa_supplicant( 4232): wlan0: Cancelling scan request
D/wpa_supplicant( 4232): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4232): wlan0: WPA: clearing own WPA/RSN IE
D/wpa_supplicant( 4232): wlan0: Automatic auth_alg selection: 0x1
D/wpa_supplicant( 4232): RSN: PMKSA cache search - network_ctx=0xb8a365a8 try_opportunistic=0
D/wpa_supplicant( 4232): RSN: Search for BSSID c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4232): RSN: No PMKSA cache entry found
D/wpa_supplicant( 4232): wlan0: RSN: using IEEE 802.11i/D9.0
,D/wpa_supplicant( 4232): wlan0: WPA: Selected cipher suites: group 16 pairwise 16 key_mgmt 2 proto 2
D/wpa_supplicant( 4232): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 4232): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4232): wlan0: WPA: using GTK CCMP
D/wpa_supplicant( 4232): wlan0: WPA: using PTK CCMP
D/wpa_supplicant( 4232): wlan0: WPA: using KEY_MGMT WPA-PSK
D/wpa_supplicant( 4232): WPA: Set own WPA IE default - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4232): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 drv_flags:0x808e2c0
D/wpa_supplicant( 4232): [LGE_P2P] wpas_p2p_assoc_req_ie() ifname:wlan0 skip P2PIE
,D/wpa_supplicant( 4232): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 4232): wlan0: State: SCANNING -> ASSOCIATING
D/wpa_supplicant( 4232): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4232): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): Limit connection to BSSID c0:ff:d4:d3:aa:48 freq=2412 MHz based on scan results (bssid_set=0)
D/wpa_supplicant( 4232): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 4232): nl80211: Unsubscribe mgmt frames handle 0xb8a35590 (mode change)
D/wpa_supplicant( 4232): nl80211: Subscribe to mgmt frames with non-AP handle 0xb8a35590
,D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a35590
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=2): 04 0a
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a35590
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=2): 04 0b
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a35590
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=2): 04 0c
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a35590
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=2): 04 0d
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a35590
,D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=6): 04 09 50 6f 9a 09
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a35590
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=5): 7f 50 6f 9a 09
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a35590
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=2): 04 0e
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a35590
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=1): 06
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a35590
,D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=2): 0a 07
D/wpa_supplicant( 4232): nl80211: Register frame type=0xd0 nl_handle=0xb8a35590
D/wpa_supplicant( 4232): nl80211: Register frame match - hexdump(len=2): 0a 11
D/wpa_supplicant( 4232): nl80211: Connect (ifindex=23)
D/wpa_supplicant( 4232):   * bssid=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4232):   * freq=2412
D/wpa_supplicant( 4232):   * SSID - hexdump(len=5): 4e 47 37 30 30
D/wpa_supplicant( 4232):   * IEs - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4232):   * Auth Type 0
,D/wpa_supplicant( 4232):   * WPA Versions 0x2
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 0 c0:ff:d4:d3:aa:4a]
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 1 c0:ff:d4:d3:aa:48]
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 2 c2:ff:d4:d3:aa:48]
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 3 38:f8:89:11:e9:11]
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 4 a0:c5:62:7a:49:97]
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 5 64:7c:34:12:7f:81]
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 6 06:7c:34:12:7f:81]
,D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 7 9e:93:4e:3e:ba:c5]
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-ADDED 8 0c:bd:51:2b:c1:25]
D/WifiMonitor(  957): Event [IFNAME=wlan0 WPS-AP-AVAILABLE-AUTH ]
W/WifiMonitor(  957): couldn't identify event type - WPS-AP-AVAILABLE-AUTH 
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
D/WifiStateMachine(  957): handleMessage: E msg.what=147461
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): processMsg: DriverStartedState
D/WifiStateMachine(  957): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  957): processMsg: SupplicantStartedState
D/WifiNative-wlan0(  957): doString: BSS RANGE=0- MASK=0x21987
D/wpa_supplicant( 4232): nl80211: Connect request send successfully
D/wpa_supplicant( 4232): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4232): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4232): EAPOL: External notification - EAP fail=0
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4232): EAPOL: External notification - portControl=Auto
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4232): RSN: Ignored PMKID candidate without preauth flag
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=25): 42 53 53 20 52 41 4e 47 45 3d 30 2d 20 4d 41 53 4b 3d 30 78 32 31 39 38 37
D/wpa_supplicant( 4232): wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
D/wpa_supplicant( 4232): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4232): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
,D/wpa_supplicant( 4232): nl80211: if_removed already cleared - ignore event
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=147462
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): setDetailed state, old =SCANNING and new state=CONNECTING
D/WifiStateMachine(  957): processMsg: ConnectModeState
,D/WifiStateMachine(  957): handleMessage: X,
,D/wpa_supplicant( 4232): nl80211: Event message available,
D/wpa_supplicant( 4232): nl80211: Drv Event 46 (NL80211_CMD_CONNECT) received for wlan0
D/wpa_supplicant( 4232): nl80211: Connect event
D/wpa_supplicant( 4232): nl80211: Associated on 2412 MHz
D/wpa_supplicant( 4232): nl80211: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4232): nl80211: Operating frequency for the associated BSS from scan results: 2412 MHz
D/wpa_supplicant( 4232): wlan0: Event ASSOC (0) received
D/wpa_supplicant( 4232): wlan0: Association info event
D/wpa_supplicant( 4232): req_ies - hexdump(len=101): 00 05 4e 47 37 30 30 01 08 82 84 8b 96 24 30 48 6c 21 02 ff 11 24 02 01 0d 30 14 01 00 00 0f ac ...
D/wpa_supplicant( 4232): resp_ies - hexdump(len=206): 01 08 82 84 8b 0c 12 96 18 24 32 04 30 48 60 6c 2d 1a 2c 00 1b ff ff 00 00 00 00 00 00 00 00 00 ...,
D/wpa_supplicant( 4232): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=24): 3d 16 01 00 05 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4232): WPA: Unrecognized EAPOL-Key Key Data IE - hexdump(len=16): 4a 0e 14 00 0a 00 2c 01 c8 00 14 00 05 00 19 00
D/wpa_supplicant( 4232): wlan0: freq=2412 MHz
D/wpa_supplicant( 4232): WPA: set own WPA/RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4232): wlan0: State: ASSOCIATING -> ASSOCIATED
D/wpa_supplicant( 4232): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4232): netlink: Operstate: linkmode=-1, operstate=5
,D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): wlan0: Associated to a new BSS: BSSID=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4232): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 4232): wlan0: WPA: clearing AP WPA IE
D/wpa_supplicant( 4232): WPA: set AP RSN IE - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
I/wpa_supplicant( 4232): wlan0: Associated with c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
D/wpa_supplicant( 4232): scard is not null..
,D/wpa_supplicant( 4232): wlan0: WPA: Association event - clear replay counter
D/wpa_supplicant( 4232): wlan0: WPA: Clear old PTK
D/wpa_supplicant( 4232): TDLS: Remove peers on association
D/wpa_supplicant( 4232): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4232): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4232): EAPOL: External notification - EAP success=0
,D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4232): EAPOL: External notification - portEnabled=1
D/wpa_supplicant( 4232): EAPOL: SUPP_PAE entering state CONNECTING
D/wpa_supplicant( 4232): EAPOL: enable timer tick
D/wpa_supplicant( 4232): EAPOL: SUPP_BE entering state IDLE
,D/wpa_supplicant( 4232): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4232): wlan0: Cancelling scan request
D/wpa_supplicant( 4232): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4232): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4232): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4232): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4232): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP])
D/wpa_supplicant( 4232): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4232): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4232): RTM_NEWLINK: operstate=0 ifi_flags=0x11003 ([UP][LOWER_UP]),
D/wpa_supplicant( 4232): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4232): nl80211: if_removed already cleared - ignore event
D/WifiMonitor(  957): Event [IFNAME=wlan0 Associated with c0:ff:d4:d3:aa:48]
W/WifiMonitor(  957): couldn't identify event type - Associated with c0:ff:d4:d3:aa:48
D/WifiStateMachine(  957): handleMessage: E msg.what=147462
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): setDetailed state, old =CONNECTING and new state=CONNECTING
D/WifiStateMachine(  957): processMsg: ConnectModeState
,D/WifiStateMachine(  957): handleMessage: X
,D/wpa_supplicant( 4232): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4232): RX EAPOL - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 ff 5b 8d 52 52 8a 58 05 cf 03 81 87 cf 6d ce ...
D/wpa_supplicant( 4232): wlan0: Setting authentication timeout: 10 sec 0 usec
D/wpa_supplicant( 4232): wlan0: IEEE 802.1X RX: version=2 type=3 length=95
D/wpa_supplicant( 4232): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 4232): wlan0:   key_info 0x8a (ver=2 keyidx=0 rsvd=0 Pairwise Ack)
D/wpa_supplicant( 4232): wlan0:   key_length=16 key_data_length=0
D/wpa_supplicant( 4232):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 4232):   key_nonce - hexdump(len=32): ff 5b 8d 52 52 8a 58 05 cf 03 81 87 cf 6d ce e5 80 68 b0 26 38 29 1f 9a cf 37 22 3b bc 9f b8 f0
D/wpa_supplicant( 4232):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4232):   key_rsc - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4232):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4232):   key_mic - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4232): WPA: RX EAPOL-Key - hexdump(len=99): 02 03 00 5f 02 00 8a 00 10 00 00 00 00 00 00 00 01 ff 5b 8d 52 52 8a 58 05 cf 03 81 87 cf 6d ce ...
D/wpa_supplicant( 4232): wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): wlan0: WPA: RX message 1 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 4232): RSN: msg 1/4 key data - hexdump(len=0):
D/wpa_supplicant( 4232): Get randomness: len=32 entropy=10
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  957): handleMessage: E msg.what=147462
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): setDetailed state, old =CONNECTING and new state=AUTHENTICATING
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): handleMessage: X
D/wpa_supplicant( 4232): WPA: Renewed SNonce - hexdump(len=32): d5 0a cc a4 fc 73 29 6c 94 52 19 25 69 08 a2 c2 06 62 07 9e 7b 00 62 b1 ab 13 22 37 e9 6a f2 55
D/wpa_supplicant( 4232): WPA: PTK derivation - A1=34:fc:ef:de:0a:e2 A2=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4232): WPA: Nonce1 - hexdump(len=32): d5 0a cc a4 fc 73 29 6c 94 52 19 25 69 08 a2 c2 06 62 07 9e 7b 00 62 b1 ab 13 22 37 e9 6a f2 55
D/wpa_supplicant( 4232): WPA: Nonce2 - hexdump(len=32): ff 5b 8d 52 52 8a 58 05 cf 03 81 87 cf 6d ce e5 80 68 b0 26 38 29 1f 9a cf 37 22 3b bc 9f b8 f0
D/wpa_supplicant( 4232): WPA: PMK - hexdump(len=32): [REMOVED]
D/wpa_supplicant( 4232): WPA: PTK - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 4232): WPA: WPA IE for msg 2/4 - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4232): WPA: Replay Counter - hexdump(len=8): 00 00 00 00 00 00 00 01
D/wpa_supplicant( 4232): wlan0: WPA: Sending EAPOL-Key 2/4
D/wpa_supplicant( 4232): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4232): WPA: Derived Key MIC - hexdump(len=16): 38 d3 6d 1e 0c 29 aa 91 ae dd 11 c5 a5 39 88 d9
,D/wpa_supplicant( 4232): WPA: TX EAPOL-Key - hexdump(len=121): 01 03 00 75 02 01 0a 00 00 00 00 00 00 00 00 00 01 d5 0a cc a4 fc 73 29 6c 94 52 19 25 69 08 a2 ...
,D/wpa_supplicant( 4232): wlan0: RX EAPOL from c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4232): RX EAPOL - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 ff 5b 8d 52 52 8a 58 05 cf 03 81 87 cf 6d ce ...
D/wpa_supplicant( 4232): wlan0: IEEE 802.1X RX: version=2 type=3 length=151
D/wpa_supplicant( 4232): wlan0:   EAPOL-Key type=2
D/wpa_supplicant( 4232): wlan0:   key_info 0x13ca (ver=2 keyidx=0 rsvd=0 Pairwise Install Ack MIC Secure Encr)
D/wpa_supplicant( 4232): wlan0:   key_length=16 key_data_length=56
D/wpa_supplicant( 4232):   replay_counter - hexdump(len=8): 00 00 00 00 00 00 00 02
D/wpa_supplicant( 4232):   key_nonce - hexdump(len=32): ff 5b 8d 52 52 8a 58 05 cf 03 81 87 cf 6d ce e5 80 68 b0 26 38 29 1f 9a cf 37 22 3b bc 9f b8 f0
D/wpa_supplicant( 4232):   key_iv - hexdump(len=16): 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4232):   key_rsc - hexdump(len=8): e2 3d 00 00 00 00 00 00
D/wpa_supplicant( 4232):   key_id (reserved) - hexdump(len=8): 00 00 00 00 00 00 00 00
D/wpa_supplicant( 4232):   key_mic - hexdump(len=16): 4b 5a 1f 53 e8 05 64 e1 59 b8 fa e9 e9 94 02 39
D/wpa_supplicant( 4232): WPA: RX EAPOL-Key - hexdump(len=155): 02 03 00 97 02 13 ca 00 10 00 00 00 00 00 00 00 02 ff 5b 8d 52 52 8a 58 05 cf 03 81 87 cf 6d ce ...
D/wpa_supplicant( 4232): RSN: encrypted key data - hexdump(len=56): 0b 98 da 42 1a dd 48 83 b7 97 5b 27 46 04 df 2b e2 e4 c7 2a 43 f2 e2 d9 79 51 52 d9 5a a8 91 d6 ...
D/wpa_supplicant( 4232): WPA: decrypted EAPOL-Key key data - hexdump(len=48): [REMOVED]
D/wpa_supplicant( 4232): wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
D/wpa_supplicant( 4232): wlan0: WPA: RX message 3 of 4-Way Handshake from c0:ff:d4:d3:aa:48 (ver=2)
D/wpa_supplicant( 4232): WPA: IE KeyData - hexdump(len=48): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00 dd 16 00 0f ac 01 02 00 01 ec ...
D/wpa_supplicant( 4232): WPA: RSN IE in EAPOL-Key - hexdump(len=22): 30 14 01 00 00 0f ac 04 01 00 00 0f ac 04 01 00 00 0f ac 02 00 00
D/wpa_supplicant( 4232): WPA: GTK in EAPOL-Key - hexdump(len=24): [REMOVED]
D/wpa_supplicant( 4232): wlan0: WPA: Sending EAPOL-Key 4/4
D/wpa_supplicant( 4232): WPA: KCK - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4232): WPA: Derived Key MIC - hexdump(len=16): 26 5d b4 6a 72 b8 bf 3f 1c 2e e1 f7 9c d3 b9 fb
D/wpa_supplicant( 4232): WPA: TX EAPOL-Key - hexdump(len=99): 01 03 00 5f 02 03 0a 00 00 00 00 00 00 00 00 00 02 00 00 00 00 00 00 00 00 00 00 00 00 00 00 00 ...
D/wpa_supplicant( 4232): wlan0: WPA: Installing PTK to the driver
D/wpa_supplicant( 4232): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb8a35c54 key_idx=0 set_tx=1 seq_len=6 key_len=16
,D/wpa_supplicant( 4232):    addr=c0:ff:d4:d3:aa:48
,D/wpa_supplicant( 4232): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4232): wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): RSN: received GTK in pairwise handshake - hexdump(len=18): [REMOVED]
D/wpa_supplicant( 4232): WPA: Group Key - hexdump(len=16): [REMOVED]
D/wpa_supplicant( 4232): wlan0: WPA: Installing GTK to the driver (keyidx=2 tx=0 len=16)
D/wpa_supplicant( 4232): WPA: RSC - hexdump(len=6): e2 3d 00 00 00 00
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/wpa_supplicant( 4232): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=3 addr=0xb6ec703a key_idx=2 set_tx=0 seq_len=6 key_len=16
D/wpa_supplicant( 4232):    broadcast key
D/WifiStateMachine(  957): handleMessage: E msg.what=147462
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): setDetailed state, old =AUTHENTICATING and new state=AUTHENTICATING
D/WifiStateMachine(  957): processMsg: ConnectModeState
,D/WifiStateMachine(  957): handleMessage: X
I/wpa_supplicant( 4232): wlan0: WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 4232): wlan0: State: GROUP_HANDSHAKE -> COMPLETED
I/wpa_supplicant( 4232): wlan0: CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]
D/WifiMonitor(  957): Event [IFNAME=wlan0 WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]]
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): wpa_driver_nl80211_set_operstate: operstate 0->1 (UP)
D/wpa_supplicant( 4232): netlink: Operstate: linkmode=-1, operstate=6
W/WifiMonitor(  957): couldn't identify event type - WPA: Key negotiation completed with c0:ff:d4:d3:aa:48 [PTK=CCMP GTK=CCMP]
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
D/WifiStateMachine(  957): handleMessage: E msg.what=147459
D/WifiStateMachine(  957): processMsg: DisconnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/wpa_supplicant( 4232): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4232): wpa_supplicant_set_state, isWPS : 0
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiStateMachine(  957): Network connection established
D/wpa_supplicant( 4232): EAPOL: External notification - portValid=1
D/wpa_supplicant( 4232): EAPOL: External notification - EAP success=1
D/wpa_supplicant( 4232): EAPOL: SUPP_PAE entering state AUTHENTICATING
D/wpa_supplicant( 4232): EAPOL: SUPP_BE entering state SUCCESS
D/wpa_supplicant( 4232): EAP: EAP entering state DISABLED
D/wpa_supplicant( 4232): EAPOL: SUPP_PAE entering state AUTHENTICATED
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Authorized
D/wpa_supplicant( 4232): nl80211: Set supplicant port authorized for c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4232): EAPOL: SUPP_BE entering state IDLE
D/wpa_supplicant( 4232): EAPOL authentication completed successfully
D/wpa_supplicant( 4232): RTM_NEWLINK: operstate=1 ifi_flags=0x11043 ([UP][RUNNING][LOWER_UP])
D/WifiNative-wlan0(  957): doString: STATUS
D/wpa_supplicant( 4232): RTM_NEWLINK, IFLA_IFNAME: Interface 'wlan0' added
D/wpa_supplicant( 4232): nl80211: if_removed already cleared - ignore event
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=6): 53 54 41 54 55 53
D/wpa_supplicant( 4232): wlan0: Control interface command 'STATUS'
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
,D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - connection to c0:ff:d4:d3:aa:48 completed (auth) [id=0 id_str=]]
,D/WifiNative-wlan0(  957):    returned bssid=c0:ff:d4:d3:aa:48
D/WifiNative-wlan0(  957): ssid=NG700
D/WifiNative-wlan0(  957): id=0
D/WifiNative-wlan0(  957): mode=station
D/WifiNative-wlan0(  957): pairwise_cipher=CCMP
D/WifiNative-wlan0(  957): group_cipher=CCMP
D/WifiNative-wlan0(  957): key_mgmt=WPA2-PSK
D/WifiNative-wlan0(  957): wpa_state=COMPLETED
D/WifiNative-wlan0(  957): p2p_device_address=36:fc:ef:de:0a:e2
D/WifiNative-wlan0(  957): address=34:fc:ef:de:0a:e2
I/WifiServiceExtension(  957): wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,I/WifiServiceExtension(  957): setKeepAlivePacketInterval is skipped if not WCN chip. it must set driver (30 sec)
,D/WifiStateMachine(  957): setDetailed state, old =AUTHENTICATING and new state=OBTAINING_IPADDR
,D/WifiStateMachine(  957): transitionTo: destState=ObtainingIpState
,D/WifiStateMachine(  957): handleMessage: new destination call exit/enter
D/WifiStateMachine(  957): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=2,curStateInfo: state=ConnectModeState,active=true,parent=DriverStartedState
,D/WifiStateMachine(  957): invokeExitMethods: DisconnectedState
,D/KeyguardUpdateMonitor( 1137): received broadcast android.net.wifi.STATE_CHANGE
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  957): ConnectivityChange for WIFI: CONNECTING/OBTAINING_IPADDR
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
,E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
,E/Parcel  (  511): Reading a NULL string not supported here.
,W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  957): NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
D/WifiStateMachine(  957): moveTempStackToStateStack: i=1,j=5
D/WifiStateMachine(  957): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  957): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=5,Top=ObtainingIpState
D/WifiStateMachine(  957): invokeEnterMethods: L2ConnectedState
,D/WifiStateMachine(  957): invokeEnterMethods: ObtainingIpState
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1137): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=147462
D/WifiStateMachine(  957): processMsg: ObtainingIpState
D/WifiStateMachine(  957): ObtainingIpState{ when=-33ms what=147462 obj=android.net.wifi.StateChangeResult@43c18d08 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/DhcpStateMachine(  957): StoppedState
D/DhcpStateMachine(  957): StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  957): WaitBeforeStartState
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=147462
D/WifiStateMachine(  957): processMsg: ObtainingIpState
D/WifiStateMachine(  957): ObtainingIpState{ when=-33ms what=147462 obj=android.net.wifi.StateChangeResult@43c19068 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=147459
D/WifiStateMachine(  957): processMsg: ObtainingIpState
,D/WifiStateMachine(  957): ObtainingIpState{ when=-34ms what=147459 obj=c0:ff:d4:d3:aa:48 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=131155
D/WifiStateMachine(  957): processMsg: ObtainingIpState
D/WifiStateMachine(  957): ObtainingIpState{ when=-11ms what=131155 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiNative-wlan0(  957): doString: SIGNAL_POLL
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4232): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4232): nl80211: survey data missing!
,D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=196612
D/WifiStateMachine(  957): processMsg: ObtainingIpState
D/WifiStateMachine(  957): ObtainingIpState{ when=-5ms what=196612 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  957): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  957): doBoolean: DRIVER BTCOEXMODE 1
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 31
D/wpa_supplicant( 4232): wlan0: Control interface command 'DRIVER BTCOEXMODE 1'
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
,E/Parcel  (  511): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,D/WifiService(  957): New client listening to asynchronous messages
,I/ActivityManager(  957): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4368 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,D/HyLog   ( 4368): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4368): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4368): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/QRemote ( 4368): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4368): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 4368): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4368): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4368): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4368): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4368): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 4368): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4368): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
I/ActivityManager(  957): Killing 4035:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  957): handleInetConditionChange: no active default network - ignore
,D/wpa_supplicant( 4232): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  957):    returned true
D/WifiStateMachine(  957): setSuspendOptimizationsNative: 1 false
,D/WifiNative-wlan0(  957): doBoolean: SET ps 0
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 30
D/wpa_supplicant( 4232): wlan0: Control interface command 'SET ps 0'
D/wpa_supplicant( 4232): CTRL_IFACE SET 'ps'='0'
,D/wpa_supplicant( 4232): nl80211: set_p2p_powersave (legacy_ps=0 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  957):    returned true
,D/WifiNative-wlan0(  957): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 4232): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 4232): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  957):    returned null
E/WifiStateMachine(  957): Unexpected BatchedScanResults :null
,D/WifiNative-wlan0(  957): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 4232): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 4232): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  957):    returned null
,E/WifiStateMachine(  957): CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
V/DhcpStateMachine(  957): Current State is mWaitBeforeStartState.
D/DhcpStateMachine(  957): WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
,D/DhcpStateMachine(  957): DHCP Start wake lock is acquired.
V/LgDhcpStateMachineHelper(  957): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
,V/LgDhcpStateMachineHelper(  957): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700" is not exist.
,D/WifiStateMachine(  957): handleMessage: X
I/ActivityManager(  957): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4395 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
D/WifiP2pService(  957): InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43350960 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  957): P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@43350960 target=com.android.internal.util.StateMachine$SmHandler }
,D/HyLog   ( 4395): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4395): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4395): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Babel   ( 4395): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4395): MmsConfig.loadMmsSettings
,I/MediaCodecList( 4395): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 4395): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/Babel   ( 4395): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
I/Babel   ( 4395): MmsConfig.loadFromDatabase
I/MediaCodecList( 4395): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 4395): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
,W/BaseRuntimeLoader( 4395): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4395): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4395): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4395): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 4395): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4395): MmsConfig.loadFromResources
,E/Babel   ( 4395): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4395): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 4395): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  957): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  957): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 4395): [loadRssi] File not exist 
V/LGRssiData( 4395): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4395): [loadFeatureFromXml] *** start feature loading from xml
I/ActivityManager(  957): Killing 3648:com.lge.appbox.client/u0a11 (adj 15): empty #17
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
V/TelephonyAutoProfiling( 4395): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4395): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4395): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/DhcpStateMachine(  957): DHCP request on wlan0
,D/LgDhcpStateMachineHelper(  957): dhcp.ap.macaddress = c0:ff:d4:d3:aa:48
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  957): addressUpdated: 192.168.1.121/24 on wlan0 flags 128 scope 0
,D/WifiStateMachine(  957): handleMessage: E msg.what=131212
,D/WifiStateMachine(  957): processMsg: ObtainingIpState
,D/WifiStateMachine(  957): ObtainingIpState{ when=-2ms what=131212 obj=192.168.1.121/24 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): processMsg: DriverStartedState
D/WifiStateMachine(  957): processMsg: DriverStartedStateExt
D/WifiStateMachine(  957): processMsg: SupplicantStartedState
,D/WifiStateMachine(  957): processMsg: DefaultState
,D/WifiStateMachine(  957): Link configuration changed for netId: 0 old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  957): handleMessage: X
,D/DhcpStateMachine(  957): DHCP succeeded on wlan0
,D/LgDhcpStateMachineHelper(  957): CheckDhcpDirectory [Lease File Count] : 3
V/LgDhcpStateMachineHelper(  957): [bssid + ssid] hash key :c0:ff:d4:d3:aa:48"NG700"
D/LgDhcpStateMachineHelper(  957): checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.121
V/LgDhcpStateMachineHelper(  957): Add DhcpResults: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds
,V/DhcpStateMachine(  957): Current State is mWaitBeforeStartState.
V/LgDhcpStateMachineHelper(  957): bShouldSendDhcpAction Result: true
D/WifiStateMachine(  957): handleMessage: E msg.what=196613
D/WifiStateMachine(  957): processMsg: ObtainingIpState
D/WifiStateMachine(  957): ObtainingIpState{ when=-1ms what=196613 arg1=1 obj={InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0} DHCP server /192.168.1.1 Vendor info  lease 86400 seconds target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiStateMachine(  957): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  957): doBoolean: SET ps 1
,D/DhcpStateMachine(  957): DHCP Start/Renew wake lock is released.
,D/DhcpStateMachine(  957): RunningState
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 4232): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 4232): CTRL_IFACE SET 'ps'='1'
,D/wpa_supplicant( 4232): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  957):    returned true
,D/WifiNative-wlan0(  957): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
,D/wpa_supplicant( 4232): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 4232): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiP2pService(  957): InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  957): P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiNative-wlan0(  957):    returned true
,D/WifiStateMachine(  957): DHCP successful
,D/WifiStateMachine(  957): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [] DnsAddresses: [] Domains: nullMTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
D/WifiStateMachine(  957): transitionTo: destState=VerifyingLinkState
D/WifiStateMachine(  957): handleMessage: new destination call exit/enter
D/WifiStateMachine(  957): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  957): invokeExitMethods: ObtainingIpState
D/WifiStateMachine(  957): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  957): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=VerifyingLinkState
,D/WifiStateMachine(  957): invokeEnterMethods: VerifyingLinkState
D/WifiStateMachine(  957): VerifyingLinkState enter
,D/WifiStateMachine(  957): setDetailed state, old =OBTAINING_IPADDR and new state=VERIFYING_POOR_LINK
,D/WifiStateMachine(  957): handleMessage: X
,D/KeyguardUpdateMonitor( 1137): received broadcast android.net.wifi.STATE_CHANGE
E/BatteryObserver( 1151): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  957): NETWORK_STATE_CHANGED_ACTION [VERIFYING_POOR_LINK]
D/WifiStateMachine(  957): handleMessage: E msg.what=135190
D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
D/ConnectivityServiceHSM(  957): send additional Connectivity Action
D/WifiStateMachine(  957): processMsg: VerifyingLinkState
,D/WifiStateMachine(  957): VerifyingLinkState GOOD_LINK_DETECTED: transition to captive portal check
D/WifiStateMachine(  957): transitionTo: destState=CaptivePortalCheckState
D/WifiStateMachine(  957): handleMessage: new destination call exit/enter
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
D/WifiStateMachine(  957): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
E/Parcel  (  511): Reading a NULL string not supported here.
D/WifiStateMachine(  957): invokeExitMethods: VerifyingLinkState
D/WifiStateMachine(  957): moveTempStackToStateStack: i=0,j=6
,D/WifiStateMachine(  957): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=CaptivePortalCheckState
D/WifiStateMachine(  957): invokeEnterMethods: CaptivePortalCheckState
D/WifiStateMachine(  957): CaptivePortalCheckState enter
,D/WifiStateMachine(  957): setDetailed state, old =VERIFYING_POOR_LINK and new state=CAPTIVE_PORTAL_CHECK
W/WifiStateTracker(  957): NETWORK_STATE_CHANGED_ACTION Link configuration changed : 
W/WifiStateTracker(  957): 
W/WifiStateTracker(  957):  old: {LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: nullMTU: 0}
W/WifiStateTracker(  957):  new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/WifiStateMachine(  957): handleMessage: X
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1137): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
D/QcConnectivityService(  957): handleConnectivityChange: preConnState=0 connState=2
D/Nat464Xlat(  957): requiresClat: netType=1, hasIPv4Address=true
,D/LocSvc_java(  957): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/KeyguardUpdateMonitor( 1137): received broadcast android.net.wifi.STATE_CHANGE
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/LocSvc_java(  957): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  957): ignore wifi update if we are not in OPENING or CLOSING
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1137): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,D/QRemote ( 4368): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1137): handleBatteryUpdate (2) (100)
,I/QRemote ( 4368): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
,D/QRemote ( 4368): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 4368): [WiFiStateReceiver.java:187:onReceive()] oooooo The network is not connected. Don't handle that intent.
D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  957): ConnectivityChange for WIFI: CONNECTING/CAPTIVE_PORTAL_CHECK
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5009
D/WifiStateMachine(  957): handleMessage: E msg.what=131092
D/WifiStateMachine(  957): processMsg: CaptivePortalCheckState
,D/WifiStateMachine(  957): CaptivePortalCheckState CMD_CAPTIVE_CHECK_COMPLETE
,D/WifiStateMachine(  957): setDetailed state, old =CAPTIVE_PORTAL_CHECK and new state=CONNECTED
,W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  957): NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
,E/Parcel  (  511): Reading a NULL string not supported here.
D/QcConnectivityService(  957): Captive portal check NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  957): handleCaptivePortalTrackerCheck: call captivePortalCheckComplete ni=NetworkInfo: type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  957): handleInetConditionChange: no active default network - ignore
,W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/WfdStateTracker( 1151): handleWifiStateChangedEvent: 1
D/WifiController(  957): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardUpdateMonitor( 1137): received broadcast android.net.wifi.STATE_CHANGE
D/WifiStateMachine(  957): transitionTo: destState=ConnectedState
D/WifiStateMachine(  957): handleMessage: new destination call exit/enter
D/WifiStateMachine(  957): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=L2ConnectedState,active=true,parent=ConnectModeState
D/WifiStateMachine(  957): invokeExitMethods: CaptivePortalCheckState
D/WifiStateMachine(  957): moveTempStackToStateStack: i=0,j=6
D/WifiStateMachine(  957): moveTempStackToStateStack: X mStateStackTop=6,startingIndex=6,Top=ConnectedState
D/WifiStateMachine(  957): invokeEnterMethods: ConnectedState
D/WifiStateMachine(  957): handleMessage: X
,W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  957): ConnectivityChange for WIFI: CONNECTED/CONNECTED
D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5001
D/GpsLocationProvider(  957): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,I/RemoteControlStatusBar( 1137): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,E/Parcel  (  511): Reading a NULL string not supported here.
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/WifiOffDelayIfNotUsed(  957): NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,I/PCSuite ( 4233): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/ActivityThread(  957): Failed to find provider info for com.lge.ims.provisioning
D/QcConnectivityService(  957): handleConnectivityChange:1 is conntected
D/QcConnectivityService(  957): handleConnectivityChange: preConnState=2 connState=1
,V/        (  264): RouteController
,D/PCSuite ( 4233): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,D/QRemote ( 4368): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,D/QRemote ( 4368): [WiFiStateReceiver.java:110:onReceive()] oooooo The network is connected.
,V/        (  264): RouteController
,I/QRemote ( 4368): [Constants.java:295:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,I/QRemote ( 4368): [WiFiStateReceiver.java:164:onReceive()] oooooo There are no stored BSSIDs.
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,D/QCNEA   (  511): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  511): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  511): |CAC| updateNetCfgInfo
V/QCNEA   (  511): |CAC| *********************************************
V/QCNEA   (  511): |CAC|                   Netconfig               
V/QCNEA   (  511): |CAC| *********************************************
V/QCNEA   (  511): |CAC| 	NetConfig: Net type   =1
V/QCNEA   (  511): |CAC| 	NetConfig: subtype rl =21
V/QCNEA   (  511): |CAC| 	NetConfig:         fl =21
V/QCNEA   (  511): |CAC| 	NetConfig: ip4        =192.168.1.121
V/QCNEA   (  511): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  511): |CAC| 	NetConfig: mtu        =1500
V/QCNEA   (  511): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  511): |CAC| *********************************************
D/QCNEA   (  511): |CAC| Received bssid= c0:ff:d4:d3:aa:48
D/QCNEA   (  511): |CAC| net type = 1
V/QCNEA   (  511): |CAC| 	bssid           =c0:ff:d4:d3:aa:48
D/QCNEA   (  511): |CAC| Received ssid= NG700
V/QCNEA   (  511): |CAC| 	ssid           =NG700
V/QCNEA   (  511): |CAC| 	DNS v4        =192.168.1.1
V/QCNEA   (  511): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  511): |CAC| *********************************************
D/QCNEA   (  511): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  511): |CAC| dispatching netcfgupdate for wlan
,D/QCNEA   (  511): |CAC| dispatchNetCfg: updating:0xb787a8dc
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/LocSvc_java(  957): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  957): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,D/Nat464Xlat(  957): requiresClat: netType=1, hasIPv4Address=true
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/LocSvc_java(  957): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  957): ignore wifi update if we are not in OPENING or CLOSING
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/wpa_supplicant( 4232): EAPOL: startWhen --> 0
,D/wpa_supplicant( 4232): EAPOL: disable timer tick
,D/GpsLocationProvider(  957): NTP server returned: 1449683676198 (Wed Dec 09 18:54:36 CET 2015) reference: 115289 certainty: 23 system time offset: 384
,E/LocSvc_afw(  957): V/Entering int loc_inject_time(GpsUtcTime, int64_t, int) line 446 
E/LocSvc_eng(  957): I/===> int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int) line 1910 
E/LocSvc_eng(  957): V/time: 1449683676198
E/LocSvc_eng(  957):   timeReference: 115289
E/LocSvc_eng(  957):   uncertainty: 23
E/LocSvc_utils_q(  957): D/msg_q_snd: Sending message with handle = 0x670D5370
E/LocSvc_utils_ll(  957): D/linked_list_add: Adding to list data_obj = 0x670D5370
E/LocSvc_utils_ll(  957): D/linked_list_remove: Removing from list
E/LocSvc_utils_q(  957): D/msg_q_rcv: Received message 0x670D5370 rv = 0
E/LocSvc_eng(  957): V/time: 1449683676198
E/LocSvc_eng(  957):   timeReference: 115289
E/LocSvc_eng(  957):   uncertainty: 23
E/LocSvc_utils_q(  957): D/msg_q_snd: Finished Sending message with handle = 0x670D5370
E/LocSvc_ApiV02(  957): V/virtual loc_api_adapter_err LocApiV02::setTime(GpsUtcTime, int64_t, int):436]: uncertainty = 23
E/LocSvc_eng(  957): V/Exiting int loc_eng_inject_time(loc_eng_data_s_type&, GpsUtcTime, int64_t, int) line 1917 0
,E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_afw(  957): V/Exiting int loc_inject_time(GpsUtcTime, int64_t, int) line 452 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 56, req_id 56 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 56
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=56, len = 16
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 56, len = 16
,E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_UTC_TIME_REQ_V02
,E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 45, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=56 buf_len=7 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 56 size = 4
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 56 is a resp size = 4
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_UTC_TIME_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 56, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 56 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 56 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 56 size = 4
,E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 4 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_MsgTask(  957): D/MsgTask::loop() 26 listening ...
,E/LocSvc_utils_q(  957): D/msg_q_rcv: Waiting on message
,D/GpsLocationProvider(  957): calling native_inject_xtra_data
E/LocSvc_afw(  957): V/Entering int loc_xtra_inject_data(char*, int) line 858 
E/LocSvc_eng(  957): V/length: 58777
E/LocSvc_eng(  957):   data: 0x671a7008
,E/LocSvc_utils_q(  957): D/msg_q_snd: Sending message with handle = 0x658C44B0
E/LocSvc_utils_ll(  957): D/linked_list_add: Adding to list data_obj = 0x658C44B0
E/LocSvc_utils_ll(  957): D/linked_list_remove: Removing from list
E/LocSvc_utils_q(  957): D/msg_q_rcv: Received message 0x658C44B0 rv = 0
E/LocSvc_eng(  957): V/length: 58777
E/LocSvc_eng(  957):   data: 0x671a7008
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1018]: xtra size = 58777
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 1/58, len = 1024, total injected = 0
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_utils_q(  957): D/msg_q_snd: Finished Sending message with handle = 0x658C44B0
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_afw(  957): V/Exiting int loc_xtra_inject_data(char*, int) line 861 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
,E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 46, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 1024
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 2/58, len = 1024, total injected = 1024
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 47, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 2048
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 3/58, len = 1024, total injected = 2048
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 48, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 3072
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 4/58, len = 1024, total injected = 3072
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 49, status = 0
,E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 4096
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 5/58, len = 1024, total injected = 4096
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 50, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 5120
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 6/58, len = 1024, total injected = 5120
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 51, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 6144
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 7/58, len = 1024, total injected = 6144
,E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 52, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 7168
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 8/58, len = 1024, total injected = 7168
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 53, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 8192
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 9/58, len = 1024, total injected = 8192
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 54, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 9216
,E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 10/58, len = 1024, total injected = 9216
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 55, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
,E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 10240
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 11/58, len = 1024, total injected = 10240
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 56, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 11264
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 12/58, len = 1024, total injected = 11264
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
,E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 57, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 12288
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 13/58, len = 1024, total injected = 12288
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 58, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 13312
,E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 14/58, len = 1024, total injected = 13312
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 59, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
,E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 14336
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 15/58, len = 1024, total injected = 14336
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 60, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 15360
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 16/58, len = 1024, total injected = 15360
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 61, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 16384
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 17/58, len = 1024, total injected = 16384
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 62, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
,E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 17408
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 18/58, len = 1024, total injected = 17408
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 63, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 18432
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 19/58, len = 1024, total injected = 18432
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 64, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 19456
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 20/58, len = 1024, total injected = 19456
,E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 65, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 20480
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 21/58, len = 1024, total injected = 20480
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 66, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
,E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 21504
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 22/58, len = 1024, total injected = 21504
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 67, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 22528
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 23/58, len = 1024, total injected = 22528
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 68, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 23552
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 24/58, len = 1024, total injected = 23552
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 69, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 24576
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 25/58, len = 1024, total injected = 24576
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 70, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 25600
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 26/58, len = 1024, total injected = 25600
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 71, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 26624
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 27/58, len = 1024, total injected = 26624
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 72, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 27648
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 28/58, len = 1024, total injected = 27648
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 73, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 28672
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 29/58, len = 1024, total injected = 28672
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 74, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 29696
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 30/58, len = 1024, total injected = 29696
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 75, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 30720
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 31/58, len = 1024, total injected = 30720
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 76, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 31744
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 32/58, len = 1024, total injected = 31744
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 77, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 32768
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 33/58, len = 1024, total injected = 32768
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 78, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 33792
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 34/58, len = 1024, total injected = 33792
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 79, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 34816
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 35/58, len = 1024, total injected = 34816
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 80, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 35840
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 36/58, len = 1024, total injected = 35840
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 81, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 36864
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 37/58, len = 1024, total injected = 36864
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 82, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 37888
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 38/58, len = 1024, total injected = 37888
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
,E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 83, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 38912
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 39/58, len = 1024, total injected = 38912
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
,E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 84, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 39936
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 40/58, len = 1024, total injected = 39936
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 85, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
,E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 40960
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 41/58, len = 1024, total injected = 40960
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 86, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
,E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 41984
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 42/58, len = 1024, total injected = 41984
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
,E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 87, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 43008
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 43/58, len = 1024, total injected = 43008
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
,E/LocSvc_api_v02(  957): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 88, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 44032
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 44/58, len = 1024, total injected = 44032
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 89, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 45056
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 45/58, len = 1024, total injected = 45056
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 90, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 46080
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 46/58, len = 1024, total injected = 46080
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
,E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 91, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 47104
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 47/58, len = 1024, total injected = 47104
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 92, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 48128
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 48/58, len = 1024, total injected = 48128
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 93, status = 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
,E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 49152
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 49/58, len = 1024, total injected = 49152
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 94, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 50176
,E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 50/58, len = 1024, total injected = 50176
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 95, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
,E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 51200
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 51/58, len = 1024, total injected = 51200
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 96, status = 0
,E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 52224
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 52/58, len = 1024, total injected = 52224
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
,E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 97, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
,E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 53248
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 53/58, len = 1024, total injected = 53248
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:219]: ind 53 arrived before wait was called 
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 98, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 54272
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 54/58, len = 1024, total injected = 54272
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 99, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
,E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 55296
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 55/58, len = 1024, total injected = 55296
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
,E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 100, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 56320
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 56/58, len = 1024, total injected = 56320
,E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 101, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 57344
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 57/58, len = 1024, total injected = 57344
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 102, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
,E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 58368
E/LocSvc_ApiV02(  957): D/[virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1050] part 58/58, len = 409, total injected = 58368
E/LocSvc_api_v02(  957): V/loc_alloc_slot:271]: returning slot 0
E/LocSvc_api_v02(  957): V/loc_sync_select_ind:356]: client handle 0x67257690, ind_id 53, req_id 53 
E/LocSvc_api_v02(  957): V/validateRequest:1552]: reqId = 53
E/LocSvc_api_v02(  957): V/validateRequest:1915]: reqId=53, len = 1044
E/LocSvc_api_v02(  957): V/locClientSendReq:2396] sending reqId= 53, len = 1044
E/LocSvc_api_v02(  957): I/---> locClientSendReq line 2402 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_api_v02(  957): V/locClientSendReq:2413] qmi_client_send_msg_sync returned 0
,E/LocSvc_api_v02(  957): V/convertQmiResponseToLocStatus:681]: result = 0, error = 103, status = 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:512]: select_id = 0,locClientSendReq returned 0
,E/LocSvc_api_v02(  957): V/locClientIndCb:1356]: Indication: msg_id=53 buf_len=12 pCallbackData = 0x67257690
,E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
E/LocSvc_api_v02(  957): V/locClientGetSizeAndTypeByIndId:556]: indId 53 is a resp size = 8
E/LocSvc_ApiV02(  957): I/<--- void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*) line 106 QMI_LOC_INJECT_PREDICTED_ORBITS_DATA_REQ_V02
E/LocSvc_ApiV02(  957): V/void globalRespCb(locClientHandleType, uint32_t, locClientRespIndUnionType, void*):112] client = 0x67257690, resp id = 53, client cookie ptr = 0x67254850
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:165]: received indication, handle = 0x67257690 ind_id = 53 
E/LocSvc_api_v02(  957): V/loc_sync_process_ind:195]: found slot 0 selected for ind 53 
E/LocSvc_api_v02(  957): V/locClientGetSizeByRespIndId:2563]: resp ind Id 53 size = 8
,E/LocSvc_api_v02(  957): V/loc_sync_process_ind:201]: copying ind payload size = 8 
E/LocSvc_api_v02(  957): D/loc_free_slot:299]: freeing slot 0
E/LocSvc_api_v02(  957): V/loc_sync_send_req:539]: success (select id 0)
E/LocSvc_ApiV02(  957): D/virtual loc_api_adapter_err LocApiV02::setXtraData(char*, int):1074]: XTRA injected length: 58777
E/LocSvc_MsgTask(  957): D/MsgTask::loop() 27 listening ...
,E/LocSvc_utils_q(  957): D/msg_q_rcv: Waiting on message
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  957): addressUpdated: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,D/WifiStateMachine(  957): handleMessage: E msg.what=131212
D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
,D/WifiStateMachine(  957): processMsg: DriverStartedState
D/WifiStateMachine(  957): processMsg: DriverStartedStateExt
D/WifiStateMachine(  957): processMsg: SupplicantStartedState
,D/WifiStateMachine(  957): processMsg: DefaultState
,D/WifiStateMachine(  957): Link configuration changed for netId: 0 old: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }new: {InterfaceName: wlan0 LinkAddresses: [192.168.1.121/24,fe80::36fc:efff:fede:ae2/64,]  Routes: [192.168.1.0/24 -> 0.0.0.0,0.0.0.0/0 -> 192.168.1.1,] DnsAddresses: [192.168.1.1,] Domains: MTU: 0HttpProxy: [ProxyProperties.mHost == null] }
,D/WifiStateMachine(  957): handleMessage: X
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458753
,D/ConnectivityServiceHSM(  957): send additional Connectivity Action
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5003
,D/LocSvc_java(  957): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/QcConnectivityService(  957): handleConnectivityChange:1 is conntected
,D/LocSvc_java(  957): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  957): ignore wifi update if we are not in OPENING or CLOSING
,D/QcConnectivityService(  957): handleConnectivityChange: addresses changed linkProperty[1]: resetMask=0
D/QcConnectivityService(  957):    car=removed=[] added=[fe80::36fc:efff:fede:ae2/64,]
,E/QcConnectivityService(  957): Exception while trying to add src route: java.lang.NullPointerException
,D/Nat464Xlat(  957): requiresClat: netType=1, hasIPv4Address=true
,D/GpsLocationProvider(  957): updateNetworkState available info: NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,I/jxcore-log( 4175): Test app app.js loaded
I/jxcore-log( 4175): 
,I/Choreographer( 4175): Skipped 406 frames!  The application may be doing too much work on its main thread.
,I/chromium( 4175): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,D/WifiStateMachine(  957): handleMessage: E msg.what=131155
,D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiNative-wlan0(  957): doString: SIGNAL_POLL
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4232): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4232): nl80211: survey data missing!
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,D/WifiStateMachine(  957): handleMessage: X
E/Parcel  (  511): Reading a NULL string not supported here.
,E/Parcel  (  511): Reading a NULL string not supported here.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  957): MasterInitialState.processMessage what=3
,D/        (  957): Setting time of day to sec=1449683678
,W/        (  957): Unable to set rtc to 1449683678: Invalid argument
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/CaptivePortalTracker(  957): NoActiveNetworkState{ when=-13ms what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTING/VERIFYING_POOR_LINK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_SET
,I/SecureClockService( 1151): Intent.ACTION_TIME_CHANGED 
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_SET, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449683678992, nextTick: 21041, mDrawingTime: 0
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449683678993, nextTick: 21040, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/WeatherService( 1883): 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 18:54:39
,I/MusicWidget( 2096): intentReceiver onReceive() action::android.intent.action.TIME_SET
,I/[LGHome]LGCalendarIcon( 1485): [LGCalendarIcon.java:188:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 9
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,I/MusicWidget( 2096): beingMusicWidget_4x2() result::false
,I/MusicWidget( 2096): beingMusicWidget_Lock() result::false
,I/MusicWidget( 2096): beingMusicWidget_Quick() result::false
,I/MusicWidget( 2096): beingMusicWidget_4x1() result::true
,I/MusicWidget( 2096): performViewUpdater handleMessage() msg.what::0
,I/MusicWidget( 2096): beingMusicWidget_4x1() result::true
,I/MusicWidget( 2096): performUpdate()_4x1
,I/[LGHome]LGCalendarIcon( 1485): [LGCalendarIcon.java:188:makeCalendarBitmap()]Locale = en_US dayofweek= Wed date= 9
,I/[LGHome]Launcher( 1485): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  957): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  957): NoActiveNetworkState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/QCNEA   (  511): |CAC| readCallback: read len:0, ret:-1, errno:11
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WeatherService( 1883): 2 : requestRefreshAppWidget, isUpdateStart : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/UpdateThreadPoolManager( 1883): 2 : This is isUpdating : false
,D/WeatherService( 1883): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1883): 2 : buildUpdate, appWidgetId: 1
,D/WeatherReflect( 1883): 2 : Map key string is -2
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,D/lim     ( 1883): 2 : time = 18:54
I/WeatherReflect( 1883): Model Name : LG-D802
D/WeatherTheme( 1883): 2 : Different view - status_min_formatted : 53 != 54
I/MusicWidget( 2096): status::mounted
,D/WeatherTheme( 1883): 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
D/WeatherTheme( 1883): 2 : Current Theme Name: com.lge.launcher2.theme.optimus
D/WeatherTheme( 1883): 2 : Fixed theme : optimus
,I/MusicWidget( 2096): defaultAppWidget()_4x1
I/MusicWidget( 2096): 4x1_currentTheme :: com.lge.launcher2.theme.optimus
,I/MusicWidget( 2096): setDefaultViewLayoutId()_4x1
,D/WeatherTheme( 1883): 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
I/MusicWidget( 2096): appWidgetViewUpdate()_4x1
,I/MusicWidget( 2096): linkButtons()_4x1
,I/ActivityManager(  957): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=4535 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
D/WeatherService( 1883): 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 18:54:39
,D/HyLog   ( 4535): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4535): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4535): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/MusicWidget( 2096): pushUpdate()_4x1
,I/MusicWidget( 2096): performViewUpdater handleMessage() msg.what::3
,I/MusicWidget( 2096): beingMusicWidget_Quick() result::false
,I/AppUp4  ( 4535):  AppBoxContentProvider onCreate
,W/AppUp4  ( 4535):  [AppBoxDatabaseHelper] construct
,I/AppUp4  ( 4535):  setFingerPrint start
,I/AppUp4  ( 4535):  newfinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
,I/AppUp4  ( 4535):  beforefinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
,I/AppUp4  ( 4535):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 4535): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 4535): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4535): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4535): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4535): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4535): onReceive
,D/AppUp4:CustFacade( 4535): Context : android.app.ReceiverRestrictedContext@42887a68
D/AppUp4:CustFacade( 4535): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4535): isOpenOperator : true
,D/AppUp4:CustFacade( 4535): isPhone : true
,I/LicenseContentProvider( 2903): start selecting data
,D/SIMObserver( 2903): simInfo1
,I/AppUp4:EulaManager( 4535): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4535): begin check event
I/AppUp4:CustModeStarterReceiver( 4535): Event For GoodConnectivity
D/AppUp4:CustModeStarterReceiver( 4535): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4535): call method handleAsyncCustNotification.
,E/AppUp4:CustModeStarterReceiver( 4535): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4535): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4535): handleAsyncCustNotification do not startCustService
,I/ActivityManager(  957): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=4554 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  957): Start proc com.android.chrome for service com.android.chrome/com.google.android.apps.chrome.sync.ChromeBrowserSyncAdapterService: pid=4567 uid=10063 gids={50063, 3003, 1028, 1015}
,D/HyLog   ( 4554): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4554): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4554): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4567): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4567): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4567): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/MusicWidget( 2096): performViewUpdater handleMessage() msg.what::1
,I/MusicWidget( 2096): beingMusicWidget_4x2() result::false
,I/MusicWidget( 2096): beingMusicWidget_Lock() result::false
,D/EAS     ( 4075): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4075): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 4075): ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,V/DownloadManager( 4554): DownloadService onCreate
,I/DownloadManager( 4554): in removeSpuriousFiles
,D/DelayedSyncController( 4567): Delaying sync.
,V/DownloadManager( 4554): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4554): created cursor android.database.sqlite.SQLiteCursor@428b60e0 on behalf of 4554
,I/DownloadManager( 4554): in trimDatabase
,V/DownloadManager( 4554): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 4554): created cursor android.database.sqlite.SQLiteCursor@428b7950 on behalf of 4554
,V/DownloadManager( 4554): DownloadService onStartCommand
,V/DownloadManager( 4554): DownloadService onStartCommand
,W/linker  ( 4075): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
D/HtmlEditor( 4075): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 4075): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
D/HtmlEditor( 4075): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 4075): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
V/DownloadManager( 4554): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
D/HtmlEditor( 4075): register_HtmlEditor, Success
D/HtmlEditor( 4075): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 4075): register_HtmlEditorTimer, Success
D/HtmlEditor( 4075): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 4075): register_HtmlEditorDownloader, Success
D/HtmlEditor( 4075): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4075): register_HtmlEditorFont, Success
,D/HtmlEditor( 4075): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4075): register_HtmlEditorDrawText, Success
,D/HtmlEditor( 4075): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4075): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 4075): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 4075): register_HtmlEditorWordIterator, Success
,D/HtmlEditor( 4075): JNI_OnLoad Success
,I/HubEmail( 4075): JNI_OnLoad()
I/HubEmail( 4075): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4075): registerNatives()
I/HubEmail( 4075): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 4075): registerNativeMethods()
,I/HubEmail( 4075): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,V/DownloadManager( 4554): created cursor android.database.sqlite.SQLiteCursor@428b9d80 on behalf of 4554
,I/ActivityManager(  957): Start proc com.android.mms for broadcast com.android.mms/.transaction.LgeMiscReceiver: pid=4594 uid=10035 gids={50035, 3003, 1028, 1015, 1023, 4002, 3002}
V/DownloadManager( 4554): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4554): created cursor android.database.sqlite.SQLiteCursor@428bddd8 on behalf of 4554
W/Settings( 4075): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HyLog   ( 4594): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4594): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4594): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/DownloadManager( 4554): DownloadService onDestroy
,D/DelayedSyncController( 4567): Delaying sync.
I/ActivityManager(  957): Killing 3665:com.android.contacts/u0a21 (adj 15): empty #17
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,I/ConversationSkinProvider( 4594): skin provider oncreate
,W/DriveInitializer( 1939): Background init thread started
,E/[MMS]   ( 4594): MmsSettings: [LGE] MmsSettings.initializeMmsSettings()
,W/BaseRuntimeLoader( 4594): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4594): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4594): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4594): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/[MMS]   ( 4594): MmsSettings: [LGE]loadXMLSettings() ++++++++++ >> Load default:false
I/[MMS]   ( 4594): MmsSettings: [LGE]loadXMLSettings() SIM(current) information
I/[MMS]   ( 4594): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 4594): MmsSettings: [LGE]loadXMLSettings() [Build] Country:EU, Operator:OPEN
D/[MMS]   ( 4594): MmsSettings: loadxmlstring=open_eu_mms_config
,D/[MMS]   ( 4594): MmsSettings: Matching Xml Data file name = 2131034168
,E/Auth.Api.Credentials( 1939): [CredentialSyncAdapter] Unknown sync event.
I/ActivityManager(  957): Killing 4094:com.google.android.apps.docs/u0a73 (adj 15): empty #17
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,D/[MMS]   ( 4594): MmsSettings: [LGE]parseDTMF() file doesn't exist
D/[MMS]   ( 4594): MmsSettings: [LGE]setDefaultDTMFVolume() set default DTMF value
E/[MMS]   ( 4594): MmsSettings: [LGE]loadXMLSettings(): Check current items.
D/[MMS]   ( 4594): MmsSettings: [LGE]---------------------------------------->
,D/[MMS]   ( 4594): MmsSettings: [LGE]   sms_dr = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   cb_on = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   sms_concat = [5]
D/[MMS]   ( 4594): MmsSettings: [LGE]   sms_char = [0]
,D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_dr_r = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_dr_a = [1]
D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_rr_r = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_rr_a = [1]
D/[MMS]   ( 4594): MmsSettings: [LGE]   auto_retr = [1]
D/[MMS]   ( 4594): MmsSettings: [LGE]   auto_retr_r = [0]
,D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_priority = [1]
D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_validity = [6]
D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_creation = [2]
D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_size = [300]
D/[MMS]   ( 4594): MmsSettings: [LGE]   slide_dur = [5]
D/[MMS]   ( 4594): MmsSettings: [LGE]   recv_adv = [1]
D/[MMS]   ( 4594): MmsSettings: [LGE]   push_on = [1]
,D/[MMS]   ( 4594): MmsSettings: [LGE]   del_old = [1]
D/[MMS]   ( 4594): MmsSettings: [LGE]   sms_limit = [500]
D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_limit = [50]
D/[MMS]   ( 4594): MmsSettings: [LGE]   max_editor_num = [2000]
D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_slide_num = [10]
D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_recipient_num = [20]
D/[MMS]   ( 4594): MmsSettings: [LGE]   attachement_storage = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   send_msg_enter_key = [1]
,D/[MMS]   ( 4594): MmsSettings: [LGE]   spam_setting = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   anonymous_spam_setting = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_recipient_length = [64]
D/[MMS]   ( 4594): MmsSettings: [LGE]   sms_recipient_length = [20]
D/[MMS]   ( 4594): MmsSettings: [LGE]   recv_adv_invisible = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_creation_invisible = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_dr_r_invisible = [0]
,D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_dr_a_invisible = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_rr_r_invisible = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_rr_a_invisible = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   auto_retr_r_invisible = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_validity_invisible = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_priority_invisible = [0]
,D/[MMS]   ( 4594): MmsSettings: [LGE]   sms_char_invisible = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   sms_dr_invisible = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   sms_validity_invisible = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   discard_visible = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_pending_in_wifi_use = [1]
,D/[MMS]   ( 4594): MmsSettings: [LGE]   attach_location = [1]
D/[MMS]   ( 4594): MmsSettings: [LGE]   custom_extract_ui = [1]
D/[MMS]   ( 4594): MmsSettings: [LGE]   msg_list_data_seperator = [1]
D/[MMS]   ( 4594): MmsSettings: [LGE]   animation_effect = [1]
D/[MMS]   ( 4594): MmsSettings: [LGE]   inline_msg_item = [1]
D/[MMS]   ( 4594): MmsSettings: [LGE]   display_as_slide_layout = [1]
D/[MMS]   ( 4594): MmsSettings: [LGE]   one_bubble = [1]
,D/[MMS]   ( 4594): MmsSettings: [LGE]   hide_sync_header_update = [1]
D/[MMS]   ( 4594): MmsSettings: [LGE]   recipient_cc_bcc = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   ciq_on = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_enabled_when_data_disabled = [1]
D/[MMS]   ( 4594): MmsSettings: [LGE]   two_finger_flick = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   kr_skt_feature_set = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   kr_kt_feature_set = [0]
,D/[MMS]   ( 4594): MmsSettings: [LGE]   kr_lgu_feature_set = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   docomo_message_setting = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   docomo_sim_card_set = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   docomo_nexti_phonebook_set = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   docomo_function_validity_period = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   docomo_led_button_blink = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   docomo_dtmf_setting = [0]
,D/[MMS]   ( 4594): MmsSettings: [LGE]   china_feature_set = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   media_resolution_restrict_off = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   attachment_save_in_slidesheow = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_max_video_resolution = [320x240]
D/[MMS]   ( 4594): MmsSettings: [LGE]   email_over_sms = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   email_over_sms_gateway_num = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   addr_len_check = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   message_poster = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   sticky_note = [0]
,D/[MMS]   ( 4594): MmsSettings: [LGE]   wificalling_feature_set = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   online_album = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   online_album_dest_num = [000]
D/[MMS]   ( 4594): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   voice_mail = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   smsc_readonly = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   latin_america_fdn_check = [0]
,D/[MMS]   ( 4594): MmsSettings: [LGE]   sms_sent_time_mode = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   fdn_gprs_check = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   reply_to_virtual_smsc = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   save_to_draft = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_signature = [0]
D/[MMS]   ( 4594): MmsSettings: [LGE]   mms_callback = [0]
,D/[MMS]   ( 4594): MmsSettings: [LGE]   message_counters_key = [0]
,E/[MMS]   ( 4594): MmsSettings: [LGE]loadXMLSettings(): Check prefMmsConfig.
,I/[MMS]   ( 4594): MmsSettings: [LGE]loadXMLSettings() Phone(saved) information
I/[MMS]   ( 4594): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 4594): MmsSettings: [LGE]loadXMLSettings(): SIM is NOT changed!!!
E/[MMS]   ( 4594): MmsSettings: [LGE]loadXMLSettings(): SIM is not ready!!!
,D/MmsConfig( 4594): [LGE] setForceSmsGsmAlphabet_SystemProperties.set: 0
,W/DriveInitializer( 1939): Awaiting to be initialized
,I/[MMS]   ( 4594): MmsConfig: [LGE]getUaString=LG-D802 LG-Android-MMS-V4.0/1.2
,I/LGDrmService( 4594): _DRM_ServiceGet() : Bind lgdrm service
,E/Diag_Lib(  276): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  276): qmi_init:  Created client handle b7c1bfc8
,E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
W/DriveInitializer( 1939): Background init thread ended
D/DRM_Adap(  276): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
,E/Diag_Lib(  276): Setting the api flag to : 1
,E/Diag_Lib(  276): qmi_client [276] 7: sending 47 bytes on fd = 16
,E/Diag_Lib(  276): qmi_client [276] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  276):  API Flag .............. 1 
E/Diag_Lib(  276):  Message ID ............... 37 
E/Diag_Lib(  276): qmi_service_release called, user_handle=20200
E/Diag_Lib(  276): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  276): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  276): qmi_service_delete_client_txns : EXIT
E/Diag_Lib(  276): qmi_free_srvc_data : ENTRY
,E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEI: success getting IMEI
,D/LGDRM   (  276): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
E/Diag_Lib(  276): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  276): qmi_init:  Created client handle b7c1bfe0
E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
,E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  276): Setting the api flag to : 1
,E/Diag_Lib(  276): qmi_client [276] 7: sending 47 bytes on fd = 16
,E/Diag_Lib(  276): qmi_client [276] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  276):  API Flag .............. 1 
E/Diag_Lib(  276):  Message ID ............... 37 
E/Diag_Lib(  276): qmi_service_release called, user_handle=20200
E/Diag_Lib(  276): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  276): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  276): qmi_service_delete_client_txns : EXIT
E/Diag_Lib(  276): qmi_free_srvc_data : ENTRY
,E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
,E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEI: success getting IMEI
D/LGDRM   (  276): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
I/DrmWrapper( 4594): isDrmV1 =true
,V/DrmWrapper( 4594): isDrmV2 =false
V/MmsConfig( 4594): [isMmsEnabledWhenDataDisabled]value=1
,V/MmsConfigStaticVar( 4594): [setMmsEnabledWhenDataDisabled]enabled=true
,V/MmsConfigStaticVar( 4594): [setMmsEnabledWhenDataRoamingDisabled]enabled=false
,D/CmasFeatures( 4594): [init]CMAS features are initialized for US country. Returning.
,V/Contact ( 4594): Contact init()_Create new insatnce
,I/MessagingNotification( 4594): registerLEDObserver
,I/MessagingNotification( 4594): registerLEDObserver REGISTER
,D/dalvikvm( 1939): GC_CONCURRENT freed 1174K, 23% free 19241K/24832K, paused 3ms+2ms, total 29ms
,I/ActivityManager(  957): Killing 3697:com.google.android.apps.plus/u0a112 (adj 15): empty #17
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,D/dalvikvm(  957): GC_EXPLICIT freed 2269K, 49% free 28966K/56776K, paused 2ms+6ms, total 90ms
,V/MmsConfig( 4594): [getMPDNSupport]is_KrDevice:false is_Mpdn:false is_Roaming:false networkOperator:
,V/TelephonyAutoProfiling(  957): [getValue] FEATURE key : vzw_roaming_state, value : null
D/CountryDetector(  957): The first listener is added
,E/ActivityThread( 4594): Failed to find provider info for com.lge.ims.provider.uc
D/LocationManagerService(  957): getProviders()=[passive, gps]
I/LOG_TAG ( 4594): registerContactDBChangeObserver
D/LocationManagerService(  957): request 44da54a8 passive Request[POWER_NONE passive fastest=0] from android(1000)
D/LocationManagerService(  957): provider request: passive ProviderRequest[ON interval=0]
I/LgeMiscReceiver( 4594): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4594): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 4594): networkInfo.isConnected() = false
,I/ActivityManager(  957): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=4638 uid=10052 gids={50052, 3003}
,V/LGRssiData( 4594): [loadRssi] File not exist 
,V/LGRssiData( 4594): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4594): [loadFeatureFromXml] *** start feature loading from xml
,V/TelephonyAutoProfiling( 4594): [getMatchedProfile] selected file : /cust/config/featureset.xml
,I/ActivityManager(  957): Killing 3724:com.android.vending/u0a50 (adj 15): empty #17
V/TelephonyAutoProfiling( 4594): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 4594): [getValue] FEATURE key : vzw_roaming_state, value : null
D/HyLog   ( 4638): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4638): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4638): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,V/TelephonyAutoProfiling(  957): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  957): [getValue] FEATURE key : vzw_roaming_state, value : null
V/LGRssiData( 4638): [loadRssi] File not exist 
,V/LGRssiData( 4638): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4638): [loadFeatureFromXml] *** start feature loading from xml
W/BaseRuntimeLoader( 4638): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4638): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4638): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4638): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/MobileConnectivityChangeReceiver( 4638): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4638): onReceive CONNECTIVITY_CHANGE networkType=1
V/TelephonyAutoProfiling( 4638): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4638): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4638): [getValue] FEATURE key : vzw_roaming_state, value : null
,E/PhoneMonitor( 4638): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 4638): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  957): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=4653 uid=10066 gids={50066, 4002, 3003, 1028}
I/ActivityManager(  957): Killing 1831:com.google.android.gms.wearable/u0a6 (adj 15): empty #17
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,I/CheckinService( 1939): Checking schedule, now: 1449683679646 next: 1449681243822
,I/CheckinService( 1939): active receiver: enabled
,D/dalvikvm(  268): GC_EXPLICIT freed 44K, 34% free 16472K/24832K, paused 1ms+2ms, total 18ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+1ms, total 13ms
,I/CheckinService( 1939): Preparing to send checkin request
,I/EventLogService( 1939): Accumulating logs since 1449683233130
D/HyLog   ( 4653): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4653): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4653): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/DrmBroadcastReceiver( 4653): Receive CONNECTIVITY_ACTION
,D/LGDMClient( 2797): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMSGCM( 4312): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2797): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4328): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4328): CONNECT : WIFI_CONNECT
I/LGDMClient( 2797): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2797): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2797): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2797): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2797): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/ActivityManager(  957): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4670 uid=10104 gids={50104, 3003, 1028, 1015}
,D/HyLog   ( 4670): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4670): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4670): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/GAV2    ( 4670): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,I/CheckinRequestBuilder( 1939): Checkin reason type: 8 attempt count: 1
D/WifiService(  957): New client listening to asynchronous messages
E/ActivityThread( 1939): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1545): GC_EXPLICIT freed 240K, 29% free 17803K/24832K, paused 1ms+3ms, total 21ms
,V/WebViewChromium( 4670): Binding Chromium to the main looper Looper (main, tid 1) {4286bbf0}
,I/chromium( 4670): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 4670): Initializing chromium process, renderers=0
,W/chromium( 4670): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 4670): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4670): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4670): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4670): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4670): Remote Branch: 
I/Adreno-EGL( 4670): Local Patches: 
I/Adreno-EGL( 4670): Reconstruct Branch: 
,W/BaseRuntimeLoader( 1939): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1939): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1939): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1939): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,I/NSApplication( 4670): Starting up...
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,I/ActivityManager(  957): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4705 uid=10112 gids={50112, 3003, 3002, 1028, 1015}
,I/ActivityManager(  957): Killing 4061:com.lge.bnr/1000 (adj 15): empty #17
V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,D/HyLog   ( 4705): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4705): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4705): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1137): handleBatteryUpdate (2) (100)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  957): battery changed pluggedType: 2
,D/NotificationService(  957): updateLightListLocked :r=null, action=2
W/CheckinRequestBuilder( 1939): awaiting user notification for token
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  957): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  957): DelayedCaptiveCheckState{ when=0 what=1 obj=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false target=com.android.internal.util.StateMachine$SmHandler }
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
I/ActivityManager(  957): Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=4723 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4723): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4723): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4723): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  957): Killing 4277:com.lge.settings.easy/1000 (adj 15): empty #17
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,W/dalvikvm( 4723): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4723): VFY: replacing opcode 0x60 at 0x000b
,D/dalvikvm( 4723): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4723): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4723): VFY: replacing opcode 0x62 at 0x005e
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/MultiDex( 4723): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4723): install
,I/MultiDex( 4723): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4723): loading existing secondary dex files
,I/MultiDex( 4723): load found 3 secondary dex files
,I/MultiDex( 4723): install done
,I/iu.SyncManager( 1939): SYNC; picasa accounts
,D/NetworkLogImpl( 1939): Loaded NetworkSpeedPredictor
,I/iu.Environment( 1939): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,D/dalvikvm( 4723): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,W/dalvikvm( 4723): VFY: unable to resolve instance field 61
,D/dalvikvm( 4723): VFY: replacing opcode 0x54 at 0x0054
,D/dalvikvm( 4723): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4723): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4723): VFY: replacing opcode 0x62 at 0x0067
,D/dalvikvm( 4723): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
D/dalvikvm( 4705): GC_FOR_ALLOC freed 422K, 17% free 20856K/24832K, paused 16ms, total 16ms
W/dalvikvm( 4723): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4723): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4723): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4723): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4723): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428742d8
D/dalvikvm( 4723): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428742d8
,D/dalvikvm( 4723): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428742d8, skipping init
,D/dalvikvm( 4723): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428742d8
D/dalvikvm( 4723): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428742d8
I/iu.UploadsManager( 1939): num queued entries: 0
,V/JNIHelp ( 4723): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/iu.UploadsManager( 1939): num updated entries: 0
,I/dalvikvm-heap( 4705): Grow heap (frag case) to 26.450MB for 4099024-byte allocation
,I/iu.SyncManager( 1939): NEXT; no task
,D/dalvikvm( 4705): GC_CONCURRENT freed 11K, 14% free 24858K/28836K, paused 2ms+1ms, total 13ms
I/ActivityManager(  957): Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=4751 uid=10010 gids={50010, 3003, 1028, 4002}
,D/HyLog   ( 4751): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4751): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4751): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 4723): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x428742d8
,D/dalvikvm( 4723): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x428742d8
D/dalvikvm( 4723): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x428742d8
,D/dalvikvm( 4723): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x428742d8
,D/dalvikvm( 4705): GC_FOR_ALLOC freed 9K, 14% free 24863K/28836K, paused 11ms, total 11ms
E/OpenGL ES Test( 4751): getCurrentLocale == en_US
,E/OpenGL ES Test( 4751): localeFound retString == en_US
E/OpenGL ES Test( 4751): getCurrentLocale == en_US
,E/OpenGL ES Test( 4751): localeFound retString == en_US
D/ALBootInit( 4751): ====action==>android.intent.action.TIME_SET
,I/dalvikvm-heap( 4705): Grow heap (frag case) to 30.363MB for 4099024-byte allocation
,D/ALBootInit( 4751): Alarm ALBootInit: TIME_SET
,D/Alarms  ( 4751): [setNextAlert] start
,D/Alarms  ( 4751): [setNextAlert] (1)
D/dalvikvm( 4705): GC_CONCURRENT freed 2K, 13% free 28867K/32840K, paused 2ms+1ms, total 14ms
,D/Alarms  ( 4751):  minTime  = 0
,D/dalvikvm( 4705): WAIT_FOR_CONCURRENT_GC blocked 4ms
,D/Alarms  ( 4751):  -- OK multi -- 0
,E/jeny.kim( 4751): [setNextAlert] setNextAlert  temp_Alarmlink + 
,E/jeny.kim( 4751): [setNextAlert]setNextAlert temp_AlarmLinkText + 
,D/Alarms  ( 4751): setStatusBarIcon : false
,I/dalvikvm-heap( 4705): Grow heap (frag case) to 34.273MB for 4099024-byte allocation
,D/Alarms  ( 4751): Enter formatDayAndTime(final Context context, long timeInMiliSec)
,D/WorldClockReceiver( 4751): ====action==>android.intent.action.TIME_SET
,E/OpenGL ES Test( 4751): getCurrentLocale == en_US
E/OpenGL ES Test( 4751): localeFound retString == en_US
E/OpenGL ES Test( 4751): getCurrentLocale == en_US
E/OpenGL ES Test( 4751): localeFound retString == en_US
E/OpenGL ES Test( 4751): getCurrentLocale == en_US
,E/OpenGL ES Test( 4751): localeFound retString == en_US
E/OpenGL ES Test( 4751): getCurrentLocale == en_US
,E/OpenGL ES Test( 4751): localeFound retString == en_US
,E/OpenGL ES Test( 4751): isExistDatabase = false
,I/CommonUtil( 4751): BUILD Country: EU
E/OpenGL ES Test( 4751): loadMapCityData() -- S
E/OpenGL ES Test( 4751): getCurrentLocale == en_US
E/OpenGL ES Test( 4751): localeFound retString == en_US
E/OpenGL ES Test( 4751): getCurrentLocale == en_US
,E/OpenGL ES Test( 4751): localeFound retString == en_US
,I/ProviderInstaller( 4723): Installed default security provider GmsCore_OpenSSL
,E/OpenGL ES Test( 4751): loadMapCityData() - While S
,D/dalvikvm( 4705): GC_CONCURRENT freed 3K, 11% free 33029K/36844K, paused 5ms+1ms, total 18ms
,I/dalvikvm( 4723): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4723): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4723): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4723): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4723): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4723): VFY: replacing opcode 0x6e at 0x0201
,E/OpenGL ES Test( 4751): loadMapCityData() - While E
,E/OpenGL ES Test( 4751): loadMapCityData() -- E
E/OpenGL ES Test( 4751): getCurrentLocale == en_US
E/OpenGL ES Test( 4751): localeFound retString == en_US
E/OpenGL ES Test( 4751): getCurrentLocale == en_US
,E/OpenGL ES Test( 4751): localeFound retString == en_US
,E/OpenGL ES Test( 4751): [updateWidgetDST] backup_cityInfoList is null >>>>
,I/ActivityManager(  957): Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory: pid=4770 uid=10015 gids={50015, 3003, 1028, 1015}
,I/ActivityManager(  957): Killing 4395:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 4770): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4770): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4770): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/WVCdm   (  271): Instantiating CDM.
,I/WVCdm   (  271): Level3 Library Nov 20 2013 18:09:31
,D/DrmWidevineDash(  271): calling OEMCrypto_Initialize, g_qsee_apps_version = 6
D/QSEECOMAPI: (  271): QSEECom_get_handle sb_length = 0x19000
,D/QSEECOMAPI: (  271): App is not loaded in QSEE
I/Config  ( 4770): LGCalendar ver.4.2.6
I/Config  ( 4770): start check model
,I/Config  ( 4770): start check native_ca
,E/Config  ( 4770): [setCountryAndOperator] Operator=OPEN, Country=EU
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
,D/GCM     ( 1545): Connected
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:1
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:firmware, action:2
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/GCM     ( 1545): Message class com.google.f.a.a.p
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/QSEECOMAPI: (  271): Loaded image: APP id = 2
D/DrmWidevineDash(  271): OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e06000
,E/DrmWidevineDash(  271): sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1e06000
,D/DrmWidevineDash(  271): OEMCrypto_Initialize exit returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_APIVersion...
,D/DrmWidevineDash(  271): OEMCrypto_APIVersion = 8
,D/DrmWidevineDash(  271): calling OEMCrypto_IsKeyboxValid...
,D/DrmWidevineDash(  271): OEMCrypto_IsKeyboxValid returns 0
,D/WVCdm   (  271): OEMCrypto_Initialize Level 1 success. I will use level 1.
I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  271): PrepareKeyRequest: nonce=2484065099
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm( 4723): Trying to load lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a92160
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
D/dalvikvm( 4723): Added shared lib /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a92160
,D/dalvikvm( 4723): No JNI_OnLoad found in /data/data/com.google.android.gms/app_dg_cache/69C93D89AA87E126AABFDE6B8111A5045CA28EB7/lib/libd24C93342F304.so 0x42a92160, skipping init
,D/CalendarWidget( 4770): Agenda AppWidgetService got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory }
,I/InitNotificationRingtoneService( 4770): Start InitializeAlertRingtoneService.onHandleIntent
,I/ActivityManager(  957): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4797 uid=10016 gids={50016, 3003, 1028, 1015}
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
,I/WVCdm   (  271): CdmEngine::OpenSession
,D/DrmWidevineDash(  271): calling OEMCrypto_OpenSession...
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_OpenSession returns 0
,I/WVCdm   (  271): CdmEngine::QueryKeyControlInfo
I/WVCdm   (  271): CdmEngine::GenerateKeyRequest
,D/DrmWidevineDash(  271): calling OEMCrypto_LoadDeviceRSAKey. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_LoadDeviceRSAKey returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GetDeviceID...
,D/DrmWidevineDash(  271): OEMCrypto_GetDeviceID returns 0
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateNonce. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateNonce returns 0
D/WVCdm   (  271): PrepareKeyRequest: nonce=587349271
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature needs buffer size = 256
D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 7
,D/DrmWidevineDash(  271): calling OEMCrypto_GenerateRSASignature. SID = 1
,D/dalvikvm(  957): GC_EXPLICIT freed 797K, 49% free 29285K/56776K, paused 2ms+8ms, total 119ms
,I/InitNotificationRingtoneService( 4770): internal content query returns 1 results.
,I/InitNotificationRingtoneService( 4770): Found default schedule notification : Schedule.ogg(id:42)
,I/InitNotificationRingtoneService( 4770): set default noti to content://media/internal/audio/media/42
,I/InitNotificationRingtoneService( 4770): End InitializeAlertRingtoneService.onHandleIntent
,D/HyLog   ( 4797): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4797): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4797): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/CalendarProvider2( 4797): Created com.android.providers.calendar.CalendarAlarmManager@4288eae0(com.android.providers.calendar.CalendarProvider2@42885a48)
,D/DrmWidevineDash(  271): OEMCrypto_GenerateRSASignature returns 0
,I/ActivityManager(  957): Start proc com.lge.task for broadcast com.lge.task/.widget.TasksWidgetProvider: pid=4818 uid=10043 gids={50043, 3003, 1028, 1015}
I/WVCdm   (  271): CdmEngine::CloseSession
,D/DrmWidevineDash(  271): calling OEMCrypto_CloseSession. SID = 1
,D/DrmWidevineDash(  271): OEMCrypto_CloseSession returns 0
I/ActivityManager(  957): Killing 4233:com.lge.sync/1000 (adj 15): empty #17
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4818): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4818): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4818): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,E/TASKS   ( 4818): init() PortStorageManger PRIMARY_STORAGE_PATH :/storage/emulated/0
,D/TASKS_APP_WIDGET( 4818): onReceive() #################################################
,I/TASKS   ( 4818): getCurrentThemeInfo START #############################
,I/TASKS   ( 4818): com.lge.launcher2.theme.optimus
,I/TASKS   ( 4818): com.lge.task
I/TASKS   ( 4818): getCurrentThemeInfo END #############################
I/TASKS   ( 4818): loadThemeResources packageName : com.lge.task
I/TASKS   ( 4818): loadLocalResId #############################
,D/TASKS_APP_WIDGET( 4818): intentAction : android.intent.action.TIME_SET
,I/ActivityManager(  957): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4835 uid=10122 gids={50122}
,I/ActivityManager(  957): Killing 4368:com.lge.qremote/u0a96 (adj 15): empty #17
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 4835): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4835): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4835): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 4835): No JNI_OnLoad found in /vendor/lib/libTimeService.so 0x42877f58, skipping init
D/TimeService( 4835): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1449683680839
D/        ( 4835): TimeServiceNative: User Time to be set is 1449683680839
D/QC-time-services( 4835): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4835): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4835): Lib:time_genoff_operation: pargs->ts_val = 1449683680839
,D/QC-time-services(  520): Daemon: Connection accepted:time_genoff
D/QC-time-services( 4835): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  520): Daemon:Received base = 2, unit = 1, operation = 0,value = 1449683680839
D/QC-time-services(  520): Daemon:genoff_opr: Base = 2, val = 1449683680839, operation = 0
D/QC-time-services(  520): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS3/16/70 5:39:33
D/QC-time-services(  520): Daemon:Value read from RTC seconds = 9092373000
D/QC-time-services(  520): Daemon:new time 1449683680839 
D/QC-time-services(  520): Daemon: delta 1440591307839 genoff 1440591307839 
D/QC-time-services(  520): Daemon:genoff_persistent_update: Writing genoff = 1440591307839 to memory
D/QC-time-services(  520): Daemon:Opening File: /data/time/ats_2
,D/QC-time-services(  520): Daemon:time_persistent_memory_opr:Genoff write operation 
,D/QC-time-services(  520): Updating the TOD offset
D/QC-time-services(  520): Daemon:genoff_persistent_update: Writing genoff = 1440591307839 to memory
D/QC-time-services(  520): Daemon:Opening File: /data/time/ats_1
,D/QC-time-services(  520): Daemon:time_persistent_memory_opr:Genoff write operation 
E/QC-time-services(  520): Daemon:Update to modem bit set
D/QC-time-services(  520): Daemon:genoff_send_modem: Sending data to MODEM !
,D/QC-time-services(  520): Daemon: Base = 2, Value being sent to MODEM = 1133718880839
,E/QC-time-services( 4835): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,I/ActivityManager(  957): Killing 4535:com.lge.appbox.client/u0a11 (adj 15): empty #17
D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
,E/QC-time-services(  520): Daemon: Time-services: Waiting to acceptconnection
,E/QC-time-services(  520): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
D/QcConnectivityService(  957): handleInetConditionHoldEnd: net=1, condition=100, published condition=0
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,I/ActivityManager(  957): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=4849 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
,D/HyLog   ( 4849): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4849): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4849): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/AppUp4  ( 4849):  AppBoxContentProvider onCreate
,W/AppUp4  ( 4849):  [AppBoxDatabaseHelper] construct
,I/AppUp4  ( 4849):  setFingerPrint start
,I/AppUp4  ( 4849):  newfinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
,I/AppUp4  ( 4849):  beforefinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
,I/AppUp4  ( 4849):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 4849): AppBoxApplication onCreate()
I/NetworkStateForAutoUpdateMonitor( 4849): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4849): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4849): [onReceive] connect :true
,I/NetworkStateForAutoUpdateMonitor( 4849): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4849): onReceive
,D/AppUp4:CustFacade( 4849): Context : android.app.ReceiverRestrictedContext@4288a110
D/AppUp4:CustFacade( 4849): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 4849): isOpenOperator : true
,D/AppUp4:CustFacade( 4849): isPhone : true
,I/LicenseContentProvider( 2903): start selecting data
,D/SIMObserver( 2903): simInfo1
,I/AppUp4:EulaManager( 4849): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 4849): begin check event
I/AppUp4:CustModeStarterReceiver( 4849): Event For GoodConnectivity
,D/AppUp4:CustModeStarterReceiver( 4849): runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
D/AppUp4:CustModeStarterReceiver( 4849): call method handleAsyncCustNotification.
E/AppUp4:CustModeStarterReceiver( 4849): handleAsync eula : false
E/AppUp4:CustModeStarterReceiver( 4849): handleAsync isTriedOnce : false
,E/AppUp4:CustModeStarterReceiver( 4849): handleAsyncCustNotification do not startCustService
,V/DownloadManager( 4554): DownloadService onCreate
,I/DownloadManager( 4554): in removeSpuriousFiles
,D/EAS     ( 4075): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 4075): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4554): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4554): created cursor android.database.sqlite.SQLiteCursor@428d3248 on behalf of 4554
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
V/DownloadManager( 4554): DownloadService onStartCommand
V/DownloadManager( 4554): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
V/DownloadManager( 4554): created cursor android.database.sqlite.SQLiteCursor@428d5820 on behalf of 4554
I/LgeMiscReceiver( 4594): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
I/LgeMiscReceiver( 4594): action = android.net.conn.CONNECTIVITY_CHANGE
I/DownloadManager( 4554): in trimDatabase
I/LgeMiscReceiver( 4594): networkInfo.isConnected() = true
D/PhoneState( 4594): setPdpRejectCasuse : false
W/Settings( 4075): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/MobileConnectivityChangeReceiver( 4638): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
D/MobileConnectivityChangeReceiver( 4638): onReceive CONNECTIVITY_CHANGE networkType=1
V/DownloadManager( 4554): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4554): created cursor android.database.sqlite.SQLiteCursor@428d70d8 on behalf of 4554
D/DrmBroadcastReceiver( 4653): Receive CONNECTIVITY_ACTION
,D/DrmBroadcastReceiver( 4653): 1  network is available. Sync DRM Time with NTP
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
V/DrmService( 4653): Service onCreate
D/DrmService( 4653): Received new request = 2
D/LGDMClient( 2797): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
V/DownloadManager( 4554): DownloadService onDestroy
I/DrmSntpClient( 4653): Start Sync process
D/DrmSntpClient( 4653): Server : 0
E/DataScheduler( 4653): isDataSchedulerEnabled():false
D/LGDMClient( 2797): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/WifiServiceExtension(  957): MESSAGE_INTERNET_CHECK msg is received.
,D/LGDMSGCM( 4312): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
W/ActivityThread(  957): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/LGDMClient( 2797): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,I/NFS     ( 4328): connectivityManager.getNetworkInfo = TYPE_WIFI
,I/Wireless_Storage( 4328): CONNECT : WIFI_CONNECT
,E/LGDMClient( 2797): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,D/LGDMClient( 2797): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2797): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/LGDMClient( 2797): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/NetworkStateForAutoUpdateMonitor( 4849): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 4849): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
I/NetworkStateForAutoUpdateMonitor( 4849): [onReceive] connect :true
D/dalvikvm( 4723): DexOpt: --- BEGIN 'f.apk' (bootstrap=0) ---
,I/NetworkStateForAutoUpdateMonitor( 4849): [onReceive] request level :IDLE....
,I/AppUp4:CustModeStarterReceiver( 4849): onReceive
,D/AppUp4:CustFacade( 4849): Context : android.app.ReceiverRestrictedContext@4288a110
D/AppUp4:CustFacade( 4849): isCustomizationCompleted : false
D/AppUp4:CustFacade( 4849): isOpenOperator : true
,D/AppUp4:CustFacade( 4849): isPhone : true
,I/LicenseContentProvider( 2903): start selecting data
,D/SIMObserver( 2903): simInfo1
,I/AppUp4:EulaManager( 4849): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 4849): begin check event
,I/AppUp4:CustModeStarterReceiver( 4849): Event For GoodConnectivity, noConnectivity : false, but skip! 
,V/DownloadManager( 4554): DownloadService onCreate
,I/DownloadManager( 4554): in removeSpuriousFiles
D/EAS     ( 4075): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,V/DownloadManager( 4554): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,D/EAS     ( 4075): [EmailEAS.java] onReceive() - bisConnected = true (at EasBroadcastReceiver.java onReceive 39)
,V/DownloadManager( 4554): created cursor android.database.sqlite.SQLiteCursor@428daaf8 on behalf of 4554
,I/DownloadManager( 4554): in trimDatabase
,V/DownloadManager( 4554): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
I/LgeMiscReceiver( 4594): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 4594): action = android.net.conn.CONNECTIVITY_CHANGE
I/LgeMiscReceiver( 4594): networkInfo.isConnected() = true
,D/PhoneState( 4594): setPdpRejectCasuse : false
,D/MobileConnectivityChangeReceiver( 4638): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,D/MobileConnectivityChangeReceiver( 4638): onReceive CONNECTIVITY_CHANGE networkType=1
,W/Settings( 4075): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/DownloadManager( 4554): created cursor android.database.sqlite.SQLiteCursor@428dc0c8 on behalf of 4554
,V/DownloadManager( 4554): DownloadService onStartCommand
,V/DownloadManager( 4554): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4554): created cursor android.database.sqlite.SQLiteCursor@428de660 on behalf of 4554
,D/LGDMClient( 2797): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,I/LGDrmService( 4653): _DRM_ServiceGet() : Bind lgdrm service
I/LGDRM   (  276): [DRM] SET TIME : YR=2015, MON=12, DAY=9
,I/LGDRM   (  276): [DRM] SET TIME : HR=17, MIN=54, SEC=41
,D/LGDMClient( 2797): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
D/LGDMSGCM( 4312): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,V/DownloadManager( 4554): DownloadService onDestroy
I/DrmSntpClient( 4653): Synched
D/DrmService( 4653): Completed !! request = 2
,D/DrmService( 4653): Request count = 0
,V/DrmService( 4653): Service onDestroy
,I/LGDMClient( 2797): [DmServiceProcessor.java] [onHandleIntent()] : [117] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
,E/LGDMClient( 2797): [DmNotiService.java] [onCreate()] : [143] : DmNotiService.onCreate()
,W/ContextImpl( 4312): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/NFS     ( 4328): connectivityManager.getNetworkInfo = TYPE_WIFI
I/Wireless_Storage( 4328): CONNECT : WIFI_CONNECT
,D/LGDMClient( 2797): [DmNotiService.java] [onStartCommand()] : [177] : in the new onStartCommand()
,D/LGDMClient( 2797): [DmNotiService.java] [handleStart()] : [206] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
,I/LGDMClient( 2797): [DmEULAPreference.java] [isEULAEnabled()] : [57] : Checking EULA Enabled
I/ActivityManager(  957): Killing 3679:com.android.gallery3d/u0a27 (adj 15): empty #17
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/dalvikvm( 4875): DexOpt: load 3ms, verify+opt 4ms, 128132 bytes
,D/WeatherAncestor( 1883): 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 18:54:41
V/WifiServiceExtension(  957): isInternetConnectionAvailable - We got a valid response : 204
,I/WifiServiceExtension(  957): MESSAGE_INTERNET_CHECK msg is received. IsInternetAvailable = true
,D/UpdateThreadPoolManager( 1883): 2 : This is isUpdating : false
D/Weather_cast( 1883): 2 : Request from alarm is Canceled
,D/WeatherAncestor( 1883): 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 18:54:41
,D/WeatherService( 1883): 2 : onStartCommand, intent!=null, action: com.lge.sizechangable.weather.action.setweathercast
D/WeatherQuickCover( 1883): 2 : quick cover state : opened : 0
,D/GCM     ( 1545): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/Weather.Utils( 1883): 2 : Utils getTopActivity com.lge.launcher2 / false
D/Weather.Utils( 1883): 2 : Utils getTopActivity com.lge.easyhome / false
,D/WeatherService( 1883): 2 : shouldTimeTickRegistered : false
,D/AuthorizationBluetoothService( 1545): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1545): Proximity feature is not enabled.
,V/GmsCoreStatsServiceLauncher( 1939): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/dalvikvm( 4723): DexOpt: --- END 'f.apk' (success) ---
,D/dalvikvm( 4723): DEX prep '/data/data/com.google.android.gms/app_fb/f.apk': unzip in 2ms, rewrite 90ms
,I/Adreno-EGL( 4723): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4723): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4723): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4723): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4723): Remote Branch: 
I/Adreno-EGL( 4723): Local Patches: 
I/Adreno-EGL( 4723): Reconstruct Branch: 
I/ActivityManager(  957): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.ContentSyncService: pid=4883 uid=10050 gids={50050, 3003, 1028, 1015}
,D/HyLog   ( 4883): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4883): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4883): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  957): Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4896 uid=10006 gids={50006, 3007, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001}
,D/HyLog   ( 4896): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4896): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4896): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm(  268): GC_EXPLICIT freed 43K, 34% free 16472K/24832K, paused 1ms+1ms, total 17ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 15ms
,W/dalvikvm( 4896): VFY: unable to resolve static field 590 (PR_SET_DUMPABLE) in Landroid/system/OsConstants;
,D/dalvikvm( 4896): VFY: replacing opcode 0x60 at 0x000b
,D/LocationInitializer( 1939): Restart initialization of location
,D/WifiStateMachine(  957): handleMessage: E msg.what=131155
,D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiNative-wlan0(  957): doString: SIGNAL_POLL
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4232): wlan0: Control interface command 'SIGNAL_POLL'
,I/dalvikvm( 4883): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 4883): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4883): VFY: replacing opcode 0x6e at 0x000b
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 0ms+2ms, total 13ms
D/dalvikvm( 4896): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4896): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4896): VFY: replacing opcode 0x62 at 0x005e
,D/wpa_supplicant( 4232): nl80211: survey data missing!
,I/MultiDex( 4896): VM with version 1.6.0 does not have multidex support
,I/MultiDex( 4896): install
,D/WifiStateMachine(  957): handleMessage: X
E/Parcel  (  511): Reading a NULL string not supported here.
,E/Parcel  (  511): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
I/ActivityManager(  957): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.babel.realtimechat.RequestWriter$NetworkStateReceiver: pid=4913 uid=10077 gids={50077, 3003, 1028, 1015, 3002}
,I/MultiDex( 4896): MultiDexExtractor.load(/data/app/com.google.android.gms-1.apk, false)
,I/MultiDex( 4896): loading existing secondary dex files
,I/MultiDex( 4896): load found 3 secondary dex files
D/HyLog   ( 4913): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/Finsky  ( 4883): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
D/HyLog   ( 4913): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4913): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/MultiDex( 4896): install done
,D/dalvikvm( 4896): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
W/dalvikvm( 4896): VFY: unable to resolve instance field 61
,D/dalvikvm( 4896): VFY: replacing opcode 0x54 at 0x0054
D/dalvikvm( 4896): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4896): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4896): VFY: replacing opcode 0x62 at 0x0067
D/dalvikvm( 4896): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4896): VFY: unable to resolve static field 156 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4896): VFY: replacing opcode 0x62 at 0x000a
D/dalvikvm( 4896): DexOpt: couldn't find field Landroid/content/pm/ApplicationInfo;.splitSourceDirs
,I/dalvikvm( 4896): DexOpt: unable to optimize instance field ref 0x003d at 0x58 in Lcom/google/android/gms/common/util/ax;.a
,D/dalvikvm( 4896): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4287bf80
D/dalvikvm( 4896): Added shared lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4287bf80
,D/dalvikvm( 4896): No JNI_OnLoad found in /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4287bf80, skipping init
,D/dalvikvm( 4896): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4287bf80
D/dalvikvm( 4896): Added shared lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4287bf80
,V/JNIHelp ( 4896): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,I/Adreno-EGL( 4723): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4723): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4723): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4723): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4723): Remote Branch: 
I/Adreno-EGL( 4723): Local Patches: 
I/Adreno-EGL( 4723): Reconstruct Branch: 
,I/dalvikvm( 4883): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 4883): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4883): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 4883): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4883): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4883): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4883): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/Finsky  ( 4883): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,I/Adreno-EGL( 4723): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4723): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4723): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4723): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4723): Remote Branch: 
I/Adreno-EGL( 4723): Local Patches: 
I/Adreno-EGL( 4723): Reconstruct Branch: 
,D/dalvikvm( 4896): Trying to load lib /data/app-lib/com.google.android.gms-1/libgmscore.so 0x4287bf80
D/dalvikvm( 4896): Shared lib '/data/app-lib/com.google.android.gms-1/libgmscore.so' already loaded in same CL 0x4287bf80
D/dalvikvm( 4896): Trying to load lib /data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so 0x4287bf80
,D/dalvikvm( 4896): Shared lib '/data/app-lib/com.google.android.gms-1/libconscrypt_gmscore_jni.so' already loaded in same CL 0x4287bf80
,W/Settings( 4883): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4883): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/dalvikvm( 4883): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4883): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4883): VFY: replacing opcode 0x6e at 0x011e
I/dalvikvm( 4883): Could not find method com.google.android.finsky.layout.DocImageView.setTransitionName, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4883): VFY: unable to resolve virtual method 23416: Lcom/google/android/finsky/layout/DocImageView;.setTransitionName (Ljava/lang/String;)V
,D/dalvikvm( 4883): VFY: replacing opcode 0x6e at 0x0292
I/dalvikvm( 4883): Could not find method com.google.android.play.layout.PlayCardViewBase.setTransitionGroup, referenced from method com.google.android.finsky.utils.PlayCardUtils.bindCard
W/dalvikvm( 4883): VFY: unable to resolve virtual method 43938: Lcom/google/android/play/layout/PlayCardViewBase;.setTransitionGroup (Z)V
,D/dalvikvm( 4883): VFY: replacing opcode 0x6e at 0x029a
,W/Settings( 4723): Setting install_non_market_apps has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/CheckinRequestBuilder( 1939): Classify the device as Phone.
,I/dalvikvm( 4883): Could not find method android.view.View.getTransitionName, referenced from method com.google.android.finsky.navigationmanager.NavigationManager.showPage
W/dalvikvm( 4883): VFY: unable to resolve virtual method 10122: Landroid/view/View;.getTransitionName ()Ljava/lang/String;
D/dalvikvm( 4883): VFY: replacing opcode 0x6e at 0x001a
,I/MediaCodecList( 4913): getNewMediaCodecItem [0][DTSDecode][audio/dts]
I/MediaCodecList( 4913): getNewMediaCodecItem [0][DDPDecode][audio/eac3]
I/MediaCodecList( 4913): getNewMediaCodecItem [0][DDPDecode][audio/ac3]
,I/MediaCodecList( 4913): getNewMediaCodecItem [0][OMX.VisualOn.Video.Decoder.XXX][video/hevc]
I/Babel   ( 4913): MmsConfig: mnc/mcc: 0/0
,I/Babel   ( 4913): MmsConfig.loadMmsSettings
,I/Babel   ( 4913): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,I/Babel   ( 4913): MmsConfig.loadFromDatabase
,V/DownloadManager( 4554): starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,I/dalvikvm( 4883): Could not find method android.app.admin.DevicePolicyManager.isProfileOwnerApp, referenced from method com.google.android.finsky.api.DfeApiContext.isManagedContext
W/dalvikvm( 4883): VFY: unable to resolve virtual method 328: Landroid/app/admin/DevicePolicyManager;.isProfileOwnerApp (Ljava/lang/String;)Z
D/dalvikvm( 4883): VFY: replacing opcode 0x6e at 0x0049
,V/DownloadManager( 4554): created cursor android.database.sqlite.SQLiteCursor@428e37b0 on behalf of 4883
,W/BaseRuntimeLoader( 4913): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4913): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4913): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4913): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
E/Babel   ( 4913): canonicalizeMccMnc: invalid mccmnc 
,I/Babel   ( 4913): MmsConfig.loadFromResources
E/Babel   ( 4913): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 4913): MmsConfig.loadMmsSettings: mUserAgent=LG-D802 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D802-M3-D1.xml
,W/Settings( 4913): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,V/TelephonyAutoProfiling(  957): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  957): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 4913): [loadRssi] File not exist 
V/LGRssiData( 4913): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 4913): [loadFeatureFromXml] *** start feature loading from xml
D/Finsky  ( 4883): [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4883): [1] 2.run: Finished loading 1 libraries.
,V/TelephonyAutoProfiling( 4913): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 4913): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 4913): [getValue] FEATURE key : vzw_roaming_state, value : null
,I/ProviderInstaller( 4896): Installed default security provider GmsCore_OpenSSL
,D/Finsky  ( 4883): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/CalendarWidget( 4770): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 4770): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
D/TASKS_APP_WIDGET( 4818): onReceive() #################################################
,I/TASKS   ( 4818): getCurrentThemeInfo START #############################
I/TASKS   ( 4818): com.lge.launcher2.theme.optimus
I/TASKS   ( 4818): com.lge.task
I/TASKS   ( 4818): getCurrentThemeInfo END #############################
I/TASKS   ( 4818): loadThemeResources packageName : com.lge.task
D/Finsky  ( 4883): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
I/TASKS   ( 4818): loadLocalResId #############################
,D/TASKS_APP_WIDGET( 4818): intentAction : com.lge.task.APPWIDGET_UPDATE
,D/CalendarWidget( 4770): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 4770): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
,D/GCM     ( 1545): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1545): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,E/AuthorizationBluetoothService( 1545): Proximity feature is not enabled.
,I/dalvikvm( 4896): Could not find method android.os.UserManager.getUserProfiles, referenced from method com.google.android.gms.wearable.service.n.a
W/dalvikvm( 4896): VFY: unable to resolve virtual method 1402: Landroid/os/UserManager;.getUserProfiles ()Ljava/util/List;
,D/dalvikvm( 4896): VFY: replacing opcode 0x6e at 0x003f
,V/GmsCoreStatsServiceLauncher( 1939): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/WearableService( 4896): callingUid 10006, callindPid: 4896
E/dalvikvm( 4896): Could not find class 'android.telecom.TelecomManager', referenced from method com.google.android.gms.wearable.service.y.a
W/dalvikvm( 4896): VFY: unable to resolve check-cast 869 (Landroid/telecom/TelecomManager;) in Lcom/google/android/gms/wearable/service/y;
,D/dalvikvm( 4896): VFY: replacing opcode 0x1f at 0x0054
,W/dalvikvm( 4896): VFY: unable to find class referenced in signature (Landroid/telecom/TelecomManager;)
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/dalvikvm( 4896): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.kf.a
W/dalvikvm( 4896): VFY: unable to resolve virtual method 460: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4896): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4896): Could not find method android.app.Notification$Builder.setLocalOnly, referenced from method com.google.android.gms.common.kf.b
W/dalvikvm( 4896): VFY: unable to resolve virtual method 166: Landroid/app/Notification$Builder;.setLocalOnly (Z)Landroid/app/Notification$Builder;
,D/dalvikvm( 4896): VFY: replacing opcode 0x6e at 0x0201
,D/LocationInitializer( 1939): Restart initialization of location
,E/MDM     ( 1422): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/MDM     ( 1422): [86] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/dalvikvm( 4883): Total arena pages for JIT: 11
,I/dalvikvm( 4883): Total arena pages for JIT: 12
I/dalvikvm( 4883): Total arena pages for JIT: 13
,I/dalvikvm( 4883): Total arena pages for JIT: 14
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=105
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5007
D/QcConnectivityService(  957): handleInetConditionHoldEnd: net=1, condition=100, published condition=100
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/CheckinTask( 1939): Sending checkin request (11511 bytes)
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,E/Babel   ( 4913): UserRecoverableAuthException.
,E/Babel   ( 4913): com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
E/Babel   ( 4913): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4913): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:190)
E/Babel   ( 4913): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4913): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4913): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4913): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4913): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4913): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4913): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4913): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
,E/Babel   ( 4913): Error getting auth token
,E/Babel   ( 4913): com.google.android.apps.babel.util.AccountsUtil$BabelAuthException
E/Babel   ( 4913): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:200)
E/Babel   ( 4913): 	at com.google.android.apps.babel.network.c.d(SourceFile:83)
E/Babel   ( 4913): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4913): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4913): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4913): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4913): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4913): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4913): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
,E/Babel   ( 4913): Account registration failedRedacted-21
,E/Babel   ( 4913): com.google.android.apps.babel.realtimechat.RequestWriter$BabelClientException: null -- null
E/Babel   ( 4913): 	at com.google.android.apps.babel.network.c.d(SourceFile:115)
E/Babel   ( 4913): 	at com.google.android.apps.babel.network.c.cO(SourceFile:123)
E/Babel   ( 4913): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:244)
E/Babel   ( 4913): 	at com.google.android.apps.babel.protocol.p.a(SourceFile:93)
E/Babel   ( 4913): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:554)
E/Babel   ( 4913): 	at com.google.android.apps.babel.protocol.ServerRequest$GoogleServerRequest.a(SourceFile:440)
E/Babel   ( 4913): 	at com.google.android.apps.babel.realtimechat.dt.b(SourceFile:880)
E/Babel   ( 4913): 	at com.google.android.apps.babel.realtimechat.du.run(SourceFile:1068)
,I/Babel   ( 4913): Account setup failed with error state:106 account:Redacted-21
,I/Babel   ( 4913): Account sign in complete with state 106account: Redacted-21
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.talk, service: oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native
I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/chat https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/hangouts https://www.googleapis.com/auth/chat.native without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,D/Finsky  ( 4883): [420] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4883): [1] 5.onFinished: Installation state replication succeeded.
I/ActivityManager(  957): Killing 4751:com.lge.clock/u0a10 (adj 15): empty #17
,D/NotificationService(  957): updateLightListLocked :r=NotificationRecord(0x43257c08: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,E/Babel   ( 4913): Unexpected exception while authenticating.
,E/Babel   ( 4913): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
E/Babel   ( 4913): 	at com.google.android.gms.auth.a.b(Unknown Source)
E/Babel   ( 4913): 	at com.google.android.gms.auth.a.a(Unknown Source)
E/Babel   ( 4913): 	at com.google.android.apps.babel.util.AccountsUtil.c(SourceFile:187)
E/Babel   ( 4913): 	at com.google.android.apps.babel.network.c.cP(SourceFile:138)
E/Babel   ( 4913): 	at com.google.android.apps.babel.realtimechat.ca.run(SourceFile:5226)
E/Babel   ( 4913): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/Babel   ( 4913): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/Babel   ( 4913): 	at java.lang.Thread.run(Thread.java:841)
D/NotificationService(  957): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,I/CalendarProvider2( 4797): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/ContentResolver( 4797): Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,D/AlertReceiver( 4770): onReceive: a=android.intent.action.PROVIDER_CHANGED Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.alerts.AlertReceiver }
,D/AlertService( 4770): 0 Action = android.intent.action.PROVIDER_CHANGED
,D/CalendarWidget( 4770): Agenda AppWidgetService got the intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetService$CalendarFactory }
,D/AlertService( 4770): Beginning updateAlertNotification
,D/AlertService( 4770): No fired or scheduled alerts
,I/ActivityManager(  957): Killing 4835:com.qualcomm.timeservice/u0a122 (adj 15): empty #17
,D/CalendarWidget( 4770): Agenda AppWidgetService init broadcastReceiver
,D/CalendarWidget( 4770): Agenda AppWidgetProvider got the intent: Intent { act=com.lge.calendar.action.APPWIDGET_UPDATE flg=0x10 cmp=com.android.calendar/.widget.CalendarAppWidgetProvider }
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/CheckinRequestBuilder( 1939): Checkin reason type: 8 attempt count: 1
E/ActivityThread( 1939): Failed to find provider info for com.google.android.wearable.settings
,D/dalvikvm( 1545): null clazz in OP_INSTANCE_OF, single-stepping
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/ProcessCpuTracker(  957): Skipping unknown process pid 4864
,W/ProcessCpuTracker(  957): Skipping unknown process pid 4982
,E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,D/dalvikvm(  957): GC_EXPLICIT freed 1563K, 49% free 29439K/56776K, paused 3ms+6ms, total 90ms
,D/dalvikvm( 1545): GC_EXPLICIT freed 1163K, 29% free 17803K/24832K, paused 1ms+2ms, total 23ms
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: AndroidCheckInServer
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> AndroidCheckInServer without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  957): updateLightListLocked :r=NotificationRecord(0x44d44eb0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  957): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
W/CheckinRequestBuilder( 1939): awaiting user notification for token
,I/CheckinRequestBuilder( 1939): Classify the device as Phone.
,I/CheckinTask( 1939): Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,I/CheckinService( 1939): Checking schedule, now: 1449683682210 next: 1450261078208
,I/CheckinService( 1939): active receiver: disabled
,I/CheckinService( 1939): Checking schedule, now: 1449683682255 next: 1450261078208
,I/CheckinService( 1939): active receiver: disabled
,D/GCM     ( 1545): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,D/Finsky  ( 4883): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
D/dalvikvm( 4883): DexOpt: couldn't find static field Landroid/os/Build;.SUPPORTED_ABIS
W/dalvikvm( 4883): VFY: unable to resolve static field 159 (SUPPORTED_ABIS) in Landroid/os/Build;
,D/dalvikvm( 4883): VFY: replacing opcode 0x62 at 0x0037
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4883): [1] 1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4883): [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,W/Finsky  ( 4883): [1] 2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,D/Finsky  ( 4883): [1] DailyHygiene.logDeviceFeaturesAndContinue: Logging device features
,D/Finsky  ( 4883): [1] DailyHygiene.flushEventLogsAndContinue: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 4883): [1] DailyHygiene.reschedule: Scheduling new run in 29 minutes (failures=2)
,D/DeviceConnectionService( 1422): client connected with version: 7571000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  957): handleMessage: E msg.what=131155
,D/WifiStateMachine(  957): processMsg: ConnectedState
,D/WifiStateMachine(  957): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  957): doString: SIGNAL_POLL
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4232): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4232): nl80211: survey data missing!
,E/Parcel  (  511): Reading a NULL string not supported here.
,E/Parcel  (  511): Reading a NULL string not supported here.
,D/WifiStateMachine(  957): handleMessage: X
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4670): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.459167 Y: -0.401291 Z: 9.758148 
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459167 .y:-0.401291 .z:9.758148
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,I/ActivityManager(  957): Killing 2903:com.lge.eula/1000 (adj 15): empty #17
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.469849 Y: -0.403122 Z: 9.758408 
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.469849 .y:-0.403122 .z:9.758408
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityThread( 4849): Removing dead content provider:android.content.ContentProviderProxy@42890810
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  957): Killing 4075:com.lge.email/u0a24 (adj 15): empty #17
,I/ActivityManager(  957): Killing 4849:com.lge.appbox.client/u0a11 (adj 15): empty #18
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  957): Killing 4594:com.android.mms/u0a35 (adj 15): empty #17
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,D/CountryDetector(  957): No listener is left
,I/LocationManagerService(  957): remove 44da54a8
,D/LocationManagerService(  957): provider request: passive ProviderRequest[ON interval=0]
D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  957): handleMessage: E msg.what=131155
,D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiNative-wlan0(  957): doString: SIGNAL_POLL
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4232): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4232): nl80211: survey data missing!
,D/WifiStateMachine(  957): handleMessage: X
,E/Parcel  (  511): Reading a NULL string not supported here.
,E/Parcel  (  511): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/CaptivePortalTracker(  957): DelayedCaptiveCheckState{ when=-1ms what=2 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/QcConnectivityService(  957): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
D/CaptivePortalTracker(  957): Checking http://216.58.209.46/generate_204
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,D/CaptivePortalTracker(  957): Don't send network conditions - lacking user consent.
,D/CaptivePortalTracker(  957): isCaptivePortal: ret=false rspCode=204
D/CaptivePortalTracker(  957): Not captive network NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
,D/CaptivePortalTracker(  957): notifyPortalCheckCompleted: captive=false ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  957): captivePortalCheckCompleted: ni=NetworkInfo: type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, smCause: 0, isConnectedToProvisioningNetwork: false captive=false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/[LGHome]EVENT( 1485): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1485): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.talk flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1485): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
E/SlideAside( 3518): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3518): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.talk
,D/administrator(  957): Handling package changes for user 0
,I/ActivityManager(  957): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=5004 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
,I/InputReader(  957): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "sms"
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/InputReader(  957): Reconfiguring input devices.  changes=0x00000010
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "smsto"
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/SlideAside( 3518): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_CHANGED
,I/SlideAside( 3518): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.google.android.gms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/[LGHome]EVENT( 1485): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1485): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1485): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 6
D/GlobalAccess( 1137): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1137): changeTargets() succeeded. size: 20
I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "mms"
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/[LGHome]Launcher( 1485): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
,D/HyLog   ( 5004): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5004): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5004): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "mmsto"
,I/[LGHome]Launcher( 1485): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "sms"
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/AppUp4  ( 5004):  AppBoxContentProvider onCreate
,W/AppUp4  ( 5004):  [AppBoxDatabaseHelper] construct
D/GlobalAccess( 1137): optimizeTargetDrawableItems(), newSize: 20
I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  957):   Scheme: "smsto"
,D/GlowPadView( 1137): changeTargets() succeeded. size: 20
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/AppUp4  ( 5004):  setFingerPrint start
,I/AppUp4  ( 5004):  newfinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
I/AppUp4  ( 5004):  beforefinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
,I/AppUp4  ( 5004):  beforefinger == newfinger no write in DB
,D/AppUp4:AppBoxApplication( 5004): AppBoxApplication onCreate()
I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "mms"
,D/AppBoxBlacklist( 5004): ConfigFile is not exist. /cust/config/appmanager.cfg
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "mmsto"
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/PackageParser( 5004): Added overlay pkg for /system/apps/bootup/LGTaskManager.apk
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "sms"
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/administrator(  957): Handling package changes for user 0
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "smsto"
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/AppUp4:Utils( 5004): [getPackageName] uri : package:com.google.android.talk
,D/AppUp4  ( 5004): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 5004): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.talk
D/PackageParser( 5004): Added overlay pkg for /system/apps/bootup/LGHome_Theme_Marshmallow.apk
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "mms"
,I/AppUp4:CustModeStarterReceiver( 5004): onReceive
,D/AppUp4:CustFacade( 5004): Context : android.app.ReceiverRestrictedContext@42883278
D/AppUp4:CustFacade( 5004): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5004): isOpenOperator : true
,D/AppUp4:CustFacade( 5004): isPhone : true
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "mmsto"
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/ActivityManager(  957): Start proc com.lge.eula for content provider com.lge.eula/.databases.LicenseContentProvider: pid=5037 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "sms"
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  957):   Scheme: "smsto"
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,D/HyLog   ( 5037): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5037): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5037): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "mms"
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1137): handleBatteryUpdate (2) (100)
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiController(  957): battery changed pluggedType: 2
D/HeadsetStateMachine( 1213): Disconnected process message: 10
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/PackageManager(  957):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  957):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  957):   Scheme: "mmsto"
I/PackageManager(  957): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1137): handleBatteryUpdate (2) (100)
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,I/LicenseContentProvider( 5037): start selecting data
,W/BaseRuntimeLoader( 5037): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5037): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5037): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5037): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/SIMObserver( 5037): simInfo1
D/WifiController(  957): battery changed pluggedType: 2
,I/AppUp4:EulaManager( 5004): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 5004): begin check event
D/AppUp4:Utils( 5004): [getPackageName] uri : package:com.google.android.talk
,I/AppUp4:CustModeStarterReceiver( 5004): Event For Nothing, skip.
,I/ActivityManager(  957): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=5051 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
,I/ActivityManager(  957): Killing 4567:com.android.chrome/u0a63 (adj 15): empty #17
,I/[LGHome]EVENT( 1485): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/ActivityManager(  957): Killing 4638:com.google.android.setupwizard/u0a52 (adj 15): empty #18
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
D/HyLog   ( 5051): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5051): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5051): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1485): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,V/GmsNetworkLocationProvi( 1422): DISABLE
,I/GCoreNlp( 1422): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,I/SystemConfig( 5051): BUILD Country: EU
,I/SystemConfig( 5051): BUILD Operator: OPEN
I/ActivityManager(  957): Killing 4653:com.lge.drmservice/u0a66 (adj 15): empty #17
,I/ActivityManager(  957): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=5067 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,I/SystemConfig( 5051): systemFeature RCS result false
,D/SystemConfig( 5051): refreshRcsSupport() :false
D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,D/HyLog   ( 5067): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5067): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5067): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/WifiStateMachine(  957): handleMessage: E msg.what=131155
D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiNative-wlan0(  957): doString: SIGNAL_POLL
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4232): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4232): nl80211: survey data missing!
,D/WifiStateMachine(  957): handleMessage: X
E/Parcel  (  511): Reading a NULL string not supported here.
,E/Parcel  (  511): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,D/LocationProviderProxy(  957): applying state to connected service
,D/LocationProviderProxy(  957): applying state to connected service
,I/IcingCorporaProvider( 2630): Updating corpora: APPS=com.google.android.talk, CONTACTS=MAYBE
I/ActivityManager(  957): Killing 4312:com.lge.lgdmsgcm/1000 (adj 15): empty #17
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 2 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Top activity resumed ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,D/PackageBroadcastService( 1939): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.talk
,I/PeopleContactsSync( 1939): CP2 sync disabled
,D/AppUp4:Utils( 5004): [getPackageName] uri : package:com.google.android.gms
D/AppUp4  ( 5004): [PreloadListManagerHelper] action android.intent.action.PACKAGE_CHANGED
,D/AppUp4  ( 5004): AppUp4:PreloadListManagerHelper isLGApp : com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 5004): onReceive
,D/AppUp4:CustFacade( 5004): Context : android.app.ReceiverRestrictedContext@42883278
,D/AppUp4:CustFacade( 5004): isCustomizationCompleted : false
D/AppUp4:CustFacade( 5004): isOpenOperator : true
D/AppUp4:CustFacade( 5004): isPhone : true
,I/LicenseContentProvider( 5037): start selecting data
,D/SIMObserver( 5037): simInfo1
,I/AppUp4:EulaManager( 5004): getAgreementForKK : Eula agreement is false
D/AppUp4:CustModeStarterReceiver( 5004): begin check event
D/AppUp4:Utils( 5004): [getPackageName] uri : package:com.google.android.gms
,I/AppUp4:CustModeStarterReceiver( 5004): Event For Nothing, skip.
,I/IcingCorporaProvider( 2630): UpdateCorporaTask done [took 50 ms] updated apps [took 50 ms] 
,I/IcingCorporaProvider( 2630): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,D/PackageBroadcastService( 1939): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PackageBroadcastService( 1939): Null package name or gms related package.  Ignoreing.
I/ActivityManager(  957): Delaying start of: ServiceRecord{4441a100 u0 com.google.android.gms/.wearable.service.WearableControlService}
,I/Icing   ( 1939): updateResources: need to parse f{com.google.android.gms}
,D/dalvikvm( 1939): GC_CONCURRENT freed 1779K, 22% free 19472K/24832K, paused 1ms+5ms, total 36ms
,D/dalvikvm(  957): GC_EXPLICIT freed 2928K, 48% free 29620K/56776K, paused 4ms+8ms, total 94ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/IcingCorporaProvider( 2630): UpdateCorporaTask done [took 294 ms] updated apps [took 294 ms] 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,D/WifiStateMachine(  957): handleMessage: E msg.what=131155
,D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  957): doString: SIGNAL_POLL
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4232): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4232): nl80211: survey data missing!
,D/WifiStateMachine(  957): handleMessage: X
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,I/GAV4    ( 4913): Thread[GAThread,5,main]: No campaign data found.
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,D/WifiStateMachine(  957): handleMessage: E msg.what=131155
,D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  957): doString: SIGNAL_POLL
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4232): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4232): nl80211: survey data missing!
,D/WifiStateMachine(  957): handleMessage: X
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,D/Finsky  ( 4883): [420] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 4883): [1] 5.onFinished: Installation state replication succeeded.
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,I/PowerManagerService(  957): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  957): [updateScreenState] screen on = false
D/KnockOnPowerController(  957): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  957): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  957): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  957): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  957): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  957): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  957): _hal_sensors_activate: handle=35, Initialized the timestamp 
,D/qcom_sensors_hal(  957): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 8258 usec
D/KnockOnPowerController(  957): [setProximitySensorEnabled] enable = true
,D/qcom_sensors_hal(  957): hal_acquire_resources
,I/qcom_sensors_hal(  957): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  957): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
I/qcom_sensors_hal(  957): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  957): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  957): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  957): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  957): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  957): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.452560 Y: -0.399414 Z: 9.760513 
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.452560 .y:-0.399414 .z:9.760513
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.463394 Y: -0.401443 Z: 9.741348 
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.463394 .y:-0.401443 .z:9.741348
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,I/Sensors (  478): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
V/qcom_sensors_hal(  957): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  957): hal_sam_gen_prox : proximity_state changed - FAR
,I/qcom_sensors_hal(  957): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  957): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  957): proximitySensorChanged  positive = true
I/KnockOnPowerController(  957): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.468384 Y: -0.394272 Z: 9.749420 
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.468384 .y:-0.394272 .z:9.749420
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.464111 Y: -0.392197 Z: 9.759918 
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.464111 .y:-0.392197 .z:9.759918
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.459000 Y: -0.394470 Z: 9.750031 
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.459000 .y:-0.394470 .z:9.750031
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.463348 Y: -0.399521 Z: 9.764359 
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.463348 .y:-0.399521 .z:9.764359
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  957): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@42afd6f8)
,D/KeyguardViewMediator( 1137): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1137): notifyScreenOnLocked
,D/KeyguardViewMediator( 1137): handleNotifyScreenOn
,D/KeyguardViewManager( 1137): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  957): **** SHOWN CALLED ****
I/WindowManager(  957): No lock screen! windowToken=null
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb8a8d450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,D/LockPatternUtilsEx( 1137): OMADM Lock is OFF
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=4
,V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.454483 Y: -0.402512 Z: 9.783279 
D/WifiStateMachine(  957): handleMessage: E msg.what=131155
D/WifiStateMachine(  957): processMsg: ConnectedState
,D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.454483 .y:-0.402512 .z:9.783279
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,D/WifiStateMachine(  957): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  957): doString: SIGNAL_POLL
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4232): wlan0: Control interface command 'SIGNAL_POLL'
,D/WifiStateMachine(  957): handleScreenStateChanged: true
,D/WifiServiceExtension(  957): sendKtScanInterval  mRtspPlay : false
,D/wpa_supplicant( 4232): nl80211: survey data missing!
,D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=131154
D/WifiStateMachine(  957): processMsg: ConnectedState
,D/WifiStateMachine(  957): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  957): doString: SIGNAL_POLL
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 4232): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 4232): nl80211: survey data missing!
,D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=131127
D/WifiStateMachine(  957): processMsg: ConnectedState
,D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): handleMessage: X
,D/WifiStateMachine(  957): handleMessage: E msg.what=131158
D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
,D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): processMsg: DriverStartedState
D/WifiStateMachine(  957): setSuspendOptimizationsNative: 4 false
,D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=132097
D/WifiStateMachine(  957): processMsg: ConnectedState
,D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): processMsg: DriverStartedState
,D/WifiStateMachine(  957): processMsg: DriverStartedStateExt
I/WifiServiceExtension(  957): set CMD_KT_SCAN_INTERVAL
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=16): 4b 54 5f 53 43 41 4e 5f 49 4e 54 45 52 56 41 4c
D/wpa_supplicant( 4232): wlan0: Control interface command 'KT_SCAN_INTERVAL'
,D/wpa_supplicant( 4232): initialize kt scan interval and do scan state=9
,D/WifiStateMachine(  957): handleMessage: X
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,D/WifiOffDelayIfNotUsed(  957): stopMonitoring
,E/AudioSystem(  957): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=on, calling pid 957
V/SRS_Proc(  271): ParamSet string: screen_state=on
,D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: enter: screen_state=on
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
,D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
,D/WeatherAncestor( 1883): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:54:59
I/EmotionalLed( 1151): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1151): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4337a8d0 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1151): enqueuing start. mLedList.size()=2
,D/qdlights( 1151): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1151): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1151): enqueuing end. mLedList.size()=3
,D/qdlights( 1151): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 255, B = 255
,E/SlideAside( 3518): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 3518): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,I/EmotionalLed( 1151): getCurrentHighestLGLedRecord() start. mLedList.size=3
E/CliptrayService( 1151): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
D/qdlights( 1151): set_light_notifications: 2,ff00ffff,10,0,2
V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  957): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
D/qdlights( 1151): [Current] = 255, R = 0, G = 255, B = 255
V/qcom_sensors_hal(  957): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  957): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  957): hal_process_report_ind: X: -0.472992 Y: -0.393417 Z: 9.763550 
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.472992 .y:-0.393417 .z:9.763550
D/qcom_sensors_hal(  957): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=0
,D/qdlights( 1151): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 255, B = 255
,D/UpdateThreadPoolManager( 1883): 2 : This is isUpdating : false
,D/WeatherAncestor( 1883): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 18:54:59
,D/LockPatternUtilsEx( 1137): OMADM Lock is OFF
,D/qdlights( 1151): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherService( 1883): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1883): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1883): 2 : shouldTimeTickRegistered : false
D/qdlights( 1151): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1151): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1151): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1151): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1151): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1151): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1151): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1151): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1151): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1151): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1151): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1151): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1151): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1151): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1151): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1151): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1151): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1151): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1151): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1151): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1151): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1151): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1151): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1151): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 207, B = 207
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  957): Excessive delay in blankDisplay() while turning screen off: 402ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1151): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 201, B = 201
,D/qdlights( 1151): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1151): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 189, B = 189
,D/qdlights( 1151): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1151): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 177, B = 177
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1151): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1151): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1151): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 159, B = 159
,D/qdlights( 1151): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1151): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 147, B = 147
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1151): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 141, B = 141
,D/qdlights( 1151): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1151): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 129, B = 129
,D/qdlights( 1151): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 123, B = 123
,D/qdlights( 1151): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 117, B = 117
,D/qdlights( 1151): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 111, B = 111
,D/qdlights( 1151): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 105, B = 105
,D/qdlights( 1151): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 99, B = 99
,D/qdlights( 1151): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 93, B = 93
,D/qdlights( 1151): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 87, B = 87
,D/qdlights( 1151): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 81, B = 81
,D/qdlights( 1151): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1151): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1151): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1151): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1151): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1151): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1151): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1151): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1151): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 27, B = 27
,D/dalvikvm( 1137): GC_FOR_ALLOC freed 9077K, 13% free 68219K/78136K, paused 70ms, total 77ms
,D/qdlights( 1151): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1151): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1151): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1151): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1151): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1151): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1151): updateLightsLocked() start. mLedList.size=2
,D/GlobalAccess( 1137): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1137): changeTargets() succeeded. size: 20
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449683700157, nextTick: 59876, mDrawingTime: 0
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449683700199, nextTick: 59834, mDrawingTime: 0
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449683700199, nextTick: 59834, mDrawingTime: 0
,D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=4
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
,E/Parcel  (  511): Reading a NULL string not supported here.
,V/TelephonyAutoProfiling(  957): [getValue] FEATURE key : trf_based_vzw, value : null
,D/WeatherService( 1883): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:55:0
,D/WeatherService( 1883): 2 : ACTION screen on
,D/WeatherService( 1883): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1883): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 18:55:0
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,D/GsmSST  ( 1447): Emergency Service
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1447): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
,V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_RAD_TEST, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_gfit, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1447): [PhoneIntfMgr] sigLevel = 5
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/PhoneApp( 1447): Action intent recieved:android.intent.action.SCREEN_ON
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  957): ACTION_SCREEN_ON
,I/qcom_sensors_hal(  957): _hal_sensors_activate: handle=0, enabled=0
,D/KeyguardViewMediator( 1137): onScreenTurnedOff(3)
D/KeyguardViewMediator( 1137): notifyScreenOffLocked
I/qcom_sensors_hal(  957): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  957): _hal_sensors_activate: handle=0, Initialized the timestamp 
,D/qcom_sensors_hal(  957): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
V/ActivityManager(  957): Moving to PAUSING: ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3}
,D/qcom_sensors_hal(  957): hal_acquire_resources
D/qcom_sensors_hal(  957): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  957): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  957): hal_wait_for_response: timeout=1000
V/qcom_sensors_hal(  957): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  957): hal_process_smgr_resp: 33
,D/qcom_sensors_hal(  957): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  957): hal_smgr_report_delete: Rcvd success response from request
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,V/ActivityManager(  957): Moving to PAUSED: ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3} (pause complete)
,D/KeyguardViewMediator( 1137): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,D/UsbSettings( 2556): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2556): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2556): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2556): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
V/ActivityManager(  957): Moving to STOPPING: ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3} (stop requested)
V/ActivityManager(  957): Moving to DESTROYING: ActivityRecord{4291f618 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  957): Moving to STOPPED: ActivityRecord{44df8448 u0 com.test.thalitest/.MainActivity t3} (stop complete)
,V/ActivityManager(  957): Moving to DESTROYED: ActivityRecord{4291f618 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 1 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Going to sleep and all paused
,D/KeyguardViewMediator( 1137): handleNotifyScreenOff
,D/KeyguardViewManager( 1137): onScreenTurnedOff()
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/LGImmersionVibrator(  957): Vibrator off
,D/WifiStateMachine(  957): handleScreenStateChanged: false
D/WifiStateMachine(  957): handleMessage: E msg.what=131154
D/WifiStateMachine(  957): processMsg: ConnectedState
,D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=131158
D/WifiStateMachine(  957): processMsg: ConnectedState
,D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): processMsg: DriverStartedState
D/WifiStateMachine(  957): setSuspendOptimizationsNative: 4 true
,D/WifiNative-wlan0(  957): doBoolean: DRIVER SETSUSPENDMODE 1
,E/AudioSystem(  957): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  271): setParameters(): io 0, keyvalue screen_state=off, calling pid 957
V/SRS_Proc(  271): ParamSet string: screen_state=off
D/audio_hw_primary(  271): adev_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: enter: screen_state=off
V/voice   (  271): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  271): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  271): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  271): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  271): adev_set_parameters: exit with code(-2)
D/WifiController(  957): CMD_SCREEN_OFF 
,D/WifiController(  957): shouldWifiStayAwake TRUE
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 53 45 54 53 55 53 50 45 4e 44 4d 4f 44 45 20 31
D/wpa_supplicant( 4232): wlan0: Control interface command 'DRIVER SETSUSPENDMODE 1'
,D/wpa_supplicant( 4232): wpa_driver_nl80211_driver_cmd  len = 0, 0
D/qdlights( 1151): set_light_notifications: 0,0,0,0,3
,D/WifiNative-wlan0(  957):    returned true
,D/WifiStateMachine(  957): handleMessage: X
,D/qdlights( 1151): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1151): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1151): getCurrentHighestLGLedRecord() start. mLedList.size=2
I/EmotionalLed( 1151): updateLightsLocked() start. mLedList.size=2
D/EmotionalLed( 1151): RESTART MSG
,D/VolumeVibrator( 1151): clear
E/CliptrayService( 1151): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
D/NativeNfcBrcmPowerMode( 1472): setPowerMode; state=2
,I/[LGHome]EVENT( 1485): [Launcher.java:1567:onReceive()]Screen Off
,E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
,E/Parcel  (  511): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,V/TelephonyAutoProfiling(  957): [getValue] FEATURE key : trf_based_vzw, value : null
D/WeatherService( 1883): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:55:0
D/WeatherService( 1883): 2 : ACTION screen off
,D/WeatherService( 1883): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 18:55:0
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,D/BrcmNfcJni( 1472): RoutingManager::applyStaticRoutes: set tech routing; ee id=0xF3; tech mask=0x3
,D/BrcmNfcJni( 1472): RoutingManager::applyStaticRoutes: set proto routing; ee id=0xF3; proto mask=0x8
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : trf_based_vzw, value : null
,D/NfcService( 1472): NFC-C OFF
,D/PhoneInterfaceManager( 1447): [PhoneIntfMgr] sigLevel = 5
D/GsmSST  ( 1447): Emergency Service
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
,D/GsmSST  ( 1447): [lge_gsmsst_dbg] - 3, 12, 13 Registration denied rejcode : 0
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] PROFILE key : HOME_NETWORK, value : null, subId : 0
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : KR_RAD_TEST, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_assisted_dialing, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1447): [getValue] FEATURE key : vzw_gfit, value : null
,V/PhoneApp( 1447): Action intent recieved:android.intent.action.SCREEN_OFF
,D/LockPatternUtilsEx( 1137): OMADM Lock is OFF
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
,D/TangibleManager( 1460): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,I/Sensors (  478): sns_pwr.c(320):releasing wakelock
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiOffDelayIfNotUsed(  957): ACTION_SCREEN_OFF
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/ThermalEngine(  285): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/WifiStateMachine(  957): handleMessage: E msg.what=131155
,D/WifiStateMachine(  957): processMsg: ConnectedState
,D/WifiStateMachine(  957): processMsg: L2ConnectedState
,D/WifiStateMachine(  957): handleMessage: X
,D/WifiStateMachine(  957): handleMessage: E msg.what=131155
,D/WifiStateMachine(  957): processMsg: ConnectedState
,D/WifiStateMachine(  957): processMsg: L2ConnectedState
,D/WifiStateMachine(  957): handleMessage: X
,D/KeyguardViewMediator( 1137): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,D/PhoneApp( 1447): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1137): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1137): OMADM Lock is OFF
,D/KeyguardViewMediator( 1137): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1137): doKeyguard is called, but is not locked.
,I/VacuumService( 1545): Vacuum at: now=1449683709441 tag=VacuumService
,I/GoogleURLConnFactory( 1545): Using platform SSLCertificateSocketFactory
,W/BaseRuntimeLoader( 1545): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1545): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1545): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 1545): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/Uploader( 1545): No account for auth token provided
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1545): GC_CONCURRENT freed 1851K, 28% free 17993K/24832K, paused 3ms+4ms, total 95ms
,W/Uploader( 1545): No account for auth token provided
,W/Uploader( 1545):  no longer exists, so no auth token.
,W/Uploader( 1545): No account for auth token provided
,W/Uploader( 1545): No account for auth token provided
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449683717727810090; DSPS: 5284664; Offset: 1449683556452663606
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1151): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  957): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1137): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
,W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449683737729782322; DSPS: 5940088; Offset: 1449683556452682713
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449683757731432210; DSPS: 6595502; Offset: 1449683556452684652
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449683760047, nextTick: 59968, mDrawingTime: 6
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449683760059, nextTick: 59974, mDrawingTime: 0
,I/rmt_storage(  522): rmt_storage_connect_cb: clnt_h=0x7 conn_h=0xb88a3178
I/rmt_storage(  522): rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: R/W request received
,I/rmt_storage(  522): wakelock acquired: 1, error no: 42
,I/rmt_storage(  522): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1198903576)
,I/rmt_storage(  522): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: Bytes written = 1572864
I/rmt_storage(  522): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xb msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  522): rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1198903576) wakelock released: 1, error no: 22
I/rmt_storage(  522): 
I/rmt_storage(  522): rmt_storage_disconnect_cb: clnt_h=0x0x7 conn_h=0x0xb88a3178
,E/Diag_Lib(  741): [IMS_FATAL]| 2912 | 750 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449683777733250795; DSPS: 7250922; Offset: 1449683556452672182
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449683797735706570; DSPS: 7906362; Offset: 1449683556452686551
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1137): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
D/WifiController(  957): battery changed pluggedType: 2
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1213): Disconnected process message: 10
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449683817737617604; DSPS: 8561785; Offset: 1449683556452674978
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449683820058, nextTick: 59965, mDrawingTime: 5
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449683820063, nextTick: 59969, mDrawingTime: 0
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449683837738961502; DSPS: 9217189; Offset: 1449683556452676102
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449683857740114724; DSPS: 9872587; Offset: 1449683556452669656
,D/wpa_supplicant( 4232): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): wlan0: BSS: Remove id 4 BSSID a0:c5:62:7a:49:97 SSID 'UPC503894600' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): wlan0: BSS: Remove id 5 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush_by_age
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 4232): wlan0: BSS: Remove id 6 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush_by_age,
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): wlan0: BSS: Remove id 7 BSSID 9e:93:4e:3e:ba:c5 SSID 'DIRECT-qjWorkCentre 3025' due to wpa_bss_flush_by_age
,D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): wlan0: BSS: Remove id 8 BSSID 0c:bd:51:2b:c1:25 SSID 'PLAY-ONLINE_1167' due to wpa_bss_flush_by_age,
,D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
,D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 a0:c5:62:7a:49:97]
,D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 64:7c:34:12:7f:81]
,D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 06:7c:34:12:7f:81]
,D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 9e:93:4e:3e:ba:c5]
,D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 0c:bd:51:2b:c1:25]
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449683877741569248; DSPS: 10527994; Offset: 1449683556452689854
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449683880042, nextTick: 59974, mDrawingTime: 7
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449683880053, nextTick: 59974, mDrawingTime: 2
,I/jxcore-log( 4175): Toggling radios to false
I/jxcore-log( 4175): 
,D/BluetoothManagerService(  957): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  957): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@44c8b578 mBinding = false
,D/BluetoothManagerService(  957): Message: 2
,D/BluetoothManagerService(  957): Sending off request.
D/WifiService(  957): setWifiEnabled: false pid=4175, uid=10304
E/WifiService(  957): Invoking mWifiStateMachine.setWifiEnabled
,I/WifiService(  957): setWifiEnabled startWifiDelaySendMsg true
D/BluetoothAdapterService(1116324896)( 1213): disable() called...
D/BluetoothAdapterState( 1213): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
I/BluetoothAdapterState( 1213): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 1213): Broadcasting updateAdapterState() to 1 receivers.
I/bt-btif ( 1213): btif_set_adapter_property type: 7, len 4, 0x42946618
I/bt-btif ( 1213): set property scan mode : 0
I/bt-btif ( 1213): bta_dm_sm_execute event:0x3
I/bt-btif ( 1213): btif_in_storage_request_copy_cb
I/bt-btif ( 1213): execute storage request event : 2
I/bt-btif ( 1213): type: 7, len 4, 0x60ab2d4a
D/bt-btif ( 1213): in, bd addr:, prop type:7, len:4
I/bt-btif ( 1213): HAL bt_hal_cbacks->adapter_properties_cb
D/WifiStateMachine(  957): handleMessage: E msg.what=131084
D/WifiStateMachine(  957): processMsg: ConnectedState
D/WifiStateMachine(  957): processMsg: L2ConnectedState
D/WifiStateMachine(  957): processMsg: ConnectModeState
D/WifiStateMachine(  957): processMsg: DriverStartedState
D/WifiStateMachine(  957): processMsg: DriverStartedStateExt
D/WifiStateMachine(  957): processMsg: SupplicantStartedState
I/BluetoothAdapterState( 1213): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
D/WifiStateMachine(  957): transitionTo: destState=WaitForP2pDisableState
D/BluetoothAdapterState( 1213): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bluedroid( 1213): disable 1
D/WifiStateMachine(  957): handleMessage: new destination call exit/enter
I/bt-btif ( 1213): BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
D/WifiStateMachine(  957): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
D/bt-btif ( 1213): h:6, process_cmd_sock return false, exit...
D/bt-btif ( 1213): socket poll thread exiting, h:6
D/bt-btif ( 1213): cleanup slot:1, fd:89, scn:6, sdp_handle:0x1000a
I/jxcore-log( 4175): Radios toggled
I/jxcore-log( 4175): 
D/bt-btif ( 1213): del_rfc_sdp_rec: handle:0x1000a
V/BluetoothMapService( 1213): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/WifiStateMachine(  957): invokeExitMethods: ConnectedState
I/bt-btif ( 1213): BTA_JvDeleteRecord
W/Settings(  957): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/bt-sdp  ( 1213): SDP_DeleteRecord ok, num_records:12
I/bt-btif ( 1213): BTA_JvRfcommStopServer
D/BluetoothManagerService(  957): Message: 60
E/bt-btif ( 1213): bta_jv_rfcomm_stop_server
D/bt-btif ( 1213): find_rfc_pcb(): FOUND rfc_cb_handle 0x1, port.jv_handle: 0x81, state: 4, rfc_cb->handle: 0x81
D/bt-btif ( 1213): bta_jv_rfcomm_stop_server: p_pcb:0x60d250e8, p_pcb->port_handle:6
D/bt-btif ( 1213): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60d250e8, user:1, state:4, jv handle: 0x81
,D/bt-btif ( 1213): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:6, user_data:1
D/bt-btif ( 1213): bta_jv_rfcomm_stop_server: sec id in use:2, rfc_cb in use:2
D/bt-btif ( 1213): cleanup slot:2, fd:91, scn:19, sdp_handle:0x1000b
D/bt-btif ( 1213): del_rfc_sdp_rec: handle:0x1000b
V/BluetoothPbapService( 1213): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/BluetoothManagerService(  957): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
I/bt-btif ( 1213): BTA_JvDeleteRecord
D/bt-sdp  ( 1213): SDP_DeleteRecord ok, num_records:11
I/bt-btif ( 1213): BTA_JvRfcommStopServer
E/bt-btif ( 1213): bta_jv_rfcomm_stop_server,
D/bt-btif ( 1213): find_rfc_pcb(): FOUND rfc_cb_handle 0x2, port.jv_handle: 0x82, state: 4, rfc_cb->handle: 0x82
D/bt-btif ( 1213): bta_jv_rfcomm_stop_server: p_pcb:0x60d250fc, p_pcb->port_handle:7
D/bt-btif ( 1213): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60d250fc, user:2, state:4, jv handle: 0x82
D/bt-btif ( 1213): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:19, user_data:2
D/bt-btif ( 1213): bta_jv_rfcomm_stop_server: sec id in use:1, rfc_cb in use:1
D/bt-btif ( 1213): cleanup slot:3, fd:95, scn:12, sdp_handle:0x1000c
D/BluetoothManagerService(  957): Bluetooth State Change Intent: 12 -> 13
D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
E/BtOppRfcommListener( 1213): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/bt-btif ( 1213): del_rfc_sdp_rec: handle:0x1000c
I/bt-btif ( 1213): BTA_JvDeleteRecord
D/bt-sdp  ( 1213): SDP_DeleteRecord ok, num_records:10
I/bt-btif ( 1213): BTA_JvRfcommStopServer
E/bt-btif ( 1213): bta_jv_rfcomm_stop_server,
D/bt-btif ( 1213): find_rfc_pcb(): FOUND rfc_cb_handle 0x3, port.jv_handle: 0x83, state: 4, rfc_cb->handle: 0x83
D/bt-btif ( 1213): bta_jv_rfcomm_stop_server: p_pcb:0x60d25110, p_pcb->port_handle:8
D/bt-btif ( 1213): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60d25110, user:3, state:4, jv handle: 0x83
D/bt-btif ( 1213): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:12, user_data:3,
D/bt-btif ( 1213): bta_jv_rfcomm_stop_server: sec id in use:0, rfc_cb in use:0
D/bt-btif ( 1213): leaving
D/WifiStateMachine(  957): invokeExitMethods: L2ConnectedState
D/bt-sdp  ( 1213): SDP_DeleteRecord ok, num_records:9
I/bt-btif ( 1213): Removing UUID=0x1116 from EIR
D/bt-btif ( 1213): BTA is generating EIR
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04031460,
,I/bt-btif ( 1213): Removing UUID=0x1116 from EIR
D/bt-btif ( 1213): BTA is generating EIR
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04031460
I/bt-btif ( 1213): Removing UUID=0x1117 from EIR
D/bt-btif ( 1213): BTA is generating EIR
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04031460
I/bt-btif ( 1213): Removing UUID=0x1115 from EIR,
D/bt-btif ( 1213): BTA is generating EIR
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04011460
I/bt-btif ( 1213): bta_dm_sm_execute event:0x1
D/bt-btif ( 1213): bta_sys_disable: module 0
,W/bt-btif ( 1213): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
I/bt-btif ( 1213): AG evt (hdl 0x0001): State 0, Event 0x0501
D/bt-btif ( 1213): bta_ag_del_records 0
D/bt-sdp  ( 1213): SDP_DeleteRecord ok, num_records:8
I/bt-btif ( 1213): Removing UUID=0x1112 from EIR,
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04001460
D/bt-btif ( 1213): bta_ag_del_records 1
D/bt-sdp  ( 1213): SDP_DeleteRecord ok, num_records:7
I/bt-btif ( 1213): Removing UUID=0x111F from EIR,
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000494 00001460
D/bt-btif ( 1213): bta_ag_scb_dealloc 1
W/bt-obex ( 1213): Ignore event 10 in state 1
D/bt-sdp  ( 1213): SDP_DeleteRecord ok, num_records:6
I/bt-btif ( 1213): Removing UUID=0x1106 from EIR
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000494 00001420
,D/bt-sdp  ( 1213): SDP_DeleteRecord ok, num_records:5,
I/bt-btif ( 1213): Removing UUID=0x112D from EIR
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000490 00001420
I/bt-btif ( 1213): bta_av_del_rc  handle: 0 status=0x10, rc_acp_handle:0, idx:1
I/bt-btif ( 1213): end del_rc handle: 255 status=0x0, rc_acp_handle:255, lidx:0
D/bt-btif ( 1213): bta_av_cleanup
D/bt-btif ( 1213): deregistered 64(h65)
,D/bt-sdp  ( 1213): SDP_DeleteRecord ok, num_records:4
I/bt-btif ( 1213): Removing UUID=0x110A from EIR
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000490 00001020
D/bt-btif ( 1213): audio 0x0, video: 0x0, disable:1
D/bt-sdp  ( 1213): SDP_DeleteRecord ok, num_records:3
I/bt-btif ( 1213): Removing UUID=0x110C from EIR
I/bt-btif ( 1213): bta_dm_eir_update_uuid UUID bit mask=0x00000490 00000020,
D/bt-btif ( 1213): audio 0x0, video: 0x0, disable:0
,W/bt-l2cap( 1213): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1213): L2CAP - PSM: 0x0017 not found for deregistration
D/bt-btif ( 1213): bta_gattc_disable
I/bt-att  ( 1213): GATT_Deregister gatt_if=3
I/bt-att  ( 1213): GATT_Listen gatt_if=3
D/bt-btif ( 1213): bta_dm_gattc_callback event = 1
I/bt-att  ( 1213): GATT_Deregister gatt_if=4
,I/bt-att  ( 1213): GATT_Listen gatt_if=4
D/bt-btif ( 1213): bta_hh_gattc_callback event = 1
I/bt-btif ( 1213): bta_dm_search_sm_execute state:0, event:0x206
E/bt-btif ( 1213): bta_gattc_deregister Deregister Failed, unknown client cif
D/bt-btif ( 1213): btif_hf_upstreams_evt: event=BTA_AG_DISABLE_EVT
D/bt-btif ( 1213): btif_fts_upstreams_evt: event=BTA_FTS_DISABLE_EVT
I/bt-btif ( 1213): File Transfer: Disable complete,
D/bt-btif ( 1213): btif_hh_upstreams_evt: event=BTA_HH_DISABLE_EVT
D/WifiStateMachine(  957): invokeExitMethods: ConnectModeState
D/IOP_DB_BT( 1213): db_close: nbr users 0
D/IOP_DB_BT( 1213): db_close: free database
D/WifiStateMachine(  957): invokeExitMethods: DriverStartedState
D/WifiNative-wlan0(  957): doString: DRIVER WLS_BATCHING GET
D/btif_config_util( 1213): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 4232): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
,E/wpa_supplicant( 4232): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  957):    returned null
E/WifiStateMachine(  957): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  957): doString: DRIVER WLS_BATCHING STOP
D/LGBluetoothAPIService( 1151): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothMapService( 1213): onReceive
D/BluetoothMapService( 1213): STATE_TURNING_OFF,
D/BluetoothMapService( 1213): MAP Service closeService in,
D/LGBluetoothMapAdapter( 1213): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1213): MAP Service closeService out
,V/BtOppService( 1213): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 1213): stopping Accept Thread
V/BtOppRfcommListener( 1213): close mBtServerSocket
,V/BtOppRfcommListener( 1213): waiting for thread to terminate
,I/BtOppRfcommListener( 1213): BluetoothSocket listen thread finished
,V/BtOppRfcommListener( 1213): done waiting for thread to terminate
,V/BtOppService( 1213): onDestroy
,D/LGBluetoothOppAdapter( 1213): [BTUI] LGBluetoothOppAdapter cleanup
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 4232): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 4232): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  957):    returned null
,D/WifiStateMachine(  957): invokeExitMethods: DriverStartedStateExt
D/WifiStateMachine(  957): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine(  957): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
,D/WifiStateMachine(  957): invokeEnterMethods: WaitForP2pDisableState
,D/WifiMonitor(  957): WifiMonitorSingleton gotten
,D/WifiMonitor(  957): stopMonitoring(p2p0) = android.net.wifi.p2p.WifiP2pService$P2pStateMachine@43125770
D/WifiP2pService(  957): InactiveState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  957): P2pEnabledState{ when=-1ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,D/WfdService( 1151): Waiting for Wifi disabling
,D/WifiStateMachine(  957): handleMessage: X
,D/WifiStateMachine(  957): handleMessage: E msg.what=131205
D/WifiStateMachine(  957): processMsg: WaitForP2pDisableState
D/WifiStateMachine(  957): transitionTo: destState=SupplicantStoppingState
,D/WifiStateMachine(  957): handleMessage: new destination call exit/enter
D/WifiStateMachine(  957): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  957): invokeExitMethods: WaitForP2pDisableState
,D/WifiStateMachine(  957): invokeExitMethods: SupplicantStartedState
D/WifiP2pService(  957): P2pDisablingState
D/WifiP2pService(  957): P2pDisablingState{ when=-6ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  957): p2p socket connection lost
,D/WifiP2pService(  957): P2pDisabledState
D/WifiStateMachine(  957): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine(  957): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine(  957): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine(  957): Stopping DHCP and clearing IP
D/WifiStateMachine(  957): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  957): doBoolean: SET ps 1
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 4232): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 4232): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 4232): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  957):    returned true
,D/WifiNative-wlan0(  957): doBoolean: DRIVER BTCOEXMODE 2
D/WifiP2pService(  957): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  957): DefaultState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/wpa_supplicant( 4232): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 4232): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 4232): wpa_driver_nl80211_driver_cmd OK len = 0, 2
,D/WifiNative-wlan0(  957):    returned true
,D/DhcpStateMachine(  957): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  957): addressRemoved: 192.168.1.121/24 on wlan0 flags 128 scope 0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/bt-btif ( 1213): btif_dm_cancel_discovery
,I/bt-btif ( 1213): bta_dm_search_sm_execute state:0, event:0x201
,D/WifiStateMachine(  957): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
,E/LGBluetoothEventManager( 2556): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  957): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  957): stopping supplicant
D/WifiMonitor(  957): WifiMonitorSingleton gotten
,D/WifiNative-p2p0(  957): doBoolean: TERMINATE
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/ContextImpl( 2556): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:156 com.android.settings.bluetooth.DockEventReceiver.onReceive:123 
D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
D/ConnectivityServiceHSM(  957): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
D/QCNEA   (  511): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  511): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  511): |CAC| updateNetCfgInfo
V/QCNEA   (  511): |CAC| *********************************************
,V/QCNEA   (  511): |CAC|                   Netconfig               
V/QCNEA   (  511): |CAC| *********************************************
V/QCNEA   (  511): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  511): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  511): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  511): |CAC| 	NetConfig: ip4        =0.0.0.0
V/QCNEA   (  511): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  511): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  511): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  511): |CAC| *********************************************
D/QCNEA   (  511): |CAC| Received bssid= 
D/QCNEA   (  511): |CAC| net type = 3
V/QCNEA   (  511): |CAC| 	bssid           =00:00:00:00:00:00
D/wpa_supplicant( 4232): RX global ctrl_iface - hexdump(len=9): 54 45 52 4d 49 4e 41 54 45
D/QCNEA   (  511): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  511): |CAC| 	ssid           =NG700
V/QCNEA   (  511): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  511): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  511): |CAC| *********************************************
D/wpa_supplicant( 4232): p2p0: Removing interface p2p0
D/QCNEA   (  511): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  511): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  511): |CAC| dispatchNetCfg: updating:0xb787a8dc
D/wpa_supplicant( 4232): p2p0: Request to deauthenticate - bssid=00:00:00:00:00:00 pending_bssid=00:00:00:00:00:00 reason=3 state=DISCONNECTED
D/wpa_supplicant( 4232): TDLS: Tear down peers
D/wpa_supplicant( 4232): p2p0: No keys have been configured - skip key clearing
D/wpa_supplicant( 4232): p2p0: State: DISCONNECTED -> DISCONNECTED
D/QCNEA   (  511): |CAC| readCallback: read len:0, ret:-1, errno:11
,D/wpa_supplicant( 4232): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4232): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4232): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
,D/wpa_supplicant( 4232): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
,D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4232): p2p0: No keys have been configured - skip key clearing
V/WfdStateTracker( 1151): handleWifiStateChangedEvent: 0
D/WifiNative-p2p0(  957):    returned true
D/WifiStateMachine(  957): setWifiState: disabling
E/WifiStateMachine(  957): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  957): useWiFiOffloading() : false
E/WifiStateMachine(  957): CONFIG_LGE_WLAN_PATH : true
W/Settings(  957): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiHS20(  957): hidePasspointNotification off =false
D/QcConnectivityService(  957): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  957): Attempting to switch to mobile
D/QcConnectivityService(  957): Attempting to switch to BLUETOOTH_TETHER
,V/BluetoothPbapReceiver( 1213): PbapReceiver onReceive 
,D/QcConnectivityService(  957): handleConnectivityChange: preConnState=1 connState=2
W/Settings(  957): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  957): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
V/BluetoothPbapReceiver( 1213): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1213): ***********state = 13
D/DockEventReceiver( 2556): finishStartingService: stopping service
V/BluetoothPbapReceiver( 1213): ***********Calling start service!!!! with action = null
D/NetworkManagementService(  957): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=131213
D/WifiStateMachine(  957): processMsg: SupplicantStoppingState
D/WifiStateMachine(  957): processMsg: DefaultState
V/BluetoothPbapService( 1213): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1213): state: 13
V/BluetoothPbapService( 1213): Pbap Service closeService in
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=131213
D/WifiStateMachine(  957): processMsg: SupplicantStoppingState
D/WifiStateMachine(  957): processMsg: DefaultState
D/WifiStateMachine(  957): handleMessage: X
V/WfdStateTracker( 1151): WfdStateTracker handleDirectStateChangedEvent: 6
D/KeyguardUpdateMonitor( 1137): received broadcast android.net.wifi.STATE_CHANGE
D/NetworkManagementService(  957): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  957): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  264): RouteController
D/BubblePopupHelper( 1137): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1137): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
I/WifiServiceExtension(  957): WIFI_STATE_CHANGED_ACTION [0]
V/BluetoothPbapService( 1213): successfully stopped pbap service
V/BluetoothPbapService( 1213): Pbap Service closeService out
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
V/BluetoothPbapService( 1213): Pbap Service onDestroy
V/BluetoothPbapService( 1213): Pbap Service closeService in
V/BluetoothPbapService( 1213): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 1213): [BTUI] cleanup
D/BluetoothPbap( 2556): Proxy object disconnected
D/PbapServerProfile( 2556): Bluetooth service disconnected
D/LGBluetoothAuthorization( 2556): [BTUI] cancel All Notification
V/        (  264): RouteController
V/        (  264): RouteController
D/BluetoothPermissionRequest( 2556): onReceive
D/LGBluetoothAuthorization( 2556): [BTUI] cancel All Notification
D/wpa_supplicant( 4232): p2p0: Cancelling scan request
D/wpa_supplicant( 4232): p2p0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4232): p2p0: Cancelling ,authentication timeout
D/wpa_supplicant( 4232): p2p0: P2P: Disable P2P since removing the management interface is being removed
D/wpa_supplicant( 4232): P2P: Stopping find
D/wpa_supplicant( 4232): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 4232): P2P: State IDLE -> IDLE
D/wpa_supplicant( 4232): wpa_driver_set_ap_wps_p2p_ie: Entry
D/BubblePopupHelper( 1137): isShowingBubblePopup : false
V/        (  264): RouteController
D/LGBluetoothResetSettingReceiver( 2556): return without doing reset settings.
V/BluetoothOppReceiver( 1213): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 1213): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 1213): [BTUI] cancel opp active transfer file notification
,V/        (  264): RouteController
,D/wpa_supplicant( 4232): netlink: Operstate: linkmode=0, operstate=6
D/wpa_supplicant( 4232): nl80211: Set mode ifindex 22 iftype 2 (STATION)
D/wpa_supplicant( 4232): nl80211: Unsubscribe mgmt frames handle 0xb8a44c28 (mode change)
I/wpa_supplicant( 4232): p2p0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
I/wpa_supplicant( 4232): [ITEC] Close WIFLUS socket interface - START
I/wpa_supplicant( 4232): [ITEC] Close WIFLUS read interface - DONE
I/wpa_supplicant( 4232): HY wiflus comm channel de-initialized : wiflus = 0
D/WifiMonitor(  957): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor(  957): Dropping event because monitor (p2p0) is stopped
D/wpa_supplicant( 4232): Control interface directory not empty - leaving it behind
D/wpa_supplicant( 4232): wlan0: Removing interface wlan0
D/wpa_supplicant( 4232): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 4232): TDLS: Tear down peers
,D/wpa_supplicant( 4232): wpa_driver_nl80211_disconnect(reason_code=3)
I/bt-btif ( 1213): bta_sys_sm_execute state:2, event:0x3
D/bt-btif ( 1213): bta_sys_hw_api_disable for 0, active modules: 0x0001
D/bt-btif ( 1213): bta_sys_disable: module 0
I/bt-btif ( 1213): bta_sys_sm_execute state:3, event:0x4
D/bt-btif ( 1213): bta_sys_hw_evt_disabled - module 0x0
,D/bt-btif ( 1213):  bta_dm_sys_hw_cback with event: 0
I/bt-btif ( 1213): btif_dm_upstreams_cback  ev: BTA_DM_DISABLE_EVT
I/bt-btif ( 1213): btif_disable_bluetooth_evt()::btif_core_cb: is_radio_req: 0, radio_ref_count: 0, state: 4
D/bt-btif ( 1213): audio 0x0, video: 0x0, disable:0
W/bt-l2cap( 1213): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1213): L2CAP - PSM: 0x0017 not found for deregistration
D/bt-btif ( 1213): audio 0x0, video: 0x0, disable:1
W/bt-l2cap( 1213): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1213): L2CAP - PSM: 0x0017 not found for deregistration
D/bt-btif ( 1213): audio 0x0, video: 0x0, disable:0
W/bt-l2cap( 1213): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1213): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 1213): ag scb idx 1 not allocated
E/bt-btif ( 1213): BTA AG is already disabled, ignoring ...
,I/bt-btif ( 1213): HC lib lpm enable=0 return 0
D/bt-btif ( 1213): bte_main_disable
D/bt-btif ( 1213): bte_hci_disable
D/bt_hwcfg( 1213): hw_epilog_process
,I/bt-btif ( 1213): HC lpm_result_cb 0
D/wpa_supplicant( 4232): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 4232): wlan0: Deauthentication notification
D/wpa_supplicant( 4232): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 4232): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 4232): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 4232): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 4232): TDLS: Remove peers on disassociation
D/wpa_supplicant( 4232): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 4232): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4232): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
,D/wpa_supplicant( 4232): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4232): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4232): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb8a34d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 4232):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 4232): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 4232): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 4232): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4232): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/wpa_supplicant( 4232): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4232): EAPOL: External notification - portValid=0
V/        (  264): RouteController
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4232): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4232): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 4232): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 4232): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 4232): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 4232): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4232): EAPOL: External notification - portValid=0
D/wpa_supplicant( 4232): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 4232): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 4232): wlan0: No keys have been configured - skip key clearing
W/wpa_supplicant( 4232): USIM:  scard_deinit function
V/        (  264): RouteController
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiStateMachine(  957): handleMessage: E msg.what=147460
D/WifiStateMachine(  957): processMsg: SupplicantStoppingState
D/WifiStateMachine(  957): processMsg: DefaultState
,D/WifiStateMachine(  957): handleMessage: X
,D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  957): handleMessage: E msg.what=147462
D/WifiStateMachine(  957): processMsg: SupplicantStoppingState
D/WifiStateMachine(  957): processMsg: DefaultState
,D/WifiStateMachine(  957): handleMessage: X
I/ActivityManager(  957): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=5412 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,V/        (  264): RouteController
,W/NetworkManagementService(  957): route cmd failed: 
W/NetworkManagementService(  957): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  957): '
W/NetworkManagementService(  957): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  957): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  957): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  957): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  957): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  957): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  957): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  957): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  957): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  957): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  957): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  957): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  957): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  957): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  957): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/NetUtils(  957): android_net_utils_resetConnections in env=0x61f148d8 clazz=0x6a400001 iface=wlan0 mask=0x3
D/HyLog   ( 5412): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5412): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5412): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/QcConnectivityService(  957): resetConnections(wlan0, 3)
,D/bt_hwcfg( 1213): hw_epilog_cback Opcode:0x0C03 Status: 0
I/ActivityManager(  957): Killing 4328:com.lge.wireless_storage/u0a101 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1545): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/wpa_supplicant( 4232): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 4232): wlan0: Cancelling scan request
D/wpa_supplicant( 4232): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 4232): wlan0: Cancelling authentication timeout
D/wpa_supplicant( 4232): netlink: Operstate: linkmode=0, operstate=6
,D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
,V/NativeCrypto( 1545): Read error: ssl=0x639ef858: I/O error during system call, Connection timed out
,V/NativeCrypto( 1545): SSL shutdown failed: ssl=0x639ef858: I/O error during system call, Broken pipe
W/BroadcastQueue(  957): Exception when sending broadcast to ComponentInfo{com.lge.wireless_storage/com.lge.wireless_storage.NetworkReceiver}
W/BroadcastQueue(  957): android.os.DeadObjectException
W/BroadcastQueue(  957): 	at android.os.BinderProxy.transact(Native Method)
W/BroadcastQueue(  957): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:814)
W/BroadcastQueue(  957): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:239)
W/BroadcastQueue(  957): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:895)
W/BroadcastQueue(  957): 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:14216)
W/BroadcastQueue(  957): 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:387)
W/BroadcastQueue(  957): 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2168)
W/BroadcastQueue(  957): 	at android.os.Binder.execTransact(Binder.java:407)
W/BroadcastQueue(  957): 	at dalvik.system.NativeStart.run(Native Method)
,I/ActivityManager(  957): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=5427 uid=10101 gids={50101, 1028, 1015, 3003}
,I/ActivityManager(  957): Process com.lge.wireless_storage (pid 4328) has died and restarted (pid 5427).
,D/wpa_supplicant( 4232): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 4232): nl80211: Unsubscribe mgmt frames handle 0xb8a35590 (mode change)
,I/wpa_supplicant( 4232): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 4232): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
I/wpa_supplicant( 4232): [ITEC] Close WIFLUS socket interface - START
I/wpa_supplicant( 4232): [ITEC] - NOT INITIALIZED - DONE
D/WifiMonitor(  957): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
D/wpa_supplicant( 4232): Control interface directory not empty - leaving it behind
,D/wpa_supplicant( 4232): Get randomness: len=20 entropy=0
D/WifiStateMachine(  957): handleMessage: E msg.what=147458
D/WifiStateMachine(  957): processMsg: SupplicantStoppingState
D/WifiStateMachine(  957): Supplicant connection lost
,D/WifiMonitor(  957): WifiMonitorSingleton gotten
,D/Tethering(  957): InitialState.processMessage what=4
D/wpa_supplicant( 4232): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
,D/Tethering(  957): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering(  957): sendTetherStateChangedBroadcast 0, 0, 0
D/WifiStateMachine(  957): setWifiState: disabled
D/HyLog   ( 5427): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5427): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5427): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/WifiOffDelayIfNotUsed(  957): stopMonitoring
,W/Settings( 4913): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/WifiActivationWhileCharging(  957): register : WIFI_ACTIVATION_WHILE_CHARGING_OFF[1]
,E/WifiStateMachine(  957): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  957): useWiFiOffloading() : false
E/WifiStateMachine(  957): CONFIG_LGE_WLAN_PATH : true
,D/WifiStateMachine(  957): transitionTo: destState=InitialState
D/WifiStateMachine(  957): handleMessage: new destination call exit/enter
D/WifiStateMachine(  957): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  957): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine(  957): moveTempStackToStateStack: i=0,j=1
,I/Wireless_Storage( 5427): CONNECT : WIFI_P2P_STATE_CHANGED_ACTION
,V/WfdStateTracker( 1151): WfdStateTracker handleDirectStateChangedEvent: 0
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
D/WifiStateMachine(  957): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
,D/WifiStateMachine(  957): invokeEnterMethods: InitialState
,W/Settings( 1422): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/ActivityManager(  957): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=5440 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,I/WifiServiceExtension(  957): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServiceExtension(  957): batteryPsActivateMsgHandler : state:0 event:1
,I/WifiServiceExtension(  957): batteryPsActivateMsgHandler : this is not treated
D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
E/Parcel  (  511): Reading a NULL string not supported here.
,E/Parcel  (  511): Reading a NULL string not supported here.
D/Nat464Xlat(  957): requiresClat: netType=1, hasIPv4Address=false
,D/QcConnectivityService(  957): handleInetConditionChange: no active default network - ignore
D/LocSvc_java(  957): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, smCause: 0, isConnectedToProvisioningNetwork: false
D/GpsLocationProvider(  957): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
I/TelephonyProvider( 1447): getPreferredApnId: subscription=0
D/LocSvc_java(  957): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  957): ignore wifi update if we are not in OPENING or CLOSING
,D/DhcpStateMachine(  957): StoppedState
,D/HyLog   ( 5440): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5440): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5440): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/bt_hci_bdroid( 1213): bt_hc_worker_thread exiting
,W/bt_userial( 1213): select_read return size <=0:0, exiting userial_read_thread
,I/bt_userial_vendor( 1213): device fd = 84 close
,D/BTSNOOP-DISP( 1213): btsnoop_close
I/GKI_LINUX( 1213): GKI_destroy_task: GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1213): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 1213): GKI_destroy_task: GKI_destroy_task(): task [BTU] terminated
,I/GKI_LINUX( 1213): GKI_freeze: GKI_freeze
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:rfkill, action:3
,I/bt-btif ( 1213): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothServiceJni( 1213): adapter_state_change_callback: Status is: 0
D/BluetoothAdapterState( 1213): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
I/PCSuite ( 5440): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,W/BluetoothAdapterService( 1213): Stopping service com.broadcom.bt.service.hfp.BrcmHeadsetService
,W/BluetoothAdapterService( 1213): Stopping service com.android.bluetooth.a2dp.A2dpService
D/BrcmHeadsetService( 1213): Received stop request...Stopping profile...
W/BluetoothAdapterService( 1213): Stopping service com.android.bluetooth.hid.HidService
I/LGBluetoothHfpAdapter( 1213): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 1213): Cleaning up Bluetooth Handsfree callback object
,D/HeadsetStateMachine( 1213): Exit Disconnected: -1
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
W/BluetoothAdapterService( 1213): Stopping service com.android.bluetooth.hdp.HealthService
D/BluetoothHeadset(  957): Proxy object disconnected
D/BluetoothHeadset( 1447): Proxy object disconnected
,D/BluetoothHeadset( 1447): Proxy object disconnected
,D/BluetoothHeadset( 1447): Proxy object disconnected
D/BluetoothHeadset( 2556): Proxy object disconnected
D/HeadsetProfile( 2556): Bluetooth service disconnected
D/PCSuite ( 5440): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 5440): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,W/BluetoothAdapterService( 1213): Stopping service com.android.bluetooth.pan.PanService
D/A2dpService( 1213): Received stop request...Stopping profile...
,D/LGBluetoothA2dpAdapter( 1213): [BTUI] LGBluetoothA2dpAdapter cleanup
D/A2dpStateMachine( 1213): Exit Disconnected: -1
,W/LGBluetoothA2dpServiceJni( 1213): Cleaning up Bluetooth Handsfree callback object
,D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
,I/ActivityManager(  957): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=5456 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,D/BluetoothA2dp( 2556): Proxy object disconnected
D/A2dpProfile( 2556): Bluetooth service disconnected
,D/BluetoothA2dp(  957): Proxy object disconnected
D/BluetoothAdapterService(1116324896)( 1213): Message: 1
D/BluetoothAdapterService(1116324896)( 1213): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1213): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.hfp.BrcmHeadsetService, state = 10, doUpdate = true
,D/BluetoothAdapterService( 1213): Profile still running: com.broadcom.bt.service.sap.SapService
D/HidService( 1213): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
,W/BluetoothAdapterService( 1213): Stopping service com.android.bluetooth.map.BluetoothMapService
D/BluetoothInputDevice( 2556): Proxy object disconnected
D/HidProfile( 2556): Bluetooth service disconnected
,D/HeadsetStateMachine( 1213): Unbinding service...
,W/BluetoothAdapterService( 1213): Stopping service com.android.bluetooth.gatt.GattService
D/HeadsetPhoneState( 1213): [BTUI] listenForPhoneState : start = false
,D/LGBluetoothHfpManager( 1213): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 1213): [BTUI] listenForPhoneState : start = false
,W/BluetoothAdapterService( 1213): Stopping service com.broadcom.bt.service.sap.SapService
D/LGBluetoothHfpManager( 1213): [BTUI] listenForMultiSimPhoneState : start = false
W/Brcm_BluetoothHeadsetServiceJni( 1213): Cleaning up Bluetooth Handsfree Interface...
I/bt-btif ( 1213): cleanup
,I/ActivityManager(  957): Killing 4670:com.google.android.apps.magazines/u0a104 (adj 15): empty #17
D/bt-btif ( 1213): btif_disable_service: Current Services:0x120108
W/Brcm_BluetoothHeadsetServiceJni( 1213): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 1213): [BTUI] LGBluetoothHfpAdapter cleanup
D/HealthService( 1213): Received stop request...Stopping profile...
W/BluetoothAdapterService( 1213): Stopping service com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
D/BluetoothAdapterService(1116324896)( 1213): Message: 1
D/BluetoothAdapterService(1116324896)( 1213): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1213): onProfileServiceStateChange: serviceName=com.android.bluetooth.a2dp.A2dpService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1213): Profile still running: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterState( 1213): Stopping profile services that were post enabled
I/bt-btif ( 1213): cleanup
I/bt-btif ( 1213): ## A2DP STOP MEDIA TASK ##
I/GKI_LINUX( 1213): GKI_destroy_task: GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
D/bt-btif ( 1213): UIPC_Close : ch_id 5
D/bt-btif ( 1213): UIPC_Close : waiting for shutdown to complete
I/bt-btif ( 1213): UIPC SEND WAKE UP
I/bt-btif ( 1213): UIPC READ THREAD EXITING
I/bt-btif ( 1213): uipc_main_cleanup
I/bt-btif ( 1213): CLOSE CHANNEL 0
I/bt-btif ( 1213): CLOSE SERVER (FD 69)
D/bt-btif ( 1213): A2DP-CTRL-CHANNEL EVENT UIPC_CLOSE_EVT
I/bt-btif ( 1213): UIPC SEND WAKE UP
I/bt-btif ( 1213): CLOSE CHANNEL 1
I/bt-btif ( 1213): CLOSE CHANNEL 2
I/bt-btif ( 1213): CLOSE CHANNEL 3
I/bt-btif ( 1213): UIPC READ THREAD DONE
D/bt-btif ( 1213): UIPC_Close : shutdown complete
D/bt-btif ( 1213): MEDIA TASK EXITING
I/GKI_LINUX( 1213): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1213): GKI_destroy_task: GKI_destroy_task(): task [A2DP-MEDIA] terminated
D/bt-btif ( 1213): btif_disable_service: Current Services:0x120100
D/LGBluetoothAvrcpAdapter( 1213): [BTUI] cleanup
D/LGBluetoothAvrcpManager( 1213): [BTUI] terminateAvrcpManager
D/LGBluetoothAvrcpManager( 1213): [BTUI] cleanupPlayStatus() : mPlayStatus = 0
V/BluetoothAVRCP1.3ServiceJni( 1213): cleanupNativeAVRCP
I/bt-btif ( 1213): ## cleanup ##
D/bt-btif ( 1213): close_uinput
D/PanService( 1213): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
D/BluetoothTethering(  957): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering(  957): attempted to stop reverse tether with nothing tethered
D/BluetoothPan(  957): BluetoothPAN Proxy object disconnected
D/BluetoothAdapterService(1116324896)( 1213): Message: 1
D/BluetoothAdapterService(1116324896)( 1213): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1213): onProfileServiceStateChange: serviceName=com.android.bluetooth.hid.HidService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1213): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothHidServiceJni( 1213): Cleaning up Bluetooth HID Interface...
I/bt-btif ( 1213): cleanup
W/bt-btif ( 1213): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 1213): Cleaning up Bluetooth GID callback object
D/HyLog   ( 5456): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5456): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 5456): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/BluetoothMapService( 1213): Received stop request...Stopping profile...
D/BluetoothPan( 2556): BluetoothPAN Proxy object disconnected
D/PanProfile( 2556): Bluetooth service disconnected
D/BluetoothMapService( 1213): stop()
D/BluetoothMapService( 1213): MAP Service closeService in
D/LGBluetoothMapAdapter( 1213): [BT,UI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1213): MAP Service closeService out
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
D/BtGatt.DebugUtils( 1213): handleDebugAction() action=null
D/BluetoothMap( 2556): Proxy object disconnected
D/MapProfile( 2556): Bluetooth service disconnected
D/BtGatt.GattService( 1213): Received stop request...Stopping profile...
D/BtGatt.GattService( 1213): stop()
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
D/SapService( 1213): Received stop request...Stopping profile...
D/SapService( 1213): Stopping Bluetooth SapService
D/LGBluetoothSapAdapter( 1213): [BTUI] LGBluetoothSapAdapter cleanup
,D/LGBluetoothSapManager( 1213): [BTUI] terminateSapManager
D/LgeBluetoothSimManager( 1447): [BTUI] SAP_DISABLE_EVT
D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
D/BluetoothAdapterService(1116324896)( 1213): Message: 1
D/BluetoothAdapterService(1116324896)( 1213): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1213): onProfileServiceStateChange: serviceName=com.android.bluetooth.hdp.HealthService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1213): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothHealthServiceJni( 1213): Cleaning up Bluetooth Health Interface...
I/bt-btif ( 1213): cleanup
D/bt-btif ( 1213): Process name (droid.bluetooth)
D/bt-btif ( 1213): btif_disable_service: Current Services:0x120100
D/bt-btif ( 1213): btif_hl_disable
D/bt-btif ( 1213): btif_hl_signal_select_exit
D/bt-btif ( 1213): select unblocked ret=1
D/bt-btif ( 1213): btif_hl_select_wake_signaled, signal ret=1
D/bt-btif ( 1213): btif_hl_select_wake_signaled
D/bt-btif ( 1213): btif_hl_select_wake_reset
D/bt-btif ( 1213): btif_hl_select_wake_signaled, signal:2
D/bt-btif ( 1213): hl thread cleanup
D/bt-btif ( 1213): Exit hl_select_thread for btif_hl_signal_select_exit
W/BluetoothHealthServiceJni( 1213): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 1213): Cleaning up Bluetooth Health object
D/**BluetoothFTPService( 1213): Received stop request...Stopping profile...
D/**BluetoothFTPService( 1213): Stopping Bluetooth FTP Service
V/BluetoothFTPServiceJni( 1213): closeFtpServerNative
I/bt-btif ( 1213): cleanup
D/bt-btif ( 1213): btif_disable_service: Current Services:0x120000
,D/BluetoothAdapterService( 1213): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4289c420
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 1 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Going to sleep and all paused
D/BluetoothAdapterService(1116324896)( 1213): Message: 1
D/BluetoothAdapterService(1116324896)( 1213): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1213): onProfileServiceStateChange: serviceName=com.android.bluetooth.pan.PanService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1213): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothPanServiceJni( 1213): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 1213): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService(1116324896)( 1213): Message: 1
D/BluetoothAdapterService(1116324896)( 1213): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1213): onProfileServiceStateChange: serviceName=com.android.bluetooth.map.BluetoothMapService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1213): Profile still running: com.broadcom.bt.service.sap.SapService
D/BluetoothMapService( 1213): cleanup()
D/BluetoothMapService( 1213): MAP Service closeService in
D/LGBluetoothMapAdapter( 1213): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1213): MAP Service closeService out
D/BluetoothAdapterService(1116324896)( 1213): Message: 1
D/BluetoothAdapterService(1116324896)( 1213): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1213): onProfileServiceStateChange: serviceName=com.android.bluetooth.gatt.GattService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1213): Profile still running: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116324896)( 1213): Message: 1
D/BluetoothAdapterService(1116324896)( 1213): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1213): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.sap.SapService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1213): Profile still running: com.broadcom.bt.service.ftp.FTPService
W/BluetoothSAPServiceJni( 1213): ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
I/bt-btif ( 1213): cleanup
D/bt-btif ( 1213): btif_disable_service: Current Services:0x100000
W/BluetoothSAPServiceJni( 1213): ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService(1116324896)( 1213): Message: 1
D/BluetoothAdapterService(1116324896)( 1213): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1213): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.ftp.FTPService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1213): All profile services stopped...
D/BluetoothAdapterState( 1213): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 1213): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1213): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothFTPService( 1213): cleanup FTP Service
V/BluetoothFTPServiceJni( 1213): closeFtpServerNative
I/bt-btif ( 1213): cleanup
V/BluetoothFTPServiceJni( 1213): cleanupNative
W/BluetoothFTPServiceJni( 1213): Cleaning up Bluetooth FTP Server Interface...
W/BluetoothFTPServiceJni( 1213): Cleaning up Bluetooth FTP callback object
D/BluetoothFTPService( 1213): BluetoothFtpBinder.cleanup()
D/BluetoothFTPService( 1213): cleanup done
I/BluetoothAdapterState( 1213): Entering OffState
D/BluetoothManagerService(  957): Message: 60
D/BluetoothManagerService(  957): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  957): Broadcasting onBluetoothStateChange(false) to 12 receivers.
D/BluetoothHeadset(  957): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1447): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1447): onBluetoothStateChange: up=false
D/BluetoothA2dp(  957): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1447): onBluetoothStateChange: up=false
D/BluetoothMap( 2556): onBluetoothStateChange: up=false
D/BluetoothPbap( 2556): onBluetoothStateChange: up=false
D/Blu,etoothInputDevice( 2556): onBluetoothStateChange: up=false
D/BluetoothA2dp( 2556): onBluetoothStateChange: up=false
D/BluetoothHeadset( 2556): onBluetoothStateChange: up=false
D/BluetoothManagerService(  957): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  957): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothManagerService(  957): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@44c8b578 mBinding = false
D/BluetoothManagerService(  957): Sending unbind request.
D/BluetoothAdapterService(1116324896)( 1213): onUnbind, calling cleanup
D/BluetoothAdapterService(1116324896)( 1213): cleanup()
D/BluetoothAdapterService( 1213): Cleaning up adapter native....
I/bluedroid( 1213): cleanup 1
I/bt-btif ( 1213): btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
I/GKI_LINUX( 1213): GKI_destroy_task: GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
D/bt-btif ( 1213): btif_disassociate_evt: notify DISASSOCIATE_JVM
I/bt-btif ( 1213): HAL bt_hal_cbacks->thread_evt_cb
E/bt-gki  ( 1213): gki_pool_usage:  0: size     64 cur   0 max  11  total  48
E/bt-gki  ( 1213): gki_pool_usage:  1: size    288 cur   0 max   2  total  26
E/bt-gki  ( 1213): gki_pool_usage:  2: size    660 cur   0 max  23  total  45
E/bt-gki  ( 1213): gki_pool_usage:  3: size   4112 cur   0 max   3  total 200
E/bt-gki  ( 1213): gki_pool_usage:  4: size   8108 cur   0 max   0  total  20
E/bt-gki  ( 1213): pool:  4: not allocated
E/bt-gki  ( 1213): gki_pool_usage:  5: size    748 cur   0 max   0  total  64
E/bt-gki  ( 1213): pool:  5: not allocated
E/bt-gki  ( 1213): gki_pool_usage:  6: size    268 cur   0 max   0  total  60
E/bt-gki  ( 1213): pool:  6: not allocated
E/bt-gki  ( 1213): gki_pool_usage:  7: size  10264 cur   0 max   0  total   2
E/bt-gki  ( 1213): pool:  7: not allocated
E/bt-gki  ( 1213): gki_pool_usage:  8: size    128 cur   3 max   3  total  30
E/bt-gki  ( 1213): gki_pool_usage:  9: size   8192 cur   0 max   0  total   5
E/bt-gki  ( 1213): pool:  9: not allocated
D/bt-btif ( 1213): btif task exiting
I/GKI_LINUX( 1213): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 1213): GKI_destroy_task: GKI_destroy_task(): task [BTIF] terminated
I/GKI_LINUX( 1213): GKI_destroy_task: GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1213): GKI_destroy_task: GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1213): GKI_destroy_task: GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1213): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 1213): GKI_exit_task: GKI_exit_task 1 done
I/GKI_LINUX( 1213): GKI_exit_task: GKI_exit_task 0 done
D/BluetoothManagerService(  957): Bluetooth State Change Intent: 13 -> 10
D/bt-btif ( 1213): btif_shutdown_bluetooth done
I/BluetoothServiceJni( 1213): cleanupNative: return from cleanup
D/BluetoothAdapterService( 1213): Done cleaning up adapter native....
W/LGBluetoothServiceJni( 1213): Cleaning up Bluetooth Service callback object
D/LGBluetoothSettingsDBObserver( 1213): [BTUI] unregister observer for LG device name DB
D/LGBluetoothAPIService( 1151): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapterService(1116324896)( 1213): cleanup() done
D/LGBluetoothAPIService( 1151): Message: 2
D/BluetoothAdapterService(1116324896)( 1213): ****onDestroy()********
D/LGBluetoothAPIService( 1151): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@432a7320 mBinding = false
D/LGBluetoothAPIService( 1151): Sending unbind request.
D/BtGatt.GattService( 1213): cleanup()
W/bt-btif ( 1213): GATTC Module not enabled/already disabled
W/bt-btif ( 1213): GATTS Module not enabled/already disabled
D/BluetoothAdapter( 1137): 1116486392: getState() :  mService = null. Returning STATE_OFF
D/LGBluetoothAPIServer( 1213): [BTUI] onUnbind()
,D/LGBluetoothAPIServer( 1213): [BTUI] cleanup() done
D/LGBluetoothAPIServer( 1213): [BTUI] onDestroy()
E/LGBluetoothEventManager( 2556): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 2556): [BTUI] clear device connection state
,D/QRemote ( 5456): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 5456): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
I/QRemote ( 5456): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
,I/QRemote ( 5456): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
I/QRemote ( 5456): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 5456): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 5456): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/QRemote ( 5456): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,I/QRemote ( 5456): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
,D/PCSuite ( 5440): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,D/UsbSettingsReceiver( 2556): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 2556): [AUTORUN] sys.usb.config = boot,adb
D/UsbSettingsReceiver( 2556): [AUTORUN] sys.usb.state = boot,adb
D/UsbSettingsReceiver( 2556): [AUTORUN] persist.sys.usb.config = boot,adb
,D/UsbSettingsReceiver( 2556): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/Config  ( 2556): getOperator() : OPEN
D/UsbSettingsControl( 2556): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 2556): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 2556): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 2556): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 2556): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
,D/UsbSettingsControl( 2556): [AUTORUN] setTetherStatus() : status=false
,D/LGDMClient( 2797): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,I/ActivityManager(  957): Killing 4554:android.process.media/u0a23 (adj 15): empty #17
D/LGDMClient( 2797): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,I/ActivityManager(  957): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=5472 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 1 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Going to sleep and all paused
,D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=131101
D/WifiStateMachine(  957): processMsg: InitialState
D/WifiStateMachine(  957): processMsg: DefaultState
D/WifiStateMachine(  957): handleMessage: X
D/WifiStateMachine(  957): handleMessage: E msg.what=196614
,D/WifiStateMachine(  957): processMsg: InitialState
D/WifiStateMachine(  957): processMsg: DefaultState
,D/WifiStateMachine(  957): handleMessage: X
,D/HyLog   ( 5472): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5472): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5472): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 5472): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.wifi.supplicant.CONNECTION_CHANGE
,W/ContextImpl( 5472): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/PCSuite ( 5440): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 5440): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 5440): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/ActivityManager(  957): Killing 4818:com.lge.task/u0a43 (adj 15): empty #17
V/BluetoothPbapReceiver( 1213): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1213): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 1213): ***********state = 10
,D/DockEventReceiver( 2556): finishStartingService: stopping service
,D/BluetoothPermissionRequest( 2556): onReceive
,W/ContextImpl( 2556): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:156 com.android.settings.bluetooth.DockEventReceiver.onReceive:123 
E/LGBluetoothUtils( 2556): [BTUI] FileNotFoundException: readPropertyjava.io.FileNotFoundException: /data/misc/bluedroid/bluetooth_property.conf: open failed: ENOENT (No such file or directory)
,D/BluetoothDiscoverableTimeoutReceiver( 2556): cancelDiscoverableAlarm(): Enter
,D/LGBluetoothResetSettingReceiver( 2556): return without doing reset settings.
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 1 tasks}
D/ActivityManager(  957): resumeTopActivityLocked: Going to sleep and all paused
,D/LGBluetoothProfileConnectionReceiver( 2556): [BTUI] STATE_OFF : reset connected device information - BluetoothSettings
,D/LGBluetoothProfileConnectionReceiver_EasySetting( 5412): [BTUI] STATE_OFF : reset connected device information EasySettings
,D/AuthorizationBluetoothService( 1545): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=111
,D/Tethering(  957): MasterInitialState.processMessage what=3
,D/CaptivePortalTracker(  957): Disconnected from active network NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, smCause: 0, isConnectedToProvisioningNetwork: false
,D/QcConnectivityService(  957): setProvNotificationVisible: E visible=false networkType=1 extraInfo=null url=null
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,D/BubblePopupHelper( 1137): isShowingBubblePopup : false
,I/NetworkStateForAutoUpdateMonitor( 5004): [onReceive] BroadcastReceiver onReceive
,I/NetworkStateForAutoUpdateMonitor( 5004): [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,I/NetworkStateForAutoUpdateMonitor( 5004): [onReceive] connect :false
,I/AppUp4:CustModeStarterReceiver( 5004): onReceive
,D/AppUp4:CustFacade( 5004): Context : android.app.ReceiverRestrictedContext@42883278
D/AppUp4:CustFacade( 5004): isCustomizationCompleted : false
,D/AppUp4:CustFacade( 5004): isOpenOperator : true
,D/AppUp4:CustFacade( 5004): isPhone : true
,I/LicenseContentProvider( 5037): start selecting data
,D/SIMObserver( 5037): simInfo1
,I/AppUp4:EulaManager( 5004): getAgreementForKK : Eula agreement is false
,D/AppUp4:CustModeStarterReceiver( 5004): begin check event
,I/AppUp4:CustModeStarterReceiver( 5004): Event For GoodConnectivity, noConnectivity : true, but skip! 
,I/ActivityManager(  957): Start proc android.process.media for broadcast com.android.providers.downloads/.DownloadReceiver: pid=5497 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,D/dalvikvm(  268): GC_EXPLICIT freed 47K, 34% free 16472K/24832K, paused 2ms+3ms, total 53ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/HyLog   ( 5497): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5497): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5497): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 2ms+3ms, total 62ms
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 23ms
,V/DownloadManager( 5497): DownloadService onCreate
,I/DownloadManager( 5497): in removeSpuriousFiles
,V/DownloadManager( 5497): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5497): created cursor android.database.sqlite.SQLiteCursor@428b89a0 on behalf of 5497
,I/DownloadManager( 5497): in trimDatabase
,V/DownloadManager( 5497): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
,V/DownloadManager( 5497): created cursor android.database.sqlite.SQLiteCursor@428bb788 on behalf of 5497
,V/DownloadManager( 5497): DownloadService onStartCommand
,V/DownloadManager( 5497): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 5497): created cursor android.database.sqlite.SQLiteCursor@428bdeb8 on behalf of 5497
I/ActivityManager(  957): Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=5538 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
,V/DownloadManager( 5497): DownloadService onDestroy
,I/ActivityManager(  957): Killing 4797:com.android.providers.calendar/u0a16 (adj 15): empty #17
D/HyLog   ( 5538): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5538): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5538): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 1 tasks}
D/ActivityManager(  957): resumeTopActivityLocked: Going to sleep and all paused
,I/LGEmail ( 5538): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
,D/LGEmail ( 5538): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
,W/BaseRuntimeLoader( 5538): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5538): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5538): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5538): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/EAS     ( 5538): [EmailEAS.java] onReceive() - NetworkInfo.getType() = 1 (at EasBroadcastReceiver.java onReceive 38)
,D/EAS     ( 5538): [EmailEAS.java] onReceive() - bisConnected = false (at EasBroadcastReceiver.java onReceive 39)
,D/eas_req ( 5538): ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,W/linker  ( 5538): libHtmlEditor.so has text relocations. This is wasting memory and is a security risk. Please fix.
,D/HtmlEditor( 5538): JNI_OnLoad
D/HtmlAPI v1.36.23.33395.LG_apps_master( 5538): HTMLEditor_GetVersion() [HtmlEditor v1.36.23.33395.LG_apps_master]
,D/HtmlEditor( 5538): register_HtmlEditor, class=com/lge/email/jni/HtmlEditor
,I/dalvikvm( 5538): threadid=1: recursive native library load attempt (/system/lib/libHtmlEditor.so)
,I/ActivityManager(  957): Start proc com.android.mms for broadcast com.android.mms/.transaction.LgeMiscReceiver: pid=5557 uid=10035 gids={50035, 3003, 1028, 1015, 1023, 4002, 3002}
D/HtmlEditor( 5538): register_HtmlEditor, Success
D/HtmlEditor( 5538): register_HtmlEditorTimer, class=com/lge/email/jni/HtmlEditor$NativeHandler
D/HtmlEditor( 5538): register_HtmlEditorTimer, Success
D/HtmlEditor( 5538): register_HtmlEditorDownloader, class=com/lge/email/jni/HtmlEditor$Downloader
D/HtmlEditor( 5538): register_HtmlEditorDownloader, Success
D/HtmlEditor( 5538): register_HtmlEditorFont, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5538): register_HtmlEditorFont, Success
D/HtmlEditor( 5538): register_HtmlEditorDrawText, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5538): register_HtmlEditorDrawText, Success
D/HtmlEditor( 5538): register_HtmlEditorDrawImage, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5538): register_HtmlEditorDrawImage, Success
D/HtmlEditor( 5538): register_HtmlEditorWordIterator, class=com/lge/email/jni/HtmlEditor
D/HtmlEditor( 5538): register_HtmlEditorWordIterator, Success
D/HtmlEditor( 5538): JNI_OnLoad Success
I/HubEmail( 5538): JNI_OnLoad()
I/HubEmail( 5538): -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5538): registerNatives()
I/HubEmail( 5538): -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
I/HubEmail( 5538): registerNativeMethods()
,I/HubEmail( 5538): -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/Settings( 5538): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HyLog   ( 5557): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5557): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5557): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  957): Killing 4770:com.android.calendar/u0a15 (adj 15): empty #17
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 1 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Going to sleep and all paused
,I/ConversationSkinProvider( 5557): skin provider oncreate
,E/[MMS]   ( 5557): MmsSettings: [LGE] MmsSettings.initializeMmsSettings()
,W/BaseRuntimeLoader( 5557): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5557): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5557): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5557): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/[MMS]   ( 5557): MmsSettings: [LGE]loadXMLSettings() ++++++++++ >> Load default:false
I/[MMS]   ( 5557): MmsSettings: [LGE]loadXMLSettings() SIM(current) information
I/[MMS]   ( 5557): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
,E/[MMS]   ( 5557): MmsSettings: [LGE]loadXMLSettings() [Build] Country:EU, Operator:OPEN
D/[MMS]   ( 5557): MmsSettings: loadxmlstring=open_eu_mms_config
,D/[MMS]   ( 5557): MmsSettings: Matching Xml Data file name = 2131034168
,D/[MMS]   ( 5557): MmsSettings: [LGE]parseDTMF() file doesn't exist
,D/[MMS]   ( 5557): MmsSettings: [LGE]setDefaultDTMFVolume() set default DTMF value
E/[MMS]   ( 5557): MmsSettings: [LGE]loadXMLSettings(): Check current items.
D/[MMS]   ( 5557): MmsSettings: [LGE]---------------------------------------->
D/[MMS]   ( 5557): MmsSettings: [LGE]   sms_dr = [0]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   cb_on = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   sms_concat = [5]
D/[MMS]   ( 5557): MmsSettings: [LGE]   sms_char = [0]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_dr_r = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_dr_a = [1]
D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_rr_r = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_rr_a = [1]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   auto_retr = [1]
D/[MMS]   ( 5557): MmsSettings: [LGE]   auto_retr_r = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_priority = [1]
D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_validity = [6]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_creation = [2]
D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_size = [300]
D/[MMS]   ( 5557): MmsSettings: [LGE]   slide_dur = [5]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   recv_adv = [1]
D/[MMS]   ( 5557): MmsSettings: [LGE]   push_on = [1]
D/[MMS]   ( 5557): MmsSettings: [LGE]   del_old = [1]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   sms_limit = [500]
D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_limit = [50]
D/[MMS]   ( 5557): MmsSettings: [LGE]   max_editor_num = [2000]
D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_slide_num = [10]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_recipient_num = [20]
D/[MMS]   ( 5557): MmsSettings: [LGE]   attachement_storage = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   send_msg_enter_key = [1]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   spam_setting = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   anonymous_spam_setting = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_recipient_length = [64]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   sms_recipient_length = [20]
D/[MMS]   ( 5557): MmsSettings: [LGE]   recv_adv_invisible = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_creation_invisible = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_dr_r_invisible = [0]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_dr_a_invisible = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_rr_r_invisible = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_rr_a_invisible = [0]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   auto_retr_r_invisible = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_validity_invisible = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_priority_invisible = [0]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   sms_char_invisible = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   sms_dr_invisible = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   sms_validity_invisible = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   discard_visible = [0]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   appointment_invisible = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_pending_in_wifi_use = [1]
D/[MMS]   ( 5557): MmsSettings: [LGE]   attach_location = [1]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   custom_extract_ui = [1]
D/[MMS]   ( 5557): MmsSettings: [LGE]   msg_list_data_seperator = [1]
D/[MMS]   ( 5557): MmsSettings: [LGE]   animation_effect = [1]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   inline_msg_item = [1]
D/[MMS]   ( 5557): MmsSettings: [LGE]   display_as_slide_layout = [1]
D/[MMS]   ( 5557): MmsSettings: [LGE]   one_bubble = [1]
D/[MMS]   ( 5557): MmsSettings: [LGE]   hide_sync_header_update = [1]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   recipient_cc_bcc = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   ciq_on = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_enabled_when_data_disabled = [1]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   two_finger_flick = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   kr_skt_feature_set = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   kr_kt_feature_set = [0]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   kr_lgu_feature_set = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   docomo_message_setting = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   docomo_sim_card_set = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   docomo_nexti_phonebook_set = [0]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   docomo_function_validity_period = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   docomo_led_button_blink = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   docomo_dtmf_setting = [0]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   china_feature_set = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   media_resolution_restrict_off = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   attachment_save_in_slidesheow = [0]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_max_video_resolution = [320x240]
D/[MMS]   ( 5557): MmsSettings: [LGE]   email_over_sms = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   email_over_sms_gateway_num = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   addr_len_check = [0]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   message_poster = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   sticky_note = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   wificalling_feature_set = [0]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   online_album = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   online_album_dest_num = [000]
D/[MMS]   ( 5557): MmsSettings: [LGE]   appointment_invisible = [0]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   voice_mail = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   smsc_readonly = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   latin_america_fdn_check = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   sms_sent_time_mode = [0]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   fdn_gprs_check = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   reply_to_virtual_smsc = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   save_to_draft = [0]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_signature = [0]
D/[MMS]   ( 5557): MmsSettings: [LGE]   mms_callback = [0]
,D/[MMS]   ( 5557): MmsSettings: [LGE]   message_counters_key = [0]
,E/[MMS]   ( 5557): MmsSettings: [LGE]loadXMLSettings(): Check prefMmsConfig.
,I/[MMS]   ( 5557): MmsSettings: [LGE]loadXMLSettings() Phone(saved) information
I/[MMS]   ( 5557): MmsSettings: [LGE]loadXMLSettings() Mcc:450, Mnc:00, Gid:Default
E/[MMS]   ( 5557): MmsSettings: [LGE]loadXMLSettings(): SIM is NOT changed!!!
,E/[MMS]   ( 5557): MmsSettings: [LGE]loadXMLSettings(): SIM is not ready!!!
,D/MmsConfig( 5557): [LGE] setForceSmsGsmAlphabet_SystemProperties.set: 0
,I/[MMS]   ( 5557): MmsConfig: [LGE]getUaString=LG-D802 LG-Android-MMS-V4.0/1.2
,I/LGDrmService( 5557): _DRM_ServiceGet() : Bind lgdrm service
,E/Diag_Lib(  276): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  276): qmi_init:  Created client handle b7c1c0f0
,E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
,E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  276): Setting the api flag to : 1
,E/Diag_Lib(  276): qmi_client [276] 7: sending 47 bytes on fd = 16
E/Diag_Lib(  276): qmi_client [276] 7: Received 93 bytes on fd = 16
,E/Diag_Lib(  276):  API Flag .............. 1 
E/Diag_Lib(  276):  Message ID ............... 37 
E/Diag_Lib(  276): qmi_service_release called, user_handle=20200
E/Diag_Lib(  276): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  276): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  276): qmi_service_delete_client_txns : EXIT
E/Diag_Lib(  276): qmi_free_srvc_data : ENTRY
,E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
,E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEI: success getting IMEI
D/LGDRM   (  276): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
,E/Diag_Lib(  276): qmi_init:  Already initialized, not calling process init sequence
E/Diag_Lib(  276): qmi_init:  Created client handle b7c1c108
,E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
,E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEIviaQmi(): QMI Client Init Success!!
E/Diag_Lib(  276): Setting the api flag to : 1
,E/Diag_Lib(  276): qmi_client [276] 7: sending 47 bytes on fd = 16
,E/Diag_Lib(  276): qmi_client [276] 7: Received 93 bytes on fd = 16
E/Diag_Lib(  276):  API Flag .............. 1 
E/Diag_Lib(  276):  Message ID ............... 37 
E/Diag_Lib(  276): qmi_service_release called, user_handle=20200
E/Diag_Lib(  276): qmi_free_srvc_data : ENTRY
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : ENTRY
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : Wait for sync transactions to complete
E/Diag_Lib(  276): qmi_service_wait_for_sync_txn_completion : EXIT
E/Diag_Lib(  276): qmi_service_delete_client_txns : ENTRY - client_id: [2]
E/Diag_Lib(  276): qmi_service_delete_client_txns : EXIT
,E/Diag_Lib(  276): qmi_free_srvc_data : ENTRY
,E/Diag_Lib(  276): qmi_client [276] 7: sending 848 bytes on fd = 16
,E/Diag_Lib(  276): qmi_client [276] 7: Received 848 bytes on fd = 16
E/Diag_Lib(  276): Sending signal ...... to read cmd data 
E/Diag_Lib(  276): qmi error code.........:0
E/Diag_Lib(  276): qmi sys error code.........:0
D/DRM_Adap(  276): drmLibGetIMEI: success getting IMEI
D/LGDRM   (  276): [DRM] drmLibGetFlexInfo() : OP code (OPEN)
I/DrmWrapper( 5557): isDrmV1 =true
,V/DrmWrapper( 5557): isDrmV2 =false
,V/MmsConfig( 5557): [isMmsEnabledWhenDataDisabled]value=1
,V/MmsConfigStaticVar( 5557): [setMmsEnabledWhenDataDisabled]enabled=true
,V/MmsConfigStaticVar( 5557): [setMmsEnabledWhenDataRoamingDisabled]enabled=false
,D/CmasFeatures( 5557): [init]CMAS features are initialized for US country. Returning.
,V/Contact ( 5557): Contact init()_Create new insatnce
,I/MessagingNotification( 5557): registerLEDObserver
,I/MessagingNotification( 5557): registerLEDObserver REGISTER
,V/TelephonyAutoProfiling(  957): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/MmsConfig( 5557): [getMPDNSupport]is_KrDevice:false is_Mpdn:false is_Roaming:false networkOperator:
,I/LOG_TAG ( 5557): registerContactDBChangeObserver
D/CountryDetector(  957): The first listener is added
,E/ActivityThread( 5557): Failed to find provider info for com.lge.ims.provider.uc
D/LocationManagerService(  957): getProviders()=[passive, gps]
D/LocationManagerService(  957): request 43f4ae10 passive Request[POWER_NONE passive fastest=0] from android(1000)
D/LocationManagerService(  957): provider request: passive ProviderRequest[ON interval=0]
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm(  957): GC_EXPLICIT freed 1707K, 48% free 29593K/56776K, paused 4ms+13ms, total 198ms
,I/LgeMiscReceiver( 5557): intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
,I/LgeMiscReceiver( 5557): action = android.net.conn.CONNECTIVITY_CHANGE
,I/LgeMiscReceiver( 5557): networkInfo.isConnected() = false
,V/LGRssiData( 5557): [loadRssi] File not exist 
,V/LGRssiData( 5557): [loadRssi] File not exist 
,V/TelephonyAutoProfiling( 5557): [loadFeatureFromXml] *** start feature loading from xml
I/ActivityManager(  957): Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.MobileConnectivityChangeReceiver: pid=5592 uid=10052 gids={50052, 3003}
I/ActivityManager(  957): Killing 4723:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,V/TelephonyAutoProfiling( 5557): [getMatchedProfile] selected file : /cust/config/featureset.xml
,V/TelephonyAutoProfiling( 5557): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
,V/TelephonyAutoProfiling( 5557): [getValue] FEATURE key : vzw_roaming_state, value : null
,D/HyLog   ( 5592): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5592): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5592): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 1 tasks}
D/ActivityManager(  957): resumeTopActivityLocked: Going to sleep and all paused
,V/TelephonyAutoProfiling(  957): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/TelephonyAutoProfiling(  957): [getValue] FEATURE key : vzw_roaming_state, value : null
,V/LGRssiData( 5592): [loadRssi] File not exist 
,V/LGRssiData( 5592): [loadRssi] File not exist 
D/MobileConnectivityChangeReceiver( 5592): onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.MobileConnectivityChangeReceiver (has extras) }
,V/TelephonyAutoProfiling( 5592): [loadFeatureFromXml] *** start feature loading from xml
,D/MobileConnectivityChangeReceiver( 5592): onReceive CONNECTIVITY_CHANGE networkType=1
,W/BaseRuntimeLoader( 5592): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5592): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 5592): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 5592): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,V/TelephonyAutoProfiling( 5592): [getMatchedProfile] selected file : /cust/config/featureset.xml
V/TelephonyAutoProfiling( 5592): [loadDataFromXml] load feature from xml complete : {KRWapPushWithSpam=true, GLOBALspam=true, copy_submit_to_uicc=true, sms_short_code_extention=true, retry_to_enable_cb=true, support_nl_mcc_list=286, KSC5601Decoding=true, OperatorMessage=true, support_nl_single_shift=true, support_emoji_in_concat_message=true, allow_sending_empty_sms=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true}
V/TelephonyAutoProfiling( 5592): [getValue] FEATURE key : vzw_roaming_state, value : null
,E/PhoneMonitor( 5592): onOtaspChanged old =0, new =3
,V/PhoneMonitor( 5592): mOtaspPhoneStateListener#onOtaspChanged, mOtaspMode=3
I/ActivityManager(  957): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=5611 uid=10063 gids={50063, 3003, 1028, 1015}
I/ActivityManager(  957): Killing 4913:com.google.android.talk/u0a77 (adj 15): empty #17
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 1 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5611): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 5611): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5611): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  957): Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=5625 uid=10066 gids={50066, 4002, 3003, 1028}
,I/ActivityManager(  957): Killing 5051:com.android.contacts/u0a21 (adj 15): empty #17
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 1 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Going to sleep and all paused
,D/HyLog   ( 5625): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5625): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5625): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/ActivityManager(  957): Killing 5067:com.android.gallery3d/u0a27 (adj 15): empty #17
D/LGDMClient( 2797): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
D/LGDMSGCM( 5472): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.conn.CONNECTIVITY_CHANGE
,D/LGDMClient( 2797): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
W/ContextImpl( 5472): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
,I/NFS     ( 5427): connectivityManager.getNetworkInfo = TYPE_WIFI
I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 1 tasks}
D/ActivityManager(  957): resumeTopActivityLocked: Going to sleep and all paused
,I/Wireless_Storage( 5427): intf.getDisplayName() = rmnet_usb0
I/Wireless_Storage( 5427): intf.getDisplayName() = lo
I/Wireless_Storage( 5427): intf.getDisplayName() = sit0
I/Wireless_Storage( 5427): intf.getDisplayName() = p2p0
I/Wireless_Storage( 5427): intf.getDisplayName() = teql0
,I/Wireless_Storage( 5427): intf.getDisplayName() = wlan0
I/Wireless_Storage( 5427): intf.getDisplayName() = rev_rmnet8
I/Wireless_Storage( 5427): intf.getDisplayName() = rev_rmnet2
I/Wireless_Storage( 5427): intf.getDisplayName() = rev_rmnet3
I/Wireless_Storage( 5427): intf.getDisplayName() = rev_rmnet4
I/Wireless_Storage( 5427): intf.getDisplayName() = rev_rmnet5
I/Wireless_Storage( 5427): intf.getDisplayName() = rev_rmnet6
I/Wireless_Storage( 5427): intf.getDisplayName() = rev_rmnet7
I/Wireless_Storage( 5427): intf.getDisplayName() = rev_rmnet0
I/Wireless_Storage( 5427): intf.getDisplayName() = rev_rmnet1
I/Wireless_Storage( 5427): intf.getDisplayName() = rmnet0
I/Wireless_Storage( 5427): intf.getDisplayName() = rmnet1
,I/Wireless_Storage( 5427): intf.getDisplayName() = rmnet2
I/Wireless_Storage( 5427): intf.getDisplayName() = rmnet3
I/Wireless_Storage( 5427): intf.getDisplayName() = rmnet4
I/Wireless_Storage( 5427): intf.getDisplayName() = rmnet5
I/Wireless_Storage( 5427): intf.getDisplayName() = rmnet6
,I/Wireless_Storage( 5427): intf.getDisplayName() = rmnet7
,I/Wireless_Storage( 5427): CONNECT : WIFI_DISCONNECT
,I/ActivityManager(  957): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=5640 uid=10104 gids={50104, 3003, 1028, 1015}
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449683897742529396; DSPS: 11183386; Offset: 1449683556452673439
,D/HyLog   ( 5640): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 5640): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 5640): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/GAV2    ( 5640): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,V/WebViewChromium( 5640): Binding Chromium to the main looper Looper (main, tid 1) {4286f8d0}
,I/chromium( 5640): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/BrowserProcessMain( 5640): Initializing chromium process, renderers=0
,W/chromium( 5640): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
,I/Adreno-EGL( 5640): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 5640): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 5640): Build Date: 01/20/14 Mon
I/Adreno-EGL( 5640): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 5640): Remote Branch: 
I/Adreno-EGL( 5640): Local Patches: 
I/Adreno-EGL( 5640): Reconstruct Branch: 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/NSApplication( 5640): Starting up...
,I/ActivityManager(  957): Killing 4896:com.google.android.gms.wearable/u0a6 (adj 15): empty #17
,I/iu.Environment( 1939): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,I/ActivityManager(  957): resumeTopActivitiesLocked(): target Stack:ActivityStack{4335db18 stackId=1, 1 tasks}
,D/ActivityManager(  957): resumeTopActivityLocked: Going to sleep and all paused
,I/iu.UploadsManager( 1939): num queued entries: 0
,I/iu.UploadsManager( 1939): num updated entries: 0
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/iu.SyncManager( 1939): NEXT; no task
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  957): handleInetConditionChange: no active default network - ignore
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiP2pService(  957): P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,D/WifiP2pService(  957): DefaultState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiStateMachine(  957): handleMessage: E msg.what=131089
,D/WifiStateMachine(  957): processMsg: InitialState
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiStateMachine(  957): processMsg: DefaultState
D/WifiStateMachine(  957): handleMessage: X
,D/dalvikvm( 2618): GC_CONCURRENT freed 7746K, 32% free 16906K/24832K, paused 15ms+2ms, total 105ms
,D/dalvikvm( 2618): WAIT_FOR_CONCURRENT_GC blocked 88ms
,D/dalvikvm( 2618): GC_CONCURRENT freed 1814K, 31% free 17140K/24832K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 2618): WAIT_FOR_CONCURRENT_GC blocked 22ms
,I/Mlt MonitorService( 2618): parseLastkmsg to dump
,I/GAV2    ( 5640): Thread[GAThread,5,main]: No campaign data found.
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=108
,D/ConnectivityServiceHSM(  957): NetTransition Wakelock for ConnectedState released by timeout
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  957): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449683917743629544; DSPS: 11838782; Offset: 1449683556452674955
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  957): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449683937745915059; DSPS: 12494217; Offset: 1449683556452671651
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449683940057, nextTick: 59968, mDrawingTime: 5
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449683940060, nextTick: 59972, mDrawingTime: 1
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  957): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449683957747516091; DSPS: 13149629; Offset: 1449683556452685769
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449683977749472647; DSPS: 13805053; Offset: 1449683556452689200
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  957): updateLightListLocked :r=NotificationRecord(0x42c781e8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  957): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1545): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1545): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1545): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1545): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1545): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1545): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1545): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1545): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4883): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4883): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4883): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4883): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4883): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4883): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4883): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4883): 	at dalvik.system.NativeStart.run(Native Method)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 4883): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 4883): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449683997751146546; DSPS: 14460468; Offset: 1449683556452684632
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684000041, nextTick: 59969, mDrawingTime: 9
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684000056, nextTick: 59975, mDrawingTime: 1
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  957): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684017753072631; DSPS: 15115891; Offset: 1449683556452688110
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684037755604656; DSPS: 15771335; Offset: 1449683556452656658
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684057756966054; DSPS: 16426739; Offset: 1449683556452675283
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684060038, nextTick: 59974, mDrawingTime: 10
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684060064, nextTick: 59964, mDrawingTime: 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684077758844171; DSPS: 17082160; Offset: 1449683556452691828
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684097760253747; DSPS: 17737567; Offset: 1449683556452667078
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684117761725093; DSPS: 18392975; Offset: 1449683556452673580
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684120041, nextTick: 59963, mDrawingTime: 13
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684120057, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684137763504149; DSPS: 19048393; Offset: 1449683556452682616
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684157765695652; DSPS: 19703825; Offset: 1449683556452676854
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1137): handleBatteryUpdate (2) (100)
D/WifiController(  957): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684177767449967; DSPS: 20359243; Offset: 1449683556452661149
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684180034, nextTick: 59979, mDrawingTime: 11
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684180057, nextTick: 59974, mDrawingTime: 1
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  957): handleInetConditionChange: no active default network - ignore
,I/LocationManagerService(  957): remove 43f4ae10
,D/LocationManagerService(  957): provider request: passive ProviderRequest[ON interval=0]
,D/LocationManagerService(  957): getAllProviders()=[passive, gps, network]
,D/LocationManagerService(  957): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/LocationManagerService(  957): getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,D/LocationManagerService(  957): getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684197775393658; DSPS: 21014863; Offset: 1449683556452670270
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684217776888910; DSPS: 21670272; Offset: 1449683556452670160
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684237778526036; DSPS: 22325686; Offset: 1449683556452659337
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684240026, nextTick: 59999, mDrawingTime: 6
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684240068, nextTick: 59963, mDrawingTime: 1
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684257780317853; DSPS: 22981104; Offset: 1449683556452681135
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684277781618209; DSPS: 23636507; Offset: 1449683556452669235
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  957): updateLightListLocked :r=NotificationRecord(0x432a56c0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  957): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1545): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1545): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1545): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1545): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1545): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1545): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1545): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1545): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4883): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4883): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4883): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4883): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4883): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4883): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4883): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4883): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4883): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684297783127889; DSPS: 24291916; Offset: 1449683556452683554
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684300045, nextTick: 59966, mDrawingTime: 9
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684300058, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684317785591944; DSPS: 24947357; Offset: 1449683556452675685
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684337786830426; DSPS: 25602758; Offset: 1449683556452662946
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684357788496878; DSPS: 26258172; Offset: 1449683556452681449
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684360050, nextTick: 59967, mDrawingTime: 8
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684360058, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684377790448431; DSPS: 26913596; Offset: 1449683556452679877
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684397792073893; DSPS: 27569009; Offset: 1449683556452687907
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  957): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684417793975135; DSPS: 28224432; Offset: 1449683556452666542
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684420050, nextTick: 59975, mDrawingTime: 5
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684420054, nextTick: 59977, mDrawingTime: 1
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684437795801795; DSPS: 28879852; Offset: 1449683556452662147
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684457797454755; DSPS: 29535266; Offset: 1449683556452667158
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684477799045738; DSPS: 30190678; Offset: 1449683556452671227
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684480041, nextTick: 59969, mDrawingTime: 9
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684480056, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684497800612396; DSPS: 30846089; Offset: 1449683556452681488
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684517801976712; DSPS: 31501494; Offset: 1449683556452672513
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684537803728214; DSPS: 32156911; Offset: 1449683556452684513
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684540050, nextTick: 59976, mDrawingTime: 5
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684540054, nextTick: 59955, mDrawingTime: 8
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684557805496436; DSPS: 32812329; Offset: 1449683556452682716
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684577807052210; DSPS: 33467740; Offset: 1449683556452682093
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  957): updateLightListLocked :r=NotificationRecord(0x43d05948: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  957): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1545): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1545): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1545): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1545): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1545): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1545): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1545): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1545): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4883): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4883): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4883): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4883): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4883): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4883): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4883): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4883): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4883): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684597808665535; DSPS: 34123153; Offset: 1449683556452677987
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684600050, nextTick: 59967, mDrawingTime: 8
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684600058, nextTick: 59971, mDrawingTime: 3
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684617810222611; DSPS: 34778564; Offset: 1449683556452678666
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684637812034166; DSPS: 35433984; Offset: 1449683556452659166
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684657813899418; DSPS: 36089405; Offset: 1449683556452662846
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684660041, nextTick: 59984, mDrawingTime: 5
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684660047, nextTick: 59967, mDrawingTime: 7
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684677815514048; DSPS: 36744818; Offset: 1449683556452660045
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684697817103675; DSPS: 37400230; Offset: 1449683556452662758
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684717818936115; DSPS: 38055650; Offset: 1449683556452664143
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684720052, nextTick: 59973, mDrawingTime: 5
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684720056, nextTick: 59973, mDrawingTime: 3
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684737820283555; DSPS: 38711054; Offset: 1449683556452668809
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684757822080369; DSPS: 39366473; Offset: 1449683556452665086
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684777823703435; DSPS: 40021886; Offset: 1449683556452670721
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684780041, nextTick: 59973, mDrawingTime: 8
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684780052, nextTick: 59977, mDrawingTime: 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684797826104521; DSPS: 40677325; Offset: 1449683556452660918
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684817827912483; DSPS: 41332744; Offset: 1449683556452668343
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684837829440443; DSPS: 41988154; Offset: 1449683556452670424
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684840046, nextTick: 59959, mDrawingTime: 12
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684840063, nextTick: 59968, mDrawingTime: 1
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  957): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  957): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684857830999916; DSPS: 42643565; Offset: 1449683556452673500
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684877832617772; DSPS: 43298978; Offset: 1449683556452673925
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  957): updateLightListLocked :r=NotificationRecord(0x43259050: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  957): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1545): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1545): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1545): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1545): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1545): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1545): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1545): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1545): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4883): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4883): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4883): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4883): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4883): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4883): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4883): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4883): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4883): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684897834144796; DSPS: 43954388; Offset: 1449683556452675070
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684900057, nextTick: 59967, mDrawingTime: 7
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684900060, nextTick: 59971, mDrawingTime: 1
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684917836190466; DSPS: 44609815; Offset: 1449683556452676062
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684937837990874; DSPS: 45265234; Offset: 1449683556452675933
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684957839820451; DSPS: 45920654; Offset: 1449683556452674455
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684960046, nextTick: 59978, mDrawingTime: 5
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449684960051, nextTick: 59977, mDrawingTime: 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684977841748932; DSPS: 46576077; Offset: 1449683556452680329
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449684997843616372; DSPS: 47231499; Offset: 1449683556452655679
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685017845579178; DSPS: 47886923; Offset: 1449683556452665360
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449685020043, nextTick: 59971, mDrawingTime: 8
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449685020055, nextTick: 59976, mDrawingTime: 1
,D/dalvikvm(  957): GC_CONCURRENT freed 3189K, 48% free 29565K/56776K, paused 6ms+10ms, total 152ms
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685037847407867; DSPS: 48542343; Offset: 1449683556452662994
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685057849217808; DSPS: 49197762; Offset: 1449683556452672398
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685077851130457; DSPS: 49853185; Offset: 1449683556452662440
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449685080042, nextTick: 59975, mDrawingTime: 8
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449685080050, nextTick: 59981, mDrawingTime: 1
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685097852865188; DSPS: 50508601; Offset: 1449683556452688187
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685117854642993; DSPS: 51164020; Offset: 1449683556452665454
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685137856925121; DSPS: 51819454; Offset: 1449683556452689282
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449685140026, nextTick: 59988, mDrawingTime: 9
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449685140067, nextTick: 59964, mDrawingTime: 1
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685157858897561; DSPS: 52474879; Offset: 1449683556452678079
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685177860758596; DSPS: 53130300; Offset: 1449683556452677542
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  957): updateLightListLocked :r=NotificationRecord(0x43f4bad8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  957): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1545): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1545): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1545): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1545): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1545): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1545): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1545): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1545): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4883): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4883): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4883): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4883): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4883): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4883): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4883): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4883): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4883): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1137): handleBatteryUpdate (2) (100)
D/WifiController(  957): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 269 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1137): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685197862148900; DSPS: 53785706; Offset: 1449683556452664037
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449685200034, nextTick: 59983, mDrawingTime: 8
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449685200058, nextTick: 59975, mDrawingTime: 0
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685217864049309; DSPS: 54441128; Offset: 1449683556452672356
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685237865942063; DSPS: 55096550; Offset: 1449683556452673021
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685257867582055; DSPS: 55751964; Offset: 1449683556452665063
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449685260043, nextTick: 59968, mDrawingTime: 10
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449685260055, nextTick: 59975, mDrawingTime: 1
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685277868968870; DSPS: 56407369; Offset: 1449683556452678587
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685297870976727; DSPS: 57062795; Offset: 1449683556452672284
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685317876324166; DSPS: 57718330; Offset: 1449683556452679147
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449685320023, nextTick: 60001, mDrawingTime: 6
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449685320061, nextTick: 59970, mDrawingTime: 1
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685337877899733; DSPS: 58373742; Offset: 1449683556452667800
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685357879271808; DSPS: 59029147; Offset: 1449683556452666584
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685377881067060; DSPS: 59684566; Offset: 1449683556452661299
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449685380082, nextTick: 59947, mDrawingTime: 3
,I/ProcessStatsService(  957): Prepared write state in 59ms
D/Clock   ( 1137): Clock updated, drawingStartTime : 1449685380085, nextTick: 59946, mDrawingTime: 1
D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/ProcessStatsService(  957): Pruning old procstats: /data/system/procstats/state-2015-12-09-06-35-06.bin
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685397882882782; DSPS: 60339985; Offset: 1449683556452676484
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685417884460847; DSPS: 60995397; Offset: 1449683556452667635
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685437886420475; DSPS: 61650821; Offset: 1449683556452674138
,D/KeyguardUpdateMonitor( 1137): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1137): handleTimeUpdate
,D/KeyguardModel( 1137): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449685440057, nextTick: 59973, mDrawingTime: 2
,D/Clock   ( 1137): Clock updated, drawingStartTime : 1449685440058, nextTick: 59973, mDrawingTime: 1
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685457888119322; DSPS: 62306237; Offset: 1449683556452664000
,D/qcom_sensors_hal(  957): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  957): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  957): hal_ts_offset_is: Apps: 1449685477889432387; DSPS: 62961640; Offset: 1449683556452664809
,I/GLSUser ( 1545): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1545): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1545): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1545): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1545): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1545): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  957): updateLightListLocked :r=NotificationRecord(0x4441dd38: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  957): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1545): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1545): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1545): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1545): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1545): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1545): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1545): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1545): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 4883): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4883): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 4883): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 4883): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 4883): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 4883): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 4883): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 4883): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 4883): Ignoring header User-Agent because its value was null.
D/libc    (  264): _dns_getaddrinfo: iptype =1
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/dalvikvm( 1545): GC_CONCURRENT freed 1797K, 27% free 18144K/24832K, paused 3ms+3ms, total 98ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,TIME-OUT KILL (timeout was 1800000ms)
```
