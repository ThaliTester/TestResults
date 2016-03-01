#### Test 61248225a3bd1fe_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigService( 1538): onCreate
I/ConfigFetchService( 1860): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1860): launchTask
D/ChimeraCfgMgr( 1860): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1860): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1860): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1860): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1860): Failed to find package metadata for com.example.hello
D/Vision  ( 1860): No vision deps
I/ConfigFetchService( 1860): service connected
D/ConfigFetchService( 1860): ConfigApi connection successful.
I/PeopleContactsSync( 1860): CP2 sync disabled
I/dalvikvm( 1860): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1860): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1860): VFY: replacing opcode 0x6e at 0x000e
D/dalvikvm( 1538): GC_EXPLICIT freed 1441K, 27% free 18136K/24832K, paused 1ms+4ms, total 31ms
W/BaseAppContext( 1860): Using Auth Proxy for data requests.
W/BaseAppContext( 1860): Using Auth Proxy for data requests.
W/BaseAppContext( 1860): Using Auth Proxy for data requests.
W/BaseAppContext( 1860): Using Auth Proxy for data requests.
W/BaseAppContext( 1860): Using Auth Proxy for data requests.
W/BaseAppContext( 1860): Using Auth Proxy for data requests.
W/GAV2    ( 4555): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  967): Killing 4035:com.android.providers.calendar/u0a16 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e69a8 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42c14e88 u0 com.android.settings/.UsbSettings t2}
D/ChimeraCfgMgr( 1860): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1860): Module APK com.google.android.play.games already loaded
E/ThermalEngine(  293): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1860): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1860): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1860): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
,D/AndroidRuntime( 4605): 
D/AndroidRuntime( 4605): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4605): CheckJNI is OFF
D/dalvikvm( 4605): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4605): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4605): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4605): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4605): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4605): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
D/WifiStateMachine(  967): handleMessage: E msg.what=131155
D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2047): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2047): wlan0: Control interface command 'SIGNAL_POLL'
D/wpa_supplicant( 2047): nl80211: survey data missing!
D/WifiStateMachine(  967): handleMessage: X
E/memtrack( 4605): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4605): failed to load memtrack module: -2
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4605): Calling main entry com.android.commands.am.Am
I/ActivityManager(  967): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 4605
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e69a8 stackId=1, 2 tasks}
D/PermissionCache(  275): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (118 us)
V/ActivityManager(  967): Moving to PAUSING: ActivityRecord{42c14e88 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  967): GC_FOR_ALLOC freed 1349K, 10% free 28520K/31448K, paused 86ms, total 86ms
I/dalvikvm-heap(  967): Grow heap (frag case) to 30.847MB for 856096-byte allocation
D/ActivityManager(  967): resumeTopActivityLocked: Pausing null
V/ActivityManager(  967): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  967): startService SlideAside
W/ContextImpl(  967): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  967): setFocusedStack: mFocusedStack=ActivityStack{434e69a8 stackId=1, 2 tasks}
D/UsbSettingsControl( 2613): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2613): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/AndroidRuntime( 4605): Shutting down VM
I/SlideAside( 4129): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/ActivityManager(  967): allPausedActivitiesComplete: r=ActivityRecord{42c14e88 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  967): Moving to PAUSED: ActivityRecord{42c14e88 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e69a8 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Restarting ActivityRecord{434d8b98 u0 com.example.hello/.MainActivity t3}
D/dalvikvm( 4605): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
I/ActivityManager(  967): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4623 uid=10312 gids={50312, 3003, 3001, 3002}
I/SlideAside( 4129): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 4129): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.example.hello (filtered)
V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{434d8b98 u0 com.example.hello/.MainActivity t3} (starting new instance)
D/HyLog   ( 4623): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4623): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4623): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4623): Binding Chromium to the background looper Looper (main, tid 1) {42b8ad58}
I/chromium( 4623): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4623): Initializing chromium process, renderers=0
W/chromium( 4623): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4623): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4623): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4623): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4623): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4623): Remote Branch: 
I/Adreno-EGL( 4623): Local Patches: 
I/Adreno-EGL( 4623): Reconstruct Branch: 
I/dalvikvm( 4623): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4623): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4623): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4623): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4623): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4623): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4623): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4623): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4623): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4623): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4623): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4623): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4623): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4623): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4623): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4623): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4623): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4623): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4623): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4623): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
W/BaseRuntimeLoader( 4623): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4623): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4623): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4623): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
D/OpenGLRenderer( 4623): Enabling debug mode 0
W/AwContents( 4623): nativeOnDraw failed; clearing to background color.
I/InputMethodManagerService(  967): IME STATUS OFF
W/AwContents( 4623): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  967): Displayed com.example.hello/.MainActivity: +453ms
I/ActivityManager( 4623): Timeline: Activity_idle id: android.os.BinderProxy@42b8c900 time:42951
I/chromium( 4623): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 4623): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/JsMessageQueue( 4623): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4623): Trying to load lib /data/app-lib/com.example.hello-2/libjxcore.so 0x42b90ab0
D/dalvikvm( 4623): Added shared lib /data/app-lib/com.example.hello-2/libjxcore.so 0x42b90ab0
D/jxcore_app_log( 4623): JniHelper::setJavaVM(0x41b3d808), pthread_self() = 1634960992
D/JX-Cordova( 4623): jxcore cordova android initializing
I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{434d8b98 u0 com.example.hello/.MainActivity t3} time:43255
D/ActivityManager(  967): no-history finish of ActivityRecord{42c14e88 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  967): Finishing activity token=Token{43604a98 ActivityRecord{42c14e88 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  967): Moving to FINISHING: ActivityRecord{42c14e88 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{434d8b98 u0 com.example.hello/.MainActivity t3}
V/ActivityManager(  967): Moving to STOPPING: ActivityRecord{42c14e88 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
D/UsbSettings( 2613): [AUTORUN] onStop()
W/jxcore-log( 4623): Initializing JXcore engine
W/jxcore-log( 4623): JXcore engine is ready
V/ActivityManager(  967): Moving to STOPPED: ActivityRecord{42c14e88 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
W/jxcore-log( 4623): Starting JXcore engine
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/jxcore-log( 4623): Platform android
W/jxcore-log( 4623): 
W/jxcore-log( 4623): Process ARCH arm
W/jxcore-log( 4623): 
,I/jxcore-log( 4623): JXcore Cordova bridge is ready!
I/jxcore-log( 4623): 
,W/jxcore-log( 4623): JXcore engine is started
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/chromium( 4623): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/chromium( 4623): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,E/jxcore-log( 4623): >> LGE-LG-D802
E/jxcore-log( 4623): 
,I/jxcore-log( 4623): Total memory 1943035904
I/jxcore-log( 4623): 
I/jxcore-log( 4623): Free memory 396013568
I/jxcore-log( 4623): 
I/jxcore-log( 4623): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4623): 
,I/jxcore-log( 4623): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4623): 
,I/jxcore-log( 4623): userPath [ 'www', 'www' ]
I/jxcore-log( 4623): 
,I/jxcore-log( 4623): Size 1080 1776
I/jxcore-log( 4623): 
,I/jxcore-log( 4623): Screen Brightness 255
I/jxcore-log( 4623): 
,E/jxcore-log( 4623): Dummy Error Log.
E/jxcore-log( 4623): 
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4623): getBuffer is called!!!!
I/jxcore-log( 4623): 
,I/CheckinService( 1860): Done disabling old GoogleServicesFramework version
,I/ActivityManager(  967): Waited long enough for: ServiceRecord{42bf9d18 u0 com.lge.slideaside/.MainService}
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2047): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2047): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2047): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,I/GAV2    ( 4555): Thread[GAThread,5,main]: No campaign data found.
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.410614 Y: -0.324722 Z: 9.808105 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.410614 .y:-0.324722 .z:9.808105
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  967): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  967): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  967): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  967): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  967): hal_process_report_ind: X: -0.429184 Y: -0.336258 Z: 9.801041 
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.429184 .y:-0.336258 .z:9.801041
,D/qcom_sensors_hal(  967): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  967): hal_wait_for_response: timeout=0
,I/ActivityManager(  967): Killing 4019:com.android.calendar/u0a15 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e69a8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{434d8b98 u0 com.example.hello/.MainActivity t3}
,D/WifiStateMachine(  967): handleMessage: E msg.what=131155
,D/WifiStateMachine(  967): processMsg: ConnectedState
,D/WifiStateMachine(  967): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  967): doString: SIGNAL_POLL
D/wpa_supplicant( 2047): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2047): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2047): nl80211: survey data missing!
,D/WifiStateMachine(  967): handleMessage: X
,D/BluetoothManagerService(  967): Message: 20
,D/BluetoothManagerService(  967): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43511d80:true
,D/BluetoothManagerService(  967): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  967): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@42c0eef0 mBinding = false
,D/BluetoothManagerService(  967): Message: 2
,D/BluetoothManagerService(  967): Sending off request.
,D/BluetoothAdapterService(1119576496)( 1214): disable() called...
,D/BluetoothAdapterState( 1214): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
,I/BluetoothAdapterState( 1214): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1214): Broadcasting updateAdapterState() to 1 receivers.
I/bt-btif ( 1214): btif_set_adapter_property type: 7, len 4, 0x42c6ac20
,I/bt-btif ( 1214): set property scan mode : 0
,I/bt-btif ( 1214): bta_dm_sm_execute event:0x3
,I/bt-btif ( 1214): btif_in_storage_request_copy_cb
,I/BluetoothAdapterState( 1214): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,I/bt-btif ( 1214): execute storage request event : 2
I/bt-btif ( 1214): type: 7, len 4, 0x606e8bc6
,D/bt-btif ( 1214): in, bd addr:, prop type:7, len:4
,I/bt-btif ( 1214): HAL bt_hal_cbacks->adapter_properties_cb
,D/BluetoothAdapterState( 1214): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
I/bluedroid( 1214): disable 1
,I/bt-btif ( 1214): BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
D/bt-btif ( 1214): h:6, process_cmd_sock return false, exit...
,D/bt-btif ( 1214): socket poll thread exiting, h:6
,D/bt-btif ( 1214): cleanup slot:1, fd:89, scn:6, sdp_handle:0x1000a
,V/BluetoothMapService( 1214): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/bt-btif ( 1214): del_rfc_sdp_rec: handle:0x1000a
I/bt-btif ( 1214): BTA_JvDeleteRecord
,D/bt-sdp  ( 1214): SDP_DeleteRecord ok, num_records:12
I/bt-btif ( 1214): BTA_JvRfcommStopServer
E/bt-btif ( 1214): bta_jv_rfcomm_stop_server
D/bt-btif ( 1214): find_rfc_pcb(): FOUND rfc_cb_handle 0x1, port.jv_handle: 0x81, state: 4, rfc_cb->handle: 0x81
,D/bt-btif ( 1214): bta_jv_rfcomm_stop_server: p_pcb:0x60d930e8, p_pcb->port_handle:6
D/bt-btif ( 1214): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60d930e8, user:1, state:4, jv handle: 0x81
D/bt-btif ( 1214): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:6, user_data:1
D/bt-btif ( 1214): bta_jv_rfcomm_stop_server: sec id in use:2, rfc_cb in use:2
,D/bt-btif ( 1214): cleanup slot:2, fd:91, scn:19, sdp_handle:0x1000b
,D/BluetoothManagerService(  967): Message: 60
D/bt-btif ( 1214): del_rfc_sdp_rec: handle:0x1000b
,V/BluetoothPbapService( 1214): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,I/bt-btif ( 1214): BTA_JvDeleteRecord
D/bt-sdp  ( 1214): SDP_DeleteRecord ok, num_records:11
I/bt-btif ( 1214): BTA_JvRfcommStopServer
,D/BluetoothManagerService(  967): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
E/bt-btif ( 1214): bta_jv_rfcomm_stop_server
D/bt-btif ( 1214): find_rfc_pcb(): FOUND rfc_cb_handle 0x2, port.jv_handle: 0x82, state: 4, rfc_cb->handle: 0x82
,D/bt-btif ( 1214): bta_jv_rfcomm_stop_server: p_pcb:0x60d930fc, p_pcb->port_handle:7
D/bt-btif ( 1214): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60d930fc, user:2, state:4, jv handle: 0x82
D/bt-btif ( 1214): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:19, user_data:2
D/bt-btif ( 1214): bta_jv_rfcomm_stop_server: sec id in use:1, rfc_cb in use:1
,D/bt-btif ( 1214): cleanup slot:3, fd:94, scn:12, sdp_handle:0x1000c
D/BluetoothManagerService(  967): Bluetooth State Change Intent: 12 -> 13
,E/BtOppRfcommListener( 1214): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,D/bt-btif ( 1214): del_rfc_sdp_rec: handle:0x1000c
I/bt-btif ( 1214): BTA_JvDeleteRecord
D/bt-sdp  ( 1214): SDP_DeleteRecord ok, num_records:10
,I/bt-btif ( 1214): BTA_JvRfcommStopServer
E/bt-btif ( 1214): bta_jv_rfcomm_stop_server
D/bt-btif ( 1214): find_rfc_pcb(): FOUND rfc_cb_handle 0x3, port.jv_handle: 0x83, state: 4, rfc_cb->handle: 0x83
D/bt-btif ( 1214): bta_jv_rfcomm_stop_server: p_pcb:0x60d93110, p_pcb->port_handle:8
,D/bt-btif ( 1214): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60d93110, user:3, state:4, jv handle: 0x83
D/bt-btif ( 1214): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:12, user_data:3
D/bt-btif ( 1214): bta_jv_rfcomm_stop_server: sec id in use:0, rfc_cb in use:0
,D/bt-btif ( 1214): leaving
D/bt-sdp  ( 1214): SDP_DeleteRecord ok, num_records:9
I/bt-btif ( 1214): Removing UUID=0x1116 from EIR
D/bt-btif ( 1214): BTA is generating EIR
,I/bt-btif ( 1214): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04031460
I/bt-btif ( 1214): Removing UUID=0x1116 from EIR
D/bt-btif ( 1214): BTA is generating EIR
I/bt-btif ( 1214): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04031460
,I/bt-btif ( 1214): Removing UUID=0x1117 from EIR
D/bt-btif ( 1214): BTA is generating EIR
I/bt-btif ( 1214): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04031460
,I/bt-btif ( 1214): Removing UUID=0x1115 from EIR
D/bt-btif ( 1214): BTA is generating EIR
,I/bt-btif ( 1214): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04011460
I/bt-btif ( 1214): bta_dm_sm_execute event:0x1
,D/bt-btif ( 1214): bta_sys_disable: module 0
W/bt-btif ( 1214): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,I/bt-btif ( 1214): AG evt (hdl 0x0001): State 0, Event 0x0501
D/bt-btif ( 1214): bta_ag_del_records 0
D/bt-sdp  ( 1214): SDP_DeleteRecord ok, num_records:8
I/bt-btif ( 1214): Removing UUID=0x1112 from EIR
,I/bt-btif ( 1214): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04001460
D/bt-btif ( 1214): bta_ag_del_records 1
D/bt-sdp  ( 1214): SDP_DeleteRecord ok, num_records:7
I/bt-btif ( 1214): Removing UUID=0x111F from EIR
,I/bt-btif ( 1214): bta_dm_eir_update_uuid UUID bit mask=0x00000494 00001460
D/bt-btif ( 1214): bta_ag_scb_dealloc 1
W/bt-obex ( 1214): Ignore event 10 in state 1
D/bt-sdp  ( 1214): SDP_DeleteRecord ok, num_records:6,
I/bt-btif ( 1214): Removing UUID=0x1106 from EIR,
I/bt-btif ( 1214): bta_dm_eir_update_uuid UUID bit mask=0x00000494 00001420
D/bt-sdp  ( 1214): SDP_DeleteRecord ok, num_records:5
I/bt-btif ( 1214): Removing UUID=0x112D from EIR
I/bt-btif ( 1214): bta_dm_eir_update_uuid UUID bit mask=0x00000490 00001420
I/bt-btif ( 1214): bta_av_del_rc  handle: 0 status=0x10, rc_acp_handle:0, idx:1
I/bt-btif ( 1214): end del_rc handle: 255 status=0x0, rc_acp_handle:255, lidx:0,
D/bt-btif ( 1214): bta_av_cleanup
D/bt-btif ( 1214): deregistered 64(h65)
D/bt-sdp  ( 1214): SDP_DeleteRecord ok, num_records:4
I/bt-btif ( 1214): Removing UUID=0x110A from EIR
I/bt-btif ( 1214): bta_dm_eir_update_uuid UUID bit mask=0x00000490 00001020
D/bt-btif ( 1214): audio 0x0, video: 0x0, disable:1
,D/bt-sdp  ( 1214): SDP_DeleteRecord ok, num_records:3
I/bt-btif ( 1214): Removing UUID=0x110C from EIR
I/bt-btif ( 1214): bta_dm_eir_update_uuid UUID bit mask=0x00000490 00000020
D/bt-btif ( 1214): audio 0x0, video: 0x0, disable:0
W/bt-l2cap( 1214): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1214): L2CAP - PSM: 0x0017 not found for deregistration
,D/bt-btif ( 1214): bta_gattc_disable
I/bt-att  ( 1214): GATT_Deregister gatt_if=3
I/bt-att  ( 1214): GATT_Listen gatt_if=3
D/bt-btif ( 1214): bta_dm_gattc_callback event = 1
I/bt-att  ( 1214): GATT_Deregister gatt_if=4,
I/bt-att  ( 1214): GATT_Listen gatt_if=4
D/bt-btif ( 1214): bta_hh_gattc_callback event = 1,
I/bt-btif ( 1214): bta_dm_search_sm_execute state:0, event:0x206
E/bt-btif ( 1214): bta_gattc_deregister Deregister Failed, unknown client cif
D/bt-btif ( 1214): btif_hf_upstreams_evt: event=BTA_AG_DISABLE_EVT
D/bt-btif ( 1214): btif_fts_upstreams_evt: event=BTA_FTS_DISABLE_EVT
I/bt-btif ( 1214): File Transfer: Disable complete
,D/bt-btif ( 1214): btif_hh_upstreams_evt: event=BTA_HH_DISABLE_EVT
D/IOP_DB_BT( 1214): db_close: nbr users 0
D/IOP_DB_BT( 1214): db_close: free database
,D/btif_config_util( 1214): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,E/LGBluetoothEventManager( 2613): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,D/BluetoothMapService( 1214): onReceive
,D/BluetoothMapService( 1214): STATE_TURNING_OFF
,D/LGBluetoothAPIService( 1156): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothMapService( 1214): MAP Service closeService in
,D/LGBluetoothMapAdapter( 1214): [BTUI] LGBluetoothMapAdapter cleanup
,V/BluetoothMapService( 1214): MAP Service closeService out
V/BtOppService( 1214): Receiver DISABLED_ACTION 
,I/BtOppRfcommListener( 1214): stopping Accept Thread
V/BtOppRfcommListener( 1214): close mBtServerSocket
V/BtOppRfcommListener( 1214): waiting for thread to terminate
,I/BtOppRfcommListener( 1214): BluetoothSocket listen thread finished
,V/BtOppRfcommListener( 1214): done waiting for thread to terminate
,V/BtOppService( 1214): onDestroy
,D/LGBluetoothOppAdapter( 1214): [BTUI] LGBluetoothOppAdapter cleanup
,D/WifiService(  967): New client listening to asynchronous messages
,D/WifiService(  967): setWifiEnabled: false pid=4623, uid=10312
E/WifiService(  967): Invoking mWifiStateMachine.setWifiEnabled
,I/WifiService(  967): setWifiEnabled startWifiDelaySendMsg true
,D/WifiStateMachine(  967): handleMessage: E msg.what=131084
,D/WifiStateMachine(  967): processMsg: ConnectedState
D/WifiStateMachine(  967): processMsg: L2ConnectedState
D/WifiStateMachine(  967): processMsg: ConnectModeState
,D/WifiStateMachine(  967): processMsg: DriverStartedState
,D/WifiStateMachine(  967): processMsg: DriverStartedStateExt
,D/WifiStateMachine(  967): processMsg: SupplicantStartedState
,I/jxcore-log( 4623): ****TEST TOOK:  5176  ms ****
I/jxcore-log( 4623): 
,I/jxcore-log( 4623): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4623): 
,D/WifiStateMachine(  967): transitionTo: destState=WaitForP2pDisableState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
D/WifiStateMachine(  967): invokeExitMethods: ConnectedState
W/Settings(  967): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiStateMachine(  967): invokeExitMethods: L2ConnectedState
D/WifiStateMachine(  967): invokeExitMethods: ConnectModeState
D/WifiStateMachine(  967): invokeExitMethods: DriverStartedState
D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING GET
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/wpa_supplicant( 2047): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2047): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2047): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
E/WifiStateMachine(  967): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  967): doString: DRIVER WLS_BATCHING STOP
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/wpa_supplicant( 2047): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2047): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
E/wpa_supplicant( 2047): wpa_driver_nl80211_driver_cmd: failed to issue private commands
D/WifiNative-wlan0(  967):    returned null
D/WifiStateMachine(  967): invokeExitMethods: DriverStartedStateExt
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
D/WifiStateMachine(  967): invokeEnterMethods: WaitForP2pDisableState
D/WifiStateMachine(  967): handleMessage: X
D/WifiMonitor(  967): WifiMonitorSingleton gotten
D/WifiMonitor(  967): stopMonitoring(p2p0) = android.net.wifi.p2p.WifiP2pService$P2pStateMachine@43421020
D/WifiStateMachine(  967): handleMessage: E msg.what=131205
D/WifiStateMachine(  967): processMsg: WaitForP2pDisableState
D/WifiStateMachine(  967): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  967): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine(  967): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine(  967): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine(  967): Stopping DHCP and clearing IP
D/WifiStateMachine(  967): setSuspendOptimizationsNative: 1 true
D/WifiNative-wlan0(  967): doBoolean: SET ps 1
D/wpa_supplicant( 2047): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2047): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2047): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2047): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
D/WifiNative-wlan0(  967):    returned true
D/WifiNative-wlan0(  967): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2047): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2047): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
D/wpa_supplicant( 2047): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WfdService( 1156): Waiting for Wifi disabling
D/WifiNative-wlan0(  967):    returned true
D/DhcpStateMachine(  967): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
D/CommandListener(  272): Clearing all IP addresses on wlan0
D/WifiStateMachine(  967): addressRemoved: 192.168.1.115/24 on wlan0 flags 128 scope 0
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiP2pService(  967): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): P2pDisablingState
D/WifiP2pService(  967): P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): p2p socket connection lost
D/WifiP2pService(  967): P2pDisabledState
D/WifiP2pService(  967): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  967): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl( 2613): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:156 com.android.settings.bluetooth.DockEventReceiver.onReceive:123 
V/BluetoothPbapReceiver( 1214): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1214): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1214): ***********state = 13
D/DockEventReceiver( 2613): finishStartingService: stopping service
V/BluetoothPbapReceiver( 1214): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 1214): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1214): state: 13
V/BluetoothPbapService( 1214): Pbap Service closeService in
V/BluetoothPbapService( 1214): successfully stopped pbap service
V/BluetoothPbapService( 1214): Pbap Service closeService out
D/LGBluetoothAuthorization( 2613): [BTUI] cancel All Notification
V/BluetoothPbapService( 1214): Pbap Service onDestroy
V/BluetoothPbapService( 1214): Pbap Service closeService in
V/BluetoothPbapService( 1214): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 1214): [BTUI] cleanup
D/WifiStateMachine(  967): setDetailed state, old =CONNECTED and new state=DISCONNECTED
D/WifiStateMachine(  967): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  967): stopping supplicant
D/WifiMonitor(  967): WifiMonitorSingleton gotten
D/WifiNative-p2p0(  967): doBoolean: TERMINATE
D/BluetoothPbap( 2613): Proxy object disconnected
,D/PbapServerProfile( 2613): Bluetooth service disconnected
D/wpa_supplicant( 2047): RX global ctrl_iface - hexdump(len=9): 54 45 52 4d 49 4e 41 54 45
D/wpa_supplicant( 2047): p2p0: Removing interface p2p0
D/wpa_supplicant( 2047): p2p0: Request to deauthenticate - bssid=00:00:00:00:00:00 pending_bssid=00:00:00:00:00:00 reason=3 state=DISCONNECTED
D/wpa_supplicant( 2047): TDLS: Tear down peers
D/wpa_supplicant( 2047): p2p0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2047): p2p0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2047): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2047): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2047): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2047): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2047): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2047): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2047): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2047): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2047): p2p0: No keys have been configured - skip key clearing
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/WifiNative-p2p0(  967):    returned true
V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 0
D/ConnectivityServiceHSM(  967): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
,D/WifiStateMachine(  967): setWifiState: disabling
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/WifiStateMachine(  967): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  967): useWiFiOffloading() : false
E/WifiStateMachine(  967): CONFIG_LGE_WLAN_PATH : true
E/Parcel  (  545): Reading a NULL string not supported here.
E/Parcel  (  545): Reading a NULL string not supported here.
E/Parcel  (  545): Reading a NULL string not supported here.
E/Parcel  (  545): Reading a NULL string not supported here.
E/Parcel  (  545): Reading a NULL string not supported here.
D/QCNEA   (  545): |CAC| readCallback: read len:492, ret:0, errno:0
D/QCNEA   (  545): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  545): |CAC| updateNetCfgInfo
V/QCNEA   (  545): |CAC| *********************************************
V/QCNEA   (  545): |CAC|                   Netconfig               
V/QCNEA   (  545): |CAC| *********************************************
V/QCNEA   (  545): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  545): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  545): |CAC| 	NetConfig:         fl =0
E/Parcel  (  545): Reading a NULL string not supported here.
V/QCNEA   (  545): |CAC| 	NetConfig: ip4        =0.0.0.0
E/Parcel  (  545): Reading a NULL string not supported here.
V/QCNEA   (  545): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  545): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  545): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  545): |CAC| *********************************************
D/QCNEA   (  545): |CAC| Received bssid= 
D/QCNEA   (  545): |CAC| net type = 3
V/QCNEA   (  545): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  545): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  545): |CAC| 	ssid           =NG700
V/QCNEA   (  545): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  545): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  545): |CAC| *********************************************
D/QCNEA   (  545): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  545): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  545): |CAC| dispatchNetCfg: updating:0xb7ecf8dc
,D/QCNEA   (  545): |CAC| readCallback: read len:0, ret:-1, errno:11
W/Settings(  967): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  967): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/WifiOffDelayIfNotUsed(  967): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/BluetoothPermissionRequest( 2613): onReceive
D/LGBluetoothAuthorization( 2613): [BTUI] cancel All Notification
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131213
D/WifiStateMachine(  967): processMsg: SupplicantStoppingState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/WifiStateMachine(  967): handleMessage: E msg.what=131213
D/WifiStateMachine(  967): processMsg: SupplicantStoppingState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
V/WfdStateTracker( 1156): WfdStateTracker handleDirectStateChangedEvent: 6
I/bt-btif ( 1214): btif_dm_cancel_discovery
I/bt-btif ( 1214): bta_dm_search_sm_execute state:0, event:0x201
D/WifiHS20(  967): hidePasspointNotification off =false
D/QcConnectivityService(  967): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
D/QcConnectivityService(  967): Attempting to switch to mobile
D/QcConnectivityService(  967): Attempting to switch to BLUETOOTH_TETHER
D/QcConnectivityService(  967): handleConnectivityChange: preConnState=1 connState=2
I/WifiServiceExtension(  967): WIFI_STATE_CHANGED_ACTION [0]
E/Parcel  (  545): Reading a NULL string not supported here.
E/Parcel  (  545): Reading a NULL string not supported here.
E/Parcel  (  545): Reading a NULL string not supported here.
E/Parcel  (  545): Reading a NULL string not supported here.
E/Parcel  (  545): Reading a NULL string not supported here.
E/Parcel  (  545): Reading a NULL string not supported here.
E/Parcel  (  545): Reading a NULL string not supported here.
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/LGBluetoothResetSettingReceiver( 2613): return without doing reset settings.
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/NetworkManagementService(  967): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  272): RouteController
V/BluetoothOppReceiver( 1214): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 1214): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 1214): [BTUI] cancel opp active transfer file notification
V/        (  272): RouteController
V/        (  272): RouteController
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
V/        (  272): RouteController
,I/ActivityManager(  967): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4712 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
D/wpa_supplicant( 2047): p2p0: Cancelling scan request
D/wpa_supplicant( 2047): p2p0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2047): p2p0: Cancelling authentication timeout
D/wpa_supplicant( 2047): p2p0: P2P: Disable P2P since removing the management interface is being removed
D/wpa_supplicant( 2047): P2P: Stopping find
D/wpa_supplicant( 2047): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 2047): P2P: State IDLE -> IDLE
D/wpa_supplicant( 2047): wpa_driver_set_ap_wps_p2p_ie: Entry
V/        (  272): RouteController
D/HyLog   ( 4712): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4712): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4712): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/        (  272): RouteController
V/        (  272): RouteController
V/        (  272): RouteController
W/NetworkManagementService(  967): route cmd failed: 
W/NetworkManagementService(  967): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  967): '
W/NetworkManagementService(  967): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  967): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  967): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  967): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  967): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  967): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  967): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  967): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  967): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  967): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  967): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  967): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  967): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  967): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  967): 	at android.os.HandlerThread.run(HandlerThread.java:61)
D/NetUtils(  967): android_net_utils_resetConnections in env=0x628f9538 clazz=0x67d00001 iface=wlan0 mask=0x3
D/AuthorizationBluetoothService( 1538): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
I/ActivityManager(  967): Killing 4094:com.google.android.talk/u0a77 (adj 15): empty #17
D/QcConnectivityService(  967): resetConnections(wlan0, 3)
V/NativeCrypto( 1538): Read error: ssl=0x60de1230: I/O error during system call, Connection timed out
V/NativeCrypto( 1538): SSL shutdown failed: ssl=0x60de1230: I/O error during system call, Broken pipe
D/wpa_supplicant( 2047): netlink: Operstate: linkmode=0, operstate=6
D/wpa_supplicant( 2047): nl80211: Set mode ifindex 22 iftype 2 (STATION)
D/wpa_supplicant( 2047): nl80211: Unsubscribe mgmt frames handle 0xb7d8fc28 (mode change)
I/wpa_supplicant( 2047): p2p0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 2047): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
I/wpa_supplicant( 2047): [ITEC] Close WIFLUS socket interface - START
I/wpa_supplicant( 2047): [ITEC] Close WIFLUS read interface - DONE
I/wpa_supplicant( 2047): HY wiflus comm channel de-initialized : wiflus = 0
D/wpa_supplicant( 2047): Control interface directory not empty - leaving it behind
D/wpa_supplicant( 2047): wlan0: Removing interface wlan0
D/wpa_supplicant( 2047): wlan0: Request to deauthenticate - bssid=f4:f2:6d:22:99:3e pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2047): TDLS: Tear down peers
D/wpa_supplicant( 2047): wpa_driver_nl80211_disconnect(reason_code=3)
I/bt-btif ( 1214): bta_sys_sm_execute state:2, event:0x3
D/bt-btif ( 1214): bta_sys_hw_api_disable for 0, active modules: 0x0001
D/bt-btif ( 1214): bta_sys_disable: module 0
I/bt-btif ( 1214): bta_sys_sm_execute state:3, event:0x4
D/bt-btif ( 1214): bta_sys_hw_evt_disabled - module 0x0
D/bt-btif ( 1214):  bta_dm_sys_hw_cback with event: 0
I/bt-btif ( 1214): btif_dm_upstreams_cback  ev: BTA_DM_DISABLE_EVT
D/WifiMonitor(  967): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
D/WifiMonitor(  967): Dropping event because monitor (p2p0) is stopped
I/bt-btif ( 1214): btif_disable_bluetooth_evt()::btif_core_cb: is_radio_req: 0, radio_ref_count: 0, state: 4
I/bt-btif ( 1214): HC lib lpm enable=0 return 0
D/bt-btif ( 1214): audio 0x0, video: 0x0, disable:0
W/bt-l2cap( 1214): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1214): L2CAP - PSM: 0x0017 not found for deregistration
D/bt-btif ( 1214): audio 0x0, video: 0x0, disable:1
W/bt-l2cap( 1214): L2CAP - PSM: 0x0019 not found for deregistration
I/bt-btif ( 1214): HC lpm_result_cb 0
W/bt-l2cap( 1214): HC lpm_result_cb 0
D/bt-btif ( 1214): audio 0x0, video: 0x0, disable:0
W/bt-l2cap( 1214): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1214): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 1214): ag scb idx 1 not allocated
E/bt-btif ( 1214): BTA AG is already disabled, ignoring ...
D/bt-btif ( 1214): bte_main_disable
D/bt-btif ( 1214): bte_hci_disable
D/bt_hwcfg( 1214): hw_epilog_process
I/ActivityManager(  967): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4733 uid=10101 gids={50101, 1028, 1015, 3003}
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e69a8 stackId=1, 2 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{434d8b98 u0 com.example.hello/.MainActivity t3}
D/wpa_supplicant( 2047): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2047): wlan0: Deauthentication notification
D/wpa_supplicant( 2047): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2047): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2047): wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
D/wpa_supplicant( 2047): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2047): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2047): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2047): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2047): wlan0: Disconnect event - remove keys
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
D/wpa_supplicant( 2047): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2047): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2047): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2047): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/WifiStateMachine(  967): handleMessage: E msg.what=147460
D/wpa_supplicant( 2047): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb7d7fd6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2047):    addr=f4:f2:6d:22:99:3e
D/WifiStateMachine(  967): processMsg: SupplicantStoppingState
D/wpa_supplicant( 2047): wlan0: State: COMPLETED -> DISCONNECTED
D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): handleMessage: X
D/wpa_supplicant( 2047): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
D/wpa_supplicant( 2047): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2047): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2047): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2047): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2047): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2047): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
D/wpa_supplicant( 2047): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2047): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2047): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2047): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2047): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2047): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2047): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2047): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2047): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2047): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2047): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2047): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2047): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2047): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2047): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2047): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2047): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2047): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2047): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2047): wlan0: No keys have been configured - skip key clearing
W/wpa_supplicant( 2047): USIM:  scard_deinit function
D/WifiStateMachine(  967): handleMessage: E msg.what=147462
D/WifiStateMachine(  967): processMsg: SupplicantStoppingState
D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
D/GpsLocationProvider(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/LocSvc_java(  967): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, smCause: 0, isConnectedToProvisioningNetwork: false
I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/Nat464Xlat(  967): requiresClat: netType=1, hasIPv4Address=false
D/LocSvc_java(  967): getAGpsConnectionInfo connType - 4
D/LocSvc_java(  967): ignore wifi update if we are not in OPENING or CLOSING
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
D/ConnectivityServiceHSM(  967): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/HyLog   ( 4733): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4733): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4733): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/bt_hwcfg( 1214): hw_epilog_cback Opcode:0x0C03 Status: 0
D/QcConnectivityService(  967): handleInetConditionChange: no active default network - ignore
I/Wireless_Storage( 4733): CONNECT : WIFI_P2P_STATE_CHANGED_ACTION
I/ActivityManager(  967): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4747 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  967): Killing 3954:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e69a8 stackId=1, 2 tasks}
,D/HyLog   ( 4747): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4747): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4747): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{434d8b98 u0 com.example.hello/.MainActivity t3}
,I/PCSuite ( 4747): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/PCSuite ( 4747): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4747): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  967): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4763 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  967): Killing 4440:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e69a8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{434d8b98 u0 com.example.hello/.MainActivity t3}
D/wpa_supplicant( 2047): wlan0: BSS: Remove id 0 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush
D/wpa_supplicant( 2047): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2047): wlan0: BSS: Remove id 1 BSSID f4:f2:6d:22:99:3e SSID 'NG700' due to wpa_bss_flush
D/wpa_supplicant( 2047): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2047): wlan0: BSS: Remove id 2 BSSID 00:1f:27:54:70:c1 SSID 'TEST_KTW01' due to wpa_bss_flush
D/wpa_supplicant( 2047): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2047): wlan0: BSS: Remove id 3 BSSID 00:1e:4a:8f:e3:6b SSID '\x00' due to wpa_bss_flush
D/wpa_supplicant( 2047): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2047): wlan0: BSS: Remove id 4 BSSID 00:1e:4a:8f:e3:60 SSID '\x00' due to wpa_bss_flush
D/wpa_supplicant( 2047): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2047): wlan0: BSS: Remove id 5 BSSID 00:1f:27:54:70:c0 SSID 'ktwtestwifi' due to wpa_bss_flush
D/wpa_supplicant( 2047): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2047): wlan0: BSS: Remove id 6 BSSID 00:1e:4a:8f:e3:6f SSID '\x00' due to wpa_bss_flush
D/wpa_supplicant( 2047): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2047): wlan0: BSS: Remove id 7 BSSID 34:4d:f7:73:42:46 SSID '_Aya' due to wpa_bss_flush
D/wpa_supplicant( 2047): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2047): wlan0: BSS: Remove id 8 BSSID 00:1f:27:54:dd:ef SSID '\x00' due to wpa_bss_flush
D/wpa_supplicant( 2047): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2047): wlan0: BSS: Remove id 9 BSSID 00:1f:27:54:dd:e2 SSID '\x00' due to wpa_bss_flush
D/wpa_supplicant( 2047): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2047): wlan0: BSS: Remove id 10 BSSID 00:1e:4a:8f:df:d4 SSID '\x00' due to wpa_bss_flush
D/wpa_supplicant( 2047): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/HyLog   ( 4763): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2047): wlan0: BSS: Remove id 11 BSSID 00:22:0d:47:49:84 SSID '\x00' due to wpa_bss_flush
D/HyLog   ( 4763): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/wpa_supplicant( 2047): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/HyLog   ( 4763): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2047): wlan0: BSS: Remove id 12 BSSID 00:1e:4a:8f:e3:64 SSID '\x00' due to wpa_bss_flush
D/wpa_supplicant( 2047): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2047): wlan0: BSS: Remove id 13 BSSID 00:1e:4a:8f:e3:63 SSID 'RA-WINGS' ,due to wpa_bss_flush
D/wpa_supplicant( 2047): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2047): wlan0: BSS: Remove id 14 BSSID 00:1f:27:54:dd:e3 SSID 'RA-WINGS' due to wpa_bss_flush
D/wpa_supplicant( 2047): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2047): wlan0: BSS: Remove id 15 BSSID 00:1f:27:54:e0:43 SSID 'RA-WINGS' due to wpa_bss_flush
D/wpa_supplicant( 2047): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2047): wlan0: Cancelling scan request
D/wpa_supplicant( 2047): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2047): wlan0: Cancelling authentication timeout
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 f0:f2:6d:22:99:3e]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 f4:f2:6d:22:99:3e]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c1]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 00:1e:4a:8f:e3:6b]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 00:1e:4a:8f:e3:60]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 00:1f:27:54:70:c0]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 00:1e:4a:8f:e3:6f]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 34:4d:f7:73:42:46]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 00:1f:27:54:dd:ef]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 00:1f:27:54:dd:e2]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 00:1e:4a:8f:df:d4]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 00:22:0d:47:49:84]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 00:1e:4a:8f:e3:64]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 13 00:1e:4a:8f:e3:63]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 14 00:1f:27:54:dd:e3]
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 15 00:1f:27:54:e0:43]
,D/QRemote ( 4763): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
,D/QRemote ( 4763): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
,I/QRemote ( 4763): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
I/QRemote ( 4763): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
,I/QRemote ( 4763): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
,D/QRemote ( 4763): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
,D/QRemote ( 4763): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
,D/DhcpStateMachine(  967): StoppedState
D/WifiStateMachine(  967): handleMessage: E msg.what=196614
D/WifiStateMachine(  967): processMsg: SupplicantStoppingState
,D/WifiStateMachine(  967): processMsg: DefaultState
D/WifiStateMachine(  967): handleMessage: X
,D/wpa_supplicant( 2047): netlink: Operstate: linkmode=0, operstate=6
,D/QRemote ( 4763): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/wpa_supplicant( 2047): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2047): nl80211: Unsubscribe mgmt frames handle 0xb7d80590 (mode change)
I/wpa_supplicant( 2047): wlan0: CTRL-EVENT-TERMINATING 
,D/wpa_supplicant( 2047): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
I/wpa_supplicant( 2047): [ITEC] Close WIFLUS socket interface - START
I/wpa_supplicant( 2047): [ITEC] - NOT INITIALIZED - DONE
D/WifiMonitor(  967): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
D/wpa_supplicant( 2047): Control interface directory not empty - leaving it behind
D/wpa_supplicant( 2047): Get randomness: len=20 entropy=0
I/bt_hci_bdroid( 1214): bt_hc_worker_thread exiting
D/WifiStateMachine(  967): handleMessage: E msg.what=147458
D/WifiStateMachine(  967): processMsg: SupplicantStoppingState
D/WifiStateMachine(  967): Supplicant connection lost
W/bt_userial( 1214): select_read return size <=0:0, exiting userial_read_thread
D/WifiMonitor(  967): WifiMonitorSingleton gotten
,I/bt_userial_vendor( 1214): device fd = 84 close
,D/Tethering(  967): InitialState.processMessage what=4
,D/Tethering(  967): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
,D/Tethering(  967): sendTetherStateChangedBroadcast 0, 0, 0
,D/BTSNOOP-DISP( 1214): btsnoop_close
I/GKI_LINUX( 1214): GKI_destroy_task: GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1214): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 1214): GKI_destroy_task: GKI_destroy_task(): task [BTU] terminated
,I/GKI_LINUX( 1214): GKI_freeze: GKI_freeze
,I/QRemote ( 4763): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
,D/PCSuite ( 4747): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:rfkill, action:3
,I/bt-btif ( 1214): HAL bt_hal_cbacks->adapter_state_changed_cb
,D/BluetoothServiceJni( 1214): adapter_state_change_callback: Status is: 0
D/BluetoothAdapterState( 1214): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,W/BluetoothAdapterService( 1214): Stopping service com.broadcom.bt.service.hfp.BrcmHeadsetService
,W/BluetoothAdapterService( 1214): Stopping service com.android.bluetooth.a2dp.A2dpService
D/BrcmHeadsetService( 1214): Received stop request...Stopping profile...
,W/BluetoothAdapterService( 1214): Stopping service com.android.bluetooth.hid.HidService
I/LGBluetoothHfpAdapter( 1214): [BTUI] LGBluetoothHfpAdapter cleanup
W/LGBluetoothHeadsetServiceJni( 1214): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 1214): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42bb61b0
,D/HeadsetStateMachine( 1214): Exit Disconnected: -1
,W/BluetoothAdapterService( 1214): Stopping service com.android.bluetooth.hdp.HealthService
D/UsbSettingsReceiver( 2613): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 2613): [AUTORUN] sys.usb.config = boot,adb
D/UsbSettingsReceiver( 2613): [AUTORUN] sys.usb.state = boot,adb
D/UsbSettingsReceiver( 2613): [AUTORUN] persist.sys.usb.config = boot,adb
,D/UsbSettingsReceiver( 2613): [AUTORUN] onReceive() : app userid = 0, current userid = 0
D/BluetoothHeadset( 1449): Proxy object disconnected
D/BluetoothHeadset(  967): Proxy object disconnected
,D/BluetoothHeadset( 1449): Proxy object disconnected
D/BluetoothHeadset( 1449): Proxy object disconnected
,W/BluetoothAdapterService( 1214): Stopping service com.android.bluetooth.pan.PanService
W/BluetoothAdapterService( 1214): Stopping service com.android.bluetooth.map.BluetoothMapService
,I/Config  ( 2613): getOperator() : OPEN
D/UsbSettingsControl( 2613): [AUTORUN] getUsbConnected() : connected=true
,I/ActivityManager(  967): Killing 4371:android.process.media/u0a23 (adj 15): empty #17
D/UsbSettingsReceiver( 2613): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 2613): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 2613): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 2613): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 2613): [AUTORUN] setTetherStatus() : status=false
D/A2dpService( 1214): Received stop request...Stopping profile...
D/LGBluetoothA2dpAdapter( 1214): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 1214): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 1214): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42bb61b0
W/BluetoothAdapterService( 1214): Stopping service com.android.bluetooth.gatt.GattService
D/A2dpStateMachine( 1214): Exit Disconnected: -1
W/BluetoothAdapterService( 1214): Stopping service com.broadcom.bt.service.sap.SapService
D/BluetoothA2dp(  967): Proxy object disconnected
D/BluetoothHeadset( 2613): Proxy object disconnected
D/HeadsetProfile( 2613): Bluetooth service disconnected
D/BluetoothAdapterService(1119576496)( 1214): Message: 1
D/BluetoothA2dp( 2613): Proxy object disconnected
D/A2dpProfile( 2613): Bluetooth service disconnected
D/BluetoothAdapterService(1119576496)( 1214): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
W/BluetoothAdapterService( 1214): Stopping service com.broadcom.bt.service.ftp.FTPService
D/BluetoothAdapterState( 1214): Stopping profile services that were post enabled
D/BluetoothAdapterService( 1214): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.hfp.BrcmHeadsetService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1214): Profile still running: com.broadcom.bt.service.sap.SapService
D/HidService( 1214): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1214): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42bb61b0
D/BluetoothInputDevice( 2613): Proxy object disconnected
D/HidProfile( 2613): Bluetooth service disconnected
D/HealthService( 1214): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1214): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42bb61b0
D/HeadsetStateMachine( 1214): Unbinding service...
D/HeadsetPhoneState( 1214): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1214): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 1214): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1214): [BTUI] listenForMultiSimPhoneState : start = false
W/Brcm_BluetoothHeadsetServiceJni( 1214): Cleaning up Bluetooth Handsfree Interface...
I/bt-btif ( 1214): cleanup
D/bt-btif ( 1214): btif_disable_service: Current Services:0x120108
W/Brcm_BluetoothHeadsetServiceJni( 1214): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 1214): [BTUI] LGBluetoothHfpAdapter cleanup
D/PanService( 1214): Received stop request...Stopping profile...
D/BluetoothTethering(  967): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering(  967): attempted to stop reverse tether with nothing tethered
D/BluetoothAdapterService( 1214): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42bb61b0
D/BluetoothPan( 2613): BluetoothPAN Proxy object disconnected
D/PanProfile( 2613): Bluetooth service disconnected
D/BluetoothPan(  967): BluetoothPAN Proxy object disconnected
D/BluetoothAdapterService(1119576496)( 1214): Message: 1
D/BluetoothAdapterService(1119576496)( 1214): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1214): onProfileServiceStateChange: serviceName=com.android.bluetooth.a2dp.A2dpService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1214): Profile still running: com.broadcom.bt.service.sap.SapService
D/BluetoothMapService( 1214): Received stop request...Stopping profile...
D/BluetoothMapService( 1214): stop()
D/BluetoothMapService( 1214,): MAP Service closeService in
D/LGBluetoothMapAdapter( 1214): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1214): MAP Service closeService out
D/BluetoothAdapterService( 1214): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42bb61b0
D/BtGatt.DebugUtils( 1214): handleDebugAction() action=null
D/BluetoothMap( 2613): Proxy object disconnected
D/MapProfile( 2613): Bluetooth service disconnected
D/BtGatt.GattService( 1214): Received stop request...Stopping profile...
D/BtGatt.GattService( 1214): stop()
D/BluetoothAdapterService( 1214): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42bb61b0
I/bt-btif ( 1214): cleanup
I/bt-btif ( 1214): ## A2DP STOP MEDIA TASK ##
I/GKI_LINUX( 1214): GKI_destroy_task: GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
D/bt-btif ( 1214): UIPC_Close : ch_id 5
D/bt-btif ( 1214): UIPC_Close : waiting for shutdown to complete
I/bt-btif ( 1214): UIPC SEND WAKE UP
I/bt-btif ( 1214): UIPC READ THREAD EXITING
I/bt-btif ( 1214): uipc_main_cleanup
I/bt-btif ( 1214): CLOSE CHANNEL 0
I/bt-btif ( 1214): CLOSE SERVER (FD 69)
D/bt-btif ( 1214): A2DP-CTRL-CHANNEL EVENT UIPC_CLOSE_EVT
I/bt-btif ( 1214): UIPC SEND WAKE UP
I/bt-btif ( 1214): CLOSE CHANNEL 1
I/bt-btif ( 1214): CLOSE CHANNEL 2
I/bt-btif ( 1214): CLOSE CHANNEL 3
I/bt-btif ( 1214): UIPC READ THREAD DONE
D/bt-btif ( 1214): UIPC_Close : shutdown complete
D/bt-btif ( 1214): MEDIA TASK EXITING
I/GKI_LINUX( 1214): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1214): GKI_destroy_task: GKI_destroy_task(): task [A2DP-MEDIA] terminated
D/bt-btif ( 1214): btif_disable_service: Current Services:0x120100
D/LGBluetoothAvrcpAdapter( 1214): [BTUI] cleanup
D/LGBluetoothAvrcpManager( 1214): [BTUI] terminateAvrcpManager
D/LGBluetoothAvrcpManager( 1214): [BTUI] cleanupPlayStatus() : mPlayStatus = 0
V/BluetoothAVRCP1.3ServiceJni( 1214): cleanupNativeAVRCP
I/bt-btif ( 1214): ## cleanup ##
D/bt-btif ( 1214): close_uinput
D/SapService( 1214): Received stop request...Stopping profile...
D/SapService( 1214): Stopping Bluetooth SapService
D/LGBluetoothSapAdapter( 1214): [BTUI] LGBluetoothSapAdapter cleanup
,D/LGBluetoothSapManager( 1214): [BTUI] terminateSapManager
,D/BluetoothAdapterService( 1214): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42bb61b0
D/LgeBluetoothSimManager( 1449): [BTUI] SAP_DISABLE_EVT
D/**BluetoothFTPService( 1214): Received stop request...Stopping profile...
D/**BluetoothFTPService( 1214): Stopping Bluetooth FTP Service
V/BluetoothFTPServiceJni( 1214): closeFtpServerNative
I/bt-btif ( 1214): cleanup
,D/bt-btif ( 1214): btif_disable_service: Current Services:0x120000
,D/BluetoothAdapterService( 1214): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42bb61b0
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e69a8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{434d8b98 u0 com.example.hello/.MainActivity t3}
D/BluetoothAdapterService(1119576496)( 1214): Message: 1
D/BluetoothAdapterService(1119576496)( 1214): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1214): onProfileServiceStateChange: serviceName=com.android.bluetooth.hid.HidService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1214): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothHidServiceJni( 1214): Cleaning up Bluetooth HID Interface...
I/bt-btif ( 1214): cleanup
W/bt-btif ( 1214): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 1214): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService(1119576496)( 1214): Message: 1
D/BluetoothAdapterService(1119576496)( 1214): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1214): onProfileServiceStateChange: serviceName=com.android.bluetooth.hdp.HealthService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1214): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothHealthServiceJni( 1214): Cleaning up Bluetooth Health Interface...
I/bt-btif ( 1214): cleanup
D/bt-btif ( 1214): Process name (droid.bluetooth)
D/bt-btif ( 1214): btif_disable_service: Current Services:0x120000
D/bt-btif ( 1214): btif_hl_disable
D/bt-btif ( 1214): btif_hl_signal_select_exit
D/bt-btif ( 1214): select unblocked ret=1
D/bt-btif ( 1214): btif_hl_select_wake_signaled, signal ret=1
D/bt-btif ( 1214): btif_hl_select_wake_signaled
D/bt-btif ( 1214): btif_hl_select_wake_reset
D/bt-btif ( 1214): btif_hl_select_wake_signaled, signal:2
D/bt-btif ( 1214): hl thread cleanup
D/bt-btif ( 1214): Exit hl_select_thread for btif_hl_signal_select_exit
W/BluetoothHealthServiceJni( 1214): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 1214): Cleaning up Bluetooth Health object
D/BluetoothAdapterService(1119576496)( 1214): Message: 1
D/BluetoothAdapterService(1119576496)( 1214): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1214): onProfileServiceStateChange: serviceName=com.android.bluetooth.pan.PanService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1214): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothPanServiceJni( 1214): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 1214): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService(1119576496)( 1214): Message: 1
D/BluetoothAdapterService(1119576496)( 1214): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1214): onProfileServiceStateChange: serviceName=com.android.bluetooth.map.BluetoothMapService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1214): Profile still running: com.broadcom.bt.service.sap.SapService
D/BluetoothMapService( 1214): cleanup()
D/BluetoothMapService( 1214): MAP Service closeService in
D/LGBluetoothMapAdapter( 1214): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1214): MAP Service closeService out
D/BluetoothAdapterService(1119576496)( 1214): Message: 1
D/BluetoothAdapterService(1119576496)( 1214): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1214): onProfileServiceStateChange: serviceName=com.android.bluetooth.gatt.GattService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1214): Profile still running: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1119576496)( 1214): Message: 1
D/BluetoothAdapterService(1119576496)( 1214): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1214): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.sap.SapService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1214): Profile still running: com.broadcom.bt.service.ftp.FTPService
W/BluetoothSAPServiceJni( 1214): ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
I/bt-btif ( 1214): cleanup
D/bt-btif ( 1214): btif_disable_service: Current Services,:0x100000
W/BluetoothSAPServiceJni( 1214): ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService(1119576496)( 1214): Message: 1
D/BluetoothAdapterService(1119576496)( 1214): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1214): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.ftp.FTPService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1214): All profile services stopped...
D/BluetoothAdapterState( 1214): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 1214): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1214): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  967): Message: 60
D/BluetoothManagerService(  967): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  967): Broadcasting onBluetoothStateChange(false) to 12 receivers.
D/BluetoothHeadset( 1449): onBluetoothStateChange: up=false
I/BluetoothAdapterState( 1214): Entering OffState
D/BluetoothFTPService( 1214): cleanup FTP Service
V/BluetoothFTPServiceJni( 1214): closeFtpServerNative
I/bt-btif ( 1214): cleanup
V/BluetoothFTPServiceJni( 1214): cleanupNative
W/BluetoothFTPServiceJni( 1214): Cleaning up Bluetooth FTP Server Interface...
W/BluetoothFTPServiceJni( 1214): Cleaning up Bluetooth FTP callback object
D/BluetoothFTPService( 1214): BluetoothFtpBinder.cleanup()
D/BluetoothFTPService( 1214): cleanup done
D/BluetoothHeadset( 1449): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1449): onBluetoothStateChange: up=false
D/BluetoothMap( 2613): onBluetoothStateChange: up=false
D/BluetoothA2dp( 2613): onBluetoothStateChange: up=false
D/AndroidRuntime( 4729): 
D/AndroidRuntime( 4729): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/BluetoothA2dp(  967): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 2613): onBluetoothStateChange: up=false
D/BluetoothPbap( 2613): onBluetoothStateChange: up=false
D/BluetoothHeadset(  967): onBluetoothStateChange: up=false
D/BluetoothHeadset( 2613): onBluetoothStateChange: up=false
D/AndroidRuntime( 4729): CheckJNI is OFF
D/BluetoothManagerService(  967): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  967): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothManagerService(  967): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@42c0eef0 mBinding = false
D/BluetoothManagerService(  967): Sending unbind request.
D/BluetoothManagerService(  967): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapterService(1119576496)( 1214): onUnbind, calling cleanup
D/BluetoothAdapterService(1119576496)( 1214): cleanup()
D/BluetoothAdapter( 1142): 1120307960: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapterService( 1214): Cleaning up adapter native....
I/bluedroid( 1214): cleanup 1
I/bt-btif ( 1214): btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
I/GKI_LINUX( 1214): GKI_destroy_task: GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
D/bt-btif ( 1214): btif_disassociate_evt: notify DISASSOCIATE_JVM
I/bt-btif ( 1214): HAL bt_hal_cbacks->thread_evt_cb
E/bt-gki  ( 1214): gki_pool_usage:  0: size     64 cur   0 max  12  total  48
E/bt-gki  ( 1214): gki_pool_usage:  1: size    288 cur   0 max   3  total  26
E/bt-gki  ( 1214): gki_pool_usage:  2: size    660 cur   0 max  23  total  45
E/bt-gki  ( 1214): gki_pool_usage:  3: size   4112 cur   0 max   3  total 200
E/bt-gki  ( 1214): gki_pool_usage:  4: size   8108 cur   0 max   0  total  20
E/bt-gki  ( 1214): pool:  4: not allocated
E/bt-gki  ( 1214): gki_pool_usage:  5: size    748 cur   0 max   0  total  64
E/bt-gki  ( 1214): pool:  5: not allocated
D/LGBluetoothAPIService( 1156): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
E/bt-gki  ( 1214): gki_pool_usage:  6: size    26,8 cur   0 max   0  total  60
E/bt-gki  ( 1214): pool:  6: not allocated
E/bt-gki  ( 1214): gki_pool_usage:  7: size  10264 cur   0 max   0  total   2
E/bt-gki  ( 1214): pool:  7: not allocated
E/bt-gki  ( 1214): gki_pool_usage:  8: size    128 cur   3 max   3  total  30
E/bt-gki  ( 1214): gki_pool_usage:  9: size   8192 cur   0 max   0  total   5
E/bt-gki  ( 1214): pool:  9: not allocated
D/bt-btif ( 1214): btif task exiting
I/GKI_LINUX( 1214): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 1214): GKI_destroy_task: GKI_destroy_task(): task [BTIF] terminated
I/GKI_LINUX( 1214): GKI_destroy_task: GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1214): GKI_destroy_task: GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1214): GKI_destroy_task: GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1214): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 1214): GKI_exit_task: GKI_exit_task 1 done
I/GKI_LINUX( 1214): GKI_exit_task: GKI_exit_task 0 done
D/LGBluetoothAPIService( 1156): Message: 2
D/LGBluetoothAPIService( 1156): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@4336c6a0 mBinding = false
D/LGBluetoothAPIService( 1156): Sending unbind request.
D/bt-btif ( 1214): btif_shutdown_bluetooth done
I/BluetoothServiceJni( 1214): cleanupNative: return from cleanup
D/BluetoothAdapterService( 1214): Done cleaning up adapter native....
W/LGBluetoothServiceJni( 1214): Cleaning up Bluetooth Service callback object
D/dalvikvm( 4729): Trying to load lib libjavacore.so 0x0
D/LGBluetoothSettingsDBObserver( 1214): [BTUI] unregister observer for LG device name DB
D/BluetoothAdapterService(1119576496)( 1214): cleanup() done
E/LGBluetoothEventManager( 2613): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothEventManager( 2613): [BTUI] clear device connection state
D/BluetoothAdapterService(1119576496)( 1214): ****onDestroy()********
D/BtGatt.GattService( 1214): cleanup()
W/bt-btif ( 1214): GATTC Module not enabled/already disabled
W/bt-btif ( 1214): GATTS Module not enabled/already disabled
D/dalvikvm( 4729): Added shared lib libjavacore.so 0x0
D/LGBluetoothAPIServer( 1214): [BTUI] onUnbind()
D/LGBluetoothAPIServer( 1214): [BTUI] cleanup() done
D/LGBluetoothAPIServer( 1214): [BTUI] onDestroy()
D/dalvikvm( 4729): Trying to load lib libnativehelper.so 0x0
W/ContextImpl( 2613): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:156 com.android.settings.bluetooth.DockEventReceiver.onReceive:123 
D/dalvikvm( 4729): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4729): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/DockEventReceiver( 2613): finishStartingService: stopping service
V/BluetoothPbapReceiver( 1214): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1214): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1214): ***********state = 10
D/BluetoothPermissionRequest( 2613): onReceive
E/LGBluetoothUtils( 2613): [BTUI] FileNotFoundException: readPropertyjava.io.FileNotFoundException: /data/misc/bluedroid/bluetooth_property.conf: open failed: ENOENT (No such file or directory)
D/BluetoothDiscoverableTimeoutReceiver( 2613): cancelDiscoverableAlarm(): Enter
D/LGBluetoothResetSettingReceiver( 2613): return without doing reset settings.
D/LGBluetoothProfileConnectionReceiver( 2613): [BTUI] STATE_OFF : reset connected device information - BluetoothSettings
D/dalvikvm( 4729): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,D/WifiStateMachine(  967): setWifiState: disabled
,D/WifiOffDelayIfNotUsed(  967): stopMonitoring
D/LGBluetoothProfileConnectionReceiver_EasySetting( 4712): [BTUI] STATE_OFF : reset connected device information EasySettings
D/WifiActivationWhileCharging(  967): register : WIFI_ACTIVATION_WHILE_CHARGING_OFF[1]
,E/WifiStateMachine(  967): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  967): useWiFiOffloading() : false
E/WifiStateMachine(  967): CONFIG_LGE_WLAN_PATH : true
,D/AuthorizationBluetoothService( 1538): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,D/LGDMClient( 2931): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/WifiStateMachine(  967): transitionTo: destState=InitialState
D/WifiStateMachine(  967): handleMessage: new destination call exit/enter
D/WifiStateMachine(  967): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  967): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine(  967): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine(  967): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
,D/WifiStateMachine(  967): invokeEnterMethods: InitialState
,V/WfdStateTracker( 1156): WfdStateTracker handleDirectStateChangedEvent: 0
,D/LGDMClient( 2931): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
,W/Settings( 1424): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/WifiServiceExtension(  967): WIFI_STATE_CHANGED_ACTION [1]
I/WifiServiceExtension(  967): batteryPsActivateMsgHandler : state:0 event:1
,I/WifiServiceExtension(  967): batteryPsActivateMsgHandler : this is not treated
E/Parcel  (  545): Reading a NULL string not supported here.
E/Parcel  (  545): Reading a NULL string not supported here.
E/Parcel  (  545): Reading a NULL string not supported here.
E/Parcel  (  545): Reading a NULL string not supported here.
,E/Parcel  (  545): Reading a NULL string not supported here.
E/Parcel  (  545): Reading a NULL string not supported here.
,E/Parcel  (  545): Reading a NULL string not supported here.
I/ActivityManager(  967): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4792 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/HyLog   ( 4792): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4792): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4792): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/LGDMSGCM( 4792): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.wifi.supplicant.CONNECTION_CHANGE
I/PCSuite ( 4747): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 4747): [StartReceiver][getUpdateNecessity]update = false
D/PCSuite ( 4747): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/ContextImpl( 4792): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/ActivityManager(  967): Killing 4491:com.google.android.partnersetup/u0a9 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e69a8 stackId=1, 2 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{434d8b98 u0 com.example.hello/.MainActivity t3}
,E/memtrack( 4729): Couldn't load memtrack module (No such file or directory)
,E/android.os.Debug( 4729): failed to load memtrack module: -2
,D/AndroidRuntime( 4729): Calling main entry com.android.commands.pm.Pm
,I/ActivityManager(  967): Force stopping com.example.hello appid=10312 user=-1: uninstall pkg
,I/ActivityManager(  967): Killing 4623:com.example.hello/u0a312 (adj 0): stop com.example.hello
,W/ActivityManager(  967): Force removing ActivityRecord{434d8b98 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{434d8b98 u0 com.example.hello/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{434d8b98 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,I/MDM     (  967):  removeProcessLocked app.persistent = false callerWillRestart = false
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{434e69a8 stackId=1, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: No more activities go home
,V/ActivityManager(  967): moveHomeStack:
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea3408 stackId=0, 1 tasks}
,I/WindowState(  967): WIN DEATH: Window{4355dc78 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  967): Client connection lost with reason: 4
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,W/PackageSettings(  967): Skipping PackageSetting{42fecf78 com.test.thalitest/10304} due to missing metadata
,D/WifiStateMachine(  967): handleMessage: X
,D/WifiStateMachine(  967): handleMessage: E msg.what=131101
D/WifiStateMachine(  967): processMsg: InitialState
D/WifiStateMachine(  967): processMsg: DefaultState
,D/WifiStateMachine(  967): handleMessage: X
,V/ActivityManager(  967): Moving to RESUMED: ActivityRecord{42eb38d8 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  967): resumeTopActivityLocked: Resumed ActivityRecord{42eb38d8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  967): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42ea3408 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42eb38d8 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1489): [Launcher.java:4947:onStart()]onStart
I/ActivityManager(  967): Force stopping com.example.hello appid=10312 user=0: pkg removed
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea3408 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42eb38d8 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1489): [Launcher.java:717:onResume()]onResume
V/ActivityManager(  967): Moving to DESTROYING: ActivityRecord{42c14e88 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
,D/KeyguardModel( 1142): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,I/InputReader(  967): Reconfiguring input devices.  changes=0x00000010
,W/System.err( 2673): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
,W/GeofencerStateMachine( 1424): Ignoring removeGeofence because network location is disabled.
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/[LGHome]EVENT( 1489): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
W/System.err( 2673): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2673): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2673): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2673): 	at android.os.Handler.handleCallback(Handler.java:733)
D/PhoneApp( 1449): getIsInUseVoLTE : false
W/System.err( 2673): 	at android.os.Handler.dispatchMessage(Handler.java:95)
D/UsbSettings( 2613): [AUTORUN] onDestroy() : getDefaultFunction =boot
W/System.err( 2673): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2673): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2673): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2673): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2673): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2673): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 2673): 	at dalvik.system.NativeStart.main(Native Method)
I/[LGHome]LGActivityUtil( 1489): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
V/UsbSettings( 2613): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2613): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
V/UsbSettings( 2613): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/AppUp4:Utils( 3753): [getPackageName] uri : package:com.example.hello
D/AppUp4  ( 3753): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
E/SlideAside( 4129): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
I/AppUp4  ( 3753):  isExcludedPackage  packagename = com.example.hello
I/SlideAside( 4129): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.example.hello
,D/AppUp4  ( 3753):  isExcludedPackage TRUE : com.example.hello
,I/[LGHome]EVENT( 1489): [Launcher.java:868:onResume()]onResume end
,D/dalvikvm( 2689): GC_EXPLICIT freed 5648K, 27% free 18228K/24832K, paused 1ms+2ms, total 64ms
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
,D/[BNRAppListMgrReceiver]( 4523): android.intent.action.PACKAGE_REMOVED : com.example.hello
,I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
V/ActivityManager(  967): Moving to DESTROYED: ActivityRecord{42c14e88 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea3408 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42eb38d8 u0 com.lge.launcher2/.Launcher t1}
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/dalvikvm(  967): GC_EXPLICIT freed 1576K, 9% free 29453K/32288K, paused 4ms+11ms, total 124ms
,D/dalvikvm(  967): WAIT_FOR_CONCURRENT_GC blocked 94ms
I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/[LGHome]EVENT( 1489): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "sms"
,W/Binder  ( 1323): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1323): java.lang.NullPointerException
W/Binder  ( 1323): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1323): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1323): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1323): 	at dalvik.system.NativeStart.run(Native Method)
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/InputMethodManagerService(  967): IME STATUS OFF
W/InputMethodManagerService(  967): Got RemoteException sending setActive(false) notification to pid 4623 uid 10312
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
,I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "smsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/administrator(  967): Handling package changes for user 0
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mms"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/VoicemailCleanupService( 1736): Cleaning up data for package: com.example.hello
,I/PackageManager(  967):   Action: "android.intent.action.SENDTO"
I/PackageManager(  967):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  967):   Scheme: "mmsto"
I/PackageManager(  967): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,I/PackageChangeReceiver( 4537): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,D/KeyguardModel( 1142): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
I/ActivityManager(  967): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4821 uid=10090 gids={50090}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,D/dalvikvm(  276): GC_EXPLICIT freed 46K, 34% free 16472K/24832K, paused 1ms+2ms, total 17ms
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,D/PackageIntentReceiver( 2613): Not supported Hotkey customization function 
,D/HyLog   ( 4821): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4821): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4821): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HideNavigationAppsReceiver( 2613): Receive package name : com.example.hello
,D/dalvikvm(  276): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
,D/HideNavigationAppsReceiver( 2613): Delete mPackageMame : com.example.hello
,D/BackupManagerService(  967): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
I/InteractionManagerConfigurator(  967): updateIntentFilterConfig
,I/InteractionManagerConfigurator(  967): com.example.hello isn't inclued in dragdropPackageList
,V/BackupManagerService(  967): removePackageParticipantsLocked: uid=10312 #1
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
I/LockScreenSettings( 4821): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
D/dalvikvm(  276): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 14ms
,D/KeyguardModel( 1142): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1142): createShortcutInfo...
,I/IcingCorporaProvider( 2689): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
D/KeyguardModel( 1142): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1142): createShortcutInfo...
,D/dalvikvm( 1489): GC_FOR_ALLOC freed 5592K, 9% free 60773K/66628K, paused 19ms, total 21ms
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
I/ActivityManager(  967): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4835 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/HyLog   ( 4835): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4835): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4835): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 1142): GC_FOR_ALLOC freed 6915K, 11% free 70768K/78644K, paused 24ms, total 24ms
,D/KeyguardModel( 1142): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1142): createShortcutInfo...
,D/dalvikvm(  967): GC_EXPLICIT freed 548K, 9% free 29426K/32288K, paused 3ms+11ms, total 205ms
W/ContextImpl( 4835): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2424 
,I/dalvikvm( 4321): Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
W/dalvikvm( 4321): VFY: unable to resolve virtual method 329: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,D/dalvikvm( 4321): VFY: replacing opcode 0x6e at 0x0013
,E/NetworkScheduler.SchedulerReceiver( 1538): Invalid parameter app
,E/NetworkScheduler.SchedulerReceiver( 1538): Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/ActivityManager(  967): Killing 3423:com.google.android.gms.wearable/u0a6 (adj 15): empty #17
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,D/KeyguardModel( 1142): handleShortcutListChanged...
,D/KeyguardModel( 1142): handleShortcutListChanged...
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,E/[LGHome]NumberBadge( 1489): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
I/ActivityManager(  967): Killing 4306:com.android.defcontainer/u0a4 (adj 15): empty #17
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea3408 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42eb38d8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea3408 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42eb38d8 u0 com.lge.launcher2/.Launcher t1}
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,D/ChimeraCfgMgr( 1860): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1860): Module APK com.google.android.play.games already loaded
,D/PackageBroadcastService( 1860): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,D/AccountUtils( 1860): Clearing selected account for com.example.hello
,D/PackageIntentReceiver( 2613): Not supported Hotkey customization function 
D/ChimeraCfgMgr( 1860): Loading module com.google.android.gms.games from APK com.google.android.play.games
,D/ChimeraModuleLdr( 1860): Module APK com.google.android.play.games already loaded
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/ActivityManager(  967): Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4861 uid=10065 gids={50065, 1028, 4002}
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
I/LocationSettingsChecker( 1860): Removing dialog suppression flag for package com.example.hello
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
D/HyLog   ( 4861): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4861): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4861): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,I/ActivityManager(  967): Delaying start of: ServiceRecord{433ee960 u0 com.google.android.gms/.wearable.service.WearableControlService}
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
D/AndroidRuntime( 4729): Shutting down VM
D/dalvikvm( 4729): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 1ms+0ms, total 2ms
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,I/ConfigFetchService( 1860): onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
,I/IcingCorporaProvider( 2689): UpdateCorporaTask done [took 214 ms] updated apps [took 214 ms] 
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,D/Documents( 4861): Loading roots for com.android.externalstorage.documents
,I/PeopleContactsSync( 1860): CP2 sync disabled
,I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
D/WeatherAncestor( 1824): 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:33:53
,D/UpdateThreadPoolManager( 1824): 2 : This is isUpdating : false
I/ActivityManager(  967): Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4881 uid=10005 gids={50005, 1028, 1015, 1023}
,I/ActivityManager(  967): Killing 4763:com.lge.qremote/u0a96 (adj 15): empty #17
D/WeatherQuickCover( 1824): 2 : quick cover state : opened : 0
D/WeatherService( 1824): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
D/WeatherService( 1824): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherAncestor( 1824): 2 : shouldTimeTickRegistered().........
W/ContextImpl( 1824): Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
D/WeatherAncestor( 1824): 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 15:33:53
D/WeatherService( 1824): 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
D/WeatherQuickCover( 1824): 2 : quick cover state : opened : 0
,D/Weather.Utils( 1824): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1824): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1824): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/WeatherService( 1824): 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,D/WeatherService( 1824): 2 : requestRefreshAppWidget, isUpdateStart : false
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea3408 stackId=0, 1 tasks}
,D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42eb38d8 u0 com.lge.launcher2/.Launcher t1}
D/UpdateThreadPoolManager( 1824): 2 : This is isUpdating : false
D/WeatherService( 1824): 2 : requestRefreshAppWidget, isUpdating : false
D/WeatherAncestor( 1824): 2 : buildUpdate, appWidgetId: 1
D/WeatherReflect( 1824): 2 : Map key string is -2
D/lim     ( 1824): 2 : time = 15:33
I/WeatherReflect( 1824): Model Name : LG-D802
D/WeatherTheme( 1824): 2 : exactly same view!
D/WeatherTheme( 1824): 2 : widgetId = 1 : widgetSize = 1 : Do not refresh any widget.
D/WeatherQuickCover( 1824): 2 : quick cover state : opened : 0
D/Weather.Utils( 1824): 2 : Utils getTopActivity com.lge.launcher2 / true
D/WeatherService( 1824): 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,D/WeatherService( 1824): 2 : shouldTimeTickRegistered : true - home screen widget is shown.
D/dalvikvm( 1860): GC_CONCURRENT freed 1593K, 22% free 19608K/24832K, paused 3ms+15ms, total 70ms
,D/dalvikvm( 1860): WAIT_FOR_CONCURRENT_GC blocked 39ms
D/dalvikvm( 1860): WAIT_FOR_CONCURRENT_GC blocked 39ms
,I/ActivityManager(  967): Killing 4733:com.lge.wireless_storage/u0a101 (adj 15): empty #17
I/Icing   ( 1860): doRemovePackageData com.example.hello
D/dalvikvm( 1860): WAIT_FOR_CONCURRENT_GC blocked 39ms
D/dalvikvm( 1860): WAIT_FOR_CONCURRENT_GC blocked 40ms
D/GOOGLEHELP_CompatibleDatabase( 1860): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
D/GOOGLEHELP_CompatibleDatabase( 1860): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
D/dalvikvm( 1860): WAIT_FOR_CONCURRENT_GC blocked 39ms
D/gH_MetricsDatabase( 1860): 0 metrics were deleted when clearing package com.example.hello.
,D/GOOGLEHELP_CompatibleDatabase( 1860): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
W/BaseAppContext( 1860): Using Auth Proxy for data requests.
D/GOOGLEHELP_CompatibleDatabase( 1860): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1860): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1860): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea3408 stackId=0, 1 tasks}
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42eb38d8 u0 com.lge.launcher2/.Launcher t1}
,D/dalvikvm( 1489): GC_FOR_ALLOC freed 4810K, 9% free 61981K/67652K, paused 18ms, total 19ms
D/HyLog   ( 4881): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4881): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4881): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,W/BaseAppContext( 1860): Using Auth Proxy for data requests.
D/GOOGLEHELP_CompatibleDatabase( 1860): Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
,D/GOOGLEHELP_CompatibleDatabase( 1860): Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
,D/GOOGLEHELP_CompatibleDatabase( 1860): Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
D/GOOGLEHELP_CompatibleDatabase( 1860): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
D/GOOGLEHELP_CompatibleDatabase( 1860): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
,D/GOOGLEHELP_CompatibleDatabase( 1860): Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
,D/ExternalStorage( 4881): After updating volumes, found 1 active roots
,D/Documents( 4861): Updating roots due to change at content://com.android.externalstorage.documents/root
,I/ActivityManager(  967): Timeline: Activity_windows_visible id: ActivityRecord{42eb38d8 u0 com.lge.launcher2/.Launcher t1} time:49917
,D/Documents( 4861): Loading roots for com.android.providers.downloads.documents
,I/ActivityManager(  967): Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4893 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,I/ActivityManager(  967): Killing 4712:com.lge.settings.easy/1000 (adj 15): empty #17
,I/ActivityManager(  967): resumeTopActivitiesLocked(): target Stack:ActivityStack{42ea3408 stackId=0, 1 tasks}
,D/HyLog   ( 4893): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/HyLog   ( 4893): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4893): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/ActivityManager(  967): resumeTopActivityLocked: Top activity resumed ActivityRecord{42eb38d8 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  967): Delaying start of: ServiceRecord{4360b738 u0 com.android.providers.downloads/.DownloadService}
,I/ActivityManager( 1489): Timeline: Activity_idle id: android.os.BinderProxy@42b8d6a0 time:49965
,D/Documents( 4861): Loading roots for com.android.providers.media.documents
,D/Documents( 4861): Loading roots for com.google.android.apps.docs.storage
,D/Documents( 4861): Update found 7 roots in 201ms
,D/Documents( 4861): Loading roots for com.android.externalstorage.documents
D/Documents( 4861): Used cached roots for com.android.providers.downloads.documents
,D/Documents( 4861): Used cached roots for com.android.providers.media.documents
D/Documents( 4861): Used cached roots for com.google.android.apps.docs.storage
,D/Documents( 4861): Update found 7 roots in 4ms
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  267): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0

```
