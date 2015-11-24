#### Test 513350288bfb88c_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1937): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1937): launchTask
W/dalvikvm( 1937): VFY: unable to find class referenced in signature (Landroid/net/Network;)
D/ChimeraCfgMgr( 1937): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1937): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1937): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1937): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1937): Failed to find package metadata for com.test.thalitest
D/Vision  ( 1937): No vision deps
V/ConfigFetchTask( 1937): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1XQ1P_6NSiK8Z8fA91FIERo9fpbmbvaNvzfhtK38p1VJJz0peIw0z9pApsGLqVPM2-gCgZK8zcqzRHARa7qhdQZ9DYA6GJWKzhh3oJAbLD-8XKAMWtJ6GbABiveXumh30GN1Auo50uEkkHEz0x6pWW-2GSGbhXw1RjA5wx75e6cidjsYLtxgr9O2wDDlV99FzypRqqI
I/GoogleURLConnFactory( 1937): Using platform SSLCertificateSocketFactory
W/BaseAppContext( 1937): Using Auth Proxy for data requests.
W/BaseAppContext( 1937): Using Auth Proxy for data requests.
I/PeopleContactsSync( 1937): CP2 sync disabled
I/dalvikvm( 1937): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1937): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1937): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1937): Using Auth Proxy for data requests.
W/BaseAppContext( 1937): Using Auth Proxy for data requests.
W/BaseAppContext( 1937): Using Auth Proxy for data requests.
W/BaseAppContext( 1937): Using Auth Proxy for data requests.
E/DataScheduler( 1937): isDataSchedulerEnabled():false
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
W/ConfigFetchTask( 1937): exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
I/ConfigFetchService( 1937): fetch service done; releasing wakelock
I/ConfigFetchService( 1937): stopping self
W/GAV2    ( 4117): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  966): Killing 3439:com.android.calendar/u0a15 (adj 15): empty #17
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ab158 stackId=1, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{431dc408 u0 com.android.settings/.UsbSettings t2}
D/ChimeraCfgMgr( 1937): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1937): Module APK com.google.android.play.games already loaded
D/dalvikvm( 1937): GC_CONCURRENT freed 1498K, 26% free 18466K/24832K, paused 3ms+5ms, total 42ms
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Icing   ( 1937): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 293 plugged : true isCharging : false
D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  966): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 292 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/WifiController(  966): battery changed pluggedType: 2
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/Icing   ( 1937): Loaded CLD2 Version V2.0 - 20141016
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1937): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/BatteryObserver( 1155): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AndroidRuntime( 4187): 
D/AndroidRuntime( 4187): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4187): CheckJNI is OFF
D/dalvikvm( 4187): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4187): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4187): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4187): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4187): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4187): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 4187): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4187): failed to load memtrack module: -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 4187): Calling main entry com.android.commands.am.Am
I/ActivityManager(  966): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from pid 4187
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ab158 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (246 us)
V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{431dc408 u0 com.android.settings/.UsbSettings t2}
D/ActivityManager(  966): resumeTopActivityLocked: Pausing null
V/ActivityManager(  966): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  966): startService SlideAside
W/ContextImpl(  966): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  966): setFocusedStack: mFocusedStack=ActivityStack{432ab158 stackId=1, 2 tasks}
D/AndroidRuntime( 4187): Shutting down VM
D/UsbSettingsControl( 2539): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2539): [AUTORUN] onPause() : mActiveCurrentFunction = boot
D/ActivityManager(  966): allPausedActivitiesComplete: r=ActivityRecord{431dc408 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{431dc408 u0 com.android.settings/.UsbSettings t2} (pause complete)
D/dalvikvm( 4187): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ab158 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Restarting ActivityRecord{44d8f288 u0 com.test.thalitest/.MainActivity t3}
I/SlideAside( 3563): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
I/ActivityManager(  966): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4207 uid=10304 gids={50304, 3003, 3001, 3002, 1028, 1015}
I/SlideAside( 3563): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
V/ActivityManager(  966): Moving to RESUMED: ActivityRecord{44d8f288 u0 com.test.thalitest/.MainActivity t3} (starting new instance)
D/SlideAside( 3563): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.test.thalitest (filtered)
D/HyLog   ( 4207): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4207): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4207): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4207): Binding Chromium to the background looper Looper (main, tid 1) {42814a08}
I/chromium( 4207): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4207): Initializing chromium process, renderers=0
W/chromium( 4207): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4207): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4207): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4207): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4207): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4207): Remote Branch: 
I/Adreno-EGL( 4207): Local Patches: 
I/Adreno-EGL( 4207): Reconstruct Branch: 
I/dalvikvm( 4207): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4207): VFY: unable to resolve virtual method 217: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4207): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4207): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4207): VFY: unable to resolve virtual method 212: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4207): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4207): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4207): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4207): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4207): VFY: unable to resolve virtual method 270: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4207): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4207): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4207): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4207): VFY: unable to resolve virtual method 228: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4207): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4207): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4207): VFY: unable to resolve virtual method 233: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4207): VFY: replacing opcode 0x6e at 0x0000
D/SystemWebViewEngine( 4207): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4207): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
,W/BaseRuntimeLoader( 4207): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4207): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4207): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4207): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4207): Enabling debug mode 0
,W/AwContents( 4207): nativeOnDraw failed; clearing to background color.
,I/ActivityManager( 4207): Timeline: Activity_idle id: android.os.BinderProxy@428161d8 time:110302
,I/ActivityManager(  966): Displayed com.test.thalitest/.MainActivity: +437ms
,D/JsMessageQueue( 4207): Set native->JS mode to OnlineEventsBridgeMode
,D/dalvikvm( 4207): Trying to load lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4281a8a8
,D/dalvikvm( 4207): Added shared lib /data/app-lib/com.test.thalitest-1/libjxcore.so 0x4281a8a8
,D/jxcore_app_log( 4207): JniHelper::setJavaVM(0x416df838), pthread_self() = 1638249392
D/JX-Cordova( 4207): jxcore cordova android initializing
I/dalvikvm( 4207): Could not find method android.bluetooth.BluetoothAdapter.isMultipleAdvertisementSupported, referenced from method io.jxcore.node.BtConnectorHelper.isBLEAdvertisingSupported
W/dalvikvm( 4207): VFY: unable to resolve virtual method 52: Landroid/bluetooth/BluetoothAdapter;.isMultipleAdvertisementSupported ()Z
D/dalvikvm( 4207): VFY: replacing opcode 0x6e at 0x0045
,I/ActivityManager(  966): Timeline: Activity_windows_visible id: ActivityRecord{44d8f288 u0 com.test.thalitest/.MainActivity t3} time:110641
,D/UsbSettings( 2539): [AUTORUN] onStop()
D/ActivityManager(  966): no-history finish of ActivityRecord{431dc408 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  966): Finishing activity token=Token{431dc570 ActivityRecord{431dc408 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  966): Moving to FINISHING: ActivityRecord{431dc408 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{44d8f288 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{431dc408 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
,V/ActivityManager(  966): Moving to STOPPED: ActivityRecord{431dc408 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 293 plugged : true isCharging : false
D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiController(  966): battery changed pluggedType: 2
,D/dalvikvm( 4207): GC_CONCURRENT freed 2873K, 13% free 21750K/24832K, paused 2ms+3ms, total 51ms
,D/dalvikvm( 4207): WAIT_FOR_CONCURRENT_GC blocked 31ms
,I/dalvikvm-heap( 4207): Grow heap (frag case) to 23.507MB for 98002-byte allocation
,D/dalvikvm( 4207): GC_FOR_ALLOC freed 193K, 13% free 21773K/24928K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4207): Grow heap (frag case) to 23.577MB for 146998-byte allocation
,D/dalvikvm( 4207): GC_FOR_ALLOC freed 260K, 13% free 21817K/25072K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4207): Grow heap (frag case) to 23.689MB for 220492-byte allocation
,D/dalvikvm( 4207): GC_FOR_ALLOC freed 380K, 14% free 21887K/25288K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4207): Grow heap (frag case) to 23.864MB for 330734-byte allocation
,D/dalvikvm( 4207): GC_FOR_ALLOC freed 592K, 15% free 21998K/25612K, paused 21ms, total 22ms
,I/dalvikvm-heap( 4207): Grow heap (frag case) to 24.128MB for 496096-byte allocation
,D/dalvikvm( 4207): GC_FOR_ALLOC freed 879K, 16% free 22176K/26100K, paused 22ms, total 22ms
,D/dalvikvm( 4207): GC_FOR_ALLOC freed 1302K, 15% free 22438K/26100K, paused 22ms, total 22ms
,I/dalvikvm-heap( 4207): Grow heap (frag case) to 25.150MB for 1116206-byte allocation
,D/dalvikvm( 4207): GC_CONCURRENT freed 1861K, 17% free 22840K/27192K, paused 1ms+3ms, total 40ms
,D/dalvikvm( 4207): GC_FOR_ALLOC freed 245K, 17% free 22749K/27192K, paused 21ms, total 21ms
,I/dalvikvm-heap( 4207): Grow heap (frag case) to 25.987MB for 1674304-byte allocation
,D/dalvikvm( 4207): GC_CONCURRENT freed 1538K, 20% free 23334K/28828K, paused 2ms+2ms, total 26ms
,D/dalvikvm( 4207): GC_FOR_ALLOC freed 1522K, 19% free 23450K/28828K, paused 25ms, total 28ms
,I/dalvikvm-heap( 4207): Grow heap (frag case) to 27.469MB for 2511452-byte allocation
,D/dalvikvm( 4207): GC_CONCURRENT freed 374K, 18% free 25758K/31284K, paused 2ms+2ms, total 38ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 4207): GC_FOR_ALLOC freed 4309K, 22% free 24409K/31284K, paused 46ms, total 46ms
,I/dalvikvm-heap( 4207): Grow heap (frag case) to 29.603MB for 3767174-byte allocation
,D/dalvikvm( 4207): GC_CONCURRENT freed 367K, 21% free 27935K/34964K, paused 3ms+3ms, total 46ms
,W/jxcore-log( 4207): Initializing JXcore engine
,W/jxcore-log( 4207): JXcore engine is ready
,W/jxcore-log( 4207): Starting JXcore engine
,W/jxcore-log( 4207): Platform android
W/jxcore-log( 4207): 
,W/jxcore-log( 4207): Process ARCH arm
W/jxcore-log( 4207): 
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.556595 Y: -0.379913 Z: 9.740692 
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.558807 Y: -0.397659 Z: 9.737366 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.556595 .y:-0.379913 .z:9.740692
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.556610 Y: -0.404343 Z: 9.725189 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.556610 .y:-0.404343 .z:9.725189
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
I/jxcore-log( 4207): JXcore Cordova bridge is ready!
I/jxcore-log( 4207): 
W/jxcore-log( 4207): JXcore engine is started
I/ActivityManager(  966): Killing 3381:com.google.android.music:main/u0a107 (adj 15): empty #17
I/chromium( 4207): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
F/ActivityManager(  966): Service ServiceRecord{43272be0 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{42bf6eb0 3381:com.google.android.music:main/u0a107} not same as in map: null
I/chromium( 4207): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
F/ActivityManager(  966): Service ServiceRecord{43268628 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{42bf6eb0 3381:com.google.android.music:main/u0a107} not same as in map: null
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ab158 stackId=1, 2 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Top activity resumed ActivityRecord{44d8f288 u0 com.test.thalitest/.MainActivity t3}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1155): usb Uevent not necessary.
I/chromium( 4207): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot call method 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/jxcore-log( 4207): Toggling radios to true
I/jxcore-log( 4207): 
D/BluetoothManagerService(  966): Message: 20
D/BluetoothManagerService(  966): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@44c40300:true
D/BluetoothAdapter( 4207): enable(): BT is already enabled..!
I/GAV2    ( 4117): Thread[GAThread,5,main]: No campaign data found.
,I/ConfigService( 1538): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BluetoothManagerService(  966): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,I/jxcore-log( 4207): Got Device Bluetooth address: 34:FC:EF:9D:93:0B
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): my name is : LGE-LG-D802_PT2477
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): attempting to connect to test coordinator
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): check test folder
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): found test : ./testFindPeers.js
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): found test : ./testReConnect.js
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): found test : ./testSendData.js
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): Test app app.js loaded
I/jxcore-log( 4207): 
,I/Choreographer( 4207): Skipped 114 frames!  The application may be doing too much work on its main thread.
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/chromium( 4207): [INFO:CONSOLE(51)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (51)
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1217): Disconnected process message: 10
,D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 294 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/WifiController(  966): battery changed pluggedType: 2
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 293 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368020032, nextTick: 60001, mDrawingTime: 0
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368020056, nextTick: 59977, mDrawingTime: 0
,I/jxcore-log( 4207): BLE advertisement not supported: Build version is 19
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,E/ThermalEngine(  284): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/WifiController(  966): battery changed pluggedType: 2
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 294 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/Finsky  ( 3743): [342] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  ( 3743): [1] 5.onFinished: Installation state replication succeeded.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.550476 Y: -0.391724 Z: 9.721939 
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.566025 Y: -0.389496 Z: 9.770767 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.550476 .y:-0.391724 .z:9.721939
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.570267 Y: -0.379074 Z: 9.742645 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.570267 .y:-0.379074 .z:9.742645
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/dalvikvm(  966): Jit: resizing JitTable from 8192 to 16384
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1155): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiController(  966): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
D/HeadsetStateMachine( 1217): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 294 plugged : true isCharging : false
I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,I/PowerManagerService(  966): Going to sleep due to screen timeout...
,D/KnockOnPowerController(  966): [updateScreenState] screen on = false
,D/KnockOnPowerController(  966): [setProximitySensorEnabled] enable = false
,I/qcom_sensors_hal(  966): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x1
,I/qcom_sensors_hal(  966): _hal_sensors_batch: period_ns=200000000 sns_hndl: 35 timeout: 0 flags:0x0
,I/qcom_sensors_hal(  966): _hal_sensors_flush: handle=35
I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=35, enabled=1
,I/qcom_sensors_hal(  966): _hal_sensors_activate: active_sensors mask=0x400000001 handle=35
,D/KnockOnPowerController(  966): [setProximitySensorEnabled] enable = true
I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=35, Initialized the timestamp 
D/qcom_sensors_hal(  966): hal_schedule_acquire_resources: Resetting acquire resources timer for 10000 usec. old_value = 6059 usec
,D/qcom_sensors_hal(  966): hal_acquire_resources
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,I/qcom_sensors_hal(  966): hal_acquire_resources, found active sensor handle=35, sample_rate=20 report_rate=0 WuFF=0 batched=0
D/qcom_sensors_hal(  966): hal_apply_rate: handle 35, sample rate:20 report rate:0 WuFF:0 buffering:0 ignore_prev:1
,V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
I/qcom_sensors_hal(  966): hal_sam_activate: Activating sensor handle 35
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.543915 Y: -0.356018 Z: 9.763031 
,V/qcom_sensors_hal(  966): hal_sam_algo_activate: Inspecting Sensor 35(0); sample rate: 20; report rate: 0, WUFF: 0
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.543915 .y:-0.356018 .z:9.763031
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
D/qcom_sensors_hal(  966): hal_sam_algo_activate: Update freq 0 -> 20
,I/qcom_sensors_hal(  966): hal_sam_send_cancel: Sending cancel to 21
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=1000
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 0, txn Id 44
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 1, Sn 21, msg Id 2, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_sam_sensor_thresh_resp: Instance ID of Sensor Threshold is 3
,D/qcom_sensors_hal(  966): hal_sam_thresh_send_enable: Received Response: 0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=2 Items=1 max_reports_per_index=2
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.559952 Y: -0.378632 Z: 9.747467 
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.557724 Y: -0.380859 Z: 9.764130 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:2;data[0].sensor:0 .type:1 .x:-0.559952 .y:-0.378632 .z:9.747467
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,I/Sensors (  361): sns_pwr.c(292):acquiring wakelock
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.537460 Y: -0.382019 Z: 9.751083 
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 21, msg Id 5, txn Id 0
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.537460 .y:-0.382019 .z:9.751083
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
V/qcom_sensors_hal(  966): hal_sam_parse_ind: Received 1 samples
I/qcom_sensors_hal(  966): hal_sam_gen_prox : proximity_state changed - FAR
I/qcom_sensors_hal(  966): hal_sam_gen_prox: prox data: 0.000000 0.000000 5.000305
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:35 .type:8 .x:5.000305 .y:0.000000 .z:0.000000
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
D/KnockOnPowerController(  966): proximity onSensorChanged : proximity = 1
D/KnockOnPowerController(  966): proximitySensorChanged  positive = true
I/KnockOnPowerController(  966): current mode = 1  value = 1 1
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.533920 Y: -0.364624 Z: 9.735687 
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.533920 .y:-0.364624 .z:9.735687
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.542572 Y: -0.381012 Z: 9.729904 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.542572 .y:-0.381012 .z:9.729904
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.539261 Y: -0.369736 Z: 9.748978 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.539261 .y:-0.369736 .z:9.748978
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  966): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
V/qcom_sensors_hal(  966): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  966): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
V/qcom_sensors_hal(  966): hal_process_report_ind: X: -0.543930 Y: -0.357056 Z: 9.761032 
,D/qcom_sensors_hal(  966): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.543930 .y:-0.357056 .z:9.761032
D/qcom_sensors_hal(  966): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=0
,V/KeyguardServiceDelegate(  966): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$18@43b6c3f8)
,D/KeyguardViewMediator( 1141): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 1141): notifyScreenOnLocked
,D/KeyguardViewMediator( 1141): handleNotifyScreenOn
,D/KeyguardViewManager( 1141): onScreenTurnedOn()
,V/KeyguardServiceDelegate(  966): **** SHOWN CALLED ****
I/WindowManager(  966): No lock screen! windowToken=null
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/SurfaceFlinger(  267): Screen released, type=0 flinger=0xb8c65450
,D/qdhwcomposer(  267): hwc_blank: Blanking display: 0
,D/NfcServiceBRCM( 1474): NFC is already turned off.
,D/WifiStateMachine(  966): handleScreenStateChanged: true
,D/WifiStateMachine(  966): handleMessage: E msg.what=131154
D/WifiStateMachine(  966): processMsg: InitialState
,D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): handleMessage: X
,D/WifiStateMachine(  966): handleMessage: E msg.what=131127
D/WifiStateMachine(  966): processMsg: InitialState
D/WifiStateMachine(  966): processMsg: DefaultState
,D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131158
,D/WifiStateMachine(  966): processMsg: InitialState
D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): setSuspendOptimizations: 4 false
,D/WifiStateMachine(  966): mSuspendOptNeedsDisabled 4
,D/WifiStateMachine(  966): handleMessage: X
,D/WifiServiceExtension(  966): sendKtScanInterval  mRtspPlay : false
,D/WifiOffDelayIfNotUsed(  966): stopMonitoring
,E/AudioSystem(  966): AudioSystem::setParameters()...keyValue screen_state=on
,V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=on, calling pid 966
,V/SRS_Proc(  270): ParamSet string: screen_state=on
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=on
V/voice   (  270): voice_set_parameters: enter: screen_state=on
,V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=on
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=2
V/EmotionalLed( 1155): startInternal : pkg=lcdon, recordId=0 : LGLedRecord{4327cd30 flags=2 patternId=2 color=0 priority=1 recordId=0 pkg=lcdon mExceptional=false mNativeNotification=false whichLedPlay=2 patternFilePath=null}
,D/EmotionalLed( 1155): enqueuing start. mLedList.size()=2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=3
,D/EmotionalLed( 1155): enqueuing end. mLedList.size()=3
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_ON
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherAncestor( 1886): 2 : onReceive, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:27:19
,E/SlideAside( 3563): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.USER_PRESENT
,I/SlideAside( 3563): [PinnedViewHolder.java:79:onReceive()] oooooo Lock screen unlock
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/UpdateThreadPoolManager( 1886): 2 : This is isUpdating : false
,D/WeatherAncestor( 1886): 2 : onReceive has processed, action: android.intent.action.USER_PRESENT, Time(hour:min:sec) 13:27:19
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/WeatherService( 1886): 2 : onStartCommand, intent!=null, action: android.intent.action.USER_PRESENT
,D/WeatherService( 1886): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1886): 2 : shouldTimeTickRegistered : false
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00ffff,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 255, B = 255
,D/qdlights( 1155): set_light_notifications: 2,ff00f9f9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 249, B = 249
,D/qdlights( 1155): set_light_notifications: 2,ff00f3f3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 243, B = 243
,D/qdlights( 1155): set_light_notifications: 2,ff00eded,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 237, B = 237
,D/qdlights( 1155): set_light_notifications: 2,ff00e7e7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 231, B = 231
,D/qdlights( 1155): set_light_notifications: 2,ff00e1e1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 225, B = 225
,D/qdlights( 1155): set_light_notifications: 2,ff00dbdb,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 219, B = 219
,D/qdlights( 1155): set_light_notifications: 2,ff00d5d5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 213, B = 213
,D/qdlights( 1155): set_light_notifications: 2,ff00cfcf,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 207, B = 207
,D/qdhwcomposer(  267): hwc_blank: Done blanking display: 0
,D/SurfaceControl(  966): Excessive delay in blankDisplay() while turning screen off: 401ms
D/qdlights( 1155): set_light_notifications: 2,ff00c9c9,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 201, B = 201
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/qdlights( 1155): set_light_notifications: 2,ff00c3c3,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 195, B = 195
,D/qdlights( 1155): set_light_notifications: 2,ff00bdbd,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 189, B = 189
,D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1141): changeTargets() succeeded. size: 20
,D/qdlights( 1155): set_light_notifications: 2,ff00b7b7,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 183, B = 183
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368039636, nextTick: 40397, mDrawingTime: 0
,D/qdlights( 1155): set_light_notifications: 2,ff00b1b1,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 177, B = 177
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/qdlights( 1155): set_light_notifications: 2,ff00abab,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 171, B = 171
,D/qdlights( 1155): set_light_notifications: 2,ff00a5a5,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 165, B = 165
,D/qdlights( 1155): set_light_notifications: 2,ff009f9f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 159, B = 159
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368039679, nextTick: 40354, mDrawingTime: 0
,D/NfcServiceBRCM( 1474): NFC is already turned off.
,D/qdlights( 1155): set_light_notifications: 2,ff009999,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 153, B = 153
,D/qdlights( 1155): set_light_notifications: 2,ff009393,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 147, B = 147
D/WeatherService( 1886): 2 : onReceive, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:27:19
,D/WeatherService( 1886): 2 : ACTION screen on
,D/WeatherService( 1886): 2 : shouldTimeTickRegistered : false
,D/WeatherService( 1886): 2 : onReceive has processed, action: android.intent.action.SCREEN_ON, Time(hour:min:sec) 13:27:19
,D/qdlights( 1155): set_light_notifications: 2,ff008d8d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 141, B = 141
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_ON
,D/qdlights( 1155): set_light_notifications: 2,ff008787,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 135, B = 135
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_ON flg=0x50000010 }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_ON
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_ON
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_ON
I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=0, enabled=0
,I/qcom_sensors_hal(  966): _hal_sensors_activate: active_sensors mask=0xc00000001 handle=0
D/KeyguardViewMediator( 1141): onScreenTurnedOff(3)
,D/KeyguardViewMediator( 1141): notifyScreenOffLocked
,I/qcom_sensors_hal(  966): _hal_sensors_activate: handle=0, Initialized the timestamp 
D/qcom_sensors_hal(  966): hal_schedule_acquire_resources: Setting acquire resources timer for 10000 usec
D/qdlights( 1155): set_light_notifications: 2,ff008181,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 129, B = 129
V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{44d8f288 u0 com.test.thalitest/.MainActivity t3}
D/qcom_sensors_hal(  966): hal_acquire_resources
D/qcom_sensors_hal(  966): hal_acquire_resources: Deactivating sensor handle=0
,D/qcom_sensors_hal(  966): hal_smgr_report_delete: handle=0
,D/qcom_sensors_hal(  966): hal_wait_for_response: timeout=1000
,D/qdlights( 1155): set_light_notifications: 2,ff007b7b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 123, B = 123
V/qcom_sensors_hal(  966): hal_sensor1_data_cb: msg_type 1, Sn 0, msg Id 33, txn Id 0
D/qcom_sensors_hal(  966): hal_process_smgr_resp: 33
D/qcom_sensors_hal(  966): hal_process_buffering_resp: Id: 0 Resp: 0 txn id 0
,D/qcom_sensors_hal(  966): hal_smgr_report_delete: Rcvd success response from request
,D/qdlights( 1155): set_light_notifications: 2,ff007575,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 117, B = 117
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/KeyguardViewMediator( 1141): setting alarm to turn off keyguard, seq = 2, timeout = 5000
D/KeyguardViewMediator( 1141): handleNotifyScreenOff
,D/KeyguardViewManager( 1141): onScreenTurnedOff()
D/qdlights( 1155): set_light_notifications: 2,ff006f6f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 111, B = 111
V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{44d8f288 u0 com.test.thalitest/.MainActivity t3} (pause complete)
V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{44d8f288 u0 com.test.thalitest/.MainActivity t3} (stop requested)
,D/UsbSettings( 2539): [AUTORUN] onDestroy() : getDefaultFunction =boot
,I/LGImmersionVibrator(  966): Vibrator off
,D/WifiStateMachine(  966): handleScreenStateChanged: false
,E/AudioSystem(  966): AudioSystem::setParameters()...keyValue screen_state=off
D/WifiStateMachine(  966): handleMessage: E msg.what=131154
D/WifiStateMachine(  966): processMsg: InitialState
D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): handleMessage: X
D/WifiStateMachine(  966): handleMessage: E msg.what=131158
D/WifiStateMachine(  966): processMsg: InitialState
D/WifiStateMachine(  966): processMsg: DefaultState
D/WifiStateMachine(  966): setSuspendOptimizations: 4 true
D/WifiStateMachine(  966): mSuspendOptNeedsDisabled 0
D/WifiStateMachine(  966): handleMessage: X
V/AudioFlinger(  270): setParameters(): io 0, keyvalue screen_state=off, calling pid 966
V/SRS_Proc(  270): ParamSet string: screen_state=off
D/audio_hw_primary(  270): adev_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: enter: screen_state=off
V/voice   (  270): voice_set_parameters: exit with code(-2)
V/msm8974_platform(  270): platform_set_parameters: enter: screen_state=off
V/msm8974_platform(  270): platform_set_parameters: exit with code(-2)
D/audio_hw_extn(  270): audio_extn_set_anc_parameters: anc_enabled:0
,V/audio_hw_primary(  270): adev_set_parameters: exit with code(-2)
V/ActivityManager(  966): Moving to DESTROYING: ActivityRecord{431dc408 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
V/ActivityManager(  966): Moving to STOPPED: ActivityRecord{44d8f288 u0 com.test.thalitest/.MainActivity t3} (stop complete)
D/WifiController(  966): CMD_SCREEN_OFF 
,D/WifiController(  966): shouldWifiStayAwake TRUE
D/qdlights( 1155): set_light_notifications: 2,ff006969,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 105, B = 105
V/UsbSettings( 2539): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2539): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2539): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
,E/CliptrayService( 1155): cliptrayEventReceiver :onReceiveandroid.intent.action.SCREEN_OFF
I/EmotionalLed( 1155): getCurrentHighestLGLedRecord() start. mLedList.size=3
D/VolumeVibrator( 1155): clear
,D/NfcServiceBRCM( 1474): NFC is already turned off.
D/qdlights( 1155): set_light_notifications: 2,ff006363,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 99, B = 99
I/rmt_storage(  418): rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb72dd178
I/rmt_storage(  418): rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,I/rmt_storage(  418): wakelock acquired: 1, error no: 42
I/rmt_storage(  418): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1221733832)
,I/[LGHome]EVENT( 1489): [Launcher.java:1567:onReceive()]Screen Off
V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{431dc408 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ab158 stackId=1, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused
V/TelephonyAutoProfiling(  966): [getValue] FEATURE key : trf_based_vzw, value : null
E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
E/Parcel  (  406): Reading a NULL string not supported here.
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
V/LGRssiData(  966): [loadRssi] File not exist 
D/qdlights( 1155): set_light_notifications: 2,ff005d5d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 93, B = 93
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/BubblePopupHelper( 1141): isShowingBubblePopup : false
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : SUPPORT_INFO_FOR_IMS, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_assisted_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : support_smart_dialing, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : vzw_gfit, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : KR_REJECT_CAUSE, value : null
V/TelephonyAutoProfiling( 1449): [getValue] FEATURE key : trf_based_vzw, value : null
D/PhoneInterfaceManager( 1449): [PhoneIntfMgr] sigLevel = 0
D/WeatherService( 1886): 2 : onReceive, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:27:19
D/WeatherService( 1886): 2 : ACTION screen off
D/WeatherService( 1886): 2 : onReceive has processed, action: android.intent.action.SCREEN_OFF, Time(hour:min:sec) 13:27:19
D/qdlights( 1155): set_light_notifications: 2,ff005757,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 87, B = 87
,V/PhoneApp( 1449): Action intent recieved:android.intent.action.SCREEN_OFF
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
D/qdlights( 1155): set_light_notifications: 2,ff005151,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 81, B = 81
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 }
D/TangibleManager( 1462): [TangibleIO] LCD is off. Remove tangible if exist.
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.SCREEN_OFF
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.SCREEN_OFF
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.SCREEN_OFF
,D/qdlights( 1155): set_light_notifications: 2,ff004b4b,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 75, B = 75
,D/qdlights( 1155): set_light_notifications: 2,ff004545,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 69, B = 69
,D/qdlights( 1155): set_light_notifications: 2,ff003f3f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 63, B = 63
,D/qdlights( 1155): set_light_notifications: 2,ff003939,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 57, B = 57
,D/qdlights( 1155): set_light_notifications: 2,ff003333,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 51, B = 51
,D/qdlights( 1155): set_light_notifications: 2,ff002d2d,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 45, B = 45
,D/qdlights( 1155): set_light_notifications: 2,ff002727,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 39, B = 39
,D/qdlights( 1155): set_light_notifications: 2,ff002121,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 33, B = 33
,I/rmt_storage(  418): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
,I/rmt_storage(  418): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,I/rmt_storage(  418): rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1221733832) wakelock released: 1, error no: 0
I/rmt_storage(  418): 
I/rmt_storage(  418): rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb72dd178
D/qdlights( 1155): set_light_notifications: 2,ff001b1b,10,0,2
D/qdlights( 1155): [Current] = 255, R = 0, G = 27, B = 27
,E/Diag_Lib(  724): [IMS_FATAL]| 2912 | 736 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,D/qdlights( 1155): set_light_notifications: 2,ff001515,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 21, B = 21
,D/qdlights( 1155): set_light_notifications: 2,ff000f0f,10,0,2
,D/qdlights( 1155): [Current] = 255, R = 0, G = 15, B = 15
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,2
,D/qdlights( 1155): set_light_notifications: 0,0,0,0,3
,D/qdlights( 1155): set_light_notifications: 1,ff00ff00,500,2000,1
I/EmotionalLed( 1155): updateLightsLocked() start. mLedList.size=2
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Sensors (  361): sns_pwr.c(320):releasing wakelock
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,E/ThermalEngine(  284): [GPU_MON] ACTION: GPU - [GPU_MON] Setting GPU[0] to 450000000
,D/KeyguardViewMediator( 1141): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/PhoneApp( 1449): getIsInUseVoLTE : false
,D/KeyguardViewMediator( 1141): doKeyguard: not showing simpin lockscreen when sim pin skipped.
,D/LockPatternUtilsEx( 1141): OMADM Lock is OFF
,D/KeyguardViewMediator( 1141): doKeyguard: not showing because lockscreen is off
,D/KeyguardViewMediator( 1141): doKeyguard is called, but is not locked.
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368052869799476; DSPS: 5122575; Offset: 1448367896541216713
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  966): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368072871664937; DSPS: 5777996; Offset: 1448367896541220602
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368080050, nextTick: 59976, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368080057, nextTick: 59972, mDrawingTime: 1
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 292 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368092873407274; DSPS: 6433413; Offset: 1448367896541223437
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368112875309610; DSPS: 7088835; Offset: 1448367896541233683
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368132877366008; DSPS: 7744262; Offset: 1448367896541245403
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368140056, nextTick: 59972, mDrawingTime: 2
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368140059, nextTick: 59971, mDrawingTime: 1
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,W/ProcessCpuTracker(  966): Skipping unknown process pid 4453
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368152879262928; DSPS: 8399685; Offset: 1448367896541219716
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368172880841826; DSPS: 9055097; Offset: 1448367896541211700
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368192882230984; DSPS: 9710502; Offset: 1448367896541227567
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368200044, nextTick: 59982, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368200050, nextTick: 59975, mDrawingTime: 3
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368212884471863; DSPS: 10365935; Offset: 1448367896541240662
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  966): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368232885576335; DSPS: 11021332; Offset: 1448367896541215984
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
,I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  966): updateLightListLocked :r=null, action=2
,W/GLSActivity( 1538): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1538): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1538): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1538): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1538): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3743): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3743): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3743): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3743): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3743): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3743): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3743): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3743): 	at dalvik.system.NativeStart.run(Native Method)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,W/System  ( 3743): Ignoring header User-Agent because its value was null.
,E/DataScheduler( 3743): isDataSchedulerEnabled():false
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/dalvikvm( 2596): GC_CONCURRENT freed 7695K, 32% free 16925K/24832K, paused 18ms+2ms, total 67ms
,D/dalvikvm( 2596): WAIT_FOR_CONCURRENT_GC blocked 45ms
,D/dalvikvm( 2596): GC_CONCURRENT freed 1830K, 32% free 17125K/24832K, paused 3ms+2ms, total 28ms
,D/dalvikvm( 2596): WAIT_FOR_CONCURRENT_GC blocked 20ms
,I/Mlt MonitorService( 2596): parseLastkmsg to dump
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368252888281640; DSPS: 11676780; Offset: 1448367896541235742
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368260048, nextTick: 59972, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368260065, nextTick: 59967, mDrawingTime: 1
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368272890176527; DSPS: 12332202; Offset: 1448367896541238539
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368292891817978; DSPS: 12987616; Offset: 1448367896541232041
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368312904500263; DSPS: 13643392; Offset: 1448367896541219013
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368320049, nextTick: 59974, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368320056, nextTick: 59972, mDrawingTime: 2
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368332906062807; DSPS: 14298803; Offset: 1448367896541225161
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368352907905247; DSPS: 14954223; Offset: 1448367896541236546
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368372909469667; DSPS: 15609635; Offset: 1448367896541214052
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368380046, nextTick: 59982, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368380049, nextTick: 59982, mDrawingTime: 1
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368392911101429; DSPS: 16265048; Offset: 1448367896541228383
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368412912920172; DSPS: 16920468; Offset: 1448367896541216071
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368432914744332; DSPS: 17575887; Offset: 1448367896541239694
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368440040, nextTick: 59968, mDrawingTime: 9
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368440057, nextTick: 59976, mDrawingTime: 0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368452916591667; DSPS: 18231308; Offset: 1448367896541225457
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368472918145045; DSPS: 18886719; Offset: 1448367896541222438
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368492919679829; DSPS: 19542129; Offset: 1448367896541231343
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368500038, nextTick: 59977, mDrawingTime: 9
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368500065, nextTick: 59967, mDrawingTime: 0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
,D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368512921269613; DSPS: 20197541; Offset: 1448367896541234213
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  966): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368532923360648; DSPS: 20852970; Offset: 1448367896541219535
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/dalvikvm(  966): GC_EXPLICIT freed 22707K, 48% free 29433K/56204K, paused 5ms+15ms, total 239ms
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x442ba208: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1538): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1538): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1538): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1538): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1538): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3743): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3743): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3743): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3743): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3743): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3743): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3743): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3743): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3743): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368552924981629; DSPS: 21508383; Offset: 1448367896541223085
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368560035, nextTick: 59979, mDrawingTime: 9
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368560072, nextTick: 59960, mDrawingTime: 0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368572926829591; DSPS: 22163803; Offset: 1448367896541239992
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368592928312291; DSPS: 22819212; Offset: 1448367896541227331
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368612929888064; DSPS: 23474624; Offset: 1448367896541216189
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368620038, nextTick: 59955, mDrawingTime: 16
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368620062, nextTick: 59971, mDrawingTime: 0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368632931690765; DSPS: 24130043; Offset: 1448367896541218353
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368652934019612; DSPS: 24785479; Offset: 1448367896541227864
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368672935919083; DSPS: 25440901; Offset: 1448367896541235246
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368680018, nextTick: 60001, mDrawingTime: 10
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368680060, nextTick: 59972, mDrawingTime: 0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368692937743868; DSPS: 26096321; Offset: 1448367896541228976
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368712939586724; DSPS: 26751741; Offset: 1448367896541240777
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368732941263487; DSPS: 27407156; Offset: 1448367896541239073
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368740033, nextTick: 59980, mDrawingTime: 10
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368740066, nextTick: 59966, mDrawingTime: 0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368752942573584; DSPS: 28062559; Offset: 1448367896541236915
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368772944180608; DSPS: 28717972; Offset: 1448367896541226507
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368792945996851; DSPS: 29373391; Offset: 1448367896541242213
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368800040, nextTick: 59954, mDrawingTime: 16
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368800064, nextTick: 59966, mDrawingTime: 1
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368812947520645; DSPS: 30028801; Offset: 1448367896541240128
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368832949376939; DSPS: 30684222; Offset: 1448367896541234850
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x431cc610: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,W/GLSActivity( 1538): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1538): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1538): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1538): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1538): 	at dalvik.system.NativeStart.run(Native Method)
D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,E/PlayEventLogger( 3743): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3743): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3743): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3743): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3743): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3743): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3743): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3743): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3743): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368852950989119; DSPS: 31339635; Offset: 1448367896541229598
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368860018, nextTick: 60001, mDrawingTime: 10
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368860072, nextTick: 59959, mDrawingTime: 1
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368872952580673; DSPS: 31995047; Offset: 1448367896541234238
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368892954966447; DSPS: 32650485; Offset: 1448367896541239641
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368912956832221; DSPS: 33305907; Offset: 1448367896541213325
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368920052, nextTick: 59961, mDrawingTime: 10
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368920065, nextTick: 59968, mDrawingTime: 0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368932958457786; DSPS: 33961320; Offset: 1448367896541221458
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368952960302154; DSPS: 34616740; Offset: 1448367896541234772
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368972961921156; DSPS: 35272153; Offset: 1448367896541236342
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368980081, nextTick: 59944, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448368980084, nextTick: 59948, mDrawingTime: 0
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448368992963645107; DSPS: 35927570; Offset: 1448367896541220791
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369012965584787; DSPS: 36582993; Offset: 1448367896541237864
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369032967035248; DSPS: 37238401; Offset: 1448367896541223481
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369040039, nextTick: 59964, mDrawingTime: 12
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369040058, nextTick: 59975, mDrawingTime: 0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369052968958417; DSPS: 37893824; Offset: 1448367896541224042
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369072970630545; DSPS: 38549239; Offset: 1448367896541217704
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369092972569235; DSPS: 39204662; Offset: 1448367896541233786
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369100022, nextTick: 59986, mDrawingTime: 12
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369100076, nextTick: 59953, mDrawingTime: 1
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  966): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
D/QcConnectivityService(  966): handleInetConditionChange: no active default network - ignore
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369112974815790; DSPS: 39860096; Offset: 1448367896541222040
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369132976711564; DSPS: 40515518; Offset: 1448367896541225725
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x4321c7c0: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1538): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1538): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1538): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1538): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1538): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3743): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3743): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3743): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3743): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3743): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3743): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3743): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3743): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3743): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369152978418431; DSPS: 41170934; Offset: 1448367896541223607
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369160023, nextTick: 59971, mDrawingTime: 17
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369160066, nextTick: 59964, mDrawingTime: 1
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369172980251393; DSPS: 41826354; Offset: 1448367896541225515
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369192981947999; DSPS: 42481770; Offset: 1448367896541213136
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369212983913357; DSPS: 43137194; Offset: 1448367896541225369
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369220017, nextTick: 60000, mDrawingTime: 11
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369220060, nextTick: 59973, mDrawingTime: 0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369232985636683; DSPS: 43792610; Offset: 1448367896541239711
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369252987282091; DSPS: 44448024; Offset: 1448367896541237170
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369272989098958; DSPS: 45103444; Offset: 1448367896541222982
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369280049, nextTick: 59964, mDrawingTime: 10
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369280060, nextTick: 59972, mDrawingTime: 0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369292990857909; DSPS: 45758861; Offset: 1448367896541242431
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369312992755922; DSPS: 46414284; Offset: 1448367896541217837
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369332994358624; DSPS: 47069696; Offset: 1448367896541233624
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369340048, nextTick: 59968, mDrawingTime: 9
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369340056, nextTick: 59974, mDrawingTime: 1
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369352996262730; DSPS: 47725119; Offset: 1448367896541215123
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369372997923139; DSPS: 48380533; Offset: 1448367896541227583
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369392999567923; DSPS: 49035947; Offset: 1448367896541224418
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369400040, nextTick: 59965, mDrawingTime: 12
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369400057, nextTick: 59976, mDrawingTime: 0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369413001425311; DSPS: 49691368; Offset: 1448367896541220233
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369433013430773; DSPS: 50347121; Offset: 1448367896541232287
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x431f0970: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
,W/GLSActivity( 1538): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1538): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1538): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1538): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1538): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3743): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3743): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3743): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3743): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3743): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3743): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3743): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3743): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3743): Ignoring header User-Agent because its value was null.
,D/libc    (  264): _dns_getaddrinfo: iptype =0
,D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369453014737120; DSPS: 51002524; Offset: 1448367896541226378
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369460033, nextTick: 59988, mDrawingTime: 8
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369460058, nextTick: 59974, mDrawingTime: 0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369473016446278; DSPS: 51657940; Offset: 1448367896541226552
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369493018187156; DSPS: 52313357; Offset: 1448367896541227928
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369513020076627; DSPS: 52968779; Offset: 1448367896541225309
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369520043, nextTick: 59980, mDrawingTime: 6
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369520048, nextTick: 59981, mDrawingTime: 1
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1141): handleBatteryUpdate (2) (100)
D/WifiController(  966): battery changed pluggedType: 2
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 278 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1141): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/HeadsetStateMachine( 1217): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369533021840161; DSPS: 53624197; Offset: 1448367896541218824
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369553024123436; DSPS: 54279631; Offset: 1448367896541243798
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369573025696709; DSPS: 54935043; Offset: 1448367896541230157
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369580044, nextTick: 59979, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369580050, nextTick: 59981, mDrawingTime: 1
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369593027256388; DSPS: 55590454; Offset: 1448367896541233439
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369613029215964; DSPS: 56245878; Offset: 1448367896541239890
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369633030673977; DSPS: 56901286; Offset: 1448367896541233060
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369640040, nextTick: 59983, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369640047, nextTick: 59983, mDrawingTime: 1
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369653032229593; DSPS: 57556697; Offset: 1448367896541232279
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369673034758806; DSPS: 58212140; Offset: 1448367896541228533
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369693036588902; DSPS: 58867560; Offset: 1448367896541227574
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369700046, nextTick: 59976, mDrawingTime: 5
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369700053, nextTick: 59975, mDrawingTime: 2
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369713037520145; DSPS: 59522950; Offset: 1448367896541243290
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369733039447741; DSPS: 60178374; Offset: 1448367896541217761
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/ActivityManager(  966): Killing 2081:android.process.media/u0a23 (adj 15): empty for 1801s
,I/ProcessStatsService(  966): Prepared write state in 38ms
,I/GLSUser ( 1538): [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.android.vending, service: androidmarket
,I/GLSUser ( 1538): [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
I/GLSUser ( 1538): [GLSUser] Extracting token using key: Auth
,W/GLSActivity( 1538): gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,V/GLSActivity( 1538): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ab158 stackId=1, 1 tasks}
,D/dalvikvm( 1538): GC_EXPLICIT freed 1667K, 29% free 17812K/24832K, paused 3ms+5ms, total 71ms
D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused
,I/Auth    ( 1538): [DefaultAuthDelegateService] Use browser flow? false
,D/dalvikvm(  966): GC_CONCURRENT freed 3338K, 48% free 29338K/56204K, paused 6ms+5ms, total 161ms
,D/dalvikvm(  966): WAIT_FOR_CONCURRENT_GC blocked 18ms
,W/GLSActivity( 1538): com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.a(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown Source)
W/GLSActivity( 1538): 	at com.google.android.gsf.loginservice.GoogleLoginService$AccountAuthenticatorImpl.getAuthToken(GoogleLoginService.java:296)
W/GLSActivity( 1538): 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
W/GLSActivity( 1538): 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
W/GLSActivity( 1538): 	at android.os.Binder.execTransact(Binder.java:407)
W/GLSActivity( 1538): 	at dalvik.system.NativeStart.run(Native Method)
,E/PlayEventLogger( 3743): Failed to get auth token: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3743): android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
E/PlayEventLogger( 3743): 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1726)
E/PlayEventLogger( 3743): 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
E/PlayEventLogger( 3743): 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1572)
E/PlayEventLogger( 3743): 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
E/PlayEventLogger( 3743): 	at android.os.Binder.execTransact(Binder.java:407)
E/PlayEventLogger( 3743): 	at dalvik.system.NativeStart.run(Native Method)
,W/System  ( 3743): Ignoring header User-Agent because its value was null.
D/NotificationService(  966): updateLightListLocked :r=NotificationRecord(0x43223c58: pkg=com.google.android.gms user=UserHandle{0} id=1 tag=null score=0: Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])), action=2
,D/NotificationService(  966): notification=Notification(pri=0 contentView=com.google.android.gms/0x1090064 vibrate=null sound=null defaults=0x0 flags=0x10 kind=[null])
D/libc    (  264): _dns_getaddrinfo: iptype =0
D/libc    (  264): _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
,I/ProcessStatsService(  966): Pruning old procstats: /data/system/procstats/state-2015-11-23-22-47-01.bin
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369753040912160; DSPS: 60833782; Offset: 1448367896541217336
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
I/ActivityManager(  966): Killing 3851:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty for 1818s
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369760031, nextTick: 59997, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369760034, nextTick: 59997, mDrawingTime: 1
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ab158 stackId=1, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369773042360434; DSPS: 61489189; Offset: 1448367896541231284
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369793044456469; DSPS: 62144618; Offset: 1448367896541221606
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/qcom_sensors_hal(  966): hal_time_data_cb: msg_type 2
,D/qcom_sensors_hal(  966): hal_time_data_cb: Sn 24, msg Id 3, txn Id 0
,D/qcom_sensors_hal(  966): hal_ts_offset_is: Apps: 1448369813046421461; DSPS: 62800042; Offset: 1448367896541233473
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
,D/KeyguardUpdateMonitor( 1141): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1141): handleTimeUpdate
I/ActivityManager(  966): Killing 3682:com.android.contacts/u0a21 (adj 15): empty for 1811s
I/ActivityManager(  966): Killing 4085:com.lge.bnr/1000 (adj 15): empty for 1811s
I/ActivityManager(  966): Killing 3665:com.lge.appbox.client/u0a11 (adj 15): empty for 1811s
I/ActivityManager(  966): Killing 4057:com.google.android.partnersetup/u0a9 (adj 15): empty for 1811s
I/ActivityManager(  966): Killing 4026:com.android.defcontainer/u0a4 (adj 15): empty for 1811s
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369820035, nextTick: 59992, mDrawingTime: 3
,D/Clock   ( 1141): Clock updated, drawingStartTime : 1448369820039, nextTick: 59992, mDrawingTime: 1
,D/KeyguardModel( 1141): mReceiver, received action: android.intent.action.TIME_TICK, sendingUserId:-1
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ab158 stackId=1, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ab158 stackId=1, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ab158 stackId=1, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ab158 stackId=1, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused
,I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{432ab158 stackId=1, 1 tasks}
,D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log( 4207): DBG, CoordinatorConnector connect_error called
I/jxcore-log( 4207): 
D/AndroidRuntime( 6095): 
D/AndroidRuntime( 6095): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 6095): CheckJNI is OFF
D/dalvikvm( 6095): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 6095): Added shared lib libjavacore.so 0x0
D/dalvikvm( 6095): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 6095): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 6095): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 6095): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
E/memtrack( 6095): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 6095): failed to load memtrack module: -2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/AndroidRuntime( 6095): Calling main entry com.android.commands.pm.Pm
I/ActivityManager(  966): Force stopping com.test.thalitest appid=10304 user=-1: uninstall pkg
I/ActivityManager(  966): Killing 4207:com.test.thalitest/u0a304 (adj 0): stop com.test.thalitest
V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{44d8f288 u0 com.test.thalitest/.MainActivity t3} (cleaning up)
I/MDM     (  966):  removeProcessLocked app.persistent = false callerWillRestart = false
I/ActivityManager(  966):   Force finishing activity ActivityRecord{44d8f288 u0 com.test.thalitest/.MainActivity t3}
V/ActivityManager(  966): Moving to FINISHING: ActivityRecord{44d8f288 u0 com.test.thalitest/.MainActivity t3 f}
D/ActivityManager(  966): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  966): moveHomeStack:
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bfe130 stackId=0, 1 tasks}
V/ActivityManager(  966): Moving to RESUMED: ActivityRecord{43017bd0 u0 com.lge.launcher2/.Launcher t1} (in existing)
V/ActivityManager(  966): Moving to PAUSING: ActivityRecord{43017bd0 u0 com.lge.launcher2/.Launcher t1}
D/ActivityManager(  966): resumeTopActivityLocked: Resumed ActivityRecord{43017bd0 u0 com.lge.launcher2/.Launcher t1}
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bfe130 stackId=0, 1 tasks}
D/ActivityManager(  966): allPausedActivitiesComplete: r=ActivityRecord{43017bd0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  966): allPausedActivitiesComplete: r=ActivityRecord{43017bd0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
V/ActivityManager(  966): resumeTopActivityLocked: Skip resume: some activity pausing.
V/ActivityManager(  966): Moving to DESTROYED: ActivityRecord{44d8f288 u0 com.test.thalitest/.MainActivity t3 f} (removed from history)
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bfe130 stackId=0, 1 tasks}
D/ActivityManager(  966): allPausedActivitiesComplete: r=ActivityRecord{43017bd0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  966): allPausedActivitiesComplete: r=ActivityRecord{43017bd0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
V/ActivityManager(  966): resumeTopActivityLocked: Skip resume: some activity pausing.
I/[LGHome]EVENT( 1489): [Launcher.java:4947:onStart()]onStart
I/WindowState(  966): WIN DEATH: Window{43b42aa0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
W/PackageSettings(  966): Skipping PackageSetting{42cd2368 com.example.hello/10311} due to missing metadata
I/ActivityManager(  966): Force stopping com.test.thalitest appid=10304 user=0: pkg removed
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bfe130 stackId=0, 1 tasks}
D/ActivityManager(  966): allPausedActivitiesComplete: r=ActivityRecord{43017bd0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
D/ActivityManager(  966): allPausedActivitiesComplete: r=ActivityRecord{43017bd0 u0 com.lge.launcher2/.Launcher t1} state=PAUSING
V/ActivityManager(  966): resumeTopActivityLocked: Skip resume: some activity pausing.
D/KeyguardModel( 1141): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
I/[LGHome]EVENT( 1489): [Launcher.java:717:onResume()]onResume
I/InputReader(  966): Reconfiguring input devices.  changes=0x00000010
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  966):   Scheme: "sms"
E/SlideAside( 3563): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
I/SlideAside( 3563): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.test.thalitest
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/dalvikvm( 2608): GC_EXPLICIT freed 3649K, 29% free 17872K/24832K, paused 1ms+2ms, total 34ms
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  966):   Scheme: "smsto"
W/System.err( 2596): android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
W/GeofencerStateMachine( 1424): Ignoring removeGeofence because network location is disabled.
W/System.err( 2596): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2596): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
W/System.err( 2596): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/System.err( 2596): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2596): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2596): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2596): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2596): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2596): 	at java.lang.reflect.Method.invoke(Method.java:515)
W/System.err( 2596): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2596): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
W/System.err( 2596): 	at dalvik.system.NativeStart.main(Native Method)
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  966):   Scheme: "mms"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/ActivityManager(  966): Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6119 uid=10011 gids={50011, 3003, 1028, 1015, 2001}
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  966):   Scheme: "mmsto"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]EVENT( 1489): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/PhoneApp( 1449): getIsInUseVoLTE : false
D/dalvikvm(  966): GC_EXPLICIT freed 1472K, 48% free 29313K/55724K, paused 3ms+8ms, total 95ms
I/ActivityManager(  966): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=6129 uid=10090 gids={50090}
W/ActivityManager(  966): getAssistContextExtras failed: no resumed activity
I/[LGHome]LGActivityUtil( 1489): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  966):   Scheme: "sms"
I/[LGHome]EVENT( 1489): [Launcher.java:868:onResume()]onResume end
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
W/ActivityManager(  966): getAssistContextExtras failed: no resumed activity
D/HyLog   ( 6119): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6119): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6119): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/GlobalAccess( 1141): optimizeTargetDrawableItems(), newSize: 20
D/GlowPadView( 1141): changeTargets() succeeded. size: 20
I/[LGHome]EVENT( 1489): [Launcher.java:894:onPause()]onPause
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  966):   Scheme: "smsto"
D/HyLog   ( 6129): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6129): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6129): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/KeyguardModel( 1141): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
D/administrator(  966): Handling package changes for user 0
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
V/ActivityManager(  966): Moving to PAUSED: ActivityRecord{43017bd0 u0 com.lge.launcher2/.Launcher t1} (pause complete)
V/ActivityManager(  966): Moving to STOPPING: ActivityRecord{43017bd0 u0 com.lge.launcher2/.Launcher t1} (stop requested)
I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
I/[LGHome]LGPlusHomeDBManager( 1489): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
I/[LGHome]EVENT( 1489): [Launcher.java:4955:onStop()]onStop
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  966):   Scheme: "mms"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/PackageManager(  966):   Action: "android.intent.action.SENDTO"
I/PackageManager(  966):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  966):   Scheme: "mmsto"
I/PackageManager(  966): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/LockScreenSettings( 6129): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/KeyguardModel( 1141): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1141): createShortcutInfo...
I/AppUp4  ( 6119):  AppBoxContentProvider onCreate
D/KeyguardModel( 1141): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1141): createShortcutInfo...
V/ActivityManager(  966): Moving to STOPPED: ActivityRecord{43017bd0 u0 com.lge.launcher2/.Launcher t1} (stop complete)
I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
D/KeyguardModel( 1141): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1141): createShortcutInfo...
I/InteractionManagerConfigurator(  966): updateIntentFilterConfig
I/InteractionManagerConfigurator(  966): com.test.thalitest isn't inclued in dragdropPackageList
D/KeyguardModel( 1141): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1141): createShortcutInfo...
W/AppUp4  ( 6119):  [AppBoxDatabaseHelper] construct
D/KeyguardModel( 1141): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1141): createShortcutInfo...
I/ActivityManager(  966): Timeline: Activity_windows_visible id: ActivityRecord{43017bd0 u0 com.lge.launcher2/.Launcher t1} time:1928418
D/BackupManagerService(  966): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
V/BackupManagerService(  966): removePackageParticipantsLocked: uid=10304 #1
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
D/KeyguardModel( 1141): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
D/KeyguardModel( 1141): createShortcutInfo...
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
D/KeyguardModel( 1141): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
D/KeyguardModel( 1141): createShortcutInfo...
D/KeyguardModel( 1141): package = com.lge.camera, class = com.lge.camera.CameraApp
D/KeyguardModel( 1141): createShortcutInfo...
I/AppUp4  ( 6119):  setFingerPrint start
I/AppUp4  ( 6119):  newfinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
I/AppUp4  ( 6119):  beforefinger = lge/g2_open_com/g2:4.4.2/KOT49I.D80220h/D80220h.1413914494:user/release-keys
I/AppUp4  ( 6119):  beforefinger == newfinger no write in DB
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
D/dalvikvm( 1141): GC_FOR_ALLOC freed 7825K, 11% free 70587K/78724K, paused 27ms, total 27ms
D/AppUp4:AppBoxApplication( 6119): AppBoxApplication onCreate()
D/AppBoxBlacklist( 6119): ConfigFile is not exist. /cust/config/appmanager.cfg
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
D/dalvikvm(  966): GC_EXPLICIT freed 474K, 48% free 29317K/55724K, paused 6ms+19ms, total 214ms
D/AndroidRuntime( 6095): Shutting down VM
D/dalvikvm( 6095): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 2ms
D/PackageParser( 6119): Added overlay pkg for /system/apps/bootup/LGTaskManager.apk
D/KeyguardModel( 1141): handleShortcutListChanged...
D/KeyguardModel( 1141): handleShortcutListChanged...
I/ActivityManager(  966): Killing 4099:com.lge.email/u0a24 (adj 15): empty for 1820s
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bfe130 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused
I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
D/AppUp4:Utils( 6119): [getPackageName] uri : package:com.test.thalitest
D/AppUp4  ( 6119): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/AppUp4  ( 6119):  isExcludedPackage  packagename = com.test.thalitest
D/AppUp4  ( 6119):  isExcludedPackage TRUE : com.test.thalitest
I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
D/PackageParser( 6119): Added overlay pkg for /system/apps/bootup/LGHome_Theme_Marshmallow.apk
I/ActivityManager(  966): Start proc com.lge.email for content provider com.lge.email/.providers.LGEmailContentProvider: pid=6159 uid=10024 gids={50024, 3003, 4002, 1023, 1028, 1015, 3001, 3002}
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
I/[LGHome]Launcher.Model( 1489): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
I/[LGHome]EVENT( 1489): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
I/ActivityManager(  966): Start proc com.lge.bnr for broadcast com.lge.bnr/.receiver.BNRAppInstallReceiver: pid=6171 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  966): Killing 3697:com.android.gallery3d/u0a27 (adj 15): empty for 1820s
D/HyLog   ( 6159): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6159): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6159): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bfe130 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused
D/HyLog   ( 6171): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6171): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6171): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
D/[BNRAppListMgrReceiver]( 6171): android.intent.action.PACKAGE_REMOVED : com.test.thalitest
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/ActivityManager(  966): Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=6184 uid=10021 gids={50021, 3003, 1028, 1015, 1023, 4002}
I/LGEmail ( 6159): [lifecycle]--onCreate() (at EmailMainApp.java onCreate 172)[v:null]
D/LGEmail ( 6159): EmailContentProvider.query: uri=content://com.lge.providers.lgemail/account, projection=[accountID, userName, mailAddress, accountName, InboxID], selection=null, selectionArgs=null sortOrder=null, TABLE_NAMES=EAccountmatch is 0 (at LGEmailContentProvider.java query 492)[v:null]
E/LGEmail ( 6159): Email Not Started (at LGEmailContentProvider.java query 509)[v:null]
E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1489): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
I/ActivityManager(  966): Killing 4117:com.google.android.apps.docs/u0a73 (adj 15): empty for 1820s
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
D/HyLog   ( 6184): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6184): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6184): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/LGEmail ( 6159): user build Type == true (at Util.java isUserModeBuildType 3500)[v:6.30.33]
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bfe130 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
E/[LGHome]NumberBadge( 1489): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
I/[LGHome]LauncherAppWidgetHostView( 1489): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
I/SystemConfig( 6184): BUILD Country: EU
I/SystemConfig( 6184): BUILD Operator: OPEN
I/ActivityManager(  966): Killing 3713:com.google.android.apps.plus/u0a112 (adj 15): empty for 1820s
I/ActivityManager(  966): Killing 2903:com.lge.eula/1000 (adj 15): empty for 1820s
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bfe130 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused
I/SystemConfig( 6184): systemFeature RCS result false
I/[LGHome]EVENT( 1489): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
D/SystemConfig( 6184): refreshRcsSupport() :false
I/[LGHome]Launcher( 1489): [Launcher.java:3741:setLoadOnResume()]setLoadOnResume
D/VoicemailCleanupService( 1803): Cleaning up data for package: com.test.thalitest
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bfe130 stackId=0, 1 tasks}
D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused
W/BaseRuntimeLoader( 6159): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6159): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6159): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 6159): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
I/ActivityManager( 1489): Timeline: Activity_idle id: android.os.BinderProxy@42817eb8 time:1928713
I/PackageChangeReceiver( 6159): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/ActivityManager(  966): Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=6204 uid=10027 gids={50027, 3003, 1028, 1015, 1023, 4002}
D/HyLog   ( 6204): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6204): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6204): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/dalvikvm( 1489): GC_EXPLICIT freed 5787K, 9% free 62269K/68340K, paused 3ms+8ms, total 48ms
E/SharedPreferencesImpl( 6204): Couldn't rename file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml to backup file /data/data/com.android.gallery3d/shared_prefs/com.android.gallery3d_preferences.xml.bak
D/PackageIntentReceiver( 2539): Not supported Hotkey customization function 
D/HideNavigationAppsReceiver( 2539): Receive package name : com.test.thalitest
D/HideNavigationAppsReceiver( 2539): Delete mPackageMame : com.test.thalitest
I/ActivityManager(  966): Killing 1814:com.google.android.gms.wearable/u0a6 (adj 15): empty for 1820s
I/IcingCorporaProvider( 2608): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
I/ActivityManager(  966): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6222 uid=10073 gids={50073, 3003, 1028, 1015}
I/ActivityManager(  966): resumeTopActivitiesLocked(): target Stack:ActivityStack{42bfe130 stackId=0, 1 tasks}
E/SQLiteLog( 2596): (3850) statement aborts at 15: [INSERT INTO t001(f006,f003,f002,f005,f004) VALUES (?,?,?,?,?)] disk I/O error
E/SQLiteDatabase( 2596): Error inserting f006=10073 f003=com.google.android.apps.docs f002=1448369829849 f005=6222 f004=13
E/SQLiteDatabase( 2596): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2596): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2596): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:785)
E/SQLiteDatabase( 2596): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
E/SQLiteDatabase( 2596): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2596): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1570)
E/SQLiteDatabase( 2596): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1440)
E/SQLiteDatabase( 2596): 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
E/SQLiteDatabase( 2596): 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:220)
E/SQLiteDatabase( 2596): 	at android.content.ContentResolver.insert(ContentResolver.java:1206)
E/SQLiteDatabase( 2596): 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2406)
E/SQLiteDatabase( 2596): 	at com.lge.mlt.MltMonitorService.access$2500(MltMonitorService.java:38)
E/SQLiteDatabase( 2596): 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3210)
E/SQLiteDatabase( 2596): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/SQLiteDatabase( 2596): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 2596): 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3313)
D/ActivityManager(  966): resumeTopActivityLocked: Going to sleep and all paused
D/HyLog   ( 6222): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 6222): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 6222): I : /data/font/config/sfconfig.dat, No such file or directory (2)
E/SQLiteLog( 2608): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
W/dalvikvm( 2608): threadid=15: thread exiting with uncaught exception (group=0x417dae48)
E/AndroidRuntime( 2608): FATAL EXCEPTION: IntentService[UpdateCorporaService]
E/AndroidRuntime( 2608): Process: com.google.android.googlequicksearchbox:search, PID: 2608
E/AndroidRuntime( 2608): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/AndroidRuntime( 2608): 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
E/AndroidRuntime( 2608): 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:558)
E/AndroidRuntime( 2608): 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
E/AndroidRuntime( 2608): 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
E/AndroidRuntime( 2608): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
E/AndroidRuntime( 2608): 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
E/AndroidRuntime( 2608): 	at cau.d(PG:186)
E/AndroidRuntime( 2608): 	at cea.g(PG:591)
E/AndroidRuntime( 2608): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider.update(PG:299)
E/AndroidRuntime( 2608): 	at android.content.ContentProvider$Transport.update(ContentProvider.java:287)
E/AndroidRuntime( 2608): 	at android.content.ContentResolver.update(ContentResolver.java:1332)
E/AndroidRuntime( 2608): 	at ceb.OV(PG:906)
E/AndroidRuntime( 2608): 	at ced.sV(PG:823)
E/AndroidRuntime( 2608): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.a(PG:1267)
E/AndroidRuntime( 2608): 	at com.google.android.search.core.summons.icing.InternalIcingCorporaProvider$UpdateCorporaService.onHandleIntent(PG:1200)
E/AndroidRuntime( 2608): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/AndroidRuntime( 2608): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/AndroidRuntime( 2608): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 2608): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Process ( 2608): Sending signal. PID: 2608 SIG: 9
E/DropBoxManagerService(  966): Can't write: system_app_crash
E/DropBoxManagerService(  966): java.io.FileNotFoundException: /data/system/dropbox/drop93.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  966): 	at libcore.io.IoBridge.open(IoBridge.java:458)
E/DropBoxManagerService(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  966): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  966): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  966): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  966): 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:10358)
E/DropBoxManagerService(  966): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  966): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  966): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  966): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  966): 	... 5 more

```
