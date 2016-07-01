#### Test 757892686fd65a6_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
,07-01 08:58:46.070  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-01 08:58:46.076  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-01 08:58:46.104  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-01 08:58:46.223  3243  3282 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
07-01 08:58:46.266  3243  3282 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
07-01 08:58:46.294  3243  3282 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-01 08:58:46.373  1928  2165 I Icing   : Indexing 0A4562BF807829C124E952811A67787B55D6217E from com.google.android.googlequicksearchbox
07-01 08:58:46.420  1928  2165 D Icing   : Loaded CLD2 Version V2.0 - 20141016
07-01 08:58:46.516  1928  2165 I Icing   : Indexing done 0A4562BF807829C124E952811A67787B55D6217E
07-01 08:58:46.823  3291  3291 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-01 08:58:46.828  3291  3291 D AndroidRuntime: CheckJNI is OFF
07-01 08:58:46.864  3291  3291 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-01 08:58:46.908  3291  3291 I Radio-JNI: register_android_hardware_Radio DONE
07-01 08:58:46.929  3291  3291 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-01 08:58:46.934   877   887 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-01 08:58:46.973  1814  1827 W SearchService: Abort, client detached.
07-01 08:58:46.982  3291  3291 D AndroidRuntime: Shutting down VM
07-01 08:58:47.000   877  1756 I ActivityManager: Start proc 3301:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-01 08:58:47.010  1814  2153 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@349ca1a
07-01 08:58:47.010  1814  1814 I HotwordDetector: Closing mic
07-01 08:58:47.010  1814  2159 E AudioRecord-JNI: Error -4 during AudioRecord native read
07-01 08:58:47.019  1814  1814 W ErrorReporter: reportError [type: 29, code: 917507]: null
07-01 08:58:47.074   375  2161 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
07-01 08:58:47.076   375  2161 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
07-01 08:58:47.085   375  1290 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
07-01 08:58:47.087  1814  2158 I MicroRecognitionRnrImpl: Detection finished
07-01 08:58:47.089  1814  2157 I MicroRecognitionRnrImpl: Stopping hotword detection.
07-01 08:58:47.134  3301  3301 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-01 08:58:47.167  3301  3301 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-01 08:58:47.247  3301  3301 I LibraryLoader: Time to load native libraries: 74 ms (timestamps 5339-5413)
07-01 08:58:47.247  3301  3301 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 08:58:47.278  3301  3301 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8e834f8}
07-01 08:58:47.278  3301  3301 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 08:58:47.279  3301  3301 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-01 08:58:47.285  3301  3301 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-01 08:58:47.286  3301  3301 E SysUtils: ApplicationContext is null in ApplicationStatus
07-01 08:58:47.365  3301  3316 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
07-01 08:58:47.376  3301  3301 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-01 08:58:47.386  3301  3301 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-01 08:58:47.386  3301  3301 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-01 08:58:47.386  3301  3301 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-01 08:58:47.386  3301  3301 I Adreno  : Build Date                       : 10/20/15
07-01 08:58:47.386  3301  3301 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-01 08:58:47.386  3301  3301 I Adreno  : Local Branch                     : M14
07-01 08:58:47.386  3301  3301 I Adreno  : Remote Branch                    : 
07-01 08:58:47.386  3301  3301 I Adreno  : Remote Branch                    : 
07-01 08:58:47.386  3301  3301 I Adreno  : Reconstruct Branch               : 
07-01 08:58:47.458   877   894 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@9a011a0:true
07-01 08:58:47.566  3301  3301 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-01 08:58:47.583  3301  3301 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
07-01 08:58:47.637  3301  3338 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
07-01 08:58:47.650  3301  3325 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
07-01 08:58:47.688  3301  3338 I OpenGLRenderer: Initialized EGL, version 1.4
07-01 08:58:47.794   877   895 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +811ms
07-01 08:58:47.803  1648  1648 I Keyboard.Facilitator: onFinishInput()
07-01 08:58:47.852   877  1754 I ActivityManager: Killing 2322:com.google.android.apps.fitness/u0a51 (adj 15): empty #17
07-01 08:58:47.894   877  1754 I ActivityManager: Killing 2986:com.qualcomm.telephony/1001 (adj 15): empty #18
07-01 08:58:47.907  3301  3301 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3301
07-01 08:58:48.048  3301  3301 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-01 08:58:48.282  3301  3340 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1696138960
07-01 08:58:48.292  3301  3340 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-01 08:58:48.292  3301  3340 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-01 08:58:48.292  3301  3340 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-01 08:58:48.292  3301  3340 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-01 08:58:48.292  3301  3340 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-01 08:58:48.292  3301  3340 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e6bb0fc added. We now have 1 listener(s)
07-01 08:58:48.309  3301  3340 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
07-01 08:58:48.313  3301  3340 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-01 08:58:48.314  3301  3340 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-01 08:58:48.314  3301  3340 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-01 08:58:48.318  3301  3340 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-01 08:58:48.318  3301  3340 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-01 08:58:48.318  3301  3340 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-01 08:58:48.318  3301  3340 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
07-01 08:58:48.318  3301  3340 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-01 08:58:48.318  3301  3340 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-01 08:58:48.318  3301  3340 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-01 08:58:48.318  3301  3340 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-01 08:58:48.318  3301  3340 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-01 08:58:48.318  3301  3340 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-01 08:58:48.318  3301  3340 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-01 08:58:48.318  3301  3340 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a2d5a0b added. We now have 1 listener(s)
07-01 08:58:48.318  3301  3340 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 08:58:48.325   877  1321 D WifiService: New client listening to asynchronous messages
07-01 08:58:48.326  3301  3340 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-01 08:58:48.326  3301  3340 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-01 08:58:48.328  3301  3340 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-01 08:58:48.328  3301  3340 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-01 08:58:48.329  3301  3340 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-01 08:58:48.330  3301  3340 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-01 08:58:48.334  3301  3340 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-01 08:58:48.334  3301  3340 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
07-01 08:58:48.336  3301  3340 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-01 08:58:48.336  3301  3340 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 08:58:48.336  3301  3340 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 08:58:48.336  3301  3340 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-01 08:58:48.336  3301  3340 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 08:58:48.336  3301  3340 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 08:58:48.336  3301  3340 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 08:58:48.336  3301  3340 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 08:58:48.336  3301  3340 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 08:58:48.336  3301  3340 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-01 08:58:48.336  3301  3340 D io.jxcore.node.ConnectivityMonitor: start: OK
07-01 08:58:48.337  3301  3340 I io.jxcore.node.LifeCycleMonitor: start: OK
07-01 08:58:48.509  3301  3301 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-01 08:58:48.517  3301  3301 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
07-01 08:58:49.260  3301  3348 W jxcore-log: Initializing JXcore engine
07-01 08:58:49.260  3301  3348 W jxcore-log: JXcore engine is ready
07-01 08:58:49.330  3348  3348 W Thread-285: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8943 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
07-01 08:58:49.330  3348  3348 W Thread-285: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9548]" dev="sockfs" ino=9548 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
07-01 08:58:49.330  3348  3348 W Thread-285: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
07-01 08:58:49.330  3348  3348 W Thread-285: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[22999]" dev="sockfs" ino=22999 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
07-01 08:58:49.346  3301  3348 W jxcore-log: Starting JXcore engine
07-01 08:58:49.438  3301  3348 W jxcore-log: Platform android
07-01 08:58:49.438  3301  3348 W jxcore-log: 
07-01 08:58:49.438  3301  3348 W jxcore-log: Process ARCH arm
07-01 08:58:49.438  3301  3348 W jxcore-log: 
07-01 08:58:49.638  3301  3348 I jxcore-log: JXcore Cordova bridge is ready!
07-01 08:58:49.638  3301  3348 I jxcore-log: 
07-01 08:58:49.638  3301  3348 W jxcore-log: JXcore engine is started
07-01 08:58:49.650  3301  3340 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-01 08:58:49.653   877  1747 I ActivityManager: START u0 {act=android.content.pm.action.REQUEST_PERMISSIONS pkg=com.android.packageinstaller cmp=com.android.packageinstaller/.permission.ui.GrantPermissionsActivity (has extras)} from uid 10000 on display 0
07-01 08:58:49.667  3301  3301 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-01 08:58:49.668  3301  3301 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
07-01 08:58:49.676  3301  3340 W PluginManager: THREAD WARNING: exec() call to ThaliPermissions.REQUEST_ACCESS_COARSE_LOCATION blocked the main thread for 26ms. Plugin should use CordovaInterface.getThreadPool().
07-01 08:58:49.697   877  1754 I ActivityManager: Start proc 3350:com.android.packageinstaller/u0a69 for activity com.android.packageinstaller/.permission.ui.GrantPermissionsActivity
,07-01 08:58:49.778  3350  3350 W System  : ClassLoader referenced unknown path: /system/priv-app/GooglePackageInstaller/lib/arm
,07-01 08:58:49.870  3350  3362 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-01 08:58:49.928  3350  3362 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-01 08:58:49.928  3350  3362 I Adreno  : Build Date                       : 10/20/15
07-01 08:58:49.928  3350  3362 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-01 08:58:49.928  3350  3362 I Adreno  : Local Branch                     : M14
07-01 08:58:49.928  3350  3362 I Adreno  : Remote Branch                    : 
07-01 08:58:49.928  3350  3362 I Adreno  : Remote Branch                    : 
07-01 08:58:49.928  3350  3362 I Adreno  : Reconstruct Branch               : 
,07-01 08:58:49.933  3350  3362 I OpenGLRenderer: Initialized EGL, version 1.4
,07-01 08:58:49.955  1648  1648 I Keyboard.Facilitator: onFinishInput()
,07-01 08:58:50.010   877   895 I ActivityManager: Displayed com.android.packageinstaller/.permission.ui.GrantPermissionsActivity: +334ms
,07-01 08:58:50.177  3301  3301 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bb1e00e Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@9a1d145, 16908290=android.view.AbsSavedState$1@9a1d145}, android:focusedViewId=100}]}]
,07-01 08:58:50.178  3301  3301 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,07-01 08:58:50.297  1529  1529 I ConfigService: onDestroy
,07-01 08:58:59.537   877   890 I ActivityManager: Waited long enough for: ServiceRecord{cd4caac u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,07-01 08:59:05.131  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 08:59:05.143  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 08:59:05.148  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 08:59:05.193  1529  1540 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-01 08:59:05.194  1529  1540 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,07-01 08:59:05.195  1529  1540 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-01 08:59:05.196  1529  1540 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 08:59:05.243  2587  2587 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-01 08:59:05.244  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-01 08:59:05.245  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,07-01 08:59:22.070   877   897 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-01 08:59:22.079  1648  1648 I Keyboard.Facilitator: onFinishInput()
,07-01 08:59:22.084   877   897 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-01 08:59:22.084   877   897 I Adreno  : Build Date                       : 10/20/15
07-01 08:59:22.084   877   897 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-01 08:59:22.084   877   897 I Adreno  : Local Branch                     : M14
07-01 08:59:22.084   877   897 I Adreno  : Remote Branch                    : 
07-01 08:59:22.084   877   897 I Adreno  : Remote Branch                    : 
07-01 08:59:22.084   877   897 I Adreno  : Reconstruct Branch               : 
,07-01 08:59:22.118   281   307 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (172 us)
,07-01 08:59:22.723   877   897 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-01 08:59:22.728   877   897 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,07-01 08:59:22.729  3301  3301 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-01 08:59:22.730  3301  3301 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-01 08:59:22.735   877   895 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,07-01 08:59:22.735   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
07-01 08:59:22.735   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,07-01 08:59:22.966   281   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,07-01 08:59:22.969   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,07-01 08:59:22.969   877  1344 D SurfaceControl: Excessive delay in setPowerMode(): 235ms
,07-01 08:59:22.975   877   897 I DreamManagerService: Entering dreamland.
,07-01 08:59:22.976   877   897 I PowerManagerService: Dozing...
07-01 08:59:22.976   877   892 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,07-01 08:59:23.041   375  1291 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-01 08:59:23.041   375  1291 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,07-01 08:59:23.056   877  1320 D WifiConfigStore: Retrieve network priorities after PNO.
,07-01 08:59:23.060   877  1320 E native  : do suspend false
,07-01 08:59:23.118  1711  3382 D NfcService: Discovery configuration equal, not updating.
,07-01 08:59:23.172   877  1320 D WifiConfigStore: Retrieve network priorities after PNO.
,07-01 08:59:23.181   375  1328 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-01 08:59:23.181   375  1328 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
07-01 08:59:23.185   877  1320 E native  : do suspend true
,07-01 08:59:27.264  1834  2321 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-01 08:59:27.493  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 08:59:27.508  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 08:59:27.514  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 08:59:27.558  1529  2670 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-01 08:59:27.558  1529  2670 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,07-01 08:59:27.558  1529  2670 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 08:59:27.559  1529  2670 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 08:59:27.595  2587  2587 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-01 08:59:27.595  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-01 08:59:27.596  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,07-01 08:59:53.526  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 08:59:53.539  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 08:59:53.544  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 08:59:53.605  1529  1884 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-01 08:59:53.605  1529  1884 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-01 08:59:53.605  1529  1884 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 08:59:53.605  1529  1884 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 08:59:53.653  2587  2587 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-01 08:59:53.654  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-01 08:59:53.655  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,07-01 09:00:22.120  1648  1766 I Keyboard.Facilitator.LanguageModelFlusher: run()
,07-01 09:00:22.121  1648  1766 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-01 09:00:22.165  1529  1529 I ConfigService: onCreate
,07-01 09:00:27.229  1529  1529 I ConfigService: onDestroy
,07-01 09:00:27.361  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:00:27.369  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:00:27.374  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:00:27.412  1529  1541 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-01 09:00:27.412  1529  1541 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-01 09:00:27.412  1529  1541 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 09:00:27.412  1529  1541 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:00:27.432  2587  2587 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-01 09:00:27.432  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-01 09:00:27.432  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,07-01 09:00:47.807  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:00:47.822  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:00:47.825  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:00:47.878  1529  1541 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-01 09:00:47.878  1529  1541 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-01 09:00:47.878  1529  1541 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 09:00:47.878  1529  1541 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:00:47.929  2587  2587 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-01 09:00:47.931  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
07-01 09:00:47.932  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-01 09:02:23.069  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:02:23.082  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:02:23.084  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:02:23.145  1529  2634 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
07-01 09:02:23.145  1529  2634 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,07-01 09:02:23.146  1529  2634 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 09:02:23.146  1529  2634 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:02:23.184  1529  2634 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-01 09:02:23.184  1529  2634 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-01 09:02:23.184  1529  2634 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-01 09:02:23.184  1529  2634 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-01 09:02:23.184  1529  2634 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-01 09:02:23.184  1529  2634 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-01 09:02:23.184  1529  2634 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-01 09:02:23.193  2587  2616 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-01 09:02:23.193  2587  2616 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-01 09:02:23.193  2587  2616 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-01 09:02:23.193  2587  2616 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-01 09:02:23.193  2587  2616 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-01 09:02:23.193  2587  2616 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-01 09:02:23.193  2587  2616 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-01 09:07:23.287  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:07:23.308  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:07:23.316  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:07:23.401  1529  1884 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-01 09:07:23.402  1529  1884 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-01 09:07:23.402  1529  1884 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 09:07:23.403  1529  1884 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:07:23.451  1529  1884 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-01 09:07:23.451  1529  1884 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-01 09:07:23.451  1529  1884 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-01 09:07:23.451  1529  1884 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-01 09:07:23.451  1529  1884 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-01 09:07:23.451  1529  1884 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-01 09:07:23.451  1529  1884 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-01 09:07:23.466  2587  2616 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-01 09:07:23.466  2587  2616 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-01 09:07:23.466  2587  2616 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-01 09:07:23.466  2587  2616 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-01 09:07:23.466  2587  2616 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-01 09:07:23.466  2587  2616 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-01 09:07:23.466  2587  2616 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-01 09:08:25.926  2587  2587 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,07-01 09:08:25.955  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:08:25.971  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:08:25.975  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:08:25.995  1928  3425 I EventLogService: Opted in for usage reporting
,07-01 09:08:25.996  1928  3425 I EventLogService: Aggregate from 1467355105792 (log), 1467355105792 (data)
,07-01 09:08:26.042  1529  2634 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
07-01 09:08:26.043  1529  2634 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-01 09:08:26.043  1529  2634 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 09:08:26.043  1529  2634 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:08:26.080  2587  2587 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-01 09:08:26.086  1928  3425 W EventLogAggregator: Unknown tag: snet_gcore
,07-01 09:08:26.087  1928  3425 W EventLogAggregator: Unknown tag: snet_launch_service
,07-01 09:08:26.104  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:08:26.167  1529  2634 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-01 09:08:26.167  1529  2634 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,07-01 09:08:26.168  1529  2634 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 09:08:26.168  1529  2634 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:08:26.215  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:08:26.228  1928  3425 I ServiceDumpSys: dumping service [account]
,07-01 09:08:26.254  1529  2670 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-01 09:08:26.254  1529  2670 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-01 09:08:26.254  1529  2670 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 09:08:26.254  1529  2670 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:08:26.281  2587  2587 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-01 09:08:26.499  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:08:26.551  1529  1540 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-01 09:08:26.551  1529  1540 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-01 09:08:26.552  1529  1540 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 09:08:26.552  1529  1540 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:08:26.585  2587  2587 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,07-01 09:08:26.586  2587  2587 D Finsky  : [1] WearSupportService.startHygiene: disabled
,07-01 09:08:26.589  2587  2587 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,07-01 09:08:26.595  2587  3155 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,07-01 09:08:26.596  2587  2587 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 30 minutes (failures=2)
,07-01 09:08:41.596  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:08:41.616  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:08:41.621  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:08:41.688  1529  1540 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-01 09:08:41.688  1529  1540 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-01 09:08:41.688  1529  1540 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 09:08:41.688  1529  1540 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:08:41.753  2587  2587 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-01 09:08:41.755  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-01 09:08:41.759  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,07-01 09:09:02.068  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:09:02.085  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:09:02.089  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:09:02.173  1529  1884 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-01 09:09:02.173  1529  1884 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-01 09:09:02.174  1529  1884 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 09:09:02.174  1529  1884 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:09:02.241  2587  2587 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-01 09:09:02.243  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-01 09:09:02.245  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,07-01 09:09:22.550  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:09:22.566  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:09:22.573  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:09:22.665  1529  1884 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-01 09:09:22.666  1529  1884 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
07-01 09:09:22.667  1529  1884 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 09:09:22.667  1529  1884 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:09:22.738  2587  2587 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-01 09:09:22.739  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-01 09:09:22.743  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,07-01 09:09:43.005  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:09:43.015  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:09:43.017  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:09:43.046  1529  1541 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-01 09:09:43.046  1529  1541 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,07-01 09:09:43.046  1529  1541 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-01 09:09:43.046  1529  1541 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:09:43.094  2587  2587 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
07-01 09:09:43.095  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-01 09:09:43.096  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,07-01 09:10:03.506  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:10:03.520  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:10:03.525  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:10:03.595  1529  1540 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
07-01 09:10:03.595  1529  1540 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,07-01 09:10:03.596  1529  1540 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 09:10:03.596  1529  1540 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:10:03.658  2587  2587 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-01 09:10:03.659  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-01 09:10:03.661  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,07-01 09:10:24.089  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:10:24.114  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:10:24.122  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:10:24.221  1529  1884 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,07-01 09:10:24.221  1529  1884 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,07-01 09:10:24.222  1529  1884 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-01 09:10:24.222  1529  1884 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:10:24.290  2587  2587 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,07-01 09:10:24.292  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,07-01 09:10:24.297  2587  2587 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,07-01 09:11:43.117  1529  1987 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-01 09:12:23.622  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:12:23.644  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:12:23.651  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:12:23.737  1529  1540 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
07-01 09:12:23.738  1529  1540 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-01 09:12:23.738  1529  1540 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 09:12:23.739  1529  1540 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:12:23.792  1529  1540 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-01 09:12:23.792  1529  1540 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-01 09:12:23.792  1529  1540 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-01 09:12:23.792  1529  1540 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-01 09:12:23.792  1529  1540 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-01 09:12:23.792  1529  1540 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-01 09:12:23.792  1529  1540 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-01 09:12:23.808  2587  2616 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-01 09:12:23.808  2587  2616 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-01 09:12:23.808  2587  2616 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-01 09:12:23.808  2587  2616 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-01 09:12:23.808  2587  2616 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-01 09:12:23.808  2587  2616 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-01 09:12:23.808  2587  2616 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-01 09:17:09.716   877   889 I UsageStatsService: User[0] Flushing usage stats to disk
,07-01 09:17:23.955  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:17:23.972  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:17:23.976  1529  1529 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-01 09:17:24.062  1529  1540 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-01 09:17:24.062  1529  1540 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-01 09:17:24.063  1529  1540 I GLSUser : [GLSUser] Extracting token using key: Auth
07-01 09:17:24.064  1529  1540 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-01 09:17:24.118  1529  1540 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-01 09:17:24.118  1529  1540 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-01 09:17:24.118  1529  1540 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-01 09:17:24.118  1529  1540 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-01 09:17:24.118  1529  1540 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-01 09:17:24.118  1529  1540 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-01 09:17:24.118  1529  1540 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-01 09:17:24.131  2587  2616 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-01 09:17:24.131  2587  2616 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-01 09:17:24.131  2587  2616 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-01 09:17:24.131  2587  2616 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-01 09:17:24.131  2587  2616 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-01 09:17:24.131  2587  2616 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-01 09:17:24.131  2587  2616 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,TIME-OUT KILL (timeout was 1400000ms)
```
