#### Test 80761374059c81f_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-16 17:13:57.714   873  1302 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,--------- beginning of system
08-16 17:13:58.406   873   883 I ActivityManager: Start proc 3773:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
08-16 17:13:58.442  3773  3773 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
08-16 17:13:58.459  3771  3771 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-16 17:13:58.463  3771  3771 D AndroidRuntime: CheckJNI is OFF
08-16 17:13:58.478  3773  3773 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
08-16 17:13:58.491  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 17:13:58.492  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 17:13:58.498  3771  3771 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-16 17:13:58.511  3773  3796 V GoogleAuthProtoRequest: [317] a.<init>: mAccountName set to: thalitester@gmail.com
08-16 17:13:58.530  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 17:13:58.533  3771  3771 I Radio-JNI: register_android_hardware_Radio DONE
08-16 17:13:58.537  1493  3072 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-16 17:13:58.537  1493  3072 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-16 17:13:58.537  1493  3072 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:13:58.537  1493  3072 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-16 17:13:58.545  1493  1987 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-16 17:13:58.545  1493  1987 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 17:13:58.545  1493  1987 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:13:58.545  1493  1987 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-16 17:13:58.551  3771  3771 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-16 17:13:58.553   873   883 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 17:13:58.557  3773  3796 W ExperimentUpdateService: [317] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
08-16 17:13:58.557  3773  3796 W ExperimentUpdateService: [317] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 17:13:58.557  3773  3796 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 17:13:58.557  3773  3796 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-16 17:13:58.557  3773  3796 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-16 17:13:58.557  3773  3796 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-16 17:13:58.557  3773  3796 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-16 17:13:58.557  3773  3796 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-16 17:13:58.557  3773  3796 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-16 17:13:58.557  3773  3796 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-16 17:13:58.557  3773  3796 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-16 17:13:58.557  3773  3796 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
08-16 17:13:58.567  2004  2016 W SearchService: Abort, client detached.
08-16 17:13:58.567  3771  3771 D AndroidRuntime: Shutting down VM
08-16 17:13:58.570  2004  2004 I HotwordDetector: Closing mic
08-16 17:13:58.572  2004  2307 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@c9bc9c0
08-16 17:13:58.572  2004  2318 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-16 17:13:58.582   873  1685 I ActivityManager: Start proc 3804:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-16 17:13:58.605  3524  3524 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-16 17:13:58.605  3524  3524 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 17:13:58.605  3524  3524 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
08-16 17:13:58.634   873   884 I ActivityManager: Killing 3135:com.google.android.apps.maps/u0a65 (adj 15): empty #17
08-16 17:13:58.634   374  2321 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-16 17:13:58.635   374  2321 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-16 17:13:58.638   374  1276 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-16 17:13:58.640  2004  2317 I MicroRecognitionRnrImpl: Detection finished
08-16 17:13:58.640  2004  2313 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-16 17:13:58.688  3804  3804 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-16 17:13:58.707  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-16 17:13:58.708  3804  3804 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-16 17:13:58.711  1493  3819 I VacuumService: Vacuum at: now=1471360438711 tag=VacuumService
08-16 17:13:58.714  3804  3804 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4088-4090)
08-16 17:13:58.715  3804  3804 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 17:13:58.730  3804  3804 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1b21c06}
08-16 17:13:58.731  3804  3804 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 17:13:58.731  3804  3804 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 17:13:58.738  3804  3804 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-16 17:13:58.740  3804  3804 E SysUtils: ApplicationContext is null in ApplicationStatus
08-16 17:13:58.753  3804  3804 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-16 17:13:58.763  3804  3804 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 17:13:58.763  3804  3804 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 17:13:58.763  3804  3804 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 17:13:58.763  3804  3804 I Adreno  : Build Date                       : 10/20/15
08-16 17:13:58.763  3804  3804 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 17:13:58.763  3804  3804 I Adreno  : Local Branch                     : M14
08-16 17:13:58.763  3804  3804 I Adreno  : Remote Branch                    : 
08-16 17:13:58.763  3804  3804 I Adreno  : Remote Branch                    : 
08-16 17:13:58.763  3804  3804 I Adreno  : Reconstruct Branch               : 
,08-16 17:13:58.800   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b1b63e1:true
,08-16 17:13:58.834  3804  3804 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-16 17:13:58.846  3804  3804 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-16 17:13:58.863  1493  3841 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-16 17:13:58.864  1493  3841 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-16 17:13:58.881  3804  3851 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-16 17:13:58.888  3804  3832 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,08-16 17:13:58.919  3804  3851 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 17:13:58.965   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +396ms
,08-16 17:13:58.976  1861  1861 I Keyboard.Facilitator: onFinishInput()
,08-16 17:13:59.011  3804  3804 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3804
,08-16 17:13:59.111  3804  3804 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 17:13:59.169  1493  3841 W Uploader:  no longer exists, so no auth token.
,08-16 17:13:59.302  3804  3854 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1684014800
,08-16 17:13:59.309  3804  3854 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 17:13:59.309  3804  3854 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 17:13:59.309  3804  3854 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 17:13:59.309  3804  3854 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 17:13:59.309  3804  3854 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 17:13:59.309  3804  3854 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@46a7f95 added. We now have 1 listener(s)
08-16 17:13:59.313  3804  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-16 17:13:59.313  3804  3854 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 17:13:59.314  3804  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:13:59.314  3804  3854 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:13:59.317  3804  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 17:13:59.317  3804  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 17:13:59.317  3804  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 17:13:59.317  3804  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-16 17:13:59.317  3804  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 17:13:59.317  3804  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 17:13:59.317  3804  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 17:13:59.317  3804  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 17:13:59.317  3804  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 17:13:59.317  3804  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 17:13:59.317  3804  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 17:13:59.317  3804  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 17:13:59.317  3804  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 17:13:59.317  3804  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-16 17:13:59.317  3804  3854 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c2c838 added. We now have 1 listener(s)
08-16 17:13:59.317  3804  3854 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:13:59.319   873  1304 D WifiService: New client listening to asynchronous messages
08-16 17:13:59.320  3804  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:13:59.320  3804  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 17:13:59.320  3804  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 17:13:59.320  3804  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 17:13:59.320  3804  3854 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 17:13:59.323  3804  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:13:59.323  3804  3854 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-16 17:13:59.327  3804  3854 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-16 17:13:59.328  3804  3854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:13:59.328  3804  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:13:59.328  3804  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:13:59.328  3804  3854 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:13:59.328  3804  3854 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:13:59.328  3804  3854 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:13:59.328  3804  3854 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:13:59.328  3804  3854 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:13:59.328  3804  3854 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-16 17:13:59.328  3804  3854 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:13:59.329  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:13:59.330  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:13:59.332  3804  3854 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 17:13:59.399   873  3066 I ActivityManager: Killing 2974:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-16 17:13:59.431   873  3066 I ActivityManager: Killing 3223:com.google.android.gm/u0a78 (adj 15): empty #18
,08-16 17:13:59.475  3804  3804 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 17:14:00.028  1493  3841 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-16 17:14:00.029  1493  3841 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-16 17:14:00.029  1493  3841 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:14:00.029  1493  3841 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:14:00.048  1493  3841 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 17:14:00.048  1493  3841 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 17:14:00.048  1493  3841 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 17:14:00.048  1493  3841 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 17:14:00.048  1493  3841 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-16 17:14:00.048  1493  3841 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-16 17:14:00.048  1493  3841 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-16 17:14:00.048  1493  3841 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-16 17:14:00.048  1493  3841 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-16 17:14:00.048  1493  3841 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-16 17:14:00.048  1493  3841 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-16 17:14:00.048  1493  3841 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-16 17:14:00.048  1493  3841 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-16 17:14:00.202  3804  3862 W jxcore-log: Initializing JXcore engine
,08-16 17:14:00.202  3804  3862 W jxcore-log: JXcore engine is ready
,08-16 17:14:00.241  3862  3862 W Thread-333: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-16 17:14:00.241  3862  3862 W Thread-333: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10494]" dev="sockfs" ino=10494 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-16 17:14:00.241  3862  3862 W Thread-333: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-16 17:14:00.241  3862  3862 W Thread-333: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[22514]" dev="sockfs" ino=22514 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-16 17:14:00.257  3804  3862 W jxcore-log: Starting JXcore engine
,08-16 17:14:00.338  3804  3862 W jxcore-log: Platform android
08-16 17:14:00.338  3804  3862 W jxcore-log: 
,08-16 17:14:00.338  3804  3862 W jxcore-log: Process ARCH arm
08-16 17:14:00.338  3804  3862 W jxcore-log: 
,08-16 17:14:00.389  1493  3841 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-16 17:14:00.390  1493  3841 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-16 17:14:00.390  1493  3841 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:14:00.390  1493  3841 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:14:00.429  1493  3841 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 17:14:00.429  1493  3841 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 17:14:00.429  1493  3841 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 17:14:00.429  1493  3841 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 17:14:00.429  1493  3841 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-16 17:14:00.429  1493  3841 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-16 17:14:00.429  1493  3841 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-16 17:14:00.429  1493  3841 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-16 17:14:00.429  1493  3841 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-16 17:14:00.429  1493  3841 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-16 17:14:00.429  1493  3841 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-16 17:14:00.429  1493  3841 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-16 17:14:00.429  1493  3841 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-16 17:14:00.596  3804  3862 I jxcore-log: JXcore Cordova bridge is ready!
08-16 17:14:00.596  3804  3862 I jxcore-log: 
,08-16 17:14:00.597  3804  3862 W jxcore-log: JXcore engine is started
,08-16 17:14:00.606  3804  3854 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 17:14:00.610  3804  3804 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 17:14:02.509  3030  3869 V KeepSync: Connecting to GoogleApiClient
,08-16 17:14:02.509   873  1982 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 17:14:02.587  1493  3072 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-16 17:14:02.588  1493  3072 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-16 17:14:02.588  1493  3072 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 17:14:02.589  1493  3072 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:14:02.631  1691  3870 V BaseAuthAsyncOperation: access token request failed
,08-16 17:14:02.632  3030  3869 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 17:14:02.698  1493  1987 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-16 17:14:02.698  1493  1987 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 17:14:02.698  1493  1987 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:14:02.698  1493  1987 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:14:02.718  3030  3869 E KeepSync: IOException
08-16 17:14:02.718  3030  3869 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 17:14:02.718  3030  3869 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 17:14:02.718  3030  3869 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 17:14:02.718  3030  3869 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 17:14:02.718  3030  3869 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 17:14:02.718  3030  3869 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 17:14:02.718  3030  3869 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 17:14:02.718  3030  3869 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 17:14:02.718  3030  3869 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 17:14:02.718  3030  3869 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 17:14:02.718  3030  3869 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 17:14:02.718  3030  3869 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 17:14:02.718  3030  3869 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 17:14:02.718  3030  3869 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 17:14:02.718  3030  3869 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 17:14:02.718  3030  3869 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 17:14:02.718  3030  3869 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 17:14:02.718  3030  3869 E KeepSync: 	... 10 more
,08-16 17:14:02.718  3030  3869 W KeepSync: Sync result 2
,08-16 17:14:02.728   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 127776, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 17:14:16.540  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 17:14:16.540  3804  3862 I jxcore-log: 
,08-16 17:14:16.542  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 17:14:16.542  3804  3862 I jxcore-log: 
,08-16 17:14:16.553  3804  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:14:16.553  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:16.553  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:16.553  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:14:16.553  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:14:16.553  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:14:16.553  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:14:16.553  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:14:16.556  3804  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:14:16.559  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 17:14:16.559  3804  3862 I jxcore-log: 
,08-16 17:14:16.561  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 17:14:16.561  3804  3862 I jxcore-log: 
,08-16 17:14:16.902  3804  3862 I jxcore-log: Running unit tests
08-16 17:14:16.902  3804  3862 I jxcore-log: 
,08-16 17:14:16.903  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:14:16.903  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d995574 added. We now have 2 listener(s)
08-16 17:14:16.905  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 17:14:16.905  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:14:16.905  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:14:16.905  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:14:16.905  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e0aea9d added. We now have 2 listener(s)
,08-16 17:14:16.905  3804  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:14:16.906  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:14:16.911  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:14:16.917  3804  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:14:16.917  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:16.917  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:16.917  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:14:16.917  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:14:16.917  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:14:16.917  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:14:16.917  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:14:16.920  3804  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:14:16.920  3804  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:14:16.921  3804  3862 D ExecuteNativeTests: Running unit tests
,08-16 17:14:16.928  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:14:16.935  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:14:16.981  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:14:16.981  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 added. We now have 3 listener(s)
08-16 17:14:16.982  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 17:14:16.982  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:14:16.982  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:14:16.982  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:14:16.982  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 added. We now have 3 listener(s)
,08-16 17:14:16.982  3804  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:14:16.983  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:14:16.984  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:14:16.991  3804  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:14:16.991  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:16.991  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:16.991  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:14:16.991  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:14:16.991  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:14:16.991  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:14:16.991  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:14:16.992  3804  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:14:16.993  3804  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:14:16.995  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 17:14:16.996  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 17:14:16.996  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 17:14:16.996  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 17:14:16.998  3804  3862 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-16 17:14:16.998  3804  3862 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 17:14:16.998  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-16 17:14:16.998  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 17:14:16.998  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:14:16.998  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:14:16.999  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:14:16.999  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:14:16.999  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:14:17.000  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:14:17.004  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:17.004  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:14:17.004  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:14:17.004  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 removed from the list
08-16 17:14:17.004  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:17.004  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 removed from the list
08-16 17:14:17.000  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:14:17.005  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:14:17.005  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:17.005  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:17.005  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:17.006  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:14:17.006  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:14:17.006  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:17.006  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
,08-16 17:14:17.007  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:14:17.008  3804  3862 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 17:14:17.010  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:14:17.010  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:14:17.010  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:14:17.010  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:14:17.010  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:17.010  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:17.010  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list
08-16 17:14:17.010  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:17.010  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:17.010  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:14:17.011  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:17.011  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:17.011  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:14:17.011  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:17.015  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:14:17.015  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:14:17.015  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:17.015  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
,08-16 17:14:17.019  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 17:14:17.019  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 17:14:17.019  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-16 17:14:17.019  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 17:14:17.019  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 17:14:17.020  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 17:14:17.020  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 17:14:17.020  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 17:14:17.020  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 17:14:17.020  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 17:14:17.020  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 17:14:17.020  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 17:14:17.020  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-16 17:14:17.020  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 17:14:17.020  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 17:14:17.020  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 17:14:17.020  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 17:14:17.020  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 17:14:17.020  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 17:14:17.020  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 17:14:17.020  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 17:14:17.020  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 17:14:17.020  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 17:14:17.020  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 17:14:17.021  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 17:14:17.021  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 17:14:17.021  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 17:14:17.021  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 17:14:17.021  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-16 17:14:17.021  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 17:14:17.021  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 17:14:17.021  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:14:17.021  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:14:17.021  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:14:17.021  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:14:17.021  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:17.021  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:17.021  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list
08-16 17:14:17.021  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:17.021  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:17.021  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:14:17.021  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:17.021  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:17.022  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:17.022  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:17.023  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:14:17.023  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:14:17.023  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:17.023  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:17.023  3804  3862 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 17:14:17.024  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:14:17.028  3804  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:14:17.028  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:17.028  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:17.028  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:14:17.028  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:14:17.028  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:14:17.028  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:14:17.028  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:14:17.029  3804  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:14:17.029  3804  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:14:17.029  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:14:17.030  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:14:17.030  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:14:17.030  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:14:17.030  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 17:14:17.033  3804  3862 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 17:14:17.033  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 17:14:17.033  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:14:17.035  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:14:17.037  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 17:14:17.039  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 17:14:17.039  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 17:14:17.041  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-16 17:14:17.044  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-16 17:14:17.045  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 17:14:17.045  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:14:17.046  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 17:14:17.046  3804  3862 D BluetoothAdapter: STATE_ON
08-16 17:14:17.051  2690  2888 D BtGatt.GattService: registerClient() - UUID=7aef3329-4e10-4bbf-a4df-1138df5537ba
08-16 17:14:17.053  2690  2741 D BtGatt.GattService: onClientRegistered() - UUID=7aef3329-4e10-4bbf-a4df-1138df5537ba, clientIf=5
08-16 17:14:17.054  3804  3814 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 17:14:17.055  2690  2703 D BtGatt.GattService: start scan with filters
,08-16 17:14:17.058  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 17:14:17.058  2690  2746 D BtGatt.ScanManager: handling starting scan
08-16 17:14:17.058  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:14:17.058  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:14:17.058  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 17:14:17.059  2690  2746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@70a6860
08-16 17:14:17.060  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:14:17.060  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 17:14:17.060  3804  3804 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:14:17.061  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-16 17:14:17.063  3804  3862 I io.jxcore.node.ConnectionHelper: start: OK
08-16 17:14:17.072  2690  2741 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-16 17:14:17.072  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:14:17.073  2690  2746 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 17:14:17.082  2690  2741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 17:14:17.082  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:14:17.083  2690  2746 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:14:17.083  2690  2746 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 17:14:17.093  2690  2741 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 17:14:17.094  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:14:17.099  2690  2741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 17:14:17.099  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:14:17.562  3804  3804 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-16 17:14:17.563  3804  3804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:14:17.563  3804  3804 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 17:14:18.042   873  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-16 17:14:18.608  2690  2690 D BtGatt.ScanManager: awakened up at time 143984
,08-16 17:14:18.610  2690  2746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 17:14:18.666  2690  2741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
08-16 17:14:18.666  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:14:18.667  2690  2741 D BtGatt.GattService: current time is 144042982534
,08-16 17:14:18.668  2690  2741 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -84, 8, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 37, -47, 14, -113, 116, -46, 1, -128, -83, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -77, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -81, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -72, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 0]
08-16 17:14:18.671  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-16 17:14:18.673  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-16 17:14:18.674  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-16 17:14:18.675  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-16 17:14:18.675  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74]
,08-16 17:14:20.191  2690  2690 D BtGatt.ScanManager: awakened up at time 145566
08-16 17:14:20.192  2690  2746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 17:14:20.237  2690  2741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-16 17:14:20.237  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:14:20.237  2690  2741 D BtGatt.GattService: current time is 145613592378
08-16 17:14:20.237  2690  2741 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -88, 6, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 81, 34, 97, 112, -14, -5, 1, -128, -82, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -82, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-16 17:14:20.238  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-16 17:14:20.238  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-16 17:14:20.238  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 17:14:20.361  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:14:20.371  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:14:20.374  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:14:20.414  1493  3072 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-16 17:14:20.414  1493  3072 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-16 17:14:20.414  1493  3072 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:14:20.414  1493  3072 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:14:20.437  3524  3524 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-16 17:14:20.437  3524  3524 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-16 17:14:20.442  3524  3524 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-16 17:14:21.073   873  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-16 17:14:21.743  2690  2690 D BtGatt.ScanManager: awakened up at time 147118
08-16 17:14:21.745  2690  2746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 17:14:21.787  2690  2741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
08-16 17:14:21.787  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:14:21.788  2690  2741 D BtGatt.GattService: current time is 147164001920
08-16 17:14:21.788  2690  2741 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -91, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, 4, -88, 16, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -92, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -82, 19, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -81, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -81, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -93, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-16 17:14:21.788  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 17:14:21.789  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-16 17:14:21.789  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-16 17:14:21.789  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-16 17:14:21.790  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 17:14:21.790  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-16 17:14:21.790  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 17:14:22.073  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:14:22.074  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:14:22.074  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 17:14:22.074  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:22.075  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-16 17:14:22.075  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:14:22.075  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:14:22.076  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 17:14:22.076  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:14:22.078  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 17:14:22.078  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:14:22.081  3804  3862 D BluetoothAdapter: STATE_ON
,08-16 17:14:22.083  2690  2703 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:14:22.086  2690  2701 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 17:14:22.087  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:14:22.091  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:14:22.091  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 17:14:22.092  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 17:14:22.092  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:14:22.095  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:14:22.097  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:14:22.097  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 17:14:22.098  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:14:22.099  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 17:14:22.102  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:14:22.103  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:14:22.103  3804  3804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:14:22.103  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:14:22.103  3804  3804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:14:22.103  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list
08-16 17:14:22.103  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:22.104  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:22.104  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:14:22.104  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:22.104  3804  3804 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:14:22.106  2690  2741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 17:14:22.106  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:14:22.106  2690  2746 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:14:22.113  2690  2741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 17:14:22.113  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:14:22.113  2690  2746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 17:14:22.121  2690  2741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 17:14:22.122  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:14:22.606  3804  3804 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 17:14:24.939   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-16 17:14:24.951  1861  1861 I Keyboard.Facilitator: onFinishInput()
,08-16 17:14:24.959   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 17:14:24.959   873   893 I Adreno  : Build Date                       : 10/20/15
08-16 17:14:24.959   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 17:14:24.959   873   893 I Adreno  : Local Branch                     : M14
08-16 17:14:24.959   873   893 I Adreno  : Remote Branch                    : 
08-16 17:14:24.959   873   893 I Adreno  : Remote Branch                    : 
08-16 17:14:24.959   873   893 I Adreno  : Reconstruct Branch               : 
,08-16 17:14:24.993   281   395 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (186 us)
,08-16 17:14:25.616  3804  3804 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 17:14:25.616  3804  3804 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-16 17:14:25.652   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-16 17:14:25.656  3804  3804 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a1daa8c Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@451a21a, 16908290=android.view.AbsSavedState$1@451a21a}, android:focusedViewId=100}]}]
,08-16 17:14:25.656  3804  3804 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-16 17:14:25.657  3804  3804 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 17:14:25.658  3804  3804 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-16 17:14:25.661   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-16 17:14:25.665   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-16 17:14:25.667   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a64000
,08-16 17:14:25.667   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-16 17:14:25.903   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-16 17:14:25.906   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-16 17:14:25.907   873  1328 D SurfaceControl: Excessive delay in setPowerMode(): 242ms
,08-16 17:14:25.917   873   893 I DreamManagerService: Entering dreamland.
08-16 17:14:25.918   873   893 I PowerManagerService: Dozing...
08-16 17:14:25.920   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-16 17:14:25.986   374  1277 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-16 17:14:25.986   374  1277 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-16 17:14:26.005   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 17:14:26.012  1927  3884 D NfcService: Discovery configuration equal, not updating.
,08-16 17:14:26.026   873  1302 E native  : do suspend false
,08-16 17:14:26.046   873  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 17:14:26.060   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 17:14:26.063   873  1302 E native  : do suspend true
,08-16 17:14:26.122   374   374 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-16 17:14:26.123   374   374 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-16 17:14:26.513   873  1302 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-16 17:14:27.105  3804  3862 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 17:14:27.111  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:14:27.125  3804  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:14:27.125  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:27.125  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:27.125  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:14:27.125  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:14:27.125  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:14:27.125  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:14:27.125  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:14:27.132  3804  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:14:27.133  3804  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:14:27.135  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 17:14:27.136  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 17:14:27.137  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 17:14:27.137  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:14:27.137  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 17:14:27.141  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:14:27.150  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:14:27.153  3804  3862 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 17:14:27.154  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:14:27.167  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:14:27.169  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 17:14:27.170  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:14:27.181  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:14:27.181  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:14:27.182  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:14:27.184  3804  3862 D BluetoothAdapter: STATE_ON
,08-16 17:14:27.191  2690  2896 D BtGatt.GattService: registerClient() - UUID=d4d206e7-c6b7-4a5b-93c7-552b228de276
,08-16 17:14:27.193  2690  2741 D BtGatt.GattService: onClientRegistered() - UUID=d4d206e7-c6b7-4a5b-93c7-552b228de276, clientIf=5
,08-16 17:14:27.194  3804  3814 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 17:14:27.195  2690  2703 D BtGatt.GattService: start scan with filters
,08-16 17:14:27.204  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 17:14:27.204  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:14:27.204  2690  2746 D BtGatt.ScanManager: handling starting scan
08-16 17:14:27.205  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 17:14:27.205  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:14:27.219  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:14:27.220  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 17:14:27.220  3804  3804 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:14:27.222  2690  2741 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 17:14:27.223  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:14:27.223  2690  2746 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 17:14:27.226  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:14:27.231  3804  3862 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 17:14:27.234  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:14:27.235  3804  3862 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 17:14:27.235  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:14:27.235  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:14:27.235  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:14:27.235  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 17:14:27.235  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:14:27.235  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 17:14:27.236  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:14:27.236  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:14:27.237  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 17:14:27.237  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:14:27.239  3804  3862 D BluetoothAdapter: STATE_ON
,08-16 17:14:27.240  2690  2741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 17:14:27.241  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:14:27.241  2690  2746 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 17:14:27.241  2690  2703 D BtGatt.GattService: stopScan() - queue size =1
08-16 17:14:27.242  2690  2746 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 17:14:27.244  2690  2896 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 17:14:27.245  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 17:14:27.245  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 17:14:27.245  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:14:27.246  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:14:27.246  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:14:27.248  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:14:27.248  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 17:14:27.248  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 17:14:27.249  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:14:27.250  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 17:14:27.253  3804  3804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:14:27.253  3804  3804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:14:27.253  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:14:27.253  3804  3804 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:14:27.253  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:27.253  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:14:27.254  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list
,08-16 17:14:27.254  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:27.254  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
,08-16 17:14:27.254  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:14:27.255  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:14:27.256  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:14:27.256  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:14:27.258  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:14:27.259  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:14:27.259  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:14:27.259  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
,08-16 17:14:27.261  3804  3862 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 17:14:27.263  2690  2741 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 17:14:27.263  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:14:27.265  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:14:27.275  2690  2741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 17:14:27.275  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:14:27.277  3804  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:14:27.277  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:27.277  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:27.277  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:14:27.277  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:14:27.277  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:14:27.277  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:14:27.277  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:14:27.280  3804  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:14:27.280  3804  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:14:27.281  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:14:27.281  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 17:14:27.281  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 17:14:27.282  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:14:27.282  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:14:27.285  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:14:27.288  3804  3862 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 17:14:27.288  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:14:27.290  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:14:27.291  2690  2741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 17:14:27.292  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:14:27.292  2690  2746 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:14:27.295  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:14:27.296  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 17:14:27.296  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:14:27.302  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:14:27.302  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:14:27.302  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:14:27.304  3804  3862 D BluetoothAdapter: STATE_ON
,08-16 17:14:27.305  2690  2741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 17:14:27.305  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:14:27.306  2690  2746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 17:14:27.309  2690  2888 D BtGatt.GattService: registerClient() - UUID=340693e4-eecc-440c-bd40-56e89f982c4c
,08-16 17:14:27.310  2690  2741 D BtGatt.GattService: onClientRegistered() - UUID=340693e4-eecc-440c-bd40-56e89f982c4c, clientIf=5
,08-16 17:14:27.310  3804  3815 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 17:14:27.311  2690  2896 D BtGatt.GattService: start scan with filters
,08-16 17:14:27.315  2690  2741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 17:14:27.315  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:14:27.316  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 17:14:27.316  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:14:27.316  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 17:14:27.316  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:14:27.317  2690  2746 D BtGatt.ScanManager: handling starting scan
08-16 17:14:27.320  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:14:27.320  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 17:14:27.320  3804  3804 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 17:14:27.323  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:14:27.325  2690  2741 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 17:14:27.325  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:14:27.325  2690  2746 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 17:14:27.332  2690  2741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 17:14:27.332  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:14:27.332  3804  3862 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 17:14:27.332  2690  2746 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:14:27.333  2690  2746 D BtGatt.ScanManager: configuring batch scan storage, appIf 5,
,08-16 17:14:27.348  2690  2741 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 17:14:27.348  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:14:27.360  2690  2741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 17:14:27.361  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:14:27.822  3804  3804 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-16 17:14:27.822  3804  3804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 17:14:27.823  3804  3804 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 17:14:28.862  2690  2690 D BtGatt.ScanManager: awakened up at time 154238
,08-16 17:14:28.864  2690  2746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 17:14:28.882  2690  2741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-16 17:14:28.882  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:14:28.883  2690  2741 D BtGatt.GattService: current time is 154259125342
,08-16 17:14:28.884  2690  2741 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -81, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, 4, -82, 3, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 71, -122, -77, 84, 69, -12, 1, -128, -92, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -79, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -83, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 35, 97, 126, -92, 22, -56, 1, -128, -78, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 17:14:28.884  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 17:14:28.885  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-16 17:14:28.886  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 17:14:28.886  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 17:14:28.887  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-16 17:14:28.888  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 17:14:30.390  2690  2690 D BtGatt.ScanManager: awakened up at time 155766
,08-16 17:14:30.392  2690  2746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 17:14:30.436  2690  2741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-16 17:14:30.436  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:14:30.439  2690  2741 D BtGatt.GattService: current time is 155815388897
,08-16 17:14:30.440  2690  2741 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -81, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -92, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -91, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 85, -113, -37, 31, -33, 8, 0, 4, -91, 1, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 35, 97, 126, -92, 22, -56, 1, -128, -92, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 17:14:30.441  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 17:14:30.442  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-16 17:14:30.442  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-16 17:14:30.443  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
,08-16 17:14:30.444  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 17:14:31.134  1876  2627 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-16 17:14:31.949  2690  2690 D BtGatt.ScanManager: awakened up at time 157325
,08-16 17:14:31.952  2690  2746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 17:14:32.009  2690  2741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-16 17:14:32.011  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:14:32.011  2690  2741 D BtGatt.GattService: current time is 157387572440
08-16 17:14:32.015  2690  2741 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -91, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -91, 26, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 81, 34, 97, 112, -14, -5, 1, -128, -82, 24, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, 85, -113, -37, 31, -33, 8, 0, 4, -85, 21, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 37, -47, 14, -113, 116, -46, 1, -128, -82, 21, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -82, 20, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -92, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-16 17:14:32.016  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-16 17:14:32.017  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-16 17:14:32.018  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
08-16 17:14:32.018  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-16 17:14:32.019  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 17:14:32.019  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-16 17:14:32.019  2690  2741 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 17:14:32.077  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:14:32.083  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:14:32.110  3773  3889 V GoogleAuthProtoRequest: [318] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 17:14:32.172  1493  2081 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-16 17:14:32.172  1493  2081 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-16 17:14:32.173  1493  2081 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 17:14:32.173  1493  2081 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:14:32.234  3773  3889 W ExperimentUpdateService: [318] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-16 17:14:32.236  3773  3889 W ExperimentUpdateService: [318] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 17:14:32.236  3773  3889 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 17:14:32.236  3773  3889 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-16 17:14:32.236  3773  3889 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-16 17:14:32.236  3773  3889 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-16 17:14:32.236  3773  3889 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-16 17:14:32.236  3773  3889 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-16 17:14:32.236  3773  3889 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-16 17:14:32.236  3773  3889 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-16 17:14:32.236  3773  3889 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-16 17:14:32.236  3773  3889 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-16 17:14:32.333  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:14:32.333  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:14:32.333  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:14:32.333  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:14:32.333  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 17:14:32.334  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 17:14:32.334  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:14:32.334  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:14:32.334  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 17:14:32.335  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:14:32.335  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:14:32.336  3804  3862 D BluetoothAdapter: STATE_ON
08-16 17:14:32.337  2690  2703 D BtGatt.GattService: stopScan() - queue size =1
08-16 17:14:32.339  2690  2896 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 17:14:32.339  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 17:14:32.339  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 17:14:32.339  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:14:32.339  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:14:32.340  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:14:32.341  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:14:32.341  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 17:14:32.341  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:14:32.342  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:14:32.343  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:14:32.347  3804  3804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:14:32.347  3804  3804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:14:32.348  3804  3804 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:14:32.356  2690  2741 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 17:14:32.356  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:14:32.357  2690  2746 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:14:32.374  2690  2741 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 17:14:32.375  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:14:32.375  2690  2746 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 17:14:32.391  2690  2741 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 17:14:32.392  2690  2741 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:14:32.849  3804  3804 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-16 17:14:32.849  3804  3804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:14:32.849  3804  3804 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 17:14:33.112  1493  3072 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 17:14:33.113  1493  3072 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 17:14:33.113  1493  3072 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:14:33.113  1493  3072 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:14:33.155  2990  3891 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 17:14:33.155  2990  3891 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 17:14:33.155  2990  3891 E HttpOperation: 	at jdm.a(PG:82)
08-16 17:14:33.155  2990  3891 E HttpOperation: 	at jcs.o(PG:406)
08-16 17:14:33.155  2990  3891 E HttpOperation: 	at jcn.a(PG:1379)
08-16 17:14:33.155  2990  3891 E HttpOperation: 	at jcs.i(PG:143)
08-16 17:14:33.155  2990  3891 E HttpOperation: 	at blb.a(PG:3937)
08-16 17:14:33.155  2990  3891 E HttpOperation: 	at czp.a(PG:18188)
08-16 17:14:33.155  2990  3891 E HttpOperation: 	at czp.a(PG:9081)
08-16 17:14:33.155  2990  3891 E HttpOperation: 	at czq.run(PG:1686)
08-16 17:14:33.155  2990  3891 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 17:14:33.155  2990  3891 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 17:14:33.155  2990  3891 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 17:14:33.155  2990  3891 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 17:14:33.155  2990  3891 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 17:14:33.155  2990  3891 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 17:14:33.155  2990  3891 E HttpOperation: 	at jdj.a(PG:4091)
08-16 17:14:33.155  2990  3891 E HttpOperation: 	at jdj.a(PG:1125)
08-16 17:14:33.155  2990  3891 E HttpOperation: 	at jdm.a(PG:77)
08-16 17:14:33.155  2990  3891 E HttpOperation: 	... 12 more
08-16 17:14:33.155  2990  3891 E HttpOperation: Caused by: faj: BadAuthentication
08-16 17:14:33.155  2990  3891 E HttpOperation: 	at fal.a(PG:38)
08-16 17:14:33.155  2990  3891 E HttpOperation: 	at jdj.a(PG:4089)
08-16 17:14:33.155  2990  3891 E HttpOperation: 	... 14 more
,08-16 17:14:33.244  1493  2081 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 17:14:33.244  1493  2081 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-16 17:14:33.244  1493  2081 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 17:14:33.245  1493  2081 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:14:33.290  2990  3891 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 17:14:33.290  2990  3891 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 17:14:33.290  2990  3891 E HttpOperation: 	at jdm.a(PG:82)
08-16 17:14:33.290  2990  3891 E HttpOperation: 	at jcs.o(PG:406)
08-16 17:14:33.290  2990  3891 E HttpOperation: 	at jcn.a(PG:1379)
08-16 17:14:33.290  2990  3891 E HttpOperation: 	at jcs.i(PG:143)
08-16 17:14:33.290  2990  3891 E HttpOperation: 	at hec.a(PG:42)
08-16 17:14:33.290  2990  3891 E HttpOperation: 	at hee.a(PG:102)
08-16 17:14:33.290  2990  3891 E HttpOperation: 	at czr.a(PG:65)
08-16 17:14:33.290  2990  3891 E HttpOperation: 	at kka.a(PG:108)
08-16 17:14:33.290  2990  3891 E HttpOperation: 	at czp.a(PG:19176)
08-16 17:14:33.290  2990  3891 E HttpOperation: 	at czp.a(PG:9081)
08-16 17:14:33.290  2990  3891 E HttpOperation: 	at czq.run(PG:1686)
08-16 17:14:33.290  2990  3891 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 17:14:33.290  2990  3891 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 17:14:33.290  2990  3891 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 17:14:33.290  2990  3891 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 17:14:33.290  2990  3891 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 17:14:33.290  2990  3891 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 17:14:33.290  2990  3891 E HttpOperation: 	at jdj.a(PG:4091)
08-16 17:14:33.290  2990  3891 E HttpOperation: 	at jdj.a(PG:1125)
08-16 17:14:33.290  2990  3891 E HttpOperation: 	at jdm.a(PG:77)
08-16 17:14:33.290  2990  3891 E HttpOperation: 	... 15 more
08-16 17:14:33.290  2990  3891 E HttpOperation: Caused by: faj: BadAuthentication
08-16 17:14:33.290  2990  3891 E HttpOperation: 	at fal.a(PG:38)
08-16 17:14:33.290  2990  3891 E HttpOperation: 	at jdj.a(PG:4089)
08-16 17:14:33.290  2990  3891 E HttpOperation: 	... 17 more
,08-16 17:14:33.293  2990  3891 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 17:14:33.293  2990  3891 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	at hec.a(PG:42)
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	at hee.a(PG:102)
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	at czr.a(PG:65)
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	at kka.a(PG:108)
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 17:14:33.293  2990  3891 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	... 15 more
08-16 17:14:33.293  2990  3891 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	at fal.a(PG:38)
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 17:14:33.293  2990  3891 E ExperimentLoader: 	... 17 more
,08-16 17:14:33.415   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 128161, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 17:14:37.349  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:14:37.350  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:14:37.350  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:14:37.351  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:14:37.351  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:14:37.352  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:14:37.352  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list
,08-16 17:14:37.352  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:14:37.353  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
,08-16 17:14:37.353  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:14:37.353  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.355  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:14:37.355  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.359  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:14:37.359  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:14:37.360  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:14:37.360  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:37.362  3804  3862 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 17:14:37.364  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:14:37.365  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:14:37.365  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:14:37.365  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:14:37.366  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.366  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.366  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list
08-16 17:14:37.367  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:37.367  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
,08-16 17:14:37.367  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:14:37.368  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.368  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.368  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.369  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.371  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:14:37.371  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:14:37.371  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:37.371  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:37.372  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 17:14:37.372  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:14:37.372  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:14:37.372  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:14:37.372  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:14:37.372  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.372  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.373  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list
08-16 17:14:37.373  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:37.373  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:37.373  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:14:37.373  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.373  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.373  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.373  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.374  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:14:37.374  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:14:37.375  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:14:37.375  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:37.375  3804  3862 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 17:14:37.375  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:14:37.376  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:14:37.376  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:14:37.376  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:14:37.376  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.376  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:14:37.376  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list
08-16 17:14:37.376  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:37.376  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:37.376  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:14:37.376  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:14:37.376  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.376  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.377  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.378  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:14:37.378  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:14:37.378  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:37.378  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:37.379  3804  3862 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-16 17:14:37.379  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:14:37.379  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:14:37.379  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:14:37.379  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:14:37.379  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:14:37.379  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.379  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list
08-16 17:14:37.379  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:37.379  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
,08-16 17:14:37.379  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:14:37.380  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.380  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.380  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.380  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.381  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:14:37.381  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:14:37.381  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:37.382  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:37.383  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 17:14:37.385  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:14:37.385  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 17:14:37.385  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:14:37.385  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 17:14:37.385  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 17:14:37.385  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 17:14:37.386  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 17:14:37.386  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 17:14:37.386  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:14:37.386  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:14:37.386  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:14:37.386  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:14:37.386  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.386  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.386  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list
08-16 17:14:37.386  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:37.386  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:37.387  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:14:37.387  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.387  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.387  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.387  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:14:37.389  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:14:37.389  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:14:37.389  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:37.389  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:37.390  3804  3862 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:14:37.390  3804  3862 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 17:14:37.390  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 17:14:37.394  3804  3862 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:14:37.394  3804  3862 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 17:14:37.394  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 17:14:37.394  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 17:14:37.394  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 17:14:37.394  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 17:14:37.395  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 17:14:37.395  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 17:14:37.395  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 17:14:37.395  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-16 17:14:37.395  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 17:14:37.395  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 17:14:37.395  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 17:14:37.395  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-16 17:14:37.395  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 17:14:37.395  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 17:14:37.396  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-16 17:14:37.396  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 17:14:37.396  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 17:14:37.396  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 17:14:37.396  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810],
08-16 17:14:37.396  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 17:14:37.396  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 17:14:37.396  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-16 17:14:37.396  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 17:14:37.397  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 17:14:37.397  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 17:14:37.397  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 17:14:37.397  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,08-16 17:14:37.397  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 17:14:37.397  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 17:14:37.397  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-16 17:14:37.399  3804  3862 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 17:14:37.400  3804  3862 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-16 17:14:37.400  3804  3862 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 17:14:37.400  3804  3862 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:14:37.400  3804  3862 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:14:37.400  3804  3862 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-16 17:14:37.401  3804  3862 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:14:37.401  3804  3862 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 17:14:37.401  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 17:14:37.403  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 17:14:37.404  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 17:14:37.404  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 17:14:37.405  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 17:14:37.405  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 17:14:37.405  3804  3862 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 17:14:37.405  3804  3862 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 17:14:37.408  3804  3862 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 17:14:37.408  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:14:37.408  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:14:37.409  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:14:37.409  3804  3893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 397)
08-16 17:14:37.409  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:14:37.410  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.410  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.410  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 17:14:37.412  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list
08-16 17:14:37.412  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:37.412  3804  3893 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:14:37.412  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:37.412  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:14:37.412  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.413  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.413  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.413  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:14:37.414  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:14:37.414  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:14:37.414  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:37.414  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
,08-16 17:14:37.415  3804  3862 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 17:14:37.416  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:14:37.416  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:14:37.416  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:14:37.416  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:14:37.417  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.417  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.417  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list
08-16 17:14:37.417  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:14:37.417  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:37.417  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:14:37.417  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.418  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.418  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:14:37.418  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.419  3804  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 397
08-16 17:14:37.420  3804  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 397)
08-16 17:14:37.421  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:14:37.421  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:14:37.422  2690  2885 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
08-16 17:14:37.422  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:37.422  3804  3893 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 397)
08-16 17:14:37.422  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:37.423  3804  3894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 397)
08-16 17:14:37.424  3804  3862 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 17:14:37.425  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:14:37.425  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:14:37.426  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:14:37.426  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:14:37.426  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.426  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:14:37.427  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list
08-16 17:14:37.427  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:37.427  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:37.427  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:14:37.428  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.428  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.428  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.428  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:14:37.430  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:14:37.430  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:14:37.431  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:37.431  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
,08-16 17:14:37.431  3804  3862 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 17:14:37.432  3804  3862 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,08-16 17:14:37.432  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:14:37.432  3804  3862 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 17:14:37.432  3804  3862 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 17:14:37.432  3804  3862 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 17:14:37.432  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-16 17:14:37.432  3804  3862 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 17:14:37.432  3804  3862 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 17:14:37.432  3804  3862 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 17:14:37.432  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:14:37.432  3804  3862 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 17:14:37.433  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:14:37.433  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:14:37.433  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:14:37.433  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:14:37.433  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.433  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:14:37.433  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list
08-16 17:14:37.433  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:37.433  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:37.433  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:14:37.433  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.433  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:14:37.434  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.434  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.435  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:14:37.435  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:14:37.435  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:37.435  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
,08-16 17:14:37.435  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:14:37.435  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.435  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:37.436  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list
08-16 17:14:37.436  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:37.436  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
,08-16 17:14:37.436  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:14:37.436  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:37.436  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:14:37.731   873  1302 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-16 17:14:40.852  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:14:40.861  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:14:40.864  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:14:40.920  1493  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 17:14:40.921  1493  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 17:14:40.921  1493  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 17:14:40.923  1493  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:14:40.993  3524  3524 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 17:14:40.994  3524  3524 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-16 17:14:40.996  3524  3524 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-16 17:14:42.437  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:14:42.437  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
,08-16 17:14:42.438  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:14:42.438  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:42.438  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:42.439  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list
08-16 17:14:42.439  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:14:42.440  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:14:42.440  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:14:42.440  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:14:42.441  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:42.441  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:42.441  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list
08-16 17:14:42.441  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:42.442  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:42.442  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:14:42.442  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:42.442  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:42.443  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:42.443  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:14:42.446  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:14:42.447  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:14:42.447  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:42.447  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
,08-16 17:14:42.452  3804  3862 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-16 17:14:42.453  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:14:42.456  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 17:14:42.457  3804  3862 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-16 17:14:42.457  3804  3862 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 17:14:42.457  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 17:14:42.457  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:14:42.457  3804  3804 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 17:14:42.458  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:14:42.458  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 17:14:42.458  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 17:14:42.458  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 17:14:42.458  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:42.458  3804  3862 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 17:14:42.458  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list
08-16 17:14:42.458  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:42.459  3804  3895 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:14:42.459  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 17:14:42.461  3804  3895 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-16 17:14:42.461  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:14:42.461  3804  3895 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 17:14:42.461  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:14:42.461  3804  3895 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 17:14:42.458  3804  3804 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 17:14:42.462  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:42.462  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:42.463  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:14:42.463  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:42.463  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:14:42.463  3804  3804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:14:42.464  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:14:42.464  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:14:42.464  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:14:42.464  3804  3804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:14:42.470  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:14:42.470  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:42.471  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list,
08-16 17:14:42.471  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:42.471  3804  3804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false,
08-16 17:14:42.471  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:42.471  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:14:42.471  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:14:42.471  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:42.471  3804  3804 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:14:42.471  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:42.471  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:14:42.473  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:14:42.473  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:14:42.473  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:42.473  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
,08-16 17:14:42.475  3804  3862 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-16 17:14:42.475  3804  3862 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-16 17:14:42.475  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 17:14:42.475  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 17:14:42.475  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 17:14:42.475  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:14:42.475  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:14:42.475  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:14:42.476  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:14:42.476  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:42.476  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:42.476  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list
,08-16 17:14:42.476  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:42.476  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:42.476  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:14:42.476  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:14:42.476  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:42.476  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:42.476  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:14:42.478  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:14:42.478  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:14:42.478  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:42.478  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
,08-16 17:14:42.482  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:14:42.482  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:14:42.482  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 17:14:42.483  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:14:42.483  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:42.483  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:42.484  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list
,08-16 17:14:42.484  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:42.484  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:42.484  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:14:42.484  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:14:42.485  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:42.485  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:42.485  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:42.487  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:14:42.487  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:14:42.487  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:14:42.487  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:42.488  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:14:42.488  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:14:42.488  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:14:42.489  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:14:42.489  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:42.489  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:42.489  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@56a2ad3 not in the list
08-16 17:14:42.489  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:14:42.489  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:42.489  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:14:42.489  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:42.489  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:14:42.489  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:42.489  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:14:42.491  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:14:42.491  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:14:42.491  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:14:42.491  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@972b610 not in the list
08-16 17:14:42.492  3804  3862 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 17:14:42.492  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:14:42.493  3804  3862 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-16 17:14:42.493  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 17:14:42.493  3804  3862 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 17:14:42.493  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 17:14:42.496  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-16 17:14:42.496  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 17:14:42.497  3804  3862 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 17:14:42.497  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-16 17:14:42.497  3804  3862 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-16 17:14:42.497  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-16 17:14:42.497  3804  3862 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 17:14:42.497  3804  3862 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 17:14:42.498  3804  3862 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 17:14:42.498  3804  3862 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-16 17:14:42.499  3804  3862 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 17:14:42.499  3804  3862 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,08-16 17:14:42.502  3804  3862 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 17:14:42.502  3804  3862 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-16 17:14:42.503  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:14:42.503  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3636ec3 added. We now have 3 listener(s)
08-16 17:14:42.504  3804  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:14:42.507  3804  3862 D BluetoothAdapter: enable(): BT is already enabled..!
,08-16 17:14:42.507   873  1686 D WifiService: setWifiEnabled: true pid=3804, uid=10000
08-16 17:14:42.507   873  1686 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 17:14:42.543  2690  2871 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,08-16 17:14:42.544  2690  2871 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-16 17:14:42.973  3804  3804 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 17:14:43.208   873  2089 D NetlinkSocketObserver: NeighborEvent{elapsedMs=168583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 17:14:47.513  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:14:47.513  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ae7c340 added. We now have 4 listener(s)
08-16 17:14:47.514  3804  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:14:47.531  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:14:47.531  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ae7c340 removed from the list
,08-16 17:14:47.532  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:14:47.532  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:47.534  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:14:47.536  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:14:47.537  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5abd279 added. We now have 4 listener(s)
08-16 17:14:47.537  3804  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:14:47.541  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:14:47.541  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5abd279 removed from the list
,08-16 17:14:47.542  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:14:47.542  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:14:47.542  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:14:47.544  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:14:47.545  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6dfabbe added. We now have 4 listener(s)
08-16 17:14:47.545  3804  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:14:47.554   873  1685 D WifiService: setWifiEnabled: false pid=3804, uid=10000
08-16 17:14:47.554   873  1685 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 17:14:47.565  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:14:47.565  2690  2737 D BluetoothAdapterState: Current state: ON, message: 23
,08-16 17:14:47.567  2690  2737 D BluetoothAdapterProperties: Setting state to 13
,08-16 17:14:47.568  2690  2737 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-16 17:14:47.569  2690  2737 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 17:14:47.571  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:14:47.571  3804  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:14:47.571  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:47.571  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:47.571  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:14:47.571  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:14:47.571  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:14:47.571  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:14:47.571  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:14:47.572  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:47.572  3804  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:14:47.572  3804  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:14:47.574  2690  2737 I BluetoothAdapterState: Entering PendingCommandState
08-16 17:14:47.577  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:14:47.578  2690  2741 D BluetoothAdapterProperties: Scan Mode:20
08-16 17:14:47.578  2690  2737 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-16 17:14:47.581  2690  2690 D HeadsetService: Received stop request...Stopping profile...
08-16 17:14:47.584  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:14:47.588  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:47.588  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:14:47.588  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:47.588  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:47.588  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:14:47.588  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:14:47.588  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:14:47.588  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:14:47.588  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:14:47.589  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:47.589  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:14:47.590  1348  2036 D BluetoothHeadset: Proxy object disconnected
08-16 17:14:47.590   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 17:14:47.590  1348  1348 D HeadsetProfile: Bluetooth service disconnected
08-16 17:14:47.590   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 17:14:47.590   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 17:14:47.591  1940  2097 D BluetoothHeadset: Proxy object disconnected
08-16 17:14:47.591  2690  2690 D A2dpService: Received stop request...Stopping profile...
08-16 17:14:47.592  2690  2891 D A2dpStateMachine: Exit Disconnected: -1
08-16 17:14:47.593  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:47.593  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:14:47.593  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:47.593  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:47.593  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:14:47.593  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:14:47.593  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:14:47.593  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:14:47.593  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:14:47.593   873   873 D BluetoothA2dp: Proxy object disconnected
,08-16 17:14:47.594  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:47.594  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:14:47.594  1348  1348 D BluetoothA2dp: Proxy object disconnected
08-16 17:14:47.594  2690  2690 D HidService: Received stop request...Stopping profile...
08-16 17:14:47.594  2690  2690 D HidService: Stopping Bluetooth HidService
,08-16 17:14:47.595  1348  1348 D BluetoothInputDevice: Proxy object disconnected
08-16 17:14:47.595  1348  1348 D HidProfile: Bluetooth service disconnected
,08-16 17:14:47.596  2690  2690 D HealthService: Received stop request...Stopping profile...
08-16 17:14:47.596  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:14:47.598  2690  2690 V BluetoothAdapterState: isTurningOff()=true
08-16 17:14:47.598  2690  2690 V BluetoothAdapterState: isTurningOn()=false
08-16 17:14:47.598  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:14:47.598  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:14:47.599  2690  2690 D PanService: Received stop request...Stopping profile...
,08-16 17:14:47.600  1348  1348 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 17:14:47.600  1348  1348 D PanProfile: Bluetooth service disconnected
,08-16 17:14:47.601  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 17:14:47.601  2690  2690 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 17:14:47.601  2690  2741 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 17:14:47.602  2690  2871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:14:47.602  2690  2690 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 17:14:47.602  2690  2871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 17:14:47.602  2690  2871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:14:47.602  2690  2741 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-16 17:14:47.603  2690  2690 D BluetoothMapService: Received stop request...Stopping profile...
08-16 17:14:47.603  2690  2690 D BluetoothMapService: stop()
08-16 17:14:47.604  2690  2690 D BluetoothMapAppObserver: deinitObservers()
08-16 17:14:47.604  2690  2690 D BluetoothMapAppObserver: removeReceiver()
08-16 17:14:47.604   873  1302 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 17:14:47.604   873  1302 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-16 17:14:47.605   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 17:14:47.605   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 17:14:47.605  1348  1348 D BluetoothMap: Proxy object disconnected
08-16 17:14:47.606  1348  1348 D MapProfile: Bluetooth service disconnected
08-16 17:14:47.606  2690  2690 V BluetoothAdapterState: isTurningOff()=true
08-16 17:14:47.606  2690  2690 V BluetoothAdapterState: isTurningOn()=false
08-16 17:14:47.606  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:14:47.606  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:14:47.610  2690  2871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:14:47.610  2690  2871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:14:47.610  2690  2871 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:14:47.610  2690  2871 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:14:47.611  2690  2871 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:14:47.611  2690  2871 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:14:47.611  2690  2741 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-16 17:14:47.612  2690  2690 V BluetoothAdapterState: isTurningOff()=true
08-16 17:14:47.612  2690  2690 V BluetoothAdapterState: isTurningOn()=false
08-16 17:14:47.612  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:14:47.612  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:14:47.613  2690  2690 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 17:14:47.613   873  1302 E native  : do suspend true
08-16 17:14:47.613  2690  2741 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 17:14:47.613  2690  2690 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-16 17:14:47.613  2690  2690 V BluetoothAdapterState: isTurningOff()=true
08-16 17:14:47.613  2690  2690 V BluetoothAdapterState: isTurningOn()=false
,08-16 17:14:47.613  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:14:47.613  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:14:47.614  2690  2690 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 17:14:47.614  2690  2741 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-16 17:14:47.614  2690  2690 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-16 17:14:47.615  2690  2690 V BluetoothAdapterState: isTurningOff()=true
,08-16 17:14:47.615  2690  2690 V BluetoothAdapterState: isTurningOn()=false
,08-16 17:14:47.615  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 17:14:47.615  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:14:47.615  2690  2690 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 17:14:47.616  2690  2690 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 17:14:47.617  2690  2690 D BluetoothMapService: MAP Service closeService in
08-16 17:14:47.617  2690  2690 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 17:14:47.617  2690  2690 D ObexServerSockets0: shutdown(block = true)
08-16 17:14:47.617  2690  2897 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-16 17:14:47.619  2690  2690 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 17:14:47.619  2690  2898 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-16 17:14:47.623  2690  2885 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-16 17:14:47.624  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:14:47.625  2690  2690 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 17:14:47.627  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:14:47.627  2690  2690 V BluetoothAdapterState: isTurningOff()=true
,08-16 17:14:47.627  2690  2690 V BluetoothAdapterState: isTurningOn()=false
08-16 17:14:47.627  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:14:47.628  2690  2690 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:14:47.628  2690  2737 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-16 17:14:47.628  2690  2737 D BluetoothAdapterProperties: Setting state to 15
,08-16 17:14:47.628  2690  2690 D BluetoothMapService: cleanup()
08-16 17:14:47.628  2690  2690 D BluetoothMapService: MAP Service closeService in
08-16 17:14:47.628  2690  2737 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 17:14:47.628  2690  2690 I BtOppRfcommListener: stopping Accept Thread
,08-16 17:14:47.629  2690  3428 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:14:47.629  2690  2737 I BluetoothAdapterState: Entering BleOnState
08-16 17:14:47.629  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:14:47.629  2690  3428 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 17:14:47.629   370   871 D CommandListener: Clearing all IP addresses on wlan0
08-16 17:14:47.629   873  2092 D DhcpClient: Clearing IP address
08-16 17:14:47.632   370   871 D CommandListener: Setting iface cfg
08-16 17:14:47.634  1493  2528 V NativeCrypto: Read error: ssl=0x9aa3e400: I/O error during system call, Connection timed out
08-16 17:14:47.639  1493  2528 V NativeCrypto: SSL shutdown failed: ssl=0x9aa3e400: I/O error during system call, Broken pipe
,08-16 17:14:47.642   873   886 I ActivityManager: Start proc 3899:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-16 17:14:47.642   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:14:47.643   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-16 17:14:47.643   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-16 17:14:47.645  1348  1359 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:14:47.646   873  1302 D WifiStateMachine: Start Disconnecting Watchdog 1
08-16 17:14:47.646   393   393 E Parcel  : Reading a NULL string not supported here.
,08-16 17:14:47.646   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 17:14:47.646   873  1302 E native  : do suspend true
08-16 17:14:47.648  1348  1360 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 17:14:47.648   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:14:47.648  1940  2284 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:14:47.649   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 17:14:47.649  1348  2036 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:14:47.650  1348  1359 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 17:14:47.652   873  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 17:14:47.653   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:14:47.654  1348  1360 D BluetoothPan: onBluetoothStateChange on: false
,08-16 17:14:47.654  1348  2036 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 17:14:47.656  2690  2737 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 17:14:47.656  2690  2737 D BluetoothAdapterProperties: Setting state to 16
08-16 17:14:47.656  2690  2737 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 17:14:47.657  2690  2737 D BluetoothAdapterProperties: onBleDisable
,08-16 17:14:47.658  2690  2738 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-16 17:14:47.658  2690  2737 I BluetoothAdapterState: Entering PendingCommandState
08-16 17:14:47.659  2690  2741 D BluetoothAdapterProperties: Scan Mode:20
,08-16 17:14:47.661  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:47.661  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:14:47.661  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:47.661  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:47.661  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:14:47.661  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:14:47.661  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:14:47.661  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:14:47.661  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:14:47.661  2690  2871 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-16 17:14:47.661  2690  2871 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:14:47.661  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:47.662  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:14:47.664  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:47.664  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:14:47.664  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:47.664  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:47.664  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:14:47.664  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:14:47.664  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
08-16 17:14:47.664  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:14:47.664  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:14:47.664  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:47.665  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:14:47.666  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:47.667  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:14:47.667  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:47.667  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:47.667  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:14:47.667  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:14:47.667  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:14:47.667  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:14:47.667  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:14:47.667  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:47.667  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:14:47.668  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:14:47.670  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:14:47.671  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:14:47.684   873  2186 D DhcpClient: Receive thread stopped
,08-16 17:14:47.691   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:14:47.703  3899  3899 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-16 17:14:47.712  3899  3899 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:14:47.716   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:14:47.716   370   871 D CommandListener: Clearing all IP addresses on wlan0
,08-16 17:14:47.717   873  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 17:14:47.717   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 17:14:47.718   873   890 D Tethering: MasterInitialState.processMessage what=3
08-16 17:14:47.721  3419  3419 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@50f7520 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-16 17:14:47.722  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:14:47.722   873  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-16 17:14:47.723  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:14:47.724  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:14:47.718  1493  1493 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:14:47.741   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b31890f:true
,08-16 17:14:47.745   873  1964 I ActivityManager: Start proc 3917:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-16 17:14:47.746   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 17:14:47.748  1876  2199 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:14:47.750  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:47.750  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:14:47.750  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:47.750  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:47.750  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:14:47.750  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:14:47.750  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:14:47.750  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:14:47.750  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:14:47.750   873  1302 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 17:14:47.751  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:47.751  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:14:47.753  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:14:47.754  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:14:47.754  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:47.754  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:47.754  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:14:47.754  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:14:47.754  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:14:47.754  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:14:47.754  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:14:47.755  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:14:47.756  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:14:47.758  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:47.758  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:14:47.758  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:47.758  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:47.758  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:14:47.758  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:14:47.758  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:14:47.758  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:14:47.758  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:14:47.759  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:47.759  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:14:47.775  3899  3899 D LocalBluetoothProfileManager: Adding local MAP profile
,08-16 17:14:47.780  3899  3899 D BluetoothMap: Create BluetoothMap proxy object
,08-16 17:14:47.785  3917  3917 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-16 17:14:47.788   370   871 E Netd    : netlink response contains error (No such file or directory)
,08-16 17:14:47.789   873  1306 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-16 17:14:47.792  3899  3899 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-16 17:14:47.803  3899  3899 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:14:47.811   873   883 I ActivityManager: Killing 3087:com.google.android.talk/u0a61 (adj 15): empty #17
,08-16 17:14:47.864  2690  2741 I bt_hci  : shut_down
,08-16 17:14:47.876  2690  2747 I bt_vendor: low_power_mode_cb
,08-16 17:14:47.877  2690  2747 D bt_hwcfg: hw_epilog_process
,08-16 17:14:47.898  2690  2747 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 17:14:47.898  2690  2747 I bt_vendor: epilog_cb
,08-16 17:14:47.899  2690  2747 I bt_hci  : epilog_finished_callback
,08-16 17:14:47.904  2690  2741 I bt_hci_h4: hal_close
,08-16 17:14:47.905  2690  2741 I bt_userial_vendor: device fd = 51 close
,08-16 17:14:48.002  3917  3917 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:14:48.002  3917  3917 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:14:48.002  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:14:48.003  3917  3917 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:14:48.003  3917  3917 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:14:48.003  3917  3917 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.r.k.d(PG:583)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:14:48.003  3917  3917 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726),
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 17:14:48.003  3917  3917 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
,08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 17:14:48.003  3917  3917 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-16 17:14:48.003  3917  3917 D StrictMode: 	,at java.io.File.lastModified(File.java:569)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:14:48.003  3917  3917 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:14:48.014  3899  3899 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:14:48.022  1493  1493 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:14:48.027  2690  2738 D bt_stack_manager: event_shut_down_stack finished.
,08-16 17:14:48.027  2690  2737 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-16 17:14:48.028  3899  3899 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:14:48.031  2690  2737 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 17:14:48.032  2690  2690 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 17:14:48.032  2690  2690 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 17:14:48.032  2690  2690 D BtGatt.GattService: stop()
,08-16 17:14:48.033  2690  2690 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 17:14:48.051   873   883 I ActivityManager: Start proc 3950:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-16 17:14:48.052   873   883 I ActivityManager: Killing 3419:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-16 17:14:48.162  2690  2690 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:14:48.162  2690  2690 V BluetoothAdapterState: isTurningOn()=false
,08-16 17:14:48.162  2690  2690 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 17:14:48.162  2690  2690 V BluetoothAdapterState: isBleTurningOff()=true
,08-16 17:14:48.163  2690  2737 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-16 17:14:48.163  2690  2737 D BluetoothAdapterProperties: Setting state to 10
08-16 17:14:48.164  2690  2737 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-16 17:14:48.165  2690  2737 I BluetoothAdapterState: Entering OffState
,08-16 17:14:48.165   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-16 17:14:48.180  2690  2690 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-16 17:14:48.180  2690  2690 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-16 17:14:48.181  2690  2690 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 17:14:48.181  2690  2738 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-16 17:14:48.183  2690  2690 I art     : System.exit called, status: 0
08-16 17:14:48.183  2690  2690 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 17:14:48.192  3950  3950 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-16 17:14:48.231   873  1964 I ActivityManager: Process com.android.bluetooth (pid 2690) has died
,08-16 17:14:48.243  3917  3941 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-16 17:14:48.480   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a28885:true
,08-16 17:14:48.543  3950  3970 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-16 17:14:48.543  3950  3970 I Babel_SMS: MmsConfig.loadMmsSettings
,08-16 17:14:48.547  3950  3970 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 17:14:48.547  3950  3970 I Babel_SMS: MmsConfig.loadFromDatabase
,08-16 17:14:48.580  3950  3970 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-16 17:14:48.580  3950  3970 I Babel_SMS: MmsConfig.loadFromResources
,08-16 17:14:48.588  3950  3970 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-16 17:14:48.589  3950  3970 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 17:14:48.612  3950  3950 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 17:14:48.615  3950  3950 I Babel_Crash: startup - clean
,08-16 17:14:48.639  3950  3950 I Babel_telephony: TeleModule.launchCompleted
,08-16 17:14:48.649   873  1380 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 17:14:48.660  3950  3950 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-16 17:14:48.667  3950  3950 W Babel   : BAM#gBA: invalid account id: -1
,08-16 17:14:48.668  3950  3950 W Babel   : BAM#gBA: invalid account id: -1
,08-16 17:14:48.668  3950  3950 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-16 17:14:48.671  3950  3975 I Babel   : deleted: false for 0
,08-16 17:14:48.680   873  1688 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 17:14:48.702  1691  1691 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 17:14:48.708  1691  1691 D SystemUpdateService: onCreate
,08-16 17:14:48.721  1691  1691 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 17:14:48.734  1691  3977 I SystemUpdateService: active receiver: enabled
,08-16 17:14:48.741  1691  1691 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 17:14:48.742  1691  3977 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 17:14:48.745  1691  3977 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-16 17:14:48.745  1691  3977 I SystemUpdateService: now status is 0 (complete)
08-16 17:14:48.745  1691  3977 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 17:14:48.746  1691  3977 I SystemUpdateService: file has been verified
08-16 17:14:48.746  1691  3977 I SystemUpdateService: OTA package size = 12249756
,08-16 17:14:48.749  1691  2505 I iu.UploadsManager: num queued entries: 0
,08-16 17:14:48.750  1691  2505 I iu.UploadsManager: num updated entries: 0
,08-16 17:14:48.751  1691  2505 I iu.SyncManager: NEXT; no task
,08-16 17:14:48.753  3950  3950 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 17:14:48.753  1691  3977 I SystemUpdateService: showing system update notification
,08-16 17:14:48.759  1691  1691 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 17:14:48.760  1691  1691 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 17:14:48.774   873  1685 I ActivityManager: Start proc 3979:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-16 17:14:48.777  1691  1691 D SystemUpdateService: onDestroy
,08-16 17:14:48.788  3950  3950 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 17:14:48.796  3950  3950 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-16 17:14:48.798  3950  3950 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 17:14:48.803  3950  3950 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 17:14:48.809  3979  3979 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-16 17:14:48.812  3950  3950 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 17:14:48.816  3950  3950 I vclib   : onServiceConnected
,08-16 17:14:48.818  3979  3979 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:14:48.825  3979  3979 D SprintDMHelper: simOperator: 
08-16 17:14:48.825  3979  3979 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 17:14:48.860   873  1380 I ActivityManager: Start proc 3991:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
08-16 17:14:48.861   873  1380 I ActivityManager: Killing 3469:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-16 17:14:49.008   873  1685 I ActivityManager: Start proc 4006:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-16 17:14:49.014  3950  4005 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-16 17:14:49.018   873  1964 I ActivityManager: Killing 1712:android.process.acore/u0a5 (adj 15): empty #17
,08-16 17:14:49.080  4006  4006 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-16 17:14:49.136  4006  4006 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-16 17:14:49.136  4006  4006 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 17:14:49.136  4006  4006 I GAv4    :   adb logcat -s GAv4
,08-16 17:14:49.153  4006  4006 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-16 17:14:49.158  4006  4006 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-16 17:14:49.184  4006  4023 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-16 17:14:49.293  4006  4006 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-16 17:14:49.330  4006  4006 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-16 17:14:49.337  4006  4006 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4710-4713)
08-16 17:14:49.337  4006  4006 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 17:14:49.349  4006  4006 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c31d05a}
,08-16 17:14:49.349  4006  4006 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 17:14:49.350  4006  4006 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 17:14:49.359  4006  4006 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-16 17:14:49.361  4006  4006 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 17:14:49.381  4006  4006 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 17:14:49.397  4006  4006 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 17:14:49.397  4006  4006 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 17:14:49.397  4006  4006 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 17:14:49.397  4006  4006 I Adreno  : Build Date                       : 10/20/15
08-16 17:14:49.397  4006  4006 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 17:14:49.397  4006  4006 I Adreno  : Local Branch                     : M14
08-16 17:14:49.397  4006  4006 I Adreno  : Remote Branch                    : 
08-16 17:14:49.397  4006  4006 I Adreno  : Remote Branch                    : 
08-16 17:14:49.397  4006  4006 I Adreno  : Reconstruct Branch               : 
,08-16 17:14:49.458  4006  4006 I NSApplication: Starting up...
,08-16 17:14:49.466  4006  4052 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 17:14:49.503   873  1964 I ActivityManager: Start proc 4057:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-16 17:14:49.505   873  1964 I ActivityManager: Killing 3639:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-16 17:14:49.566  4057  4057 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-16 17:14:49.739   873  1380 I ActivityManager: Killing 3654:com.android.musicfx/u0a18 (adj 15): empty #17
,08-16 17:14:52.575   873  1687 D WifiService: setWifiEnabled: true pid=3804, uid=10000
,08-16 17:14:52.576   873  1687 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 17:14:52.594   873  1302 D WifiConfigStore: Loading config and enabling all networks 
,08-16 17:14:52.600  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:14:52.601  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:14:52.601  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:52.601  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:52.601  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:14:52.601  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:14:52.601  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:14:52.601  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:14:52.601  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:14:52.601  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:14:52.602  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:14:52.605  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:14:52.605  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:14:52.605  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:52.605  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:52.605  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:14:52.605  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:14:52.605  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:14:52.605  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:14:52.605  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:14:52.605  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:52.606  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,08-16 17:14:52.608  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:14:52.609  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:14:52.609  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:52.609  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:52.609  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:14:52.609  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:14:52.609  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:14:52.609  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:14:52.609  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:14:52.609  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:52.609  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:14:52.643   873  1302 D WifiConfigStore: loaded 0 passpoint configs
,08-16 17:14:52.644   873  1302 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-16 17:14:52.645   873  1302 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000,
08-16 17:14:52.646   873  1302 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 17:14:52.646   873  1302 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 17:14:52.646   873  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-16 17:14:52.647   873  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 17:14:52.666   370   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 17:14:52.667   873  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-16 17:14:52.667   370   871 D CommandListener: Setting iface cfg
08-16 17:14:52.668   873  1301 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
08-16 17:14:52.668   873  1301 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 17:14:52.679   873  1302 E native  : do suspend true
,08-16 17:14:52.679   873  1301 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 17:14:52.685   873  1301 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 17:14:52.692   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 17:14:53.560   873  1964 I ActivityManager: Killing 3489:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-16 17:14:54.069   873  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 17:14:54.117   873  1302 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=5.69 rxSuccessRate=8.19 delta 1000 -> 994
,08-16 17:14:54.123   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 17:14:54.123   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:14:54.146   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 17:14:54.218   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 17:14:54.224  1456  1456 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 17:14:54.652  1456  1456 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 17:14:54.677  1456  1456 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 17:14:54.678  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 17:14:54.681   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 17:14:54.692   873  1302 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 17:14:54.692   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:14:54.693   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 17:14:54.711   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:14:54.722   370   871 D CommandListener: Setting iface cfg
08-16 17:14:54.723   873  1302 D WifiStateMachine: Start Dhcp Watchdog 2
,08-16 17:14:54.729   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 17:14:54.768   873  4081 D DhcpClient: Receive thread started
,08-16 17:14:54.856   873  1302 E native  : do suspend false
,08-16 17:14:54.879   873  2092 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 17:14:54.895   873  4081 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172643, domain null
,08-16 17:14:54.897   873  2092 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172643 seconds
,08-16 17:14:54.900   873  2092 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 17:14:54.912   873  4081 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 17:14:54.913   873  2092 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 17:14:54.919   370   871 D CommandListener: Setting iface cfg
,08-16 17:14:54.931   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 17:14:54.933   873  2092 D DhcpClient: Scheduling renewal in 86399s
08-16 17:14:54.933   873  1302 E native  : do suspend true
,08-16 17:14:54.963   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 17:14:54.967   873  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 17:14:54.969   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 17:14:54.973   873  1306 D ConnectivityService: Adding iface wlan0 to network 101
,08-16 17:14:54.986   873  1302 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 17:14:55.021   873  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 17:14:55.021   873  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-16 17:14:55.023   873  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-16 17:14:55.025   873  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-16 17:14:55.027   873  1306 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-16 17:14:55.040   873  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 17:14:55.046   873  1306 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-16 17:14:55.046   873  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-16 17:14:55.046   873  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-16 17:14:55.046   873  1306 D ConnectivityService:    accepting network in place of null
,08-16 17:14:55.046   873  1302 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-16 17:14:55.047   873  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-16 17:14:55.048   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 17:14:55.059   873  4080 D NetlinkSocketObserver: NeighborEvent{elapsedMs=180434, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 17:14:55.106   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:14:55.132   873  4079 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:80c::200e
,08-16 17:14:55.140   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:14:55.149   873  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-16 17:14:55.151   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:14:55.154   873  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-16 17:14:55.157   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 17:14:55.165  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:55.166  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:14:55.166  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:55.166  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:55.166  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:14:55.166  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:14:55.166  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:14:55.166  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:14:55.166  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:14:55.166  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:14:55.166  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:14:55.175  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:14:55.175  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:14:55.175  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:55.175  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:55.175  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:14:55.175  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:14:55.175  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:14:55.175  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:14:55.175  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:14:55.175  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:55.175  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:14:55.179  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:14:55.179  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:14:55.179  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:55.179  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:55.179  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:14:55.179  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:14:55.179  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:14:55.179  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:14:55.179  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 17:14:55.180  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:55.180  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:14:55.191  1691  1691 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 17:14:55.195  1691  1691 D SystemUpdateService: onCreate
,08-16 17:14:55.199  1691  1691 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 17:14:55.211   873  4079 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 15:14:55 GMT], X-Android-Received-Millis=[1471360495210], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471360495181]}
,08-16 17:14:55.216   873  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 17:14:55.217   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-16 17:14:55.217   873  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 17:14:55.219   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 17:14:55.209  3736  4092 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 17:14:55.228  1691  4094 I SystemUpdateService: active receiver: enabled
,08-16 17:14:55.233  1691  1691 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 17:14:55.234  1691  2505 I iu.UploadsManager: num queued entries: 0
,08-16 17:14:55.244  1691  2505 I iu.UploadsManager: num updated entries: 0
,08-16 17:14:55.245  1691  2505 I iu.SyncManager: NEXT; no task
,08-16 17:14:55.247  1691  1691 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 17:14:55.248  1691  1691 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 17:14:55.250  3979  3979 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:14:55.255  1691  4097 I MDM     : [173] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-16 17:14:55.255  1691  4097 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 17:14:55.256  3979  3979 D SprintDMHelper: simOperator: 
08-16 17:14:55.256  3979  3979 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 17:14:55.278  1691  4097 V GoogleAuthProtoRequest: [173] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 17:14:55.283  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:14:55.285  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:14:55.289  1691  4094 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 17:14:55.305  1691  4094 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 17:14:55.305  1691  4094 I SystemUpdateService: now status is 0 (complete)
08-16 17:14:55.305  1691  4094 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 17:14:55.305  1691  4094 I SystemUpdateService: file has been verified
,08-16 17:14:55.305  1691  4094 I SystemUpdateService: OTA package size = 12249756
,08-16 17:14:55.337  1691  4094 I SystemUpdateService: showing system update notification
,08-16 17:14:55.372  3736  4104 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 17:14:55.375  1691  1691 D SystemUpdateService: onDestroy
,08-16 17:14:55.377  1493  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-16 17:14:55.377  1493  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-16 17:14:55.377  1493  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:14:55.378  1493  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:14:55.405  3950  4100 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 17:14:55.411  1493  1505 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 17:14:55.411  1493  1505 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 17:14:55.411  1493  1505 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:14:55.412  1493  1505 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:14:55.443  1493  1987 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-16 17:14:55.443  1493  1987 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 17:14:55.443  1493  1987 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:14:55.443  1493  1987 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:14:55.446  1691  4097 E MDM     : [173] SitrepService.a: Error sending sitrep.
,08-16 17:14:55.459  3736  4104 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 17:14:55.459  3736  4092 E BooksSync: Soft error
08-16 17:14:55.459  3736  4092 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 17:14:55.459  3736  4092 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 17:14:55.459  3736  4092 E BooksSync: Sync error
08-16 17:14:55.459  3736  4092 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 17:14:55.459  3736  4092 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 17:14:55.460  3736  4092 I BooksSync: Finished books sync
,08-16 17:14:55.471   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 160540, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 17:14:56.148   873  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 17:14:57.588   873  3066 D WifiService: setWifiEnabled: false pid=3804, uid=10000
08-16 17:14:57.588   873  3066 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 17:14:57.626  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 17:14:57.635   873  1302 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-16 17:14:57.636   873  1302 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-16 17:14:57.636   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 17:14:57.636   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:14:57.654   873  1302 E native  : do suspend true
,08-16 17:14:57.675   873  2092 D DhcpClient: Clearing IP address
,08-16 17:14:57.675   370   871 D CommandListener: Clearing all IP addresses on wlan0
,08-16 17:14:57.680   370   871 D CommandListener: Setting iface cfg
,08-16 17:14:57.689  1493  4105 V NativeCrypto: Read error: ssl=0x9aa08800: I/O error during system call, Connection timed out
,08-16 17:14:57.692   873  4081 D DhcpClient: Receive thread stopped
08-16 17:14:57.694   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-16 17:14:57.694  1493  4105 V NativeCrypto: SSL shutdown failed: ssl=0x9aa08800: I/O error during system call, Broken pipe
08-16 17:14:57.694   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-16 17:14:57.700   873  1302 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-16 17:14:57.702   393   393 E Parcel  : Reading a NULL string not supported here.
,08-16 17:14:57.706   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 17:14:57.706   873  1302 E native  : do suspend true
08-16 17:14:57.709   873  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-16 17:14:57.759   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:14:57.799   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:14:57.801   370   871 D CommandListener: Clearing all IP addresses on wlan0
,08-16 17:14:57.803   873  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 17:14:57.803   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:14:57.810   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 17:14:57.823   873  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 17:14:57.824  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:14:57.824  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:14:57.824  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:57.824  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:57.824  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:14:57.824  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:14:57.824  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:14:57.824  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:14:57.824  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:14:57.825  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:57.825  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:14:57.829  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:57.830  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:14:57.830  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:57.830  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:57.830  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:14:57.830  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:14:57.830  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:14:57.830  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:14:57.830  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:14:57.830  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:57.830  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:14:57.834  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:57.835  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:14:57.835  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:57.835  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:57.835  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:14:57.835  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:14:57.835  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:14:57.835  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:14:57.835  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:14:57.835  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:57.835  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:14:57.848  1691  1691 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-16 17:14:57.849   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 17:14:57.853  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:57.853  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:14:57.853  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:57.853  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:57.853  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:14:57.853  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:14:57.853  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:14:57.853  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:14:57.853  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:14:57.854  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:57.854  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:14:57.855  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:57.855  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:14:57.855  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:57.855  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:57.855  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:14:57.855  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:14:57.855  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:14:57.855  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:14:57.855  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:14:57.855  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:14:57.855  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:14:57.857  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:57.857  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:14:57.857  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:14:57.857  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:14:57.857  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:14:57.857  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:14:57.857  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:14:57.857  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:14:57.857  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:14:57.857  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:14:57.857  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:14:57.858  1691  1691 D SystemUpdateService: onCreate
08-16 17:14:57.858   873  1302 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-16 17:14:57.861  1876  2199 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 17:14:57.862  1691  1691 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 17:14:57.875  1691  1691 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 17:14:57.877  1691  2505 I iu.UploadsManager: num queued entries: 0
,08-16 17:14:57.880  1691  4116 I SystemUpdateService: active receiver: enabled
,08-16 17:14:57.881  1691  1691 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 17:14:57.883  1691  1691 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 17:14:57.884  3979  3979 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:14:57.889  3979  3979 D SprintDMHelper: simOperator: 
08-16 17:14:57.889  3979  3979 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 17:14:57.891  1691  2505 I iu.UploadsManager: num updated entries: 0
,08-16 17:14:57.899   370   871 E Netd    : netlink response contains error (No such file or directory)
,08-16 17:14:57.900   873  1306 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-16 17:14:57.911  3950  4120 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-16 17:14:57.919  1691  2505 I iu.SyncManager: NEXT; no task
,08-16 17:14:57.919  1691  4116 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 17:14:57.926  1691  4116 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-16 17:14:57.926  1691  4116 I SystemUpdateService: now status is 0 (complete)
08-16 17:14:57.927  1691  4116 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 17:14:57.927  1691  4116 I SystemUpdateService: file has been verified
08-16 17:14:57.927  1691  4116 I SystemUpdateService: OTA package size = 12249756
,08-16 17:14:57.933  1691  4116 I SystemUpdateService: showing system update notification
,08-16 17:14:57.942  1691  1691 D SystemUpdateService: onDestroy
,08-16 17:15:02.645   873   890 I ActivityManager: Start proc 4124:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 17:15:02.777  4124  4124 D AdapterServiceConfig: Adding HeadsetService
,08-16 17:15:02.777  4124  4124 D AdapterServiceConfig: Adding A2dpService
,08-16 17:15:02.778  4124  4124 D AdapterServiceConfig: Adding HidService
,08-16 17:15:02.778  4124  4124 D AdapterServiceConfig: Adding HealthService
,08-16 17:15:02.778  4124  4124 D AdapterServiceConfig: Adding PanService
,08-16 17:15:02.778  4124  4124 D AdapterServiceConfig: Adding GattService
,08-16 17:15:02.778  4124  4124 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 17:15:02.793   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ffd813:true
08-16 17:15:02.793  4124  4124 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 17:15:02.799  4124  4124 I bt_bluedroid: init
,08-16 17:15:02.799  4124  4136 I BluetoothAdapterState: Entering OffState
,08-16 17:15:02.804  4124  4137 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 17:15:02.805  4124  4137 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 17:15:02.805  4124  4137 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 17:15:02.806  4124  4137 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 17:15:02.808  4124  4124 I bt_bluedroid: get_profile_interface socket
,08-16 17:15:02.810  4124  4124 I bt_bluedroid: get_profile_interface sdp
,08-16 17:15:02.813  4124  4140 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-16 17:15:02.813  4124  4135 I bt_bluedroid: config_hci_snoop_log
,08-16 17:15:02.816  4124  4140 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 17:15:02.818   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 17:15:02.826  4124  4136 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 17:15:02.827  4124  4136 D BluetoothAdapterProperties: Setting state to 14
08-16 17:15:02.827  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 17:15:02.829  4124  4136 D BluetoothBondStateMachine: make
,08-16 17:15:02.833  4124  4141 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 17:15:02.837  4124  4136 I BluetoothAdapterState: Entering PendingCommandState
,08-16 17:15:02.839  4124  4124 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 17:15:02.843  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@70a6860
,08-16 17:15:02.844  4124  4124 D BtGatt.DebugUtils: handleDebugAction() action=null,
,08-16 17:15:02.845  4124  4124 D BtGatt.GattService: Received start request. Starting profile...
,08-16 17:15:02.845  4124  4124 D BtGatt.GattService: start()
,08-16 17:15:02.846  4124  4124 I bt_bluedroid: get_profile_interface gatt
08-16 17:15:02.847  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@70a6860
,08-16 17:15:02.847  4124  4124 D BtGatt.AdvertiseManager: advertise manager created
,08-16 17:15:02.858  4124  4124 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:15:02.858  4124  4124 V BluetoothAdapterState: isTurningOn()=false
,08-16 17:15:02.858  4124  4124 V BluetoothAdapterState: isBleTurningOn()=true
,08-16 17:15:02.858  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:15:02.860  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-16 17:15:02.860  4124  4136 I bt_bluedroid: enable
08-16 17:15:02.860  4124  4137 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-16 17:15:02.861  4124  4137 I bt_hci  : start_up
,08-16 17:15:02.883  4124  4137 I bt_vendor: alloc value 0xb3a4e189
,08-16 17:15:02.883  4124  4137 I bt_vendor: init
08-16 17:15:02.883  4124  4137 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-16 17:15:02.884  4124  4137 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 17:15:02.994  4124  4137 D bt_hci  : start_up starting async portion
,08-16 17:15:02.994  4124  4144 I bt_hci  : event_finish_startup
08-16 17:15:02.995  4124  4144 I bt_hci_h4: hal_open
,08-16 17:15:02.995  4124  4144 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 17:15:03.002  4124  4144 I bt_userial_vendor: device fd = 51 open
,08-16 17:15:03.034  4124  4144 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 17:15:03.051   873  1306 D ConnectivityService: handlePromptUnvalidated 101
,08-16 17:15:03.066  4124  4144 D bt_hwcfg: Chipset BCM4354A2
,08-16 17:15:03.067  4124  4144 D bt_hwcfg: Target name = [BCM4354A2]
08-16 17:15:03.068  4124  4144 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 17:15:03.724  4124  4144 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 17:15:03.726  4124  4144 D bt_hwcfg: Settlement delay -- 100 ms
08-16 17:15:03.726  4124  4144 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 17:15:03.843  4124  4144 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 17:15:03.844  4124  4144 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 17:15:03.873  4124  4144 I bt_hwcfg: vendor lib fwcfg completed
,08-16 17:15:03.874  4124  4144 I bt_vendor: firmware callback
,08-16 17:15:03.874  4124  4144 I bt_hci  : firmware_config_callback
,08-16 17:15:03.885  4124  4146 I bt_btu  : btu_task pending for preload complete event
,08-16 17:15:03.886  4124  4146 I bt_btu_task: Bluetooth chip preload is complete
08-16 17:15:03.886  4124  4146 I bt_btu  : btu_task received preload complete event
,08-16 17:15:03.896  4124  4146 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 17:15:03.896  4124  4146 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 17:15:03.897  4124  4146 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 17:15:03.897  4124  4146 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-16 17:15:03.897  4124  4146 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-16 17:15:03.898  4124  4146 I         : BTE_InitTraceLevels -- TRC_A2D
,08-16 17:15:03.898  4124  4146 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 17:15:03.898  4124  4146 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 17:15:03.898  4124  4146 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 17:15:03.898  4124  4146 I         : BTE_InitTraceLevels -- TRC_PAN
,08-16 17:15:03.899  4124  4146 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 17:15:03.899  4124  4146 I         : BTE_InitTraceLevels -- TRC_GATT
,08-16 17:15:03.899  4124  4146 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 17:15:03.899  4124  4146 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 17:15:03.900  4124  4146 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 17:15:04.035  4124  4146 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39cbd9d
08-16 17:15:04.035  4124  4146 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39cbd9d 
,08-16 17:15:04.046  4124  4140 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 17:15:04.048  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 17:15:04.049  4124  4140 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 17:15:04.054  4124  4140 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 17:15:04.058  4124  4140 D BluetoothAdapterProperties: Scan Mode:20
,08-16 17:15:04.058  4124  4140 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 17:15:04.059  4124  4140 D bt_hci  : do_postload posting postload work item
08-16 17:15:04.059  4124  4144 I bt_hci  : event_postload
08-16 17:15:04.059  4124  4144 I bt_vendor: sco_config_cb
08-16 17:15:04.059  4124  4144 I bt_hci  : sco_config_callback postload finished.
,08-16 17:15:04.063  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:15:04.064  4124  4140 D bt_bte_conf: Device ID record 1 : primary
,08-16 17:15:04.064  4124  4140 D bt_bte_conf:   vendorId            = 000f
08-16 17:15:04.064  4124  4140 D bt_bte_conf:   vendorIdSource      = 0001
08-16 17:15:04.066  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:15:04.069  4124  4144 I bt_vendor: low_power_mode_cb
08-16 17:15:04.067  4124  4140 D bt_bte_conf:   product             = 1200
08-16 17:15:04.069  4124  4140 D bt_bte_conf:   version             = 1436
,08-16 17:15:04.069  4124  4140 D bt_bte_conf:   clientExecutableURL = 
08-16 17:15:04.069  4124  4140 D bt_bte_conf:   serviceDescription  = 
,08-16 17:15:04.069  4124  4140 D bt_bte_conf:   documentationURL    = 
08-16 17:15:04.069  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:15:04.070  4124  4140 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-16 17:15:04.070  4124  4137 D bt_stack_manager: event_start_up_stack finished
08-16 17:15:04.072  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-16 17:15:04.073  4124  4136 D BluetoothAdapterProperties: Setting state to 15
08-16 17:15:04.073  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-16 17:15:04.074  4124  4136 I BluetoothAdapterState: Entering BleOnState
,08-16 17:15:04.079  4124  4136 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-16 17:15:04.079  4124  4136 D BluetoothAdapterProperties: Setting state to 11
08-16 17:15:04.079  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-16 17:15:04.089  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@70a6860
,08-16 17:15:04.091  4124  4124 D HeadsetService: Received start request. Starting profile...
08-16 17:15:04.091  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-16 17:15:04.097  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:15:04.099  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:15:04.101  4124  4124 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 17:15:04.101  4124  4124 D HeadsetStateMachine: make
,08-16 17:15:04.105  4124  4136 I BluetoothAdapterState: Entering PendingCommandState
,08-16 17:15:04.111  4124  4124 D HeadsetStateMachine: max_hf_connections = 1
,08-16 17:15:04.111  4124  4124 I bt_bluedroid: get_profile_interface handsfree
,08-16 17:15:04.111  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 17:15:04.111  4124  4140 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-16 17:15:04.115  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@70a6860
08-16 17:15:04.115  4124  4124 D A2dpService: Received start request. Starting profile...
08-16 17:15:04.116  4124  4124 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-16 17:15:04.116  4124  4124 I bt_bluedroid: get_profile_interface avrcp
,08-16 17:15:04.123  4124  4124 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 17:15:04.123  4124  4124 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 17:15:04.123  4124  4124 D A2dpStateMachine: make
,08-16 17:15:04.124  4124  4124 I bt_bluedroid: get_profile_interface a2dp
,08-16 17:15:04.124  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-16 17:15:04.129  4124  4156 D A2dpStateMachine: Enter Disconnected: -2
08-16 17:15:04.129  4124  4124 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 17:15:04.130  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@70a6860
,08-16 17:15:04.131  4124  4124 D HidService: Received start request. Starting profile...
,08-16 17:15:04.131  4124  4124 I bt_bluedroid: get_profile_interface hidhost
08-16 17:15:04.131  4124  4124 D HidService: setHidService(): set to: null
08-16 17:15:04.131  4124  4140 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39ad3e5
08-16 17:15:04.132  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 17:15:04.132  4124  4124 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 17:15:04.132  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@70a6860
,08-16 17:15:04.133  4124  4124 D HealthService: Received start request. Starting profile...
,08-16 17:15:04.134  4124  4124 I bt_bluedroid: get_profile_interface health
,08-16 17:15:04.136  4124  4124 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 17:15:04.136  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@70a6860
,08-16 17:15:04.137  4124  4124 D PanService: Received start request. Starting profile...
,08-16 17:15:04.138  4124  4124 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 17:15:04.138  4124  4124 I bt_bluedroid: get_profile_interface pan
,08-16 17:15:04.138  3899  3899 D BluetoothInputDevice: Proxy object connected
08-16 17:15:04.138  3899  3899 D HidProfile: Bluetooth service connected
,08-16 17:15:04.139  1493  1493 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:15:04.140  4124  4124 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@70a6860
08-16 17:15:04.140  4124  4140 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 17:15:04.141  4124  4124 D BluetoothMapService: Received start request. Starting profile...
,08-16 17:15:04.141  3899  3899 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 17:15:04.141  4124  4124 D BluetoothMapService: start()
08-16 17:15:04.142  3899  3899 D PanProfile: Bluetooth service connected
,08-16 17:15:04.142  3899  3899 D BluetoothMap: Proxy object connected
08-16 17:15:04.142  3899  3899 D MapProfile: Bluetooth service connected
08-16 17:15:04.142  3899  3899 D BluetoothMap: getConnectedDevices()
,08-16 17:15:04.143  3899  3899 D BluetoothMap: Bluetooth is Not enabled
08-16 17:15:04.143  4124  4124 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-16 17:15:04.144  4124  4124 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-16 17:15:04.144  4124  4124 D BluetoothMapAppObserver: createReceiver()
08-16 17:15:04.145  4124  4124 D BluetoothMapAppObserver: initObservers()
,08-16 17:15:04.145  4124  4124 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 17:15:04.153  4124  4154 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-16 17:15:04.153  4124  4124 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:15:04.153  4124  4124 V BluetoothAdapterState: isTurningOn()=true
08-16 17:15:04.153  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 17:15:04.153  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:15:04.155  4124  4124 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:15:04.155  4124  4124 V BluetoothAdapterState: isTurningOn()=true
,08-16 17:15:04.155  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 17:15:04.155  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:15:04.155  4124  4124 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:15:04.155  4124  4124 V BluetoothAdapterState: isTurningOn()=true
08-16 17:15:04.155  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:15:04.155  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:15:04.155  4124  4124 V BluetoothAdapterState: isTurningOff()=false
08-16 17:15:04.156  4124  4124 V BluetoothAdapterState: isTurningOn()=true
08-16 17:15:04.156  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 17:15:04.156  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:15:04.156  4124  4124 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:15:04.156  4124  4124 V BluetoothAdapterState: isTurningOn()=true
,08-16 17:15:04.156  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:15:04.156  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:15:04.158  4124  4124 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:15:04.158  4124  4124 V BluetoothAdapterState: isTurningOn()=true
08-16 17:15:04.158  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:15:04.158  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:15:04.158  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 17:15:04.158  4124  4136 D BluetoothAdapterProperties: ScanMode =  20
08-16 17:15:04.158  4124  4136 D BluetoothAdapterProperties: State =  11
08-16 17:15:04.158  4124  4136 D BluetoothAdapterProperties: Setting state to 12
08-16 17:15:04.158  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 17:15:04.159  4124  4136 I BluetoothAdapterState: Entering OnState
08-16 17:15:04.159  4124  4140 D BluetoothAdapterProperties: Scan Mode:21
08-16 17:15:04.159  4124  4140 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 17:15:04.159  3899  3910 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 17:15:04.159   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 17:15:04.160  3899  3911 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 17:15:04.161   873   873 D BluetoothA2dp: Proxy object connected
08-16 17:15:04.162  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:15:04.162  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:15:04.162  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:15:04.162  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:15:04.162  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:15:04.162  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:15:04.162  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:15:04.162  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:15:04.163  1348  2036 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 17:15:04.164  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:15:04.164  3899  3910 D BluetoothPan: onBluetoothStateChange on: true
08-16 17:15:04.164  1348  1360 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 17:15:04.166  1348  1348 D BluetoothInputDevice: Proxy object connected
08-16 17:15:04.166  1348  1348 D HidProfile: Bluetooth service connected
08-16 17:15:04.166  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:15:04.166  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:15:04.166  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:15:04.166  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:15:04.166  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:15:04.166  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:15:04.166  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:15:04.166  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:15:04.167   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:15:04.167  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:15:04.168  1940  1952 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:15:04.168   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 17:15:04.169  1348  1359 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 17:15:04.170  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:15:04.170  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:15:04.170  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:15:04.170  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:15:04.170  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:15:04.170  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:15:04.170  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:15:04.170  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:15:04.170  1348  2029 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 17:15:04.170  1348  1348 D BluetoothA2dp: Proxy object connected
08-16 17:15:04.171  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:15:04.172  4124  4124 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 17:15:04.172  4124  4124 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 17:15:04.172   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:15:04.172  1348  1360 D BluetoothPan: onBluetoothStateChange on: true
08-16 17:15:04.173  4124  4124 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:15:04.174  1348  1348 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 17:15:04.174  1348  1348 D PanProfile: Bluetooth service connected
08-16 17:15:04.174  1348  2036 D BluetoothMap: onBluetoothStateChange: up=true
08-16 17:15:04.175  1348  1348 D BluetoothMap: Proxy object connected
08-16 17:15:04.175  1348  1348 D MapProfile: Bluetooth service connected
08-16 17:15:04.175  1348  1348 D BluetoothMap: getConnectedDevices()
08-16 17:15:04.175  3899  3911 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 17:15:04.175  4124  4124 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:15:04.177   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-16 17:15:04.178  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:15:04.178  4124  4124 D ObexServerSockets: Succeed to create listening sockets 
08-16 17:15:04.178  4124  4124 D ObexServerSockets0: startAccept()
08-16 17:15:04.178  4124  4124 D ObexServerSockets0: prepareForNewConnect()
08-16 17:15:04.179  4124  4124 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-16 17:15:04.180  4124  4124 D BluetoothSdpJni: SDP Create record success - handle: 0
08-16 17:15:04.180  4124  4161 D ObexServerSockets0: Accepting socket connection...
08-16 17:15:04.180  4124  4124 D BluetoothMapService: onReceive
08-16 17:15:04.180  4124  4124 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 17:15:04.180  4124  4124 D BluetoothMapService: STATE_ON
08-16 17:15:04.181  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:15:04.181  4124  4162 D ObexServerSockets0: Accepting socket connection...
08-16 17:15:04.181  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:15:04.182  3899  3899 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-16 17:15:04.186  3899  3899 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-16 17:15:04.190  3899  3899 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:15:04.192  3899  3899 D BluetoothA2dp: Proxy object connected
,08-16 17:15:04.194  1493  1493 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:15:04.199  3899  3899 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:15:04.200  3899  3899 D BluetoothPbap: Proxy object connected
,08-16 17:15:04.201  3899  3899 D PbapServerProfile: Bluetooth service connected
08-16 17:15:04.201  1348  1348 D BluetoothPbap: Proxy object connected
08-16 17:15:04.201  1348  1348 D PbapServerProfile: Bluetooth service connected
,08-16 17:15:04.205  4124  4124 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 17:15:04.205  4124  4124 D ObexServerSockets0: prepareForNewConnect()
,08-16 17:15:04.206  4124  4166 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:15:04.219  4124  4170 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:15:04.220  4124  4170 I BtOppRfcommListener: Accept thread started.
,08-16 17:15:04.265  1348  2036 D BluetoothHeadset: Proxy object connected
,08-16 17:15:04.265  1348  1348 D HeadsetProfile: Bluetooth service connected
08-16 17:15:04.266   873   873 D BluetoothHeadset: Proxy object connected
08-16 17:15:04.266   873   873 D BluetoothHeadset: Proxy object connected
08-16 17:15:04.266   873   873 D BluetoothHeadset: Proxy object connected
08-16 17:15:04.266  1940  1951 D BluetoothHeadset: Proxy object connected
,08-16 17:15:04.268   873   890 D BluetoothHeadset: Proxy object connected
,08-16 17:15:04.268  1940  2285 D BluetoothHeadset: Proxy object connected
,08-16 17:15:04.268   873   890 D BluetoothHeadset: Proxy object connected
,08-16 17:15:04.272   873   890 D BluetoothHeadset: Proxy object connected
,08-16 17:15:04.289  3899  3910 D BluetoothHeadset: Proxy object connected
,08-16 17:15:04.290  3899  3899 D HeadsetProfile: Bluetooth service connected
,08-16 17:15:07.608  4124  4136 D BluetoothAdapterState: Current state: ON, message: 23
,08-16 17:15:07.609  4124  4136 D BluetoothAdapterProperties: Setting state to 13
,08-16 17:15:07.609  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-16 17:15:07.611  4124  4136 D BluetoothAdapterProperties: onBluetoothDisable()
,08-16 17:15:07.619  4124  4136 I BluetoothAdapterState: Entering PendingCommandState
,08-16 17:15:07.621  4124  4124 D BluetoothMapService: onReceive
,08-16 17:15:07.621  4124  4124 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:15:07.626  4124  4124 D BluetoothMapService: STATE_TURNING_OFF
,08-16 17:15:07.627  4124  4124 D BluetoothMapService: MAP Service closeService in
,08-16 17:15:07.627  4124  4124 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 17:15:07.628  4124  4124 D ObexServerSockets0: shutdown(block = true)
08-16 17:15:07.629  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:15:07.629  4124  4161 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-16 17:15:07.630  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:15:07.630  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:15:07.630  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:15:07.630  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:15:07.630  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:15:07.630  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:15:07.630  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:15:07.630  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:15:07.633  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:15:07.633  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:15:07.634  4124  4140 D BluetoothAdapterProperties: Scan Mode:20
08-16 17:15:07.638  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-16 17:15:07.638  4124  4124 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-16 17:15:07.638  4124  4124 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 17:15:07.639  4124  4162 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-16 17:15:07.640  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:15:07.640  4124  4124 I BtOppRfcommListener: stopping Accept Thread
08-16 17:15:07.640  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:15:07.640  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:15:07.640  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:15:07.640  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:15:07.640  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:15:07.640  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:15:07.640  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:15:07.640  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:15:07.640  4124  4170 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 17:15:07.641  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:15:07.641  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:15:07.642  4124  4170 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 17:15:07.642  4124  4149 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-16 17:15:07.644  4124  4124 D HeadsetService: Received stop request...Stopping profile...
08-16 17:15:07.645  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 17:15:07.645  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:15:07.645  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:15:07.645  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:15:07.645  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:15:07.645  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 17:15:07.645  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:15:07.645  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:15:07.645  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:15:07.646  1348  1360 D BluetoothHeadset: Proxy object disconnected
,08-16 17:15:07.647  3804  3804 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 17:15:07.647  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:15:07.648  4124  4124 D A2dpService: Received stop request...Stopping profile...
08-16 17:15:07.648  4124  4156 D A2dpStateMachine: Exit Disconnected: -1
,08-16 17:15:07.647   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 17:15:07.653  4124  4124 D HidService: Received stop request...Stopping profile...
,08-16 17:15:07.655   873   873 D BluetoothHeadset: Proxy object disconnected
,08-16 17:15:07.655  4124  4124 D HidService: Stopping Bluetooth HidService
08-16 17:15:07.655   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 17:15:07.655  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:15:07.655  3899  3910 D BluetoothHeadset: Proxy object disconnected
08-16 17:15:07.656  1940  2097 D BluetoothHeadset: Proxy object disconnected
,08-16 17:15:07.656  1348  1348 D HeadsetProfile: Bluetooth service disconnected
08-16 17:15:07.656   873   873 D BluetoothA2dp: Proxy object disconnected
,08-16 17:15:07.656  1348  1348 D BluetoothA2dp: Proxy object disconnected
08-16 17:15:07.657  1348  1348 D BluetoothInputDevice: Proxy object disconnected
08-16 17:15:07.651  3899  3899 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 17:15:07.657  1348  1348 D HidProfile: Bluetooth service disconnected
08-16 17:15:07.657  4124  4124 D HealthService: Received stop request...Stopping profile...
08-16 17:15:07.657  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:15:07.658  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:15:07.660  3899  3899 D BluetoothA2dp: Proxy object disconnected
08-16 17:15:07.660  3899  3899 D HeadsetProfile: Bluetooth service disconnected
08-16 17:15:07.661  3899  3899 D BluetoothInputDevice: Proxy object disconnected
08-16 17:15:07.661  3899  3899 D HidProfile: Bluetooth service disconnected
,08-16 17:15:07.661  4124  4124 V BluetoothAdapterState: isTurningOff()=true
,08-16 17:15:07.661  4124  4124 V BluetoothAdapterState: isTurningOn()=false
,08-16 17:15:07.661  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:15:07.661  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:15:07.663  4124  4124 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-16 17:15:07.663  4124  4124 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 17:15:07.663  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 17:15:07.663  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 17:15:07.664  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:15:07.664  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:15:07.664  4124  4140 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-16 17:15:07.664  4124  4124 D PanService: Received stop request...Stopping profile...
,08-16 17:15:07.666  1348  1348 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-16 17:15:07.666  1348  1348 D PanProfile: Bluetooth service disconnected
08-16 17:15:07.666  4124  4124 D BluetoothMapService: Received stop request...Stopping profile...
08-16 17:15:07.666  4124  4124 D BluetoothMapService: stop()
,08-16 17:15:07.667  3899  3899 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:15:07.667  4124  4124 D BluetoothMapAppObserver: deinitObservers()
,08-16 17:15:07.667  4124  4124 D BluetoothMapAppObserver: removeReceiver()
08-16 17:15:07.669  1348  1348 D BluetoothMap: Proxy object disconnected
08-16 17:15:07.669  1348  1348 D MapProfile: Bluetooth service disconnected
08-16 17:15:07.670  4124  4124 V BluetoothAdapterState: isTurningOff()=true
08-16 17:15:07.670  4124  4124 V BluetoothAdapterState: isTurningOn()=false
08-16 17:15:07.670  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:15:07.671  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:15:07.671  3899  3899 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 17:15:07.672  3899  3899 D PanProfile: Bluetooth service disconnected
08-16 17:15:07.672  3899  3899 D BluetoothMap: Proxy object disconnected
08-16 17:15:07.672  3899  3899 D MapProfile: Bluetooth service disconnected
08-16 17:15:07.672  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-16 17:15:07.673  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:15:07.673  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:15:07.673  4124  4146 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:15:07.673  4124  4146 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:15:07.673  4124  4146 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 17:15:07.673  4124  4146 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 17:15:07.673  4124  4124 V BluetoothAdapterState: isTurningOff()=true
08-16 17:15:07.673  4124  4124 V BluetoothAdapterState: isTurningOn()=false
08-16 17:15:07.674  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:15:07.674  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:15:07.674  4124  4124 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 17:15:07.674  4124  4140 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 17:15:07.674  4124  4124 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 17:15:07.675  4124  4124 V BluetoothAdapterState: isTurningOff()=true
08-16 17:15:07.675  4124  4124 V BluetoothAdapterState: isTurningOn()=false
08-16 17:15:07.675  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:15:07.675  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:15:07.675  4124  4124 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 17:15:07.675  4124  4140 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 17:15:07.675  4124  4124 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 17:15:07.679  4124  4124 V BluetoothAdapterState: isTurningOff()=true
08-16 17:15:07.679  4124  4124 V BluetoothAdapterState: isTurningOn()=false
08-16 17:15:07.679  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:15:07.679  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:15:07.679  1493  1493 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 17:15:07.679  4124  4124 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 17:15:07.679  4124  4124 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 17:15:07.680  4124  4124 D BluetoothMapService: MAP Service closeService in
08-16 17:15:07.680  4124  4124 V BluetoothAdapterState: isTurningOff()=true
08-16 17:15:07.680  4124  4124 V BluetoothAdapterState: isTurningOn()=false
08-16 17:15:07.680  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:15:07.680  4124  4124 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:15:07.681  4124  4136 D BluetoothAdapterState: Current state:, PENDING_COMMAND, message: 26
08-16 17:15:07.681  4124  4136 D BluetoothAdapterProperties: Setting state to 15
08-16 17:15:07.681  4124  4124 D BluetoothMapService: cleanup()
08-16 17:15:07.681  4124  4124 D BluetoothMapService: MAP Service closeService in
08-16 17:15:07.681  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 17:15:07.682  4124  4136 I BluetoothAdapterState: Entering BleOnState
08-16 17:15:07.683  1348  1348 D BluetoothPbap: Proxy object disconnected
08-16 17:15:07.683  3899  3911 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 17:15:07.683  1348  1348 D PbapServerProfile: Bluetooth service disconnected
08-16 17:15:07.683  3899  3899 D BluetoothPbap: Proxy object disconnected
08-16 17:15:07.683   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:15:07.683  3899  3899 D PbapServerProfile: Bluetooth service disconnected
08-16 17:15:07.684  3899  3910 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 17:15:07.686  1348  1359 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:15:07.686  3899  3911 D BluetoothPan: onBluetoothStateChange on: false
08-16 17:15:07.687  1348  2029 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 17:15:07.688   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:15:07.688  1940  2284 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:15:07.688   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:15:07.688  3899  3910 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:15:07.689  1348  1360 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 17:15:07.689  1348  2036 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 17:15:07.690   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:15:07.690  1348  1359 D BluetoothPan: onBluetoothStateChange on: false
08-16 17:15:07.690  1348  2029 D BluetoothMap: onBluetoothStateChange: up=false
08-16 17:15:07.691  3899  3911 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 17:15:07.691  3899  3910 D BluetoothMap: onBluetoothStateChange: up=false
08-16 17:15:07.692  4124  4136 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 17:15:07.692  4124  4136 D BluetoothAdapterProperties: Setting state to 16
08-16 17:15:07.692  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 17:15:07.693  4124  4136 D BluetoothAdapterProperties: onBleDisable
08-16 17:15:07.694  4124  4136 I BluetoothAdapterState: Entering PendingCommandState
08-16 17:15:07.694  4124  4137 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-16 17:15:07.695  4124  4146 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 17:15:07.695  4124  4146 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 17:15:07.696  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:15:07.697  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:15:07.697  4124  4140 D BluetoothAdapterProperties: Scan Mode:20
08-16 17:15:07.699  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:15:07.700  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:15:07.701  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:15:07.702  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:15:07.704  3899  3899 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:15:07.709  1493  1493 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:15:07.710  3899  3899 D DockEventReceiver: finishStartingService: stopping service
,08-16 17:15:07.899  4124  4140 I bt_hci  : shut_down
,08-16 17:15:07.911  4124  4144 I bt_vendor: low_power_mode_cb
,08-16 17:15:07.911  4124  4144 D bt_hwcfg: hw_epilog_process
,08-16 17:15:07.929  4124  4144 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 17:15:07.929  4124  4144 I bt_vendor: epilog_cb
08-16 17:15:07.930  4124  4144 I bt_hci  : epilog_finished_callback
,08-16 17:15:07.937  4124  4140 I bt_hci_h4: hal_close
,08-16 17:15:07.938  4124  4140 I bt_userial_vendor: device fd = 51 close
,08-16 17:15:08.065  4124  4137 D bt_stack_manager: event_shut_down_stack finished.
,08-16 17:15:08.065  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 17:15:08.072  4124  4124 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 17:15:08.073  4124  4136 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 17:15:08.073  4124  4124 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 17:15:08.074  4124  4124 D BtGatt.GattService: stop()
08-16 17:15:08.074  4124  4124 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 17:15:08.079  4124  4124 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:15:08.080  4124  4124 V BluetoothAdapterState: isTurningOn()=false
,08-16 17:15:08.080  4124  4124 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 17:15:08.081  4124  4124 V BluetoothAdapterState: isBleTurningOff()=true
08-16 17:15:08.083  4124  4136 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-16 17:15:08.084  4124  4136 D BluetoothAdapterProperties: Setting state to 10
,08-16 17:15:08.085  4124  4136 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-16 17:15:08.086  4124  4136 I BluetoothAdapterState: Entering OffState
,08-16 17:15:08.088   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-16 17:15:08.108  4124  4124 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-16 17:15:08.108  4124  4124 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 17:15:08.109  4124  4124 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 17:15:08.111  4124  4137 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 17:15:08.118  4124  4137 D bt_stack_manager: event_clean_up_stack finished.
,08-16 17:15:08.123  4124  4124 I art     : System.exit called, status: 0
,08-16 17:15:08.124  4124  4124 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 17:15:08.183   873  1686 I ActivityManager: Process com.android.bluetooth (pid 4124) has died
,08-16 17:15:12.605  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:15:12.606  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:15:12.612  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:15:12.612  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6dfabbe removed from the list
,08-16 17:15:12.613  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:15:12.613  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:15:12.613  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:15:12.616  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:15:12.616  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d25d36c added. We now have 4 listener(s)
,08-16 17:15:12.617  3804  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:15:12.619  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:15:12.619  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d25d36c removed from the list
08-16 17:15:12.619  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:15:12.620  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:15:12.620  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:15:12.622  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:15:12.622  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10e1d35 added. We now have 4 listener(s)
08-16 17:15:12.623  3804  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:15:17.634  3804  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:15:17.681   873   890 I ActivityManager: Start proc 4180:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 17:15:17.810  4180  4180 D AdapterServiceConfig: Adding HeadsetService
,08-16 17:15:17.811  4180  4180 D AdapterServiceConfig: Adding A2dpService
,08-16 17:15:17.811  4180  4180 D AdapterServiceConfig: Adding HidService
08-16 17:15:17.811  4180  4180 D AdapterServiceConfig: Adding HealthService
08-16 17:15:17.811  4180  4180 D AdapterServiceConfig: Adding PanService,
08-16 17:15:17.811  4180  4180 D AdapterServiceConfig: Adding GattService
08-16 17:15:17.812  4180  4180 D AdapterServiceConfig: Adding BluetoothMapService,
,08-16 17:15:17.826  4180  4180 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 17:15:17.826   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c61b4a4:true
,08-16 17:15:17.831  4180  4180 I bt_bluedroid: init
,08-16 17:15:17.832  4180  4192 I BluetoothAdapterState: Entering OffState
,08-16 17:15:17.838  4180  4193 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 17:15:17.838  4180  4193 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 17:15:17.839  4180  4193 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-16 17:15:17.839  4180  4193 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 17:15:17.841  4180  4180 I bt_bluedroid: get_profile_interface socket
,08-16 17:15:17.845  4180  4196 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 17:15:17.848  4180  4180 I bt_bluedroid: get_profile_interface sdp
08-16 17:15:17.848  4180  4196 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 17:15:17.855  4180  4191 I bt_bluedroid: config_hci_snoop_log
,08-16 17:15:17.858   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 17:15:17.870  4180  4192 D BluetoothAdapterState: Current state: OFF, message: 0
08-16 17:15:17.871  4180  4192 D BluetoothAdapterProperties: Setting state to 14
,08-16 17:15:17.871  4180  4192 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 17:15:17.875  4180  4192 D BluetoothBondStateMachine: make
,08-16 17:15:17.880  4180  4197 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 17:15:17.886  4180  4192 I BluetoothAdapterState: Entering PendingCommandState
,08-16 17:15:17.889  4180  4180 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 17:15:17.895  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@70a6860
,08-16 17:15:17.897  4180  4180 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 17:15:17.899  4180  4180 D BtGatt.GattService: Received start request. Starting profile...
08-16 17:15:17.899  4180  4180 D BtGatt.GattService: start()
08-16 17:15:17.899  4180  4180 I bt_bluedroid: get_profile_interface gatt
08-16 17:15:17.901  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@70a6860
,08-16 17:15:17.901  4180  4180 D BtGatt.AdvertiseManager: advertise manager created
,08-16 17:15:17.917  4180  4180 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:15:17.917  4180  4180 V BluetoothAdapterState: isTurningOn()=false
,08-16 17:15:17.917  4180  4180 V BluetoothAdapterState: isBleTurningOn()=true
08-16 17:15:17.917  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:15:17.918  4180  4192 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-16 17:15:17.919  4180  4192 I bt_bluedroid: enable
08-16 17:15:17.919  4180  4193 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-16 17:15:17.920  4180  4193 I bt_hci  : start_up
,08-16 17:15:17.937  4180  4193 I bt_vendor: alloc value 0xb3a4e189
,08-16 17:15:17.937  4180  4193 I bt_vendor: init
08-16 17:15:17.937  4180  4193 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-16 17:15:17.937  4180  4193 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 17:15:18.046  4180  4193 D bt_hci  : start_up starting async portion
,08-16 17:15:18.047  4180  4200 I bt_hci  : event_finish_startup
08-16 17:15:18.047  4180  4200 I bt_hci_h4: hal_open
08-16 17:15:18.048  4180  4200 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 17:15:18.056  4180  4200 I bt_userial_vendor: device fd = 51 open
,08-16 17:15:18.089  4180  4200 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 17:15:18.121  4180  4200 D bt_hwcfg: Chipset BCM4354A2
08-16 17:15:18.121  4180  4200 D bt_hwcfg: Target name = [BCM4354A2]
,08-16 17:15:18.122  4180  4200 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 17:15:18.958  4180  4200 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 17:15:18.960  4180  4200 D bt_hwcfg: Settlement delay -- 100 ms
,08-16 17:15:18.961  4180  4200 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 17:15:19.079  4180  4200 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 17:15:19.080  4180  4200 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 17:15:19.108  4180  4200 I bt_hwcfg: vendor lib fwcfg completed
,08-16 17:15:19.108  4180  4200 I bt_vendor: firmware callback
08-16 17:15:19.108  4180  4200 I bt_hci  : firmware_config_callback
,08-16 17:15:19.122  4180  4202 I bt_btu  : btu_task pending for preload complete event
,08-16 17:15:19.122  4180  4202 I bt_btu_task: Bluetooth chip preload is complete
08-16 17:15:19.122  4180  4202 I bt_btu  : btu_task received preload complete event
,08-16 17:15:19.132  4180  4202 I         : BTE_InitTraceLevels -- TRC_HCI
,08-16 17:15:19.132  4180  4202 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 17:15:19.133  4180  4202 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 17:15:19.133  4180  4202 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 17:15:19.133  4180  4202 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 17:15:19.134  4180  4202 I         : BTE_InitTraceLevels -- TRC_A2D
,08-16 17:15:19.134  4180  4202 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-16 17:15:19.134  4180  4202 I         : BTE_InitTraceLevels -- TRC_BTM
,08-16 17:15:19.134  4180  4202 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 17:15:19.135  4180  4202 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 17:15:19.135  4180  4202 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 17:15:19.135  4180  4202 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 17:15:19.135  4180  4202 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 17:15:19.136  4180  4202 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 17:15:19.136  4180  4202 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 17:15:19.288  4180  4202 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39cbd9d
,08-16 17:15:19.288  4180  4202 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39cbd9d 
,08-16 17:15:19.301  4180  4196 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
08-16 17:15:19.303  4180  4196 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 17:15:19.304  4180  4196 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-16 17:15:19.308  4180  4196 D BluetoothAdapterProperties: Name is: Nexus 6
08-16 17:15:19.311  4180  4196 D BluetoothAdapterProperties: Scan Mode:20
,08-16 17:15:19.311  4180  4196 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 17:15:19.312  4180  4196 D bt_hci  : do_postload posting postload work item
,08-16 17:15:19.313  4180  4200 I bt_hci  : event_postload
,08-16 17:15:19.314  4180  4200 I bt_vendor: sco_config_cb
,08-16 17:15:19.314  4180  4200 I bt_hci  : sco_config_callback postload finished.
,08-16 17:15:19.317  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:15:19.317  4180  4196 D bt_bte_conf: Device ID record 1 : primary
,08-16 17:15:19.317  4180  4196 D bt_bte_conf:   vendorId            = 000f
,08-16 17:15:19.318  4180  4196 D bt_bte_conf:   vendorIdSource      = 0001,
,08-16 17:15:19.318  4180  4196 D bt_bte_conf:   product             = 1200
,08-16 17:15:19.318  4180  4196 D bt_bte_conf:   version             = 1436
,08-16 17:15:19.318  4180  4196 D bt_bte_conf:   clientExecutableURL = ,
08-16 17:15:19.319  4180  4196 D bt_bte_conf:   serviceDescription  = 
,08-16 17:15:19.319  4180  4196 D bt_bte_conf:   documentationURL    = 
08-16 17:15:19.319  4180  4196 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-16 17:15:19.320  4180  4193 D bt_stack_manager: event_start_up_stack finished,
08-16 17:15:19.321  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-16 17:15:19.322  4180  4200 I bt_vendor: low_power_mode_cb
08-16 17:15:19.322  4180  4192 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-16 17:15:19.323  4180  4192 D BluetoothAdapterProperties: Setting state to 15
08-16 17:15:19.323  4180  4192 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-16 17:15:19.324  4180  4192 I BluetoothAdapterState: Entering BleOnState
,08-16 17:15:19.332  4180  4192 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-16 17:15:19.332  4180  4192 D BluetoothAdapterProperties: Setting state to 11
,08-16 17:15:19.332  4180  4192 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-16 17:15:19.337  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@70a6860
,08-16 17:15:19.338  4180  4180 D HeadsetService: Received start request. Starting profile...
,08-16 17:15:19.341  4180  4180 I BluetoothHeadsetServiceJni: classInitNative: succeeds,
08-16 17:15:19.341  4180  4180 D HeadsetStateMachine: make
,08-16 17:15:19.355  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:15:19.356  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:15:19.358  4180  4180 D HeadsetStateMachine: max_hf_connections = 1
08-16 17:15:19.358  4180  4180 I bt_bluedroid: get_profile_interface handsfree
08-16 17:15:19.359  4180  4196 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-16 17:15:19.359  4180  4196 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-16 17:15:19.361  4180  4192 I BluetoothAdapterState: Entering PendingCommandState
,08-16 17:15:19.364  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@70a6860
,08-16 17:15:19.365  4180  4180 D A2dpService: Received start request. Starting profile...
,08-16 17:15:19.366  4180  4180 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 17:15:19.366  4180  4180 I bt_bluedroid: get_profile_interface avrcp
,08-16 17:15:19.372  4180  4180 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 17:15:19.372  4180  4180 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 17:15:19.372  4180  4180 D A2dpStateMachine: make
,08-16 17:15:19.374  4180  4180 I bt_bluedroid: get_profile_interface a2dp
,08-16 17:15:19.375  4180  4196 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 17:15:19.376  4180  4211 D A2dpStateMachine: Enter Disconnected: -2
,08-16 17:15:19.377  4180  4180 I BluetoothHidServiceJni: classInitNative: succeeds
,08-16 17:15:19.378  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@70a6860
,08-16 17:15:19.378  4180  4180 D HidService: Received start request. Starting profile...
08-16 17:15:19.378  4180  4180 I bt_bluedroid: get_profile_interface hidhost
08-16 17:15:19.379  4180  4180 D HidService: setHidService(): set to: null
,08-16 17:15:19.379  4180  4196 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39ad3e5
08-16 17:15:19.379  4180  4196 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-16 17:15:19.379  4180  4180 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-16 17:15:19.380  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@70a6860
08-16 17:15:19.381  4180  4180 D HealthService: Received start request. Starting profile...
,08-16 17:15:19.382  4180  4180 I bt_bluedroid: get_profile_interface health
,08-16 17:15:19.383  4180  4180 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 17:15:19.384  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@70a6860
,08-16 17:15:19.386  4180  4180 D PanService: Received start request. Starting profile...
,08-16 17:15:19.386  4180  4180 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-16 17:15:19.386  4180  4180 I bt_bluedroid: get_profile_interface pan
,08-16 17:15:19.387  4180  4196 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 17:15:19.390  4180  4180 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@70a6860
,08-16 17:15:19.390  4180  4180 D BluetoothMapService: Received start request. Starting profile...
,08-16 17:15:19.390  4180  4180 D BluetoothMapService: start()
,08-16 17:15:19.393  4180  4180 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 17:15:19.394  4180  4180 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-16 17:15:19.394  4180  4180 D BluetoothMapAppObserver: createReceiver()
,08-16 17:15:19.395  4180  4180 D BluetoothMapAppObserver: initObservers()
,08-16 17:15:19.395  4180  4180 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 17:15:19.402  4180  4180 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:15:19.402  4180  4180 V BluetoothAdapterState: isTurningOn()=true
08-16 17:15:19.402  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:15:19.402  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 17:15:19.404  1493  1493 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:15:19.405  4180  4180 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:15:19.405  4180  4180 V BluetoothAdapterState: isTurningOn()=true
08-16 17:15:19.405  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:15:19.405  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:15:19.405  4180  4180 V BluetoothAdapterState: isTurningOff()=false
08-16 17:15:19.405  4180  4180 V BluetoothAdapterState: isTurningOn()=true
,08-16 17:15:19.405  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:15:19.405  4180  4207 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 17:15:19.405  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:15:19.406  4180  4180 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:15:19.406  4180  4180 V BluetoothAdapterState: isTurningOn()=true
08-16 17:15:19.406  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:15:19.406  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:15:19.406  4180  4180 V BluetoothAdapterState: isTurningOff()=false
08-16 17:15:19.406  4180  4180 V BluetoothAdapterState: isTurningOn()=true
08-16 17:15:19.406  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:15:19.406  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:15:19.406  4180  4180 V BluetoothAdapterState: isTurningOff()=false
,08-16 17:15:19.407  4180  4180 V BluetoothAdapterState: isTurningOn()=true
08-16 17:15:19.407  4180  4180 V BluetoothAdapterState: isBleTurningOn()=false
08-16 17:15:19.407  4180  4180 V BluetoothAdapterState: isBleTurningOff()=false
08-16 17:15:19.407  4180  4192 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 17:15:19.407  4180  4192 D BluetoothAdapterProperties: ScanMode =  20
08-16 17:15:19.407  4180  4192 D BluetoothAdapterProperties: State =  11
,08-16 17:15:19.408  4180  4192 D BluetoothAdapterProperties: Setting state to 12
08-16 17:15:19.408  4180  4192 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 17:15:19.409  3899  3911 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 17:15:19.410  4180  4192 I BluetoothAdapterState: Entering OnState
,08-16 17:15:19.410  4180  4196 D BluetoothAdapterProperties: Scan Mode:21
,08-16 17:15:19.410  4180  4196 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 17:15:19.413  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:15:19.413  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:15:19.413  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:15:19.413  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:15:19.413  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:15:19.413  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:15:19.413  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:15:19.413  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 17:15:19.413   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 17:15:19.414  3899  3910 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 17:15:19.414  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:15:19.415   873   873 D BluetoothA2dp: Proxy object connected
,08-16 17:15:19.417  1348  1360 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:15:19.417  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:15:19.417  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:15:19.417  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:15:19.417  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:15:19.417  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:15:19.417  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:15:19.417  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:15:19.417  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:15:19.418  3899  3911 D BluetoothPan: onBluetoothStateChange on: true
,08-16 17:15:19.419  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:15:19.419  1348  2036 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 17:15:19.420  3899  3899 D BluetoothInputDevice: Proxy object connected
08-16 17:15:19.420  3899  3899 D HidProfile: Bluetooth service connected
08-16 17:15:19.421  1348  1348 D BluetoothInputDevice: Proxy object connected
,08-16 17:15:19.421   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:15:19.421  1348  1348 D HidProfile: Bluetooth service connected
08-16 17:15:19.421  1940  2284 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 17:15:19.421  4180  4180 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 17:15:19.422   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:15:19.422  4180  4180 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 17:15:19.422  3899  3911 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 17:15:19.423  4180  4180 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:15:19.425  1348  2029 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 17:15:19.425  3899  3899 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 17:15:19.425  3899  3899 D PanProfile: Bluetooth service connected
,08-16 17:15:19.425  3899  3899 D BluetoothA2dp: Proxy object connected
08-16 17:15:19.425  4180  4180 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:15:19.426  1348  1348 D BluetoothA2dp: Proxy object connected
08-16 17:15:19.426  1348  1359 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 17:15:19.426  4180  4180 D ObexServerSockets: Succeed to create listening sockets 
,08-16 17:15:19.427  4180  4180 D ObexServerSockets0: startAccept()
,08-16 17:15:19.427  4180  4180 D ObexServerSockets0: prepareForNewConnect()
,08-16 17:15:19.427   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 17:15:19.428  1348  2036 D BluetoothPan: onBluetoothStateChange on: true
08-16 17:15:19.428  4180  4180 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-16 17:15:19.428  4180  4180 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-16 17:15:19.429  4180  4219 D ObexServerSockets0: Accepting socket connection...
08-16 17:15:19.429  1348  1348 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 17:15:19.429  1348  1348 D PanProfile: Bluetooth service connected
08-16 17:15:19.430  1348  1360 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 17:15:19.430  4180  4220 D ObexServerSockets0: Accepting socket connection...
,08-16 17:15:19.431  3899  4217 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 17:15:19.432  1348  1348 D BluetoothMap: Proxy object connected
,08-16 17:15:19.432  1348  1348 D MapProfile: Bluetooth service connected
08-16 17:15:19.432  1348  1348 D BluetoothMap: getConnectedDevices()
,08-16 17:15:19.432  3899  3910 D BluetoothMap: onBluetoothStateChange: up=true
08-16 17:15:19.434  3899  3899 D BluetoothMap: Proxy object connected
,08-16 17:15:19.434  3899  3899 D MapProfile: Bluetooth service connected
,08-16 17:15:19.434  3899  3899 D BluetoothMap: getConnectedDevices()
08-16 17:15:19.436  4180  4180 D BluetoothMapService: onReceive
,08-16 17:15:19.436  4180  4180 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 17:15:19.436  4180  4180 D BluetoothMapService: STATE_ON
,08-16 17:15:19.437   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 17:15:19.437  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:15:19.440  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:15:19.444  3899  3899 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 17:15:19.450  1493  1493 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 17:15:19.459  3899  3899 D DockEventReceiver: finishStartingService: stopping service
08-16 17:15:19.459  3899  3899 D BluetoothPbap: Proxy object connected
08-16 17:15:19.459  3899  3899 D PbapServerProfile: Bluetooth service connected
08-16 17:15:19.461  4180  4180 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 17:15:19.461  4180  4180 D ObexServerSockets0: prepareForNewConnect()
08-16 17:15:19.462  4180  4227 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:15:19.465  1348  1348 D BluetoothPbap: Proxy object connected
,08-16 17:15:19.465  1348  1348 D PbapServerProfile: Bluetooth service connected
,08-16 17:15:19.476  4180  4231 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 17:15:19.477  4180  4231 I BtOppRfcommListener: Accept thread started.
,08-16 17:15:19.519  1348  1359 D BluetoothHeadset: Proxy object connected
,08-16 17:15:19.519  1348  1348 D HeadsetProfile: Bluetooth service connected
08-16 17:15:19.519   873   873 D BluetoothHeadset: Proxy object connected
,08-16 17:15:19.519   873   873 D BluetoothHeadset: Proxy object connected
,08-16 17:15:19.519   873   873 D BluetoothHeadset: Proxy object connected
08-16 17:15:19.519  3899  4217 D BluetoothHeadset: Proxy object connected
08-16 17:15:19.520  3899  3899 D HeadsetProfile: Bluetooth service connected
,08-16 17:15:19.520  1940  1952 D BluetoothHeadset: Proxy object connected
,08-16 17:15:19.521   873   890 D BluetoothHeadset: Proxy object connected
08-16 17:15:19.521  1940  1951 D BluetoothHeadset: Proxy object connected
,08-16 17:15:19.522   873   890 D BluetoothHeadset: Proxy object connected
,08-16 17:15:19.527   873   890 D BluetoothHeadset: Proxy object connected
,08-16 17:15:19.531  3899  3911 D BluetoothHeadset: Proxy object connected
,08-16 17:15:19.531  3899  3899 D HeadsetProfile: Bluetooth service connected
,08-16 17:15:22.653  3804  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:15:22.653  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:15:22.653  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:15:22.653  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 17:15:22.653  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:15:22.653  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:15:22.653  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:15:22.653  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:15:22.660  3804  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:15:22.661  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:15:22.661  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10e1d35 removed from the list
08-16 17:15:22.662  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:15:22.662  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:15:22.662  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:15:22.665  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:15:22.665  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@be6c5ca added. We now have 4 listener(s)
08-16 17:15:22.665  3804  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:15:22.670   873  1374 D WifiService: setWifiEnabled: false pid=3804, uid=10000
,08-16 17:15:22.670   873  1374 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 17:15:24.992  1861  1912 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-16 17:15:24.992  1861  1912 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-16 17:15:25.041  1493  1493 I ConfigService: onCreate
,08-16 17:15:27.682  3804  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:15:27.683   873  1687 D WifiService: setWifiEnabled: true pid=3804, uid=10000
08-16 17:15:27.683   873  1687 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 17:15:27.696   873  1302 D WifiConfigStore: Loading config and enabling all networks 
,08-16 17:15:27.716  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:15:27.716  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:15:27.716  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:15:27.716  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:15:27.716  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:15:27.716  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:15:27.716  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:15:27.716  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:15:27.721  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 17:15:27.729  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:15:27.729  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:15:27.729  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:15:27.729  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:15:27.729  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:15:27.729  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 17:15:27.729  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 17:15:27.729  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 17:15:27.732   873  1302 D WifiConfigStore: loaded 0 passpoint configs
,08-16 17:15:27.733   873  1302 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-16 17:15:27.733   873  1302 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-16 17:15:27.734   873  1302 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 17:15:27.734  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 17:15:27.735   873  1302 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-16 17:15:27.735   873  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-16 17:15:27.735   873  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 17:15:27.757   370   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-16 17:15:27.757   873  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 17:15:27.758   370   871 D CommandListener: Setting iface cfg
,08-16 17:15:27.809   873  1301 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
,08-16 17:15:27.809   873  1301 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 17:15:27.817   873  1302 E native  : do suspend true
,08-16 17:15:27.831   873  1301 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 17:15:27.831   873  1301 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 17:15:27.846   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 17:15:29.231   873  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 17:15:29.349   873  1302 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.44 rxSuccessRate=9.75 delta 1000 -> 994
,08-16 17:15:29.351   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 17:15:29.351   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:15:29.368   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 17:15:29.435   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 17:15:29.440  1456  1456 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 17:15:29.881  1456  1456 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 17:15:29.927  1456  1456 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 17:15:29.928  1456  1456 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 17:15:29.934   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 17:15:29.942   873  1302 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 17:15:29.943   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 17:15:29.943   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 17:15:29.969   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 17:15:29.982   370   871 D CommandListener: Setting iface cfg
,08-16 17:15:29.983   873  1302 D WifiStateMachine: Start Dhcp Watchdog 3
,08-16 17:15:30.001   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 17:15:30.014   873  4240 D DhcpClient: Receive thread started
,08-16 17:15:30.096  1493  1493 I ConfigService: onDestroy
,08-16 17:15:30.108   873  1302 E native  : do suspend false
,08-16 17:15:30.136   873  2092 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 17:15:30.150   873  4240 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,08-16 17:15:30.151   873  2092 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,08-16 17:15:30.155   873  2092 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 17:15:30.171   873  4240 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 17:15:30.172   873  2092 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 17:15:30.177   370   871 D CommandListener: Setting iface cfg
,08-16 17:15:30.189   873  2092 D DhcpClient: Scheduling renewal in 86399s
08-16 17:15:30.189   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 17:15:30.193   873  1302 E native  : do suspend true
,08-16 17:15:30.210   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 17:15:30.213   873  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 17:15:30.214   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 17:15:30.223   873  1302 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 17:15:30.223   873  1306 D ConnectivityService: Adding iface wlan0 to network 102
,08-16 17:15:30.296   873  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 17:15:30.296   873  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-16 17:15:30.299   873  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-16 17:15:30.301   873  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-16 17:15:30.303   873  1306 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-16 17:15:30.320   873  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 17:15:30.325   873  1306 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-16 17:15:30.325   873  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-16 17:15:30.325   873  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-16 17:15:30.325   873  1306 D ConnectivityService:    accepting network in place of null
08-16 17:15:30.325   873  1302 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-16 17:15:30.326   873  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-16 17:15:30.328   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 17:15:30.370   873  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=215746, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 17:15:30.407   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:15:30.441   873  4238 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:80c::200e
,08-16 17:15:30.463   370   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 17:15:30.473   873  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-16 17:15:30.474   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:15:30.481   873  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-16 17:15:30.484   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 17:15:30.500  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:15:30.500  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:15:30.500  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:15:30.500  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:15:30.500  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:15:30.500  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:15:30.500  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:15:30.500  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:15:30.504  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:15:30.511  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:15:30.511  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:15:30.511  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:15:30.511  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:15:30.511  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:15:30.511  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:15:30.511  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:15:30.511  3804  3804 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:15:30.514  3804  3804 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:15:30.520  1691  1691 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 17:15:30.525  1691  1691 D SystemUpdateService: onCreate
,08-16 17:15:30.526   873  4238 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 15:15:30 GMT], X-Android-Received-Millis=[1471360530525], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471360530490]}
,08-16 17:15:30.527   873  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 17:15:30.527   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-16 17:15:30.527   873  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 17:15:30.528   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 17:15:30.533  1691  1691 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 17:15:30.556  1691  4251 I SystemUpdateService: active receiver: enabled
,08-16 17:15:30.559  1691  1691 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 17:15:30.568  1691  2505 I iu.UploadsManager: num queued entries: 0
,08-16 17:15:30.569  1691  2505 I iu.UploadsManager: num updated entries: 0
,08-16 17:15:30.570  1691  1691 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 17:15:30.571  1691  2505 I iu.SyncManager: NEXT; no task
08-16 17:15:30.571  1691  1691 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-16 17:15:30.572  1691  4251 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 17:15:30.574  1691  4251 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 17:15:30.574  1691  4251 I SystemUpdateService: now status is 0 (complete)
08-16 17:15:30.574  1691  4251 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 17:15:30.574  1691  4251 I SystemUpdateService: file has been verified
08-16 17:15:30.574  1691  4251 I SystemUpdateService: OTA package size = 12249756
,08-16 17:15:30.579  1691  4254 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-16 17:15:30.580  1691  4254 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 17:15:30.580  3979  3979 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 17:15:30.581  1691  4254 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 17:15:30.584  3979  3979 D SprintDMHelper: simOperator: 
,08-16 17:15:30.584  3979  3979 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 17:15:30.619  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:15:30.620  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:15:30.628  3736  4256 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 17:15:30.636  1691  4251 I SystemUpdateService: showing system update notification
,08-16 17:15:30.713  1691  1691 D SystemUpdateService: onDestroy
,08-16 17:15:30.717  3736  4261 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 17:15:30.732  1493  2081 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 17:15:30.732  1493  2081 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-16 17:15:30.732  1493  2081 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:15:30.732  1493  2081 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:15:30.755  1493  1505 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 17:15:30.755  1493  1505 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 17:15:30.755  1493  1505 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:15:30.755  1493  1505 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:15:30.760  3950  4257 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 17:15:30.767  3736  4261 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 17:15:30.767  3736  4256 E BooksSync: Soft error
08-16 17:15:30.767  3736  4256 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 17:15:30.767  3736  4256 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 17:15:30.768  3736  4256 E BooksSync: Sync error
08-16 17:15:30.768  3736  4256 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 17:15:30.768  3736  4256 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 17:15:30.769  3736  4256 I BooksSync: Finished books sync
,08-16 17:15:30.773   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 211297, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 17:15:30.775  1493  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-16 17:15:30.775  1493  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 17:15:30.775  1493  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:15:30.775  1493  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:15:30.788  1691  4254 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-16 17:15:31.474   873  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-16 17:15:32.337  3773  4264 V GoogleAuthProtoRequest: [320] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 17:15:32.368  1493  1505 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-16 17:15:32.368  1493  1505 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-16 17:15:32.368  1493  1505 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:15:32.369  1493  1505 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:15:32.389  3773  4264 W ExperimentUpdateService: [320] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-16 17:15:32.389  3773  4264 W ExperimentUpdateService: [320] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 17:15:32.389  3773  4264 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 17:15:32.389  3773  4264 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-16 17:15:32.389  3773  4264 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-16 17:15:32.389  3773  4264 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-16 17:15:32.389  3773  4264 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-16 17:15:32.389  3773  4264 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-16 17:15:32.389  3773  4264 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-16 17:15:32.389  3773  4264 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-16 17:15:32.389  3773  4264 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-16 17:15:32.389  3773  4264 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-16 17:15:32.706  3804  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 17:15:32.706  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:15:32.706  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:15:32.706  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:15:32.706  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:15:32.706  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:15:32.706  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:15:32.706  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:15:32.713  3804  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:15:32.714  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:15:32.714  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@be6c5ca removed from the list
,08-16 17:15:32.715  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:15:32.715  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:15:32.715  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:15:32.727  3804  4265 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-16 17:15:32.727  3804  4265 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 17:15:35.735  3804  4265 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-16 17:15:35.735  3804  4266 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-16 17:15:35.737  3804  4266 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-16 17:15:35.737  3804  4265 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-16 17:15:35.738  3804  4266 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 17:15:35.738  3804  4265 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 17:15:35.739  3804  4266 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 17:15:35.742  3804  4268 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 428, name: IncomingSocketThread/Sender)
,08-16 17:15:35.743  3804  4265 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 17:15:35.744  3804  4265 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-16 17:15:35.744  3804  4266 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-16 17:15:35.749  3804  4270 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: OutgoingSocketThread/Receiver)
,08-16 17:15:35.751  3804  4269 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 429, name: OutgoingSocketThread/Sender)
08-16 17:15:35.751  3804  4270 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 431, thread name: OutgoingSocketThread/Receiver)
,08-16 17:15:35.752  3804  4270 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 17:15:35.752  3804  4270 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 431, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 17:15:35.754  3804  4271 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 430, name: IncomingSocketThread/Receiver)
,08-16 17:15:35.756  3804  4271 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 430, thread name: IncomingSocketThread/Receiver)
08-16 17:15:35.756  3804  4271 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 17:15:35.757  3804  4271 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 430, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-16 17:15:38.333   873  1306 D ConnectivityService: handlePromptUnvalidated 102
,08-16 17:15:38.734  3804  3862 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 17:15:38.736  3804  3862 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 17:15:38.743  3804  3862 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a1daa8c Bundle[{}]
,08-16 17:15:38.745  3804  3862 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 17:15:38.745  3804  3862 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 17:15:38.747  3804  3862 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 17:15:38.749  3804  3862 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-16 17:15:38.750  3804  3862 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-16 17:15:38.751  3804  3862 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 17:15:38.763  3804  3862 I System.out: Running OutgoingSocketThread
,08-16 17:15:38.765  3804  4272 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-16 17:15:38.765  3804  4272 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 17:15:41.776  3804  4273 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-16 17:15:41.776  3804  4273 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-16 17:15:41.777  3804  4273 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 17:15:41.777  3804  4272 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-16 17:15:41.777  3804  4272 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 17:15:41.778  3804  4272 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 17:15:41.778  3804  4273 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 17:15:41.779  3804  4272 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 17:15:41.781  3804  4273 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-16 17:15:41.787  3804  4275 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 440, name: IncomingSocketThread/Sender)
,08-16 17:15:41.788  3804  4272 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-16 17:15:41.791  3804  4276 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 441, name: OutgoingSocketThread/Sender)
,08-16 17:15:41.798  3804  4277 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 442, name: IncomingSocketThread/Receiver)
,08-16 17:15:41.800  3804  4278 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 443, name: OutgoingSocketThread/Receiver)
,08-16 17:15:41.801  3804  4277 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 442, thread name: IncomingSocketThread/Receiver)
,08-16 17:15:41.802  3804  4277 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 17:15:41.803  3804  4278 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 443, thread name: OutgoingSocketThread/Receiver)
08-16 17:15:41.803  3804  4277 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 442, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 17:15:41.803  3804  4278 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 17:15:41.803  3804  4278 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 443, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-16 17:15:44.779  3804  3862 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 452)
,08-16 17:15:44.781  3804  3862 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-16 17:15:44.781  3804  3862 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 453)
,08-16 17:15:44.787  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 17:15:44.787  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c1f33b added. We now have 3 listener(s)
08-16 17:15:44.789  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 17:15:44.789  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:15:44.789  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:15:44.789  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:15:44.789  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@652ba58 added. We now have 4 listener(s)
08-16 17:15:44.789  3804  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:15:44.790  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:15:44.793  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:15:44.802  3804  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:15:44.802  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:15:44.802  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:15:44.802  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:15:44.802  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:15:44.802  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:15:44.802  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:15:44.802  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:15:44.806  3804  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:15:44.806  3804  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:15:44.807  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:15:44.807  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:15:44.807  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:15:44.807  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:15:44.807  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:15:44.807  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:15:44.808  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:15:44.808  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c1f33b removed from the list
08-16 17:15:44.808  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:15:44.808  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@652ba58 removed from the list
,08-16 17:15:44.813  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-16 17:15:44.813  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:15:44.814  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:15:44.815  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:15:44.815  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:15:44.816  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:15:44.817  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:15:44.817  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:15:44.817  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@652ba58 not in the list
08-16 17:15:44.817  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:15:44.817  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:15:44.818  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:15:44.818  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:15:44.818  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:15:44.818  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@652ba58 not in the list
08-16 17:15:44.818  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:15:44.819  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:15:44.819  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:15:44.819  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c1f33b not in the list
08-16 17:15:44.819  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:15:44.820  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b937496 added. We now have 3 listener(s)
08-16 17:15:44.821  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 17:15:44.821  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:15:44.822  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:15:44.822  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:15:44.822  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d528817 added. We now have 4 listener(s)
08-16 17:15:44.822  3804  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:15:44.822  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:15:44.822  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:15:44.825  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:15:44.830  3804  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:15:44.830  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:15:44.830  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:15:44.830  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:15:44.830  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:15:44.830  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:15:44.830  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:15:44.830  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:15:44.836  3804  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:15:44.836  3804  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:15:44.837  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 17:15:44.837  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 17:15:44.838  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:15:44.838  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:15:44.838  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:15:44.839  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:15:44.843  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:15:44.845  3804  3862 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 17:15:44.845  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:15:44.851  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:15:44.852  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 17:15:44.852  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:15:44.857  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 17:15:44.857  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 17:15:44.857  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:15:44.859  3804  3862 D BluetoothAdapter: STATE_ON
,08-16 17:15:44.864  4180  4209 D BtGatt.GattService: registerClient() - UUID=af633338-d345-461a-b25c-cb8242d89c80
,08-16 17:15:44.866  4180  4196 D BtGatt.GattService: onClientRegistered() - UUID=af633338-d345-461a-b25c-cb8242d89c80, clientIf=5
,08-16 17:15:44.868  3804  3815 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 17:15:44.869  4180  4222 D BtGatt.GattService: start scan with filters,
,08-16 17:15:44.880  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 17:15:44.880  4180  4199 D BtGatt.ScanManager: handling starting scan
08-16 17:15:44.880  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 17:15:44.880  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 17:15:44.880  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 17:15:44.883  4180  4199 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@70a6860
,08-16 17:15:44.890  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:15:44.890  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-16 17:15:44.890  3804  3804 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:15:44.895  4180  4196 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 17:15:44.895  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:15:44.896  4180  4199 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 17:15:44.896  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:15:44.906  3804  3862 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 17:15:44.906  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:15:44.907  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 17:15:44.908  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:15:44.908  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 17:15:44.908  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 17:15:44.908  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 17:15:44.908  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:15:44.908  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:15:44.908  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
08-16 17:15:44.908  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 17:15:44.909  4180  4196 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 17:15:44.909  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:15:44.909  3804  3862 D BluetoothAdapter: STATE_ON
,08-16 17:15:44.910  4180  4199 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:15:44.910  4180  4199 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 17:15:44.910  4180  4216 D BtGatt.GattService: stopScan() - queue size =1
08-16 17:15:44.913  4180  4209 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 17:15:44.913  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:15:44.913  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:15:44.913  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 17:15:44.913  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:15:44.913  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 17:15:44.915  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:15:44.915  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 17:15:44.915  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:15:44.915  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:15:44.916  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:15:44.917  3804  3804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:15:44.917  3804  3804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:15:44.918  3804  3804 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:15:44.928  4180  4196 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 17:15:44.928  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:15:44.935  4180  4196 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 17:15:44.936  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:15:44.946  4180  4196 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 17:15:44.946  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:15:44.947  4180  4199 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:15:44.956  4180  4196 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 17:15:44.956  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:15:44.956  4180  4199 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 17:15:44.965  4180  4196 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 17:15:44.965  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:15:45.419  3804  3804 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 17:15:45.420  3804  3804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:15:45.420  3804  3804 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 17:15:47.917  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:15:47.918  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:15:47.918  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:15:47.919  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:15:47.919  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:15:47.919  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 17:15:47.920  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:15:47.920  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b937496 removed from the list
08-16 17:15:47.920  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:15:47.921  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d528817 removed from the list
08-16 17:15:47.921  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:15:47.921  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:15:47.923  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:15:47.923  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:15:47.927  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:15:47.927  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:15:47.928  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:15:47.928  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d528817 not in the list
,08-16 17:15:47.928  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:15:47.929  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:15:47.932  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:15:47.932  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:15:47.932  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:15:47.933  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d528817 not in the list
08-16 17:15:47.933  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:15:47.933  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:15:47.934  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:15:47.935  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b937496 not in the list
08-16 17:15:47.935  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 17:15:47.935  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4127c70 added. We now have 3 listener(s)
08-16 17:15:47.938  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 17:15:47.938  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:15:47.938  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:15:47.938  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 17:15:47.938  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c694be9 added. We now have 4 listener(s)
08-16 17:15:47.938  3804  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:15:47.939  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:15:47.941  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:15:47.947  3804  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:15:47.947  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:15:47.947  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:15:47.947  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:15:47.947  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:15:47.947  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:15:47.947  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:15:47.947  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:15:47.949  3804  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:15:47.950  3804  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:15:47.951  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-16 17:15:47.952  3804  3862 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
,08-16 17:15:47.952  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-16 17:15:47.953  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:15:47.955  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:15:47.957  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 17:15:47.957  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-16 17:15:47.957  3804  3862 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,08-16 17:15:47.958  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:15:47.959  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
08-16 17:15:47.959  3804  3862 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,08-16 17:15:47.959  3804  3862 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 17:15:47.960  3804  3804 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-16 17:15:47.961  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-16 17:15:47.961  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-16 17:15:47.961  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:15:47.961  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 17:15:47.962  3804  4279 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 17:15:47.967  3804  3862 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 17:15:47.967  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:15:47.970  3804  4279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-16 17:15:47.971  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 17:15:47.972  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings,
08-16 17:15:47.972  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:15:47.975  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-16 17:15:47.975  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 17:15:47.975  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-16 17:15:47.977  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-16 17:15:47.977  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-16 17:15:47.977  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-16 17:15:47.978  3804  3862 D BluetoothAdapter: STATE_ON
,08-16 17:15:47.981  4180  4216 D BtGatt.GattService: registerClient() - UUID=344629b5-93d1-450f-94b1-a4d28c9c35cc
,08-16 17:15:47.981  4180  4196 D BtGatt.GattService: onClientRegistered() - UUID=344629b5-93d1-450f-94b1-a4d28c9c35cc, clientIf=5
,08-16 17:15:47.981  3804  3814 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-16 17:15:47.983  4180  4198 D BtGatt.AdvertiseManager: message : 0
,08-16 17:15:47.986  4180  4198 D BtGatt.AdvertiseManager: starting multi advertising
,08-16 17:15:47.996  4180  4196 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-16 17:15:48.004  4180  4196 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-16 17:15:48.006  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-16 17:15:48.006  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 17:15:48.012  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:15:48.015  3804  3804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-16 17:15:48.016  3804  3804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-16 17:15:48.016  3804  3804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-16 17:15:48.016  3804  3804 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-16 17:15:48.016  3804  3804 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
,08-16 17:15:48.017  3804  3804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-16 17:15:48.021  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-16 17:15:48.024  3804  3804 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-16 17:15:48.024  3804  3804 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-16 17:15:48.525  3804  3804 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-16 17:15:48.526  3804  3804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-16 17:15:48.526  3804  3804 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 17:15:51.022  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 17:15:51.022  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
,08-16 17:15:51.023  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 17:15:51.023  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-16 17:15:51.023  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-16 17:15:51.024  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-16 17:15:51.027  3804  4279 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-16 17:15:51.027  3804  4279 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-16 17:15:51.028  3804  4279 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 17:15:51.028  3804  3804 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 17:15:51.030  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 17:15:51.031  3804  3862 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 17:15:51.031  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:15:51.032  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 17:15:51.032  3804  3804 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 17:15:51.032  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 17:15:51.032  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 17:15:51.033  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 17:15:51.035  3804  3862 D BluetoothAdapter: STATE_ON
08-16 17:15:51.035  3804  3862 D BluetoothLeScanner: could not find callback wrapper
08-16 17:15:51.036  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:15:51.036  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-16 17:15:51.038  4180  4198 D BtGatt.AdvertiseManager: message : 1
08-16 17:15:51.041  4180  4198 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-16 17:15:51.049  4180  4196 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0,
08-16 17:15:51.049  4180  4196 D BtGatt.GattService: Client app is not null!
,08-16 17:15:51.050  4180  4190 D BtGatt.GattService: unregisterClient() - clientIf=5,
08-16 17:15:51.051  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 17:15:51.051  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-16 17:15:51.051  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-16 17:15:51.051  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
08-16 17:15:51.051  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,08-16 17:15:51.053  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:15:51.053  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 17:15:51.053  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 17:15:51.054  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 17:15:51.056  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:15:51.057  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,08-16 17:15:51.057  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 17:15:51.057  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:15:51.058  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4127c70 removed from the list
,08-16 17:15:51.058  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:15:51.058  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c694be9 removed from the list
08-16 17:15:51.058  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:15:51.059  3804  3804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:15:51.059  3804  3804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-16 17:15:51.060  3804  3804 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 17:15:51.059  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:15:51.061  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:15:51.062  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:15:51.064  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:15:51.065  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:15:51.065  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:15:51.065  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c694be9 not in the list
08-16 17:15:51.065  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:15:51.066  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:15:51.068  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 17:15:51.068  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:15:51.068  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:15:51.069  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c694be9 not in the list
,08-16 17:15:51.069  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:15:51.069  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:15:51.069  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:15:51.070  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4127c70 not in the list,
08-16 17:15:51.071  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:15:51.072  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4357a added. We now have 3 listener(s)
,08-16 17:15:51.077  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 17:15:51.078  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:15:51.078  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:15:51.079  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:15:51.079  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@492212b added. We now have 4 listener(s)
08-16 17:15:51.079  3804  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:15:51.080  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:15:51.085  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:15:51.092  3804  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:15:51.092  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:15:51.092  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:15:51.092  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:15:51.092  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:15:51.092  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:15:51.092  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:15:51.092  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:15:51.095  3804  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:15:51.096  3804  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:15:51.096  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:15:51.096  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 17:15:51.097  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 17:15:51.097  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 17:15:51.097  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 17:15:51.102  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:15:51.103  3804  3862 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 17:15:51.103  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 17:15:51.106  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:15:51.110  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 17:15:51.111  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 17:15:51.111  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 17:15:51.117  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 17:15:51.117  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-16 17:15:51.118  3804  3862 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 17:15:51.119  3804  3862 D BluetoothAdapter: STATE_ON
,08-16 17:15:51.123  4180  4222 D BtGatt.GattService: registerClient() - UUID=a73e4e6a-37fc-4581-bcb4-5fdeead81061
,08-16 17:15:51.124  4180  4196 D BtGatt.GattService: onClientRegistered() - UUID=a73e4e6a-37fc-4581-bcb4-5fdeead81061, clientIf=5
,08-16 17:15:51.125  3804  3815 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 17:15:51.125  4180  4190 D BtGatt.GattService: start scan with filters
,08-16 17:15:51.129  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 17:15:51.129  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 17:15:51.130  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING],
,08-16 17:15:51.130  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 17:15:51.130  4180  4199 D BtGatt.ScanManager: handling starting scan
,08-16 17:15:51.138  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:15:51.138  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 17:15:51.138  3804  3804 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 17:15:51.141  4180  4196 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 17:15:51.141  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
08-16 17:15:51.142  4180  4199 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 17:15:51.144  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 17:15:51.152  4180  4196 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 17:15:51.153  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:15:51.153  4180  4199 D BtGatt.ScanManager: Starting BLE batch scan
08-16 17:15:51.153  4180  4199 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 17:15:51.181  4180  4196 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 17:15:51.182  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:15:51.196  4180  4196 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 17:15:51.196  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:15:51.561  3804  3804 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 17:15:51.639  3804  3804 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-16 17:15:51.639  3804  3804 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 17:15:51.640  3804  3804 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 17:15:52.704  4180  4180 D BtGatt.ScanManager: awakened up at time 238080
,08-16 17:15:52.709  4180  4199 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 17:15:52.757  4180  4196 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
08-16 17:15:52.758  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:15:52.758  4180  4196 D BtGatt.GattService: current time is 238134495329
08-16 17:15:52.759  4180  4196 D BtGatt.GattService: Batch record : [85, -113, -37, 31, -33, 8, 0, 4, -82, 8, 0, 27, 2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 19, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101, 35, 97, 126, -92, 22, -56, 1, -128, -77, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -81, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 0, 71, -122, -77, 84, 69, -12, 1, -128, -92, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -86, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -83, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0]
08-16 17:15:52.762  4180  4196 D BtGatt.GattService: ScanRecord : [2, 1, 2, 3, 3, -66, -2, 19, -1, 16, 1, 64, 12, 2, 67, 48, 117, 18, -41, 74, -25, 92, -13, 112, 116, -42, 103, 2, 10, 4, 15, 9, 83, 108, 117, 99, 104, 97, 119, 107, 105, 32, 66, 111, 115, 101]
08-16 17:15:52.764  4180  4196 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74]
08-16 17:15:52.764  4180  4196 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74]
08-16 17:15:52.765  4180  4196 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-16 17:15:52.765  4180  4196 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-16 17:15:52.766  4180  4196 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
,08-16 17:15:54.160  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:15:54.160  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 17:15:54.161  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 17:15:54.161  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:15:54.161  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-16 17:15:54.162  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 17:15:54.162  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 17:15:54.162  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 17:15:54.163  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 17:15:54.164  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 17:15:54.164  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 17:15:54.166  3804  3862 D BluetoothAdapter: STATE_ON
08-16 17:15:54.168  4180  4216 D BtGatt.GattService: stopScan() - queue size =1
,08-16 17:15:54.171  4180  4191 D BtGatt.GattService: unregisterClient() - clientIf=5
08-16 17:15:54.172  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 17:15:54.173  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 17:15:54.173  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 17:15:54.174  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 17:15:54.174  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 17:15:54.177  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:15:54.177  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-16 17:15:54.177  3804  3862 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 17:15:54.178  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 17:15:54.180  4180  4180 D BtGatt.ScanManager: awakened up at time 239556
,08-16 17:15:54.180  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 17:15:54.182  3804  3804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 17:15:54.182  3804  3804 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 17:15:54.182  3804  3804 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 17:15:54.183  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:15:54.183  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:15:54.183  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:15:54.183  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:15:54.183  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4357a removed from the list
,08-16 17:15:54.183  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:15:54.184  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@492212b removed from the list
,08-16 17:15:54.184  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 17:15:54.184  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:15:54.185  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:15:54.185  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:15:54.187  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:15:54.187  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:15:54.187  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 17:15:54.187  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@492212b not in the list
08-16 17:15:54.188  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:15:54.188  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:15:54.190  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:15:54.191  4180  4196 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 17:15:54.192  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 17:15:54.190  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:15:54.192  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:15:54.192  4180  4199 D BtGatt.ScanManager: stopping BLe Batch
,08-16 17:15:54.192  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@492212b not in the list
08-16 17:15:54.193  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 17:15:54.193  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 17:15:54.193  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:15:54.193  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4357a not in the list
,08-16 17:15:54.195  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:15:54.195  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2db9634 added. We now have 3 listener(s)
08-16 17:15:54.199  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 17:15:54.199  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:15:54.200  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:15:54.200  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:15:54.200  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7afc5d added. We now have 4 listener(s)
,08-16 17:15:54.200  3804  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:15:54.201  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:15:54.206  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:15:54.206  4180  4196 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 17:15:54.207  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:15:54.207  4180  4199 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 17:15:54.212  3804  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:15:54.212  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:15:54.212  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:15:54.212  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:15:54.212  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:15:54.212  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:15:54.212  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:15:54.212  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:15:54.215  4180  4196 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 17:15:54.215  4180  4196 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 17:15:54.215  3804  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:15:54.215  3804  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:15:54.215  3804  3862 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 17:15:54.216  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 17:15:54.216  3804  3862 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 17:15:54.216  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:15:54.216  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:15:54.216  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 17:15:54.216  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 17:15:54.216  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2db9634 removed from the list
08-16 17:15:54.216  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:15:54.217  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7afc5d removed from the list
,08-16 17:15:54.218  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:15:54.218  3804  3862 D io.jxcore.node.ConnectivityMonitor: stop
08-16 17:15:54.218  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:15:54.218  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:15:54.219  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:15:54.220  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 17:15:54.220  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:15:54.220  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:15:54.220  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7afc5d not in the list
08-16 17:15:54.220  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:15:54.220  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 17:15:54.221  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 17:15:54.222  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 17:15:54.222  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 17:15:54.222  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 17:15:54.222  3804  3862 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f7afc5d not in the list
,08-16 17:15:54.222  3804  3862 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 17:15:54.222  3804  3862 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 17:15:54.222  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 17:15:54.222  3804  3862 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2db9634 not in the list
,08-16 17:15:54.223  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 17:15:54.223  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 17:15:54.224  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-16 17:15:54.224  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 17:15:54.224  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 17:15:54.224  3804  3862 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 17:15:54.683  3804  3804 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 17:15:56.239  3804  4281 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 462, name: My test thread name)
,08-16 17:15:58.236  3804  3862 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 462
,08-16 17:15:58.237  3804  3862 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 462, name: My test thread name)
,08-16 17:15:58.243  3804  4282 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 463, name: My test thread name)
,08-16 17:15:58.243  3804  4282 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 463, thread name: My test thread name)
08-16 17:15:58.243  3804  4282 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 463, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-16 17:15:58.247  3804  3862 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 17:15:58.256  3804  4283 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 467, name: My test thread name)
,08-16 17:15:58.256  3804  4283 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 467, thread name: My test thread name): Test exception.
08-16 17:15:58.257  3804  4283 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 467, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-16 17:15:58.265  3804  3862 I jxcore-log: Total number of executed tests:  82
08-16 17:15:58.265  3804  3862 I jxcore-log: 
,08-16 17:15:58.266  3804  3862 I jxcore-log: Number of passed tests:  82
08-16 17:15:58.266  3804  3862 I jxcore-log: 
08-16 17:15:58.267  3804  3862 I jxcore-log: Number of failed tests:  0
08-16 17:15:58.267  3804  3862 I jxcore-log: 
08-16 17:15:58.268  3804  3862 I jxcore-log: Number of ignored tests:  0
08-16 17:15:58.268  3804  3862 I jxcore-log: 
,08-16 17:15:58.270  3804  3862 I jxcore-log: Total duration:  101280
08-16 17:15:58.270  3804  3862 I jxcore-log: 
,08-16 17:15:58.278  3804  3862 I jxcore-log: Unit Test app is loaded
08-16 17:15:58.278  3804  3862 I jxcore-log: 
,08-16 17:15:58.306  3804  4281 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 462, name: My test thread name), during the lifetime of the thread the total number of bytes read was 176 and the total number of bytes written 176
,08-16 17:15:58.306  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:15:58.306  3804  3862 I jxcore-log: 
08-16 17:15:58.307  3804  3804 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-16 17:15:58.320  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:15:58.320  3804  3862 I jxcore-log: 
,08-16 17:15:58.321  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:15:58.321  3804  3862 I jxcore-log: 
,08-16 17:15:58.322  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:15:58.322  3804  3862 I jxcore-log: 
,08-16 17:15:58.323  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-16 17:15:58.323  3804  3862 I jxcore-log: 
,08-16 17:15:58.324  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:15:58.324  3804  3862 I jxcore-log: 
,08-16 17:15:58.327  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:15:58.327  3804  3862 I jxcore-log: 
,08-16 17:15:58.329  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:15:58.329  3804  3862 I jxcore-log: 
,08-16 17:15:58.330  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-16 17:15:58.330  3804  3862 I jxcore-log: 
,08-16 17:15:58.331  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:15:58.331  3804  3862 I jxcore-log: 
08-16 17:15:58.331  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:15:58.331  3804  3862 I jxcore-log: 
08-16 17:15:58.332  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:15:58.332  3804  3862 I jxcore-log: 
08-16 17:15:58.333  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:15:58.333  3804  3862 I jxcore-log: 
,08-16 17:15:58.334  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:15:58.334  3804  3862 I jxcore-log: 
,08-16 17:15:58.335  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:15:58.335  3804  3862 I jxcore-log: 
08-16 17:15:58.336  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:15:58.336  3804  3862 I jxcore-log: 
,08-16 17:15:58.337  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:15:58.337  3804  3862 I jxcore-log: 
,08-16 17:15:58.338  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:15:58.338  3804  3862 I jxcore-log: 
,08-16 17:15:58.338  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:15:58.338  3804  3862 I jxcore-log: 
,08-16 17:15:58.339  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:15:58.339  3804  3862 I jxcore-log: 
,08-16 17:15:58.340  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:15:58.340  3804  3862 I jxcore-log: 
,08-16 17:15:58.341  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:15:58.341  3804  3862 I jxcore-log: 
,08-16 17:15:58.342  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:15:58.342  3804  3862 I jxcore-log: 
,08-16 17:15:58.342  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:15:58.342  3804  3862 I jxcore-log: 
,08-16 17:15:58.343  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:15:58.343  3804  3862 I jxcore-log: 
,08-16 17:15:58.344  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:15:58.344  3804  3862 I jxcore-log: 
,08-16 17:15:58.345  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:15:58.345  3804  3862 I jxcore-log: 
,08-16 17:15:58.346  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:15:58.346  3804  3862 I jxcore-log: 
,08-16 17:15:58.346  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 17:15:58.346  3804  3862 I jxcore-log: 
08-16 17:15:58.347  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:15:58.347  3804  3862 I jxcore-log: 
08-16 17:15:58.348  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:15:58.348  3804  3862 I jxcore-log: 
08-16 17:15:58.349  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:15:58.349  3804  3862 I jxcore-log: 
08-16 17:15:58.349  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:15:58.349  3804  3862 I jxcore-log: 
08-16 17:15:58.350  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:15:58.350  3804  3862 I jxcore-log: 
,08-16 17:15:58.351  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:15:58.351  3804  3862 I jxcore-log: 
08-16 17:15:58.352  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:15:58.352  3804  3862 I jxcore-log: 
08-16 17:15:58.352  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:15:58.352  3804  3862 I jxcore-log: 
08-16 17:15:58.353  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 17:15:58.353  3804  3862 I jxcore-log: 
08-16 17:15:58.354  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:15:58.354  3804  3862 I jxcore-log: 
08-16 17:15:58.355  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:15:58.355  3804  3862 I jxcore-log: 
08-16 17:15:58.355  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 17:15:58.355  3804  3862 I jxcore-log: 
08-16 17:15:58.356  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:15:58.356  3804  3862 I jxcore-log: 
08-16 17:15:58.357  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 17:15:58.357  3804  3862 I jxcore-log: 
,08-16 17:15:58.359  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:15:58.359  3804  3862 I jxcore-log: 
08-16 17:15:58.359  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:15:58.359  3804  3862 I jxcore-log: 
08-16 17:15:58.360  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:15:58.360  3804  3862 I jxcore-log: 
08-16 17:15:58.360  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:15:58.360  3804  3862 I jxcore-log: 
,08-16 17:15:58.361  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:15:58.361  3804  3862 I jxcore-log: 
08-16 17:15:58.361  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:15:58.361  3804  3862 I jxcore-log: 
,08-16 17:15:58.362  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:15:58.362  3804  3862 I jxcore-log: 
08-16 17:15:58.362  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-16 17:15:58.362  3804  3862 I jxcore-log: 
08-16 17:15:58.363  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:15:58.363  3804  3862 I jxcore-log: 
08-16 17:15:58.363  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:15:58.363  3804  3862 I jxcore-log: 
,08-16 17:15:58.364  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-16 17:15:58.364  3804  3862 I jxcore-log: 
08-16 17:15:58.364  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:15:58.364  3804  3862 I jxcore-log: 
,08-16 17:15:58.365  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 17:15:58.365  3804  3862 I jxcore-log: 
08-16 17:15:58.368  3804  3862 I jxcore-log: My device name is: motorola-Nexus 6
08-16 17:15:58.368  3804  3862 I jxcore-log: 
,08-16 17:16:00.661  3804  3862 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-16 17:16:00.661  3804  3862 I jxcore-log: 
,08-16 17:16:00.676  3804  3862 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-16 17:16:00.677  3804  3862 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-16 17:16:00.677  3804  3862 I jxcore-log: 
,08-16 17:16:01.397  3736  4285 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 17:16:01.436  3736  4286 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 17:16:01.461  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:16:01.466  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:16:01.503  1493  1987 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-16 17:16:01.504  1493  1987 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-16 17:16:01.504  1493  1987 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:16:01.504  1493  1987 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:16:01.551  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:16:01.554  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:16:01.592  1493  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 17:16:01.592  1493  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 17:16:01.592  1493  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 17:16:01.593  1493  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:16:01.616  3736  4286 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 17:16:01.617  3736  4285 E BooksSync: Soft error
08-16 17:16:01.617  3736  4285 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 17:16:01.617  3736  4285 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 17:16:01.619  3736  4285 E BooksSync: Sync error
08-16 17:16:01.619  3736  4285 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 17:16:01.619  3736  4285 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 17:16:01.620  3736  4285 I BooksSync: Finished books sync
,08-16 17:16:01.634   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 246617, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 17:16:13.201   873  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=258577, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 17:16:22.008   873  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=267384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-16 17:16:31.854  3030  4288 V KeepSync: Connecting to GoogleApiClient
,08-16 17:16:31.855   873  1688 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 17:16:31.903  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:16:31.905  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:16:31.928  1493  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-16 17:16:31.928  1493  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-16 17:16:31.928  1493  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:16:31.928  1493  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:16:31.955  1691  4289 V BaseAuthAsyncOperation: access token request failed
,08-16 17:16:31.956  3030  4288 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 17:16:32.014  1493  3072 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-16 17:16:32.014  1493  3072 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 17:16:32.014  1493  3072 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:16:32.014  1493  3072 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:16:32.027  3030  4288 E KeepSync: IOException
08-16 17:16:32.027  3030  4288 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 17:16:32.027  3030  4288 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 17:16:32.027  3030  4288 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 17:16:32.027  3030  4288 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 17:16:32.027  3030  4288 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 17:16:32.027  3030  4288 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 17:16:32.027  3030  4288 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 17:16:32.027  3030  4288 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 17:16:32.027  3030  4288 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 17:16:32.027  3030  4288 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 17:16:32.027  3030  4288 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 17:16:32.027  3030  4288 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 17:16:32.027  3030  4288 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 17:16:32.027  3030  4288 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 17:16:32.027  3030  4288 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 17:16:32.027  3030  4288 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 17:16:32.027  3030  4288 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 17:16:32.027  3030  4288 E KeepSync: 	... 10 more
,08-16 17:16:32.027  3030  4288 W KeepSync: Sync result 2
,08-16 17:16:32.034   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 252200, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 17:17:02.480  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:17:02.486  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:17:02.546  1493  1505 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 17:17:02.546  1493  1505 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 17:17:02.546  1493  1505 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:17:02.546  1493  1505 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:17:02.576  2990  4297 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 17:17:02.576  2990  4297 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 17:17:02.576  2990  4297 E HttpOperation: 	at jdm.a(PG:82)
08-16 17:17:02.576  2990  4297 E HttpOperation: 	at jcs.o(PG:406)
08-16 17:17:02.576  2990  4297 E HttpOperation: 	at jcn.a(PG:1379)
08-16 17:17:02.576  2990  4297 E HttpOperation: 	at jcs.i(PG:143)
08-16 17:17:02.576  2990  4297 E HttpOperation: 	at blb.a(PG:3937)
08-16 17:17:02.576  2990  4297 E HttpOperation: 	at czp.a(PG:18188)
08-16 17:17:02.576  2990  4297 E HttpOperation: 	at czp.a(PG:9081)
08-16 17:17:02.576  2990  4297 E HttpOperation: 	at czq.run(PG:1686)
08-16 17:17:02.576  2990  4297 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 17:17:02.576  2990  4297 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 17:17:02.576  2990  4297 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 17:17:02.576  2990  4297 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 17:17:02.576  2990  4297 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 17:17:02.576  2990  4297 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 17:17:02.576  2990  4297 E HttpOperation: 	at jdj.a(PG:4091)
08-16 17:17:02.576  2990  4297 E HttpOperation: 	at jdj.a(PG:1125)
08-16 17:17:02.576  2990  4297 E HttpOperation: 	at jdm.a(PG:77)
08-16 17:17:02.576  2990  4297 E HttpOperation: 	... 12 more
08-16 17:17:02.576  2990  4297 E HttpOperation: Caused by: faj: BadAuthentication
08-16 17:17:02.576  2990  4297 E HttpOperation: 	at fal.a(PG:38)
08-16 17:17:02.576  2990  4297 E HttpOperation: 	at jdj.a(PG:4089)
08-16 17:17:02.576  2990  4297 E HttpOperation: 	... 14 more
,08-16 17:17:02.636  1493  2081 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 17:17:02.636  1493  2081 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 17:17:02.636  1493  2081 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 17:17:02.636  1493  2081 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:17:02.688  2990  4297 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 17:17:02.688  2990  4297 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 17:17:02.688  2990  4297 E HttpOperation: 	at jdm.a(PG:82)
08-16 17:17:02.688  2990  4297 E HttpOperation: 	at jcs.o(PG:406)
08-16 17:17:02.688  2990  4297 E HttpOperation: 	at jcn.a(PG:1379)
08-16 17:17:02.688  2990  4297 E HttpOperation: 	at jcs.i(PG:143)
08-16 17:17:02.688  2990  4297 E HttpOperation: 	at hec.a(PG:42)
08-16 17:17:02.688  2990  4297 E HttpOperation: 	at hee.a(PG:102)
08-16 17:17:02.688  2990  4297 E HttpOperation: 	at czr.a(PG:65)
08-16 17:17:02.688  2990  4297 E HttpOperation: 	at kka.a(PG:108)
08-16 17:17:02.688  2990  4297 E HttpOperation: 	at czp.a(PG:19176)
08-16 17:17:02.688  2990  4297 E HttpOperation: 	at czp.a(PG:9081)
08-16 17:17:02.688  2990  4297 E HttpOperation: 	at czq.run(PG:1686)
08-16 17:17:02.688  2990  4297 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 17:17:02.688  2990  4297 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 17:17:02.688  2990  4297 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 17:17:02.688  2990  4297 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 17:17:02.688  2990  4297 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 17:17:02.688  2990  4297 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 17:17:02.688  2990  4297 E HttpOperation: 	at jdj.a(PG:4091)
08-16 17:17:02.688  2990  4297 E HttpOperation: 	at jdj.a(PG:1125)
08-16 17:17:02.688  2990  4297 E HttpOperation: 	at jdm.a(PG:77)
08-16 17:17:02.688  2990  4297 E HttpOperation: 	... 15 more
08-16 17:17:02.688  2990  4297 E HttpOperation: Caused by: faj: BadAuthentication
08-16 17:17:02.688  2990  4297 E HttpOperation: 	at fal.a(PG:38)
08-16 17:17:02.688  2990  4297 E HttpOperation: 	at jdj.a(PG:4089)
08-16 17:17:02.688  2990  4297 E HttpOperation: 	... 17 more
,08-16 17:17:02.689  2990  4297 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 17:17:02.689  2990  4297 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	at hec.a(PG:42)
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	at hee.a(PG:102)
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	at czr.a(PG:65)
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	at kka.a(PG:108)
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 17:17:02.689  2990  4297 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	... 15 more
08-16 17:17:02.689  2990  4297 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	at fal.a(PG:38)
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 17:17:02.689  2990  4297 E ExperimentLoader: 	... 17 more
,08-16 17:17:02.771   873   882 I art     : Background partial concurrent mark sweep GC freed 31192(1856KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 29MB/43MB, paused 1.266ms total 108.162ms
,08-16 17:17:02.826   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 284495, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 17:17:02.864  3736  4302 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 17:17:02.888  3736  4303 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 17:17:02.913  3030  4301 V KeepSync: Connecting to GoogleApiClient
,08-16 17:17:02.913   873   883 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 17:17:02.989  1493  3072 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 17:17:02.989  1493  3072 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-16 17:17:02.989  1493  3072 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 17:17:02.989  1493  3072 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:17:03.100  1493  2081 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-16 17:17:03.100  1493  2081 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-16 17:17:03.100  1493  2081 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:17:03.100  1493  2081 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:17:03.108  1493  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 17:17:03.108  1493  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-16 17:17:03.108  1493  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 17:17:03.108  1493  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:17:03.132  1691  4304 V BaseAuthAsyncOperation: access token request failed
,08-16 17:17:03.134  3030  4301 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 17:17:03.138  3736  4303 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 17:17:03.138  3736  4302 E BooksSync: Soft error
08-16 17:17:03.138  3736  4302 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 17:17:03.138  3736  4302 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 17:17:03.138  3736  4302 E BooksSync: Sync error
08-16 17:17:03.138  3736  4302 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 17:17:03.138  3736  4302 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 17:17:03.139  3736  4302 I BooksSync: Finished books sync
,08-16 17:17:03.156   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 307946, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 17:17:03.222  1493  1505 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-16 17:17:03.222  1493  1505 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 17:17:03.222  1493  1505 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:17:03.222  1493  1505 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:17:03.242  3030  4301 E KeepSync: IOException
08-16 17:17:03.242  3030  4301 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 17:17:03.242  3030  4301 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 17:17:03.242  3030  4301 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 17:17:03.242  3030  4301 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 17:17:03.242  3030  4301 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 17:17:03.242  3030  4301 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 17:17:03.242  3030  4301 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 17:17:03.242  3030  4301 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 17:17:03.242  3030  4301 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 17:17:03.242  3030  4301 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 17:17:03.242  3030  4301 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 17:17:03.242  3030  4301 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 17:17:03.242  3030  4301 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 17:17:03.242  3030  4301 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 17:17:03.242  3030  4301 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 17:17:03.242  3030  4301 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 17:17:03.242  3030  4301 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 17:17:03.242  3030  4301 E KeepSync: 	... 10 more
08-16 17:17:03.243  3030  4301 W KeepSync: Sync result 2
,08-16 17:17:03.255   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 307803, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 17:17:04.328   873  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=309703, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 17:17:12.595   873  4239 D NetlinkSocketObserver: NeighborEvent{elapsedMs=317970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-16 17:17:32.566  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:17:32.571  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:17:32.583  3773  4314 V GoogleAuthProtoRequest: [321] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 17:17:32.609  1493  1987 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-16 17:17:32.609  1493  1987 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-16 17:17:32.609  1493  1987 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:17:32.609  1493  1987 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:17:32.625  3773  4314 W ExperimentUpdateService: [321] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-16 17:17:32.626  3773  4314 W ExperimentUpdateService: [321] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 17:17:32.626  3773  4314 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 17:17:32.626  3773  4314 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-16 17:17:32.626  3773  4314 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-16 17:17:32.626  3773  4314 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-16 17:17:32.626  3773  4314 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-16 17:17:32.626  3773  4314 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-16 17:17:32.626  3773  4314 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-16 17:17:32.626  3773  4314 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-16 17:17:32.626  3773  4314 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-16 17:17:32.626  3773  4314 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-16 17:17:33.530  1493  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 17:17:33.530  1493  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 17:17:33.530  1493  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:17:33.530  1493  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:17:33.549  2990  4316 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 17:17:33.549  2990  4316 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 17:17:33.549  2990  4316 E HttpOperation: 	at jdm.a(PG:82)
08-16 17:17:33.549  2990  4316 E HttpOperation: 	at jcs.o(PG:406)
08-16 17:17:33.549  2990  4316 E HttpOperation: 	at jcn.a(PG:1379)
08-16 17:17:33.549  2990  4316 E HttpOperation: 	at jcs.i(PG:143)
08-16 17:17:33.549  2990  4316 E HttpOperation: 	at blb.a(PG:3937)
08-16 17:17:33.549  2990  4316 E HttpOperation: 	at czp.a(PG:18188)
08-16 17:17:33.549  2990  4316 E HttpOperation: 	at czp.a(PG:9081)
08-16 17:17:33.549  2990  4316 E HttpOperation: 	at czq.run(PG:1686)
08-16 17:17:33.549  2990  4316 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 17:17:33.549  2990  4316 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 17:17:33.549  2990  4316 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 17:17:33.549  2990  4316 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 17:17:33.549  2990  4316 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 17:17:33.549  2990  4316 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 17:17:33.549  2990  4316 E HttpOperation: 	at jdj.a(PG:4091)
08-16 17:17:33.549  2990  4316 E HttpOperation: 	at jdj.a(PG:1125)
08-16 17:17:33.549  2990  4316 E HttpOperation: 	at jdm.a(PG:77)
08-16 17:17:33.549  2990  4316 E HttpOperation: 	... 12 more
08-16 17:17:33.549  2990  4316 E HttpOperation: Caused by: faj: BadAuthentication
08-16 17:17:33.549  2990  4316 E HttpOperation: 	at fal.a(PG:38)
08-16 17:17:33.549  2990  4316 E HttpOperation: 	at jdj.a(PG:4089)
08-16 17:17:33.549  2990  4316 E HttpOperation: 	... 14 more
,08-16 17:17:33.603  1493  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 17:17:33.604  1493  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 17:17:33.604  1493  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 17:17:33.604  1493  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:17:33.621  2990  4316 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 17:17:33.621  2990  4316 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 17:17:33.621  2990  4316 E HttpOperation: 	at jdm.a(PG:82)
08-16 17:17:33.621  2990  4316 E HttpOperation: 	at jcs.o(PG:406)
08-16 17:17:33.621  2990  4316 E HttpOperation: 	at jcn.a(PG:1379)
08-16 17:17:33.621  2990  4316 E HttpOperation: 	at jcs.i(PG:143)
08-16 17:17:33.621  2990  4316 E HttpOperation: 	at hec.a(PG:42)
08-16 17:17:33.621  2990  4316 E HttpOperation: 	at hee.a(PG:102)
08-16 17:17:33.621  2990  4316 E HttpOperation: 	at czr.a(PG:65)
08-16 17:17:33.621  2990  4316 E HttpOperation: 	at kka.a(PG:108)
08-16 17:17:33.621  2990  4316 E HttpOperation: 	at czp.a(PG:19176)
08-16 17:17:33.621  2990  4316 E HttpOperation: 	at czp.a(PG:9081)
08-16 17:17:33.621  2990  4316 E HttpOperation: 	at czq.run(PG:1686)
08-16 17:17:33.621  2990  4316 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 17:17:33.621  2990  4316 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 17:17:33.621  2990  4316 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 17:17:33.621  2990  4316 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 17:17:33.621  2990  4316 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 17:17:33.621  2990  4316 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 17:17:33.621  2990  4316 E HttpOperation: 	at jdj.a(PG:4091)
08-16 17:17:33.621  2990  4316 E HttpOperation: 	at jdj.a(PG:1125)
08-16 17:17:33.621  2990  4316 E HttpOperation: 	at jdm.a(PG:77)
08-16 17:17:33.621  2990  4316 E HttpOperation: 	... 15 more
08-16 17:17:33.621  2990  4316 E HttpOperation: Caused by: faj: BadAuthentication
08-16 17:17:33.621  2990  4316 E HttpOperation: 	at fal.a(PG:38)
08-16 17:17:33.621  2990  4316 E HttpOperation: 	at jdj.a(PG:4089)
08-16 17:17:33.621  2990  4316 E HttpOperation: 	... 17 more
,08-16 17:17:33.621  2990  4316 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 17:17:33.621  2990  4316 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	at hec.a(PG:42)
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	at hee.a(PG:102)
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	at czr.a(PG:65)
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	at kka.a(PG:108)
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 17:17:33.621  2990  4316 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	... 15 more
08-16 17:17:33.621  2990  4316 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	at fal.a(PG:38)
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 17:17:33.621  2990  4316 E ExperimentLoader: 	... 17 more
,08-16 17:17:33.764   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 338373, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 17:17:36.473  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:17:36.509  1493  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-16 17:17:36.509  1493  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-16 17:17:36.509  1493  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:17:36.509  1493  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:17:36.535  1493  1507 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 17:17:36.535  1493  1507 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 17:17:36.535  1493  1507 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 17:17:36.535  1493  1507 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-16 17:17:36.535  1493  1507 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-16 17:17:36.535  1493  1507 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-16 17:17:36.535  1493  1507 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-16 17:17:36.546  3524  3556 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 17:17:36.546  3524  3556 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-16 17:17:36.546  3524  3556 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-16 17:17:36.546  3524  3556 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-16 17:17:36.546  3524  3556 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-16 17:17:36.546  3524  3556 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-16 17:17:36.546  3524  3556 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-16 17:18:04.193  3030  4323 V KeepSync: Connecting to GoogleApiClient
,08-16 17:18:04.194   873   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 17:18:04.235  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:18:04.238  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:18:04.275  1493  2081 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-16 17:18:04.275  1493  2081 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-16 17:18:04.276  1493  2081 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 17:18:04.276  1493  2081 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:18:04.299  1691  4324 V BaseAuthAsyncOperation: access token request failed
08-16 17:18:04.301  3030  4323 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 17:18:04.371  1493  1987 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-16 17:18:04.371  1493  1987 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 17:18:04.371  1493  1987 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:18:04.372  1493  1987 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:18:04.395  3030  4323 E KeepSync: IOException
08-16 17:18:04.395  3030  4323 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 17:18:04.395  3030  4323 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 17:18:04.395  3030  4323 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 17:18:04.395  3030  4323 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 17:18:04.395  3030  4323 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 17:18:04.395  3030  4323 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 17:18:04.395  3030  4323 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 17:18:04.395  3030  4323 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 17:18:04.395  3030  4323 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 17:18:04.395  3030  4323 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 17:18:04.395  3030  4323 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 17:18:04.395  3030  4323 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 17:18:04.395  3030  4323 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 17:18:04.395  3030  4323 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 17:18:04.395  3030  4323 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 17:18:04.395  3030  4323 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 17:18:04.395  3030  4323 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 17:18:04.395  3030  4323 E KeepSync: 	... 10 more
08-16 17:18:04.395  3030  4323 W KeepSync: Sync result 2
,08-16 17:18:04.412   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 369418, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 17:18:31.985  1493  2071 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-16 17:18:34.834  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:18:34.838  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:18:34.880  1493  1987 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 17:18:34.880  1493  1987 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 17:18:34.880  1493  1987 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:18:34.880  1493  1987 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:18:34.901  2990  4328 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 17:18:34.901  2990  4328 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 17:18:34.901  2990  4328 E HttpOperation: 	at jdm.a(PG:82)
08-16 17:18:34.901  2990  4328 E HttpOperation: 	at jcs.o(PG:406)
08-16 17:18:34.901  2990  4328 E HttpOperation: 	at jcn.a(PG:1379)
08-16 17:18:34.901  2990  4328 E HttpOperation: 	at jcs.i(PG:143)
08-16 17:18:34.901  2990  4328 E HttpOperation: 	at blb.a(PG:3937)
08-16 17:18:34.901  2990  4328 E HttpOperation: 	at czp.a(PG:18188)
08-16 17:18:34.901  2990  4328 E HttpOperation: 	at czp.a(PG:9081)
08-16 17:18:34.901  2990  4328 E HttpOperation: 	at czq.run(PG:1686)
08-16 17:18:34.901  2990  4328 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 17:18:34.901  2990  4328 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 17:18:34.901  2990  4328 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 17:18:34.901  2990  4328 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 17:18:34.901  2990  4328 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 17:18:34.901  2990  4328 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 17:18:34.901  2990  4328 E HttpOperation: 	at jdj.a(PG:4091)
08-16 17:18:34.901  2990  4328 E HttpOperation: 	at jdj.a(PG:1125)
08-16 17:18:34.901  2990  4328 E HttpOperation: 	at jdm.a(PG:77)
08-16 17:18:34.901  2990  4328 E HttpOperation: 	... 12 more
08-16 17:18:34.901  2990  4328 E HttpOperation: Caused by: faj: BadAuthentication
08-16 17:18:34.901  2990  4328 E HttpOperation: 	at fal.a(PG:38)
08-16 17:18:34.901  2990  4328 E HttpOperation: 	at jdj.a(PG:4089)
08-16 17:18:34.901  2990  4328 E HttpOperation: 	... 14 more
,08-16 17:18:34.995  1493  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-16 17:18:34.995  1493  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-16 17:18:34.995  1493  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:18:34.995  1493  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:18:35.024  2990  4328 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 17:18:35.024  2990  4328 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 17:18:35.024  2990  4328 E HttpOperation: 	at jdm.a(PG:82)
08-16 17:18:35.024  2990  4328 E HttpOperation: 	at jcs.o(PG:406)
08-16 17:18:35.024  2990  4328 E HttpOperation: 	at jcn.a(PG:1379)
08-16 17:18:35.024  2990  4328 E HttpOperation: 	at jcs.i(PG:143)
08-16 17:18:35.024  2990  4328 E HttpOperation: 	at hec.a(PG:42)
08-16 17:18:35.024  2990  4328 E HttpOperation: 	at hee.a(PG:102)
08-16 17:18:35.024  2990  4328 E HttpOperation: 	,at czr.a(PG:65)
08-16 17:18:35.024  2990  4328 E HttpOperation: 	at kka.a(PG:108)
08-16 17:18:35.024  2990  4328 E HttpOperation: 	at czp.a(PG:19176)
08-16 17:18:35.024  2990  4328 E HttpOperation: 	at czp.a(PG:9081)
08-16 17:18:35.024  2990  4328 E HttpOperation: 	at czq.run(PG:1686)
08-16 17:18:35.024  2990  4328 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 17:18:35.024  2990  4328 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 17:18:35.024  2990  4328 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 17:18:35.024  2990  4328 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 17:18:35.024  2990  4328 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 17:18:35.024  2990  4328 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
,08-16 17:18:35.024  2990  4328 E HttpOperation: 	at jdj.a(PG:4091)
08-16 17:18:35.024  2990  4328 E HttpOperation: 	at jdj.a(PG:1125)
08-16 17:18:35.024  2990  4328 E HttpOperation: 	at jdm.a(PG:77)
08-16 17:18:35.024  2990  4328 E HttpOperation: 	... 15 more
08-16 17:18:35.024  2990  4328 E HttpOperation: Caused by: faj: BadAuthentication
08-16 17:18:35.024  2990  4328 E HttpOperation: 	at fal.a(PG:38)
08-16 17:18:35.024  2990  4328 E HttpOperation: 	at jdj.a(PG:4089)
08-16 17:18:35.024  2990  4328 E HttpOperation: 	... 17 more
,08-16 17:18:35.024  2990  4328 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 17:18:35.024  2990  4328 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	at hec.a(PG:42)
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	at hee.a(PG:102)
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	at czr.a(PG:65)
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	at kka.a(PG:108)
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 17:18:35.024  2990  4328 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	... 15 more
08-16 17:18:35.024  2990  4328 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	at fal.a(PG:38)
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 17:18:35.024  2990  4328 E ExperimentLoader: 	... 17 more
,08-16 17:18:35.140   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, POLL, currentRunTime 399482, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 17:19:05.244  3736  4331 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 17:19:05.270  3736  4332 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 17:19:05.282  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:19:05.284  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:19:05.312  1493  1505 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 17:19:05.312  1493  1505 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 17:19:05.312  1493  1505 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 17:19:05.312  1493  1505 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:19:05.362  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:19:05.364  1493  1493 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 17:19:05.377  1493  1507 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books,
08-16 17:19:05.377  1493  1507 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 17:19:05.377  1493  1507 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 17:19:05.377  1493  1507 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 17:19:05.388  3736  4332 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 17:19:05.389  3736  4331 E BooksSync: Soft error
08-16 17:19:05.389  3736  4331 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 17:19:05.389  3736  4331 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 17:19:05.389  3736  4331 E BooksSync: Sync error
08-16 17:19:05.389  3736  4331 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 17:19:05.389  3736  4331 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 17:19:05.389  3736  4331 I BooksSync: Finished books sync
,08-16 17:19:05.400   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 430404, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 17:19:23.182  3804  3862 I jxcore-log: TAP version 13
08-16 17:19:23.182  3804  3862 I jxcore-log: 
,08-16 17:19:23.189  3804  3862 I jxcore-log: # setup
08-16 17:19:23.189  3804  3862 I jxcore-log: 
,08-16 17:19:23.413  3804  3862 I jxcore-log: # 1. onPeerLost calls jxcore
08-16 17:19:23.413  3804  3862 I jxcore-log: 
,08-16 17:19:23.525  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 17:19:23.526  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5f78aa3 added. We now have 3 listener(s)
,08-16 17:19:23.528  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 17:19:23.528  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 17:19:23.528  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 17:19:23.529  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:19:23.529  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b5e1a0 added. We now have 4 listener(s)
08-16 17:19:23.529  3804  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 17:19:23.529  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 17:19:23.532  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:19:23.543  3804  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:19:23.543  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:19:23.543  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:19:23.543  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:19:23.543  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:19:23.543  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:19:23.543  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:19:23.543  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:19:23.547  3804  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 17:19:23.547  3804  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 17:19:23.549  3804  3862 I io.jxcore.node.ConnectionHelper: onPeerLost: [<no peer name> 11:22:33:22:11:00]
,08-16 17:19:23.549  3804  3862 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID 11:22:33:22:11:00
08-16 17:19:23.552  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:19:23.557  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:19:25.553  3804  3862 I jxcore-log: onPeerLost
08-16 17:19:25.553  3804  3862 I jxcore-log: 
,08-16 17:19:25.557  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:19:25.557  3804  3862 I jxcore-log: 
,08-16 17:19:25.577  3804  3862 I jxcore-log: # teardown
08-16 17:19:25.577  3804  3862 I jxcore-log: 
,08-16 17:19:25.589  3804  3862 I jxcore-log: ok 1 check if callback was fired by onPeerLost
08-16 17:19:25.589  3804  3862 I jxcore-log: 
,08-16 17:19:25.591  3804  3862 I jxcore-log: ok 2 check if peerAvailable is false
08-16 17:19:25.591  3804  3862 I jxcore-log: 
,08-16 17:19:25.830  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 17:19:25.830  3804  3862 I jxcore-log: 
,08-16 17:19:25.832  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 17:19:25.832  3804  3862 I jxcore-log: 
,08-16 17:19:25.842  3804  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:19:25.842  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:19:25.842  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:19:25.842  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:19:25.842  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:19:25.842  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:19:25.842  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:19:25.842  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:19:25.849  3804  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:19:25.850  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 17:19:25.850  3804  3862 I jxcore-log: 
,08-16 17:19:25.852  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 17:19:25.852  3804  3862 I jxcore-log: 
,08-16 17:19:25.855  3804  3862 I jxcore-log: # setup
08-16 17:19:25.855  3804  3862 I jxcore-log: 
,08-16 17:19:25.856  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:19:25.856  3804  3862 I jxcore-log: 
,08-16 17:19:25.962  3804  3862 I jxcore-log: # 2. onPeerDiscovered calls jxcore
08-16 17:19:25.962  3804  3862 I jxcore-log: 
,08-16 17:19:26.393  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 17:19:26.393  3804  3862 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6fe11e added. We now have 4 listener(s)
,08-16 17:19:26.395  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 17:19:26.395  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 17:19:26.396  3804  3862 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 17:19:26.396  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 17:19:26.396  3804  3862 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36e2dff added. We now have 5 listener(s)
08-16 17:19:26.396  3804  3862 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 17:19:26.397  3804  3862 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 17:19:26.405  3804  3862 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 17:19:26.419  3804  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:19:26.419  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:19:26.419  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:19:26.419  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:19:26.419  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:19:26.419  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:19:26.419  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:19:26.419  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:19:26.427  3804  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:19:26.428  3804  3862 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 17:19:26.428  3804  3862 I io.jxcore.node.ConnectionHelper: onPeerDiscovered: [<no peer name> 33:44:55:44:33:22], Bluetooth address: 33:44:55:44:33:22, device name: '', device address: ''
,08-16 17:19:26.436  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:19:26.445  3804  3804 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 17:19:28.434  3804  3862 I jxcore-log: onPeerDiscovered
08-16 17:19:28.434  3804  3862 I jxcore-log: 
,08-16 17:19:28.439  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:19:28.439  3804  3862 I jxcore-log: 
,08-16 17:19:28.455  3804  3862 I jxcore-log: # teardown
08-16 17:19:28.455  3804  3862 I jxcore-log: 
,08-16 17:19:28.462  3804  3862 I jxcore-log: ok 3 check if callback was fired by onPeerDiscovered
08-16 17:19:28.462  3804  3862 I jxcore-log: 
,08-16 17:19:28.464  3804  3862 I jxcore-log: ok 4 check if peerAvailable is true
08-16 17:19:28.464  3804  3862 I jxcore-log: 
,08-16 17:19:29.449  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 17:19:29.449  3804  3862 I jxcore-log: 
,08-16 17:19:29.453  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 17:19:29.453  3804  3862 I jxcore-log: 
,08-16 17:19:29.467  3804  3862 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 17:19:29.467  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 17:19:29.467  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 17:19:29.467  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 17:19:29.467  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 17:19:29.467  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 17:19:29.467  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 17:19:29.467  3804  3862 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 17:19:29.472  3804  3862 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 17:19:29.477  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 17:19:29.477  3804  3862 I jxcore-log: 
,08-16 17:19:29.482  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 17:19:29.482  3804  3862 I jxcore-log: 
,08-16 17:19:29.489  3804  3862 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 17:19:29.489  3804  3862 I jxcore-log: 
,08-16 17:19:29.701  3804  3862 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-16 17:19:29.701  3804  3862 I jxcore-log: 
,08-16 17:19:30.366  4333  4333 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-16 17:19:30.372  4333  4333 D AndroidRuntime: CheckJNI is OFF
,08-16 17:19:30.414  4333  4333 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-16 17:19:30.462  4333  4333 I Radio-JNI: register_android_hardware_Radio DONE
,08-16 17:19:30.484  4333  4333 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 17:19:30.496   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-16 17:19:30.497   873   886 I ActivityManager: Killing 3804:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-16 17:19:30.611   873   897 W PackageSettings: Skipping PackageSetting{a29102d com.example.hello/10273} due to missing metadata
,08-16 17:19:30.635   873  1304 D WifiService: Client connection lost with reason: 4
,08-16 17:19:30.635   873  1687 D GraphicsStats: Buffer count: 2
,08-16 17:19:30.635   873  1688 I WindowState: WIN DEATH: Window{c52c153 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 17:19:30.645   873   897 I art     : Starting a blocking GC Explicit
,08-16 17:19:30.671   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-16 17:19:30.671   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-16 17:19:30.672   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-16 17:19:30.672   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-16 17:19:30.672   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-16 17:19:30.672   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-16 17:19:30.672   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-16 17:19:30.672   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-16 17:19:30.672   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-16 17:19:30.672   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-16 17:19:30.672   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-16 17:19:30.672   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-16 17:19:30.672   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-16 17:19:30.672   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-16 17:19:30.672   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-16 17:19:30.672   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-16 17:19:30.672   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-16 17:19:30.672   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-16 17:19:30.672   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:19:30.672   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:19:30.672   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 17:19:30.672   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-16 17:19:30.673   873   886 I ActivityManager:   Force finishing activity ActivityRecord{7802994 u0 com.test.thalitest/.MainActivity t2}
,08-16 17:19:30.678   873   884 W ActivityManager: Spurious death for ProcessRecord{dd1c4cb 0:com.test.thalitest/u0a0}, curProc for 3804: null
,08-16 17:19:30.713   873   897 I art     : Explicit concurrent mark sweep GC freed 19339(1351KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 28MB/43MB, paused 1.121ms total 66.973ms
,08-16 17:19:30.734   873   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-16 17:19:30.738  4333  4333 I art     : System.exit called, status: 0
,08-16 17:19:30.738  4333  4333 I AndroidRuntime: VM exiting with result code 0.
,08-16 17:19:30.742   873   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-16 17:19:30.756   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-16 17:19:30.763  4180  4180 D BluetoothMapAppObserver: onReceive
,08-16 17:19:30.763  4180  4180 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-16 17:19:30.763  1876  2141 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 17:19:30.769  3624  3624 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-16 17:19:30.769  1861  1861 I Keyboard.Facilitator: resetDictionaries() : en_US
08-16 17:19:30.781   873  1294 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 17:19:30.785  1861  4346 I Keyboard.Facilitator.DecoderInitializer: run()
,08-16 17:19:30.812  1940  1940 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-16 17:19:30.814   873  1686 I ActivityManager: Start proc 4349:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-16 17:19:30.820  1861  4346 I Decoder : createOrResetDecoder
,08-16 17:19:30.845  1493  1493 I ConfigService: onCreate
,08-16 17:19:30.854  4349  4349 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-16 17:19:30.860  1493  4362 W FileUtils: Failed to chmod(/data/user/0/com.google.android.gms/databases/config.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-16 17:19:30.875  1861  4346 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-16 17:19:30.878   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 17:19:30.880   873  1685 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3804 uid 10000
,08-16 17:19:30.882  1861  1861 I Keyboard.Facilitator: onFinishInput()
,08-16 17:19:30.891   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-16 17:19:30.891  1953  2033 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-16 17:19:30.891   873   885 E PackageManager: Failed to write settings, restoring backup
08-16 17:19:30.891   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-16 17:19:30.891   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-16 17:19:30.891   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-16 17:19:30.891   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-16 17:19:30.891   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-16 17:19:30.891   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:19:30.891   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:19:30.891   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 17:19:30.896   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-16 17:19:30.896   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-16 17:19:30.896   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 17:19:30.896   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 17:19:30.896   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 17:19:30.896   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 17:19:30.896   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 17:19:30.896   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 17:19:30.896   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-16 17:19:30.896   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-16 17:19:30.896   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-16 17:19:30.896   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 17:19:30.896   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 17:19:30.896   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:19:30.896   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 17:19:30.896   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-16 17:19:30.896   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 17:19:30.896   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 17:19:30.896   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 17:19:30.896   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 17:19:30.896   873   886 E DropBoxManagerService: 	... 13 more
,08-16 17:19:30.904   873   884 I ActivityManager: Start proc 4363:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-16 17:19:30.905  1953  2033 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-16 17:19:30.905  1953  2033 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1953
08-16 17:19:30.905  1953  2033 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 17:19:30.905  1953  2033 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 17:19:30.905  1953  2033 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 17:19:30.905  1953  2033 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 17:19:30.905  1953  2033 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 17:19:30.905  1953  2033 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 17:19:30.905  1953  2033 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-16 17:19:30.905  1953  2033 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-16 17:19:30.905  1953  2033 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 17:19:30.905  1953  2033 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 17:19:30.905  1953  2033 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:19:30.905  1953  2033 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 17:19:30.908   873  4343 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 17:19:30.908   873  4369 E DropBoxManagerService: Can't write: system_app_crash
08-16 17:19:30.908   873  4369 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-16 17:19:30.908   873  4369 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 17:19:30.908   873  4369 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 17:19:30.908   873  4369 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 17:19:30.908   873  4369 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 17:19:30.908   873  4369 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 17:19:30.908   873  4369 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 17:19:30.908   873  4369 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 17:19:30.908   873  4369 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 17:19:30.908   873  4369 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 17:19:30.908   873  4369 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 17:19:30.908   873  4369 E DropBoxManagerService: 	... 5 more
,08-16 17:19:30.912  1953  2033 I Process : Sending signal. PID: 1953 SIG: 9
,08-16 17:19:30.937  1861  4346 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-16 17:19:30.939  1861  4346 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-16 17:19:30.939  1861  4346 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-16 17:19:30.954  1861  4346 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-16 17:19:30.954  1861  4346 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-16 17:19:30.955  1861  4346 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-16 17:19:30.955  1861  4346 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-16 17:19:30.955  1861  4346 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-16 17:19:30.955  1861  4346 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-16 17:19:30.955  1861  4346 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-16 17:19:30.956  1861  4346 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-16 17:19:30.956  1861  4346 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-16 17:19:30.956  1861  4346 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-16 17:19:30.971   873  1686 I WindowState: WIN DEATH: Window{e8aaee4 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-16 17:19:30.971   873  3066 D GraphicsStats: Buffer count: 1
,08-16 17:19:30.987   873  1687 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1953) has died
,08-16 17:19:30.988   873  1687 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-16 17:19:30.990   873  1687 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-16 17:19:30.996  4349  4349 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-16 17:19:31.008  4349  4378 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 17:19:31.008  4349  4378 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:19:31.008  4349  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:19:31.008  4349  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:19:31.008  4349  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:19:31.008  4349  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:19:31.008  4349  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:19:31.008  4349  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:19:31.008  4349  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 17:19:31.008  4349  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:19:31.008  4349  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:19:31.008  4349  4378 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:19:31.008  4349  4378 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:19:31.008  4349  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:19:31.008  4349  4378 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 17:19:31.008  4349  4378 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 17:19:31.008  4349  4378 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 17:19:31.008  4349  4378 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 17:19:31.008  4349  4378 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 17:19:31.008  4349  4378 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:19:31.008  4349  4378 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:19:31.008  4349  4378 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:19:31.009  4349  4378 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 17:19:31.012   873   886 I ActivityManager: Start proc 4381:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 17:19:31.031   873  1964 I ActivityManager: Start proc 4393:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,08-16 17:19:31.044  4349  4395 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-16 17:19:31.063  4381  4381 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:19:31.063  4381  4381 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:19:31.063  4381  4381 D AndroidRuntime: Shutting down VM
,08-16 17:19:31.071  4381  4381 E AndroidRuntime: FATAL EXCEPTION: main
08-16 17:19:31.071  4381  4381 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4381
08-16 17:19:31.071  4381  4381 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 17:19:31.071  4381  4381 E AndroidRuntime: 	... 10 more
08-16 17:19:31.072   873  1686 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 17:19:31.073  4381  4381 I Process : Sending signal. PID: 4381 SIG: 9
,08-16 17:19:31.075   873  4408 E DropBoxManagerService: Can't write: system_app_crash
08-16 17:19:31.075   873  4408 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-16 17:19:31.075   873  4408 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 17:19:31.075   873  4408 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 17:19:31.075   873  4408 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 17:19:31.075   873  4408 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 17:19:31.075   873  4408 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 17:19:31.075   873  4408 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 17:19:31.075   873  4408 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 17:19:31.075   873  4408 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 17:19:31.075   873  4408 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 17:19:31.075   873  4408 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 17:19:31.075   873  4408 E DropBoxManagerService: 	... 5 more
,08-16 17:19:31.087  1691  4407 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-16 17:19:31.090  4393  4393 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-16 17:19:31.091  1691  4407 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-16 17:19:31.096  1691  4407 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,08-16 17:19:31.097  1691  4407 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,08-16 17:19:31.098   873   884 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4381) has died
,08-16 17:19:31.099   873   884 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-16 17:19:31.113   873   886 I ActivityManager: Start proc 4409:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 17:19:31.135  1493  1493 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-16 17:19:31.139  1493  1493 D AndroidRuntime: Shutting down VM
,08-16 17:19:31.142  1493  1493 E AndroidRuntime: FATAL EXCEPTION: main
08-16 17:19:31.142  1493  1493 E AndroidRuntime: Process: com.google.process.gapps, PID: 1493
08-16 17:19:31.142  1493  1493 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 17:19:31.142  1493  1493 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-16 17:19:31.142  1493  1493 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-16 17:19:31.142  1493  1493 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-16 17:19:31.142  1493  1493 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:19:31.142  1493  1493 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:19:31.142  1493  1493 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:19:31.142  1493  1493 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:19:31.142  1493  1493 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:19:31.142  1493  1493 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 17:19:31.142  1493  1493 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 17:19:31.142  1493  1493 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 17:19:31.142  1493  1493 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 17:19:31.142  1493  1493 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 17:19:31.142  1493  1493 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 17:19:31.142  1493  1493 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 17:19:31.142  1493  1493 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-16 17:19:31.142  1493  1493 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-16 17:19:31.142  1493  1493 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-16 17:19:31.142  1493  1493 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-16 17:19:31.142  1493  1493 E AndroidRuntime: 	... 8 more
,08-16 17:19:31.145   873  4424 E DropBoxManagerService: Can't write: system_app_crash
08-16 17:19:31.145   873  4424 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-16 17:19:31.145   873  4424 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 17:19:31.145   873  4424 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 17:19:31.145   873  4424 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 17:19:31.145   873  4424 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 17:19:31.145   873  4424 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 17:19:31.145   873  4424 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 17:19:31.145   873  4424 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 17:19:31.145   873  4424 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 17:19:31.145   873  4424 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 17:19:31.145   873  4424 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 17:19:31.145   873  4424 E DropBoxManagerService: 	... 5 more
,08-16 17:19:31.147  1493  1493 I Process : Sending signal. PID: 1493 SIG: 9
08-16 17:19:31.148   873  4343 I ActivityManager: Killing 3677:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-16 17:19:31.158  4409  4409 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:19:31.158  4409  4409 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 17:19:31.158  4409  4409 D AndroidRuntime: Shutting down VM
,08-16 17:19:31.185  4349  4378 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,08-16 17:19:31.189  4349  4395 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:19:31.189  4349  4395 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 17:19:31.190  4349  4395 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-16 17:19:31.190  4349  4395 E AndroidRuntime: Process: android.process.acore, PID: 4349
08-16 17:19:31.190  4349  4395 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:19:31.190  4349  4395 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 17:19:31.193   873  1304 D WifiService: Client connection lost with reason: 4
,08-16 17:19:31.196  4349  4378 I Process : Sending signal. PID: 4349 SIG: 9
,08-16 17:19:31.218  4409  4409 E AndroidRuntime: FATAL EXCEPTION: main
08-16 17:19:31.218  4409  4409 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4409
08-16 17:19:31.218  4409  4409 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 17:19:31.218  4409  4409 E AndroidRuntime: 	... 10 more
08-16 17:19:31.218   873  4426 E DropBoxManagerService: Can't write: system_app_crash
08-16 17:19:31.218   873  4426 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-16 17:19:31.218   873  4426 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 17:19:31.218   873  4426 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 17:19:31.218   873  4426 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 17:19:31.218   873  4426 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 17:19:31.218   873  4426 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 17:19:31.218   873  4426 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 17:19:31.218   873  4426 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 17:19:31.218   873  4426 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 17:19:31.218   873  4426 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 17:19:31.218   873  4426 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 17:19:31.218   873  4426 E DropBoxManagerService: 	... 5 more
08-16 17:19:31.218   279   279 E lowmemorykiller: Error writing /proc/4349/oom_score_adj; errno=22
08-16 17:19:31.219   873  1688 I ActivityManager: Process com.google.process.gapps (pid 1493) has died
08-16 17:19:31.219   873  1688 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
08-16 17:19:31.219   873  1688 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
,08-16 17:19:31.220   873  1688 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
08-16 17:19:31.221   279   279 E lowmemorykiller: Error writing /proc/4349/oom_score_adj; errno=22,
,08-16 17:19:31.223  1691  1691 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-16 17:19:31.224   873  1380 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 17:19:31.225   873  4427 E DropBoxManagerService: Can't write: system_app_crash
08-16 17:19:31.225   873  4427 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-16 17:19:31.225   873  4427 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 17:19:31.225   873  4427 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 17:19:31.225   873  4427 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 17:19:31.225   873  4427 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 17:19:31.225   873  4427 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 17:19:31.225   873  4427 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 17:19:31.225   873  4427 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 17:19:31.225   873  4427 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 17:19:31.225   873  4427 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 17:19:31.225   873  4427 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 17:19:31.225   873  4427 E DropBoxManagerService: 	... 5 more
08-16 17:19:31.226  4409  4409 I Process : Sending signal. PID: 4409 SIG: 9
,08-16 17:19:31.248   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
