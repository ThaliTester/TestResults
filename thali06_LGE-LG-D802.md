#### Test 5038801913f4183_thali06_LGE-LG-D802 Logs


```
--------- beginning of /dev/log/main
I/ConfigFetchService( 1887): onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
I/ConfigFetchService( 1887): launchTask
W/dalvikvm( 1887): VFY: unable to find class referenced in signature (Landroid/net/Network;)
V/ConfigFetchTask( 1887): ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1WBxJncvqkdN7lh_3Wxg-OxP4VpK0xfoJULjgX_AWq-qwAGx0Pxt8YRlppiFbl-qw4udTJP0gcTfrtoILkX91Ld4r02eTkQc_AOAgsrf7ECdZopFGYdszGURHqF4lP8hMa61DSsc6KYB7i6htGv3dH-F09pwykMOJ6TKSVDgYsz-Kg--6fQRpf4PjQIBQPnP9oVDJRf
I/GoogleURLConnFactory( 1887): Using platform SSLCertificateSocketFactory
D/ChimeraCfgMgr( 1887): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1887): Module APK com.google.android.play.games already loaded
D/ChimeraCfgMgr( 1887): Loading module com.google.android.gms.vision from APK com.google.android.gms
D/Vision  ( 1887): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
D/Vision  ( 1887): Failed to find package metadata for com.example.hello
D/Vision  ( 1887): No vision deps
D/libc    (  264): _dns_getaddrinfo: iptype =1
D/libc    (  264): _dns_getaddrinfo: query_ipv4=1, query_ipv6=0
I/PeopleContactsSync( 1887): CP2 sync disabled
I/dalvikvm( 1887): Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
W/dalvikvm( 1887): VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
D/dalvikvm( 1887): VFY: replacing opcode 0x6e at 0x000e
W/BaseAppContext( 1887): Using Auth Proxy for data requests.
W/BaseAppContext( 1887): Using Auth Proxy for data requests.
W/BaseAppContext( 1887): Using Auth Proxy for data requests.
W/BaseAppContext( 1887): Using Auth Proxy for data requests.
W/BaseAppContext( 1887): Using Auth Proxy for data requests.
W/BaseAppContext( 1887): Using Auth Proxy for data requests.
E/ThermalEngine(  285): [GPU_MON] 0 percent. Current Sampling Time is 4 sec 
D/dalvikvm( 1530): GC_EXPLICIT freed 1060K, 29% free 17832K/24832K, paused 2ms+3ms, total 23ms
W/GAV2    ( 4503): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
--------- beginning of /dev/log/system
I/ActivityManager(  962): Killing 4079:com.android.providers.calendar/u0a16 (adj 15): empty #17
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{435261b8 stackId=1, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42eb1968 u0 com.android.settings/.UsbSettings t2}
I/ConfigFetchService( 1887): fetch service done; releasing wakelock
I/ConfigFetchService( 1887): stopping self
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/dalvikvm( 1887): GC_CONCURRENT freed 1503K, 22% free 19453K/24832K, paused 2ms+4ms, total 30ms
D/ChimeraCfgMgr( 1887): Loading module com.google.android.gms.games from APK com.google.android.play.games
D/ChimeraModuleLdr( 1887): Module APK com.google.android.play.games already loaded
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Icing   ( 1887): Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
D/Icing   ( 1887): Loaded CLD2 Version V2.0 - 20141016
I/Icing   ( 1887): Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 284 plugged : true isCharging : false
D/WifiController(  962): battery changed pluggedType: 2
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/HeadsetStateMachine( 1215): Disconnected process message: 10
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  962): battery changed pluggedType: 2
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 285 plugged : true isCharging : false
D/HeadsetStateMachine( 1215): Disconnected process message: 10
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/BatteryObserver( 1156): usb Uevent not necessary.
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/AndroidRuntime( 4554): 
D/AndroidRuntime( 4554): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4554): CheckJNI is OFF
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/dalvikvm( 4554): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4554): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4554): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4554): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4554): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
D/dalvikvm( 4554): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/memtrack( 4554): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4554): failed to load memtrack module: -2
D/AndroidRuntime( 4554): Calling main entry com.android.commands.am.Am
I/ActivityManager(  962): START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 4554
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{435261b8 stackId=1, 2 tasks}
D/PermissionCache(  267): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (134 us)
V/ActivityManager(  962): Moving to PAUSING: ActivityRecord{42eb1968 u0 com.android.settings/.UsbSettings t2}
D/dalvikvm(  962): GC_FOR_ALLOC freed 1429K, 10% free 28698K/31796K, paused 76ms, total 76ms
I/dalvikvm-heap(  962): Grow heap (frag case) to 31.022MB for 856096-byte allocation
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
D/ActivityManager(  962): resumeTopActivityLocked: Pausing null
V/ActivityManager(  962): resumeTopActivityLocked: Skip resume: need to start pausing
I/ActivityManager(  962): startService SlideAside
W/ContextImpl(  962): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
D/ActivityManager(  962): setFocusedStack: mFocusedStack=ActivityStack{435261b8 stackId=1, 2 tasks}
D/AndroidRuntime( 4554): Shutting down VM
D/UsbSettingsControl( 2612): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettings( 2612): [AUTORUN] onPause() : mActiveCurrentFunction = boot
I/SlideAside( 3754): [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
D/dalvikvm( 4554): GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 1ms+0ms, total 3ms
D/ActivityManager(  962): allPausedActivitiesComplete: r=ActivityRecord{42eb1968 u0 com.android.settings/.UsbSettings t2} state=PAUSING
V/ActivityManager(  962): Moving to PAUSED: ActivityRecord{42eb1968 u0 com.android.settings/.UsbSettings t2} (pause complete)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{435261b8 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Restarting ActivityRecord{42ec96c8 u0 com.example.hello/.MainActivity t3}
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/WifiStateMachine(  962): handleMessage: E msg.what=131155
D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2066): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
D/wpa_supplicant( 2066): wlan0: Control interface command 'SIGNAL_POLL'
I/ActivityManager(  962): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=4583 uid=10312 gids={50312, 3003, 3001, 3002}
I/SlideAside( 3754): [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
D/SlideAside( 3754): [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.example.hello (filtered)
D/wpa_supplicant( 2066): nl80211: survey data missing!
V/ActivityManager(  962): Moving to RESUMED: ActivityRecord{42ec96c8 u0 com.example.hello/.MainActivity t3} (starting new instance)
D/WifiStateMachine(  962): handleMessage: X
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
D/HyLog   ( 4583): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4583): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4583): I : /data/font/config/sfconfig.dat, No such file or directory (2)
V/WebViewChromium( 4583): Binding Chromium to the background looper Looper (main, tid 1) {42a789c0}
I/chromium( 4583): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/BrowserProcessMain( 4583): Initializing chromium process, renderers=0
W/chromium( 4583): [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
I/Adreno-EGL( 4583): <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
I/Adreno-EGL( 4583): OpenGL ES Shader Compiler Version: E031.24.00.02
I/Adreno-EGL( 4583): Build Date: 01/20/14 Mon
I/Adreno-EGL( 4583): Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
I/Adreno-EGL( 4583): Remote Branch: 
I/Adreno-EGL( 4583): Local Patches: 
I/Adreno-EGL( 4583): Reconstruct Branch: 
I/dalvikvm( 4583): Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
W/dalvikvm( 4583): VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
D/dalvikvm( 4583): VFY: replacing opcode 0x6e at 0x0016
I/dalvikvm( 4583): Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
W/dalvikvm( 4583): VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
D/dalvikvm( 4583): VFY: replacing opcode 0x6e at 0x0008
W/dalvikvm( 4583): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
W/dalvikvm( 4583): VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
I/dalvikvm( 4583): Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
W/dalvikvm( 4583): VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
D/dalvikvm( 4583): VFY: replacing opcode 0x6f at 0x001a
W/dalvikvm( 4583): VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
I/dalvikvm( 4583): Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
W/dalvikvm( 4583): VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
D/dalvikvm( 4583): VFY: replacing opcode 0x6e at 0x000d
I/dalvikvm( 4583): Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
W/dalvikvm( 4583): VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
D/dalvikvm( 4583): VFY: replacing opcode 0x6e at 0x0000
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/SystemWebViewEngine( 4583): CordovaWebView is running on device made by: LGE
D/dalvikvm( 4583): Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
W/BaseRuntimeLoader( 4583): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4583): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4583): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
W/BaseRuntimeLoader( 4583): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,D/OpenGLRenderer( 4583): Enabling debug mode 0
W/AwContents( 4583): nativeOnDraw failed; clearing to background color.
I/ActivityManager(  962): Displayed com.example.hello/.MainActivity: +371ms
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
I/InputMethodManagerService(  962): IME STATUS OFF
W/AwContents( 4583): nativeOnDraw failed; clearing to background color.
I/ActivityManager( 4583): Timeline: Activity_idle id: android.os.BinderProxy@42a7a278 time:42740
I/ActivityManager(  962): Waited long enough for: ServiceRecord{434f3a78 u0 com.lge.slideaside/.MainService}
I/chromium( 4583): [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 4583): Unable to open asset URL: file:///android_asset/www/jxcore.js
D/JsMessageQueue( 4583): Set native->JS mode to OnlineEventsBridgeMode
D/dalvikvm( 4583): Trying to load lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42a7e770
D/dalvikvm( 4583): Added shared lib /data/app-lib/com.example.hello-1/libjxcore.so 0x42a7e770
D/jxcore_app_log( 4583): JniHelper::setJavaVM(0x41a2e808), pthread_self() = 1634916176
D/JX-Cordova( 4583): jxcore cordova android initializing
W/jxcore-log( 4583): Initializing JXcore engine
W/jxcore-log( 4583): JXcore engine is ready
W/jxcore-log( 4583): Starting JXcore engine
D/ActivityManager(  962): no-history finish of ActivityRecord{42eb1968 u0 com.android.settings/.UsbSettings t2}
V/ActivityManager(  962): Finishing activity token=Token{436529d0 ActivityRecord{42eb1968 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
V/ActivityManager(  962): Moving to FINISHING: ActivityRecord{42eb1968 u0 com.android.settings/.UsbSettings t2 f}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ec96c8 u0 com.example.hello/.MainActivity t3}
D/UsbSettings( 2612): [AUTORUN] onStop()
I/ActivityManager(  962): Timeline: Activity_windows_visible id: ActivityRecord{42ec96c8 u0 com.example.hello/.MainActivity t3} time:43137
V/ActivityManager(  962): Moving to STOPPING: ActivityRecord{42eb1968 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
V/ActivityManager(  962): Moving to STOPPED: ActivityRecord{42eb1968 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
W/jxcore-log( 4583): Platform android
W/jxcore-log( 4583): 
W/jxcore-log( 4583): Process ARCH arm
W/jxcore-log( 4583): 
,I/jxcore-log( 4583): JXcore Cordova bridge is ready!
I/jxcore-log( 4583): 
,W/jxcore-log( 4583): JXcore engine is started
,I/chromium( 4583): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/chromium( 4583): [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/jxcore-log( 4583): >> LGE-LG-D802
E/jxcore-log( 4583): 
I/jxcore-log( 4583): Total memory 1943035904
I/jxcore-log( 4583): 
I/jxcore-log( 4583): Free memory 417165312
I/jxcore-log( 4583): 
I/jxcore-log( 4583): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4583): 
I/jxcore-log( 4583): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 4583): 
I/jxcore-log( 4583): userPath [ 'www' ]
I/jxcore-log( 4583): 
I/jxcore-log( 4583): Size 1080 1776
I/jxcore-log( 4583): 
I/jxcore-log( 4583): Screen Brightness 255
I/jxcore-log( 4583): 
E/jxcore-log( 4583): Dummy Error Log.
E/jxcore-log( 4583): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/jxcore-log( 4583): getBuffer is called!!!!
I/jxcore-log( 4583): 
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/CheckinService( 1887): Done disabling old GoogleServicesFramework version
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2066): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2066): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2066): nl80211: survey data missing!
,D/WifiStateMachine(  962): handleMessage: X
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/Parcel  (  477): Reading a NULL string not supported here.
,E/Parcel  (  477): Reading a NULL string not supported here.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/GAV2    ( 4503): Thread[GAThread,5,main]: No campaign data found.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ConfigService( 1530): onDestroy
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/dalvikvm( 1156): GC_CONCURRENT freed 1260K, 6% free 25448K/26884K, paused 10ms+2ms, total 41ms
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  962): Killing 3581:com.android.calendar/u0a15 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{435261b8 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ec96c8 u0 com.example.hello/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.460068 Y: -0.405899 Z: 9.763611 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.460068 .y:-0.405899 .z:9.763611
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,V/qcom_sensors_hal(  962): hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,D/qcom_sensors_hal(  962): hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
,V/qcom_sensors_hal(  962): hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,V/qcom_sensors_hal(  962): hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,V/qcom_sensors_hal(  962): hal_process_report_ind: X: -0.461014 Y: -0.403091 Z: 9.761871 
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.461014 .y:-0.403091 .z:9.761871
,D/qcom_sensors_hal(  962): _hal_sensors_data_poll: cnt: 36
,D/qcom_sensors_hal(  962): hal_wait_for_response: timeout=0
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
,D/WifiStateMachine(  962): handleMessage: E msg.what=131155
,D/WifiStateMachine(  962): processMsg: ConnectedState
,D/WifiStateMachine(  962): processMsg: L2ConnectedState
,D/WifiNative-wlan0(  962): doString: SIGNAL_POLL
D/wpa_supplicant( 2066): RX ctrl_iface - hexdump(len=11): 53 49 47 4e 41 4c 5f 50 4f 4c 4c
,D/wpa_supplicant( 2066): wlan0: Control interface command 'SIGNAL_POLL'
,D/wpa_supplicant( 2066): nl80211: survey data missing!
,E/Parcel  (  477): Reading a NULL string not supported here.
,E/Parcel  (  477): Reading a NULL string not supported here.
,D/WifiStateMachine(  962): handleMessage: X
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
,D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/BluetoothManagerService(  962): Message: 20
,D/BluetoothManagerService(  962): Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@43428210:true
,D/BluetoothManagerService(  962): checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,D/BluetoothManagerService(  962): disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@43424e80 mBinding = false
,D/BluetoothManagerService(  962): Message: 2
,D/BluetoothManagerService(  962): Sending off request.
,D/BluetoothAdapterService(1118466416)( 1215): disable() called...
D/BluetoothAdapterState( 1215): CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
,I/BluetoothAdapterState( 1215): Bluetooth adapter state changed: 12-> 13
,D/BluetoothAdapterService( 1215): Broadcasting updateAdapterState() to 1 receivers.
I/bt-btif ( 1215): btif_set_adapter_property type: 7, len 4, 0x42b59b20
I/bt-btif ( 1215): set property scan mode : 0
,I/bt-btif ( 1215): bta_dm_sm_execute event:0x3
,I/bt-btif ( 1215): btif_in_storage_request_copy_cb,
I/BluetoothAdapterState( 1215): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
I/bt-btif ( 1215): execute storage request event : 2
,I/bt-btif ( 1215): type: 7, len 4, 0x606dcbc6
D/bt-btif ( 1215): in, bd addr:, prop type:7, len:4
,I/bt-btif ( 1215): HAL bt_hal_cbacks->adapter_properties_cb
,D/BluetoothAdapterState( 1215): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,I/bluedroid( 1215): disable 1
I/bt-btif ( 1215): BTIF DISABLE BLUETOOTH:: current btif_core_radio_refcount: 1, btif_core_state: 2, btif_core_cb.dut_mode: 0
,D/bt-btif ( 1215): h:6, process_cmd_sock return false, exit...
D/bt-btif ( 1215): socket poll thread exiting, h:6
D/bt-btif ( 1215): cleanup slot:1, fd:89, scn:19, sdp_handle:0x1000a
,D/bt-btif ( 1215): del_rfc_sdp_rec: handle:0x1000a
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
V/BluetoothPbapService( 1215): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/BluetoothManagerService(  962): Message: 60
I/bt-btif ( 1215): BTA_JvDeleteRecord
D/bt-sdp  ( 1215): SDP_DeleteRecord ok, num_records:12
I/bt-btif ( 1215): BTA_JvRfcommStopServer
E/bt-btif ( 1215): bta_jv_rfcomm_stop_server
D/bt-btif ( 1215): find_rfc_pcb(): FOUND rfc_cb_handle 0x1, port.jv_handle: 0x81, state: 4, rfc_cb->handle: 0x81
D/bt-btif ( 1215): bta_jv_rfcomm_stop_server: p_pcb:0x60d870e8, p_pcb->port_handle:6
D/bt-btif ( 1215): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60d870e8, user:1, state:4, jv handle: 0x81
D/bt-btif ( 1215): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:19, user_data:1
D/bt-btif ( 1215): bta_jv_rfcomm_stop_server: sec id in use:2, rfc_cb in use:2
D/bt-btif ( 1215): cleanup slot:2, fd:91, scn:6, sdp_handle:0x1000b
D/bt-btif ( 1215): del_rfc_sdp_rec: handle:0x1000b
V/BluetoothMapService( 1215): Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/BluetoothManagerService(  962): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
I/bt-btif ( 1215): BTA_JvDeleteRecord
D/BluetoothManagerService(  962): Bluetooth State Change Intent: 12 -> 13
D/bt-sdp  ( 1215): SDP_DeleteRecord ok, num_records:11
I/bt-btif ( 1215): BTA_JvRfcommStopServer
E/bt-btif ( 1215): bta_jv_rfcomm_stop_server
D/bt-btif ( 1215): find_rfc_pcb(): FOUND rfc_cb_handle 0x2, port.jv_handle: 0x82, state: 4, rfc_cb->handle: 0x82
D/bt-btif ( 1215): bta_jv_rfcomm_stop_server: p_pcb:0x60d870fc, p_pcb->port_handle:7
D/bt-btif ( 1215): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60d870fc, user:2, state:4, jv handle: 0x82
D/bt-btif ( 1215): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:6, user_data:2
D/bt-btif ( 1215): bta_jv_rfcomm_stop_server: sec id in use:1, rfc_cb in use:1
D/bt-btif ( 1215): cleanup slot:3, fd:96, scn:12, sdp_handle:0x1000c
E/BtOppRfcommListener( 1215): Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
D/bt-btif ( 1215): del_rfc_sdp_rec: handle:0x1000c
I/bt-btif ( 1215): BTA_JvDeleteRecord
D/bt-sdp  ( 1215): SDP_DeleteRecord ok, num_records:10
I/bt-btif ( 1215): BTA_JvRfcommStopServer
E/bt-btif ( 1215): bta_jv_rfcomm_stop_server
D/bt-btif ( 1215): find_rfc_pcb(): FOUND rfc_cb_handle 0x3, port.jv_handle: 0x83, state: 4, rfc_cb->handle: 0x83
D/bt-btif ( 1215): bta_jv_rfcomm_stop_server: p_pcb:0x60d87110, p_pcb->port_handle:8
D/bt-btif ( 1215): bta_jv_free_sr_rfc_cb: max_sess:7, curr_sess:1, p_pcb:0x60d87110, user:3, state:4, jv handle: 0x83
D/bt-btif ( 1215): bta_jv_free_sr_rfc_cb: state: BTA_JV_ST_SR_LISTEN, scn:12, user_data:3
D/bt-btif ( 1215): bta_jv_rfcomm_stop_server: sec id in use:0, rfc_cb in use:0
D/bt-btif ( 1215): leaving
D/bt-sdp  ( 1215): SDP_DeleteRecord ok, num_records:9
I/bt-btif ( 1215): Removing UUID=0x1116 from EIR
D/bt-btif ( 1215): BTA is generating EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04031460
I/bt-btif ( 1215): Removing UUID=0x1116 from EIR
D/bt-btif ( 1215): BTA is generating EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04031460
I/bt-btif ( 1215): Removing UUID=0x1117 from EIR
D/bt-btif ( 1215): BTA is generating EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04031460
I/bt-btif ( 1215): Removing UUID=0x1115 from EIR
D/bt-btif ( 1215): BTA is generating EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04011460
I/bt-btif ( 1215): bta_dm_sm_execute event:0x1
D/bt-btif ( 1215): bta_sys_disable: module 0
W/bt-btif ( 1215): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
I/bt-btif ( 1215): AG evt (hdl 0x0001): State 0, Event 0x0501
D/bt-btif ( 1215): bta_ag_del_records 0
D/bt-sdp  ( 1215): SDP_DeleteRecord ok, num_records:8
I/bt-btif ( 1215): Removing UUID=0x1112 from EIR
I/,bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000494 04001460
D/bt-btif ( 1215): bta_ag_del_records 1
D/bt-sdp  ( 1215): SDP_DeleteRecord ok, num_records:7
I/bt-btif ( 1215): Removing UUID=0x111F from EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000494 00001460
D/bt-btif ( 1215): bta_ag_scb_dealloc 1
W/bt-obex ( 1215): Ignore event 10 in state 1
D/bt-sdp  ( 1215): SDP_DeleteRecord ok, num_records:6
I/bt-btif ( 1215): Removing UUID=0x1106 from EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000494 00001420
D/bt-sdp  ( 1215): SDP_DeleteRecord ok, num_records:5
I/bt-btif ( 1215): Removing UUID=0x112D from EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000490 00001420
I/bt-btif ( 1215): bta_av_del_rc  handle: 0 status=0x10, rc_acp_handle:0, idx:1
I/bt-btif ( 1215): end del_rc handle: 255 status=0x0, rc_acp_handle:255, lidx:0
D/bt-btif ( 1215): bta_av_cleanup
D/bt-btif ( 1215): deregistered 64(h65)
D/bt-sdp  ( 1215): SDP_DeleteRecord ok, num_records:4
I/bt-btif ( 1215): Removing UUID=0x110A from EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000490 00001020
D/bt-btif ( 1215): audio 0x0, video: 0x0, disable:1
D/bt-sdp  ( 1215): SDP_DeleteRecord ok, num_records:3
I/bt-btif ( 1215): Removing UUID=0x110C from EIR
I/bt-btif ( 1215): bta_dm_eir_update_uuid UUID bit mask=0x00000490 00000020
D/bt-btif ( 1215): audio 0x0, video: 0x0, disable:0
W/bt-l2cap( 1215): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1215): L2CAP - PSM: 0x0017 not found for deregistration
D/bt-btif ( 1215): bta_gattc_disable
I/bt-att  ( 1215): GATT_Deregister gatt_if=3
I/bt-att  ( 1215): GATT_Listen gatt_if=3
D/bt-btif ( 1215): bta_dm_gattc_callback event = 1
I/bt-att  ( 1215): GATT_Deregister gatt_if=4
I/bt-att  ( 1215): GATT_Listen gatt_if=4
D/bt-btif ( 1215): bta_hh_gattc_callback event = 1
I/bt-btif ( 1215): bta_dm_search_sm_execute state:0, event:0x206
E/bt-btif ( 1215): bta_gattc_deregister Deregister Failed, unknown client cif
D/bt-btif ( 1215): btif_hf_upstreams_evt: event=BTA_AG_DISABLE_EVT
D/bt-btif ( 1215): btif_fts_upstreams_evt: event=BTA_FTS_DISABLE_EVT
I/bt-btif ( 1215): File Transfer: Disable complete
D/bt-btif ( 1215): btif_hh_upstreams_evt: event=BTA_HH_DISABLE_EVT
D/IOP_DB_BT( 1215): db_close: nbr users 0
D/IOP_DB_BT( 1215): db_close: free database
D/btif_config_util( 1215): btif_config_save_file(L153): in file name:/data/misc/bluedroid/bt_config.new
,D/LGBluetoothAPIService( 1156): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothMapService( 1215): onReceive
,D/BluetoothMapService( 1215): STATE_TURNING_OFF
D/BluetoothMapService( 1215): MAP Service closeService in
D/LGBluetoothMapAdapter( 1215): [BTUI] LGBluetoothMapAdapter cleanup
,V/BluetoothMapService( 1215): MAP Service closeService out
V/BtOppService( 1215): Receiver DISABLED_ACTION 
I/BtOppRfcommListener( 1215): stopping Accept Thread
,V/BtOppRfcommListener( 1215): close mBtServerSocket
V/BtOppRfcommListener( 1215): waiting for thread to terminate
,I/BtOppRfcommListener( 1215): BluetoothSocket listen thread finished
,V/BtOppRfcommListener( 1215): done waiting for thread to terminate
,V/BtOppService( 1215): onDestroy
,D/LGBluetoothOppAdapter( 1215): [BTUI] LGBluetoothOppAdapter cleanup
,D/WifiService(  962): New client listening to asynchronous messages
,D/WifiService(  962): setWifiEnabled: false pid=4583, uid=10312
E/WifiService(  962): Invoking mWifiStateMachine.setWifiEnabled
,I/WifiService(  962): setWifiEnabled startWifiDelaySendMsg true
,D/WifiStateMachine(  962): handleMessage: E msg.what=131084
,D/WifiStateMachine(  962): processMsg: ConnectedState
D/WifiStateMachine(  962): processMsg: L2ConnectedState
D/WifiStateMachine(  962): processMsg: ConnectModeState
D/WifiStateMachine(  962): processMsg: DriverStartedState
,D/WifiStateMachine(  962): processMsg: DriverStartedStateExt
D/WifiStateMachine(  962): processMsg: SupplicantStartedState
D/WifiStateMachine(  962): transitionTo: destState=WaitForP2pDisableState
,D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=SupplicantStartedState,active=true,parent=DefaultState
D/WifiStateMachine(  962): invokeExitMethods: ConnectedState
,W/Settings(  962): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/jxcore-log( 4583): ****TEST TOOK:  5219  ms ****
I/jxcore-log( 4583): 
,I/jxcore-log( 4583): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 4583): 
,D/WifiStateMachine(  962): invokeExitMethods: L2ConnectedState
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5010
D/WifiStateMachine(  962): invokeExitMethods: ConnectModeState
D/WifiStateMachine(  962): invokeExitMethods: DriverStartedState
D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING GET
D/wpa_supplicant( 2066): RX ctrl_iface - hexdump(len=23): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 47 45 54
D/wpa_supplicant( 2066): wlan0: Control interface command 'DRIVER WLS_BATCHING GET'
E/wpa_supplicant( 2066): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  962):    returned null
,E/WifiStateMachine(  962): Unexpected BatchedScanResults :null
D/WifiNative-wlan0(  962): doString: DRIVER WLS_BATCHING STOP
D/wpa_supplicant( 2066): RX ctrl_iface - hexdump(len=24): 44 52 49 56 45 52 20 57 4c 53 5f 42 41 54 43 48 49 4e 47 20 53 54 4f 50
D/wpa_supplicant( 2066): wlan0: Control interface command 'DRIVER WLS_BATCHING STOP'
,E/wpa_supplicant( 2066): wpa_driver_nl80211_driver_cmd: failed to issue private commands
,D/WifiNative-wlan0(  962):    returned null
D/WifiStateMachine(  962): invokeExitMethods: DriverStartedStateExt
,D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=2
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=2,startingIndex=2,Top=WaitForP2pDisableState
D/WifiStateMachine(  962): invokeEnterMethods: WaitForP2pDisableState
D/WifiMonitor(  962): WifiMonitorSingleton gotten
,D/WifiMonitor(  962): stopMonitoring(p2p0) = android.net.wifi.p2p.WifiP2pService$P2pStateMachine@433403a0
D/WifiP2pService(  962): InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  962): P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,D/WifiP2pService(  962): P2pDisablingState
D/WfdService( 1156): Waiting for Wifi disabling
,D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131205
,D/WifiStateMachine(  962): processMsg: WaitForP2pDisableState
D/WifiStateMachine(  962): transitionTo: destState=SupplicantStoppingState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  962): invokeExitMethods: WaitForP2pDisableState
D/WifiStateMachine(  962): invokeExitMethods: SupplicantStartedState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=1
,D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=SupplicantStoppingState
D/WifiStateMachine(  962): invokeEnterMethods: SupplicantStoppingState
D/WifiStateMachine(  962): Stopping DHCP and clearing IP
D/WifiStateMachine(  962): setSuspendOptimizationsNative: 1 true
,D/WifiNative-wlan0(  962): doBoolean: SET ps 1
D/WifiP2pService(  962): P2pDisablingState{ when=-7ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  962): p2p socket connection lost
D/WifiP2pService(  962): P2pDisabledState
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
E/LGBluetoothEventManager( 2612): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
D/wpa_supplicant( 2066): RX ctrl_iface - hexdump(len=8): 53 45 54 20 70 73 20 31
D/wpa_supplicant( 2066): wlan0: Control interface command 'SET ps 1'
D/wpa_supplicant( 2066): CTRL_IFACE SET 'ps'='1'
D/wpa_supplicant( 2066): nl80211: set_p2p_powersave (legacy_ps=1 opp_ps=-1 ctwindow=-1)
,D/WifiNative-wlan0(  962):    returned true
D/WifiNative-wlan0(  962): doBoolean: DRIVER BTCOEXMODE 2
D/wpa_supplicant( 2066): RX ctrl_iface - hexdump(len=19): 44 52 49 56 45 52 20 42 54 43 4f 45 58 4d 4f 44 45 20 32
D/wpa_supplicant( 2066): wlan0: Control interface command 'DRIVER BTCOEXMODE 2'
,D/wpa_supplicant( 2066): wpa_driver_nl80211_driver_cmd OK len = 0, 2
D/WifiNative-wlan0(  962):    returned true
,D/DhcpStateMachine(  962): RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,D/CommandListener(  264): Clearing all IP addresses on wlan0
,D/WifiStateMachine(  962): addressRemoved: 192.168.1.140/24 on wlan0 flags 128 scope 0
,V/BluetoothPbapReceiver( 1215): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1215): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
,V/BluetoothPbapReceiver( 1215): ***********state = 13
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
D/WifiP2pService(  962): P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
D/WifiP2pService(  962): DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,W/ContextImpl( 2612): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:156 com.android.settings.bluetooth.DockEventReceiver.onReceive:123 
D/DockEventReceiver( 2612): finishStartingService: stopping service
V/BluetoothPbapReceiver( 1215): ***********Calling start service!!!! with action = null
V/BluetoothPbapService( 1215): action: android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapService( 1215): state: 13
V/BluetoothPbapService( 1215): Pbap Service closeService in
D/WifiStateMachine(  962): addressRemoved: fe80::36fc:efff:fede:ae2/64 on wlan0 flags 128 scope 253
D/WifiStateMachine(  962): setDetailed state, old =CONNECTED and new state=DISCONNECTED
V/BluetoothPbapService( 1215): successfully stopped pbap service
V/BluetoothPbapService( 1215): Pbap Service closeService out
D/WifiStateMachine(  962): stopping supplicant
D/WifiMonitor(  962): WifiMonitorSingleton gotten
D/WifiNative-p2p0(  962): doBoolean: TERMINATE
,V/BluetoothPbapService( 1215): Pbap Service onDestroy
V/BluetoothPbapService( 1215): Pbap Service closeService in
V/BluetoothPbapService( 1215): Pbap Service closeService out
D/LGBluetoothPbapAdapter( 1215): [BTUI] cleanup
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=458752
,D/ConnectivityServiceHSM(  962): ConnectivityChange for WIFI: DISCONNECTED/DISCONNECTED
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5002
D/wpa_supplicant( 2066): RX global ctrl_iface - hexdump(len=9): 54 45 52 4d 49 4e 41 54 45
D/wpa_supplicant( 2066): p2p0: Removing interface p2p0
D/wpa_supplicant( 2066): p2p0: Request to deauthenticate - bssid=00:00:00:00:00:00 pending_bssid=00:00:00:00:00:00 reason=3 state=DISCONNECTED
D/wpa_supplicant( 2066): TDLS: Tear down peers
D/wpa_supplicant( 2066): p2p0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2066): p2p0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2066): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2066): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2066): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2066): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2066): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2066): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2066): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2066): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2066): p2p0: No keys have been configured - skip key clearing
D/WifiNative-p2p0(  962):    returned true
D/WifiStateMachine(  962): setWifiState: disabling
E/WifiStateMachine(  962): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  962): useWiFiOffloading() : false
E/WifiStateMachine(  962): CONFIG_LGE_WLAN_PATH : true
D/BluetoothPbap( 2612): Proxy object disconnected
,D/PbapServerProfile( 2612): Bluetooth service disconnected
D/WifiHS20(  962): hidePasspointNotification off =false
,D/QcConnectivityService(  962): tryFailover: set mActiveDefaultNetwork=-1, prevNetType=1
V/WfdStateTracker( 1156): handleWifiStateChangedEvent: 0
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131213
D/WifiStateMachine(  962): processMsg: SupplicantStoppingState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): handleMessage: X
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  477): Reading a NULL string not supported here.
D/WifiStateMachine(  962): handleMessage: E msg.what=131213
W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
E/Parcel  (  477): Reading a NULL string not supported here.
D/QCNEA   (  477): |CAC| readCallback: read len:492, ret:0, errno:0
E/Parcel  (  477): Reading a NULL string not supported here.
D/QCNEA   (  477): |CAC| updateWlanNetCfgInfo
D/QCNEA   (  477): |CAC| updateNetCfgInfo
V/QCNEA   (  477): |CAC| *********************************************
V/QCNEA   (  477): |CAC|                   Netconfig               
V/QCNEA   (  477): |CAC| *********************************************
V/QCNEA   (  477): |CAC| 	NetConfig: Net type   =3
V/QCNEA   (  477): |CAC| 	NetConfig: subtype rl =0
V/QCNEA   (  477): |CAC| 	NetConfig:         fl =0
V/QCNEA   (  477): |CAC| 	NetConfig: ip4        =0.0.0.0
D/WifiStateMachine(  962): processMsg: SupplicantStoppingState
V/QCNEA   (  477): |CAC| 	NetConfig: ip6        =::
V/QCNEA   (  477): |CAC| 	NetConfig: mtu        =0
V/QCNEA   (  477): |CAC| 	NetConfig: Default    =true
V/QCNEA   (  477): |CAC| *********************************************
D/QCNEA   (  477): |CAC| Received bssid= 
D/QCNEA   (  477): |CAC| net type = 3
V/QCNEA   (  477): |CAC| 	bssid           =00:00:00:00:00:00
D/QCNEA   (  477): |CAC| Received ssid= <unknown ssid>
V/QCNEA   (  477): |CAC| 	ssid           =NG700
V/QCNEA   (  477): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  477): |CAC| 	DNS v4        =0.0.0.0
V/QCNEA   (  477): |CAC| *********************************************
D/QCNEA   (  477): |CAC| updateCache: CAS_WLAN_NETCFG_INFO
D/QCNEA   (  477): |CAC| dispatching netcfgupdate for wlan
D/QCNEA   (  477): |CAC| dispatchNetCfg: updating:0xb76a58dc
D/QCNEA   (  477): |CAC| readCallback: read len:0, ret:-1, errno:11
D/WifiOffDelayIfNotUsed(  962): NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): handleMessage: X
I/WifiServiceExtension(  962): WIFI_STATE_CHANGED_ACTION [0]
V/WfdStateTracker( 1156): WfdStateTracker handleDirectStateChangedEvent: 6
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
D/LGBluetoothAuthorization( 2612): [BTUI] cancel All Notification
I/bt-btif ( 1215): btif_dm_cancel_discovery
,I/bt-btif ( 1215): bta_dm_search_sm_execute state:0, event:0x201
D/QcConnectivityService(  962): Attempting to switch to mobile
D/QcConnectivityService(  962): Attempting to switch to BLUETOOTH_TETHER
,D/QcConnectivityService(  962): handleConnectivityChange: preConnState=1 connState=2
D/KeyguardUpdateMonitor( 1142): received broadcast android.net.wifi.STATE_CHANGE
D/BluetoothPermissionRequest( 2612): onReceive
D/LGBluetoothAuthorization( 2612): [BTUI] cancel All Notification
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
I/RemoteControlStatusBar( 1142): Receive Broadcast [Action]:android.net.wifi.STATE_CHANGE
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '37 interface route remove wlan0 default 192.168.1.0 24 0.0.0.0' failed with '400 37 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '38 interface route remove wlan0 default 0.0.0.0 0 192.168.1.1' failed with '400 38 Failed to remove route from default table (No such process)'
D/NetworkManagementService(  962): Interface [ wlan0 ] is already down, so modifyRoute is faild. error = com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '39 interface route remove wlan0 default 192.168.1.1 32 0.0.0.0' failed with '400 39 Failed to remove route from default table (No such process)'
V/        (  264): RouteController
D/LGBluetoothResetSettingReceiver( 2612): return without doing reset settings.
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
V/BluetoothOppReceiver( 1215): Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
D/BluetoothOppNotification( 1215): [BTUI] cancel opp incoming file confirm notification
D/BluetoothOppNotification( 1215): [BTUI] cancel opp active transfer file notification
V/        (  264): RouteController
V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,V/        (  264): RouteController
,I/ActivityManager(  962): Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=4683 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
V/        (  264): RouteController
,W/NetworkManagementService(  962): route cmd failed: 
W/NetworkManagementService(  962): com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '41 route del src v6 2' failed with '400 41 -6 rule del table 2: RTNETLINK answers: No such file or directory
W/NetworkManagementService(  962): '
W/NetworkManagementService(  962): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:413)
W/NetworkManagementService(  962): 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:340)
W/NetworkManagementService(  962): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:305)
W/NetworkManagementService(  962): 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:290)
W/NetworkManagementService(  962): 	at com.android.server.NetworkManagementService.delSrcRoute(NetworkManagementService.java:2480)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService.updateRoutes(QcConnectivityService.java:4270)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService.handleConnectivityChange(QcConnectivityService.java:4107)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService.handleDisconnect(QcConnectivityService.java:3164)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService.access$5700(QcConnectivityService.java:239)
W/NetworkManagementService(  962): 	at com.android.server.QcConnectivityService$ConnectivityServiceHSM$DefaultConnectivityState.processMessage(QcConnectivityService.java:5112)
W/NetworkManagementService(  962): 	at com.android.internal.util.StateMachine$SmHandler.processMsg(StateMachine.java:966)
W/NetworkManagementService(  962): 	at com.android.internal.util.StateMachine$SmHandler.handleMessage(StateMachine.java:789)
W/NetworkManagementService(  962): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/NetworkManagementService(  962): 	at android.os.Looper.loop(Looper.java:136)
W/NetworkManagementService(  962): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,D/NetUtils(  962): android_net_utils_resetConnections in env=0x61f77518 clazz=0x6c800001 iface=wlan0 mask=0x3
D/QcConnectivityService(  962): resetConnections(wlan0, 3)
,D/HyLog   ( 4683): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4683): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4683): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,V/NativeCrypto( 1530): Read error: ssl=0x63a5b040: I/O error during system call, Connection timed out
I/bt-btif ( 1215): bta_sys_sm_execute state:2, event:0x3
D/bt-btif ( 1215): bta_sys_hw_api_disable for 0, active modules: 0x0001
D/bt-btif ( 1215): bta_sys_disable: module 0
I/bt-btif ( 1215): bta_sys_sm_execute state:3, event:0x4
D/bt-btif ( 1215): bta_sys_hw_evt_disabled - module 0x0
D/bt-btif ( 1215):  bta_dm_sys_hw_cback with event: 0
I/bt-btif ( 1215): btif_dm_upstreams_cback  ev: BTA_DM_DISABLE_EVT
I/bt-btif ( 1215): btif_disable_bluetooth_evt()::btif_core_cb: is_radio_req: 0, radio_ref_count: 0, state: 4
I/bt-btif ( 1215): HC lib lpm enable=0 return 0
D/bt-btif ( 1215): bte_main_disable
D/bt-btif ( 1215): bte_hci_disable
D/bt_hwcfg( 1215): hw_epilog_process
D/bt-btif ( 1215): audio 0x0, video: 0x0, disable:0
W/bt-l2cap( 1215): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1215): L2CAP - PSM: 0x0017 not found for deregistration
D/bt-btif ( 1215): audio 0x0, video: 0x0, disable:1
W/bt-l2cap( 1215): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1215): L2CAP - PSM: 0x0017 not found for deregistration
D/bt-btif ( 1215): audio 0x0, video: 0x0, disable:0
W/bt-l2cap( 1215): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 1215): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-btif ( 1215): ag scb idx 1 not allocated
,E/bt-btif ( 1215): BTA AG is already disabled, ignoring ...
V/NativeCrypto( 1530): SSL shutdown failed: ssl=0x63a5b040: I/O error during system call, Broken pipe
,I/bt-btif ( 1215): HC lpm_result_cb 0
,I/ActivityManager(  962): Killing 4180:com.google.android.talk/u0a77 (adj 15): empty #17
,D/AuthorizationBluetoothService( 1530): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,E/JavaBinder(  962): !!! FAILED BINDER TRANSACTION !!!
D/Nat464Xlat(  962): requiresClat: netType=1, hasIPv4Address=false
,W/ActivityManager(  962): Failed to clear dns cache for: com.google.android.talk
D/wpa_supplicant( 2066): p2p0: Cancelling scan request
D/wpa_supplicant( 2066): p2p0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2066): p2p0: Cancelling authentication timeout
D/wpa_supplicant( 2066): p2p0: P2P: Disable P2P since removing the management interface is being removed
D/wpa_supplicant( 2066): P2P: Stopping find
D/wpa_supplicant( 2066): P2P: Clear timeout (state=IDLE)
D/wpa_supplicant( 2066): P2P: State IDLE -> IDLE
D/wpa_supplicant( 2066): wpa_driver_set_ap_wps_p2p_ie: Entry
D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=104
,D/ConnectivityServiceHSM(  962): Actual State: DefaultConnectivityState, Current State: DefaultConnectivityState.processMessage what=5006
,D/LocSvc_java(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, smCause: 0, isConnectedToProvisioningNetwork: false
,D/GpsLocationProvider(  962): updateNetworkState unavailable info: NetworkInfo: type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, smCause: 0, isConnectedToProvisioningNetwork: false
D/QcConnectivityService(  962): handleInetConditionChange: no active default network - ignore
,D/bt_hwcfg( 1215): hw_epilog_cback Opcode:0x0C03 Status: 0
,I/ActivityManager(  962): Start proc com.lge.wireless_storage for broadcast com.lge.wireless_storage/.NetworkReceiver: pid=4703 uid=10101 gids={50101, 1028, 1015, 3003}
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{435261b8 stackId=1, 2 tasks}
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
,I/TelephonyProvider( 1449): getPreferredApnId: subscription=0
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ec96c8 u0 com.example.hello/.MainActivity t3}
,D/LocSvc_java(  962): getAGpsConnectionInfo connType - 4
,D/LocSvc_java(  962): ignore wifi update if we are not in OPENING or CLOSING
,D/wpa_supplicant( 2066): netlink: Operstate: linkmode=0, operstate=6
D/wpa_supplicant( 2066): nl80211: Set mode ifindex 22 iftype 2 (STATION)
D/wpa_supplicant( 2066): nl80211: Unsubscribe mgmt frames handle 0xb8992c28 (mode change)
,I/wpa_supplicant( 2066): p2p0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 2066): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
I/wpa_supplicant( 2066): [ITEC] Close WIFLUS socket interface - START
I/wpa_supplicant( 2066): [ITEC] Close WIFLUS read interface - DONE
I/wpa_supplicant( 2066): HY wiflus comm channel de-initialized : wiflus = 0
D/wpa_supplicant( 2066): Control interface directory not empty - leaving it behind
D/wpa_supplicant( 2066): wlan0: Removing interface wlan0
D/wpa_supplicant( 2066): wlan0: Request to deauthenticate - bssid=c0:ff:d4:d3:aa:48 pending_bssid=00:00:00:00:00:00 reason=3 state=COMPLETED
D/wpa_supplicant( 2066): TDLS: Tear down peers
,D/wpa_supplicant( 2066): wpa_driver_nl80211_disconnect(reason_code=3)
,D/WifiMonitor(  962): Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,D/WifiMonitor(  962): Dropping event because monitor (p2p0) is stopped
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
E/BatteryObserver( 1156): usb Uevent not necessary.
,D/HyLog   ( 4703): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4703): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4703): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/wpa_supplicant( 2066): wlan0: Event DEAUTH (12) received
D/wpa_supplicant( 2066): wlan0: Deauthentication notification
D/wpa_supplicant( 2066): wlan0:  * reason 3 (locally generated)
D/wpa_supplicant( 2066): Deauthentication frame IE(s) - hexdump(len=0): [NULL]
I/wpa_supplicant( 2066): wlan0: CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1
D/wpa_supplicant( 2066): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
,D/wpa_supplicant( 2066): wlan0: Auto connect disabled: do not try to re-connect
D/wpa_supplicant( 2066): wlan0: Ignore connection failure indication since interface has been put into disconnected state
D/wpa_supplicant( 2066): TDLS: Remove peers on disassociation
D/wpa_supplicant( 2066): wlan0: Disconnect event - remove keys
D/wpa_supplicant( 2066): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2066): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=1 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2066): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=2 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2066): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0x0 key_idx=3 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2066): wpa_driver_nl80211_set_key: ifindex=23 (wlan0) alg=0 addr=0xb8982d6c key_idx=0 set_tx=0 seq_len=0 key_len=0
D/wpa_supplicant( 2066):    addr=c0:ff:d4:d3:aa:48
D/wpa_supplicant( 2066): wlan0: State: COMPLETED -> DISCONNECTED
D/wpa_supplicant( 2066): wpa_driver_nl80211_set_operstate: operstate 1->0 (DORMANT)
,D/wpa_supplicant( 2066): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2066): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2066): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2066): EAPOL: SUPP_PAE entering state DISCONNECTED
D/wpa_supplicant( 2066): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2066): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
,D/wpa_supplicant( 2066): EAPOL: SUPP_BE entering state INITIALIZE
D/wpa_supplicant( 2066): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2066): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2066): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2066): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2066): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2066): EAPOL: External notification - EAP success=0
D/wpa_supplicant( 2066): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2066): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2066): wlan0: No keys have been configured - skip key clearing
D/wpa_supplicant( 2066): wlan0: State: DISCONNECTED -> DISCONNECTED
D/wpa_supplicant( 2066): wpa_driver_nl80211_set_operstate: operstate 0->0 (DORMANT)
D/wpa_supplicant( 2066): netlink: Operstate: linkmode=-1, operstate=5
D/wpa_supplicant( 2066): EAPOL: External notification - portEnabled=0
D/wpa_supplicant( 2066): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2066): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2066): EAPOL: External notification - portValid=0
D/wpa_supplicant( 2066): EAPOL: Supplicant port status: Unauthorized
D/wpa_supplicant( 2066): nl80211: Set supplicant port unauthorized for 00:00:00:00:00:00
D/wpa_supplicant( 2066): wlan0: No keys have been configured - skip key clearing
W/wpa_supplicant( 2066): USIM:  scard_deinit function
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=c0:ff:d4:d3:aa:48 reason=3 locally_generated=1]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=c0:ff:d4:d3:aa:48 SSID=NG700]
D/WifiStateMachine(  962): handleMessage: E msg.what=147460
D/WifiStateMachine(  962): processMsg: SupplicantStoppingState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): handleMessage: X
,D/WifiStateMachine(  962): handleMessage: E msg.what=147462
D/WifiStateMachine(  962): processMsg: SupplicantStoppingState
D/WifiStateMachine(  962): processMsg: DefaultState
,D/WifiStateMachine(  962): handleMessage: X
,I/Wireless_Storage( 4703): CONNECT : WIFI_P2P_STATE_CHANGED_ACTION
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:platform, action:3
D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/HeadsetStateMachine( 1215): Disconnected process message: 10
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  962): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
W/Settings(  962): Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/Settings(  962): Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/HeadsetStateMachine( 1215): Disconnected process message: 10
I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 286 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
I/ActivityManager(  962): Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=4716 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
I/ActivityManager(  962): Killing 3926:com.google.android.gms.unstable/u0a6 (adj 15): empty #17
D/WifiController(  962): battery changed pluggedType: 2
,D/HyLog   ( 4716): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4716): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4716): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{435261b8 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ec96c8 u0 com.example.hello/.MainActivity t3}
,I/PCSuite ( 4716): [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,D/DhcpStateMachine(  962): StoppedState
D/WifiStateMachine(  962): handleMessage: E msg.what=196614
D/WifiStateMachine(  962): processMsg: SupplicantStoppingState
D/WifiStateMachine(  962): processMsg: DefaultState
,D/WifiStateMachine(  962): handleMessage: X
D/PCSuite ( 4716): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4716): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,I/ActivityManager(  962): Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=4732 uid=10096 gids={50096, 1023, 1028, 1015, 3003, 3002}
,I/ActivityManager(  962): Killing 2139:android.process.media/u0a23 (adj 15): empty #17
,D/wpa_supplicant( 2066): wlan0: BSS: Remove id 0 BSSID c0:ff:d4:d3:aa:4a SSID 'NG7005g' due to wpa_bss_flush
D/wpa_supplicant( 2066): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2066): wlan0: BSS: Remove id 1 BSSID c0:ff:d4:d3:aa:48 SSID 'NG700' due to wpa_bss_flush
D/wpa_supplicant( 2066): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2066): wlan0: BSS: Remove id 2 BSSID c2:ff:d4:d3:aa:48 SSID '01ABC' due to wpa_bss_flush
D/wpa_supplicant( 2066): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2066): wlan0: BSS: Remove id 3 BSSID 38:f8:89:11:e9:11 SSID 'Gonzos' due to wpa_bss_flush
D/wpa_supplicant( 2066): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2066): wlan0: BSS: Remove id 4 BSSID 64:7c:34:12:7f:81 SSID 'UPC5999698' due to wpa_bss_flush
D/wpa_supplicant( 2066): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2066): wlan0: BSS: Remove id 5 BSSID 06:7c:34:12:7f:81 SSID 'UPC Wi-Free' due to wpa_bss_flush
D/wpa_supplicant( 2066): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
D/wpa_supplicant( 2066): wlan0: Cancelling scan request
D/wpa_supplicant( 2066): wlan0: P2P: Station mode scan operation not pending anymore (sta_scan_pending=0 p2p_cb_on_scan_complete=0)
D/wpa_supplicant( 2066): wlan0: Cancelling authentication timeout
,D/AndroidRuntime( 4675): 
D/AndroidRuntime( 4675): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
I/bt_hci_bdroid( 1215): bt_hc_worker_thread exiting
,W/bt_userial( 1215): select_read return size <=0:0, exiting userial_read_thread
I/bt_userial_vendor( 1215): device fd = 84 close
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 c0:ff:d4:d3:aa:4a]
,D/AndroidRuntime( 4675): CheckJNI is OFF
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 1 c0:ff:d4:d3:aa:48]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 c2:ff:d4:d3:aa:48]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 38:f8:89:11:e9:11]
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 64:7c:34:12:7f:81]
,D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 06:7c:34:12:7f:81]
D/BTSNOOP-DISP( 1215): btsnoop_close
I/GKI_LINUX( 1215): GKI_destroy_task: GKI_destroy_task(0): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1215): gki_task_entry: gki_task task_id=0 [BTU] terminating
I/GKI_LINUX( 1215): GKI_destroy_task: GKI_destroy_task(): task [BTU] terminated
,I/GKI_LINUX( 1215): GKI_freeze: GKI_freeze
D/HyLog   ( 4732): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4732): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4732): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{435261b8 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ec96c8 u0 com.example.hello/.MainActivity t3}
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:rfkill, action:3
D/dalvikvm( 4675): Trying to load lib libjavacore.so 0x0
D/dalvikvm( 4675): Added shared lib libjavacore.so 0x0
D/dalvikvm( 4675): Trying to load lib libnativehelper.so 0x0
D/dalvikvm( 4675): Added shared lib libnativehelper.so 0x0
D/dalvikvm( 4675): No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
I/bt-btif ( 1215): HAL bt_hal_cbacks->adapter_state_changed_cb
D/BluetoothServiceJni( 1215): adapter_state_change_callback: Status is: 0
D/BluetoothAdapterState( 1215): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
W/BluetoothAdapterService( 1215): Stopping service com.broadcom.bt.service.hfp.BrcmHeadsetService
W/BluetoothAdapterService( 1215): Stopping service com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 1215): Stopping service com.android.bluetooth.hid.HidService
D/BrcmHeadsetService( 1215): Received stop request...Stopping profile...
W/BluetoothAdapterService( 1215): Stopping service com.android.bluetooth.hdp.HealthService
I/LGBluetoothHfpAdapter( 1215): [BTUI] LGBluetoothHfpAdapter cleanup
D/HeadsetStateMachine( 1215): Exit Disconnected: -1
W/LGBluetoothHeadsetServiceJni( 1215): Cleaning up Bluetooth Handsfree callback object
W/BluetoothAdapterService( 1215): Stopping service com.android.bluetooth.pan.PanService
D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42aa7170
D/BluetoothHeadset( 1449): Proxy object disconnected
D/BluetoothHeadset(  962): Proxy object disconnected
D/BluetoothHeadset( 1449): Proxy object disconnected
D/BluetoothHeadset( 1449): Proxy object disconnected
W/BluetoothAdapterService( 1215): Stopping service com.android.bluetooth.map.BluetoothMapService
D/A2dpService( 1215): Received stop request...Stopping profile...
W/BluetoothAdapterService( 1215): Stopping service com.android.bluetooth.gatt.GattService
D/BluetoothHeadset( 2612): Proxy object disconnected
D/HeadsetProfile( 2612): Bluetooth service disconnected
D/LGBluetoothA2dpAdapter( 1215): [BTUI] LGBluetoothA2dpAdapter cleanup
W/LGBluetoothA2dpServiceJni( 1215): Cleaning up Bluetooth Handsfree callback object
D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42aa7170
D/A2dpStateMachine( 1215): Exit Disconnected: -1
D/BluetoothA2dp(  962): Proxy object disconnected
W/BluetoothAdapterService( 1215): Stopping service com.broadcom.bt.service.sap.SapService
W/BluetoothAdapterService( 1215): Stopping service com.broadcom.bt.service.ftp.FTPService
D/HidService( 1215): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42aa7170
D/BluetoothA2dp( 2612): Proxy object disconnected
D/A2dpProfile( 2612): Bluetooth service disconnected
D/BluetoothAdapterState( 1215): Stopping profile services that were post enabled
D/BluetoothAdapterService(1118466416)( 1215): Message: 1
D/BluetoothAdapterService(1118466416)( 1215): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1215): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.hfp.BrcmHeadsetService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1215): Profile still running: com.broadcom.bt.service.sap.SapService
D/BluetoothInputDevice( 2612): Proxy object disconnected
D/HidProfile( 2612): Bluetooth service disconnected
D/HealthService( 1215): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42aa7170
D/HeadsetStateMachine( 1215): Unbinding service...
D/HeadsetPhoneState( 1215): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1215): [BTUI] listenForMultiSimPhoneState : start = false
D/HeadsetPhoneState( 1215): [BTUI] listenForPhoneState : start = false
D/LGBluetoothHfpManager( 1215): [BTUI] listenForMultiSimPhoneState : start = fa,lse
W/Brcm_BluetoothHeadsetServiceJni( 1215): Cleaning up Bluetooth Handsfree Interface...
I/bt-btif ( 1215): cleanup
D/bt-btif ( 1215): btif_disable_service: Current Services:0x120108
W/Brcm_BluetoothHeadsetServiceJni( 1215): Cleaning up Bluetooth Handsfree callback object
I/LGBluetoothHfpAdapter( 1215): [BTUI] LGBluetoothHfpAdapter cleanup
D/PanService( 1215): Received stop request...Stopping profile...
D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42aa7170
D/BluetoothTethering(  962): got CMD_CHANNEL_DISCONNECTED
E/BluetoothTethering(  962): attempted to stop reverse tether with nothing tethered
D/BluetoothPan(  962): BluetoothPAN Proxy object disconnected
D/BluetoothPan( 2612): BluetoothPAN Proxy object disconnected
D/PanProfile( 2612): Bluetooth service disconnected
D/BluetoothMapService( 1215): Received stop request...Stopping profile...
D/wpa_supplicant( 2066): netlink: Operstate: linkmode=0, operstate=6
D/BluetoothMapService( 1215): stop()
D/BluetoothMapService( 1215): MAP Service closeService in
D/LGBluetoothMapAdapter( 1215): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1215): MAP Service closeService out
D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42aa7170
D/BluetoothMap( 2612): Proxy object disconnected
D/MapProfile( 2612): Bluetooth service disconnected
D/BluetoothAdapterService(1118466416)( 1215): Message: 1
D/BluetoothAdapterService(1118466416)( 1215): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1215): onProfileServiceStateChange: serviceName=com.android.bluetooth.a2dp.A2dpService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1215): Profile still running: com.broadcom.bt.service.sap.SapService
D/BtGatt.DebugUtils( 1215): handleDebugAction() action=null
D/BtGatt.GattService( 1215): Received stop request...Stopping profile...
D/BtGatt.GattService( 1215): stop()
D/QRemote ( 4732): [QRemoteApplication.java:238:onCreate()] oooooo QRemoteApp onCreate....
D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42aa7170
I/bt-btif ( 1215): cleanup
I/bt-btif ( 1215): ## A2DP STOP MEDIA TASK ##
I/GKI_LINUX( 1215): GKI_destroy_task: GKI_destroy_task(2): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
D/bt-btif ( 1215): UIPC_Close : ch_id 5
D/bt-btif ( 1215): UIPC_Close : waiting for shutdown to complete
I/bt-btif ( 1215): UIPC SEND WAKE UP
I/bt-btif ( 1215): UIPC READ THREAD EXITING
I/bt-btif ( 1215): uipc_main_cleanup
I/bt-btif ( 1215): CLOSE CHANNEL 0
I/bt-btif ( 1215): CLOSE SERVER (FD 69)
D/bt-btif ( 1215): A2DP-CTRL-CHANNEL EVENT UIPC_CLOSE_EVT
I/bt-btif ( 1215): UIPC SEND WAKE UP
I/bt-btif ( 1215): CLOSE CHANNEL 1
I/bt-btif ( 1215): CLOSE CHANNEL 2
I/bt-btif ( 1215): CLOSE CHANNEL 3
I/bt-btif ( 1215): UIPC READ THREAD DONE
D/bt-btif ( 1215): UIPC_Close : shutdown complete
D/bt-btif ( 1215): MEDIA TASK EXITING
I/GKI_LINUX( 1215): gki_task_entry: gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 1215): GKI_destroy_task: GKI_destroy_task(): task [A2DP-MEDIA] terminated
D/bt-btif ( 1215): btif_disable_service: Current Services:0x120100
D/LGBluetoothAvrcpAdapter( 1215): [BTUI] cleanup
D/LGBluetoothAvrcpManager( 1215): [BTUI] terminateAvrcpManager
D/LGBluetoothAvrcpManager( 1215): [BTUI] cleanupPlayStatus() : mPlayStatus = 0
V/BluetoothAVRCP1.3ServiceJni( 1215): cleanupNativeAVRCP
I/bt-btif ( 1215): ## cleanup ##
D/bt-btif ( 1215): close_uinput
D/BluetoothAdapterService(1118466416)( 1215): Message: 1
D/BluetoothAdapterService(1118466416)( 1215): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1215): onProfileServiceStateChange: serviceName=com.android.bluetooth.hid.HidService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1215): Profile still running: com.broadcom.bt.service.sap.SapService
D/SapService( 1215): Received stop request...Stopping profile...
D/SapService( 1215): Stopping Bluetooth SapService
D/LGBluetoothSapAdapter( 1215): [BTUI] LGBluetoothSapAdapter cleanup
D/LGBluetoothSapManager( 1215): [BTUI] terminateSapManager
D/LgeBluetoothSimManager( 1449): [BTUI] SAP_DISABLE_EVT
D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42aa7170
D/**BluetoothFTPService( 1215): Received stop request...Stopping profile...
D/**BluetoothFTPService( 1215): Stopping Bluetooth FTP Service
V/BluetoothFTPServiceJni( 1215): closeFtpServerNative
I/bt-btif ( 1215): cleanup
D/bt-btif ( 1215): btif_disable_service: Current Services:0x120000
D/BluetoothAdapterService( 1215): getAdapterService(): returning com.android.bluetooth.btservice.AdapterService@42aa7170
W/BluetoothHidServiceJni( 1215): Cleaning up Bluetooth HID Interface...
I/bt-btif ( 1215): cleanup
W/bt-btif ( 1215): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 1215): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService(1118466416)( 1215): Message: 1
D/BluetoothAdapterService(1118466416)( 1215): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1215): onProfileServiceStateChange: serviceName=com.android.bluetooth.hdp.HealthService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1215): Profile still running: com.broadcom.bt.service.sap.SapService
W/BluetoothHealthServiceJni( 1215): Cleaning up Bluetooth Health Interface...
I/bt-btif ( 1215): cleanup
D/bt-btif ( 1215): Process name (droid.bluetooth)
D/bt-btif ( 1215): btif_disable_service: Current Services:0x120000
D/bt-btif ( 1215): btif_hl_disable
D/bt-btif ( 1215): btif_hl_signal_select_exit
D/bt-btif ( 1215): select unblocked ret=1
D/bt-btif ( 1215): btif_hl_select_wake_signaled, signal ret=1
D/bt-btif ( 1215): btif_hl_select_wake_signaled
D/bt-btif ( 1215): btif_hl_select_wake_reset
D/bt-btif ( 1215): btif_hl_select_wake_signaled, signal:2
D/bt-btif ( 1215): hl thread cleanup
D/bt-btif ( 1215): Exit hl_select_thread for btif_hl_signal_select_exit
W/BluetoothHealthServiceJni( 1215): Cleaning up Bluetooth Health object
W/LGBluetoothHealthServiceJni( 1215): Cleaning up Bluetooth Health object
D/QRemote ( 4732): [CarrierUtils.java:900:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D802
D/BluetoothAdapterService(1118466416)( 1215): Message: 1
D/BluetoothAdapterService(1118466416)( 1215): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1215): onProfileServiceStateChange: serviceName=com.android.bluetooth.pan.PanService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1215): Profile still running: com.broadcom.bt.service.sap.SapService
I/QRemote ( 4732): [CarrierUtils.java:901:getHardwareSettings()] oooooo getCountry :: EU
D/wpa_supplicant( 2066): nl80211: Set mode ifindex 23 iftype 2 (STATION)
D/wpa_supplicant( 2066): nl80211: Unsubscribe mgmt frames handle 0xb8983590 (mode change)
I/wpa_supplicant( 2066): wlan0: CTRL-EVENT-TERMINATING 
D/wpa_supplicant( 2066): CTRL_IFACE monitor send - hexdump(len=39): 2f 64 61 74 61 2f 6d 69 73 63 2f 77 69 66 69 2f 73 6f 63 6b 65 74 73 2f 77 70 61 5f 63 74 72 6c ...
I/wpa_supplicant( 2066): [ITEC] Close WIFLUS socket interface - START
I/wpa_supplicant( 2066): [ITEC] - NOT INITIALIZED - DONE
D/wpa_supplicant( 2066): Control interface directory not empty - leaving it behind
D/wpa_supplicant( 2066): Get randomness: len=20 entropy=0
D/dalvikvm( 4675): Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
D/Tethering(  962): InitialState.processMessage what=4
D/WifiMonitor(  962): Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
D/WifiStateMachine(  962): handleMessage: E msg.what=147458
D/WifiStateMachine(  962): processMsg: SupplicantStoppingState
D/WifiStateMachine(  962): Supplicant connection lost
D/WifiMonitor(  962): WifiMonitorSingleton gotten
D/wpa_supplicant( 2066): random: Updated entropy file /data/misc/wifi/entropy.bin (own_pool_ready=2)
I/QRemote ( 4732): [CarrierUtils.java:902:getHardwareSettings()] oooooo getCarrier :: OPEN
D/Tethering(  962): Exception adding default nw to upstreamIfaceTypes: java.lang.NullPointerException
I/QRemote ( 4732): [CarrierUtils.java:903:getHardwareSettings()] oooooo getArea :: COM
D/Tethering(  962): sendTetherStateChangedBroadcast 0, 0, 0
W/BluetoothPanServiceJni( 1215): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 1215): Cleaning up Bluetooth PAN callback object
D/BluetoothAdapterService(1118466416)( 1215): Message: 1
D/BluetoothAdapterService(1118466416)( 1215): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1215): onProfileServiceStateChange: serviceName=com.android.bluetooth.map.BluetoothMapService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1215): Profile still running: com.broadcom.bt.service.sap.SapService
D/BluetoothMapService( 1215): cleanup()
D/BluetoothMapService( 1215): MAP Service closeService in
D/LGBluetoothMapAdapter( 1215): [BTUI] LGBluetoothMapAdapter cleanup
V/BluetoothMapService( 1215): MAP Service closeService out
D/BluetoothAdapterService(1118466416)( 1215): Message: 1
D/BluetoothAdapterService(1118466416)( 1215): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1215): onProfileServiceStateChange: serviceName=com.android.bluetooth.gatt.GattService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1215): Profile still running: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService(1118466416)( 1215): Message: 1
D/BluetoothAdapterService(1118466416)( 1215): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1215): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.sap.SapService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1215): Profile still running: com.broadcom.bt.service.ftp.FTPService
W/BluetoothSAPServiceJni( 1215): ## WARNING : cleanupNative(L223): Cleaning up Bluetooth SAP Interface...##
I/bt-btif ( 1215): cleanup
D/bt-btif ( 1215): btif_disable_service: Current Services:0x100000
W/BluetoothSAPServiceJni( 1215): ## WARNING : cleanupNative(L229): Cleaning up Bluetooth SAP callback object##
D/BluetoothAdapterService(1118466416)( 1215): Message: 1
D/BluetoothAdapterService(1118466416)( 1215): MESSAGE_PROFILE_SERVICE_STATE_CHANGED
D/BluetoothAdapterService( 1215): onProfileServiceStateChange: serviceName=com.broadcom.bt.service.ftp.FTPService, state = 10, doUpdate = true
D/BluetoothAdapterService( 1215): All profile services stopped...
D/BluetoothFTPService( 1215): cleanup FTP Service
V/BluetoothFTPServiceJni( 1215): closeFtpServerNative
I/bt-btif ( 1215): cleanup
V/BluetoothFTPServiceJni( 1215): cleanupNative
W/BluetoothFTPServiceJni( 1215): Cleaning up Bluetooth FTP Server Interface...
W/BluetoothFTPServiceJni( 1215): Cleaning up Bluetooth FTP callback object
D/BluetoothFTPService( 1215): BluetoothFtpBinder.cleanup()
D/BluetoothFTPService( 1215): cleanup done
D/QRemote ( 4732): [CarrierUtils.java:904:getHardwareSettings()] oooooo Loading Config...
D/BluetoothAdapterState( 1215): CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
I/BluetoothAdapterState( 1215): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 1215): Broadcasting updateAdapterState() to 1 receivers.
D/BluetoothManagerService(  962): Message: 60
D/BluetoothManagerService(  962): MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
D/BluetoothManagerService(  962): Broadcasting onBluetoothStateChange(false) to 12 receivers.
D/BluetoothHeadset( 1449): onBluetoothStateChange: up=false
D/QRemote ( 4732): [CarrierUtils.java:918:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
I/BluetoothAdapterState( 1215): Entering OffState
D/BluetoothPbap( 2612): onBluetoothStateChange: up=false
D/BluetoothMap( 2612): onBluetoothStateChange: up=false
D/BluetoothA2dp(  962): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1449): onBluetoothStateChange: up=false
D/BluetoothHeadset(  962): onBluetoothStateChange: up=false
D/BluetoothHeadset( 2612): onBluetoothStateChange: up=false
D/BluetoothHeadset( 1449): onBluetoothStateChange: up=false
D/BluetoothInputDevice( 2612): onBluetoothStateChange: up=false
D/BluetoothA2dp( 2612): onBluetoothStateChange: up=false
D/BluetoothManagerService(  962): Calling onBluetoothServiceDown callbacks
D/BluetoothManagerService(  962): Broadcasting onBluetoothServiceDown() to 9 receivers.
D/BluetoothManagerService(  962): unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@43424e80 mBinding = false
D/BluetoothManagerService(  962): Sending unbind request.
D/BluetoothManagerService(  962): Bluetooth State Change Intent: 13 -> 10
D/BluetoothAdapterService(1118466416)( 1215): onUnbind, calling cleanup
D/BluetoothAdapterService(1118466416)( 1215): cleanup()
D/BluetoothAdapterService( 1215): Cleaning up adapter native....
I/bluedroid( 1215): cleanup 1
I/bt-btif ( 1215): btif_shutdown_bluetooth()::btif_core_cb: state: 0, is_radio_req: 0, radio_ref_count: 0, dut_mode: 0, shutdown_pending: 0
I/GKI_LINUX( 1215): GKI_destroy_task: GKI_destroy_task(1): OSRdyTbl: 1, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
D/bt-btif ( 1215): btif_disassociate_evt: notify DISASSOCIATE_JVM
I/bt-btif ( 1215): HAL bt_hal_cbacks->thread_evt_cb
E/bt-gki  ( 1215): gki_pool_usage:  0: size     64 cur   0 max  11  total  48
E/bt-gki  ( 1215): gki_pool_usage:  1: size    288 cur   0 max   3  total  26
E/bt-gki  ( 1215): gki_pool_usage:  2: size    660 cur   0 max  24  total  45
E/bt-gki  ( 1215): gki_pool_usage:  3: size   4112 cur   0 max   3  total 200
E/bt-gki  ( 1215): gki_pool_usage:  4: size   8108 cur   0 max   0  total  20
E/bt-gki  ( 1215): pool:  4: not allocated
E/bt-gki  ( 1215): gki_pool_usage:  5: size    748 cur   0 max   0  total  64
E/bt-gki  ( 1215): pool:  5: not allocated
E/bt-gki  ( 1215): gki_pool_usage:  6: size    268 cur   0 max   0  total  60
E/bt-gki  ( 1215): pool:  6: not allocated
E/bt-gki  ( 1215): gki_pool_usage:  7: size  10264 cur   0 max   0  total   2
E/bt-gki  ( 1215): pool:  7: not allocated
E/bt-gki  ( 1215): gki_pool_usage:  8: size    128 cur   3 max   3  total  30
E/bt-gki  ( 1215): gki_pool_usage:  9: size   8192 cur   0 max   0  total   5
E/bt-gki  ( 1215): pool:  9: not allocated
D/bt-btif ( 1215): btif task exiting
I/GKI_LINUX( 1215): gki_task_entry: gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 1215): GKI_destroy_task: GKI_destroy_task(): task [BTIF] terminated
I/GKI_LINUX( 1215): GKI_destroy_task: GKI_destroy_task(2): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1215): GKI_destroy_task: GKI_destroy_task(1): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1215): GKI_destroy_task: GKI_destroy_task(0): OSRdyTbl: 0, OSWaitEvt: 0x0, Tmr0R: 0, Tmr1R: 0, QFirst0: 0x0, QFirst2: 0x0
I/GKI_LINUX( 1215): GKI_exit_task: GKI_exit_task 2 done
I/GKI_LINUX( 1215): GKI_exit_task: GKI_exit_task 1 done
I/GKI_LINUX( 1215): GKI_exit_task: GKI_exit_task 0 done
D/bt-btif ( 1215): btif_shutdown_bluetooth done
I/BluetoothServiceJni( 1215): cleanupNative: return from cleanup
D/BluetoothAdapterService( 1215): Done cleaning up adapter native....
W/LGBluetoothServiceJni( 1215): Cleaning up Bluetooth Service callback object
D/QRemote ( 4732): [WiFiStateReceiver.java:106:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
D/LGBluetoothAPIService( 1156): [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
D/LGBluetoothAPIService( 1156): Message: 2
D/LGBluetoothAPIService( 1156): unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@43397f88 mBinding = false
D/LGBluetoothAPIService( 1156): Sending unbind request.
D/BluetoothAdapter( 1142): 1120329168: getState() :  mService = null. Returning STATE_OFF
D/LGBluetoothSettingsDBObserver( 1215): [BTUI] unregister observer for LG device name DB
D/BluetoothAdapterService(1118466416)( 1215): cleanup() done
D/BluetoothAdapterService(1118466416)( 1215): ****onDestroy()********
D/BtGatt.GattService( 1215): cleanup()
W/bt-btif ( 1215): GATTC Module not enabled/already disabled
W/bt-btif ( 1215): GATTS Module not enabled/already disabled
E/LGBluetoothEventManager( 2612): [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
D/LGBluetoothAPIServer( 1215): [BTUI] onUnbind()
D/LGBluetoothAPIServer( 1215): [BTUI] cleanup() done
D/LGBluetoothAPIServer( 1215): [BTUI] onDestroy()
D/LGBluetoothEventManager( 2612): [BTUI] clear device connection state
I/QRemote ( 4732): [WiFiStateReceiver.java:185:onReceive()] oooooo The network is disconnected.
D/PCSuite ( 4716): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
D/UsbSettingsReceiver( 2612): [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
D/UsbSettingsReceiver( 2612): [AUTORUN] sys.usb.config = boot,adb
D/UsbSettingsReceiver( 2612): [AUTORUN] sys.usb.state = boot,adb
D/UsbSettingsReceiver( 2612): [AUTORUN] persist.sys.usb.config = boot,adb
I/ActivityManager(  962): Killing 4412:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
D/UsbSettingsReceiver( 2612): [AUTORUN] onReceive() : app userid = 0, current userid = 0
I/Config  ( 2612): getOperator() : OPEN
D/UsbSettingsControl( 2612): [AUTORUN] getUsbConnected() : connected=true
D/UsbSettingsReceiver( 2612): [AUTORUN] onReceive() : availableList=[]
D/UsbSettingsReceiver( 2612): [AUTORUN] onReceive() : activeList=[]
D/UsbSettingsReceiver( 2612): [AUTORUN] onReceive() : errorList=[]
D/UsbSettingsControl( 2612): [AUTORUN] isAutorunTimer() : mAutorunChanging=false
D/UsbSettingsControl( 2612): [AUTORUN] setTetherStatus() : status=false
V/BluetoothPbapReceiver( 1215): PbapReceiver onReceive 
V/BluetoothPbapReceiver( 1215): ***********action = android.bluetooth.adapter.action.STATE_CHANGED
V/BluetoothPbapReceiver( 1215): ***********state = 10
W/ContextImpl( 2612): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:156 com.android.settings.bluetooth.DockEventReceiver.onReceive:123 
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{435261b8 stackId=1, 2 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ec96c8 u0 com.example.hello/.MainActivity t3}
D/DockEventReceiver( 2612): finishStartingService: stopping service
D/BluetoothPermissionRequest( 2612): onReceive
E/LGBluetoothUtils( 2612): [BTUI] FileNotFoundException: readPropertyjava.io.FileNotFoundException: /data/misc/bluedroid/bluetooth_property.conf: open failed: ENOENT (No such file or directory)
D/BluetoothDiscoverableTimeoutReceiver( 2612): cancelDiscoverableAlarm(): Enter
D/LGBluetoothResetSettingReceiver( 2612): return without doing reset settings.
,D/LGBluetoothProfileConnectionReceiver( 2612): [BTUI] STATE_OFF : reset connected device information - BluetoothSettings
E/memtrack( 4675): Couldn't load memtrack module (No such file or directory)
E/android.os.Debug( 4675): failed to load memtrack module: -2
D/LGBluetoothProfileConnectionReceiver_EasySetting( 4683): [BTUI] STATE_OFF : reset connected device information EasySettings
D/AuthorizationBluetoothService( 1530): Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
D/WifiStateMachine(  962): setWifiState: disabled
D/WifiOffDelayIfNotUsed(  962): stopMonitoring
D/LGDMClient( 2870): [DmDeviceActionReceiver.java] [onReceive()] : [66] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
D/WifiActivationWhileCharging(  962): register : WIFI_ACTIVATION_WHILE_CHARGING_OFF[1]
E/WifiStateMachine(  962): Couldn't get getWiFiOffloadingIface : 
E/WifiStateMachine(  962): useWiFiOffloading() : false
E/WifiStateMachine(  962): CONFIG_LGE_WLAN_PATH : true
,D/LGDMClient( 2870): [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [1605] : iAgentState=0, isUserType=0
D/WifiStateMachine(  962): transitionTo: destState=InitialState
D/WifiStateMachine(  962): handleMessage: new destination call exit/enter
D/WifiStateMachine(  962): setupTempStateStackWithStatesToEnter: X mTempStateStackCount=1,curStateInfo: state=DefaultState,active=true,parent=null
D/WifiStateMachine(  962): invokeExitMethods: SupplicantStoppingState
D/WifiStateMachine(  962): moveTempStackToStateStack: i=0,j=1
D/WifiStateMachine(  962): moveTempStackToStateStack: X mStateStackTop=1,startingIndex=1,Top=InitialState
,D/WifiStateMachine(  962): invokeEnterMethods: InitialState
,I/WifiServiceExtension(  962): WIFI_STATE_CHANGED_ACTION [1]
V/WfdStateTracker( 1156): WfdStateTracker handleDirectStateChangedEvent: 0
I/WifiServiceExtension(  962): batteryPsActivateMsgHandler : state:0 event:1
,I/WifiServiceExtension(  962): batteryPsActivateMsgHandler : this is not treated
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
E/Parcel  (  477): Reading a NULL string not supported here.
D/BubblePopupHelper( 1142): isShowingBubblePopup : false
E/Parcel  (  477): Reading a NULL string not supported here.
,E/Parcel  (  477): Reading a NULL string not supported here.
,W/Settings( 1424): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/ActivityManager(  962): Start proc com.lge.lgdmsgcm for broadcast com.lge.lgdmsgcm/.ConnectivityReceiver: pid=4758 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/HyLog   ( 4758): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4758): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4758): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/LGDMSGCM( 4758): [ConnectivityReceiver.java] [onReceive()] : [25] : ConnectivityReceiver android.net.wifi.supplicant.CONNECTION_CHANGE
,D/AndroidRuntime( 4675): Calling main entry com.android.commands.pm.Pm
I/PCSuite ( 4716): [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
D/PCSuite ( 4716): [StartReceiver][getUpdateNecessity]update = false
,D/PCSuite ( 4716): [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
W/ContextImpl( 4758): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 com.lge.lgdmsgcm.ConnectivityReceiver.onReceive:33 android.app.ActivityThread.handleReceiver:2424 android.app.ActivityThread.access$1700:139 
I/ActivityManager(  962): Killing 4439:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{435261b8 stackId=1, 2 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ec96c8 u0 com.example.hello/.MainActivity t3}
,I/ActivityManager(  962): Force stopping com.example.hello appid=10312 user=-1: uninstall pkg
,I/ActivityManager(  962): Killing 4583:com.example.hello/u0a312 (adj 0): stop com.example.hello
,W/ActivityManager(  962): Force removing ActivityRecord{42ec96c8 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,V/ActivityManager(  962): Moving to DESTROYED: ActivityRecord{42ec96c8 u0 com.example.hello/.MainActivity t3 f} (removed from history)
,V/ActivityManager(  962): Moving to DESTROYED: ActivityRecord{42ec96c8 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,I/MDM     (  962):  removeProcessLocked app.persistent = false callerWillRestart = false
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{435261b8 stackId=1, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: No more activities go home
V/ActivityManager(  962): moveHomeStack:
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e4a848 stackId=0, 1 tasks}
,I/WindowState(  962): WIN DEATH: Window{435baa80 u0 com.example.hello/com.example.hello.MainActivity}
,D/WifiService(  962): Client connection lost with reason: 4
,W/PackageSettings(  962): Skipping PackageSetting{42f33388 com.test.thalitest/10304} due to missing metadata
,V/ActivityManager(  962): Moving to RESUMED: ActivityRecord{42ee1d20 u0 com.lge.launcher2/.Launcher t1} (in existing)
,D/ActivityManager(  962): resumeTopActivityLocked: Resumed ActivityRecord{42ee1d20 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  962): resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42e4a848 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ee1d20 u0 com.lge.launcher2/.Launcher t1}
,I/ActivityManager(  962): Force stopping com.example.hello appid=10312 user=0: pkg removed
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e4a848 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ee1d20 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1487): [Launcher.java:4947:onStart()]onStart
,D/KeyguardModel( 1142): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,D/UsbSettings( 2612): [AUTORUN] onDestroy() : getDefaultFunction =boot
,V/ActivityManager(  962): Moving to DESTROYING: ActivityRecord{42eb1968 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
E/SlideAside( 3754): [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
I/SlideAside( 3754): [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.example.hello
I/[LGHome]EVENT( 1487): [Launcher.java:717:onResume()]onResume
I/InputReader(  962): Reconfiguring input devices.  changes=0x00000010
D/AppUp4:Utils( 4015): [getPackageName] uri : package:com.example.hello
D/AppUp4  ( 4015): [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
I/AppUp4  ( 4015):  isExcludedPackage  packagename = com.example.hello
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
,I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/AppUp4  ( 4015):  isExcludedPackage TRUE : com.example.hello
I/ActivityManager(  962): Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4774 uid=10090 gids={50090}
,D/dalvikvm( 2681): GC_EXPLICIT freed 3731K, 28% free 17915K/24832K, paused 1ms+2ms, total 39ms
,W/System.err( 2669): android.content.pm.PackageManager$NameNotFoundException: com.example.hello
W/System.err( 2669): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
W/System.err( 2669): 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
,W/System.err( 2669): 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
W/GeofencerStateMachine( 1424): Ignoring removeGeofence because network location is disabled.
,W/System.err( 2669): 	at android.os.Handler.handleCallback(Handler.java:733)
W/System.err( 2669): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/System.err( 2669): 	at android.os.Looper.loop(Looper.java:136)
W/System.err( 2669): 	at android.app.ActivityThread.main(ActivityThread.java:5105)
W/System.err( 2669): 	at java.lang.reflect.Method.invokeNative(Native Method)
W/System.err( 2669): 	at java.lang.reflect.Method.invoke(Method.java:515)
,W/System.err( 2669): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
W/System.err( 2669): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,W/System.err( 2669): 	at dalvik.system.NativeStart.main(Native Method)
V/UsbSettings( 2612): [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
V/UsbSettings( 2612): [AUTORUN] onDestroy() : sys.usb.config=boot,adb
,V/UsbSettings( 2612): [AUTORUN] onDestroy() : sys.usb.state=boot,adb
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "smsto"
,D/[BNRAppListMgrReceiver]( 4473): android.intent.action.PACKAGE_REMOVED : com.example.hello
,I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]EVENT( 1487): [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
D/PhoneApp( 1449): getIsInUseVoLTE : false
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mms"
,I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
I/[LGHome]LGActivityUtil( 1487): [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
D/WifiStateMachine(  962): handleMessage: X
D/WifiStateMachine(  962): handleMessage: E msg.what=131101
D/WifiStateMachine(  962): processMsg: InitialState
D/WifiStateMachine(  962): processMsg: DefaultState
D/WifiStateMachine(  962): handleMessage: X
,D/HyLog   ( 4774): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4774): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4774): I : /data/font/config/sfconfig.dat, No such file or directory (2)
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
I/PackageManager(  962):   Scheme: "mmsto"
,I/[LGHome]EVENT( 1487): [Launcher.java:868:onResume()]onResume end
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,V/ActivityManager(  962): Moving to DESTROYED: ActivityRecord{42eb1968 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e4a848 stackId=0, 1 tasks}
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "sms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ee1d20 u0 com.lge.launcher2/.Launcher t1}
,D/dalvikvm(  962): GC_EXPLICIT freed 1733K, 10% free 29586K/32636K, paused 4ms+9ms, total 113ms
,D/dalvikvm(  962): WAIT_FOR_CONCURRENT_GC blocked 61ms
,I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "smsto"
,I/LockScreenSettings( 4774): Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/VoicemailCleanupService( 1736): Cleaning up data for package: com.example.hello
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,I/[LGHome]LGPlusHomeDBManager( 1487): [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
,I/PackageChangeReceiver( 4486): intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mms"
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/KeyguardModel( 1142): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1142): createShortcutInfo...
,I/[LGHome]EVENT( 1487): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
I/PackageManager(  962):   Action: "android.intent.action.SENDTO"
I/PackageManager(  962):   Category: "android.intent.category.DEFAULT"
,I/PackageManager(  962):   Scheme: "mmsto"
D/administrator(  962): Handling package changes for user 0
I/PackageManager(  962): Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,D/PackageIntentReceiver( 2612): Not supported Hotkey customization function 
,W/Binder  ( 1318): Caught a RuntimeException from the binder stub implementation.
W/Binder  ( 1318): java.lang.NullPointerException
W/Binder  ( 1318): 	at android.inputmethodservice.IInputMethodWrapper.setSessionEnabled(IInputMethodWrapper.java:280)
W/Binder  ( 1318): 	at com.android.internal.view.IInputMethod$Stub.onTransact(IInputMethod.java:129)
W/Binder  ( 1318): 	at android.os.Binder.execTransact(Binder.java:407)
W/Binder  ( 1318): 	at dalvik.system.NativeStart.run(Native Method)
I/InputMethodManagerService(  962): IME STATUS OFF
W/InputMethodManagerService(  962): Got RemoteException sending setActive(false) notification to pid 4583 uid 10312
,D/KeyguardModel( 1142): package = com.android.mms, class = com.android.mms.ui.ConversationList
D/HideNavigationAppsReceiver( 2612): Receive package name : com.example.hello
,D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1142): createShortcutInfo...
,D/HideNavigationAppsReceiver( 2612): Delete mPackageMame : com.example.hello
D/KeyguardModel( 1142): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1142): createShortcutInfo...
,I/IcingCorporaProvider( 2681): Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
,D/GlobalAccess( 1142): optimizeTargetDrawableItems(), newSize: 20
,D/GlowPadView( 1142): changeTargets() succeeded. size: 20
,I/ActivityManager(  962): Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4791 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,D/KeyguardModel( 1142): mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,D/KeyguardModel( 1142): handleShortcutListChanged...
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
I/ActivityManager(  962): Killing 3914:com.google.android.apps.plus/u0a112 (adj 15): empty #17
,D/KeyguardModel( 1142): package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.android.mms, class = com.android.mms.ui.ConversationList
,D/KeyguardModel( 1142): createShortcutInfo...
D/HyLog   ( 4791): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4791): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4791): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e4a848 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ee1d20 u0 com.lge.launcher2/.Launcher t1}
,D/KeyguardModel( 1142): package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
,D/KeyguardModel( 1142): createShortcutInfo...
D/KeyguardModel( 1142): package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
,D/KeyguardModel( 1142): createShortcutInfo...
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,D/KeyguardModel( 1142): package = com.lge.camera, class = com.lge.camera.CameraApp
,D/KeyguardModel( 1142): createShortcutInfo...
I/InteractionManagerConfigurator(  962): updateIntentFilterConfig
,I/InteractionManagerConfigurator(  962): com.example.hello isn't inclued in dragdropPackageList
D/BackupManagerService(  962): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
V/BackupManagerService(  962): removePackageParticipantsLocked: uid=10312 #1
,D/dalvikvm(  962): GC_EXPLICIT freed 455K, 10% free 29608K/32636K, paused 3ms+11ms, total 187ms
D/dalvikvm( 1487): GC_CONCURRENT freed 5435K, 9% free 60767K/66404K, paused 1ms+3ms, total 24ms
,D/dalvikvm( 1487): WAIT_FOR_CONCURRENT_GC blocked 11ms
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,E/BatteryObserver( 1156): usb Uevent not necessary.
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
D/AndroidRuntime( 4675): Shutting down VM
,D/dalvikvm( 4675): GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 2ms
W/ContextImpl( 4791): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2424 
,D/TangibleManager( 1462): [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
D/OtgUmsTangibleController( 1462): [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
D/HeadsetTangibleController( 1462): [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,D/UsbTangibleController( 1462): [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
D/WifiController(  962): battery changed pluggedType: 2
I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,I/ActivityManager(  962): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=4804 uid=10112 gids={50112, 3003, 3002, 1028, 1015}
,I/IcingCorporaProvider( 2681): UpdateCorporaTask done [took 149 ms] updated apps [took 149 ms] 
D/HyLog   ( 4804): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4804): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4804): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,D/dalvikvm( 1142): GC_FOR_ALLOC freed 7079K, 10% free 70961K/78552K, paused 24ms, total 24ms
,I/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,E/[LGHome]NumberBadge.LGUnreadLgeEmailsBadge( 1487): [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,I/[LGHome]EVENT( 1487): [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,E/[LGHome]NumberBadge( 1487): [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,I/[LGHome]Launcher.Model( 1487): [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,I/ActivityManager(  962): Start proc android.process.media for content provider com.android.providers.media/.MediaProvider: pid=4824 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
D/dalvikvm(  268): GC_EXPLICIT freed 46K, 34% free 16472K/24832K, paused 1ms+1ms, total 17ms
D/HyLog   ( 4824): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4824): I : /data/font/config/dfactpre.dat, No such file or directory (2)
D/HyLog   ( 4824): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+1ms, total 14ms
,D/KeyguardModel( 1142): handleShortcutListChanged...
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
I/ActivityManager(  962): Killing 4302:com.android.vending/u0a50 (adj 15): empty #17
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
,D/KeyguardUpdateMonitor( 1142): received broadcast android.intent.action.BATTERY_CHANGED
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 287 plugged : true isCharging : false
,I/[SystemUI]LGPowerUI( 1142): [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
,D/dalvikvm(  268): GC_EXPLICIT freed <1K, 34% free 16472K/24832K, paused 1ms+2ms, total 15ms
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e4a848 stackId=0, 1 tasks}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
,D/KeyguardUpdateMonitor( 1142): handleBatteryUpdate (2) (100)
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ee1d20 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
I/ActivityManager(  962): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=4840 uid=10050 gids={50050, 3003, 1028, 1015}
,I/ActivityManager(  962): Killing 1755:com.google.android.gms.wearable/u0a6 (adj 15): empty #17
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,D/HyLog   ( 4840): I : /data/font/config/sfconfig.dat, No such file or directory (2)
D/HyLog   ( 4840): I : /data/font/config/dfactpre.dat, No such file or directory (2)
,D/HyLog   ( 4840): I : /data/font/config/sfconfig.dat, No such file or directory (2)
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e4a848 stackId=0, 1 tasks}
D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ee1d20 u0 com.lge.launcher2/.Launcher t1}
,V/DownloadManager( 4824): DownloadService onCreate
,I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,I/DownloadManager( 4824): in removeSpuriousFiles
V/DownloadManager( 4824): starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
I/[LGHome]LauncherAppWidgetHostView( 1487): [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
V/DownloadManager( 4824): created cursor android.database.sqlite.SQLiteCursor@42ac1b50 on behalf of 4824
I/DownloadManager( 4824): in trimDatabase
V/DownloadManager( 4824): starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
V/DownloadManager( 4824): created cursor android.database.sqlite.SQLiteCursor@42ac5058 on behalf of 4824
,V/DownloadManager( 4824): DownloadService onStartCommand
I/[LGHome]EVENT( 1487): [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
V/DownloadManager( 4824): starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,V/DownloadManager( 4824): created cursor android.database.sqlite.SQLiteCursor@42ac9438 on behalf of 4824
,I/ActivityManager(  962): Delaying start of: ServiceRecord{434f54b8 u0 com.google.android.apps.plus/.service.FingerprintScannerIntentService}
V/DownloadManager( 4824): DownloadService onDestroy
,I/dalvikvm( 4840): Could not find method android.content.pm.PackageManager.getPackageInstaller, referenced from method com.google.android.gms.common.GooglePlayServicesUtil.zzl
W/dalvikvm( 4840): VFY: unable to resolve virtual method 574: Landroid/content/pm/PackageManager;.getPackageInstaller ()Landroid/content/pm/PackageInstaller;
,D/dalvikvm( 4840): VFY: replacing opcode 0x6e at 0x000b
,D/dalvikvm( 1487): GC_FOR_ALLOC freed 5102K, 9% free 62060K/68008K, paused 18ms, total 18ms
,I/ActivityManager(  962): Killing 4250:com.android.defcontainer/u0a4 (adj 15): empty #17
,I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e4a848 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ee1d20 u0 com.lge.launcher2/.Launcher t1}
,D/Finsky  ( 4840): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/ActivityManager( 1487): Timeline: Activity_idle id: android.os.BinderProxy@42a7cf30 time:49772
,I/ActivityManager(  962): Timeline: Activity_windows_visible id: ActivityRecord{42ee1d20 u0 com.lge.launcher2/.Launcher t1} time:49784
,I/dalvikvm( 4840): Could not find method android.content.pm.ApplicationInfo.loadUnbadgedIcon, referenced from method com.google.android.finsky.utils.NotificationManager.showSuccessfulNewInstallMessage
W/dalvikvm( 4840): VFY: unable to resolve virtual method 530: Landroid/content/pm/ApplicationInfo;.loadUnbadgedIcon (Landroid/content/pm/PackageManager;)Landroid/graphics/drawable/Drawable;
,D/dalvikvm( 4840): VFY: replacing opcode 0x6e at 0x004f
,W/BaseRuntimeLoader( 4840): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4840): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4840): don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
,W/BaseRuntimeLoader( 4840): don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
,E/RollingFileStream( 4840): Could not create a temp file with prefix: "eventlog.store" and suffix: ".log" in dir: "/data/data/com.android.vending/cache/logs/com.google.thalitester%40gmail.com".
,D/Finsky  ( 4840): [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,W/Settings( 4840): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 4840): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
E/SQLiteDatabase( 4840): Failed to open database '/data/data/com.android.vending/databases/library.db'.
E/SQLiteDatabase( 4840): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4840): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4840): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4840): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/SQLiteDatabase( 4840): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/SQLiteDatabase( 4840): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/SQLiteDatabase( 4840): 	at android.os.Handler.handleCallback(Handler.java:733),
E/SQLiteDatabase( 4840): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/SQLiteDatabase( 4840): 	at android.os.Looper.loop(Looper.java:136)
E/SQLiteDatabase( 4840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/dalvikvm( 4840): threadid=27: thread exiting with uncaught exception (group=0x41a3fe48)
,E/SQLiteDatabase( 4840): Failed to open database '/data/data/com.android.vending/databases/localappstate.db'.
E/SQLiteDatabase( 4840): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/SQLiteDatabase( 4840): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/SQLiteDatabase( 4840): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/SQLiteDatabase( 4840): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/SQLiteDatabase( 4840): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.reopen(SQLiteInstallerDataStore.java:288)
E/SQLiteDatabase( 4840): 	at com.google.android.finsky.appstate.SQLiteInstallerDataStore.getAll(SQLiteInstallerDataStore.java:368)
E/SQLiteDatabase( 4840): 	at com.google.android.finsky.appstate.WriteThroughInstallerDataStore.load(WriteThroughInstallerDataStore.java:55)
E/SQLiteDatabase( 4840): 	at com.google.android.finsky.appstate.AppStates.blockingLoad(AppStates.java:82)
E/SQLiteDatabase( 4840): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:177)
E/SQLiteDatabase( 4840): 	at com.google.android.finsky.receivers.InstallerImpl$1.doInBackground(InstallerImpl.java:164)
E/SQLiteDatabase( 4840): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
E/SQLiteDatabase( 4840): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
E/SQLiteDatabase( 4840): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
E/SQLiteDatabase( 4840): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 4840): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 4840): 	at java.lang.Thread.run(Thread.java:841)
,E/AndroidRuntime( 4840): FATAL EXCEPTION: libraries-thread
E/AndroidRuntime( 4840): Process: com.android.vending, PID: 4840
E/AndroidRuntime( 4840): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/AndroidRuntime( 4840): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/AndroidRuntime( 4840): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
E/AndroidRuntime( 4840): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
E/AndroidRuntime( 4840): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
E/AndroidRuntime( 4840): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
E/AndroidRuntime( 4840): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
E/AndroidRuntime( 4840): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:905)
E/AndroidRuntime( 4840): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:890)
E/AndroidRuntime( 4840): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
E/AndroidRuntime( 4840): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1033)
E/AndroidRuntime( 4840): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:256)
E/AndroidRuntime( 4840): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:224)
E/AndroidRuntime( 4840): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:164)
E/AndroidRuntime( 4840): 	at com.google.android.finsky.library.SQLiteLibrary.reopen(SQLiteLibrary.java:256)
E/AndroidRuntime( 4840): 	at com.google.android.finsky.library.LibraryLoader.loadBlocking(LibraryLoader.java:66)
E/AndroidRuntime( 4840): 	at com.google.android.finsky.library.LibraryLoader$1.run(LibraryLoader.java:57)
E/AndroidRuntime( 4840): 	at android.os.Handler.handleCallback(Handler.java:733)
E/AndroidRuntime( 4840): 	at android.os.Handler.dispatchMessage(Handler.java:95)
E/AndroidRuntime( 4840): 	at android.os.Looper.loop(Looper.java:136)
E/AndroidRuntime( 4840): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/dalvikvm( 4840): threadid=28: thread exiting with uncaught exception (group=0x41a3fe48)
,I/Process ( 4840): Sending signal. PID: 4840 SIG: 9
E/DropBoxManagerService(  962): Can't write: system_app_crash
E/DropBoxManagerService(  962): java.io.FileNotFoundException: /data/system/dropbox/drop101.tmp: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  962): 	at libcore.io.IoBridge.open(IoBridge.java:458)
E/DropBoxManagerService(  962): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
E/DropBoxManagerService(  962): 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
E/DropBoxManagerService(  962): 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
E/DropBoxManagerService(  962): 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
E/DropBoxManagerService(  962): 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:10358)
E/DropBoxManagerService(  962): Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
E/DropBoxManagerService(  962): 	at libcore.io.Posix.open(Native Method)
E/DropBoxManagerService(  962): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
E/DropBoxManagerService(  962): 	at libcore.io.IoBridge.open(IoBridge.java:442)
E/DropBoxManagerService(  962): 	... 5 more
,I/ActivityManager(  962): Process com.android.vending (pid 4840) has died.
I/ActivityManager(  962): resumeTopActivitiesLocked(): target Stack:ActivityStack{42e4a848 stackId=0, 1 tasks}
,D/ActivityManager(  962): resumeTopActivityLocked: Top activity resumed ActivityRecord{42ee1d20 u0 com.lge.launcher2/.Launcher t1}
,I/[LGHome]EVENT( 1487): [Launcher.java:5467:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
W/InputMethodManagerService(  962): Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@434d0490 attribute=null, token = android.os.BinderProxy@43420d48
,E/qdhwcomposer(  267): hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,E/qdhwcomposer(  267): hwc_sync: acq_fen_fd_cnt=3 flags=0 fd=16 dpy=0 numHwLayers=4
E/qdoverlay(  267): Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
E/qdoverlay(  267): MdpData failed to play
E/qdoverlay(  267): == Dump MdpData start ==
E/qdoverlay(  267): == Dump OvFD fd=63 path=/dev/graphics/fb0 start/end ==
E/qdoverlay(  267): mOvData msmfb_overlay_data id=64
E/qdoverlay(  267): data msmfb_data offset=0 memid=36 id=0 flags=0x0 priv=0
E/qdoverlay(  267): == Dump MdpData end ==
E/qdhwcomposer(  267): draw: queueBuffer failed for display:0 
E/qdhwcomposer(  267): hwc_set_primary: MDPComp draw failed
E/qdoverlay(  267): Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
E/qdoverlay(  267): static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,E/qdhwcomposer(  267): hwc_set_primary: display commit fail for 0 dpy!
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,I/Vold    (  259): [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0

```
