#### Test 5133502860beea6_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
W/GAV2    ( 4007): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  962): Killing 3410:com.google.android.gm/u0a68 (adj 15): empty #17
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{4306a0a0 stackId=1, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{431e78c8 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm( 1958): GC_CONCURRENT freed 1563K, 26% free 18401K/24832K, paused 2ms+3ms, total 26ms
D/ChimeraCfgMgr( 1958): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1958): Module APK com.google.android.play.games already loaded
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1958): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1958): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1958): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  962): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,E/ThermalEngine(  284): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
D/AndroidRuntime( 4062): 
D/AndroidRuntime( 4062): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4062): CheckJNI is OFF
D/dalvikvm( 4062): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4062): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4062): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4062): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4062): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4062): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
D/WifiController(  962): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/memtrack( 4062): Couldn't load memtrack module (No such file or directory)
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
E/android.os.Debug( 4062): failed to load memtrack module: -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4062): Calling main entry com.android.commands.am.Am
I/ActivityManager(  962): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4062
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{4306a0a0 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (133 us)
V/ActivityManager(  962): Moving to PAUSING: ActivityRecord{431e78c8 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  962): resumeTopActivityLocked: Pausing null
V/ActivityManager(  962): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  962): startService SlideAside
W/ContextImpl(  962): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  962): setFocusedStack: mFocusedStack=ActivityStack{4306a0a0 stackId=1, 2 tasks}
D/UsbSettingsControl( 2521): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2521): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/ActivityManager(  962): allPausedActivitiesComplete: r=ActivityRecord{431e78c8 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  962): Moving to PAUSED: ActivityRecord{431e78c8 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{4306a0a0 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Restarting ActivityRecord{44d3e170 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 3469): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/AndroidRuntime( 4062): Shutting down VM
D/dalvikvm( 4062): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
I/ActivityManager(  962): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4080 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
V/ActivityManager(  962): Moving to RESUMED: ActivityRecord{44d3e170 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
I/SlideAside( 3469): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3469): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/HyLog   ( 4080): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4080): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4080): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4080): Binding Chromium to the background looper Looper (main, tid 1) {4284a0a8}
I/chromium( 4080): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4080): Initializing chromium process, renderers=0
W/chromium( 4080): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4080): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4080): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4080): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4080): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4080): Remote Branch: 
I/Adreno-EGL( 4080): Local Patches: 
I/Adreno-EGL( 4080): Reconstruct Branch: 
I/dalvikvm( 4080): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4080): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4080): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4080): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4080): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4080): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4080): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4080): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4080): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4080): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4080): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4080): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4080): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4080): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4080): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4080): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4080): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4080): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4080): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4080): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4080): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4080): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4080): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4080): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4080): Enabling debug mode 0
,W/AwContents( 4080): nativeOnDraw failed; clearing to background color.
,I/ActivityManager(  962): Displayed com.test.thalitest/.MainActivity: +526ms
,I/ActivityManager( 4080): Timeline: Activity_idle id: android.os.BinderProxy@4284b968 time:122437
,D/JsMessageQueue( 4080): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4080): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4284fa48
,D/dalvikvm( 4080): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4284fa48
,D/jxcore_app_log( 4080): JniHelper::setJavaVM(0x41717838), pthread_self() = 1631689872
,D/JX-Cordova( 4080): jxcore cordova android initializing
,I/dalvikvm( 4080): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 4080): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
,D/dalvikvm( 4080): VFY: replacing opcode 0x6e at 0x0045
,I/ActivityManager(  962): Timeline: Activity_windows_visible id: ActivityRecord{44d3e170 u0 com.test.thalitest/.MainActivity t3} time:122656
D/ActivityManager(  962): no-history finish of ActivityRecord{431e78c8 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  962): Finishing activity token=Token{43345b70 ActivityRecord{431e78c8 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  962): Moving to FINISHING: ActivityRecord{431e78c8 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{44d3e170 u0 com.test.thalitest/.MainActivity t3}
,V/ActivityManager(  962): Moving to STOPPING: ActivityRecord{431e78c8 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/UsbSettings( 2521): [AUTORUN] onStop()
,V/ActivityManager(  962): Moving to STOPPED: ActivityRecord{431e78c8 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,D/dalvikvm( 4080): GC_CONCURRENT freed 2882K, 13% free 21751K/24832K, paused 3ms+1ms, total 34ms
,D/dalvikvm( 4080): WAIT_FOR_CONCURRENT_GC blocked 18ms
,I/dalvikvm-heap( 4080): Grow heap (frag case) to 23.508MB for 98002-byte allocation
,D/dalvikvm( 4080): GC_FOR_ALLOC freed 218K, 13% free 21750K/24928K, paused 20ms, total 20ms
,I/dalvikvm-heap( 4080): Grow heap (frag case) to 23.554MB for 146998-byte allocation
,D/dalvikvm( 4080): GC_FOR_ALLOC freed 257K, 14% free 21798K/25072K, paused 22ms, total 23ms
,I/dalvikvm-heap( 4080): Grow heap (frag case) to 23.671MB for 220492-byte allocation
,D/dalvikvm( 4080): GC_FOR_ALLOC freed 376K, 14% free 21874K/25288K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4080): Grow heap (frag case) to 23.850MB for 330734-byte allocation
,D/dalvikvm( 4080): GC_FOR_ALLOC freed 580K, 15% free 21998K/25612K, paused 21ms, total 22ms
,I/dalvikvm-heap( 4080): Grow heap (frag case) to 24.129MB for 496096-byte allocation
,D/dalvikvm( 4080): GC_FOR_ALLOC freed 882K, 16% free 22177K/26100K, paused 22ms, total 24ms
,D/dalvikvm( 4080): GC_FOR_ALLOC freed 1306K, 15% free 22437K/26100K, paused 24ms, total 24ms
,I/dalvikvm-heap( 4080): Grow heap (frag case) to 25.150MB for 1116206-byte allocation
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
D/dalvikvm( 4080): GC_CONCURRENT freed 1808K, 17% free 22833K/27192K, paused 0ms+6ms, total 37ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4080): GC_FOR_ALLOC freed 296K, 17% free 22758K/27192K, paused 23ms, total 23ms
I/dalvikvm-heap( 4080): Grow heap (frag case) to 25.995MB for 1674304-byte allocation
,D/dalvikvm( 4080): GC_CONCURRENT freed 1764K, 19% free 23358K/28828K, paused 1ms+4ms, total 45ms
,D/dalvikvm( 4080): GC_FOR_ALLOC freed 1339K, 19% free 23430K/28828K, paused 24ms, total 25ms
,I/dalvikvm-heap( 4080): Grow heap (frag case) to 27.450MB for 2511452-byte allocation
,D/dalvikvm( 4080): GC_CONCURRENT freed 291K, 18% free 25750K/31284K, paused 2ms+1ms, total 30ms
,D/dalvikvm( 4080): GC_CONCURRENT freed 4381K, 22% free 24419K/31284K, paused 2ms+4ms, total 38ms
,D/dalvikvm( 4080): WAIT_FOR_CONCURRENT_GC blocked 27ms
,I/dalvikvm-heap( 4080): Grow heap (frag case) to 29.613MB for 3767174-byte allocation
,D/dalvikvm( 4080): GC_CONCURRENT freed 376K, 21% free 27858K/34964K, paused 2ms+3ms, total 30ms
,D/dalvikvm( 4080): GC_FOR_ALLOC freed 2907K, 28% free 25366K/34964K, paused 22ms, total 22ms
,W/jxcore-log( 4080): Initializing JXcore engine
,W/jxcore-log( 4080): JXcore engine is ready
,D/dalvikvm( 4080): GC_CONCURRENT freed 303K, 20% free 28023K/34964K, paused 0ms+1ms, total 22ms
,D/dalvikvm( 4080): WAIT_FOR_CONCURRENT_GC blocked 20ms
,W/jxcore-log( 4080): Starting JXcore engine
,W/jxcore-log( 4080): Platform android
W/jxcore-log( 4080): 
,W/jxcore-log( 4080): Process ARCH arm
W/jxcore-log( 4080): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/GAV2    ( 4007): Thread[GAThread,5,main]: No campaign data found.
,I/jxcore-log( 4080): JXcore Cordova bridge is ready!
I/jxcore-log( 4080): 
,W/jxcore-log( 4080): JXcore engine is started
,I/chromium( 4080): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/chromium( 4080): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4080): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/jxcore-log( 4080): Toggling radios to true
I/jxcore-log( 4080): 
,D/BluetoothManagerService(  962): Message: 20
D/BluetoothManagerService(  962): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@448e6418:true
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  962): enable():  mBluetooth =null mBinding = false
,D/BluetoothManagerService(  962): Message: 1
,D/BluetoothManagerService(  962): MESSAGE_ENABLE: mBluetooth = null
,D/BluetoothAdapterService( 1215): REFCOUNT: CREATED. INSTANCE_COUNT1
,D/BluetoothAdapterService(1116189344)( 1215): onCreate
,D/BluetoothManagerService(  962): Message: 20
D/BluetoothManagerService(  962): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@448b6bb8:true
,D/BluetoothAdapterState( 1215): make
,I/bluedroid( 1215): init ready=0
D/bt-btif ( 1215): in initialized:0
D/bt-btif ( 1215): root, p->name:Bluedroid, child/value:0x60653bf0, bytes:160
,D/bt-btif ( 1215): p->used:0, type:0, p->flag:0
,I/BluetoothAdapterState( 1215): Entering OffState
,I/bte_conf( 1215): Attempt to load stack conf from /etc/bluetooth/bt_stack.conf
W/BT_PROF ( 1215): set profile trace flags 0x0
D/BTIF_CORE( 1215): [BTUI] lge_load_bluetooth_address
D/bt-btif ( 1215):  [BTUI] Load_abtddress
D/bt-btif ( 1215): PERSIST_BDADDR_PROPERTY is  34:FC:EF:9D:93:0B
D/bt-btif ( 1215): Got prior random BDA 34:FC:EF:9D:93:0B
,D/btif_config_util( 1215): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/lge_bdaddr_loader( 4130): [BTUI] bdaddr_loader ::: START
,D/lge_bdaddr_loader( 4130): [BTUI] bluetooth_load_bdaddress
,D/lge_bdaddr_loader( 4130): [BTUI] bdaddr to set in property : 34:FC:EF:9D:93:0B
,E/lge_bdaddr_loader( 4130): [BTUI] bluetooth_load_bdaddress : OK => 34:FC:EF:9D:93:0B
,D/lge_bdaddr_loader( 4130): [BTUI] bdaddr_loader ::: END
,I/bluedroid( 1215): get_profile_interface socket
,I/bt-btif ( 1215): btif_get_adapter_property 2
I/bt-btif ( 1215): btif_get_adapter_property 1
,D/BluetoothAdapterService(1116189344)( 1215): onBind
D/BluetoothManagerService(  962): BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,D/BluetoothManagerService(  962): Message: 40
D/BluetoothManagerService(  962): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
,I/bluedroid( 1215): config_hci_snoop_log
D/BluetoothManagerService(  962): Calling onBluetoothServiceUp callbacks
,D/BluetoothManagerService(  962): Broadcasting onBluetoothServiceUp() to 8 receivers.
D/dalvikvm( 1215): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
I/GKI_LINUX( 1215): gki_task_entry: gki_task_entry task_id=1 [BTIF] starting
D/bt-btif ( 1215): btif task starting
D/bt-btif ( 1215): btif_associate_evt: notify ASSOCIATE_JVM
I/bt-btif ( 1215): HAL bt_hal_cbacks->thread_evt_cb
I/bt-btif ( 1215): execute storage request event : 3
D/bt-btif ( 1215): btif_storage_get_adapter_property property->type:2 
I/bt-btif ( 1215): HAL bt_hal_cbacks->adapter_properties_cb
I/bt-btif ( 1215): execute storage request event : 3
D/bt-btif ( 1215): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1215): in, bd addr:, prop type:1, len:512
I/bt-btif ( 1215): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothManagerService(  962): Bluetooth Adapter name changed to Thali Test's G2
D/BluetoothManagerService(  962): Stored Bluetooth name: Thali Test's G2
D/BluetoothAdapterService(1116189344)( 1215): Enable called with quiet mode status =  false
D/BluetoothAdapterState( 1215): CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
I/BluetoothAdapterState( 1215): Bluetooth adapter state changed: 10-> 11
D/BluetoothAdapterService( 1215): Broadcasting updateAdapterState() to 1 receivers.
,D/BluetoothManagerService(  962): Message: 60
D/BluetoothManagerService(  962): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
,D/BluetoothManagerService(  962): Bluetooth State Change Intent: 10 -> 11
,D/BluetoothAdapterService(1116189344)( 1215): processStart()
,D/LGBluetoothAPIService( 1157): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothAdapterService(1116189344)( 1215): processStart(): Make Bond State Machine
,D/BluetoothBondStateMachine( 1215): make
,D/BluetoothAdapterService( 1215): setAdapterService(): set to: null
,D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4287b2a0
D/LGBluetoothServiceAdapter( 1215): [BTUI] check adapter is available - false.
D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4287b2a0
D/LGBluetoothServiceAdapter( 1215): [BTUI] check adapter is available - true : set adapter available.
,D/LGBluetoothSettingsDBObserver( 1215): [BTUI] register observer for LG device name DB
,E/BluetoothAdapterService( 1215): File transfer profiels supported!!
,W/BluetoothAdapterService( 1215): Starting service com.broadcom.bt.service.hfp.BrcmHeadsetService
,D/BluetoothHeadset(  962): Proxy object connected
,D/BluetoothHeadset( 1448): Proxy object connected
D/BluetoothHeadset( 1448): Proxy object connected
,D/BluetoothHeadset( 1448): Proxy object connected
,D/BrcmHeadsetService( 1215): Received start request. Starting profile...
I/Brcm_BluetoothHeadsetServiceJni( 1215): classInitNative: succeeds
,D/HeadsetStateMachine( 1215): make
,E/BluetoothAdapterService( 1215): File transfer profiels supported!!
,W/BluetoothAdapterService( 1215): Starting service com.android.bluetooth.a2dp.A2dpService
,E/BluetoothAdapterService( 1215): File transfer profiels supported!!
,I/BluetoothBondStateMachine( 1215): StableState(): Entering Off State
,W/BluetoothAdapterService( 1215): Starting service com.android.bluetooth.hid.HidService
,E/BluetoothAdapterService( 1215): File transfer profiels supported!!
,W/BluetoothAdapterService( 1215): Starting service com.android.bluetooth.hdp.HealthService
,E/BluetoothAdapterService( 1215): File transfer profiels supported!!
,W/BluetoothAdapterService( 1215): Starting service com.android.bluetooth.pan.PanService
,I/LGBluetoothHeadsetServiceJni( 1215): classInitNative: succeeds
,D/LGBluetoothHfpAdapter( 1215): Version 1.5
,I/bluedroid( 1215): get_profile_interface handsfree
,E/BluetoothAdapterService( 1215): File transfer profiels supported!!
,W/BluetoothAdapterService( 1215): Starting service com.android.bluetooth.map.BluetoothMapService
,E/BluetoothAdapterService( 1215): File transfer profiels supported!!
I/bt-btif ( 1215): btif_hf_get_interface
I/bt-btif ( 1215): init
,D/bt-btif ( 1215): btif_enable_service: current services:0x40
,W/BluetoothAdapterService( 1215): Starting service com.android.bluetooth.gatt.GattService
V/AudioPolicyService(  270): getOutput()
V/AudioPolicyManagerBase(  270): getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
V/AudioPolicyManagerBase(  270): getOutput() returns output 2
,V/AudioSystem( 1215): getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,V/AudioFlinger(  270): registerClient() client 0xb7cdede0, pid 1215
V/AudioFlinger(  270): sendIoConfigEvent() num events 1 event 0, param 0
V/AudioFlinger(  270): thread 0xb2705008 type 0 TID 918 waking up
,V/AudioFlinger(  270): sendIoConfigEvent() num events 1 event 0, param 0
V/AudioFlinger(  270): acquireWakeLock_l() AudioOut_2 status 0
V/AudioFlinger(  270): processConfigEvents() remaining events 1
V/AudioFlinger(  270): thread 0xb2594008 type 0 TID 1000 waking up
V/AudioFlinger(  270): PlaybackThread::audioConfigChanged_l, thread 0xb2705008, event 0, param 0
V/AudioSystem(  270): ioConfigChanged() event 0, ioHandle 2
,V/AudioSystem(  270): ioConfigChanged() opening already existing output! 2
V/AudioFlinger(  270): acquireWakeLock_l() AudioOut_3 status 0
V/AudioFlinger(  270): processConfigEvents() remaining events 1
V/AudioFlinger(  270): PlaybackThread::audioConfigChanged_l, thread 0xb2594008, event 0, param 0
V/AudioFlinger(  270): acquireWakeLock_l() AudioOut_2 status 0
V/AudioSystem(  962): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem(  270): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem(  962): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  270): ioConfigChanged() opening already existing output! 3
V/AudioSystem( 1215): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1601): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1601): ioConfigChanged() opening already existing output! 2
V/AudioSystem(  962): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem(  962): ioConfigChanged() opening already existing output! 3
,V/AudioSystem( 1448): ioConfigChanged() event 0, ioHandle 2
V/AudioSystem( 1448): ioConfigChanged() opening already existing output! 2
V/AudioSystem( 1448): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1448): ioConfigChanged() opening already existing output! 3
V/AudioSystem( 1215): ioConfigChanged() new output samplingRate 48000, format 1 channel mask 0x3 frameCount 960 latency 160
V/AudioFlinger(  270): acquireWakeLock_l() AudioOut_3 status 0
V/AudioSystem( 1601): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1601): ioConfigChanged() opening already existing output! 3
V/AudioSystem( 1215): ioConfigChanged() event 0, ioHandle 3
V/AudioSystem( 1215): ioConfigChanged() new output samplingRate 48000, format 1 channel mask 0x3 frameCount 960 latency 50
,V/AudioSystem( 1215): getSamplingRate() streamType 8, output 2, sampling rate 48000
,V/AudioTrack( 1215): sampleRate 0, channelMask 0x1, format 1
,E/BluetoothAdapterService( 1215): File transfer profiels supported!!
V/AudioTrack( 1215): streamType 8
V/AudioTrack( 1215): set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
V/AudioPolicyService(  270): checkPlayCondition().. streamType = 8
V/AudioPolicyManagerBase(  270): checkPlayCondition()... stream = 8, bResult = 0
V/AudioTrack( 1215): set() checkPlaycondition!!!! streamType 8 return NO_INIT.
,D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4287b2a0
,D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4287b2a0
,D/LGBluetoothXmlHandler( 2521): dvice configuraion start
,D/HeadsetStateMachine( 1215): Enter Disconnected: -2
D/HeadsetPhoneState( 1215): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1215): [BTUI] listenForMultiSimPhoneState : start = false
,D/HeadsetStateMachine( 1215): [BTUI] change sampling rate to 8000 when device is disconnected
,E/AudioSystem( 1215): AudioSystem::setParameters()...keyValue bt_samplerate=8000
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 1215
V/SRS_Proc(  270): ParamSet string: bt_samplerate=8000
D/audio_hw_primary(  270): adev_set_parameters: enter: bt_samplerate=8000
V/voice   (  270): voice_set_parameters: enter: bt_samplerate=8000
V/voice   (  270): voice_set_parameters: exit with code(-2)
,V/msm8974_platform(  270): platform_set_parameters: enter: bt_samplerate=8000
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
,W/BluetoothAdapterService( 1215): Starting service com.broadcom.bt.service.sap.SapService
,D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
,D/BluetoothA2dp(  962): Proxy object connected
,D/A2dpService( 1215): Received start request. Starting profile...
I/BluetoothA2dpServiceJni( 1215): classInitNative: succeeds
,D/A2dpStateMachine( 1215): make
,E/BluetoothAdapterService( 1215): File transfer profiels supported!!
,W/BluetoothAdapterService( 1215): Starting service com.broadcom.bt.service.ftp.FTPService
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.542847 Y: -0.389786 Z: 9.740005 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.542847 .y:-0.389786 .z:9.740005
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
D/dalvikvm( 1215): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/bluedroid( 1215): get_profile_interface a2dp
I/bt-btif ( 1215): btif_av_get_interface
I/bt-btif ( 1215): init
I/bt-btif ( 1215): ## A2DP START MEDIA TASK ##
I/GKI_LINUX( 1215): gki_task_entry: gki_task_entry task_id=2 [A2DP-MEDIA] starting
D/bt-btif ( 1215): UIPC_Init
I/bt-btif ( 1215): ### uipc_main_init ###
I/BluetoothAdapterState( 1215): Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
D/bt-btif ( 1215): UIPC_Open : ch_id 0, p_cback 60ae6b25
I/bt-btif ( 1215): SETUP CHANNEL SERVER 0
I/bt-btif ( 1215): create_server_socket /data/misc/bluedroid/.a2dp_ctrl
I/bt-btif ( 1215): created socket fd 69
I/bt-btif ( 1215): ADD SERVER FD TO ACTIVE SET 69
I/bt-btif ( 1215): UIPC SEND WAKE UP
I/ConfigService( 1548): onDestroy
D/LGBluetoothXmlHandler( 2521): startDocument!
D/LGBluetoothXmlHandler( 2521): startElement - elet = Device
D/LGBluetoothXmlHandler( 2521): startElement - elet = OLDHELP
D/LGBluetoothXmlHandler( 2521): startElement - elet = OLDHELP
D/LGBluetoothXmlHandler( 2521): startElement - elet = OPPDIRECTORYBLUETOOTH
D/LGBluetoothXmlHandler( 2521): startElement - elet = OPP_DIRECTORY_BLUETOOTH
,D/LGBluetoothXmlHandler( 2521): endDocument!
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/bt-btif ( 1215): ## A2DP MEDIA TASK STARTED ##
E/bt-btif ( 1215): warning : media task started media_task_refcnt 1 
D/bt-btif ( 1215): btif_enable_service: current services:0x48
D/bt-btif ( 1215): btif_av_state_idle_handler event:BTIF_SM_ENTER_EVT flags 0
I/bt-btif ( 1215): ## ON A2DP IDLE ##
D/bt-btif ( 1215): UIPC_Close : ch_id 1
I/bt-btif ( 1215): CHANNEL 1 ALREADY CLOSED
I/LGBluetoothA2dpServiceJni( 1215): classInitNative: succeeds
I/LGBluetoothA2dpAdapter( 1215): [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
I/BluetoothAVRCP1.3ServiceJni( 1215): classInitNativeAVRCP
V/Avrcp   ( 1215): make
D/A2dpStateMachine( 1215): Enter Disconnected: -2
D/LGBluetoothAvrcpManager( 1215): [BTUI] initAvcrpManager
D/LGBluetoothAvrcpManager( 1215): [BTUI] initPlayStatus() : isMusicActive = false
D/LGBluetoothAvrcpAdapter( 1215): [BTUI] Use LG AVRCP : init jni
I/BluetoothAVRCP1.3ServiceJni( 1215): initNativeAVRCP
I/bluedroid( 1215): get_profile_interface avrcp
I/bt-btif ( 1215): btif_rc_get_interface
I/bt-btif ( 1215): ## init ##
D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4287b2a0
I/BluetoothHidServiceJni( 1215): classInitNative: succeeds
D/HidService( 1215): Received start request. Starting profile...
I/bluedroid( 1215): get_profile_interface hidhost
I/bt-btif ( 1215): btif_hh_get_interface
I/bt-btif ( 1215): init
D/bt-btif ( 1215): btif_enable_service: current services:0x100048
D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4287b2a0
I/BluetoothHealthServiceJni( 1215): classInitNative: succeeds
D/HealthService( 1215): Received start request. Starting profile...
I/bluedroid( 1215): get_profile_interface health
I/bt-btif ( 1215): btif_hl_get_interface
I/bt-btif ( 1215): init
D/bt-btif ( 1215): Process name (droid.bluetooth)
D/bt-btif ( 1215): btif_hl_soc_thread_init
D/bt-btif ( 1215): create_thread: entered
D/bt-btif ( 1215): create_thread: thread created successfully
D/bt-btif ( 1215): entered btif_hl_select_thread
D/bt-btif ( 1215): btif_hl_select_wakeup_init
I/LGBluetoothHealthServiceJni( 1215): classInitNative: succeeds
D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4287b2a0
D/bt-btif ( 1215): btif_hl_select_wakeup_init signal_fds[0]=79 signal_fds[1]=80
D/bt-btif ( 1215): max_s=79 
D/bt-btif ( 1215): set curr_set = org_set 
I/BluetoothPanServiceJni( 1215): classInitNative(L105): succeeds
D/BluetoothPan(  962): BluetoothPAN Proxy object connected
D/PanService( 1215): Received start request. Starting profile...
D/BluetoothPanServiceJni( 1215): initializeNative(L110): pan
I/bluedroid( 1215): get_profile_interface pan
D/bt-btif ( 1215): stack_initialized = 0, btpan_cb.enabled:0
D/BluetoothTethering(  962): got CMD_CHANNEL_HALF_CONNECTED
D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4287b2a0
D/HeadsetStateMachine( 1215): Proxy object connected
D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4287b2a0
I/LGBluetoothMapAdapter( 1215): [BTUI] getInstance : create [LGBluetoothMapAdapter]
V/BluetoothMapService( 1215): BluetoothMapBinder()
D/BluetoothMapService( 1215): Received start request. Starting profile...
D/BluetoothMapService( 1215): start()
D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4287b2a0
I/BtGatt.JNI( 1215): classInitNative(L685): classInitNative: Success!
D/BtGatt.DebugUtils( 1215): handleDebugAction() action=null
D/BtGatt.GattService( 1215): Received start request. Starting profile...
D/BtGatt.GattService( 1215): start()
I/bluedroid( 1215): get_profile_interface gatt
,D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4287b2a0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
D/BluetoothAdapterService(1116189344)( 1215): Message: 1
D/BluetoothAdapterService(1116189344)( 1215): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1215): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.hfp.BrcmHeadsetService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1215): Profile still not running:com.broadcom.bt.service.sap.SapService
D/HeadsetStateMachine( 1215): Disconnected process message: 10
D/HeadsetPhoneState( 1215): sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
D/HeadsetStateMachine( 1215): Disconnected process message: 11
I/BluetoothSAPServiceJni( 1215): classInitNative(L170): succeeds
D/SapService( 1215): Received start request. Starting profile...
D/BluetoothSAPServiceJni( 1215): initializeNative(L175): sap
I/bluedroid( 1215): get_profile_interface sap
I/bt-btif ( 1215): btif_sc_get_interface
I/bt-btif ( 1215): init
D/bt-btif ( 1215): btif_enable_service: current services:0x120048
I/LGBluetoothSapAdapter( 1215): [BTUI] getInstance : create [LGBluetoothSapAdapter]
I/LGBluetoothSapAdapter( 1215): [BTUI] Create LGBluetoothSapManager Instance
D/LGBluetoothSapManager( 1215): [BTUI] initSapManager
D/LgeBluetoothSimManager( 1448): [BTUI] SAP_ENABLE_EVT
D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4287b2a0
V/BluetoothFTPServiceJni( 1215): classInitNative
,I/BluetoothFTPServiceJni( 1215): classInitNative(L271): succeeds
D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4287b2a0
,D/BluetoothFTPService( 1215): BluetoothFtpBinder()
D/**BluetoothFTPService( 1215): Received start request. Starting profile...
,V/BluetoothFTPService( 1215): FTP-Server Service start
D/BluetoothFTPServiceJni( 1215): initFtpNativeDataNative(L275): FTP
I/bluedroid( 1215): get_profile_interface ftp
I/bt-btif ( 1215): btif_fts_get_interface
I/bt-btif ( 1215): init
,D/bt-btif ( 1215): btif_enable_service: current services:0x120148
D/BluetoothFTPServiceJni( 1215): initFtpNativeDataNative(L317): FTP init done
D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4287b2a0
,V/BluetoothPbapReceiver( 1215): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1215): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 1215): ***********state = 11
D/BluetoothAdapterService(1116189344)( 1215): Message: 1
,D/BluetoothAdapterService(1116189344)( 1215): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1215): onProfileServiceStateChange: serviceName=com.android.bluetooth.a2dp.A2dpService, state = 12, doUpdate = true
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BluetoothAdapterService( 1215): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116189344)( 1215): Message: 1
D/BluetoothAdapterService(1116189344)( 1215): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1215): onProfileServiceStateChange: serviceName=com.android.bluetooth.hid.HidService, state = 12, doUpdate = true
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/BluetoothPermissionRequest( 2521): onReceive
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/BluetoothAdapterService( 1215): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116189344)( 1215): Message: 1
D/BluetoothAdapterService(1116189344)( 1215): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
,D/BluetoothAdapterService( 1215): onProfileServiceStateChange: serviceName=com.android.bluetooth.hdp.HealthService, state = 12, doUpdate = true
,D/BluetoothManagerService(  962): Message: 20
,D/BluetoothManagerService(  962): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4481f870:true
,D/WifiController(  962): battery changed pluggedType: 2
D/BluetoothAdapterService( 1215): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116189344)( 1215): Message: 1
D/BluetoothAdapterService(1116189344)( 1215): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1215): onProfileServiceStateChange: serviceName=com.android.bluetooth.pan.PanService, state = 12, doUpdate = true
D/LGBluetoothResetSettingReceiver( 2521): [BTUI] Loading JNI Library
D/BluetoothAdapterService( 1215): Profile still not running:com.broadcom.bt.service.sap.SapService
V/BluetoothMapService( 1215): Handler(): got msg=1
E/BluetoothSettings_JNI( 2521): [BTUI] JNI_OnLoad : ### LGBT_USE_BDT : TRUE ###
D/BluetoothAdapterService(1116189344)( 1215): Message: 1
D/BluetoothAdapterService(1116189344)( 1215): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1215): onProfileServiceStateChange: serviceName=com.android.bluetooth.map.BluetoothMapService, state = 12, doUpdate = true
D/LGBluetoothResetSettingReceiver( 2521): return without doing reset settings.
D/BluetoothAdapterService( 1215): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116189344)( 1215): Message: 1
D/BluetoothAdapterService(1116189344)( 1215): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1215): onProfileServiceStateChange: serviceName=com.android.bluetooth.gatt.GattService, state = 12, doUpdate = true
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.547775 Y: -0.381226 Z: 9.753830 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.547775 .y:-0.381226 .z:9.753830
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
D/BluetoothAdapterService( 1215): Profile still not running:com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1116189344)( 1215): Message: 1
D/BluetoothAdapterService(1116189344)( 1215): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1215): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.sap.SapService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1215): Profile still not running:com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterService(1116189344)( 1215): Message: 1
D/BluetoothAdapterService(1116189344)( 1215): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1215): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.ftp.FTPService, state = 12, doUpdate = true
D/BluetoothAdapterService( 1215): All profile services started.
D/BluetoothAdapterState( 1215): CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
I/bluedroid( 1215): enable 1
I/bt-btif ( 1215): BTIF ENABLE BLUETOOTH :: current btif_core_radio_refcount: 0, btif_core_state: 0, btif_core_cb.dut_mode: 0
E/bt-btu  ( 1215): VERSION G2-AFBT-440-21_MI_00.02_OPP10 (BTE: BCM1200_PI_10.3.20.55)
D/HeadsetStateMachine( 1215): Disconnected process message: 10
I/bt_hci_bdroid( 1215): init
I/bt_vendor( 1215): init
I/bt_vnd_conf( 1215): Attempt to load conf from /etc/bluetooth/bt_vendor.conf
I/bt_vnd_conf( 1215): vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
I/bt-btif ( 1215): libbt-hci init returns 0
I/bt_hci_bdroid( 1215): bt_hc_worker_thread started
I/GKI_LINUX( 1215): gki_task_entry: gki_task_entry task_id=0 [BTU] starting
,I/ActivityManager(  962): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4160 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/HyLog   ( 4160): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4160): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4160): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/AuthorizationBluetoothService( 1548): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  962): Killing 3298:com.google.android.music:main/u0a107 (adj 15): empty #17
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:rfkill, action:3
,F/ActivityManager(  962): Service ServiceRecord{4303f4d0 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{43285838 3298:com.google.android.music:main/u0a107} not same as in map: null
,F/ActivityManager(  962): Service ServiceRecord{42b58a50 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{43285838 3298:com.google.android.music:main/u0a107} not same as in map: null
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{4306a0a0 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{44d3e170 u0 com.test.thalitest/.MainActivity t3}
,I/bt_userial_vendor( 1215): userial vendor open: opening /dev/ttyHS99
D/bt_userial_vendor( 1215): userial_vendor_open():UART is setup
,I/bt_userial_vendor( 1215): device fd = 84 open
,D/bt_hwcfg( 1215): Chipset BCM4335A0
,D/bt_hwcfg( 1215): Target name = [BCM4335A0]
D/bt_hwcfg( 1215): Target name = [BCM4335]
I/bt_hwcfg( 1215): Found patchfile: /system/bin//BCM4335B0_002.001.006.0191.0201_ORC.hcd
,I/bt_hwcfg( 1215): Applying 4335 AXI BRIDGE patch...
,I/bt_hwcfg( 1215): bt vendor lib: set UART baud 4000000
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  962): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1215): Disconnected process message: 10
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1215): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
D/WifiController(  962): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/bt_hwcfg( 1215): Releasing 4335 AXI BRIDGE lock
,I/bt_hwcfg( 1215): bt vendor lib: set UART baud 115200
,D/bt_hwcfg( 1215): Settlement delay -- 100 ms
,I/bt_hwcfg( 1215): bt vendor lib: set UART baud 4000000
,I/bt_hwcfg( 1215): Setting local bd addr to 34:FC:EF:9D:93:0B
,I/bt_hwcfg( 1215): vendor lib fwcfg completed
,I/bt-btif ( 1215): HC preload_cb 0 [0:SUCCESS 1:FAIL]
I/        ( 1215): BTE_InitTraceLevels -- TRC_HCI
I/        ( 1215): BTE_InitTraceLevels -- TRC_L2CAP
,I/        ( 1215): BTE_InitTraceLevels -- TRC_RFCOMM
I/        ( 1215): BTE_InitTraceLevels -- TRC_OBEX
I/        ( 1215): BTE_InitTraceLevels -- TRC_AVDT
I/        ( 1215): BTE_InitTraceLevels -- TRC_AVRC
I/        ( 1215): BTE_InitTraceLevels -- TRC_A2D
I/        ( 1215): BTE_InitTraceLevels -- TRC_BNEP
I/        ( 1215): BTE_InitTraceLevels -- TRC_BTM
I/        ( 1215): BTE_InitTraceLevels -- TRC_GAP
I/        ( 1215): BTE_InitTraceLevels -- TRC_PAN
I/        ( 1215): BTE_InitTraceLevels -- TRC_SAP
I/        ( 1215): BTE_InitTraceLevels -- TRC_SDP
,I/        ( 1215): BTE_InitTraceLevels -- TRC_GATT
I/        ( 1215): BTE_InitTraceLevels -- TRC_SMP
I/        ( 1215): BTE_InitTraceLevels -- TRC_BTAPP
I/        ( 1215): BTE_InitTraceLevels -- TRC_BTIF
I/        ( 1215): BTE_InitTraceLevels -- TRC_PROTOCOL
D/bt-btif ( 1215): btif_task(): received trigger stack init event, state: 1, radio_ref_count: 1, is_radio_req 0, dut_mode: 0
,D/bt-btif ( 1215): btif_dm_load_ble_local_keys BLE ER key loaded
D/bt-btif ( 1215): btif_dm_load_ble_local_keys BLE ID keys loaded
I/bt-btif ( 1215): bta_dm_sm_execute event:0x0
I/bt-btif ( 1215): bta_sys_sm_execute state:0, event:0x0
I/bt-btif ( 1215): bta_sys_hw_api_enable for 0, active modules 0x0001
I/bt-btif ( 1215): bta_sys_sm_execute state:1, event:0x1
,I/bt-btif ( 1215): bta_sys_hw_evt_enabled for 0
,D/bt-btif ( 1215):  bta_sys_hw_btm_cback was called with parameter: 0
,I/bt-btif ( 1215): bta_sys_sm_execute state:1, event:0x2
D/bt-btif ( 1215):  bta_sys_hw_evt_stack_enabled!notify the callers
D/bt-btif ( 1215):  bta_dm_sys_hw_cback with event: 1
D/bt-btif ( 1215): ##################################
D/bt-btif ( 1215): bta_dm_co_ble_load_local_keys:  Load local keys if any are persisted
D/bt-btif ( 1215): ##################################
D/bt-btif ( 1215): btif_dm_get_ble_local_keys  *p_key_mask=0x03
E/bt-btm  ( 1215): BTM_SecRegister:p_cb_info->p_le_callback == 0x60b3b4c5 
I/bt-smp  ( 1215): SMP_Register state=0
,E/bt-btm  ( 1215): BTM_SecRegister: btm_cb.api.p_le_callback = 0x60b3b4c5 
D/bt-btif ( 1215): bta_gattc_register state 0
D/bt-btif ( 1215): bta_gattc_enable
I/bt-att  ( 1215): GATT_Register
D/bt-att  ( 1215): UUID=[0x87878787878787878787878787878787]
I/bt-att  ( 1215): allocated gatt_if=3
D/bt-btif ( 1215): bta_dm_gattc_callback event = 0
D/bt-btif ( 1215): BTA_GATTC_REG_EVT client_if = 3
,I/bt-att  ( 1215): GATT_StartIf gatt_if=3
D/bt-att  ( 1215): gatt_find_the_connected_bda start_idx=0
,D/bt-att  ( 1215): gatt_find_the_connected_bda found=0 found_idx=7
,I/bt-btif ( 1215): btif_dm_upstreams_cback  ev: BTA_DM_ENABLE_EVT
,D/bt-btif ( 1215): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1215): in, bd addr:, prop type:1, len:249
I/bt-btif ( 1215): bta_dm_sm_execute event:0x2
D/bt-btif ( 1215): BTA is generating EIR
D/bt-sdp  ( 1215): SDP_CreateRecord ok, num_records:3
,I/bt-btif ( 1215): Adding UUID=0x110C into EIR
D/bt-btif ( 1215): BTA is generating EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00001000
D/bt-btif ( 1215): nsc_mask: 0x6
D/bt-btif ( 1215): bta_av_co_audio_init
D/bt-btif ( 1215): bta_av_co_audio_init: 0
D/bt-btif ( 1215): audio[0] av_handle: 1 codec_type: 0
D/bt-btif ( 1215): bta_av_co_audio_init
D/bt-btif ( 1215): bta_av_co_audio_init: 1
,D/bt-btif ( 1215): BTIF_APTX_CODEC_ID:6
D/bt-btif ( 1215): audio[1] av_handle: 2 codec_type: 255
D/bt-sdp  ( 1215): SDP_CreateRecord ok, num_records:4
I/bt-a2d  ( 1215): A2D_AddRecord uuid: 110a
I/bt-btif ( 1215): Adding UUID=0x110A into EIR
D/bt-btif ( 1215): BTA is generating EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00001400
D/bt-btif ( 1215): rc_acp_handle:0 idx:1
,D/bt-btif ( 1215): create 0, role: 1, shdl:0, rc_handle:0, lidx:3, status:0x10
D/bt-btif ( 1215): reg_audio: 0x1
D/bt-btif ( 1215): bta_ag_scb_alloc 1
I/bt-btif ( 1215): AG evt (hdl 0x0001): State 0, Event 0x0500
D/bt-sdp  ( 1215): SDP_CreateRecord ok, num_records:5
,D/bt-btif ( 1215): bta_ag_add_record uuid: 1112
I/bt-btif ( 1215): Adding UUID=0x1112 into EIR
D/bt-btif ( 1215): BTA is generating EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000000 00011400
D/bt-sdp  ( 1215): SDP_CreateRecord ok, num_records:6
D/bt-btif ( 1215): bta_ag_add_record uuid: 111f
I/bt-btif ( 1215): Adding UUID=0x111F into EIR
D/bt-btif ( 1215): BTA is generating EIR
,I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000000 04011400
D/bt-btif ( 1215): getAccess buffer->st_uid:1000 buffer->st_gid:1028
D/bt-btif ( 1215): bta_fts_api_enable srm:1
D/bt-sdp  ( 1215): SDP_CreateRecord ok, num_records:7
,I/bt-btif ( 1215): Adding UUID=0x1106 into EIR
D/bt-btif ( 1215): BTA is generating EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000000 04011440
D/bt-btif ( 1215): FTS:  SDP Registered (handle 0x00010006)
I/bt-btif ( 1215): bta_fts_ci_resume status:1
I/bt-btif ( 1215): FTP SERVER enabled with Root Path [/storage]
D/bt-sdp  ( 1215): SDP_CreateRecord ok, num_records:8
,I/bt-btif ( 1215): Adding UUID=0x112D into EIR
D/bt-btif ( 1215): BTA is generating EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04011440
D/bt-btif ( 1215): bte_sap_evt: event=0
,E/bt-btif ( 1215): Calling BTA_HhEnable
D/bt-btif ( 1215): bta_gattc_register state 2
I/bt-att  ( 1215): GATT_Register
D/bt-att  ( 1215): UUID=[0x0000454c205245564f20484820415442]
I/bt-att  ( 1215): allocated gatt_if=4
D/bt-btif ( 1215): bta_hh_gattc_callback event = 0
I/bt-att  ( 1215): GATT_StartIf gatt_if=4
,D/bt-att  ( 1215): gatt_find_the_connected_bda start_idx=0
D/bt-att  ( 1215): gatt_find_the_connected_bda found=0 found_idx=7
D/bt-btif ( 1215): in add:1
D/bt-btif ( 1215): Remote device:00:f4:6f:30:e0:6c, size:18
D/bt-btif ( 1215): Remote device:f8:95:c7:87:3c:51, size:18
,D/bt-btif ( 1215): Remote device:e0:db:10:1f:c9:5e, size:18
D/bt-btif ( 1215): Remote device:b0:c5:59:3f:75:69, size:18
D/bt-btif ( 1215): Remote device:14:b4:84:21:3b:49, size:18
D/bt-btif ( 1215): Remote device:80:01:84:8a:b3:68, size:18
D/bt-btif ( 1215): Remote device:58:3f:54:73:64:c0, size:18
,I/bt-btif ( 1215): bta_dm_sm_execute event:0x9
D/bt-btif ( 1215): Remote device:10:d3:8a:fb:85:d4, size:18
D/bt-btif ( 1215): Remote device:b4:ce:f6:ab:a4:6a, size:18
D/bt-btif ( 1215): Remote device:08:ec:a9:50:75:41, size:18
D/bt-btif ( 1215): Remote device:f8:cf:c5:d9:e5:61, size:18
D/bt-btif ( 1215): Remote device:08:ec:a9:50:76:27, size:18
D/bt-btif ( 1215): Remote device:7c:f9:0e:51:18:22, size:18
D/bt-btif ( 1215): Remote device:44:80:eb:7b:5a:05, size:18
,D/bt-btif ( 1215): Remote device:50:2e:6c:ac:21:50, size:18
D/bt-btif ( 1215): Remote device:7c:f9:0e:37:96:ab, size:18
D/bt-btif ( 1215): Remote device:f4:f1:e1:5c:3b:e2, size:18
D/bt-btif ( 1215): Remote device:34:fc:ef:11:ae:67, size:18
,D/bt-btif ( 1215): Remote device:f8:95:c7:87:85:54, size:18
D/bt-btif ( 1215): Remote device:7c:f9:0e:34:8a:a0, size:18
D/bt-btif ( 1215): Remote device:e0:db:10:14:e2:c0, size:18
D/bt-btif ( 1215): Remote device:34:fc:ef:11:b1:66, size:18
D/bt-btif ( 1215): Remote device:90:e7:c4:f6:69:77, size:18
D/bt-btif ( 1215): Remote device:90:e7:c4:3c:62:6a, size:18
D/bt-btif ( 1215): Remote device:58:2a:f7:ed:96:be, size:18
,D/bt-btif ( 1215): Remote device:, size:128
E/bt-btif ( 1215): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
E/bt-btif ( 1215): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
D/bt-btif ( 1215): out
D/bt-btif ( 1215): btif_storage_get_adapter_property property->type:2 
,D/bt-btif ( 1215): btif_storage_get_adapter_property property->type:1 
D/bt-btif ( 1215): in, bd addr:, prop type:1, len:249
I/bt-btif ( 1215): btif_storage_load_bonded_devices  BT_PROPERTY_DEVICE_MODE
D/bt-btif ( 1215): btif_storage_get_adapter_property property->type:16 
D/bt-btif ( 1215): in, bd addr:, prop type:16, len:4
E/bt-btif ( 1215): Unknow prop type:16
I/bt-btif ( 1215): btif_dm_get_adapter_property: type=0x10
,D/bt-btif ( 1215): btif_dm_get_adapter_property btif_device_mode 0
D/bt-btif ( 1215): btif_storage_get_adapter_property property->type:9 
D/bt-btif ( 1215): in, bd addr:, prop type:9, len:4
D/bt-btif ( 1215): btif_storage_get_adapter_property property->type:3 
E/bt-btif ( 1215): btif_storage_get_adapter_property service_mask:0x120148
D/bt-btif ( 1215): btif_storage_get_adapter_property property->type:3 devicemode 0
,D/bt-btif ( 1215): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1215): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1215): btif_storage_get_adapter_property property->type:3 devicemode 0
D/bt-btif ( 1215): btif_storage_get_adapter_property property->type:3 devicemode 0
,I/bt-btif ( 1215): HAL bt_hal_cbacks->adapter_properties_cb
,D/BluetoothManagerService(  962): Bluetooth Adapter name changed to Thali Test's G2
,D/BluetoothManagerService(  962): Stored Bluetooth name: Thali Test's G2
,E/BluetoothAdapterProperties( 1215): Property change not handled in Java land:16
,I/bt-btif ( 1215): btif_storage_load_bonded_devices: 1 bonded devices found
D/bt-btif ( 1215): in, bd addr:58:3f:54:73:64:c0, prop type:1, len:249
D/bt-btif ( 1215): in, bd addr:58:3f:54:73:64:c0, prop type:10, len:249
D/bt-btif ( 1215): in, bd addr:58:3f:54:73:64:c0, prop type:4, len:4
D/bt-btif ( 1215): in, bd addr:58:3f:54:73:64:c0, prop type:5, len:4
D/bt-btif ( 1215): in, bd addr:58:3f:54:73:64:c0, prop type:3, len:512
,I/bt-btif ( 1215): HAL bt_hal_cbacks->remote_device_properties_cb
,E/BluetoothRemoteDevices( 1215): devicePropertyChangedCallback: bdDevice: 58:3F:54:73:64:C0, value is empty for type: 10
,I/LGRemoteDevicePropertySetting( 1215): [BTUI] remoteDeviceSetProperties
,I/LGRemoteDevicePropertySetting( 1215): [BTUI] Get BRCM HeadsetService
,D/bt-btif ( 1215): btif_enable_bluetooth_evt: status 0, local bd [34:fc:ef:9d:93:0b]
E/bt_hwcfg( 1215): hw_sco_config...
,E/bt_hwcfg( 1215): SCO PCM configure {0, 4, 0, 0, 0}
I/bt-btif ( 1215): HC lib lpm enable=1 return 0
,I/bt-btif ( 1215): BTA_BrcmInit
E/bt-gki  ( 1215): ### ERROR: incorrect Process context BTIF called function btu_start_timer() ###
D/IOP_DB_BT( 1215): db_open: file /etc/bluetooth/iop_bt.db
,I/bt-btif ( 1215): HC lpm_result_cb 1
,D/IOP_DB_BT( 1215): db_open: db_open : handle 1623362092l, read 7547 bytes onto local cache
D/IOP_DB_BT( 1215): db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
D/IOP_DB_BT( 1215): db_query: result 1
I/        ( 1215): iop_db_open: iop_db_open status 0
D/bt-btif ( 1215): btsock initializing...
D/bt-btif ( 1215): in initialized:1
D/bt-btif ( 1215): ts[7].used:1
,D/bt-btif ( 1215): ts[6].used:0
D/bt-btif ( 1215): alloc_thread_slot ret:6
D/bt-btif ( 1215): h:6, cmd_fdr:87, cmd_fdw:88
D/bt-btif ( 1215): h:6, thread id:1626515752
I/bt-btif ( 1215): BTA_JvEnable
D/bt-btif ( 1215): jv_dm_cback: event:0, slot id:0
D/bt-btif ( 1215): unhandled event:0, slot id:0
,D/bt-btif ( 1215): btsock successfully initialized
D/bt-btif ( 1215): jni_initialized = 1, btpan_cb.enabled:0
D/bt-btif ( 1215): Enabling PAN....
I/bt-btif ( 1215): bta_pan_co_init
D/bt-btif ( 1215): local_role:3
D/bt-btif ( 1215): btpan_role:0x3
,D/bt-sdp  ( 1215): SDP_CreateRecord ok, num_records:9
I/bt-btif ( 1215): Adding UUID=0x1116 into EIR
D/bt-btif ( 1215): BTA is generating EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04051440
I/bt-btif ( 1215): Adding UUID=0x1115 into EIR
D/bt-btif ( 1215): BTA is generating EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1215): Adding UUID=0x1116 into EIR
,D/bt-btif ( 1215): BTA is generating EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1215): Removing UUID=0x1117 from EIR
D/bt-btif ( 1215): BTA is generating EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
I/bt-btif ( 1215): Adding UUID=0x1115 into EIR
D/bt-btif ( 1215): BTA is generating EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000004 04071440
,I/bte_conf( 1215): Attempt to load did conf from /etc/bluetooth/bt_did.conf
I/bte_conf( 1215): [1] primary_record=1 vendor_id=0x00C4 vendor_id_source=0x0001 product_id=0x13A1 version=0x1000
,I/bt-btif ( 1215): bta_dm_sm_execute event:0x31
D/bt-sdp  ( 1215): SDP_CreateRecord ok, num_records:10
I/bt-btif ( 1215): Adding UUID=0x1200 into EIR
D/bt-btif ( 1215): BTA is generating EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000084 04071440
I/bt-btif ( 1215): bte did registered::handle: 0x10009, bta status: 0 (0==OK)
I/bte_conf( 1215): Attempt to load did conf from /etc/bluetooth/bt_did.conf
,I/bte_conf( 1215): Attempt to load did conf from /etc/bluetooth/bt_did.conf
D/bt-btif ( 1215): btif_dm_load_local_oob prop_oob = 3
,I/bt-btif ( 1215): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothServiceJni( 1215): adapter_state_change_callback: Status is: 1
D/bt-btif ( 1215): btif_av_state_idle_handler event:BTA_AV_ENABLE_EVT flags 0
D/BluetoothAdapterState( 1215): CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
D/BluetoothAdapterProperties( 1215): ScanMode =  20
,D/BluetoothAdapterProperties( 1215): State =  11
D/BluetoothAdapterProperties( 1215): mDiscoverableTimeout =  120
I/bt-btif ( 1215): btif_set_adapter_property type: 7, len 4, 0x428de058
I/bt-btif ( 1215): set property scan mode : 1
I/bt-btif ( 1215): bta_dm_sm_execute event:0x3
I/bt-btif ( 1215): btif_in_storage_request_copy_cb
,I/bt-btif ( 1215): btif_set_adapter_property type: 9, len 4, 0x428de0b0
I/bt-btif ( 1215): btif_in_storage_request_copy_cb
I/BluetoothAdapterState( 1215): Bluetooth adapter state changed: 11-> 12
D/bt-btif ( 1215): btif_av_state_idle_handler event:BTA_AV_REGISTER_EVT flags 0
D/bt-btif ( 1215): btif_av_state_idle_handler devicemode: 0
,D/bt-btif ( 1215): btif_hf_upstreams_evt: event=BTA_AG_ENABLE_EVT
D/BluetoothAdapterService( 1215): Broadcasting updateAdapterState() to 1 receivers.
D/bt-btif ( 1215): btif_hf_upstreams_evt: event=BTA_AG_REGISTER_EVT
D/bt-btif ( 1215): btif_fts_upstreams_evt: event=BTA_FTS_ENABLE_EVT
,D/BluetoothManagerService(  962): Message: 60
D/BluetoothManagerService(  962): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
D/BluetoothManagerService(  962): Broadcasting onBluetoothStateChange(true) to 6 receivers.
,D/BluetoothPan(  962): onBluetoothStateChange(on) call bindService
I/bt-btif ( 1215): File Transfer: Enable Complete
I/bt-btif ( 1215): HAL bt_fts_callbacks->operation_cmpl_cb
D/BluetoothFTPServiceJni( 1215): operation_cmpl_callback(L192):  oper:3 status:0
,I/BluetoothFTPService( 1215): onFtpServerEnabled: /storage
V/BluetoothAdapterService( 1215): startPbapService
,D/bt-btif ( 1215): btif_sc_upstreams_evt: event=BTA_SC_ENABLE_EVT
D/bt-btif ( 1215): btif_hh_upstreams_evt: event=BTA_HH_ENABLE_EVT
D/bt-btif ( 1215): btif_hh_upstreams_evt: BTA_HH_ENABLE_EVT: status =0
D/bt-btif ( 1215): btif_hh_upstreams_evt--Loading added devices
D/bt-btif ( 1215): Remote device:00:f4:6f:30:e0:6c, size:18
,D/bt-btif ( 1215): Remote device:f8:95:c7:87:3c:51, size:18
,D/BluetoothHeadset( 1448): onBluetoothStateChange: up=true
D/bt-btif ( 1215): Remote device:e0:db:10:1f:c9:5e, size:18
,D/bt-btif ( 1215): Remote device:b0:c5:59:3f:75:69, size:18
D/bt-btif ( 1215): Remote device:14:b4:84:21:3b:49, size:18
D/bt-btif ( 1215): Remote device:80:01:84:8a:b3:68, size:18
,D/bt-btif ( 1215): Remote device:58:3f:54:73:64:c0, size:18
D/bt-btif ( 1215): Remote device:10:d3:8a:fb:85:d4, size:18
D/bt-btif ( 1215): Remote device:b4:ce:f6:ab:a4:6a, size:18
D/bt-btif ( 1215): Remote device:08:ec:a9:50:75:41, size:18
,D/bt-btif ( 1215): Remote device:f8:cf:c5:d9:e5:61, size:18
D/bt-btif ( 1215): Remote device:08:ec:a9:50:76:27, size:18
D/bt-btif ( 1215): Remote device:7c:f9:0e:51:18:22, size:18
D/bt-btif ( 1215): Remote device:44:80:eb:7b:5a:05, size:18
D/bt-btif ( 1215): Remote device:50:2e:6c:ac:21:50, size:18
,D/bt-btif ( 1215): Remote device:7c:f9:0e:37:96:ab, size:18
D/bt_h4   ( 1215): vendor lib postload completed
I/bt-btif ( 1215): HC postload_cb 0
,D/bt-btif ( 1215): Remote device:f4:f1:e1:5c:3b:e2, size:18
D/bt-btif ( 1215): Remote device:34:fc:ef:11:ae:67, size:18
D/bt-btif ( 1215): Remote device:f8:95:c7:87:85:54, size:18
D/bt-btif ( 1215): Remote device:7c:f9:0e:34:8a:a0, size:18
D/bt-btif ( 1215): Remote device:e0:db:10:14:e2:c0, size:18
,D/bt-btif ( 1215): Remote device:34:fc:ef:11:b1:66, size:18
,W/ContextImpl(  962): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan$1.onBluetoothStateChange:192 com.android.server.BluetoothManagerService.sendBluetoothStateCallback:510 com.android.server.BluetoothManagerService.bluetoothStateChangeHandler:1164 
D/bt-btif ( 1215): Remote device:90:e7:c4:f6:69:77, size:18
D/bt-btif ( 1215): Remote device:90:e7:c4:3c:62:6a, size:18
D/bt-btif ( 1215): Remote device:58:2a:f7:ed:96:be, size:18
D/bt-btif ( 1215): Remote device:, size:18
E/bt-btif ( 1215): ## btif_config_get assert section && *section && key && *key && name && *name && bytes && type failed at line:211 ##
D/bt-btif ( 1215): BTA_PAN_ENABLE_EVT
D/bt-btif ( 1215): bta_pan_role:0x5
D/BluetoothPanServiceJni( 1215): control_state_callback(L61): state:0, local_role:0, ifname:bt-pan
I/bt-btif ( 1215): execute storage request event : 2
I/bt-btif ( 1215): type: 7, len 4, 0x60a9103a
D/bt-btif ( 1215): in, bd addr:, prop type:7, len:4
I/bt-btif ( 1215): HAL bt_hal_cbacks->adapter_properties_cb
I/BluetoothAdapterState( 1215): Entering On State
D/BluetoothHeadset( 1448): onBluetoothStateChange: up=true
I/bt-btif ( 1215): execute storage request event : 2
D/BluetoothA2dp(  962): onBluetoothStateChange: up=true
I/bt-btif ( 1215): type: 9, len 4, 0x60a91086
D/bt-btif ( 1215): in, bd addr:, prop type:9, len:4
D/BluetoothHeadset( 1448): onBluetoothStateChange: up=true
I/bt-btif ( 1215): HAL bt_hal_cbacks->adapter_properties_cb
D/BluetoothHeadset(  962): onBluetoothStateChange: up=true
D/BluetoothManagerService(  962): Bluetooth State Change Intent: 11 -> 12
D/LGBluetoothServiceAdapter( 1215): [BTUI] OnState
D/LGBluetoothServiceAdapter( 1215): [BTUI]         global_name: Thali Test's G2
D/LGBluetoothServiceAdapter( 1215): [BTUI]         local_name: Thali Test's G2
D/BluetoothAdapterService(1116189344)( 1215): Quiet mode Enabled = false
D/BluetoothAdapterService(1116189344)( 1215): Initiate auto connection on BT on...
D/BluetoothAdapterService( 1215): [BTUI] autoConnect() : not allowed
D/LGBluetoothAPIService( 1157): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1157): Message: 1
D/LGBluetoothAPIService( 1157): MESSAGE_BOOT_COMPLETED
D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@4287b2a0
D/BluetoothAdapterService(1116189344)( 1215): Get Bonded Devices being called
V/BluetoothPbapService( 1215): Pbap Service onCreate
V/BluetoothPbapService( 1215): Starting PBAP service
I/LGBluetoothAPIService( 1157): [BTUI] LGBluetoothAPIService Binding Success
D/LGBluetoothPbapAdapter( 1215): [BTUI] getInstance : create
V/BluetoothPbapService( 1215): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1215): state: 12
D/BluetoothManagerService(  962): BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
D/BluetoothManagerService(  962): Message: 40
D/BluetoothManagerService(  962): MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
D/BluetoothMapService( 1215): onReceive
D/BluetoothMapService( 1215): STATE_ON
D/LGBluetoothAPIServer( 1215): [BTUI] onCreate()
D/LGBluetoothAPIServer( 1215): [BTUI] onBind()
D/LGBluetoothAPIService( 1157): [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
D/LGBluetoothAPIService( 1157): Message: 100
D/LGBluetoothAPIService( 1157): MESSAGE_BLUETOOTH_SERVICE_CONNECTED
V/BluetoothPbapService( 1215): Handler(): got msg=1
V/BluetoothPbapService( 1215): Pbap Service startRfcommSocketListener
V/BluetoothMapService( 1215): Handler(): got msg=1
V/BluetoothPbapService( 1215): Pbap Service initSocket
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
D/BluetoothMapService( 1215): Map Service startRfcommSocketListener
W/BluetoothAdapter( 1215): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1215): SO,CK FLAG = 1 ***********************
D/bt-btif ( 1215): btsock_rfc_listen, service_name:OBEX Phonebook Access Server
D/bt-btif ( 1215): BTA_JvCreateRecordByUser:OBEX Phonebook Access Server
I/bt-btif ( 1215): BTA_JvCreateRecordByUser
D/bt-btif ( 1215): jv_dm_cback: event:11, slot id:1
D/bt-btif ( 1215): name:OBEX Phonebook Access Server, scn:19
D/bt-btif ( 1215): add_pbap_sdd:scn 19, service name OBEX Phonebook Access Server
D/bt-sdp  ( 1215): SDP_CreateRecord ok, num_records:11
I/bt-btif ( 1215): Adding UUID=0x112F into EIR
D/bt-btif ( 1215): BTA is generating EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000094 04071440
D/bt-btif ( 1215): PBS:  SDP Registered (handle 0x0001000a)
I/bt-btif ( 1215): BTA_JvRfcommStartServer
D/bt-btif ( 1215): bta_jv_rfcomm_start_server: sec id in use:0, rfc_cb in use:0
D/bt-btif ( 1215): bta_jv_alloc_rfc_cb port_handle:6 handle:0x81
D/LGBluetoothServiceAdapter( 1215): [BTUI] createSocketChannel FD=90 mFd=0
V/BluetoothPbapService( 1215): Succeed to create listening socket 
V/BluetoothPbapService( 1215): Accepting socket connection...
D/BluetoothMapService( 1215): Map Service initSocket
D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
W/BluetoothAdapter( 1215): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1215): SOCK FLAG = 1 ***********************
D/bt-btif ( 1215): btsock_rfc_listen, service_name:MAP SMS/MMS
D/bt-btif ( 1215): BTA_JvCreateRecordByUser:MAP SMS/MMS
I/bt-btif ( 1215): BTA_JvCreateRecordByUser
D/bt-btif ( 1215): jv_dm_cback: event:11, slot id:2
D/bt-btif ( 1215): name:MAP SMS/MMS, scn:6
D/bt-btif ( 1215): add_maps_sdd:scn 6, service name MAP SMS/MMS
D/bt-sdp  ( 1215): SDP_CreateRecord ok, num_records:12
I/bt-btif ( 1215): Adding UUID=0x1132 into EIR
D/bt-btif ( 1215): BTA is generating EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04071440
D/bt-btif ( 1215): MAPSS:  SDP Registered (handle 0x0001000b)
I/bt-btif ( 1215): BTA_JvRfcommStartServer
D/bt-btif ( 1215): bta_jv_rfcomm_start_server: sec id in use:1, rfc_cb in use:1
D/bt-btif ( 1215): bta_jv_alloc_rfc_cb port_handle:7 handle:0x82
D/LGBluetoothServiceAdapter( 1215): [BTUI] createSocketChannel FD=92 mFd=90
V/BluetoothMapService( 1215): Succeed to create listening socket 
D/BluetoothMapService( 1215): Accepting socket connection...
W/ContextImpl( 2521): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:156 com.android.settings.bluetooth.DockEventReceiver.onReceive:123 
V/BluetoothPbapReceiver( 1215): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1215): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1215): ***********state = 12
D/LocalBluetoothProfileManager( 2521): Adding local A2DP profile
D/BluetoothManagerService(  962): Message: 30
D/LocalBluetoothProfileManager( 2521): Adding local HEADSET profile
D/BluetoothManagerService(  962): Message: 30
D/BluetoothManagerService(  962): Message: 30
W/ContextImpl( 2521): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothA2dp.doBind:165 android.bluetooth.BluetoothA2dp.<init>:158 android.bluetooth.BluetoothAdapter.getProfileProxy:1207 
W/ContextImpl( 2521): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothHeadset.doBind:283 android.bluetooth.BluetoothHeadset.<init>:276 android.bluetooth.BluetoothAdapter.getProfileProxy:1204 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BluetoothManagerService(  962): Message: 30
D/LocalBluetoothProfileManager( 2521): Adding local MAP profile
D/BluetoothMap( 2521): Create BluetoothMap proxy object
D/BluetoothManagerService(  962): Message: 30
,D/BluetoothManagerService(  962): Message: 30
W/ContextImpl( 2521): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothInputDevice.doBind:245 android.bluetooth.BluetoothInputDevice.<init>:238 android.bluetooth.BluetoothAdapter.getProfileProxy:1210 
W/ContextImpl( 2521): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPan.doBind:149 android.bluetooth.BluetoothPan.<init>:141 android.bluetooth.BluetoothAdapter.getProfileProxy:1213 
W/ContextImpl( 2521): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothMap.doBind:109 android.bluetooth.BluetoothMap.<init>:102 android.bluetooth.BluetoothAdapter.getProfileProxy:1219 
W/ContextImpl( 2521): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 android.bluetooth.BluetoothPbap.doBind:164 android.bluetooth.BluetoothPbap.<init>:157 com.android.settings.bluetooth.PbapServerProfile.<init>:72 
V/BluetoothPbapService( 1215): Pbap Service onBind
D/LocalBluetoothProfileManager( 2521): LocalBluetoothProfileManager construction complete
D/LGBluetoothUserBindClient( 2521): [BTUI] initUserBindClient
D/DockEventReceiver( 2521): finishStartingService: stopping service
D/BluetoothA2dp( 2521): Proxy object connected
D/A2dpProfile( 2521): Bluetooth service connected
W/ContextImpl( 2521): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1632 android.content.ContextWrapper.bindService:517 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
D/BluetoothHeadset( 2521): Proxy object connected
D/HeadsetProfile( 2521): Bluetooth service connected
D/BluetoothInputDevice( 2521): Proxy object connected
D/HidProfile( 2521): Bluetooth service connected
D/BluetoothPan( 2521): BluetoothPAN Proxy object connected
D/PanProfile( 2521): Bluetooth service connected
D/BluetoothMap( 2521): Proxy object connected
D/MapProfile( 2521): Bluetooth service connected
D/BluetoothMap( 2521): getConnectedDevices()
V/BluetoothMapService( 1215): getConnectedDevices()
D/BluetoothPbap( 2521): Proxy object connected
D/PbapServerProfile( 2521): Bluetooth service connected
D/LGBluetoothUserBindClient( 2521): [BTUI] onServiceConnected
D/BluetoothPermissionRequest( 2521): onReceive
D/LGBluetoothFeatureConfig( 2521): isPrivacyLogsEnabled : true
E/LGBluetoothUtils( 2521): [BTUI] FileNotFoundException: readPropertyjava.io.FileNotFoundException: /data/misc/bluedroid/bluetooth_property.conf: open failed: ENOENT (No such file or directory)
D/LGBluetoothResetSettingReceiver( 2521): return without doing reset settings.
V/BluetoothOppReceiver( 1215): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
I/LGBluetoothOppAdapter( 1215): [BTUI] startOppService()
V/BluetoothOppManager( 1215): restoreApplicationData! falsefalsenullnull
D/LGBluetoothFeatureConfig( 1215): isPrivacyLogsEnabled : true
V/BtOppService( 1215): onCreate
D/LGBluetoothOppAdapter( 1215): [BTUI] getInstance : create [LGBluetoothOppAdapter]
V/BluetoothOppNotification( 1215): send message
,V/BtOppService( 1215): Starting RfcommListener
D/BluetoothOppPreference( 1215): Dumping Names:  
D/BluetoothOppPreference( 1215): {}
D/BluetoothOppPreference( 1215): Dumping Channels:  
,D/BluetoothOppPreference( 1215): {}
,V/BtOppService( 1215): onStartCommand
,V/BtOppService( 1215): pendingUpdate is true keepUpdateThread is false sListenStarted is true
,V/BluetoothOppProvider( 1215): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
,V/BtOppService( 1215): Deleted complete outbound shares, number =  0
,V/BluetoothOppNotification( 1215): new notify threadi!
V/BluetoothOppNotification( 1215): send delay message
V/BtOppService( 1215): Deleted complete inbound failed shares, number = 0
,V/BluetoothOppProvider( 1215): starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
V/BtOppService( 1215): start RfcommListener
,V/BluetoothOppProvider( 1215): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
,V/BluetoothOppProvider( 1215): created cursor android.database.sqlite.SQLiteCursor@4290fa40 on behalf of 
V/BtOppService( 1215): RfcommListener started
V/BtOppRfcommListener( 1215): Starting RFCOMM listener....
V/BtOppService( 1215): ContentObserver received notification
V/BtOppService( 1215): ContentObserver received notification
,D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
V/BluetoothOppProvider( 1215): created cursor android.database.sqlite.SQLiteCursor@4290cd88 on behalf of 
,V/BluetoothOppProvider( 1215): created cursor android.database.sqlite.SQLiteCursor@42911620 on behalf of 
,W/BluetoothAdapter( 1215): getBluetoothService() called with no BluetoothManagerCallback
E/BluetoothServiceJni( 1215): SOCK FLAG = 0 ***********************
D/bt-btif ( 1215): btsock_rfc_listen, service_name:OBEX Object Push
D/bt-btif ( 1215): BTA_JvCreateRecordByUser:OBEX Object Push
I/bt-btif ( 1215): BTA_JvCreateRecordByUser
D/bt-btif ( 1215): jv_dm_cback: event:11, slot id:3
D/bt-btif ( 1215): name:OBEX Object Push, scn:12
,D/bt-btif ( 1215): scn 12, service name OBEX Object Push
D/LGBluetoothServiceAdapter( 1215): [BTUI] createSocketChannel FD=97 mFd=92
D/bt-sdp  ( 1215): SDP_CreateRecord ok, num_records:13
I/bt-btif ( 1215): Adding UUID=0x1105 into EIR
D/bt-btif ( 1215): BTA is generating EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04071460
I/bt-btif ( 1215): BTA_JvRfcommStartServer
D/bt-btif ( 1215): bta_jv_rfcomm_start_server: sec id in use:2, rfc_cb in use:2
D/bt-btif ( 1215): bta_jv_alloc_rfc_cb port_handle:8 handle:0x83
V/BtOppRfcommListener( 1215): Started RFCOMM listener....
I/BtOppRfcommListener( 1215): Accept thread started.
,V/BtOppRfcommListener( 1215): Accepting connection...
V/BtOppService( 1215): pendingUpdate is true keepUpdateThread is false sListenStarted is true
,V/BluetoothOppProvider( 1215): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
D/AuthorizationBluetoothService( 1548): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/AuthorizationBluetoothService( 1548): Proximity feature is not enabled.
V/BluetoothOppProvider( 1215): created cursor android.database.sqlite.SQLiteCursor@42914c58 on behalf of 
,V/BluetoothOppNotification( 1215): update too frequent, put in queue
V/BluetoothOppNotification( 1215): mUpdateCompleteNotification = true
,V/BtOppService( 1215): pendingUpdate is false keepUpdateThread is false sListenStarted is true
,V/BluetoothOppProvider( 1215): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1215): created cursor android.database.sqlite.SQLiteCursor@42917058 on behalf of 
,V/BluetoothOppNotification( 1215): outbound: succ-0  fail-0
,V/BluetoothOppNotification( 1215): outbound notification was removed.
,V/BluetoothOppProvider( 1215): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,V/BluetoothOppProvider( 1215): created cursor android.database.sqlite.SQLiteCursor@42918dd0 on behalf of 
,V/BluetoothOppNotification( 1215): inbound: succ-0  fail-0
,V/BluetoothOppNotification( 1215): inbound notification was removed.
,V/BluetoothOppProvider( 1215): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
,D/dalvikvm(  962): GC_EXPLICIT freed 21929K, 49% free 29364K/56632K, paused 2ms+7ms, total 122ms
,V/BluetoothOppProvider( 1215): created cursor android.database.sqlite.SQLiteCursor@4291a4b8 on behalf of 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
I/jxcore-log( 4080): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4080): 
I/jxcore-log( 4080): my name is : LGE-LG-D802_PT4353
I/jxcore-log( 4080): 
I/jxcore-log( 4080): attempting to connect to test coordinator
I/jxcore-log( 4080): 
I/jxcore-log( 4080): check test folder
I/jxcore-log( 4080): 
I/jxcore-log( 4080): found test : ./testFindPeers.js
I/jxcore-log( 4080): 
I/jxcore-log( 4080): found test : ./testReConnect.js
I/jxcore-log( 4080): 
I/jxcore-log( 4080): found test : ./testSendData.js
I/jxcore-log( 4080): 
I/jxcore-log( 4080): Test app app.js loaded
I/jxcore-log( 4080): 
I/Choreographer( 4080): Skipped 130 frames!  The application may be doing too much work on its main thread.
I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
I/chromium( 4080): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
D/WifiController(  962): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 288 plugged : true isCharging : false
D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1215): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
V/BluetoothOppNotification( 1215): new notify threadi!
V/BluetoothOppNotification( 1215): send delay message
V/BluetoothOppProvider( 1215): starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1215): created cursor android.database.sqlite.SQLiteCursor@4291d020 on behalf of 
V/BluetoothOppNotification( 1215): mUpdateCompleteNotification = true
V/BluetoothOppProvider( 1215): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1215): created cursor android.database.sqlite.SQLiteCursor@4291ec58 on behalf of 
V/BluetoothOppNotification( 1215): outbound: succ-0  fail-0
V/BluetoothOppNotification( 1215): outbound notification was removed.
V/BluetoothOppProvider( 1215): starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
V/BluetoothOppProvider( 1215): created cursor android.database.sqlite.SQLiteCursor@429207e8 on behalf of 
V/BluetoothOppNotification( 1215): inbound: succ-0  fail-0
V/BluetoothOppNotification( 1215): inbound notification was removed.
V/BluetoothOppProvider( 1215): starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
V/BluetoothOppProvider( 1215): created cursor android.database.sqlite.SQLiteCursor@42921d90 on behalf of 
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1157): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/AudioFlinger(  270): releaseWakeLock_l() AudioOut_2
,V/AudioFlinger(  270): thread 0xb2705008 type 0 TID 918 going to sleep
,V/AudioFlinger(  270): releaseWakeLock_l() AudioOut_3
,V/AudioFlinger(  270): thread 0xb2594008 type 0 TID 1000 going to sleep
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/dalvikvm(  962): Jit: resizing JitTable from 8192 to 16384
,I/jxcore-log( 4080): BLE advertisement not supported: Build version is 19
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 3637): [336] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3637): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
,D/WifiController(  962): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/HeadsetStateMachine( 1215): Disconnected process message: 10
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,I/PowerManagerService(  962): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  962): [updateScreenState] screen on = false
,D/KnockOnPowerController(  962): [setProximitySensorEnabled] enable = false
,D/KnockOnPowerController(  962): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  962): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
I/qcom_sensors_hal(  962): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
I/qcom_sensors_hal(  962): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=35, enabled=1
I/qcom_sensors_hal(  962): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  962): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 9153 usec
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/qcom_sensors_hal(  962): hal_acquire_resources
,I/qcom_sensors_hal(  962): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  962): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
,I/qcom_sensors_hal(  962): hal_sam_activate: Activating sensor handle 35
V/qcom_sensors_hal(  962): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
,D/qcom_sensors_hal(  962): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  962): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  962): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.556458 Y: -0.397964 Z: 9.753632 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.556458 .y:-0.397964 .z:9.753632
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,I/Sensors (  576): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.544373 Y: -0.388565 Z: 9.751251 
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.544373 .y:-0.388565 .z:9.751251
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
V/qcom_sensors_hal(  962): hal_sam_parse_ind: Received 1 samples
,I/qcom_sensors_hal(  962): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  962): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/KnockOnPowerController(  962): proximity onSensorChanged : proximity = 1
,D/KnockOnPowerController(  962): proximitySensorChanged  positive = true
,I/KnockOnPowerController(  962): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.560867 Y: -0.383820 Z: 9.747437 
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.572937 Y: -0.390396 Z: 9.737549 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.560867 .y:-0.383820 .z:9.747437
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.549240 Y: -0.373123 Z: 9.716690 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.549240 .y:-0.373123 .z:9.716690
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.556854 Y: -0.367386 Z: 9.736633 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.556854 .y:-0.367386 .z:9.736633
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.553345 Y: -0.393997 Z: 9.743683 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.553345 .y:-0.393997 .z:9.743683
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  962): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43b8a2d0)
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb8098450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
D/KeyguardViewMediator( 1143): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1143): notifyScreenOnLocked
D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
D/KeyguardViewMediator( 1143): handleNotifyScreenOn
,D/KeyguardViewManager( 1143): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  962): **** SHOWN CALLED ****
I/WindowManager(  962): No lock screen! windowToken=null
,D/NfcServiceBRCM( 1472): NFC is already turned off.
,D/WifiStateMachine(  962): handleScreenStateChanged: true
,D/WifiServiceExtension(  962): sendKtScanInterval  mRtspPlay : false
D/WifiStateMachine(  962): handleMessage: E msg.what=131154
D/WifiStateMachine(  962): processMsg: InitialState
D/WifiStateMachine(  962): processMsg: DefaultState
,D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131127
D/WifiStateMachine(  962): processMsg: InitialState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=131158
D/WifiStateMachine(  962): processMsg: InitialState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): setSuspendOptimizations: 4 false
D/WifiStateMachine(  962): mSuspendOptNeedsDisabled 4
,D/WifiStateMachine(  962): handleMessage: X
,D/WifiOffDelayIfNotUsed(  962): stopMonitoring
,E/AudioSystem(  962): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 962
V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
,V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=2,
V/EmotionalLed( 1157): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4320a910 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1157): enqueuing start. mLedList.size()=2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1157): enqueuing end. mLedList.size()=3
,I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1857): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 11:37:22
,E/SlideAside( 3469): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 3469): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/UpdateThreadPoolManager( 1857): 2 : This is isUpdating : false
D/WeatherAncestor( 1857): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 11:37:22
,D/WeatherService( 1857): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
D/WeatherService( 1857): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1857): 2 : shouldTimeTickRegistered : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1157): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1157): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1157): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1157): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1157): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1157): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1157): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1157): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 207, B = 207
,D/qdlights( 1157): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 201, B = 201
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  962): Excessive delay in blankDisplay() while turning screen off: 401ms
,D/qdlights( 1157): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 195, B = 195
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1157): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 189, B = 189
,D/GlobalAccess( 1143): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1143): changeTargets() succeeded. size: 20
D/qdlights( 1157): set_light_notifications: 2,ff00b7b7,10,0,2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448361442884, nextTick: 37149, mDrawingTime: 0
,D/qdlights( 1157): [Current] = 255, R = 0, G = 183, B = 183
,D/qdlights( 1157): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 177, B = 177
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448361442904, nextTick: 37128, mDrawingTime: 0
,D/NfcServiceBRCM( 1472): NFC is already turned off.
,D/qdlights( 1157): set_light_notifications: 2,ff00abab,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 171, B = 171
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.542450 Y: -0.383377 Z: 9.746216 
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.542450 .y:-0.383377 .z:9.746216
D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/qdlights( 1157): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 165, B = 165
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WeatherService( 1857): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 11:37:22
,D/WeatherService( 1857): 2 : ACTION screen on
,D/WeatherService( 1857): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1857): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 11:37:22
,D/qdlights( 1157): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 159, B = 159
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_ON
D/qdlights( 1157): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 153, B = 153
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=0, enabled=0
I/qcom_sensors_hal(  962): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
I/qcom_sensors_hal(  962): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  962): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/KeyguardViewMediator( 1143): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1143): notifyScreenOffLocked
,D/qdlights( 1157): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 147, B = 147
,V/ActivityManager(  962): Moving to PAUSING: ActivityRecord{44d3e170 u0 com.test.thalitest/.MainActivity t3}
D/qcom_sensors_hal(  962): hal_acquire_resources
D/qcom_sensors_hal(  962): hal_acquire_resources: Deactivating sensor handle=0
D/qcom_sensors_hal(  962): hal_smgr_report_delete: handle=0
D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=1000
D/qdlights( 1157): set_light_notifications: 2,ff008d8d,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 141, B = 141
V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  962): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  962): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
D/qcom_sensors_hal(  962): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1157): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 135, B = 135
,D/qdlights( 1157): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 129, B = 129
,V/ActivityManager(  962): Moving to PAUSED: ActivityRecord{44d3e170 u0 com.test.thalitest/.MainActivity t3} (pause complete)
,V/ActivityManager(  962): Moving to STOPPING: ActivityRecord{44d3e170 u0 com.test.thalitest/.MainActivity t3} (stop requested)
D/qdlights( 1157): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 123, B = 123
,D/KeyguardViewMediator( 1143): setting alarm to turn off keyguard, seq = 2, timeout = 5000
,I/LGImmersionVibrator(  962): Vibrator off
V/ActivityManager(  962): Moving to DESTROYING: ActivityRecord{431e78c8 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,V/ActivityManager(  962): Moving to STOPPED: ActivityRecord{44d3e170 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/WifiStateMachine(  962): handleScreenStateChanged: false
D/qdlights( 1157): set_light_notifications: 2,ff007575,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 117, B = 117
D/WifiStateMachine(  962): handleMessage: E msg.what=131154
D/WifiStateMachine(  962): processMsg: InitialState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131158
D/WifiStateMachine(  962): processMsg: InitialState
D/WifiStateMachine(  962): processMsg: DefaultState
I/rmt_storage(  612): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb71a5178
I/rmt_storage(  612): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
I/rmt_storage(  612): wakelock acquired: 1, error no: 42
I/rmt_storage(  612): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1223011784)
D/WifiStateMachine(  962): setSuspendOptimizations: 4 true
D/WifiStateMachine(  962): mSuspendOptNeedsDisabled 0
D/WifiStateMachine(  962): handleMessage: X
,D/UsbSettings( 2521): [AUTORUN] onDestroy() : getDefaultFunction =boot
V/UsbSettings( 2521): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2521): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2521): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
D/KeyguardViewMediator( 1143): handleNotifyScreenOff
D/KeyguardViewManager( 1143): onScreenTurnedOff()
D/qdlights( 1157): set_light_notifications: 2,ff006f6f,10,0,2
D/qdlights( 1157): [Current] = 255, R = 0, G = 111, B = 111
E/AudioSystem(  962): AudioSystem::setParameters()...keyValue screen_state=off
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 962
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiController(  962): CMD_SCREEN_OFF 
D/WifiController(  962): shouldWifiStayAwake TRUE
D/qdlights( 1157): set_light_notifications: 2,ff006969,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 105, B = 105
I/EmotionalLed( 1157): getCurrentHighestLGLedRecord() start. mLedList.size=3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/VolumeVibrator( 1157): clear
E/CliptrayService( 1157): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
,D/qdlights( 1157): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 99, B = 99
,D/NfcServiceBRCM( 1472): NFC is already turned off.
V/ActivityManager(  962): Moving to DESTROYED: ActivityRecord{431e78c8 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{4306a0a0 stackId=1, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/[LGHome]EVENT( 1488): [Launcher.java:1567:onReceive()]Screen Off
V/TelephonyAutoProfiling(  962): [getValue] FEATURE key : trf_based_vzw, value : null
,V/LGRssiData(  962): [loadRssi] File not exist 
D/qdlights( 1157): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 93, B = 93
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
E/Parcel  (  599): Reading a NULL string not supported here.
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,D/BubblePopupHelper( 1143): isShowingBubblePopup : false
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : support_smart_dialing, value : null
,V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1448): [getValue] FEATURE key : trf_based_vzw, value : null
,D/PhoneInterfaceManager( 1448): [PhoneIntfMgr] sigLevel = 0
,D/WeatherService( 1857): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 11:37:23
D/WeatherService( 1857): 2 : ACTION screen off
,D/WeatherService( 1857): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 11:37:23
D/qdlights( 1157): set_light_notifications: 2,ff005757,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 87, B = 87
,V/PhoneApp( 1448): Action intent recieved:android.intent.action.SCREEN_OFF
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
D/qdlights( 1157): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 81, B = 81
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
,D/TangibleManager( 1460): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
D/qdlights( 1157): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1157): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1157): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1157): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1157): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1157): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1157): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 39, B = 39
I/rmt_storage(  612): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
I/rmt_storage(  612): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  612): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1223011784) wakelock released: 1, error no: 0
I/rmt_storage(  612): 
,I/rmt_storage(  612): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb71a5178
,E/Diag_Lib(  703): [IMS_FATAL]| 2912 | 707 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
D/qdlights( 1157): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 33, B = 33
,D/qdlights( 1157): set_light_notifications: 2,ff001b1b,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 27, B = 27
,D/qdlights( 1157): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1157): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1157): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1157): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1157): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1157): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  576): sns_pwr.c(320):releasing wakelock
,E/ThermalEngine(  284): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardViewMediator( 1143): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/PhoneApp( 1448): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1143): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1143): OMADM Lock is OFF
,D/KeyguardViewMediator( 1143): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1143): doKeyguard is called, but is not locked.
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361456133124684; DSPS: 5109990; Offset: 1448361300188605642
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1157): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  962): battery changed pluggedType: 2
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1215): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 289 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361476135259885; DSPS: 5765420; Offset: 1448361300188604612
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448361480045, nextTick: 59984, mDrawingTime: 1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448361480050, nextTick: 59962, mDrawingTime: 7
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361496137769148; DSPS: 6420862; Offset: 1448361300188611434
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361516139369140; DSPS: 7076274; Offset: 1448361300188624512
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361536141688821; DSPS: 7731711; Offset: 1448361300188594339
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448361540036, nextTick: 59980, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448361540063, nextTick: 59968, mDrawingTime: 1
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361556144182511; DSPS: 8387152; Offset: 1448361300188616105
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361576146197399; DSPS: 9042578; Offset: 1448361300188616833
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361596148088537; DSPS: 9698000; Offset: 1448361300188615881
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448361600032, nextTick: 59993, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448361600056, nextTick: 59975, mDrawingTime: 1
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361616151244467; DSPS: 10353464; Offset: 1448361300188597983
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361636153216855; DSPS: 11008888; Offset: 1448361300188617246
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1548): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x430e3cf8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1548): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1548): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1548): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1548): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1548): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1548): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1548): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1548): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3637): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3637): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3637): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3637): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3637): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3637): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3637): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3637): 	at dalvik.system.NativeStart.run(Native Method)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 3637): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 3637): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/SocketClient(  264): write error (Broken pipe)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/dalvikvm( 2579): GC_CONCURRENT freed 7698K, 32% free 16931K/24832K, paused 4ms+2ms, total 57ms
,D/dalvikvm( 2579): WAIT_FOR_CONCURRENT_GC blocked 48ms
,D/dalvikvm( 2579): GC_CONCURRENT freed 1813K, 31% free 17165K/24832K, paused 3ms+2ms, total 29ms
,D/dalvikvm( 2579): WAIT_FOR_CONCURRENT_GC blocked 20ms
,D/dalvikvm( 2579): GC_FOR_ALLOC freed 1577K, 31% free 17317K/24832K, paused 21ms, total 21ms
,I/Mlt MonitorService( 2579): parseLastkmsg to dump
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361656154402056; DSPS: 11664287; Offset: 1448361300188612262
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448361660052, nextTick: 59973, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448361660056, nextTick: 59974, mDrawingTime: 1
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361676156929548; DSPS: 12319730; Offset: 1448361300188606795
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361696159257040; DSPS: 12975166; Offset: 1448361300188614951
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361716161964325; DSPS: 13630615; Offset: 1448361300188606171
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448361720028, nextTick: 60002, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448361720047, nextTick: 59984, mDrawingTime: 1
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,W/ProcessCpuTracker(  962): Skipping unknown process pid 4577
,W/ProcessCpuTracker(  962): Skipping unknown process pid 4578
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/WifiController(  962): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1215): Disconnected process message: 10
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361736163886088; DSPS: 14286038; Offset: 1448361300188605327
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361756165838268; DSPS: 14941462; Offset: 1448361300188604382
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361776167826958; DSPS: 15596887; Offset: 1448361300188609429
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448361780036, nextTick: 59969, mDrawingTime: 10
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448361780054, nextTick: 59979, mDrawingTime: 0
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361796170176846; DSPS: 16252324; Offset: 1448361300188609464
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361816172177308; DSPS: 16907750; Offset: 1448361300188595766
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361836174615372; DSPS: 17563189; Offset: 1448361300188622941
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448361840022, nextTick: 60002, mDrawingTime: 6
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448361840058, nextTick: 59974, mDrawingTime: 0
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361856177501042; DSPS: 18218644; Offset: 1448361300188609441
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361876179866555; DSPS: 18874082; Offset: 1448361300188594583
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361896182613735; DSPS: 19529531; Offset: 1448361300188625698
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448361900035, nextTick: 59961, mDrawingTime: 14
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448361900060, nextTick: 59970, mDrawingTime: 1
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361916184305082; DSPS: 20184947; Offset: 1448361300188608061
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/ActivityManager(  962): Killing 2079:android.process.media/u0a23 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{4306a0a0 stackId=1, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361936186660334; DSPS: 20840384; Offset: 1448361300188613459
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1548): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x4321acc8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1548): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1548): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1548): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1548): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1548): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1548): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1548): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1548): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3637): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3637): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3637): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3637): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3637): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3637): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3637): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3637): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3637): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/SocketClient(  264): write error (Broken pipe)
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361956188339337; DSPS: 21495799; Offset: 1448361300188613996
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448361960030, nextTick: 59981, mDrawingTime: 12
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448361960064, nextTick: 59967, mDrawingTime: 1
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361976190874486; DSPS: 22151242; Offset: 1448361300188616186
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448361996192847499; DSPS: 22806667; Offset: 1448361300188605556
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362016194923689; DSPS: 23462095; Offset: 1448361300188606551
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362020023, nextTick: 59995, mDrawingTime: 9
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362020064, nextTick: 59969, mDrawingTime: 0
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362036197019098; DSPS: 24117524; Offset: 1448361300188596247
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362056199163778; DSPS: 24772954; Offset: 1448361300188604696
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362076201870750; DSPS: 25428403; Offset: 1448361300188595604
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362080026, nextTick: 59980, mDrawingTime: 12
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362080064, nextTick: 59969, mDrawingTime: 0
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362096203878711; DSPS: 26083828; Offset: 1448361300188619922
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362116206250630; DSPS: 26739266; Offset: 1448361300188611470
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362136208779112; DSPS: 27394709; Offset: 1448361300188606993
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362140057, nextTick: 59963, mDrawingTime: 8
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362140062, nextTick: 59971, mDrawingTime: 0
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362156211008219; DSPS: 28050142; Offset: 1448361300188608317
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362176213251961; DSPS: 28705575; Offset: 1448361300188624276
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362196215421121; DSPS: 29361006; Offset: 1448361300188626688
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362200026, nextTick: 60003, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362200045, nextTick: 59988, mDrawingTime: 0
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362216218028456; DSPS: 30016452; Offset: 1448361300188609511
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362236220701679; DSPS: 30671900; Offset: 1448361300188597187
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1548): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x447840c0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1548): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1548): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1548): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1548): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1548): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1548): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1548): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1548): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3637): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3637): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3637): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3637): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3637): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3637): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3637): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3637): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3637): Ignoring header User-Agent because its value was null.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362256227833910; DSPS: 31327493; Offset: 1448361300188618823
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362260036, nextTick: 59980, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362260046, nextTick: 59986, mDrawingTime: 0
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362276230074735; DSPS: 31982927; Offset: 1448361300188601347
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362296232802281; DSPS: 32638376; Offset: 1448361300188612828
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362316234770658; DSPS: 33293801; Offset: 1448361300188597563
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362320035, nextTick: 59992, mDrawingTime: 4
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362320044, nextTick: 59986, mDrawingTime: 1
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362336237703983; DSPS: 33949257; Offset: 1448361300188601200
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362356239603090; DSPS: 34604679; Offset: 1448361300188608217
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362376242292771; DSPS: 35260127; Offset: 1448361300188612352
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362380042, nextTick: 59985, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362380045, nextTick: 59986, mDrawingTime: 1
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362396244605576; DSPS: 35915563; Offset: 1448361300188605821
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362416247129370; DSPS: 36571006; Offset: 1448361300188596656
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362436249056341; DSPS: 37226429; Offset: 1448361300188601019
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362440036, nextTick: 59966, mDrawingTime: 11
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362440057, nextTick: 59974, mDrawingTime: 1
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362456251714459; DSPS: 37881876; Offset: 1448361300188604108
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362476254867576; DSPS: 38537339; Offset: 1448361300188613914
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362496257279600; DSPS: 39192778; Offset: 1448361300188615050
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362500031, nextTick: 59983, mDrawingTime: 10
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362500063, nextTick: 59968, mDrawingTime: 1
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362516258876415; DSPS: 39848190; Offset: 1448361300188624951
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362536261288491; DSPS: 40503629; Offset: 1448361300188626138
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1548): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm( 1548): GC_EXPLICIT freed 1514K, 29% free 17811K/24832K, paused 3ms+7ms, total 52ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/GLSActivity( 1548): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1548): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1548): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1548): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1548): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1548): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1548): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1548): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3637): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3637): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3637): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3637): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3637): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3637): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3637): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3637): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3637): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/dalvikvm(  962): GC_CONCURRENT freed 2921K, 48% free 29664K/56632K, paused 4ms+7ms, total 127ms
,D/dalvikvm(  962): WAIT_FOR_CONCURRENT_GC blocked 115ms
D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x44e886a0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362556263650410; DSPS: 41159067; Offset: 1448361300188607686
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362560033, nextTick: 59992, mDrawingTime: 6
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362560059, nextTick: 59969, mDrawingTime: 2
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362576265430090; DSPS: 41814485; Offset: 1448361300188617346
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362596267461541; DSPS: 42469912; Offset: 1448361300188604120
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362616269884971; DSPS: 43125351; Offset: 1448361300188616661
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362620073, nextTick: 59957, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362620076, nextTick: 59955, mDrawingTime: 1
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362636272859338; DSPS: 43780809; Offset: 1448361300188600305
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362656274851726; DSPS: 44436234; Offset: 1448361300188609051
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362676277076823; DSPS: 45091667; Offset: 1448361300188606365
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362680048, nextTick: 59982, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362680049, nextTick: 59982, mDrawingTime: 1
D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,W/ProcessCpuTracker(  962): Skipping unknown process pid 5492
,W/ProcessCpuTracker(  962): Skipping unknown process pid 5494
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362696279199940; DSPS: 45747096; Offset: 1448361300188623769
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362716281871912; DSPS: 46402544; Offset: 1448361300188610194
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362736283791175; DSPS: 47057967; Offset: 1448361300188606849
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362740036, nextTick: 59969, mDrawingTime: 10
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362740054, nextTick: 59979, mDrawingTime: 0
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362756286150646; DSPS: 47713404; Offset: 1448361300188616467
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362776288634337; DSPS: 48368846; Offset: 1448361300188597716
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362796291415007; DSPS: 49024297; Offset: 1448361300188601287
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362800048, nextTick: 59964, mDrawingTime: 10
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362800060, nextTick: 59970, mDrawingTime: 1
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362816293150467; DSPS: 49679714; Offset: 1448361300188597245
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362836295690147; DSPS: 50335157; Offset: 1448361300188603966
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1548): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x432134c8: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1548): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1548): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1548): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1548): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1548): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1548): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1548): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1548): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3637): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3637): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3637): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3637): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3637): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3637): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3637): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3637): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3637): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362856298088264; DSPS: 50990595; Offset: 1448361300188621712
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362860035, nextTick: 59986, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362860041, nextTick: 59990, mDrawingTime: 1
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362876301256695; DSPS: 51646059; Offset: 1448361300188616315
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362896303698979; DSPS: 52301499; Offset: 1448361300188617192
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362916305641210; DSPS: 52956923; Offset: 1448361300188606298
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362920045, nextTick: 59974, mDrawingTime: 7
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362920054, nextTick: 59979, mDrawingTime: 0
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1143): handleBatteryUpdate (2) (100)
,D/WifiController(  962): battery changed pluggedType: 2
,D/TangibleManager( 1460): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1460): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1460): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/HeadsetTangibleController( 1460): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1215): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 277 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1143): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362936307682504; DSPS: 53612350; Offset: 1448361300188602915
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362956309985726; DSPS: 54267785; Offset: 1448361300188617318
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362976312047490; DSPS: 54923213; Offset: 1448361300188603887
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362980043, nextTick: 59981, mDrawingTime: 5
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448362980049, nextTick: 59978, mDrawingTime: 2,
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448362996313908264; DSPS: 55578634; Offset: 1448361300188603089
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448363016316217266; DSPS: 56234069; Offset: 1448361300188623272
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448363036318571112; DSPS: 56889507; Offset: 1448361300188596747
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448363040037, nextTick: 59991, mDrawingTime: 3
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448363040061, nextTick: 59968, mDrawingTime: 2
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448363056320856783; DSPS: 57544941; Offset: 1448361300188624117
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/dalvikvm( 2579): GC_CONCURRENT freed 2500K, 33% free 16736K/24832K, paused 3ms+2ms, total 34ms
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448363076323270420; DSPS: 58200381; Offset: 1448361300188596348
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448363096325637027; DSPS: 58855818; Offset: 1448361300188613102
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448363100037, nextTick: 59992, mDrawingTime: 2
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448363100070, nextTick: 59961, mDrawingTime: 1
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448363116327868738; DSPS: 59511251; Offset: 1448361300188617030
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448363136329869772; DSPS: 60166677; Offset: 1448361300188603903
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/ProcessStatsService(  962): Prepared write state in 27ms
,I/GLSUser ( 1548): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1548): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1548): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1548): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1548): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1548): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  962): updateLightListLocked :r=NotificationRecord(0x42e85220: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1548): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1548): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1548): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1548): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1548): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1548): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1548): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1548): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  962): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 3637): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3637): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3637): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3637): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3637): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3637): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3637): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3637): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3637): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ProcessStatsService(  962): Pruning old procstats: /data/system/procstats/state-2015-11-23-17-38-31.bin
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448363156332936380; DSPS: 60822137; Offset: 1448361300188618754
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
I/ActivityManager(  962): Killing 3733:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty for 1817s
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448363160032, nextTick: 59999, mDrawingTime: 1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448363160033, nextTick: 59998, mDrawingTime: 1
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{4306a0a0 stackId=1, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Going to sleep and all paused
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448363176335032049; DSPS: 61477566; Offset: 1448361300188608710
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448363196336492041; DSPS: 62132974; Offset: 1448361300188603858
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448363216338935679; DSPS: 62788414; Offset: 1448361300188606090
,D/KeyguardUpdateMonitor( 1143): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1143): handleTimeUpdate
,D/KeyguardModel( 1143): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448363220047, nextTick: 59981, mDrawingTime: 2
,D/Clock   ( 1143): Clock updated, drawingStartTime : 1448363220051, nextTick: 59961, mDrawingTime: 7
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,D/qcom_sensors_hal(  962): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  962): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  962): hal_ts_offset_is: Apps: 1448363236341156662; DSPS: 63443847; Offset: 1448361300188599289
,I/jxcore-log( 4080): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4080): 
,TIME-OUT KILL (timeout was 1800000ms)
```
