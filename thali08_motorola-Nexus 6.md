#### Test 7578926851a8f91_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main,
06-30 12:52:04.788  1915  2155 I Icing   : Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
06-30 12:52:04.843  1915  2155 D Icing   : Loaded CLD2 Version V2.0 - 20141016
06-30 12:52:04.905  1915  2155 I Icing   : Indexing done 0A4562BF807829C124E952811A67787B55D6217E
06-30 12:52:05.430  3307  3307 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
06-30 12:52:05.435  3307  3307 D AndroidRuntime: CheckJNI is OFF
06-30 12:52:05.471  3307  3307 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
06-30 12:52:05.513  3307  3307 I Radio-JNI: register_android_hardware_Radio DONE
06-30 12:52:05.534  3307  3307 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
06-30 12:52:05.540   875  1384 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 12:52:05.613  1807  1828 W SearchService: Abort, client detached.
06-30 12:52:05.640  3307  3307 D AndroidRuntime: Shutting down VM
06-30 12:52:05.641  1807  2121 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@bde2bb3
06-30 12:52:05.643  1807  2137 E AudioRecord-JNI: Error -4 during AudioRecord native read
06-30 12:52:05.643  1807  1807 I HotwordDetector: Closing mic
06-30 12:52:05.671   875  1836 I ActivityManager: Start proc 3316:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
06-30 12:52:05.684  1807  1807 W ErrorReporter: reportError [type: 29, code: 917507]: null
06-30 12:52:05.702   376  2139 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
06-30 12:52:05.703   376  2139 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
06-30 12:52:05.709   376  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
06-30 12:52:05.711  1807  2136 I MicroRecognitionRnrImpl: Detection finished
06-30 12:52:05.712  1807  2135 I MicroRecognitionRnrImpl: Stopping hotword detection.
06-30 12:52:05.737  3316  3316 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
06-30 12:52:05.757  3316  3316 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
06-30 12:52:05.764  3316  3316 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4129-4131)
06-30 12:52:05.764  3316  3316 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 12:52:05.776  3316  3316 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a56897d}
06-30 12:52:05.777  3316  3316 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 12:52:05.777  3316  3316 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 12:52:05.782  3316  3316 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 12:52:05.783  3316  3316 E SysUtils: ApplicationContext is null in ApplicationStatus
06-30 12:52:05.809  3316  3332 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
06-30 12:52:05.816  3316  3316 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
06-30 12:52:05.825  3316  3316 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 12:52:05.825  3316  3316 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
06-30 12:52:05.825  3316  3316 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
06-30 12:52:05.825  3316  3316 I Adreno  : Build Date                       : 10/20/15
06-30 12:52:05.825  3316  3316 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
06-30 12:52:05.825  3316  3316 I Adreno  : Local Branch                     : M14
06-30 12:52:05.825  3316  3316 I Adreno  : Remote Branch                    : 
06-30 12:52:05.825  3316  3316 I Adreno  : Remote Branch                    : 
06-30 12:52:05.825  3316  3316 I Adreno  : Reconstruct Branch               : 
,06-30 12:52:05.922   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@85b7482:true
06-30 12:52:05.955  3316  3316 W AwContents: onDetachedFromWindow called when already detached. Ignoring
06-30 12:52:05.970  3316  3316 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
06-30 12:52:06.044  3316  3354 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
06-30 12:52:06.052  3316  3341 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
06-30 12:52:06.091  3316  3354 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 12:52:06.231   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +574ms
06-30 12:52:06.234  1663  1663 I Keyboard.Facilitator: onFinishInput()
06-30 12:52:06.364  3316  3316 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3316
06-30 12:52:06.479   875  1385 I ActivityManager: Killing 3002:com.qualcomm.telephony/1001 (adj 15): empty #17
06-30 12:52:06.510  3316  3316 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
06-30 12:52:06.522   875  1385 I ActivityManager: Killing 2900:com.google.android.youtube/u0a86 (adj 15): empty #18
06-30 12:52:06.644  3316  3357 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1686111952
06-30 12:52:06.649  3316  3357 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 12:52:06.649  3316  3357 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 12:52:06.649  3316  3357 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 12:52:06.649  3316  3357 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 12:52:06.649  3316  3357 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 12:52:06.649  3316  3357 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@73fa518 added. We now have 1 listener(s)
06-30 12:52:06.651  3316  3357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
06-30 12:52:06.652  3316  3357 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
06-30 12:52:06.652  3316  3357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 12:52:06.652  3316  3357 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-30 12:52:06.655  3316  3357 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 12:52:06.655  3316  3357 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 12:52:06.655  3316  3357 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 12:52:06.655  3316  3357 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
06-30 12:52:06.655  3316  3357 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 12:52:06.655  3316  3357 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 12:52:06.655  3316  3357 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 12:52:06.655  3316  3357 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 12:52:06.655  3316  3357 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 12:52:06.655  3316  3357 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 12:52:06.655  3316  3357 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 12:52:06.655  3316  3357 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f981d7 added. We now have 1 listener(s)
06-30 12:52:06.655  3316  3357 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 12:52:06.664  3316  3357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 12:52:06.664  3316  3357 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
06-30 12:52:06.665  3316  3357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 12:52:06.665  3316  3357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 12:52:06.665   875  1311 D WifiService: New client listening to asynchronous messages
06-30 12:52:06.666  3316  3357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 12:52:06.668  3316  3357 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-30 12:52:06.672  3316  3357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 12:52:06.672  3316  3357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
06-30 12:52:06.681  3316  3357 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 12:52:06.681  3316  3357 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 12:52:06.681  3316  3357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 12:52:06.681  3316  3357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 12:52:06.681  3316  3357 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 12:52:06.681  3316  3357 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 12:52:06.681  3316  3357 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 12:52:06.681  3316  3357 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 12:52:06.681  3316  3357 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 12:52:06.681  3316  3357 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 12:52:06.681  3316  3357 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 12:52:06.682  3316  3357 I io.jxcore.node.LifeCycleMonitor: start: OK
06-30 12:52:06.682  3316  3316 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 12:52:06.708  3316  3316 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 12:52:07.667  3316  3367 W jxcore-log: Initializing JXcore engine
06-30 12:52:07.667  3316  3367 W jxcore-log: JXcore engine is ready
06-30 12:52:07.753  3367  3367 W Thread-285: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8943 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
06-30 12:52:07.753  3367  3367 W Thread-285: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[12740]" dev="sockfs" ino=12740 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
06-30 12:52:07.753  3367  3367 W Thread-285: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
06-30 12:52:07.753  3367  3367 W Thread-285: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[22186]" dev="sockfs" ino=22186 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
06-30 12:52:07.778  3316  3367 W jxcore-log: Starting JXcore engine
06-30 12:52:07.821   875  1702 I ActivityManager: Killing 2694:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
06-30 12:52:07.922  3316  3367 W jxcore-log: Platform android
06-30 12:52:07.922  3316  3367 W jxcore-log: 
06-30 12:52:07.923  3316  3367 W jxcore-log: Process ARCH arm
06-30 12:52:07.923  3316  3367 W jxcore-log: 
06-30 12:52:08.118  3316  3367 I jxcore-log: JXcore Cordova bridge is ready!
06-30 12:52:08.118  3316  3367 I jxcore-log: 
06-30 12:52:08.118  3316  3367 W jxcore-log: JXcore engine is started
06-30 12:52:08.128  3316  3357 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
06-30 12:52:08.130   875  1384 I ActivityManager: START u0 {act=android.content.pm.action.REQUEST_PERMISSIONS pkg=com.android.packageinstaller cmp=com.android.packageinstaller/.permission.ui.GrantPermissionsActivity (has extras)} from uid 10000 on display 0
06-30 12:52:08.135  3316  3316 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
06-30 12:52:08.136  3316  3316 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
06-30 12:52:08.157   875  1835 I ActivityManager: Start proc 3368:com.android.packageinstaller/u0a69 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
06-30 12:52:08.220  3368  3368 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
06-30 12:52:08.353  3368  3381 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
06-30 12:52:08.459  3368  3381 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
06-30 12:52:08.459  3368  3381 I Adreno  : Build Date                       : 10/20/15
06-30 12:52:08.459  3368  3381 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
06-30 12:52:08.459  3368  3381 I Adreno  : Local Branch                     : M14
06-30 12:52:08.459  3368  3381 I Adreno  : Remote Branch                    : 
06-30 12:52:08.459  3368  3381 I Adreno  : Remote Branch                    : 
06-30 12:52:08.459  3368  3381 I Adreno  : Reconstruct Branch               : 
06-30 12:52:08.467  3368  3381 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 12:52:08.499  1663  1663 I Keyboard.Facilitator: onFinishInput()
,06-30 12:52:08.545   875   893 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +402ms
,06-30 12:52:08.718  3316  3316 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c51f13b Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@9f96416, 16908290=android.view.AbsSavedState$1@9f96416}, android:focusedViewId=100}]}]
,06-30 12:52:08.718  3316  3316 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,06-30 12:52:08.725  1513  1513 I ConfigService: onDestroy
,06-30 12:52:18.043   875   888 I ActivityManager: Waited long enough for: ServiceRecord{a5440b0 u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,06-30 12:52:23.665  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:52:23.681  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:52:23.686  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:52:23.774  1513  2071 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 12:52:23.774  1513  2071 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,06-30 12:52:23.775  1513  2071 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 12:52:23.775  1513  2071 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 12:52:23.837  2571  2571 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 12:52:23.838  2571  2571 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 12:52:23.839  2571  2571 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,06-30 12:52:51.807   875   895 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,06-30 12:52:51.816  1663  1663 I Keyboard.Facilitator: onFinishInput()
,06-30 12:52:51.838   875   895 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
06-30 12:52:51.838   875   895 I Adreno  : Build Date                       : 10/20/15
06-30 12:52:51.838   875   895 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
06-30 12:52:51.838   875   895 I Adreno  : Local Branch                     : M14
06-30 12:52:51.838   875   895 I Adreno  : Remote Branch                    : 
06-30 12:52:51.838   875   895 I Adreno  : Remote Branch                    : 
06-30 12:52:51.838   875   895 I Adreno  : Reconstruct Branch               : 
,06-30 12:52:51.879   281   358 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (311 us)
,06-30 12:52:51.939   875   884 I art     : Background partial concurrent mark sweep GC freed 27553(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 1.199ms total 114.990ms
,06-30 12:52:52.579   875   895 V KeyguardServiceDelegate: onScreenTurnedOff()
,06-30 12:52:52.589   875   895 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,06-30 12:52:52.590  3316  3316 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
06-30 12:52:52.590  3316  3316 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,06-30 12:52:52.594   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,06-30 12:52:52.594   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
06-30 12:52:52.594   875   893 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,06-30 12:52:52.827   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,06-30 12:52:52.829   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,06-30 12:52:52.835   875  1337 D SurfaceControl: Excessive delay in setPowerMode(): 240ms
,06-30 12:52:52.840   875   895 I DreamManagerService: Entering dreamland.
,06-30 12:52:52.842   875   895 I PowerManagerService: Dozing...
,06-30 12:52:52.843   875   890 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,06-30 12:52:52.872   376  1280 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,06-30 12:52:52.873   376  1280 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,06-30 12:52:52.883   875  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,06-30 12:52:52.885   875  1309 E native  : do suspend false
,06-30 12:52:52.986  1730  3396 D NfcService: Discovery configuration equal, not updating.
,06-30 12:52:53.015   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
06-30 12:52:53.015   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,06-30 12:52:53.019   875  1309 D WifiConfigStore: Retrieve network priorities after PNO.
,06-30 12:52:53.022   875  1309 E native  : do suspend true
,06-30 12:52:57.146  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:52:57.162  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:52:57.168  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:52:57.236  1513  2674 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 12:52:57.236  1513  2674 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,06-30 12:52:57.237  1513  2674 I GLSUser : [GLSUser] Extracting token using key: Auth
,06-30 12:52:57.237  1513  2674 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 12:52:57.284  1845  2314 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 12:52:57.285  2571  2571 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 12:52:57.286  2571  2571 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 12:52:57.289  2571  2571 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,06-30 12:53:23.369  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:53:23.380  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:53:23.385  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:53:23.439  1513  2071 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 12:53:23.439  1513  2071 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,06-30 12:53:23.440  1513  2071 I GLSUser : [GLSUser] Extracting token using key: Auth
,06-30 12:53:23.440  1513  2071 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 12:53:23.476  2571  2571 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
06-30 12:53:23.477  2571  2571 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 12:53:23.477  2571  2571 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,06-30 12:53:43.701  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:53:43.714  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:53:43.719  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:53:43.778  1513  2071 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 12:53:43.778  1513  2071 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
06-30 12:53:43.778  1513  2071 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 12:53:43.779  1513  2071 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 12:53:43.825  2571  2571 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,06-30 12:53:43.826  2571  2571 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
06-30 12:53:43.826  2571  2571 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,06-30 12:53:51.858  1663  1711 I Keyboard.Facilitator.LanguageModelFlusher: run()
06-30 12:53:51.859  1663  1711 I Keyboard.Facilitator: flushDynamicLanguageModels()
,06-30 12:53:51.907  1513  1513 I ConfigService: onCreate
,06-30 12:53:57.000  1513  1513 I ConfigService: onDestroy
,06-30 12:54:04.035  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:54:04.044  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:54:04.050  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:54:04.077  1513  2070 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,06-30 12:54:04.077  1513  2070 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,06-30 12:54:04.077  1513  2070 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 12:54:04.077  1513  2070 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 12:54:04.106  2571  2571 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
06-30 12:54:04.106  2571  2571 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,06-30 12:54:04.106  2571  2571 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,06-30 12:55:52.751  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:55:52.763  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:55:52.764  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 12:55:52.812  1513  2071 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
06-30 12:55:52.812  1513  2071 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 12:55:52.813  1513  2071 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 12:55:52.813  1513  2071 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 12:55:52.846  1513  2071 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 12:55:52.846  1513  2071 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 12:55:52.846  1513  2071 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 12:55:52.846  1513  2071 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 12:55:52.846  1513  2071 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 12:55:52.846  1513  2071 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 12:55:52.846  1513  2071 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 12:55:52.851  2571  2604 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 12:55:52.851  2571  2604 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 12:55:52.851  2571  2604 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 12:55:52.851  2571  2604 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 12:55:52.851  2571  2604 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 12:55:52.851  2571  2604 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 12:55:52.851  2571  2604 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:00:52.997  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:00:53.014  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:00:53.018  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:00:53.098  1513  2674 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
06-30 13:00:53.098  1513  2674 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 13:00:53.099  1513  2674 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 13:00:53.099  1513  2674 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 13:00:53.145  1513  2674 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.,
06-30 13:00:53.145  1513  2674 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 13:00:53.145  1513  2674 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 13:00:53.145  1513  2674 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 13:00:53.145  1513  2674 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 13:00:53.145  1513  2674 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 13:00:53.145  1513  2674 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:00:53.161  2571  2604 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 13:00:53.161  2571  2604 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 13:00:53.161  2571  2604 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 13:00:53.161  2571  2604 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
,06-30 13:00:53.161  2571  2604 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 13:00:53.161  2571  2604 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 13:00:53.161  2571  2604 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:05:11.264  1513  3454 I VacuumService: Vacuum at: now=1467284711264 tag=VacuumService
,06-30 13:05:11.360   875  1384 I ProcessStatsService: Added stats: 2016-06-30-11-03-31, over +1h30m27s461ms
,06-30 13:05:11.365   875  1384 I ProcessStatsService: Added stats: 2016-06-30-07-18-42, over +2h0m0s284ms
,06-30 13:05:11.375   875  1384 I ProcessStatsService: Added stats: 2016-06-30-04-18-42, over +3h0m0s435ms
,06-30 13:05:11.391   875  1384 I ProcessStatsService: Added stats: 2016-06-30-01-18-41, over +3h0m0s349ms,
,06-30 13:05:11.398   875  1384 I ProcessStatsService: Added stats: 2016-06-29-22-18-41, over +3h0m0s413ms,
,06-30 13:05:11.404   875  1384 I ProcessStatsService: Added stats: 2016-06-29-19-18-41, over +3h0m0s346ms,
,06-30 13:05:11.410   875  1384 I ProcessStatsService: Added stats: 2016-06-29-16-18-40, over +3h0m0s370ms
,06-30 13:05:11.415   875  1384 I ProcessStatsService: Added stats: 2016-06-29-13-18-40, over +3h0m0s457ms
,06-30 13:05:11.425   875  1384 I ProcessStatsService: Added stats: 2016-06-29-10-18-18, over +3h0m21s159ms
,06-30 13:05:53.300  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:05:53.311  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:05:53.317  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:05:53.376  1513  2071 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
06-30 13:05:53.376  1513  2071 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 13:05:53.376  1513  2071 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 13:05:53.376  1513  2071 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 13:05:53.400  1513  2071 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 13:05:53.400  1513  2071 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 13:05:53.400  1513  2071 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 13:05:53.400  1513  2071 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 13:05:53.400  1513  2071 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 13:05:53.400  1513  2071 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 13:05:53.400  1513  2071 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:05:53.407  2571  2604 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 13:05:53.407  2571  2604 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 13:05:53.407  2571  2604 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 13:05:53.407  2571  2604 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 13:05:53.407  2571  2604 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 13:05:53.407  2571  2604 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 13:05:53.407  2571  2604 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:10:40.549   875   887 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 13:10:53.469  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:10:53.491  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:10:53.499  1513  1513 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,06-30 13:10:53.541  1513  1525 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
06-30 13:10:53.541  1513  1525 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
06-30 13:10:53.541  1513  1525 I GLSUser : [GLSUser] Extracting token using key: Auth
06-30 13:10:53.542  1513  1525 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,06-30 13:10:53.586  1513  1525 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
06-30 13:10:53.586  1513  1525 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
06-30 13:10:53.586  1513  1525 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
06-30 13:10:53.586  1513  1525 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
06-30 13:10:53.586  1513  1525 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
06-30 13:10:53.586  1513  1525 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
06-30 13:10:53.586  1513  1525 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,06-30 13:10:53.597  2571  2604 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
06-30 13:10:53.597  2571  2604 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
06-30 13:10:53.597  2571  2604 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
06-30 13:10:53.597  2571  2604 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
06-30 13:10:53.597  2571  2604 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
06-30 13:10:53.597  2571  2604 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
06-30 13:10:53.597  2571  2604 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms)
```
