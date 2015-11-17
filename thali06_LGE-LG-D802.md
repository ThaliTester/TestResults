#### Test 50388019b27d54e_thali06_LGE-LG-D802 Logs


```--------- beginning of /dev/log/main
11-17 18:21:07.162  1956  1956 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
11-17 18:21:07.172  1956  1956 I ConfigFetchService: launchTask
11-17 18:21:07.172  1956  1956 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/net/Network;)
11-17 18:21:07.182  1956  3861 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1UbvT5-_R7uQtkUQg-bW-cl25aIb3BCw9MrV4H11HWe0IO2yNa4NcM83_HjECm87fLOJnaetgtu2GrYKrEhojsuCy4OFy-03uigdMgPprWaJHNCxQBTtT8pnmN9YO7AVVmsTQVRqr5wyue1RVlYRNO5c3Q8pg_s8q_UpnuNS6B3kB8Pr1j4Gndze0LVYnY2sm1sH2Yp
11-17 18:21:07.182  1956  3861 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
11-17 18:21:07.192  1956  1956 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-17 18:21:07.192  1956  1956 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-17 18:21:07.212  1956  1956 D ChimeraCfgMgr: Loading module com.google.android.gms.vision from APK com.google.android.gms
11-17 18:21:07.212  1956  1956 D Vision  : Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.example.hello flg=0x4000010 cmp=com.google.android.gms/.vision.DependencyBroadcastReceiverProxy (has extras) }
11-17 18:21:07.212  3825  3825 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
11-17 18:21:07.212  1956  1956 D Vision  : Failed to find package metadata for com.example.hello
11-17 18:21:07.212  1956  1956 D Vision  : No vision deps
--------- beginning of /dev/log/system
11-17 18:21:07.212   948  1531 I ActivityManager: Killing 3312:com.android.calendar/u0a15 (adj 15): empty #17
11-17 18:21:07.232  1956  3863 I PeopleContactsSync: CP2 sync disabled
11-17 18:21:07.242  1956  3863 I dalvikvm: Could not find method android.app.Activity.finishAfterTransition, referenced from method android.support.v4.app.l.onBackPressed
11-17 18:21:07.242  1956  3863 W dalvikvm: VFY: unable to resolve virtual method 50: Landroid/app/Activity;.finishAfterTransition ()V
11-17 18:21:07.242  1956  3863 D dalvikvm: VFY: replacing opcode 0x6e at 0x000e
11-17 18:21:07.242  1956  3865 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:21:07.242  1956  3865 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:21:07.262   948  1171 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{432e5350 stackId=1, 1 tasks}
11-17 18:21:07.262   948  1171 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{4324b9d0 u0 com.android.settings/.UsbSettings t2}
11-17 18:21:07.262   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
11-17 18:21:07.272  1956  3865 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:21:07.282  1956  3861 E DataScheduler: isDataSchedulerEnabled():false
11-17 18:21:07.282   264  3872 D libc    : _dns_getaddrinfo: iptype =0
11-17 18:21:07.282   264  3872 D libc    : _dns_getaddrinfo: query_ipv4=0, query_ipv6=0
11-17 18:21:07.282  1956  3865 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:21:07.282  1956  3861 W ConfigFetchTask: exception on config fetch: java.net.UnknownHostException: Unable to resolve host "android.clients.google.com": No address associated with hostname
11-17 18:21:07.282  1956  1956 I ConfigFetchService: fetch service done; releasing wakelock
11-17 18:21:07.282  1956  1956 I ConfigFetchService: stopping self
11-17 18:21:07.292  1956  3865 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:21:07.292  1956  3865 W BaseAppContext: Using Auth Proxy for data requests.
11-17 18:21:07.472  1956  3865 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-17 18:21:07.472  1956  3865 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-17 18:21:07.502  1956  1960 D dalvikvm: GC_CONCURRENT freed 1552K, 26% free 18423K/24832K, paused 2ms+3ms, total 24ms
11-17 18:21:07.572   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
11-17 18:21:07.572  1956  2654 I Icing   : Indexing DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49 from com.google.android.googlequicksearchbox
11-17 18:21:07.612  1956  2654 D Icing   : Loaded CLD2 Version V2.0 - 20141016
11-17 18:21:07.682  1956  2654 I Icing   : Indexing done DFFA14CF019A7CEA55CB76CA91D0874B2A84FF49
11-17 18:21:07.872   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
11-17 18:21:07.922   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
11-17 18:21:07.922  1154  1378 E BatteryObserver: usb Uevent not necessary.
11-17 18:21:07.932   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
11-17 18:21:07.952  1140  1140 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
11-17 18:21:07.952  1140  1140 I [SystemUI]LGPowerUI: [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 298 plugged : true isCharging : false
11-17 18:21:07.952  1140  1140 I [SystemUI]LGPowerUI: [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
11-17 18:21:07.952   948  1129 D WifiController: battery changed pluggedType: 2
11-17 18:21:07.952   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
11-17 18:21:07.962  1462  1462 D TangibleManager: [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
11-17 18:21:07.962  1462  1462 D OtgUmsTangibleController: [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
11-17 18:21:07.962  1462  1462 D HeadsetTangibleController: [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
11-17 18:21:07.962  1462  1462 D UsbTangibleController: [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
11-17 18:21:07.962  1140  1140 D KeyguardUpdateMonitor: handleBatteryUpdate (2) (100)
,11-17 18:21:08.582  3886  3886 D AndroidRuntime: 
11-17 18:21:08.582  3886  3886 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
11-17 18:21:08.592  3886  3886 D AndroidRuntime: CheckJNI is OFF
11-17 18:21:08.592  1154  1378 E BatteryObserver: usb Uevent not necessary.
11-17 18:21:08.592   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
11-17 18:21:08.602  3886  3886 D dalvikvm: Trying to load lib libjavacore.so 0x0
11-17 18:21:08.602  1140  1140 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
11-17 18:21:08.602   948  1129 D WifiController: battery changed pluggedType: 2
11-17 18:21:08.612  1140  1140 I [SystemUI]LGPowerUI: [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 299 plugged : true isCharging : false
11-17 18:21:08.612  3886  3886 D dalvikvm: Added shared lib libjavacore.so 0x0
11-17 18:21:08.612  1462  1462 D TangibleManager: [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
11-17 18:21:08.612  1462  1462 D OtgUmsTangibleController: [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
11-17 18:21:08.612  1462  1462 D HeadsetTangibleController: [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
11-17 18:21:08.612  1462  1462 D UsbTangibleController: [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
11-17 18:21:08.612   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
11-17 18:21:08.622  3886  3886 D dalvikvm: Trying to load lib libnativehelper.so 0x0
11-17 18:21:08.622  3886  3886 D dalvikvm: Added shared lib libnativehelper.so 0x0
11-17 18:21:08.622  3886  3886 D dalvikvm: No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
11-17 18:21:08.622  1140  1140 I [SystemUI]LGPowerUI: [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
11-17 18:21:08.622   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
11-17 18:21:08.632  1140  1140 D KeyguardUpdateMonitor: handleBatteryUpdate (2) (100)
11-17 18:21:08.662  3886  3886 D dalvikvm: Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
11-17 18:21:08.732  1956  2975 I CheckinService: Done disabling old GoogleServicesFramework version
11-17 18:21:08.762  3886  3886 E memtrack: Couldn't load memtrack module (No such file or directory)
11-17 18:21:08.762  3886  3886 E android.os.Debug: failed to load memtrack module: -2
11-17 18:21:08.802   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
11-17 18:21:08.822  3886  3886 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-17 18:21:08.832   948   958 I ActivityManager: START u0 {flg=0x10000000 cmp=com.example.hello/.MainActivity} from pid 3886
11-17 18:21:08.832   948   958 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{432e5350 stackId=1, 2 tasks}
11-17 18:21:08.842   267  1686 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (123 us)
11-17 18:21:08.842   948   958 V ActivityManager: Moving to PAUSING: ActivityRecord{4324b9d0 u0 com.android.settings/.UsbSettings t2}
11-17 18:21:08.922   948   958 D dalvikvm: GC_FOR_ALLOC freed 1364K, 12% free 27467K/31052K, paused 78ms, total 78ms
11-17 18:21:08.922   948   958 I dalvikvm-heap: Grow heap (frag case) to 29.819MB for 856096-byte allocation
11-17 18:21:09.012   948   958 D dalvikvm: GC_FOR_ALLOC freed 75K, 12% free 28229K/31892K, paused 75ms, total 75ms
11-17 18:21:09.012   948   958 I dalvikvm-heap: Grow heap (frag case) to 30.563MB for 856096-byte allocation
11-17 18:21:09.022   948   958 D ActivityManager: resumeTopActivityLocked: Pausing null
11-17 18:21:09.022   948   958 V ActivityManager: resumeTopActivityLocked: Skip resume: need to start pausing
11-17 18:21:09.022   948   958 D ActivityManager: setFocusedStack: mFocusedStack=ActivityStack{432e5350 stackId=1, 2 tasks}
11-17 18:21:09.022   948   958 D ActivityManager: allPausedActivitiesComplete: r=ActivityRecord{4324b9d0 u0 com.android.settings/.UsbSettings t2} state=PAUSING
11-17 18:21:09.022  2478  2478 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
11-17 18:21:09.022  2478  2478 D UsbSettings: [AUTORUN] onPause() : mActiveCurrentFunction = boot
11-17 18:21:09.022   948   992 I ActivityManager: startService SlideAside
11-17 18:21:09.022   948  1486 V ActivityManager: Moving to PAUSED: ActivityRecord{4324b9d0 u0 com.android.settings/.UsbSettings t2} (pause complete)
11-17 18:21:09.022   948  1486 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{432e5350 stackId=1, 2 tasks}
11-17 18:21:09.022   948  1486 D ActivityManager: resumeTopActivityLocked: Restarting ActivityRecord{4323d768 u0 com.example.hello/.MainActivity t3}
11-17 18:21:09.022   948   992 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1226 com.android.server.am.ActivityStack.notifyTaskStart:4115 com.android.server.am.ActivityStack.access$000:95 com.android.server.am.ActivityStack$ActivityStackHandler.handleMessage:347 android.os.Handler.dispatchMessage:102 
11-17 18:21:09.032  3886  3886 D AndroidRuntime: Shutting down VM
11-17 18:21:09.032  3886  3891 D dalvikvm: GC_CONCURRENT freed 98K, 15% free 614K/716K, paused 0ms+0ms, total 2ms
11-17 18:21:09.032   948  1486 I ActivityManager: Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3903 uid=10311 gids={50311, 3003, 3001, 3002}
11-17 18:21:09.042  3430  3430 I SlideAside: [CaptureReceiver.java:14:onReceive()] oooooo onReceive : intent = com.lge.android.intent.action.TASK_STARTED
11-17 18:21:09.042   948  1531 V ActivityManager: Moving to RESUMED: ActivityRecord{4323d768 u0 com.example.hello/.MainActivity t3} (starting new instance)
11-17 18:21:09.062  3903  3903 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
11-17 18:21:09.062  3903  3903 D HyLog   : I : /data/font/config/dfactpre.dat, No such file or directory (2)
11-17 18:21:09.062  3903  3903 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
11-17 18:21:09.062  3430  3430 I SlideAside: [MainService.java:214:checkPrecondition()] oooooo Statusbar is closed
11-17 18:21:09.062  3430  3430 D SlideAside: [MainService.java:201:handleNewActivity()] oooooo User executes an App : com.example.hello (filtered)
11-17 18:21:09.082  3903  3903 V WebViewChromium: Binding Chromium to the background looper Looper (main, tid 1) {428a0bb0}
11-17 18:21:09.082  3903  3903 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
11-17 18:21:09.082  3903  3903 I BrowserProcessMain: Initializing chromium process, renderers=0
11-17 18:21:09.092  3903  3922 W chromium: [WARNING:proxy_service.cc(888)] PAC support disabled because there is no system implementation
11-17 18:21:09.092  3903  3903 I Adreno-EGL: <qeglDrvAPI_eglInitialize:385>: EGL 1.4 QUALCOMM build:  ()
11-17 18:21:09.092  3903  3903 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.24.00.02
11-17 18:21:09.092  3903  3903 I Adreno-EGL: Build Date: 01/20/14 Mon
11-17 18:21:09.092  3903  3903 I Adreno-EGL: Local Branch: PMH2-KK_3.5-RB1-AU61-554722-586267-set2
11-17 18:21:09.092  3903  3903 I Adreno-EGL: Remote Branch: 
11-17 18:21:09.092  3903  3903 I Adreno-EGL: Local Patches: 
11-17 18:21:09.092  3903  3903 I Adreno-EGL: Reconstruct Branch: 
11-17 18:21:09.122  3903  3903 I dalvikvm: Could not find method android.webkit.CookieManager.setAcceptThirdPartyCookies, referenced from method org.apache.cordova.engine.SystemCookieManager.<init>
11-17 18:21:09.122  3903  3903 W dalvikvm: VFY: unable to resolve virtual method 168: Landroid/webkit/CookieManager;.setAcceptThirdPartyCookies (Landroid/webkit/WebView;Z)V
11-17 18:21:09.122  3903  3903 D dalvikvm: VFY: replacing opcode 0x6e at 0x0016
11-17 18:21:09.122  3903  3903 I dalvikvm: Could not find method android.webkit.CookieManager.flush, referenced from method org.apache.cordova.engine.SystemCookieManager.flush
11-17 18:21:09.122  3903  3903 W dalvikvm: VFY: unable to resolve virtual method 163: Landroid/webkit/CookieManager;.flush ()V
11-17 18:21:09.122  3903  3903 D dalvikvm: VFY: replacing opcode 0x6e at 0x0008
11-17 18:21:09.132  3903  3903 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
11-17 18:21:09.132  3903  3903 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/webkit/ClientCertRequest;)
11-17 18:21:09.132  3903  3903 I dalvikvm: Could not find method android.webkit.WebViewClient.onReceivedClientCertRequest, referenced from method org.apache.cordova.engine.SystemWebViewClient.onReceivedClientCertRequest
11-17 18:21:09.132  3903  3903 W dalvikvm: VFY: unable to resolve virtual method 221: Landroid/webkit/WebViewClient;.onReceivedClientCertRequest (Landroid/webkit/WebView;Landroid/webkit/ClientCertRequest;)V
11-17 18:21:09.132  3903  3903 D dalvikvm: VFY: replacing opcode 0x6f at 0x001a
11-17 18:21:09.132  3903  3903 W dalvikvm: VFY: unable to find class referenced in signature (Landroid/webkit/PermissionRequest;)
11-17 18:21:09.132  3903  3903 I dalvikvm: Could not find method android.webkit.PermissionRequest.getResources, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onPermissionRequest
11-17 18:21:09.132  3903  3903 W dalvikvm: VFY: unable to resolve virtual method 179: Landroid/webkit/PermissionRequest;.getResources ()[Ljava/lang/String;
11-17 18:21:09.132  3903  3903 D dalvikvm: VFY: replacing opcode 0x6e at 0x000d
11-17 18:21:09.132  3903  3903 I dalvikvm: Could not find method android.webkit.WebChromeClient$FileChooserParams.createIntent, referenced from method org.apache.cordova.engine.SystemWebChromeClient.onShowFileChooser
11-17 18:21:09.132  3903  3903 W dalvikvm: VFY: unable to resolve virtual method 184: Landroid/webkit/WebChromeClient$FileChooserParams;.createIntent ()Landroid/content/Intent;
11-17 18:21:09.132  3903  3903 D dalvikvm: VFY: replacing opcode 0x6e at 0x0000
11-17 18:21:09.132  3903  3903 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
11-17 18:21:09.152  3903  3903 D dalvikvm: Note: class Lcom/lge/mdm/manager/ILGMDMDevicePolicyManager$Stub; has 319 unimplemented (abstract) methods
11-17 18:21:09.282  3903  3930 W BaseRuntimeLoader: don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
11-17 18:21:09.292  3903  3930 W BaseRuntimeLoader: don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
11-17 18:21:09.292  3903  3930 W BaseRuntimeLoader: don't searchcom.lge.telephony.msim.QcomMSimTelephonyManagerAdaptor class
11-17 18:21:09.292  3903  3930 W BaseRuntimeLoader: don't searchcom.lge.telephony.msim.MtkMSimTelephonyManagerAdaptor class
11-17 18:21:09.342  3903  3903 D OpenGLRenderer: Enabling debug mode 0
11-17 18:21:09.352  3903  3903 W AwContents: nativeOnDraw failed; clearing to background color.
11-17 18:21:09.472  3903  3903 I ActivityManager: Timeline: Activity_idle id: android.os.BinderProxy@428a2288 time:44320
11-17 18:21:09.472   948   991 I ActivityManager: Displayed com.example.hello/.MainActivity: +444ms
11-17 18:21:09.562  3903  3903 I chromium: [INFO:CONSOLE(10)] "Viewport target-densitydpi is not supported.", source: file:///android_asset/www/index.html (10)
11-17 18:21:09.582  3903  3923 E AndroidProtocolHandler: Unable to open asset URL: file:///android_asset/www/jxcore.js
11-17 18:21:09.602   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
11-17 18:21:09.602  1154  1378 E BatteryObserver: usb Uevent not necessary.
11-17 18:21:09.622   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
11-17 18:21:09.632  3903  3903 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
11-17 18:21:09.642  1140  1140 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
11-17 18:21:09.642  1140  1140 I [SystemUI]LGPowerUI: [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 300 plugged : true isCharging : false
11-17 18:21:09.642  1462  1462 D TangibleManager: [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
11-17 18:21:09.642  1462  1462 D OtgUmsTangibleController: [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
11-17 18:21:09.642  1462  1462 D HeadsetTangibleController: [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
11-17 18:21:09.642  1462  1462 D UsbTangibleController: [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
11-17 18:21:09.642  1140  1140 I [SystemUI]LGPowerUI: [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
11-17 18:21:09.642  1140  1140 D KeyguardUpdateMonitor: handleBatteryUpdate (2) (100)
11-17 18:21:09.642   948  1129 D WifiController: battery changed pluggedType: 2
11-17 18:21:09.662  1140  1140 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
11-17 18:21:09.662   948  1129 D WifiController: battery changed pluggedType: 2
11-17 18:21:09.672  1140  1140 I [SystemUI]LGPowerUI: [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 299 plugged : true isCharging : false
11-17 18:21:09.672  1140  1140 I [SystemUI]LGPowerUI: [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
11-17 18:21:09.672  1462  1462 D TangibleManager: [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
11-17 18:21:09.672  1462  1462 D OtgUmsTangibleController: [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
11-17 18:21:09.672  1462  1462 D HeadsetTangibleController: [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
11-17 18:21:09.672  1462  1462 D UsbTangibleController: [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
11-17 18:21:09.672  1140  1140 D KeyguardUpdateMonitor: handleBatteryUpdate (2) (100)
11-17 18:21:09.702   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
11-17 18:21:09.732  3903  3933 D dalvikvm: Trying to load lib /data/app-lib/com.example.hello-2/libjxcore.so 0x428a6438
11-17 18:21:09.742  3903  3933 D dalvikvm: Added shared lib /data/app-lib/com.example.hello-2/libjxcore.so 0x428a6438
11-17 18:21:09.742  3903  3933 D jxcore_app_log: JniHelper::setJavaVM(0x41857808), pthread_self() = 1634462888
11-17 18:21:09.742  3903  3933 D JX-Cordova: jxcore cordova android initializing
11-17 18:21:09.782   948   991 I ActivityManager: Timeline: Activity_windows_visible id: ActivityRecord{4323d768 u0 com.example.hello/.MainActivity t3} time:44635
11-17 18:21:09.782   948   992 D ActivityManager: no-history finish of ActivityRecord{4324b9d0 u0 com.android.settings/.UsbSettings t2}
11-17 18:21:09.782   948   992 V ActivityManager: Finishing activity token=Token{4324bb38 ActivityRecord{4324b9d0 u0 com.android.settings/.UsbSettings t2}} r=, result=0, data=null, reason=no-history
11-17 18:21:09.782   948   992 V ActivityManager: Moving to FINISHING: ActivityRecord{4324b9d0 u0 com.android.settings/.UsbSettings t2 f}
11-17 18:21:09.782   948   992 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{4323d768 u0 com.example.hello/.MainActivity t3}
11-17 18:21:09.782   948   992 V ActivityManager: Moving to STOPPING: ActivityRecord{4324b9d0 u0 com.android.settings/.UsbSettings t2 f} (stop requested)
11-17 18:21:09.792  2478  2478 D UsbSettings: [AUTORUN] onStop()
11-17 18:21:09.802   948  1486 V ActivityManager: Moving to STOPPED: ActivityRecord{4324b9d0 u0 com.android.settings/.UsbSettings t2 f} (stop complete)
11-17 18:21:09.832  3903  3903 W jxcore-log: Initializing JXcore engine
11-17 18:21:09.832  3903  3903 W jxcore-log: JXcore engine is ready
11-17 18:21:09.842  3903  3903 W jxcore-log: Starting JXcore engine
11-17 18:21:09.992  3903  3903 W jxcore-log: Platform android
11-17 18:21:09.992  3903  3903 W jxcore-log: 
11-17 18:21:09.992  3903  3903 W jxcore-log: Process ARCH arm
11-17 18:21:09.992  3903  3903 W jxcore-log: 
,11-17 18:21:10.022  3903  3903 I jxcore-log: JXcore Cordova bridge is ready!
11-17 18:21:10.022  3903  3903 I jxcore-log: 
,11-17 18:21:10.032  3903  3903 W jxcore-log: JXcore engine is started
,11-17 18:21:10.042  3903  3903 I chromium: [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,11-17 18:21:10.072  3903  3903 I chromium: [INFO:async_pixel_transfer_manager_android.cc(56)] Async pixel transfers not supported
,11-17 18:21:10.112  3903  3903 E jxcore-log: >> LGE-LG-D802
11-17 18:21:10.112  3903  3903 E jxcore-log: 
,11-17 18:21:10.112  3903  3903 I jxcore-log: Total memory 1943035904
11-17 18:21:10.112  3903  3903 I jxcore-log: 
11-17 18:21:10.112  3903  3903 I jxcore-log: Free memory 464457728
11-17 18:21:10.112  3903  3903 I jxcore-log: 
11-17 18:21:10.112  3903  3903 I jxcore-log: execPath /data/data/com.example.hello/files/www/jxcore
11-17 18:21:10.112  3903  3903 I jxcore-log: 
,11-17 18:21:10.112  3903  3903 I jxcore-log: process.cwd /data/data/com.example.hello/files/www/jxcore
11-17 18:21:10.112  3903  3903 I jxcore-log: 
,11-17 18:21:10.112  3903  3903 I jxcore-log: userPath [ 'www' ]
11-17 18:21:10.112  3903  3903 I jxcore-log: 
,11-17 18:21:10.112  3903  3903 I jxcore-log: Size 1080 1776
11-17 18:21:10.112  3903  3903 I jxcore-log: 
11-17 18:21:10.112  3903  3903 I jxcore-log: Screen Brightness 255
11-17 18:21:10.112  3903  3903 I jxcore-log: 
,11-17 18:21:10.122  3903  3903 E jxcore-log: Dummy Error Log.
11-17 18:21:10.122  3903  3903 E jxcore-log: 
,11-17 18:21:10.312   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,11-17 18:21:10.362   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,11-17 18:21:10.632   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:21:10.632  1154  1378 E BatteryObserver: usb Uevent not necessary.
,11-17 18:21:10.642   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:21:10.652   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:21:10.672  3903  3903 I jxcore-log: getBuffer is called!!!!
11-17 18:21:10.672  3903  3903 I jxcore-log: 
,11-17 18:21:10.692   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:21:10.972   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:21:10.972  1154  1378 E BatteryObserver: usb Uevent not necessary.
,11-17 18:21:10.982   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:21:11.142   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,11-17 18:21:11.442   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,11-17 18:21:11.622   948  1532 I ActivityManager: Killing 3372:com.google.android.gm/u0a68 (adj 15): empty #17
,11-17 18:21:11.642   948   958 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{432e5350 stackId=1, 2 tasks}
,11-17 18:21:11.642   948   958 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{4323d768 u0 com.example.hello/.MainActivity t3}
,11-17 18:21:11.642   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:21:11.652  1154  1378 E BatteryObserver: usb Uevent not necessary.
,11-17 18:21:11.652   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:21:11.812  3825  3843 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,11-17 18:21:11.982   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:21:11.982  1154  1378 E BatteryObserver: usb Uevent not necessary.
,11-17 18:21:11.992   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:21:12.002   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:21:12.302  1535  1535 I ConfigService: onDestroy
,11-17 18:21:12.832   948  1116 V qcom_sensors_hal: hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,11-17 18:21:12.832   948  1116 D qcom_sensors_hal: hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
11-17 18:21:12.832   948  1116 V qcom_sensors_hal: hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
11-17 18:21:12.832   948  1116 V qcom_sensors_hal: hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
,11-17 18:21:12.832   948  1116 V qcom_sensors_hal: hal_process_report_ind: X: -0.573410 Y: -0.377350 Z: 9.711060 
11-17 18:21:12.832   948   990 D qcom_sensors_hal: _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.573410 .y:-0.377350 .z:9.711060
,11-17 18:21:12.832   948   990 D qcom_sensors_hal: _hal_sensors_data_poll: cnt: 36
,11-17 18:21:12.832   948   990 D qcom_sensors_hal: hal_wait_for_response: timeout=0
,11-17 18:21:12.902   948  1116 V qcom_sensors_hal: hal_sensor1_data_cb: msg_type 2, Sn 0, msg Id 34, txn Id 0
,11-17 18:21:12.902   948  1116 D qcom_sensors_hal: hal_process_buffering_ind: Samples_len=1 Items=1 max_reports_per_index=1
11-17 18:21:12.902   948  1116 V qcom_sensors_hal: hal_process_report_ind: St: 0 ReportId: 0 Rate: 0, Len: 1
,11-17 18:21:12.902   948  1116 V qcom_sensors_hal: hal_process_report_ind: Id: ACCEL_DATA: Ty: 0 Q: 13
11-17 18:21:12.902   948  1116 V qcom_sensors_hal: hal_process_report_ind: X: -0.572403 Y: -0.384567 Z: 9.701462 
,11-17 18:21:12.902   948   990 D qcom_sensors_hal: _hal_sensors_data_poll: poll data:1;data[0].sensor:0 .type:1 .x:-0.572403 .y:-0.384567 .z:9.701462
,11-17 18:21:12.912   948   990 D qcom_sensors_hal: _hal_sensors_data_poll: cnt: 36
,11-17 18:21:12.912   948   990 D qcom_sensors_hal: hal_wait_for_response: timeout=0
,11-17 18:21:12.972   948  1487 I ActivityManager: Killing 3262:com.google.android.music:main/u0a107 (adj 15): empty #17
,11-17 18:21:12.992   948  1532 F ActivityManager: Service ServiceRecord{4332a460 u0 com.google.android.music/.net.NetworkMonitor} in process ProcessRecord{4320f3c8 3262:com.google.android.music:main/u0a107} not same as in map: null
,11-17 18:21:13.012   948  1532 F ActivityManager: Service ServiceRecord{43277ee0 u0 com.google.android.music/.preferences.MusicPreferenceService$MusicPreferenceServiceBinder} in process ProcessRecord{4320f3c8 3262:com.google.android.music:main/u0a107} not same as in map: null
,11-17 18:21:13.022   948  1532 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{432e5350 stackId=1, 2 tasks}
,11-17 18:21:13.022   948  1532 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{4323d768 u0 com.example.hello/.MainActivity t3}
,11-17 18:21:15.132   948   997 D BluetoothManagerService: Message: 20
,11-17 18:21:15.132   948   997 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@431b53f8:true
,11-17 18:21:15.132   948  1486 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,11-17 18:21:15.132   948  1486 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
,11-17 18:21:15.132   948   997 D BluetoothManagerService: Message: 2
,11-17 18:21:15.152   948  1129 D WifiService: New client listening to asynchronous messages
,11-17 18:21:15.162   948  1513 D WifiService: setWifiEnabled: false pid=3903, uid=10311
,11-17 18:21:15.162   948  1513 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 18:21:15.162  3903  3903 I jxcore-log: ****TEST TOOK:  5054  ms ****
11-17 18:21:15.162  3903  3903 I jxcore-log: 
,11-17 18:21:15.162  3903  3903 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
11-17 18:21:15.162  3903  3903 I jxcore-log: 
11-17 18:21:15.162   948  1513 I WifiService: setWifiEnabled startWifiDelaySendMsg true
,11-17 18:21:15.622  3971  3971 D AndroidRuntime: 
11-17 18:21:15.622  3971  3971 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,11-17 18:21:15.622  3971  3971 D AndroidRuntime: CheckJNI is OFF
,11-17 18:21:15.632  3971  3971 D dalvikvm: Trying to load lib libjavacore.so 0x0
,11-17 18:21:15.632  3971  3971 D dalvikvm: Added shared lib libjavacore.so 0x0
,11-17 18:21:15.632  3971  3971 D dalvikvm: Trying to load lib libnativehelper.so 0x0
11-17 18:21:15.632  3971  3971 D dalvikvm: Added shared lib libnativehelper.so 0x0
,11-17 18:21:15.632  3971  3971 D dalvikvm: No JNI_OnLoad found in libnativehelper.so 0x0, skipping init
,11-17 18:21:15.662  3971  3971 D dalvikvm: Note: class Landroid/app/ActivityManagerNative; has 185 unimplemented (abstract) methods
,11-17 18:21:15.712  1154  1378 E BatteryObserver: usb Uevent not necessary.
,11-17 18:21:15.712   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:21:15.722   948  1129 D WifiController: battery changed pluggedType: 2
,11-17 18:21:15.732  1140  1140 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,11-17 18:21:15.732  1140  1140 I [SystemUI]LGPowerUI: [LGPowerUI.java:766:batteryThermNotification()]batteryThermNotification temperature : 300 plugged : true isCharging : false
,11-17 18:21:15.732  1140  1140 I [SystemUI]LGPowerUI: [LGPowerUI.java:775:batteryThermNotification()]StopCharging degree: 500
11-17 18:21:15.732   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
11-17 18:21:15.742   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:21:15.762  1462  1462 D TangibleManager: [TangibleIO] TangibleIntentReceiver onReceive intent = Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,11-17 18:21:15.762  1462  1462 D OtgUmsTangibleController: [TangibleIO] OtgUmsTangibleController onAction action = android.intent.action.BATTERY_CHANGED
11-17 18:21:15.762  1462  1462 D HeadsetTangibleController: [TangibleIO] HeadsetTangibleController onAction action = android.intent.action.BATTERY_CHANGED
,11-17 18:21:15.762  1462  1462 D UsbTangibleController: [TangibleIO] UsbTangibleController action = android.intent.action.BATTERY_CHANGED
,11-17 18:21:15.762  1140  1140 D KeyguardUpdateMonitor: handleBatteryUpdate (2) (100)
,11-17 18:21:15.792  1154  1158 D dalvikvm: GC_CONCURRENT freed 1252K, 6% free 25438K/26868K, paused 6ms+3ms, total 57ms
,11-17 18:21:15.812   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,11-17 18:21:15.822  3971  3971 E memtrack: Couldn't load memtrack module (No such file or directory)
,11-17 18:21:15.822  3971  3971 E android.os.Debug: failed to load memtrack module: -2
11-17 18:21:15.822   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,11-17 18:21:15.872  3971  3971 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-17 18:21:15.892   948   992 I ActivityManager: Force stopping com.example.hello appid=10311 user=-1: uninstall pkg
,11-17 18:21:15.892   948   992 I ActivityManager: Killing 3903:com.example.hello/u0a311 (adj 0): stop com.example.hello
,11-17 18:21:15.902   948   992 W ActivityManager: Force removing ActivityRecord{4323d768 u0 com.example.hello/.MainActivity t3}: app died, no saved state
,11-17 18:21:15.902   948   992 V ActivityManager: Moving to DESTROYED: ActivityRecord{4323d768 u0 com.example.hello/.MainActivity t3 f} (removed from history)
,11-17 18:21:15.902   948   992 V ActivityManager: Moving to DESTROYED: ActivityRecord{4323d768 u0 com.example.hello/.MainActivity t3 f} (cleaning up)
,11-17 18:21:15.902   948   992 I MDM     :  removeProcessLocked app.persistent = false callerWillRestart = false
11-17 18:21:15.902   948   992 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{432e5350 stackId=1, 1 tasks}
11-17 18:21:15.902   948   992 D ActivityManager: resumeTopActivityLocked: No more activities go home
,11-17 18:21:15.902   948   992 V ActivityManager: moveHomeStack:
,11-17 18:21:15.902   948   992 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{42c79ec0 stackId=0, 1 tasks}
,11-17 18:21:15.912   948  1487 I WindowState: WIN DEATH: Window{4338b990 u0 com.example.hello/com.example.hello.MainActivity}
,11-17 18:21:15.912   948  1129 D WifiService: Client connection lost with reason: 4
,11-17 18:21:15.952   948  1000 W PackageSettings: Skipping PackageSetting{42d4cc28 com.test.thalitest/10304} due to missing metadata
,11-17 18:21:15.982   948   992 V ActivityManager: Moving to RESUMED: ActivityRecord{42c89920 u0 com.lge.launcher2/.Launcher t1} (in existing)
,11-17 18:21:15.982   948   992 D ActivityManager: resumeTopActivityLocked: Resumed ActivityRecord{42c89920 u0 com.lge.launcher2/.Launcher t1}
,11-17 18:21:15.982   948   992 I ActivityManager: resumeTopActivitiesLocked(): Non-target Stack:ActivityStack{42c79ec0 stackId=0, 1 tasks}
,11-17 18:21:15.982   948   992 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{42c89920 u0 com.lge.launcher2/.Launcher t1}
,11-17 18:21:15.982  1489  1489 I [LGHome]EVENT: [Launcher.java:4947:onStart()]onStart
11-17 18:21:15.982   948  1000 I ActivityManager: Force stopping com.example.hello appid=10311 user=0: pkg removed
11-17 18:21:15.992   948  1000 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{42c79ec0 stackId=0, 1 tasks}
11-17 18:21:15.992   948  1000 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{42c89920 u0 com.lge.launcher2/.Launcher t1}
,11-17 18:21:16.002  1489  1489 I [LGHome]EVENT: [Launcher.java:717:onResume()]onResume
,11-17 18:21:16.002  1489  1489 I [LGHome]EVENT: [LauncherModel.java:1386:startLoader()]startLoader isLaunching=true
,11-17 18:21:16.002  1489  1547 I [LGHome]Launcher.Model: [LauncherModel.java:1514:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,11-17 18:21:16.002  1449  2467 D PhoneApp: getIsInUseVoLTE : false
,11-17 18:21:16.002  1140  1140 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,11-17 18:21:16.002   948  1115 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-17 18:21:16.002   948   992 V ActivityManager: Moving to DESTROYING: ActivityRecord{4324b9d0 u0 com.android.settings/.UsbSettings t2 f} (destroy requested)
11-17 18:21:16.012  2555  2555 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.example.hello
11-17 18:21:16.012  1489  1489 I [LGHome]LGActivityUtil: [LGActivityUtil.java:310:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,11-17 18:21:16.012   948  1532 I PackageManager:   Action: "android.intent.action.SENDTO"
,11-17 18:21:16.012   948  1532 I PackageManager:   Category: "android.intent.category.DEFAULT"
11-17 18:21:16.012   948  1532 I PackageManager:   Scheme: "sms"
,11-17 18:21:16.012   948  1532 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
11-17 18:21:16.022  3550  3550 D AppUp4:Utils: [getPackageName] uri : package:com.example.hello
11-17 18:21:16.022  3550  3550 D AppUp4  : [PreloadListManagerHelper] action android.intent.action.PACKAGE_REMOVED
11-17 18:21:16.022  3550  3550 I AppUp4  :  isExcludedPackage  packagename = com.example.hello
,11-17 18:21:16.022  2555  2555 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:82)
,11-17 18:21:16.022  2555  2555 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
11-17 18:21:16.022   948  1486 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=4000 uid=10090 gids={50090}
,11-17 18:21:16.032  2555  2555 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:778)
11-17 18:21:16.032  2555  2555 W System.err: 	at android.os.Handler.handleCallback(Handler.java:733)
11-17 18:21:16.032  2555  2555 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 18:21:16.032  2555  2555 W System.err: 	at android.os.Looper.loop(Looper.java:136)
,11-17 18:21:16.032  2555  2555 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5105)
,11-17 18:21:16.032  2555  2555 W System.err: 	at java.lang.reflect.Method.invokeNative(Native Method)
11-17 18:21:16.032  2555  2555 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:515)
11-17 18:21:16.032  2555  2555 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:792)
11-17 18:21:16.032  2555  2555 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:608)
,11-17 18:21:16.032  2555  2555 W System.err: 	at dalvik.system.NativeStart.main(Native Method)
,11-17 18:21:16.032  3550  3550 D AppUp4  :  isExcludedPackage TRUE : com.example.hello
,11-17 18:21:16.032  3430  3430 E SlideAside: [PinnedViewHolder.java:41:onReceive()] oooooo android.intent.action.PACKAGE_REMOVED
,11-17 18:21:16.032  1489  1489 I [LGHome]EVENT: [Launcher.java:868:onResume()]onResume end
,11-17 18:21:16.042  3300  3300 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_REMOVED : com.example.hello
11-17 18:21:16.042   948   958 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:21:16.042   948   958 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:21:16.042   948   958 I PackageManager:   Scheme: "smsto"
,11-17 18:21:16.042  3430  3430 I SlideAside: [PinnedViewHolder.java:69:onReceive()] oooooo RemovedPackageName = com.example.hello
,11-17 18:21:16.042  1424  1816 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-17 18:21:16.042   948   958 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
11-17 18:21:16.052  2478  2478 D UsbSettings: [AUTORUN] onDestroy() : getDefaultFunction =boot
11-17 18:21:16.052  2478  2478 V UsbSettings: [AUTORUN] onDestroy() : persist.sys.usb.config=boot,adb
11-17 18:21:16.052  2478  2478 V UsbSettings: [AUTORUN] onDestroy() : sys.usb.config=boot,adb
11-17 18:21:16.052  2478  2478 V UsbSettings: [AUTORUN] onDestroy() : sys.usb.state=boot,adb
11-17 18:21:16.052  1489  1489 I [LGHome]EVENT: [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
11-17 18:21:16.052  1489  1489 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:297:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
11-17 18:21:16.052  1489  1489 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:363:packageUpdate()]PackageUpdatedTask: 3
,11-17 18:21:16.052  2567  2567 D dalvikvm: GC_EXPLICIT freed 3646K, 29% free 17873K/24832K, paused 4ms+6ms, total 66ms
11-17 18:21:16.062   948  1513 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:21:16.062   948  1513 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:21:16.062   948  1513 I PackageManager:   Scheme: "mms"
11-17 18:21:16.062  4000  4000 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
11-17 18:21:16.062  4000  4000 D HyLog   : I : /data/font/config/dfactpre.dat, No such file or directory (2)
,11-17 18:21:16.062  4000  4000 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
11-17 18:21:16.062   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
11-17 18:21:16.062   948  1513 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,11-17 18:21:16.072   948  1530 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:21:16.072   948  1530 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:21:16.072   948  1530 I PackageManager:   Scheme: "mmsto"
11-17 18:21:16.072   948  1530 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
11-17 18:21:16.082   948  1487 V ActivityManager: Moving to DESTROYED: ActivityRecord{4324b9d0 u0 com.android.settings/.UsbSettings t2 f} (removed from history)
11-17 18:21:16.082   948  1487 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{42c79ec0 stackId=0, 1 tasks}
11-17 18:21:16.082   948  1487 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{42c89920 u0 com.lge.launcher2/.Launcher t1}
,11-17 18:21:16.092  4000  4000 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
11-17 18:21:16.102   948  1487 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:21:16.102   948  1487 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:21:16.102   948  1487 I PackageManager:   Scheme: "sms"
11-17 18:21:16.102   948  1487 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,11-17 18:21:16.132   948  1487 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:21:16.132   948  1487 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:21:16.132   948  1487 I PackageManager:   Scheme: "smsto"
,11-17 18:21:16.132   948   948 D dalvikvm: GC_EXPLICIT freed 1020K, 11% free 29243K/32732K, paused 2ms+8ms, total 141ms
,11-17 18:21:16.132   948  1000 D dalvikvm: WAIT_FOR_CONCURRENT_GC blocked 135ms
11-17 18:21:16.132   948  1487 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
,11-17 18:21:16.142  1489  1489 I [LGHome]Launcher.Model: [LauncherModel.java:2268:run()] LauncherModel bind current page shortcut
11-17 18:21:16.142   948  1487 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:21:16.142   948  1487 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:21:16.142   948  1487 I PackageManager:   Scheme: "mms"
,11-17 18:21:16.142   948  1487 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
11-17 18:21:16.152  1822  4021 D VoicemailCleanupService: Cleaning up data for package: com.example.hello
,11-17 18:21:16.162  1140  1167 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,11-17 18:21:16.162  1140  1167 D KeyguardModel: createShortcutInfo...
,11-17 18:21:16.162  3804  3804 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
11-17 18:21:16.162   948  1531 I PackageManager:   Action: "android.intent.action.SENDTO"
11-17 18:21:16.162   948  1531 I PackageManager:   Category: "android.intent.category.DEFAULT"
,11-17 18:21:16.162   948  1531 I PackageManager:   Scheme: "mmsto"
,11-17 18:21:16.162   948  1531 I PackageManager: Adding preferred activity ComponentInfo{com.android.mms/com.android.mms.ui.ComposeMessageActivity} for user 0 :
11-17 18:21:16.172  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Settings] in screen 2 [0, 4]
11-17 18:21:16.172  1140  1167 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
,11-17 18:21:16.172  1140  1167 D KeyguardModel: createShortcutInfo...
,11-17 18:21:16.172   948   948 D administrator: Handling package changes for user 0
11-17 18:21:16.182  1140  1140 D GlobalAccess: optimizeTargetDrawableItems(), newSize: 20
11-17 18:21:16.182  1140  1140 D GlowPadView: changeTargets() succeeded. size: 20
11-17 18:21:16.182  1140  1167 D KeyguardModel: package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
11-17 18:21:16.182  1140  1167 D KeyguardModel: createShortcutInfo...
11-17 18:21:16.182  1140  1167 D KeyguardModel: package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
11-17 18:21:16.182  1140  1167 D KeyguardModel: createShortcutInfo...
11-17 18:21:16.182  1140  1167 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
11-17 18:21:16.182  1140  1167 D KeyguardModel: createShortcutInfo...
11-17 18:21:16.182  1140  1140 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
11-17 18:21:16.182  1140  1140 D KeyguardModel: handleShortcutListChanged...
11-17 18:21:16.192  1140  1167 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
11-17 18:21:16.192  1140  1167 D KeyguardModel: createShortcutInfo...
11-17 18:21:16.192  1140  1167 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
11-17 18:21:16.192  1140  1167 D KeyguardModel: createShortcutInfo...
11-17 18:21:16.192  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Email] in screen 2 [1, 4]
11-17 18:21:16.192  1140  1167 D KeyguardModel: package = com.lge.Notebook, class = com.lge.Notebook.viewallnotes.RNote_AllNotesView
11-17 18:21:16.192  1140  1167 D KeyguardModel: createShortcutInfo...
11-17 18:21:16.192  1140  1167 D KeyguardModel: package = com.google.android.googlequicksearchbox, class = com.google.android.googlequicksearchbox.SearchActivity
11-17 18:21:16.192  1140  1167 D KeyguardModel: createShortcutInfo...
11-17 18:21:16.192  1140  1167 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
11-17 18:21:16.192  1140  1167 D KeyguardModel: createShortcutInfo...
,11-17 18:21:16.192  2478  2478 D PackageIntentReceiver: Not supported Hotkey customization function 
,11-17 18:21:16.192  1140  1140 D KeyguardModel: handleShortcutListChanged...
,11-17 18:21:16.192  2478  2478 D HideNavigationAppsReceiver: Receive package name : com.example.hello
,11-17 18:21:16.192   948  1169 I ActivityManager: Killing 2064:android.process.media/u0a23 (adj 15): empty #17
11-17 18:21:16.202  2478  2478 D HideNavigationAppsReceiver: Delete mPackageMame : com.example.hello
11-17 18:21:16.202  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Play Store] in screen 2 [2, 4]
,11-17 18:21:16.202   948  1530 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{42c79ec0 stackId=0, 1 tasks}
,11-17 18:21:16.202   948  1530 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{42c89920 u0 com.lge.launcher2/.Launcher t1}
11-17 18:21:16.212  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Camera] in screen 2 [3, 4]
11-17 18:21:16.212  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Gallery] in screen 2 [4, 4]
,11-17 18:21:16.222  2567  4023 I IcingCorporaProvider: Updating corpora: APPS=com.example.hello, CONTACTS=MAYBE
,11-17 18:21:16.232   948  1486 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=4024 uid=1000 gids={41000, 3002, 1028, 1015, 3001, 3003, 1002, 3008, 1023, 1004, 2002, 1007, 1009, 1027, 3005, 4002, 5000, 2001, 1021, 3004, 1000, 3009, 1010}
,11-17 18:21:16.252  4024  4024 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
,11-17 18:21:16.252  4024  4024 D HyLog   : I : /data/font/config/dfactpre.dat, No such file or directory (2)
,11-17 18:21:16.252  4024  4024 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
,11-17 18:21:16.262  1489  1493 D dalvikvm: GC_CONCURRENT freed 5397K, 9% free 61086K/66664K, paused 2ms+3ms, total 21ms
,11-17 18:21:16.262  1489  1489 D dalvikvm: WAIT_FOR_CONCURRENT_GC blocked 9ms
,11-17 18:21:16.272  4024  4024 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1568 android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2424 
11-17 18:21:16.282   948  1000 D dalvikvm: GC_EXPLICIT freed 432K, 11% free 29199K/32732K, paused 3ms+18ms, total 147ms
,11-17 18:21:16.292   948   948 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,11-17 18:21:16.292   948   948 I InteractionManagerConfigurator: updateIntentFilterConfig
,11-17 18:21:16.292   948   948 I InteractionManagerConfigurator: com.example.hello isn't inclued in dragdropPackageList
11-17 18:21:16.292   948   948 V BackupManagerService: removePackageParticipantsLocked: uid=10311 #1
,11-17 18:21:16.332  3656  3656 I dalvikvm: Could not find method android.app.admin.DevicePolicyManager.isUninstallBlocked, referenced from method com.google.android.finsky.activities.AppActionAnalyzer.isUninstallBlockedByAdmin
11-17 18:21:16.332  3656  3656 W dalvikvm: VFY: unable to resolve virtual method 329: Landroid/app/admin/DevicePolicyManager;.isUninstallBlocked (Landroid/content/ComponentName;Ljava/lang/String;)Z
,11-17 18:21:16.332  3656  3656 D dalvikvm: VFY: replacing opcode 0x6e at 0x0013
,11-17 18:21:16.332  1489  4039 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:143:countUnreadItems()]countUnreadItems() started..
,11-17 18:21:16.332  1140  1140 D dalvikvm: GC_FOR_ALLOC freed 6527K, 12% free 69538K/78860K, paused 23ms, total 23ms
,11-17 18:21:16.332  1489  1489 I [LGHome]Launcher.Model: [LauncherModel.java:2282:run()] LauncherModel bind current page shortcut
,11-17 18:21:16.332  3971  3971 D AndroidRuntime: Shutting down VM
,11-17 18:21:16.342  3971  3976 D dalvikvm: GC_CONCURRENT freed 97K, 15% free 586K/688K, paused 0ms+0ms, total 2ms
,11-17 18:21:16.342  1489  1489 I [LGHome]Launcher.Model: [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,11-17 18:21:16.342  1489  1489 I [LGHome]LauncherAppWidgetHostView: [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.weather/com.lge.sizechangable.weather.layout.Weather4x2}
,11-17 18:21:16.342  1489  4039 E [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:188:countUnreadItems()]Could not get cursor from provider for com.lge.email
,11-17 18:21:16.342  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.weather.layout.Weather4x2] in screen 2 [0, 0]
,11-17 18:21:16.342  1489  1489 I [LGHome]Launcher.Model: [LauncherModel.java:2294:run()] LauncherModel bind current page widget
,11-17 18:21:16.342  1489  1489 I [LGHome]LauncherAppWidgetHostView: [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}) and appWidget.provider = ComponentInfo{com.lge.appwidget.lgsearch/com.lge.appwidget.lgsearch.LGSearchWidgetProvider}
,11-17 18:21:16.342  2567  4023 I IcingCorporaProvider: UpdateCorporaTask done [took 127 ms] updated apps [took 127 ms] 
,11-17 18:21:16.352  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.appwidget.lgsearch.LGSearchWidgetProvider] in screen 2 [0, 2]
,11-17 18:21:16.352  1489  1489 E [LGHome]NumberBadge: [LGNumberBadge.java:123:handleMessage()]MSG_RESPOND_RESULT_FROM_PROVIDER_FAILED
,11-17 18:21:16.352  1535  1535 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-17 18:21:16.352  1535  1535 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-17 18:21:16.362  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Life Square] in screen 1 [0, 4]
,11-17 18:21:16.372  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Notebook] in screen 1 [1, 4]
,11-17 18:21:16.382  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Alarm/Clock] in screen 1 [2, 4]
11-17 18:21:16.382  1956  1956 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-17 18:21:16.382  1956  1956 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-17 18:21:16.382  1956  1956 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-17 18:21:16.382  1956  1956 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
11-17 18:21:16.382   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:21:16.382  1154  1378 E BatteryObserver: usb Uevent not necessary.
11-17 18:21:16.392  2478  2478 D PackageIntentReceiver: Not supported Hotkey customization function 
11-17 18:21:16.392  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Quick Translator] in screen 1 [3, 4]
11-17 18:21:16.392  1956  4048 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.example.hello
11-17 18:21:16.392  1956  4048 D AccountUtils: Clearing selected account for com.example.hello
11-17 18:21:16.392  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Calendar] in screen 1 [4, 4]
,11-17 18:21:16.402   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:power_supply, action:3
,11-17 18:21:16.402  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Videos] in screen 3 [0, 4]
11-17 18:21:16.402   948  1171 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=4050 uid=10065 gids={50065, 1028, 4002}
,11-17 18:21:16.422  1956  4048 I LocationSettingsChecker: Removing dialog suppression flag for package com.example.hello
,11-17 18:21:16.422  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Maps] in screen 3 [1, 4]
,11-17 18:21:16.422  4050  4050 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
11-17 18:21:16.432  4050  4050 D HyLog   : I : /data/font/config/dfactpre.dat, No such file or directory (2)
,11-17 18:21:16.432  4050  4050 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
,11-17 18:21:16.432  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [YouTube] in screen 3 [2, 4]
,11-17 18:21:16.432  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Quick Remote] in screen 3 [3, 4]
11-17 18:21:16.432   948  1513 I ActivityManager: Delaying start of: ServiceRecord{432f0510 u0 com.google.android.gms/.wearable.service.WearableControlService}
11-17 18:21:16.442  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add Shortcut [Video Editor] in screen 3 [4, 4]
,11-17 18:21:16.442  1489  1489 I [LGHome]EVENT: [LauncherModel.java:1177:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,11-17 18:21:16.452  1489  1489 I [LGHome]LauncherAppWidgetHostView: [LauncherAppWidgetHostView.java:65:<init>()]appWidget = AppWidgetProviderInfo(provider=ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}) and appWidget.provider = ComponentInfo{com.lge.sizechangable.musicwidget.widget/com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1}
,11-17 18:21:16.462  1535  1535 I ConfigService: onCreate
,11-17 18:21:16.462  1956  1956 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,11-17 18:21:16.472  1489  1489 I [LGHome]EVENT: [Workspace.java:886:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 3 [0, 0]
,11-17 18:21:16.482  1956  4069 I PeopleContactsSync: CP2 sync disabled
,11-17 18:21:16.482  1956  2654 I Icing   : doRemovePackageData com.example.hello
,11-17 18:21:16.482  1956  4066 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:21:16.482  1956  4065 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 1
,11-17 18:21:16.482  1956  4065 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 2
11-17 18:21:16.492  1956  4065 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.example.hello.
,11-17 18:21:16.492  1956  4065 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db: 1
,11-17 18:21:16.502  1956  4066 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 18:21:16.512  1956  4065 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 1
,11-17 18:21:16.512  1956  4065 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 2
,11-17 18:21:16.512  1956  4065 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db: 1
,11-17 18:21:16.522  4050  4070 D Documents: Loading roots for com.android.externalstorage.documents
,11-17 18:21:16.522  1859  1859 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:21:16
,11-17 18:21:16.522  1859  1859 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,11-17 18:21:16.522  1859  1859 D WeatherQuickCover: 2 : quick cover state : opened : 0
,11-17 18:21:16.522   948  1513 I ActivityManager: Killing 3178:com.google.android.talk/u0a77 (adj 15): empty #17
11-17 18:21:16.532  1956  4065 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 1
11-17 18:21:16.532  1956  4065 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 2
11-17 18:21:16.532  1859  1859 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
11-17 18:21:16.532  1859  1859 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
11-17 18:21:16.532  1859  1859 D WeatherAncestor: 2 : shouldTimeTickRegistered().........
11-17 18:21:16.532  1956  4065 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db: 1
11-17 18:21:16.532  1859  1859 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.lge.weather.WIDGET_REFRESH } android.content.ContextWrapper.startService:494 android.content.ContextWrapper.startService:494 com.lge.sizechangable.weather.layout.WeatherWidget.onReceive:415 
11-17 18:21:16.532  1956  4065 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/metrics.db, release reference: 0
11-17 18:21:16.532  1956  4065 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/help_responses.db, release reference: 0
11-17 18:21:16.532  1859  1859 D WeatherService: 2 : TimeTick Receiver Register
11-17 18:21:16.532  1956  4065 D GOOGLEHELP_CompatibleDatabase: Close SQLiteDatabase: /data/data/com.google.android.gms/databases/auto_complete_suggestions.db, release reference: 0
11-17 18:21:16.532  1859  1859 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 18:21:16
11-17 18:21:16.532  1859  1859 D WeatherService: 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
11-17 18:21:16.532  1859  1859 D WeatherQuickCover: 2 : quick cover state : opened : 0
,11-17 18:21:16.552   948  1513 I ActivityManager: Start proc com.android.externalstorage for content provider com.android.externalstorage/.ExternalStorageProvider: pid=4071 uid=10005 gids={50005, 1028, 1015, 1023}
,11-17 18:21:16.552  1859  1859 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
,11-17 18:21:16.552   948   991 I ActivityManager: Timeline: Activity_windows_visible id: ActivityRecord{42c89920 u0 com.lge.launcher2/.Launcher t1} time:51405
,11-17 18:21:16.552  1859  1859 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,11-17 18:21:16.552  1489  1489 I ActivityManager: Timeline: Activity_idle id: android.os.BinderProxy@428a5fa8 time:51407
,11-17 18:21:16.552  1859  1859 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
11-17 18:21:16.552   948  1169 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{42c79ec0 stackId=0, 1 tasks}
,11-17 18:21:16.552   948  1169 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{42c89920 u0 com.lge.launcher2/.Launcher t1}
11-17 18:21:16.562  1859  1859 D WeatherService: 2 : onStartCommand, intent!=null, action: com.lge.weather.WIDGET_REFRESH
,11-17 18:21:16.562  1859  1859 D WeatherService: 2 : requestRefreshAppWidget, isUpdateStart : false
,11-17 18:21:16.562  1859  1859 D UpdateThreadPoolManager: 2 : This is isUpdating : false
11-17 18:21:16.562  1859  1859 D WeatherService: 2 : requestRefreshAppWidget, isUpdating : false
11-17 18:21:16.562  1859  1859 D WeatherAncestor: 2 : buildUpdate, appWidgetId: 1
,11-17 18:21:16.562  1859  1859 D WeatherReflect: 2 : Map key string is -2
,11-17 18:21:16.562  1859  1859 D lim     : 2 : time = 18:21
11-17 18:21:16.562  1859  1859 I WeatherReflect: Model Name : LG-D802
11-17 18:21:16.562  1859  1859 D WeatherTheme: 2 : Different view - status_min_formatted : 20 != 21
11-17 18:21:16.562  1859  1859 D WeatherTheme: 2 : widgetId = 1 : widgetSize = 1 : Refresh widgets.
11-17 18:21:16.562  1859  1859 D WeatherTheme: 2 : Current Theme Name: com.lge.launcher2.theme.optimus
11-17 18:21:16.562  1859  1859 D WeatherTheme: 2 : Fixed theme : optimus
,11-17 18:21:16.562  1859  1859 D WeatherTheme: 2 : package is not available: com.lge.sizechangable.weather.theme.optimus
,11-17 18:21:16.562  1859  1859 D WeatherQuickCover: 2 : quick cover state : opened : 0
11-17 18:21:16.562  1859  1859 D Weather.Utils: 2 : Utils getTopActivity com.lge.launcher2 / true
11-17 18:21:16.562  4071  4071 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
11-17 18:21:16.562  4071  4071 D HyLog   : I : /data/font/config/dfactpre.dat, No such file or directory (2)
,11-17 18:21:16.562  4071  4071 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
11-17 18:21:16.562  1859  1859 D WeatherService: 2 : shouldTimeTickRegistered - 4x2 : 1, 4x1 : 0, FphWidget : 0
,11-17 18:21:16.562  1859  1859 D WeatherService: 2 : shouldTimeTickRegistered : true - home screen widget is shown.
11-17 18:21:16.562   948   959 I ActivityManager: Killing 3739:com.lge.appbox.client:AppBoxCommonService/u0a11 (adj 15): empty #17
11-17 18:21:16.572   948  1171 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{42c79ec0 stackId=0, 1 tasks}
,11-17 18:21:16.572   948  1171 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{42c89920 u0 com.lge.launcher2/.Launcher t1}
,11-17 18:21:16.582  4071  4071 D ExternalStorage: After updating volumes, found 1 active roots
,11-17 18:21:16.582  4050  4050 D Documents: Updating roots due to change at content://com.android.externalstorage.documents/root
,11-17 18:21:16.592  4050  4070 D Documents: Loading roots for com.android.providers.downloads.documents
,11-17 18:21:16.602   948  1513 I ActivityManager: Start proc android.process.media for content provider com.android.providers.downloads/.DownloadStorageProvider: pid=4083 uid=10023 gids={50023, 1023, 1028, 1015, 1024, 2001, 3003, 3007, 4002}
,11-17 18:21:16.612   948  1486 I ActivityManager: Killing 3777:com.google.android.partnersetup/u0a9 (adj 15): empty #17
,11-17 18:21:16.612  4083  4083 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
,11-17 18:21:16.612  4083  4083 D HyLog   : I : /data/font/config/dfactpre.dat, No such file or directory (2)
,11-17 18:21:16.612  4083  4083 D HyLog   : I : /data/font/config/sfconfig.dat, No such file or directory (2)
11-17 18:21:16.612   948  1486 I ActivityManager: resumeTopActivitiesLocked(): target Stack:ActivityStack{42c79ec0 stackId=0, 1 tasks}
11-17 18:21:16.612   948  1486 D ActivityManager: resumeTopActivityLocked: Top activity resumed ActivityRecord{42c89920 u0 com.lge.launcher2/.Launcher t1}
,11-17 18:21:16.632   948  1486 I ActivityManager: Delaying start of: ServiceRecord{432e3ae0 u0 com.android.providers.downloads/.DownloadService}
,11-17 18:21:16.692  4050  4070 D Documents: Loading roots for com.android.providers.media.documents
,11-17 18:21:16.702  4050  4070 D Documents: Loading roots for com.google.android.apps.docs.storage
,11-17 18:21:16.722  1956  4064 W DriveInitializer: Awaiting to be initialized
,11-17 18:21:16.722  1956  4102 W DriveInitializer: Background init thread started
,11-17 18:21:16.722  1956  4102 E SQLiteLog: (3850) statement aborts at 5: [DELETE FROM ContentFileDeletionLock112] disk I/O error
,11-17 18:21:16.722  1956  4102 E DocListDatabase: Failed to delete from ContentFileDeletionLock112
11-17 18:21:16.722  1956  4102 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 18:21:16.722  1956  4102 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-17 18:21:16.722  1956  4102 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:737)
11-17 18:21:16.722  1956  4102 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
11-17 18:21:16.722  1956  4102 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-17 18:21:16.722  1956  4102 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
11-17 18:21:16.722  1956  4102 E DocListDatabase: 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
11-17 18:21:16.722  1956  4102 E DocListDatabase: 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
11-17 18:21:16.722  1956  4102 E DocListDatabase: 	at com.google.android.gms.drive.r.run(SourceFile:69)
11-17 18:21:16.722  1956  4102 W DriveInitializer: Background init thread ended
11-17 18:21:16.722  1956  4102 W dalvikvm: threadid=24: thread exiting with uncaught exception (group=0x41868e48)
,11-17 18:21:16.722  1956  4064 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,11-17 18:21:16.722  1956  4064 E DriveAsyncService: disk I/O error (code 3850)
11-17 18:21:16.722  1956  4064 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 18:21:16.722  1956  4064 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-17 18:21:16.722  1956  4064 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:558)
11-17 18:21:16.722  1956  4064 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
11-17 18:21:16.722  1956  4064 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
11-17 18:21:16.722  1956  4064 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
11-17 18:21:16.722  1956  4064 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
11-17 18:21:16.722  1956  4064 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.l(SourceFile:596)
11-17 18:21:16.722  1956  4064 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:570)
11-17 18:21:16.722  1956  4064 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.h(SourceFile:1473)
11-17 18:21:16.722  1956  4064 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bc.a(SourceFile:16)
11-17 18:21:16.722  1956  4064 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
11-17 18:21:16.722  1956  4064 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
11-17 18:21:16.722  1956  4064 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
11-17 18:21:16.722  1956  4064 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:841)
11-17 18:21:16.722  1956  4102 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
11-17 18:21:16.722  1956  4102 E AndroidRuntime: Process: com.google.android.gms, PID: 1956
11-17 18:21:16.722  1956  4102 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-17 18:21:16.722  1956  4102 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-17 18:21:16.722  1956  4102 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:737)
11-17 18:21:16.722  1956  4102 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:892)
11-17 18:21:16.722  1956  4102 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-17 18:21:16.722  1956  4102 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
11-17 18:21:16.722  1956  4102 E AndroidRuntime: 	at com.google.android.gms.drive.database.k.a(SourceFile:520)
11-17 18:21:16.722  1956  4102 E AndroidRuntime: 	at com.google.android.gms.drive.database.f.h(SourceFile:1056)
11-17 18:21:16.722  1956  4102 E AndroidRuntime: 	at com.google.android.gms.drive.r.run(SourceFile:69)
,11-17 18:21:16.722   948  4103 E DropBoxManagerService: Can't write: system_app_crash
11-17 18:21:16.722   948  4103 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop87.tmp: open failed: EROFS (Read-only file system)
11-17 18:21:16.722   948  4103 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:458)
11-17 18:21:16.722   948  4103 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:88)
11-17 18:21:16.722   948  4103 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:73)
11-17 18:21:16.722   948  4103 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-17 18:21:16.722   948  4103 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:272)
11-17 18:21:16.722   948  4103 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:10358)
11-17 18:21:16.722   948  4103 E DropBoxManagerService: Caused by: libcore.io.ErrnoException: open failed: EROFS (Read-only file system)
11-17 18:21:16.722   948  4103 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-17 18:21:16.722   948  4103 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:110)
11-17 18:21:16.722   948  4103 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
11-17 18:21:16.722   948  4103 E DropBoxManagerService: 	... 5 more
11-17 18:21:16.732  4050  4070 D Documents: Update found 7 roots in 217ms
11-17 18:21:16.732  4050  4104 D Documents: Loading roots for com.android.externalstorage.documents
11-17 18:21:16.732  4050  4104 D Documents: Used cached roots for com.android.providers.downloads.documents
11-17 18:21:16.732  4050  4104 D Documents: Used cached roots for com.android.providers.media.documents
11-17 18:21:16.732  4050  4104 D Documents: Used cached roots for com.google.android.apps.docs.storage
11-17 18:21:16.732  4050  4104 D Documents: Update found 7 roots in 7ms
,11-17 18:21:16.782   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:21:16.782   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=6
11-17 18:21:16.782   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:21:16.782   267   267 E qdoverlay: MdpData failed to play
11-17 18:21:16.782   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:21:16.782   267   267 E qdoverlay: == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
11-17 18:21:16.782   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:21:16.782   267   267 E qdoverlay: data msmfb_data offset=0 memid=74 id=0 flags=0x0 priv=0
11-17 18:21:16.782   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:21:16.782   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:21:16.782   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:21:16.782   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:21:16.782   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:21:16.782   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:21:16.802   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:21:16.802   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=6
11-17 18:21:16.802   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:21:16.802   267   267 E qdoverlay: MdpData failed to play
11-17 18:21:16.802   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:21:16.802   267   267 E qdoverlay: == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
11-17 18:21:16.802   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:21:16.802   267   267 E qdoverlay: data msmfb_data offset=0 memid=27 id=0 flags=0x0 priv=0
11-17 18:21:16.802   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:21:16.802   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:21:16.802   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:21:16.802   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:21:16.802   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:21:16.802   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:21:16.812   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:21:16.812   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:21:16.812   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:21:16.812   267   267 E qdoverlay: MdpData failed to play
11-17 18:21:16.812   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:21:16.812   267   267 E qdoverlay: == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
11-17 18:21:16.812   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:21:16.812   267   267 E qdoverlay: data msmfb_data offset=0 memid=30 id=0 flags=0x0 priv=0
11-17 18:21:16.812   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:21:16.812   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:21:16.812   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:21:16.812   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:21:16.812   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:21:16.812   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:21:16.832   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:21:16.832   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:21:16.832   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:21:16.832   267   267 E qdoverlay: MdpData failed to play
11-17 18:21:16.832   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:21:16.832   267   267 E qdoverlay: == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
11-17 18:21:16.832   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:21:16.832   267   267 E qdoverlay: data msmfb_data offset=0 memid=74 id=0 flags=0x0 priv=0
11-17 18:21:16.832   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:21:16.832   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:21:16.832   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:21:16.832   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:21:16.832   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:21:16.832   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:21:16.852   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:21:16.852   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:21:16.852   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:21:16.852   267   267 E qdoverlay: MdpData failed to play
11-17 18:21:16.852   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:21:16.852   267   267 E qdoverlay: == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
11-17 18:21:16.852   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:21:16.852   267   267 E qdoverlay: data msmfb_data offset=0 memid=27 id=0 flags=0x0 priv=0
11-17 18:21:16.852   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:21:16.852   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:21:16.852   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:21:16.852   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:21:16.852   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:21:16.852   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:21:16.862   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:21:16.862   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:21:16.862   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:21:16.862   267   267 E qdoverlay: MdpData failed to play
11-17 18:21:16.862   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:21:16.862   267   267 E qdoverlay: == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
11-17 18:21:16.862   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:21:16.862   267   267 E qdoverlay: data msmfb_data offset=0 memid=30 id=0 flags=0x0 priv=0
11-17 18:21:16.862   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:21:16.862   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:21:16.862   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:21:16.862   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:21:16.862   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:21:16.862   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:21:16.882   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:21:16.882   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:21:16.882   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:21:16.882   267   267 E qdoverlay: MdpData failed to play
11-17 18:21:16.882   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:21:16.882   267   267 E qdoverlay: == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
11-17 18:21:16.882   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:21:16.882   267   267 E qdoverlay: data msmfb_data offset=0 memid=74 id=0 flags=0x0 priv=0
11-17 18:21:16.882   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:21:16.882   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:21:16.882   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:21:16.882   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:21:16.882   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:21:16.882   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:21:16.902   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,11-17 18:21:16.902   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:21:16.902   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:21:16.902   267   267 E qdoverlay: MdpData failed to play
11-17 18:21:16.902   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:21:16.902   267   267 E qdoverlay: == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
11-17 18:21:16.902   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:21:16.902   267   267 E qdoverlay: data msmfb_data offset=0 memid=27 id=0 flags=0x0 priv=0
11-17 18:21:16.902   267   267 E qdoverlay: == Dump MdpData end ==
,11-17 18:21:16.902   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:21:16.902   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:21:16.902   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:21:16.902   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:21:16.902   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:21:16.912   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,11-17 18:21:16.912   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:21:16.912   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:21:16.912   267   267 E qdoverlay: MdpData failed to play
11-17 18:21:16.912   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:21:16.912   267   267 E qdoverlay: == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
11-17 18:21:16.912   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:21:16.912   267   267 E qdoverlay: data msmfb_data offset=0 memid=30 id=0 flags=0x0 priv=0
11-17 18:21:16.912   267   267 E qdoverlay: == Dump MdpData end ==
,11-17 18:21:16.912   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:21:16.912   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:21:16.912   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:21:16.912   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:21:16.912   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:21:16.932   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,11-17 18:21:16.932   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:21:16.932   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:21:16.932   267   267 E qdoverlay: MdpData failed to play
11-17 18:21:16.932   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:21:16.932   267   267 E qdoverlay: == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
11-17 18:21:16.932   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:21:16.932   267   267 E qdoverlay: data msmfb_data offset=0 memid=74 id=0 flags=0x0 priv=0
11-17 18:21:16.932   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:21:16.932   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:21:16.932   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
,11-17 18:21:16.932   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:21:16.932   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:21:16.932   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:21:16.952   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:21:16.952   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:21:16.952   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:21:16.952   267   267 E qdoverlay: MdpData failed to play
11-17 18:21:16.952   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:21:16.952   267   267 E qdoverlay: == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
11-17 18:21:16.952   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:21:16.952   267   267 E qdoverlay: data msmfb_data offset=0 memid=27 id=0 flags=0x0 priv=0
11-17 18:21:16.952   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:21:16.952   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:21:16.952   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:21:16.952   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:21:16.952   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:21:16.952   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:21:16.962   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
11-17 18:21:16.972   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:21:16.972   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:21:16.972   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:21:16.972   267   267 E qdoverlay: MdpData failed to play
11-17 18:21:16.972   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:21:16.972   267   267 E qdoverlay: == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
11-17 18:21:16.972   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:21:16.972   267   267 E qdoverlay: data msmfb_data offset=0 memid=30 id=0 flags=0x0 priv=0
11-17 18:21:16.972   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:21:16.972   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:21:16.972   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:21:16.972   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:21:16.972   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
11-17 18:21:16.972   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:21:16.982   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
11-17 18:21:16.982   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:21:16.982   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:21:16.982   267   267 E qdoverlay: MdpData failed to play
11-17 18:21:16.982   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:21:16.982   267   267 E qdoverlay: == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
11-17 18:21:16.982   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:21:16.982   267   267 E qdoverlay: data msmfb_data offset=0 memid=74 id=0 flags=0x0 priv=0
11-17 18:21:16.982   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:21:16.982   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:21:16.982   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:21:16.982   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:21:16.982   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:21:16.982   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:21:17.002   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,11-17 18:21:17.002   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:21:17.002   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:21:17.002   267   267 E qdoverlay: MdpData failed to play
11-17 18:21:17.002   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:21:17.002   267   267 E qdoverlay: == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
11-17 18:21:17.002   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:21:17.002   267   267 E qdoverlay: data msmfb_data offset=0 memid=27 id=0 flags=0x0 priv=0
11-17 18:21:17.002   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:21:17.002   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:21:17.002   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
,11-17 18:21:17.002   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:21:17.002   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:21:17.002   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
,11-17 18:21:17.022   267   267 E qdhwcomposer: hwc_sync: ioctl MSMFB_BUFFER_SYNC failed, err=Operation not permitted
,11-17 18:21:17.022   267   267 E qdhwcomposer: hwc_sync: acq_fen_fd_cnt=1 flags=0 fd=16 dpy=0 numHwLayers=7
11-17 18:21:17.022   267   267 E qdoverlay: Failed to call ioctl MSMFB_OVERLAY_PLAY err=Operation not permitted
11-17 18:21:17.022   267   267 E qdoverlay: MdpData failed to play
11-17 18:21:17.022   267   267 E qdoverlay: == Dump MdpData start ==
11-17 18:21:17.022   267   267 E qdoverlay: == Dump OvFD fd=38 path=/dev/graphics/fb0 start/end ==
11-17 18:21:17.022   267   267 E qdoverlay: mOvData msmfb_overlay_data id=8
11-17 18:21:17.022   267   267 E qdoverlay: data msmfb_data offset=0 memid=30 id=0 flags=0x0 priv=0
,11-17 18:21:17.022   267   267 E qdoverlay: == Dump MdpData end ==
11-17 18:21:17.022   267   267 E qdhwcomposer: draw: queueBuffer failed for FBUpdate
11-17 18:21:17.022   267   267 E qdhwcomposer: hwc_set_primary: FBUpdate draw failed
11-17 18:21:17.022   267   267 E qdoverlay: Failed to call ioctl MSMFB_DISPLAY_COMMIT err=Operation not permitted
11-17 18:21:17.022   267   267 E qdoverlay: static bool overlay::Overlay::displayCommit(const int&, const overlay::utils::Dim&): commit failed
,11-17 18:21:17.022   267   267 E qdhwcomposer: hwc_set_primary: display commit fail for 0 dpy!
11-17 18:21:17.022   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
,11-17 18:21:17.082   259   299 I Vold    : [LGE][VOLD][NetlinkHandler.cpp][onEvent()] subsys:cpu, action:0
```
