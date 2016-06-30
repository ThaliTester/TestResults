#### Test 757892682551a10_thali04_htc-Nexus 9 Logs


```
--------- beginning of main
,06-30 13:52:29.366  1219  1337 I Icing   : Indexing FE72E5689930BAC1831A9FCDE09FBA6A729DB6B4 from com.google.android.googlequicksearchbox
06-30 13:52:29.429  1219  1337 I Icing   : Indexing done FE72E5689930BAC1831A9FCDE09FBA6A729DB6B4
06-30 13:52:29.730  2358  2358 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 13:52:29.734  2358  2358 D AndroidRuntime: CheckJNI is OFF
06-30 13:52:29.768  2358  2358 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 13:52:29.801  2358  2358 I Radio-JNI: register_android_hardware_Radio DONE
06-30 13:52:29.824  2358  2358 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
06-30 13:52:29.829   556  1154 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 13:52:29.844  2358  2358 D AndroidRuntime: Shutting down VM
06-30 13:52:29.853  1080  1091 W SearchService: Abort, client detached.
06-30 13:52:29.866   556  1097 I ActivityManager: Start proc 2367:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
06-30 13:52:29.869  1080  1080 I HotwordDetector: Closing mic
06-30 13:52:29.869  1080  1326 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@dcdc04f
06-30 13:52:29.881   221   645 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
06-30 13:52:29.882  1080  1080 W ErrorReporter: reportError [type: 29, code: 917507]: null
06-30 13:52:29.888  1080  1332 I MicroRecognitionRnrImpl: Detection finished
06-30 13:52:29.888  1080  1328 I MicroRecognitionRnrImpl: Stopping hotword detection.
06-30 13:52:29.979  2367  2367 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,06-30 13:52:30.110  2367  2367 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
06-30 13:52:30.133  2367  2367 I LibraryLoader: Time to load native libraries: 14 ms (timestamps 8582-8596)
06-30 13:52:30.133  2367  2367 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:52:30.174  2367  2367 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {dd9bb47}
06-30 13:52:30.174  2367  2367 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:52:30.174  2367  2367 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 13:52:30.179  2367  2367 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 13:52:30.180  2367  2367 E SysUtils: ApplicationContext is null in ApplicationStatus
06-30 13:52:30.210  2367  2383 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
06-30 13:52:30.216  2367  2367 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
06-30 13:52:30.234  2367  2367 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 13:52:30.234  2367  2367 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 13:52:30.502   556   602 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a08c4b:true
06-30 13:52:30.556  2367  2367 W AwContents: onDetachedFromWindow called when already detached. Ignoring
06-30 13:52:30.573  2367  2367 D SystemWebViewEngine: CordovaWebView is running on device made by: htc
06-30 13:52:30.631  2367  2407 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
06-30 13:52:30.647  2367  2394 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
06-30 13:52:30.673  2367  2407 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 13:52:30.762   556   604 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +907ms
06-30 13:52:30.767   994   994 I Keyboard.Facilitator: onFinishInput()
06-30 13:52:30.841  2367  2367 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 2367
06-30 13:52:30.851   556  1079 I ActivityManager: Killing 1823:com.google.android.apps.fitness/u0a45 (adj 15): empty #17
06-30 13:52:30.894   556  1079 I ActivityManager: Killing 2033:com.google.android.youtube/u0a81 (adj 15): empty #18
06-30 13:52:30.958  2367  2367 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
06-30 13:52:31.114  2367  2408 D jxcore_app_log: JniHelper::setJavaVM(0xab0957b8), pthread_self() = -552277712
06-30 13:52:31.123  2367  2408 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 13:52:31.123  2367  2408 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 13:52:31.123  2367  2408 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 13:52:31.123  2367  2408 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 13:52:31.123  2367  2408 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 13:52:31.124  2367  2408 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4f6fb2a added. We now have 1 listener(s)
06-30 13:52:31.127  2367  2408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: B4:CE:F6:34:3D:CC
06-30 13:52:31.130  2367  2408 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "B4:CE:F6:34:3D:CC"
06-30 13:52:31.131  2367  2408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 13:52:31.132  2367  2408 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-30 13:52:31.134  2367  2408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 13:52:31.134  2367  2408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 13:52:31.134  2367  2408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 13:52:31.134  2367  2408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: B4:CE:F6:34:3D:CC
06-30 13:52:31.134  2367  2408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 13:52:31.134  2367  2408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 13:52:31.134  2367  2408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 13:52:31.134  2367  2408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 13:52:31.134  2367  2408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 13:52:31.134  2367  2408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 13:52:31.134  2367  2408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 13:52:31.135  2367  2408 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d989491 added. We now have 1 listener(s)
06-30 13:52:31.135  2367  2408 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 13:52:31.141   556   664 D WifiService: New client listening to asynchronous messages
06-30 13:52:31.141  2367  2408 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 13:52:31.141  2367  2408 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
06-30 13:52:31.146  2367  2408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 13:52:31.147  2367  2408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 13:52:31.147  2367  2408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 13:52:31.147  2367  2408 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-30 13:52:31.149  2367  2408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 13:52:31.149  2367  2408 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is B4:CE:F6:34:3D:CC
06-30 13:52:31.151  2367  2408 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 13:52:31.151  2367  2408 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 13:52:31.151  2367  2408 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:52:31.151  2367  2408 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 13:52:31.151  2367  2408 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:52:31.151  2367  2408 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:52:31.151  2367  2408 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:52:31.151  2367  2408 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:52:31.151  2367  2408 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:52:31.151  2367  2408 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 13:52:31.151  2367  2408 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 13:52:31.152  2367  2408 I io.jxcore.node.LifeCycleMonitor: start: OK
06-30 13:52:31.199  2367  2367 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 13:52:31.761  2367  2416 W jxcore-log: Initializing JXcore engine
06-30 13:52:31.761  2367  2416 W jxcore-log: JXcore engine is ready
06-30 13:52:31.803  2416  2416 W Thread-53: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=10101 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
06-30 13:52:31.803  2416  2416 W Thread-53: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[5601]" dev="sockfs" ino=5601 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
06-30 13:52:31.803  2416  2416 W Thread-53: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=454 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-30 13:52:31.803  2416  2416 W Thread-53: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[17333]" dev="sockfs" ino=17333 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
06-30 13:52:31.816  2367  2416 W jxcore-log: Starting JXcore engine
,06-30 13:52:33.383  1100  1100 I ConfigService: onDestroy
,06-30 13:52:33.938  2367  2416 W jxcore-log: Platform android
06-30 13:52:33.938  2367  2416 W jxcore-log: 
,06-30 13:52:33.938  2367  2416 W jxcore-log: Process ARCH arm
06-30 13:52:33.938  2367  2416 W jxcore-log: 
,06-30 13:52:34.064  2367  2416 I jxcore-log: JXcore Cordova bridge is ready!
06-30 13:52:34.064  2367  2416 I jxcore-log: 
06-30 13:52:34.064  2367  2416 W jxcore-log: JXcore engine is started
,06-30 13:52:34.068  2367  2408 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 13:52:34.069   556  1154 I ActivityManager: START u0 {act=android.content.pm.action.REQUEST_PERMISSIONS pkg=com.android.packageinstaller cmp=com.android.packageinstaller/.permission.ui.GrantPermissionsActivity (has extras)} from uid 10000 on display 0
,06-30 13:52:34.080  2367  2367 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,06-30 13:52:34.080  2367  2367 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,06-30 13:52:34.094   556   578 I ActivityManager: Start proc 2439:com.android.packageinstaller/u0a64 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
,06-30 13:52:34.151  2439  2439 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm64
,06-30 13:52:34.261  2439  2452 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,06-30 13:52:34.304  2439  2452 I OpenGLRenderer: Initialized EGL, version 1.4
,06-30 13:52:34.352   994   994 I Keyboard.Facilitator: onFinishInput()
,06-30 13:52:34.389   556   604 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +305ms
,06-30 13:52:34.578  2367  2367 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1e7c255 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@fd9778, 16908290=android.view.AbsSavedState$1@fd9778}, android:focusedViewId=100}]}]
06-30 13:52:34.578  2367  2367 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,06-30 13:52:40.053  1100  1110 I art     : Background partial concurrent mark sweep GC freed 10971(738KB) AllocSpace objects, 2(80KB) LOS objects, 40% free, 12MB/20MB, paused 6.625ms total 45.757ms
,06-30 13:52:42.968  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:52:42.972  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:52:42.973  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:52:42.987  1100  1112 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 13:52:42.987  1100  1112 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 13:52:42.987  1100  1112 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 13:52:42.987  1100  1112 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 13:52:43.005  1705  1705 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 13:52:43.006  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 13:52:43.006  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,06-30 13:53:03.096  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:03.100  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:03.101  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:03.115  1100  1111 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 13:53:03.115  1100  1111 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 13:53:03.115  1100  1111 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 13:53:03.115  1100  1111 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 13:53:03.127  1705  1705 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 13:53:03.127  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 13:53:03.127  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,06-30 13:53:24.673   556   606 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,06-30 13:53:24.685   994   994 I Keyboard.Facilitator: onFinishInput()
,06-30 13:53:24.704   556   606 I PowerManagerService: Sleeping (uid 1000)...
,06-30 13:53:24.711   171   971 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (333 us)
,06-30 13:53:24.849  2367  2367 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,06-30 13:53:24.849  2367  2367 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,06-30 13:53:24.954   556   566 I art     : Background partial concurrent mark sweep GC freed 9093(706KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 16MB/25MB, paused 16.248ms total 159.130ms
,06-30 13:53:25.470   556   606 V KeyguardServiceDelegate: onScreenTurnedOff()
,06-30 13:53:25.489   556   606 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,06-30 13:53:25.490   556   604 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
06-30 13:53:25.494   171   171 D SurfaceFlinger: Set power mode=0, type=0 flinger=0x55a9974430
06-30 13:53:25.495   171   171 D hwcomposer: hwc_blank: display 0: blank
06-30 13:53:25.496   171   171 D hwcomposer: hwc_blank_display: display 0: [0 -> 1]
,06-30 13:53:25.798   556   682 D SurfaceControl: Excessive delay in setPowerMode(): 307ms
,06-30 13:53:25.900   556   663 D WifiConfigStore: Retrieve network priorities after PNO.
,06-30 13:53:25.914   556   663 E WifiStateMachine:  Fail to set up pno, want false now false
,06-30 13:53:25.943   556   663 D WifiConfigStore: Retrieve network priorities after PNO.
,06-30 13:53:25.943   556   663 E WifiStateMachine:  Fail to set up pno, want false now false
,06-30 13:53:28.272  1061  1415 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 13:53:29.963  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:29.970  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:29.971  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:29.991  1100  2265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 13:53:29.991  1100  2265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 13:53:29.991  1100  2265 I GLSUser : [GLSUser] Extracting token using key: Auth
,06-30 13:53:29.992  1100  2265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 13:53:30.011  1705  1705 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 13:53:30.012  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 13:53:30.012  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,06-30 13:53:56.077  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:56.084  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:56.086  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:53:56.106  1100  1302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 13:53:56.106  1100  1302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 13:53:56.107  1100  1302 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 13:53:56.107  1100  1302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 13:53:56.123  1705  1705 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 13:53:56.123  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 13:53:56.124  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,06-30 13:54:24.689   994  1098 I Keyboard.Facilitator.LanguageModelFlusher: run()
,06-30 13:54:24.690   994  1098 I Keyboard.Facilitator: flushDynamicLanguageModels()
,06-30 13:54:24.717  1100  1100 I ConfigService: onCreate
,06-30 13:54:29.763  1100  1100 I ConfigService: onDestroy
,06-30 13:54:30.012  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:54:30.018  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:54:30.019  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:54:30.039  1100  1111 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 13:54:30.039  1100  1111 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 13:54:30.039  1100  1111 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 13:54:30.039  1100  1111 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 13:54:30.055  1705  1705 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
06-30 13:54:30.056  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 13:54:30.056  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,06-30 13:54:50.193  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:54:50.198  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:54:50.200  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:54:50.228  1100  1111 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 13:54:50.228  1100  1111 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 13:54:50.229  1100  1111 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 13:54:50.229  1100  1111 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 13:54:50.255  1705  1705 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 13:54:50.255  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 13:54:50.255  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,06-30 13:56:25.269  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:56:25.283  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
06-30 13:56:25.286  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:56:25.317  1100  1112 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 13:56:25.317  1100  1112 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 13:56:25.317  1100  1112 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 13:56:25.317  1100  1112 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 13:56:25.358  1100  1112 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 13:56:25.358  1100  1112 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 13:56:25.358  1100  1112 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 13:56:25.358  1100  1112 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 13:56:25.358  1100  1112 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 13:56:25.358  1100  1112 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 13:56:25.358  1100  1112 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:56:25.364  1705  1745 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 13:56:25.364  1705  1745 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 13:56:25.364  1705  1745 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 13:56:25.364  1705  1745 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 13:56:25.364  1705  1745 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 13:56:25.364  1705  1745 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 13:56:25.364  1705  1745 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:01:25.428  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:01:25.442  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:01:25.447  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:01:25.485  1100  1111 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 14:01:25.486  1100  1111 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 14:01:25.486  1100  1111 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 14:01:25.486  1100  1111 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 14:01:25.505  1100  1111 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 14:01:25.505  1100  1111 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 14:01:25.505  1100  1111 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 14:01:25.505  1100  1111 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 14:01:25.505  1100  1111 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:01:25.505  1100  1111 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:01:25.505  1100  1111 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:01:25.509  1705  1745 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 14:01:25.509  1705  1745 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 14:01:25.509  1705  1745 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 14:01:25.509  1705  1745 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 14:01:25.509  1705  1745 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 14:01:25.509  1705  1745 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 14:01:25.509  1705  1745 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:02:01.906  1705  1705 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,06-30 14:02:01.921  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:02:01.932  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:02:01.934  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:02:01.963  1100  1111 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 14:02:01.963  1100  1111 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 14:02:01.964  1100  1111 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 14:02:01.964  1100  1111 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 14:02:02.001  1705  1705 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,06-30 14:02:02.014  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:02:02.043  1100  1111 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 14:02:02.043  1100  1111 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 14:02:02.044  1100  1111 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 14:02:02.044  1100  1111 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 14:02:02.068  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:02:02.088  1100  1111 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 14:02:02.088  1100  1111 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 14:02:02.088  1100  1111 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 14:02:02.088  1100  1111 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 14:02:02.105  1705  1705 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,06-30 14:02:02.208  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:02:02.244  1100  2265 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 14:02:02.244  1100  2265 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 14:02:02.244  1100  2265 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 14:02:02.244  1100  2265 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 14:02:02.274  1705  1705 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,06-30 14:02:02.276  1705  1705 D Finsky  : [1] WearSupportService.startHygiene: disabled
,06-30 14:02:02.278  1705  1705 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,06-30 14:02:02.282  1705  2241 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186446
,06-30 14:02:02.283  1705  1705 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 28 minutes (failures=2)
,06-30 14:02:17.215  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:02:17.226  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:02:17.228  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:02:17.251  1100  1302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 14:02:17.251  1100  1302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 14:02:17.251  1100  1302 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 14:02:17.251  1100  1302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 14:02:17.272  1705  1705 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 14:02:17.272  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 14:02:17.272  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,06-30 14:02:37.393  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:02:37.400  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:02:37.401  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:02:37.422  1100  1302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 14:02:37.422  1100  1302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 14:02:37.422  1100  1302 I GLSUser : [GLSUser] Extracting token using key: Auth
,06-30 14:02:37.422  1100  1302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 14:02:37.438  1705  1705 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 14:02:37.438  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 14:02:37.439  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,06-30 14:02:57.557  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:02:57.564  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:02:57.566  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:02:57.587  1100  1111 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 14:02:57.587  1100  1111 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 14:02:57.587  1100  1111 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 14:02:57.588  1100  1111 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 14:02:57.606  1705  1705 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
06-30 14:02:57.606  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 14:02:57.608  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,06-30 14:03:17.719  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:03:17.725  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:03:17.727  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:03:17.747  1100  1111 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 14:03:17.748  1100  1111 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 14:03:17.748  1100  1111 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 14:03:17.748  1100  1111 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 14:03:17.766  1705  1705 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 14:03:17.766  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 14:03:17.767  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,06-30 14:03:37.869  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:03:37.876  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:03:37.877  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:03:37.896  1100  1161 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 14:03:37.896  1100  1161 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 14:03:37.897  1100  1161 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 14:03:37.897  1100  1161 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 14:03:37.912  1705  1705 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 14:03:37.912  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 14:03:37.912  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,06-30 14:03:58.019  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:03:58.025  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:03:58.027  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:03:58.051  1100  1111 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 14:03:58.052  1100  1111 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 14:03:58.052  1100  1111 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 14:03:58.052  1100  1111 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 14:03:58.074  1705  1705 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 14:03:58.074  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 14:03:58.074  1705  1705 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,06-30 14:04:02.027  1100  1241 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 14:06:25.542  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:25.555  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:25.558  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:06:25.593  1100  1302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,06-30 14:06:25.593  1100  1302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,06-30 14:06:25.593  1100  1302 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 14:06:25.593  1100  1302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 14:06:25.615  1100  1302 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 14:06:25.615  1100  1302 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 14:06:25.615  1100  1302 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 14:06:25.615  1100  1302 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 14:06:25.615  1100  1302 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:06:25.615  1100  1302 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:06:25.615  1100  1302 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:06:25.619  1705  1745 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 14:06:25.619  1705  1745 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 14:06:25.619  1705  1745 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 14:06:25.619  1705  1745 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 14:06:25.619  1705  1745 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 14:06:25.619  1705  1745 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 14:06:25.619  1705  1745 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:11:11.230   556   590 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 14:11:25.662  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:11:25.673  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:11:25.674  1100  1100 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 14:11:25.701  1100  1302 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
06-30 14:11:25.701  1100  1302 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 14:11:25.702  1100  1302 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 14:11:25.702  1100  1302 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 14:11:25.719  1100  1302 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 14:11:25.719  1100  1302 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 14:11:25.719  1100  1302 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 14:11:25.719  1100  1302 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 14:11:25.719  1100  1302 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 14:11:25.719  1100  1302 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 14:11:25.719  1100  1302 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 14:11:25.723  1705  1745 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 14:11:25.723  1705  1745 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 14:11:25.723  1705  1745 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 14:11:25.723  1705  1745 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 14:11:25.723  1705  1745 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 14:11:25.723  1705  1745 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 14:11:25.723  1705  1745 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms)
```
