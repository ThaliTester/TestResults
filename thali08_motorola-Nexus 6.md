#### Test 79751015cf21110_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-09 07:50:54.832  1907  1907 I ConfigFetchService: fetch service done; releasing wakelock
,08-09 07:50:54.835  1907  1907 I ConfigFetchService: stopping self
08-09 07:50:55.517  3653  3653 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-09 07:50:55.522  3653  3653 D AndroidRuntime: CheckJNI is OFF
08-09 07:50:55.559  3653  3653 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-09 07:50:55.602  3653  3653 I Radio-JNI: register_android_hardware_Radio DONE
08-09 07:50:55.623  3653  3653 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-09 07:50:55.633   874  1738 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-09 07:50:55.680  3653  3653 D AndroidRuntime: Shutting down VM
08-09 07:50:55.686  1807  1827 W SearchService: Abort, client detached.
08-09 07:50:55.690  1807  2153 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@dc5860f
08-09 07:50:55.692  1807  1807 I HotwordDetector: Closing mic
08-09 07:50:55.692  1807  2158 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-09 07:50:55.718   874  1772 I ActivityManager: Start proc 3662:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-09 07:50:55.755   376  2160 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-09 07:50:55.756   376  2160 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-09 07:50:55.760   376  1278 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-09 07:50:55.762  1807  2156 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-09 07:50:55.763  1807  2157 I MicroRecognitionRnrImpl: Detection finished
08-09 07:50:55.803  3662  3662 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-09 07:50:55.831  3662  3662 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-09 07:50:55.838  3662  3662 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5684-5686)
08-09 07:50:55.838  3662  3662 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-09 07:50:55.864  3662  3662 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {65f3e72}
08-09 07:50:55.865  3662  3662 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-09 07:50:55.866  3662  3662 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-09 07:50:55.885  3662  3662 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-09 07:50:55.886  3662  3662 E SysUtils: ApplicationContext is null in ApplicationStatus
08-09 07:50:55.904  3662  3662 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-09 07:50:55.914  3662  3662 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-09 07:50:55.914  3662  3662 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-09 07:50:55.914  3662  3662 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-09 07:50:55.914  3662  3662 I Adreno  : Build Date                       : 10/20/15
08-09 07:50:55.914  3662  3662 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-09 07:50:55.914  3662  3662 I Adreno  : Local Branch                     : M14
08-09 07:50:55.914  3662  3662 I Adreno  : Remote Branch                    : 
08-09 07:50:55.914  3662  3662 I Adreno  : Remote Branch                    : 
08-09 07:50:55.914  3662  3662 I Adreno  : Reconstruct Branch               : 
08-09 07:50:55.982   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@fdac9c5:true
08-09 07:50:56.035  3662  3662 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-09 07:50:56.053  3662  3662 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
08-09 07:50:56.137  3662  3702 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
08-09 07:50:56.151  3662  3688 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-09 07:50:56.184  3662  3702 I OpenGLRenderer: Initialized EGL, version 1.4
08-09 07:50:56.257   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +566ms
08-09 07:50:56.262  1659  1659 I Keyboard.Facilitator: onFinishInput()
08-09 07:50:56.360  3662  3662 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3662
08-09 07:50:56.467  3662  3662 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-09 07:50:56.523   874  1384 I ActivityManager: Killing 2849:com.google.android.calendar/u0a37 (adj 15): empty #17
08-09 07:50:56.560   874  1384 I ActivityManager: Killing 2991:com.google.android.apps.maps/u0a65 (adj 15): empty #18
08-09 07:50:56.699  3662  3704 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1714816720
08-09 07:50:56.705  3662  3704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-09 07:50:56.705  3662  3704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-09 07:50:56.705  3662  3704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-09 07:50:56.705  3662  3704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-09 07:50:56.705  3662  3704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-09 07:50:56.705  3662  3704 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9e4b56 added. We now have 1 listener(s)
08-09 07:50:56.711  3662  3704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
08-09 07:50:56.712  3662  3704 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-09 07:50:56.713  3662  3704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 07:50:56.713  3662  3704 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 07:50:56.717  3662  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-09 07:50:56.717  3662  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-09 07:50:56.717  3662  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-09 07:50:56.717  3662  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-09 07:50:56.717  3662  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-09 07:50:56.717  3662  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-09 07:50:56.717  3662  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-09 07:50:56.717  3662  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-09 07:50:56.717  3662  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-09 07:50:56.717  3662  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-09 07:50:56.717  3662  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-09 07:50:56.717  3662  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-09 07:50:56.717  3662  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-09 07:50:56.717  3662  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-09 07:50:56.717  3662  3704 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f4093ad added. We now have 1 listener(s)
08-09 07:50:56.717  3662  3704 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 07:50:56.723   874  1309 D WifiService: New client listening to asynchronous messages
08-09 07:50:56.724  3662  3704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 07:50:56.724  3662  3704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-09 07:50:56.724  3662  3704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-09 07:50:56.724  3662  3704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-09 07:50:56.724  3662  3704 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-09 07:50:56.732  3662  3704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 07:50:56.733  3662  3704 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-09 07:50:56.747  3662  3704 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-09 07:50:56.748  3662  3704 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 07:50:56.748  3662  3704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:50:56.748  3662  3704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:50:56.748  3662  3704 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:50:56.748  3662  3704 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 07:50:56.748  3662  3704 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: 00:1f:27:54:70:c0
08-09 07:50:56.748  3662  3704 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 07:50:56.748  3662  3704 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 07:50:56.748  3662  3704 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-09 07:50:56.748  3662  3704 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 07:50:56.749  3662  3704 I io.jxcore.node.LifeCycleMonitor: start: OK
08-09 07:50:56.814  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:50:56.815  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:50:56.817  3662  3662 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-09 07:50:57.546   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-09 07:50:57.684  3662  3713 W jxcore-log: Initializing JXcore engine
08-09 07:50:57.684  3662  3713 W jxcore-log: JXcore engine is ready
08-09 07:50:57.725  3713  3713 W Thread-325: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8984 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-09 07:50:57.725  3713  3713 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13075]" dev="sockfs" ino=13075 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-09 07:50:57.725  3713  3713 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-09 07:50:57.725  3713  3713 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25933]" dev="sockfs" ino=25933 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-09 07:50:57.737  3662  3713 W jxcore-log: Starting JXcore engine
,08-09 07:50:57.861  3662  3713 W jxcore-log: Platform android
08-09 07:50:57.861  3662  3713 W jxcore-log: 
08-09 07:50:57.861  3662  3713 W jxcore-log: Process ARCH arm
08-09 07:50:57.861  3662  3713 W jxcore-log: 
,08-09 07:50:58.085  3662  3713 I jxcore-log: JXcore Cordova bridge is ready!
08-09 07:50:58.085  3662  3713 I jxcore-log: 
08-09 07:50:58.086  3662  3713 W jxcore-log: JXcore engine is started
,08-09 07:50:58.095  3662  3704 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-09 07:50:58.101  3662  3662 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-09 07:50:58.215   874  2021 D NetlinkSocketObserver: NeighborEvent{elapsedMs=108063, 10.76.36.21, [000C29197AF9], RTM_NEWNEIGH, NUD_PROBE}
,08-09 07:50:58.269   874  2021 D NetlinkSocketObserver: NeighborEvent{elapsedMs=108116, 10.76.36.1, [001C7F369383], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 07:50:59.888  1515  1515 I ConfigService: onDestroy
,08-09 07:51:07.596   874   887 I ActivityManager: Waited long enough for: ServiceRecord{1c9166f u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,08-09 07:51:07.834   874  1773 I ActivityManager: Start proc 3723:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-09 07:51:07.865   874  1772 I ActivityManager: Start proc 3735:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,08-09 07:51:07.879  3723  3723 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-09 07:51:07.893  3735  3735 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-09 07:51:07.927  3735  3735 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-09 07:51:07.943  3723  3749 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-09 07:51:07.951  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-09 07:51:07.953  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:51:07.973  3735  3764 V GoogleAuthProtoRequest: [321] a.<init>: mAccountName set to: thalitester@gmail.com
,08-09 07:51:08.001  3723  3749 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-09 07:51:08.013  1515  2416 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-09 07:51:08.013  1515  2416 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-09 07:51:08.013  1515  2416 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:51:08.014  1515  2416 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:51:08.033  3723  3749 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-09 07:51:08.043  3735  3764 W ExperimentUpdateService: [321] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-09 07:51:08.044  3735  3764 W ExperimentUpdateService: [321] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-09 07:51:08.044  3735  3764 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-09 07:51:08.044  3735  3764 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-09 07:51:08.044  3735  3764 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-09 07:51:08.044  3735  3764 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-09 07:51:08.044  3735  3764 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-09 07:51:08.044  3735  3764 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-09 07:51:08.044  3735  3764 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-09 07:51:08.044  3735  3764 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-09 07:51:08.044  3735  3764 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-09 07:51:08.044  3735  3764 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-09 07:51:08.104  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:51:08.116  3723  3723 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-09 07:51:08.146  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:51:08.163  3781  3781 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-1382872381.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-1382872381.dex
,08-09 07:51:08.171  1515  2067 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-09 07:51:08.171  1515  2067 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-09 07:51:08.171  1515  2067 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 07:51:08.171  1515  2067 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:51:08.184  3397  3397 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-09 07:51:08.184  3397  3397 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-09 07:51:08.184  3397  3397 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 1.
,08-09 07:51:08.211  3781  3781 I dex2oat : dex2oat took 48.736ms (threads: 4) arena alloc=321KB java alloc=29KB native alloc=1513KB free=1558KB
,08-09 07:51:08.257  3723  3723 W InstanceID/Rpc: Found 10011
,08-09 07:51:08.314   874  1384 I ActivityManager: Killing 3292:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-09 07:51:08.362   874  1384 I ActivityManager: Killing 3087:com.google.android.gm/u0a78 (adj 15): empty #18
,08-09 07:51:08.516  1515  3831 I VacuumService: Vacuum at: now=1470721868516 tag=VacuumService
,08-09 07:51:08.691  1515  3832 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-09 07:51:08.694  1515  3832 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-09 07:51:08.724  1515  3832 W Uploader:  no longer exists, so no auth token.
,08-09 07:51:09.597  1515  3832 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-09 07:51:09.597  1515  3832 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-09 07:51:09.598  1515  3832 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 07:51:09.598  1515  3832 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:51:09.629  1515  3832 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-09 07:51:09.629  1515  3832 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-09 07:51:09.629  1515  3832 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-09 07:51:09.629  1515  3832 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-09 07:51:09.629  1515  3832 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-09 07:51:09.629  1515  3832 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-09 07:51:09.629  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-09 07:51:09.629  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-09 07:51:09.629  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-09 07:51:09.629  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-09 07:51:09.629  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-09 07:51:09.629  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-09 07:51:09.629  1515  3832 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-09 07:51:09.641   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-09 07:51:10.783  1515  3832 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-09 07:51:10.783  1515  3832 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-09 07:51:10.783  1515  3832 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:51:10.783  1515  3832 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:51:10.808  1515  3832 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-09 07:51:10.808  1515  3832 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-09 07:51:10.808  1515  3832 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-09 07:51:10.808  1515  3832 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-09 07:51:10.808  1515  3832 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-09 07:51:10.808  1515  3832 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-09 07:51:10.808  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-09 07:51:10.808  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-09 07:51:10.808  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-09 07:51:10.808  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-09 07:51:10.808  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-09 07:51:10.808  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-09 07:51:10.808  1515  3832 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-09 07:51:11.083  1515  3832 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-09 07:51:11.083  1515  3832 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-09 07:51:11.083  1515  3832 I GLSUser : [GLSUser] Extracting token using key: Auth,
,08-09 07:51:11.084  1515  3832 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:51:11.123  1515  3832 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-09 07:51:11.123  1515  3832 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-09 07:51:11.123  1515  3832 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-09 07:51:11.123  1515  3832 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-09 07:51:11.123  1515  3832 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-09 07:51:11.123  1515  3832 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-09 07:51:11.123  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-09 07:51:11.123  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-09 07:51:11.123  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-09 07:51:11.123  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-09 07:51:11.123  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-09 07:51:11.123  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-09 07:51:11.123  1515  3832 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-09 07:51:11.432  1515  3832 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-09 07:51:11.433  1515  3832 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-09 07:51:11.433  1515  3832 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 07:51:11.433  1515  3832 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:51:11.475  1515  3832 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-09 07:51:11.475  1515  3832 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-09 07:51:11.475  1515  3832 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-09 07:51:11.475  1515  3832 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-09 07:51:11.475  1515  3832 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-09 07:51:11.475  1515  3832 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-09 07:51:11.475  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-09 07:51:11.475  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-09 07:51:11.475  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-09 07:51:11.475  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-09 07:51:11.475  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-09 07:51:11.475  1515  3832 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-09 07:51:11.475  1515  3832 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-09 07:51:14.468  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-09 07:51:14.468  3662  3713 I jxcore-log: 
,08-09 07:51:14.471  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-09 07:51:14.471  3662  3713 I jxcore-log: 
,08-09 07:51:14.478  3662  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 07:51:14.478  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:14.478  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:14.478  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:51:14.478  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 07:51:14.478  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: 00:1f:27:54:70:c0
08-09 07:51:14.478  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 07:51:14.478  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 07:51:14.481  3662  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: 00:1f:27:54:70:c0
,08-09 07:51:14.484  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-09 07:51:14.484  3662  3713 I jxcore-log: 
,08-09 07:51:14.485  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-09 07:51:14.485  3662  3713 I jxcore-log: 
,08-09 07:51:14.827  3662  3713 D ExecuteNativeTests: Running unit tests
,08-09 07:51:14.885  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 07:51:14.885  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 added. We now have 2 listener(s)
,08-09 07:51:14.886  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-09 07:51:14.887  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-09 07:51:14.887  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-09 07:51:14.887  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-09 07:51:14.887  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 added. We now have 2 listener(s)
,08-09 07:51:14.887  3662  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 07:51:14.888  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 07:51:14.891  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 07:51:14.900  3662  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 07:51:14.900  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:14.900  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:14.900  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:51:14.900  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 07:51:14.900  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: 00:1f:27:54:70:c0
08-09 07:51:14.900  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 07:51:14.900  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 07:51:14.904  3662  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: 00:1f:27:54:70:c0
,08-09 07:51:14.905  3662  3713 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-09 07:51:14.911  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-09 07:51:14.914  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 07:51:14.915  3662  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 07:51:14.915  3662  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-09 07:51:14.917  3662  3713 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-09 07:51:14.919  3662  3713 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-09 07:51:14.919  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-09 07:51:14.919  3662  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-09 07:51:14.919  3662  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-09 07:51:14.919  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-09 07:51:14.920  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-09 07:51:14.920  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-09 07:51:14.920  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-09 07:51:14.920  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:14.921  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 07:51:14.921  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 07:51:14.921  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 removed from the list
,08-09 07:51:14.921  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:14.921  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 removed from the list
08-09 07:51:14.923  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:14.923  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:14.923  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:14.925  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 07:51:14.926  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:14.927  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:14.928  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:14.928  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 07:51:14.928  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:14.929  3662  3713 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-09 07:51:14.930  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 07:51:14.930  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:14.930  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 07:51:14.930  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-09 07:51:14.930  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:14.930  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:14.930  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
08-09 07:51:14.930  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:14.930  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:14.930  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:14.930  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:14.930  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:14.930  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:14.931  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 07:51:14.932  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:14.932  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:14.932  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:14.933  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
,08-09 07:51:14.938  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-09 07:51:14.938  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-09 07:51:14.938  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-09 07:51:14.938  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-09 07:51:14.938  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-09 07:51:14.938  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-09 07:51:14.938  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-09 07:51:14.938  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-09 07:51:14.938  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-09 07:51:14.938  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-09 07:51:14.938  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-09 07:51:14.938  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-09 07:51:14.938  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,08-09 07:51:14.938  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-09 07:51:14.938  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-09 07:51:14.938  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-09 07:51:14.938  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-09 07:51:14.939  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-09 07:51:14.939  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-09 07:51:14.939  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-09 07:51:14.939  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-09 07:51:14.939  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-09 07:51:14.939  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-09 07:51:14.939  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-09 07:51:14.939  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-09 07:51:14.939  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-09 07:51:14.939  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-09 07:51:14.939  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-09 07:51:14.939  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-09 07:51:14.939  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,08-09 07:51:14.939  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-09 07:51:14.939  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 07:51:14.939  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:14.939  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 07:51:14.939  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:14.940  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 07:51:14.940  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:14.940  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
08-09 07:51:14.940  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:14.940  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:14.940  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:14.940  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:14.940  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:14.940  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:14.940  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:14.941  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:14.941  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-09 07:51:14.941  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:14.942  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:14.942  3662  3713 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-09 07:51:14.944  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 07:51:14.949  3662  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 07:51:14.949  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:14.949  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:14.949  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:51:14.949  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 07:51:14.949  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: 00:1f:27:54:70:c0
08-09 07:51:14.949  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 07:51:14.949  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 07:51:14.951  3662  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: 00:1f:27:54:70:c0
08-09 07:51:14.951  3662  3713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 07:51:14.951  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-09 07:51:14.951  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 07:51:14.951  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 07:51:14.951  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 07:51:14.951  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 07:51:14.953  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 07:51:14.956  3662  3713 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-09 07:51:14.956  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-09 07:51:14.957  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 07:51:14.962  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-09 07:51:14.963  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-09 07:51:14.964  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-09 07:51:14.967  3662  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-09 07:51:14.972  3662  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-09 07:51:14.972  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-09 07:51:14.973  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-09 07:51:14.975  3662  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
,08-09 07:51:14.976  3662  3713 D BluetoothAdapter: STATE_ON
,08-09 07:51:14.981  2560  2767 D BtGatt.GattService: registerClient() - UUID=415c1f3b-f40b-4c3b-9678-0e3142508fd8
,08-09 07:51:14.982  2560  2611 D BtGatt.GattService: onClientRegistered() - UUID=415c1f3b-f40b-4c3b-9678-0e3142508fd8, clientIf=5
08-09 07:51:14.982  3662  3673 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-09 07:51:14.983  2560  2574 D BtGatt.GattService: start scan with filters
,08-09 07:51:14.987  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-09 07:51:14.988  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-09 07:51:14.988  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-09 07:51:14.988  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-09 07:51:14.988  2560  2615 D BtGatt.ScanManager: handling starting scan
,08-09 07:51:14.994  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-09 07:51:14.994  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-09 07:51:14.994  3662  3662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-09 07:51:14.995  2560  2615 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f3976c
08-09 07:51:14.996  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-09 07:51:14.998  3662  3713 I io.jxcore.node.ConnectionHelper: start: OK
,08-09 07:51:15.001  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-09 07:51:15.001  3662  3713 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-09 07:51:15.001  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-09 07:51:15.001  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-09 07:51:15.002  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 07:51:15.002  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-09 07:51:15.002  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-09 07:51:15.002  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-09 07:51:15.002  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-09 07:51:15.002  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-09 07:51:15.003  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-09 07:51:15.003  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-09 07:51:15.004  3662  3713 D BluetoothAdapter: STATE_ON
08-09 07:51:15.004  2560  2611 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-09 07:51:15.004  2560  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:15.005  2560  2573 D BtGatt.GattService: stopScan() - queue size =1
08-09 07:51:15.006  2560  2767 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-09 07:51:15.006  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 07:51:15.007  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-09 07:51:15.007  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-09 07:51:15.007  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-09 07:51:15.008  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-09 07:51:15.007  2560  2615 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-09 07:51:15.009  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 07:51:15.010  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-09 07:51:15.010  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-09 07:51:15.010  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-09 07:51:15.011  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 07:51:15.012  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-09 07:51:15.012  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 07:51:15.012  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 07:51:15.012  3662  3662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-09 07:51:15.012  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
08-09 07:51:15.012  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.012  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.012  3662  3662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-09 07:51:15.012  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:15.012  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.013  3662  3662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-09 07:51:15.013  3662  3713 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-09 07:51:15.015  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 07:51:15.016  2560  2611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-09 07:51:15.016  2560  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:15.016  2560  2615 D BtGatt.ScanManager: Starting BLE batch scan
,08-09 07:51:15.016  2560  2615 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-09 07:51:15.021  3662  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 07:51:15.021  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:15.021  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:15.021  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:51:15.021  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 07:51:15.021  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: 00:1f:27:54:70:c0
08-09 07:51:15.021  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 07:51:15.021  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 07:51:15.024  3662  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: 00:1f:27:54:70:c0
08-09 07:51:15.024  3662  3713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 07:51:15.024  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-09 07:51:15.024  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 07:51:15.024  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 07:51:15.024  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 07:51:15.024  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 07:51:15.025  2560  2611 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-09 07:51:15.025  2560  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:15.027  3662  3713 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-09 07:51:15.027  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-09 07:51:15.028  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:15.030  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:15.031  2560  2611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-09 07:51:15.031  2560  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-09 07:51:15.035  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-09 07:51:15.036  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-09 07:51:15.037  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-09 07:51:15.039  2560  2611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-09 07:51:15.040  2560  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:15.040  2560  2615 D BtGatt.ScanManager: stopping BLe Batch
,08-09 07:51:15.043  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-09 07:51:15.043  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-09 07:51:15.043  3662  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-09 07:51:15.043  3662  3713 D BluetoothAdapter: STATE_ON
,08-09 07:51:15.045  2560  2573 D BtGatt.GattService: registerClient() - UUID=9f4a6243-83b3-4fdf-bee6-1033a2d679c5
,08-09 07:51:15.046  2560  2611 D BtGatt.GattService: onClientRegistered() - UUID=9f4a6243-83b3-4fdf-bee6-1033a2d679c5, clientIf=5
08-09 07:51:15.048  2560  2611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-09 07:51:15.048  2560  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-09 07:51:15.049  2560  2615 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-09 07:51:15.049  3662  3673 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-09 07:51:15.049  2560  2767 D BtGatt.GattService: start scan with filters
,08-09 07:51:15.053  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-09 07:51:15.053  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-09 07:51:15.053  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-09 07:51:15.053  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-09 07:51:15.054  2560  2611 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-09 07:51:15.054  2560  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-09 07:51:15.056  2560  2615 D BtGatt.ScanManager: handling starting scan
,08-09 07:51:15.056  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-09 07:51:15.057  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-09 07:51:15.057  3662  3662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-09 07:51:15.058  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-09 07:51:15.060  3662  3713 I io.jxcore.node.ConnectionHelper: start: OK
,08-09 07:51:15.062  2560  2611 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-09 07:51:15.062  2560  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:15.063  2560  2615 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-09 07:51:15.063  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 07:51:15.063  3662  3713 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-09 07:51:15.063  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:15.063  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-09 07:51:15.063  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.064  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 07:51:15.064  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-09 07:51:15.064  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-09 07:51:15.064  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-09 07:51:15.064  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-09 07:51:15.064  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-09 07:51:15.064  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-09 07:51:15.065  3662  3713 D BluetoothAdapter: STATE_ON
08-09 07:51:15.065  2560  2766 D BtGatt.GattService: stopScan() - queue size =1
08-09 07:51:15.066  2560  2573 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-09 07:51:15.066  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-09 07:51:15.066  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-09 07:51:15.066  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-09 07:51:15.067  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-09 07:51:15.067  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-09 07:51:15.068  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 07:51:15.068  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-09 07:51:15.068  2560  2611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-09 07:51:15.068  2560  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:15.069  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-09 07:51:15.069  2560  2615 D BtGatt.ScanManager: Starting BLE batch scan
08-09 07:51:15.069  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 07:51:15.069  2560  2615 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-09 07:51:15.069  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 07:51:15.070  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:15.070  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 07:51:15.070  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 07:51:15.070  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
08-09 07:51:15.070  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.070  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.070  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:15.070  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.070  3662  3662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 07:51:15.070  3662  3662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 07:51:15.070  3662  3662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 07:51:15.071  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.071  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.072  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:15.072  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:15.072  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 07:51:15.072  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.073  3662  3713 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-09 07:51:15.075  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 07:51:15.078  2560  2611 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-09 07:51:15.078  2560  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-09 07:51:15.081  3662  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 07:51:15.081  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:15.081  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:15.081  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:51:15.081  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 07:51:15.081  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: 00:1f:27:54:70:c0
08-09 07:51:15.081  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 07:51:15.081  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 07:51:15.082  3662  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: 00:1f:27:54:70:c0
08-09 07:51:15.082  3662  3713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 07:51:15.082  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 07:51:15.082  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 07:51:15.082  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 07:51:15.083  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 07:51:15.083  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 07:51:15.084  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:15.085  2560  2611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-09 07:51:15.085  2560  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:15.086  3662  3713 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-09 07:51:15.086  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-09 07:51:15.087  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:15.090  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-09 07:51:15.092  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-09 07:51:15.092  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-09 07:51:15.093  2560  2611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-09 07:51:15.093  2560  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:15.093  2560  2615 D BtGatt.ScanManager: stopping BLe Batch
08-09 07:51:15.096  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-09 07:51:15.096  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-09 07:51:15.096  3662  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-09 07:51:15.097  3662  3713 D BluetoothAdapter: STATE_ON
08-09 07:51:15.099  2560  2573 D BtGatt.GattService: registerClient() - UUID=2051b005-f73e-4644-a497-eac8dc71495d
08-09 07:51:15.099  2560  2611 D BtGatt.GattService: onClientRegistered() - UUID=2051b005-f73e-4644-a497-eac8dc71495d, clientIf=5
08-09 07:51:15.100  2560  2611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-09 07:51:15.100  2560  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:15.100  3662  3673 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-09 07:51:15.100  2560  2754 D BtGatt.GattService: start scan with filters
08-09 07:51:15.100  2560  2615 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-09 07:51:15.103  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-09 07:51:15.103  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-09 07:51:15.103  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-09 07:51:15.103  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-09 07:51:15.105  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-09 07:51:15.105  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-09 07:51:15.105  3662  3662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-09 07:51:15.106  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-09 07:51:15.107  2560  2611 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-09 07:51:15.107  2560  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:15.108  3662  3713 I io.jxcore.node.ConnectionHelper: start: OK
08-09 07:51:15.108  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 07:51:15.108  3662  3713 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-09 07:51:15.108  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:15.108  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-09 07:51:15.108  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.108  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 07:51:15.108  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-09 07:51:15.108  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-09 07:51:15.108  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-09 07:51:15.108  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-09 07:51:15.108  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-09 07:51:15.108  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-09 07:51:15.109  3662  3713 D BluetoothAdapter: STATE_ON
08-09 07:51:15.109  2560  2615 D BtGatt.ScanManager: handling starting scan
08-09 07:51:15.109  2560  2573 D BtGatt.GattService: stopScan() - queue size =0
08-09 07:51:15.110  2560  2754 D BtGatt.GattService: unregisterClient() - clientIf=5
08-09 07:51:15.110  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 07:51:15.110  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-09 07:51:15.110  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-09 07:51:15.110  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-09 07:51:15.110  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-09 07:51:15.111  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 07:51:15.111  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-09 07:51:15.111  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-09 07:51:15.111  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 07:51:15.111  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 07:51:15.112  3662  3662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 07:51:15.112  3662  3662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 07:51:15.112  3662  3662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 07:51:15.113  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 07:51:15.113  3662  3713 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-09 07:51:15.113  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:15.113  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 07:51:15.113  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:15.113  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.113  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 07:51:15.113  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
08-09 07:51:15.113  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.113  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.113  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:15.114  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.114  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.114  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.115  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:15.115  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:15.115  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.115  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.115  3662  3713 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-09 07:51:15.116  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 07:51:15.116  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:15.116  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 07:51:15.116  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:15.116  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.116  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.116  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
08-09 07:51:15.116  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.116  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.116  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:15.116  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.116  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.116  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.117  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.117  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:15.117  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:15.117  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.117  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.117  2560  2611 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-09 07:51:15.118  2560  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:15.118  2560  2615 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-09 07:51:15.118  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-09 07:51:15.118  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 07:51:15.118  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:15.118  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 07:51:15.119  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:15.119  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.119  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.119  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
08-09 07:51:15.119  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.119  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.119  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:15.119  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.119  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.119  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.119  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.120  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:15.120  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:15.120  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.120  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.121  3662  3713 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-09 07:51:15.121  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 07:51:15.121  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:15.121  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 07:51:15.121  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:15.121  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.121  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.121  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
08-09 07:51:15.121  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.121  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.121  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:15.121  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.122  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.122  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.122  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 07:51:15.122  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:15.122  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:15.122  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.122  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.123  3662  3713 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-09 07:51:15.123  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 07:51:15.123  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:15.123  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 07:51:15.123  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-09 07:51:15.123  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.123  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.124  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
08-09 07:51:15.124  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.124  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.124  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:15.124  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.124  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 07:51:15.124  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.124  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.124  2560  2611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-09 07:51:15.124  2560  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:15.124  2560  2615 D BtGatt.ScanManager: Starting BLE batch scan
08-09 07:51:15.124  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:15.124  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:15.124  2560  2615 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-09 07:51:15.125  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.125  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.125  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-09 07:51:15.126  3662  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 07:51:15.126  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-09 07:51:15.126  3662  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 07:51:15.126  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-09 07:51:15.126  3662  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-09 07:51:15.127  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 07:51:15.127  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:15.127  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 07:51:15.127  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:15.127  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.127  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.128  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
08-09 07:51:15.128  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.128  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.128  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:15.128  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.128  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.128  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.128  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.129  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:15.129  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:15.129  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.129  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.131  3662  3713 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 07:51:15.131  3662  3713 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-09 07:51:15.131  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-09 07:51:15.135  3662  3713 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 07:51:15.136  3662  3713 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-09 07:51:15.136  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-09 07:51:15.136  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-09 07:51:15.136  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-09 07:51:15.136  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-09 07:51:15.136  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-09 07:51:15.136  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-09 07:51:15.136  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-09 07:51:15.137  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-09 07:51:15.137  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-09 07:51:15.137  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-09 07:51:15.137  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-09 07:51:15.137  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-09 07:51:15.137  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-09 07:51:15.137  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-09 07:51:15.137  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-09 07:51:15.137  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-09 07:51:15.137  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-09 07:51:15.137  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-09 07:51:15.137  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-09 07:51:15.137  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-09 07:51:15.138  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-09 07:51:15.138  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-09 07:51:15.138  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-09 07:51:15.138  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-09 07:51:15.138  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-09 07:51:15.138  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-09 07:51:15.138  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-09 07:51:15.138  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-09 07:51:15.138  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-09 07:51:15.139  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-09 07:51:15.139  3662  3713 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-09 07:51:15.139  3662  3713 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-09 07:51:15.139  3662  3713 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-09 07:51:15.139  3662  3713 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 07:51:15.139  3662  3713 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-09 07:51:15.139  3662  3713 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
,08-09 07:51:15.139  3662  3713 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 07:51:15.139  3662  3713 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-09 07:51:15.139  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-09 07:51:15.142  2560  2611 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-09 07:51:15.142  2560  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:15.142  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-09 07:51:15.143  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-09 07:51:15.143  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-09 07:51:15.143  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-09 07:51:15.143  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-09 07:51:15.143  3662  3713 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-09 07:51:15.144  3662  3713 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-09 07:51:15.144  3662  3713 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-09 07:51:15.144  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 07:51:15.144  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:15.144  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 07:51:15.144  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-09 07:51:15.144  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.145  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.145  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-09 07:51:15.146  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
,08-09 07:51:15.146  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.146  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.146  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:15.146  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 07:51:15.146  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.146  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.146  3662  3845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 389)
,08-09 07:51:15.146  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.147  3662  3846 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 389
08-09 07:51:15.147  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:15.147  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:15.147  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.147  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.148  3662  3713 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-09 07:51:15.148  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-09 07:51:15.148  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-09 07:51:15.148  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-09 07:51:15.148  2560  2611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-09 07:51:15.148  2560  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:15.150  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-09 07:51:15.150  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.150  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 07:51:15.150  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
08-09 07:51:15.150  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.150  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
,08-09 07:51:15.150  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:15.150  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.150  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.150  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.150  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.151  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:15.151  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:15.151  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 07:51:15.151  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.151  3662  3713 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-09 07:51:15.152  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 07:51:15.152  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:15.152  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 07:51:15.152  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:15.152  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 07:51:15.152  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.152  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
08-09 07:51:15.152  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.152  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
,08-09 07:51:15.152  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:15.152  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 07:51:15.152  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.152  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.152  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.153  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:15.153  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:15.153  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 07:51:15.153  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.154  3662  3713 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-09 07:51:15.154  3662  3713 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-09 07:51:15.154  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-09 07:51:15.154  3662  3713 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-09 07:51:15.154  3662  3713 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-09 07:51:15.154  3662  3713 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-09 07:51:15.154  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-09 07:51:15.154  3662  3713 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-09 07:51:15.154  3662  3713 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-09 07:51:15.154  3662  3713 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,08-09 07:51:15.154  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-09 07:51:15.154  3662  3713 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-09 07:51:15.154  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-09 07:51:15.154  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:15.154  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 07:51:15.155  2560  2611 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-09 07:51:15.155  2560  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:15.154  3662  3845 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 07:51:15.155  2560  2615 D BtGatt.ScanManager: stopping BLe Batch
08-09 07:51:15.155  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:15.155  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.155  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.155  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
,08-09 07:51:15.155  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.155  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
,08-09 07:51:15.155  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:15.155  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.155  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 07:51:15.155  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.155  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 07:51:15.157  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:15.157  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:15.157  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 07:51:15.157  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.157  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-09 07:51:15.158  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.158  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 07:51:15.158  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
,08-09 07:51:15.158  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.158  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
,08-09 07:51:15.158  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:15.158  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 07:51:15.158  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.158  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.158  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list,
08-09 07:51:15.158  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:15.158  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 07:51:15.158  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.158  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
,08-09 07:51:15.158  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-09 07:51:15.158  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:15.158  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-09 07:51:15.159  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:15.159  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.159  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 07:51:15.159  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
08-09 07:51:15.159  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.159  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
,08-09 07:51:15.159  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:15.159  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.159  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 07:51:15.159  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.159  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.160  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-09 07:51:15.160  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:15.160  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.160  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
,08-09 07:51:15.162  3662  3713 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-09 07:51:15.162  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 07:51:15.162  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-09 07:51:15.163  3662  3713 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-09 07:51:15.163  3662  3713 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-09 07:51:15.163  3662  3662 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-09 07:51:15.163  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-09 07:51:15.163  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-09 07:51:15.163  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:15.164  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-09 07:51:15.164  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-09 07:51:15.164  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-09 07:51:15.164  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.164  3662  3713 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-09 07:51:15.164  3662  3662 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-09 07:51:15.164  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
08-09 07:51:15.164  2560  2611 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-09 07:51:15.164  2560  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:15.164  2560  2615 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-09 07:51:15.164  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.164  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-09 07:51:15.164  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-09 07:51:15.165  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-09 07:51:15.164  3662  3847 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 07:51:15.165  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 07:51:15.165  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.166  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 07:51:15.166  3662  3662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 07:51:15.166  3662  3662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 07:51:15.166  3662  3662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 07:51:15.166  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.166  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 07:51:15.166  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:15.166  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 07:51:15.166  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-09 07:51:15.166  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.166  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.166  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
08-09 07:51:15.166  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.167  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.167  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:15.167  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.167  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.167  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.167  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.167  3662  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-09 07:51:15.167  3662  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-09 07:51:15.167  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:15.167  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:15.167  3662  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-09 07:51:15.167  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.167  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.168  3662  3662 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-09 07:51:15.169  3662  3713 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-09 07:51:15.169  3662  3713 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-09 07:51:15.169  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-09 07:51:15.170  3662  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-09 07:51:15.171  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-09 07:51:15.171  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:15.171  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 07:51:15.171  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:15.171  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.171  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.171  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
08-09 07:51:15.171  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.171  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.171  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:15.172  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.172  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.172  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.172  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.174  2560  2611 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-09 07:51:15.174  2560  2611 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:15.174  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:15.174  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:15.174  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.174  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.178  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 07:51:15.178  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:15.178  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 07:51:15.178  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:15.178  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.178  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.178  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
08-09 07:51:15.178  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.178  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.179  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:15.179  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.179  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.179  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.179  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.180  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:15.180  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:15.180  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.180  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.181  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 07:51:15.181  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:15.181  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 07:51:15.181  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:15.181  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.181  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.181  3662  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fae916 not in the list
08-09 07:51:15.181  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.181  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.181  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:15.181  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.181  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.181  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:15.181  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:15.182  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:15.182  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:15.182  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:15.182  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1de2297 not in the list
08-09 07:51:15.183  3662  3713 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-09 07:51:15.183  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-09 07:51:15.183  3662  3713 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-09 07:51:15.183  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-09 07:51:15.184  3662  3713 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-09 07:51:15.184  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-09 07:51:15.185  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-09 07:51:15.186  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-09 07:51:15.186  3662  3713 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-09 07:51:15.186  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-09 07:51:15.186  3662  3713 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-09 07:51:15.186  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-09 07:51:15.186  3662  3713 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-09 07:51:15.187  3662  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-09 07:51:15.187  3662  3713 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-09 07:51:15.187  3662  3713 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-09 07:51:15.188  3662  3713 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-09 07:51:15.188  3662  3713 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-09 07:51:15.188  3662  3713 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-09 07:51:15.188  3662  3713 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-09 07:51:15.189  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 07:51:15.189  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b02a5a1 added. We now have 2 listener(s)
08-09 07:51:15.189  3662  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 07:51:15.191  3662  3713 D BluetoothAdapter: enable(): BT is already enabled..!
08-09 07:51:15.191   874  1385 D WifiService: setWifiEnabled: true pid=3662, uid=10000
08-09 07:51:15.191   874  1385 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-09 07:51:15.192  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 07:51:15.192  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a1dc3c6 added. We now have 3 listener(s)
08-09 07:51:15.192  3662  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 07:51:15.197  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 07:51:15.199  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@176df87 added. We now have 4 listener(s)
08-09 07:51:15.199  3662  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 07:51:15.203  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 07:51:15.203  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1227eb4 added. We now have 5 listener(s)
08-09 07:51:15.203  3662  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 07:51:15.205   874   885 D WifiService: setWifiEnabled: false pid=3662, uid=10000
08-09 07:51:15.205   874   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-09 07:51:15.209  2560  2607 D BluetoothAdapterState: Current state: ON, message: 23
08-09 07:51:15.209  2560  2607 D BluetoothAdapterProperties: Setting state to 13
08-09 07:51:15.209  2560  2607 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-09 07:51:15.209  2560  2607 D BluetoothAdapterProperties: onBluetoothDisable()
,08-09 07:51:15.211  2560  2560 D BluetoothMapService: onReceive
08-09 07:51:15.211  2560  2560 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 07:51:15.211  2560  2560 D BluetoothMapService: STATE_TURNING_OFF
08-09 07:51:15.211  2560  2560 D BluetoothMapService: MAP Service closeService in
,08-09 07:51:15.212  2560  2560 D BluetoothMapMasInstance0: MAP Service shutdown
08-09 07:51:15.212  2560  2560 D ObexServerSockets0: shutdown(block = true)
08-09 07:51:15.212  2560  2560 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-09 07:51:15.212  2560  2769 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-09 07:51:15.212  2560  2560 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-09 07:51:15.212  2560  2770 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-09 07:51:15.213  2560  2560 I BtOppRfcommListener: stopping Accept Thread
08-09 07:51:15.213  2560  3300 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 07:51:15.213  2560  2751 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-09 07:51:15.213  2560  3300 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-09 07:51:15.213  2560  2607 I BluetoothAdapterState: Entering PendingCommandState
08-09 07:51:15.214  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 07:51:15.215  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 07:51:15.215  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:15.215  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:15.215  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:51:15.215  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 07:51:15.215  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: 00:1f:27:54:70:c0
08-09 07:51:15.215  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 07:51:15.215  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 07:51:15.215  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 07:51:15.215  3662  3662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: 00:1f:27:54:70:c0
08-09 07:51:15.221  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=00:1f:27:54:70:c0 reason=3 locally_generated=1
08-09 07:51:15.224   874  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-09 07:51:15.224   874  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-09 07:51:15.224   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-09 07:51:15.224   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "ktwtestwifi"WPA_EAP to any
08-09 07:51:15.226   874   887 I ActivityManager: Start proc 3850:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-09 07:51:15.226  2560  2611 D BluetoothAdapterProperties: Scan Mode:20
08-09 07:51:15.228  2560  2607 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-09 07:51:15.230  2560  2560 D HeadsetService: Received stop request...Stopping profile...
08-09 07:51:15.232   874   874 D BluetoothHeadset: Proxy object disconnected
08-09 07:51:15.232  1723  1737 D BluetoothHeadset: Proxy object disconnected
08-09 07:51:15.232  1361  1377 D BluetoothHeadset: Proxy object disconnected
08-09 07:51:15.233   874   874 D BluetoothHeadset: Proxy object disconnected
08-09 07:51:15.233   874   874 D BluetoothHeadset: Proxy object disconnected
08-09 07:51:15.233  2560  2560 D A2dpService: Received stop request...Stopping profile...
08-09 07:51:15.234  2560  2757 D A2dpStateMachine: Exit Disconnected: -1
08-09 07:51:15.235   874  2022 D DhcpClient: Clearing IP address
08-09 07:51:15.235   874   874 D BluetoothA2dp: Proxy object disconnected
08-09 07:51:15.236   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-09 07:51:15.236  2560  2560 D HidService: Received stop request...Stopping profile...
08-09 07:51:15.237  2560  2560 D HidService: Stopping Bluetooth HidService
08-09 07:51:15.237  1361  1361 D HeadsetProfile: Bluetooth service disconnected
08-09 07:51:15.237  1361  1361 D BluetoothA2dp: Proxy object disconnected
08-09 07:51:15.237  2560  2560 V BluetoothAdapterState: isTurningOff()=true
08-09 07:51:15.237  1361  1361 D BluetoothInputDevice: Proxy object disconnected
08-09 07:51:15.238  2560  2560 V BluetoothAdapterState: isTurningOn()=false
08-09 07:51:15.238  2560  2560 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:15.238  2560  2560 V BluetoothAdapterState: isBleTurningOff()=false
08-09 07:51:15.238  1361  1361 D HidProfile: Bluetooth service disconnected
08-09 07:51:15.239   372   872 D CommandListener: Setting iface cfg
08-09 07:51:15.239  2560  2560 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-09 07:51:15.239  2560  2560 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-09 07:51:15.240  2560  2611 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-09 07:51:15.240  2560  2730 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 07:51:15.240  2560  2730 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 07:51:15.240  2560  2730 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 07:51:15.240  2560  2611 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-09 07:51:15.240  2560  2560 D HealthService: Received stop request...Stopping profile...
08-09 07:51:15.242  2560  2560 D PanService: Received stop request...Stopping profile...
08-09 07:51:15.243  1515  3465 V NativeCrypto: Read error: ssl=0xaeb6a600: I/O error during system call, Connection timed out
08-09 07:51:15.243  2560  2560 V BluetoothAdapterState: isTurningOff()=true
08-09 07:51:15.243  2560  2560 V BluetoothAdapterState: isTurningOn()=false
08-09 07:51:15.243  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-09 07:51:15.243  1361  1361 D PanProfile: Bluetooth service disconnected
08-09 07:51:15.243  2560  2560 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:15.244  2560  2560 V BluetoothAdapterState: isBleTurningOff()=false
08-09 07:51:15.244  1515  3465 V NativeCrypto: SSL shutdown failed: ssl=0xaeb6a600: I/O error during system call, Broken pipe
08-09 07:51:15.245   874  2025 D DhcpClient: Receive thread stopped
,08-09 07:51:15.246   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-09 07:51:15.247   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-09 07:51:15.249   395   395 E Parcel  : Reading a NULL string not supported here.
08-09 07:51:15.250  2560  2611 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-09 07:51:15.250  2560  2730 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 07:51:15.250  2560  2730 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 07:51:15.250  2560  2730 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 07:51:15.250  2560  2730 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 07:51:15.250  2560  2730 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 07:51:15.250  2560  2730 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 07:51:15.251  2560  2560 D BluetoothMapService: Received stop request...Stopping profile...
,08-09 07:51:15.251  2560  2560 D BluetoothMapService: stop()
08-09 07:51:15.251  2560  2560 D BluetoothMapAppObserver: deinitObservers()
08-09 07:51:15.251  2560  2560 D BluetoothMapAppObserver: removeReceiver()
08-09 07:51:15.253  2560  2560 V BluetoothAdapterState: isTurningOff()=true
08-09 07:51:15.253  2560  2560 V BluetoothAdapterState: isTurningOn()=false
08-09 07:51:15.253  2560  2560 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:15.253   874  1308 D WifiStateMachine: Start Disconnecting Watchdog 1
08-09 07:51:15.253  2560  2560 V BluetoothAdapterState: isBleTurningOff()=false
08-09 07:51:15.253  2560  2560 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-09 07:51:15.253  2560  2611 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-09 07:51:15.253  2560  2560 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-09 07:51:15.254  2560  2560 V BluetoothAdapterState: isTurningOff()=true
08-09 07:51:15.254  2560  2560 V BluetoothAdapterState: isTurningOn()=false
08-09 07:51:15.254  2560  2560 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:15.254  2560  2560 V BluetoothAdapterState: isBleTurningOff()=false
08-09 07:51:15.254  2560  2560 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-09 07:51:15.254  2560  2611 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-09 07:51:15.255  2560  2560 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-09 07:51:15.255   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-09 07:51:15.255  2560  2560 V BluetoothAdapterState: isTurningOff()=true
08-09 07:51:15.255  2560  2560 V BluetoothAdapterState: isTurningOn()=false
08-09 07:51:15.255  2560  2560 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:15.255  2560  2560 V BluetoothAdapterState: isBleTurningOff()=false
08-09 07:51:15.255  2560  2560 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-09 07:51:15.255   874  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-09 07:51:15.255  2560  2560 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-09 07:51:15.256  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 07:51:15.256   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-09 07:51:15.258  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 07:51:15.258  3662  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 07:51:15.258  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:15.258  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:15.258  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:51:15.258  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 07:51:15.258  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 07:51:15.258  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 07:51:15.258  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 07:51:15.259  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 07:51:15.259  3662  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 07:51:15.259  3662  3713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 07:51:15.260  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 07:51:15.260  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 07:51:15.260  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:15.260  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:15.260  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:51:15.260  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 07:51:15.260  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 07:51:15.260  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 07:51:15.260  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 07:51:15.260  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 07:51:15.260  3662  3662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 07:51:15.265  1361  1361 D BluetoothMap: Proxy object disconnected
08-09 07:51:15.265  1361  1361 D MapProfile: Bluetooth service disconnected
08-09 07:51:15.265  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 07:51:15.265  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 07:51:15.265  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:15.265  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:15.265  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:51:15.265  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 07:51:15.265  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 07:51:15.265  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 07:51:15.265  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 07:51:15.266  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:15.268  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:15.268  2560  2560 D BluetoothMapService: MAP Service closeService in
08-09 07:51:15.268  2560  2560 V BluetoothAdapterState: isTurningOff()=true
08-09 07:51:15.268  2560  2560 V BluetoothAdapterState: isTurningOn()=false
08-09 07:51:15.268  2560  2560 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 07:51:15.268  2560  2560 V BluetoothAdapterState: isBleTurningOff()=false
08-09 07:51:15.268  2560  2607 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-09 07:51:15.268  2560  2607 D BluetoothAdapterProperties: Setting state to 15
08-09 07:51:15.268  2560  2607 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-09 07:51:15.268  2560  2560 D BluetoothMapService: cleanup()
08-09 07:51:15.268  2560  2560 D BluetoothMapService: MAP Service closeService in
08-09 07:51:15.269  2560  2607 I BluetoothAdapterState: Entering BleOnState
08-09 07:51:15.269  1723  1737 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 07:51:15.269  1361  1835 D BluetoothPan: onBluetoothStateChange on: false
08-09 07:51:15.270  1361  1383 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-09 07:51:15.272  1361  1377 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 07:51:15.272   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 07:51:15.272   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 07:51:15.273   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
08-09 07:51:15.274  1361  1835 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 07:51:15.276   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 07:51:15.276  1361  1377 D BluetoothMap: onBluetoothStateChange: up=false
08-09 07:51:15.277  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 07:51:15.277  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 07:51:15.277  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:15.277  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:15.277  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 07:51:15.277  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 07:51:15.277  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 07:51:15.277  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 07:51:15.277  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 07:51:15.277  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 07:51:15.277  3662  3662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 07:51:15.278   874  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-09 07:51:15.279  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 07:51:15.279  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 07:51:15.279  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:15.279  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:15.279  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 07:51:15.279  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 07:51:15.279  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 07:51:15.279  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 07:51:15.279  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 07:51:15.280  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 07:51:15.280  3662  3662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 07:51:15.280  1361  1837 D BluetoothPbap: onBluetoothStateChange: up=false
08-09 07:51:15.281   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 07:51:15.281  2560  2607 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-09 07:51:15.281  2560  2607 D BluetoothAdapterProperties: Setting state to 16
08-09 07:51:15.281  2560  2607 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-09 07:51:15.282  2560  2607 D BluetoothAdapterProperties: onBleDisable
08-09 07:51:15.282  2560  2607 I BluetoothAdapterState: Entering PendingCommandState
08-09 07:51:15.282  2560  2608 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-09 07:51:15.283  2560  2730 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-09 07:51:15.283  2560  2730 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 07:51:15.283  3662  3845 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 389)
08-09 07:51:15.284  2560  2611 D BluetoothAdapterProperties: Scan Mode:20
08-09 07:51:15.288  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:15.289  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:15.291  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:15.292  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:15.297  1890  2060 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-09 07:51:15.312   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 07:51:15.317  3850  3850 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-09 07:51:15.327  3468  3867 I BooksSync: Starting books sync for 61035162, extras: ade
,08-09 07:51:15.329  3850  3850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-09 07:51:15.332   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 07:51:15.333   874  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-09 07:51:15.333   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-09 07:51:15.336   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-09 07:51:15.338  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 07:51:15.338  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 07:51:15.339  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:15.344   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@dd8d808:true
08-09 07:51:15.352   874   884 I ActivityManager: Start proc 3870:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-09 07:51:15.373  3850  3850 D LocalBluetoothProfileManager: Adding local MAP profile
,08-09 07:51:15.375  3850  3850 D BluetoothMap: Create BluetoothMap proxy object
08-09 07:51:15.377   372   872 E Netd    : netlink response contains error (No such file or directory)
,08-09 07:51:15.387  3850  3850 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-09 07:51:15.391  3468  3489 E BooksSync: annotations sync failed
08-09 07:51:15.391  3468  3489 E BooksSync: com.google.android.apps.books.net.HttpHelper$OfflineIoException: Skipping sync: not connected
08-09 07:51:15.391  3468  3489 E BooksSync: com.google.android.apps.books.annotations.AnnotationControllerImpl.uploadAllPendingOperations(AnnotationControllerImpl.java:826)
,08-09 07:51:15.410  3870  3870 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-09 07:51:15.408  3468  3886 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-09 07:51:15.418  3850  3850 D DockEventReceiver: finishStartingService: stopping service
,08-09 07:51:15.431  1515  1958 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-09 07:51:15.432  1515  1958 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-09 07:51:15.432  1515  1958 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:51:15.432  1515  1958 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:51:15.461  1515  2416 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-09 07:51:15.461  1515  2416 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-09 07:51:15.461  1515  2416 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:51:15.462  1515  2416 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:51:15.472  3468  3886 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-09 07:51:15.473  3468  3867 E BooksSync: Soft error
08-09 07:51:15.473  3468  3867 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-09 07:51:15.473  3468  3867 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-09 07:51:15.473  3468  3867 E BooksSync: Sync error
08-09 07:51:15.473  3468  3867 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-09 07:51:15.473  3468  3867 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-09 07:51:15.473  3468  3867 I BooksSync: Finished books sync
,08-09 07:51:15.479   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 125038, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-09 07:51:15.478   874  1682 I ActivityManager: Killing 2947:com.google.android.talk/u0a61 (adj 15): empty #17
,08-09 07:51:15.488  2560  2611 I bt_hci  : shut_down
,08-09 07:51:15.488  2560  2616 D bt_hwcfg: hw_epilog_process
,08-09 07:51:15.521  2560  2616 I bt_vendor: low_power_mode_cb,
,08-09 07:51:15.553  2560  2616 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-09 07:51:15.553  2560  2616 I bt_vendor: epilog_cb
08-09 07:51:15.553  2560  2616 I bt_hci  : epilog_finished_callback
,08-09 07:51:15.556  2560  2611 I bt_hci_h4: hal_close
,08-09 07:51:15.557  2560  2611 I bt_userial_vendor: device fd = 51 close
,08-09 07:51:15.565  3870  3870 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at java.io.File.exists(File.java:361)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 07:51:15.565  3870  3870 D StrictMode: StrictMode policy violation; ~duration=104 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 07:51:15.565  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 07:51:15.566  3870  3870 D StrictMode: StrictMode policy violation; ~duration=99 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 07:51:15.566  3870  3870 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 07:51:15.566  3870  3870 D StrictMode: StrictMode policy violation; ~duration=98 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 07:51:15.566  3870  3870 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.r.e.b(PG:170)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 07:51:15.566  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-09 07:51:15.567  3870  3870 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.r.k.d(PG:583)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.r.e.b(PG:170)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-09 07:51:15.567  3870  3870 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at java.io.File.exists(File.java:361)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-09 07:51:15.567  3870  3870 D StrictMode: StrictMode policy violation; ~duration=54 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at java.io.File.exists(File.java:361)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-09 07:51:15.567  3870  3870 D StrictMode: StrictMode policy violation; ~duration=54 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 07:51:15.567  3870  3870 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-09 07:51:15.600   874  1738 I ActivityManager: Start proc 3903:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
08-09 07:51:15.601   874  1738 I ActivityManager: Killing 2964:com.google.android.keep/u0a79 (adj 15): empty #17
,08-09 07:51:15.666  3662  3662 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-09 07:51:15.673  2560  2608 D bt_stack_manager: event_shut_down_stack finished.
,08-09 07:51:15.674  2560  2607 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-09 07:51:15.678  2560  2560 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-09 07:51:15.679  2560  2607 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-09 07:51:15.679  2560  2560 D BtGatt.GattService: Received stop request...Stopping profile...
08-09 07:51:15.679  2560  2560 D BtGatt.GattService: stop()
08-09 07:51:15.679  2560  2560 D BtGatt.AdvertiseManager: advertise clients cleared
,08-09 07:51:15.683  2560  2560 V BluetoothAdapterState: isTurningOff()=false
,08-09 07:51:15.684  2560  2560 V BluetoothAdapterState: isTurningOn()=false
,08-09 07:51:15.684  2560  2560 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:15.684  2560  2560 V BluetoothAdapterState: isBleTurningOff()=true
08-09 07:51:15.686  2560  2607 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-09 07:51:15.687  3903  3903 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
08-09 07:51:15.687  2560  2607 D BluetoothAdapterProperties: Setting state to 10
,08-09 07:51:15.687  2560  2607 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-09 07:51:15.689  2560  2607 I BluetoothAdapterState: Entering OffState
08-09 07:51:15.689   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-09 07:51:15.712  2560  2560 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-09 07:51:15.712  2560  2560 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-09 07:51:15.712  2560  2560 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-09 07:51:15.713  2560  2608 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-09 07:51:15.715  2560  2608 D bt_stack_manager: event_clean_up_stack finished.
,08-09 07:51:15.726  2560  2560 I art     : System.exit called, status: 0
,08-09 07:51:15.726  2560  2560 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-09 07:51:15.778   874  1384 I ActivityManager: Process com.android.bluetooth (pid 2560) has died
,08-09 07:51:15.912  3903  3923 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-09 07:51:15.912  3903  3923 I Babel_SMS: MmsConfig.loadMmsSettings
,08-09 07:51:15.913  3903  3923 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-09 07:51:15.920  3903  3923 I Babel_SMS: MmsConfig.loadFromDatabase
,08-09 07:51:15.979  3903  3923 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-09 07:51:15.979  3903  3923 I Babel_SMS: MmsConfig.loadFromResources
,08-09 07:51:15.986  3903  3923 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-09 07:51:15.987  3903  3923 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-09 07:51:16.020  3903  3903 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-09 07:51:16.024  3903  3903 I Babel_Crash: startup - clean
,08-09 07:51:16.089  3903  3903 I Babel_telephony: TeleModule.launchCompleted
,08-09 07:51:16.099   874  1682 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-09 07:51:16.116  3903  3903 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-09 07:51:16.126  3903  3903 W Babel   : BAM#gBA: invalid account id: -1
,08-09 07:51:16.126  3903  3903 W Babel   : BAM#gBA: invalid account id: -1
08-09 07:51:16.127  3903  3903 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-09 07:51:16.143  3903  3929 I Babel   : deleted: false for 0
,08-09 07:51:16.145   874  1777 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-09 07:51:16.207   874  1384 I ActivityManager: Start proc 3932:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,08-09 07:51:16.285  3932  3932 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm
,08-09 07:51:16.315  3903  3903 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-09 07:51:16.392  3903  3903 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-09 07:51:16.401  3903  3903 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-09 07:51:16.417  3903  3903 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-09 07:51:16.425  3903  3903 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-09 07:51:16.441  3903  3903 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-09 07:51:16.460  3903  3903 I vclib   : onServiceConnected
,08-09 07:51:16.508  3850  3850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-09 07:51:16.538  3870  3891 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-09 07:51:16.542   874  1385 I ActivityManager: Start proc 3949:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-09 07:51:16.544  3850  3850 D DockEventReceiver: finishStartingService: stopping service
,08-09 07:51:16.601   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3b096ba:true
,08-09 07:51:16.632  3949  3949 D AdapterServiceConfig: Adding HeadsetService
,08-09 07:51:16.632  3949  3949 D AdapterServiceConfig: Adding A2dpService
08-09 07:51:16.632  3949  3949 D AdapterServiceConfig: Adding HidService
,08-09 07:51:16.632  3949  3949 D AdapterServiceConfig: Adding HealthService
,08-09 07:51:16.633  3949  3949 D AdapterServiceConfig: Adding PanService
08-09 07:51:16.633  3949  3949 D AdapterServiceConfig: Adding GattService
08-09 07:51:16.633  3949  3949 D AdapterServiceConfig: Adding BluetoothMapService
08-09 07:51:16.635   874  1777 I ActivityManager: Killing 2634:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-09 07:51:16.669  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 07:51:16.692   874   885 I ActivityManager: Killing 3071:android.process.acore/u0a5 (adj 15): empty #17
,08-09 07:51:16.749  1907  1907 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-09 07:51:16.757  1907  1907 D SystemUpdateService: onCreate
,08-09 07:51:16.767  1907  1907 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-09 07:51:16.774  1907  3966 I SystemUpdateService: active receiver: enabled
,08-09 07:51:16.783  1907  3966 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-09 07:51:16.785  1907  3966 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-09 07:51:16.785  1907  3966 I SystemUpdateService: now status is 0 (complete)
08-09 07:51:16.785  1907  3966 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-09 07:51:16.785  1907  3966 I SystemUpdateService: file has been verified
08-09 07:51:16.785  1907  3966 I SystemUpdateService: OTA package size = 12249756
,08-09 07:51:16.785  1907  1907 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-09 07:51:16.790  1907  2411 I iu.UploadsManager: num queued entries: 0
08-09 07:51:16.792  1907  2411 I iu.UploadsManager: num updated entries: 0
,08-09 07:51:16.796  1907  3966 I SystemUpdateService: showing system update notification
,08-09 07:51:16.797  1907  2411 I iu.SyncManager: NEXT; no task
,08-09 07:51:16.805  1907  1907 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-09 07:51:16.806  1907  1907 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-09 07:51:16.823   874  1682 I ActivityManager: Start proc 3968:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-09 07:51:16.824  1907  1907 D SystemUpdateService: onDestroy
,08-09 07:51:16.908  3968  3968 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-09 07:51:16.910  3968  3968 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-09 07:51:16.921  3968  3968 D SprintDMHelper: simOperator: 
,08-09 07:51:16.922  3968  3968 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-09 07:51:16.940   874  1385 I ActivityManager: Start proc 3980:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
08-09 07:51:16.941   874  1385 I ActivityManager: Killing 3555:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-09 07:51:17.097   874  1384 I ActivityManager: Start proc 3995:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-09 07:51:17.101  3903  3994 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-09 07:51:17.105   874  1772 I ActivityManager: Killing 3570:com.android.musicfx/u0a18 (adj 15): empty #17
,08-09 07:51:17.181  3995  3995 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-09 07:51:17.229  3995  3995 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-09 07:51:17.229  3995  3995 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-09 07:51:17.229  3995  3995 I GAv4    :   adb logcat -s GAv4
,08-09 07:51:17.242  3995  3995 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-09 07:51:17.247  3995  3995 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-09 07:51:17.271  3995  4012 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-09 07:51:17.376  3995  3995 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-09 07:51:17.410  3995  3995 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-09 07:51:17.417  3995  3995 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7262-7265)
,08-09 07:51:17.417  3995  3995 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-09 07:51:17.430  3995  3995 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c7e3606}
,08-09 07:51:17.430  3995  3995 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-09 07:51:17.431  3995  3995 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-09 07:51:17.437  3995  3995 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-09 07:51:17.439  3995  3995 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-09 07:51:17.461  3995  3995 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-09 07:51:17.471  3995  3995 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-09 07:51:17.473  3995  3995 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-09 07:51:17.473  3995  3995 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-09 07:51:17.473  3995  3995 I Adreno  : Build Date                       : 10/20/15
08-09 07:51:17.473  3995  3995 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-09 07:51:17.473  3995  3995 I Adreno  : Local Branch                     : M14
08-09 07:51:17.473  3995  3995 I Adreno  : Remote Branch                    : 
08-09 07:51:17.473  3995  3995 I Adreno  : Remote Branch                    : 
08-09 07:51:17.473  3995  3995 I Adreno  : Reconstruct Branch               : 
,08-09 07:51:17.510  3995  4041 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-09 07:51:17.525  3995  3995 I NSApplication: Starting up...
,08-09 07:51:17.562   874  1773 I ActivityManager: Start proc 4046:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-09 07:51:17.563   874  1773 I ActivityManager: Killing 3332:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-09 07:51:17.650  4046  4046 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-09 07:51:17.822   874  1769 I ActivityManager: Killing 3517:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-09 07:51:18.261   874  1688 D WifiService: setWifiEnabled: true pid=3662, uid=10000
,08-09 07:51:18.262   874  1688 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-09 07:51:18.273   874  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-09 07:51:18.284  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 07:51:18.285  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 07:51:18.285  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:18.285  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:18.285  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:51:18.285  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 07:51:18.285  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 07:51:18.285  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 07:51:18.285  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 07:51:18.285  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 07:51:18.285  3662  3662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 07:51:18.288  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 07:51:18.289  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 07:51:18.289  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:18.289  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:18.289  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:51:18.289  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 07:51:18.289  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 07:51:18.289  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 07:51:18.289  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 07:51:18.289  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 07:51:18.289  3662  3662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-09 07:51:18.326   874  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-09 07:51:18.326   874  1308 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-09 07:51:18.327   874  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-09 07:51:18.328   874  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-09 07:51:18.329   874  1308 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
08-09 07:51:18.330   874  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-09 07:51:18.330   874  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 3
08-09 07:51:18.330   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-09 07:51:18.330   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-09 07:51:18.330   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "ktwtestwifi"WPA_EAP
,08-09 07:51:18.344   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-09 07:51:18.344   874  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=15.75 rxSuccessRate=11.50 delta 1000 -> 994,
,08-09 07:51:18.345   372   872 D CommandListener: Setting iface cfg
08-09 07:51:18.346   874  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,08-09 07:51:18.346   874  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-09 07:51:18.353   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-09 07:51:18.353   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-09 07:51:18.353   874  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-09 07:51:18.361   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-09 07:51:18.362   874  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-09 07:51:18.446   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-09 07:51:18.453  1460  1460 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-09 07:51:18.883  1460  1460 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-09 07:51:18.885  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-EAP-SUCCESS EAP authentication completed successfully (based on lower layer success)
,08-09 07:51:18.936  1460  1460 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-09 07:51:18.936  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-09 07:51:18.942   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-09 07:51:18.956   874  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-09 07:51:18.956   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-09 07:51:18.956   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-09 07:51:18.979   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-09 07:51:18.992   372   872 D CommandListener: Setting iface cfg
,08-09 07:51:18.993   874  1308 D WifiStateMachine: Start Dhcp Watchdog 2
,08-09 07:51:19.006   874  1310 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-09 07:51:19.008   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-09 07:51:19.023   874  4067 D DhcpClient: Receive thread started
,08-09 07:51:19.107   874  1308 E native  : do suspend false
,08-09 07:51:19.129   874  2022 D DhcpClient: Broadcasting DHCPDISCOVER
,08-09 07:51:19.143   874  4067 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172524, domain null
,08-09 07:51:19.144   874  2022 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172524 seconds
,08-09 07:51:19.150   874  2022 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-09 07:51:19.163   874  4067 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-09 07:51:19.164   874  2022 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-09 07:51:19.171   372   872 D CommandListener: Setting iface cfg
,08-09 07:51:19.182   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-09 07:51:19.188   874  2022 D DhcpClient: Scheduling renewal in 86399s
,08-09 07:51:19.208   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-09 07:51:19.212   874  1308 D WifiConfigStore: No blacklist allowed without epno enabled,
,08-09 07:51:19.212   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-09 07:51:19.214   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-09 07:51:19.217   874  1310 D ConnectivityService: Adding iface wlan0 to network 101
,08-09 07:51:19.242   874  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-09 07:51:19.293   874  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-09 07:51:19.293   874  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-09 07:51:19.295   874  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-09 07:51:19.297   874  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-09 07:51:19.299   874  1310 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-09 07:51:19.314   874  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-09 07:51:19.319   874  1310 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-09 07:51:19.319   874  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-09 07:51:19.319   874  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-09 07:51:19.319   874  1310 D ConnectivityService:    accepting network in place of null
08-09 07:51:19.319   874  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-09 07:51:19.321   874  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -40]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-09 07:51:19.322   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-09 07:51:19.337   874  4066 D NetlinkSocketObserver: NeighborEvent{elapsedMs=129185, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 07:51:19.373   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 07:51:19.410   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 07:51:19.412   874  4065 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.93,2a00:1450:400d:802::200e
,08-09 07:51:19.421   874  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-09 07:51:19.423   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-09 07:51:19.434  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 07:51:19.434  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 07:51:19.434  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:19.434  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:19.434  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:51:19.434  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 07:51:19.434  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 07:51:19.434  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 07:51:19.434  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 07:51:19.434  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 07:51:19.435  3662  3662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 07:51:19.436   874   891 D Tethering: MasterInitialState.processMessage what=3
08-09 07:51:19.436   874  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-09 07:51:19.442  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 07:51:19.442  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 07:51:19.442  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:19.442  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:19.442  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:51:19.442  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 07:51:19.442  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 07:51:19.442  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 07:51:19.442  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 07:51:19.443  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 07:51:19.443  3662  3662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-09 07:51:19.453   874  4065 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Aug 2016 05:51:20 GMT], X-Android-Received-Millis=[1470721879447], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470721879443]}
,08-09 07:51:19.454  1907  1907 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-09 07:51:19.454   874  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-09 07:51:19.454   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-09 07:51:19.455   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-09 07:51:19.457  1907  1907 D SystemUpdateService: onCreate
,08-09 07:51:19.457   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-09 07:51:19.461  1907  1907 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-09 07:51:19.464  1907  4079 I SystemUpdateService: active receiver: enabled
,08-09 07:51:19.470  1907  4079 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-09 07:51:19.472  1907  4079 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-09 07:51:19.472  1907  4079 I SystemUpdateService: now status is 0 (complete)
,08-09 07:51:19.472  1907  4079 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-09 07:51:19.472  1907  4079 I SystemUpdateService: file has been verified
08-09 07:51:19.473  1907  4079 I SystemUpdateService: OTA package size = 12249756
,08-09 07:51:19.478  1907  4079 I SystemUpdateService: showing system update notification
,08-09 07:51:19.484  1907  1907 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-09 07:51:19.487  1907  4083 I MDM     : [220] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-09 07:51:19.487  1907  4083 W BaseAppContext: Using Auth Proxy for data requests.
08-09 07:51:19.488  1907  4083 V GoogleAuthProtoRequest: [220] a.<init>: mAccountName set to: thalitester@gmail.com
08-09 07:51:19.490  1907  1907 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-09 07:51:19.492  1907  1907 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-09 07:51:19.493  3968  3968 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-09 07:51:19.495  1907  2411 I iu.UploadsManager: num queued entries: 0
,08-09 07:51:19.496  1907  2411 I iu.UploadsManager: num updated entries: 0
08-09 07:51:19.497  1907  2411 I iu.SyncManager: NEXT; no task
08-09 07:51:19.498  3968  3968 D SprintDMHelper: simOperator: 
08-09 07:51:19.498  3968  3968 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-09 07:51:19.501  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:51:19.504  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:51:19.507  1907  1907 D SystemUpdateService: onDestroy
,08-09 07:51:19.535  1907  4087 V Herrevad: [222] CaptivePortalReportService.onHandleIntent: Handle latency report/cp broadcast, intent: Intent { cmp=com.google.android.gms/.herrevad.services.CaptivePortalReportService (has extras) }
,08-09 07:51:19.542  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-09 07:51:19.543  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-09 07:51:19.544  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:51:19.544  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:51:19.555  1907  4087 I Herrevad: [222] CaptivePortalReportService.onHandleIntent: CP report successful
,08-09 07:51:19.584  1907  4083 E MDM     : [220] SitrepService.a: Error sending sitrep.
,08-09 07:51:19.592  3903  4086 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-09 07:51:19.613  1515  4090 V NQFileLogger: [130] e.a: about to write to file
,08-09 07:51:19.619  1515  4090 V ProcessReports: [130] ProcessReportsService.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,08-09 07:51:19.669  1515  1958 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-09 07:51:19.670  1515  1958 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-09 07:51:19.670  1515  1958 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:51:19.670  1515  1958 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:51:19.679  3932  4094 V KeepSync: Connecting to GoogleApiClient
,08-09 07:51:19.680   874  1384 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-09 07:51:19.687  2513  4092 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-09 07:51:19.687  2513  4092 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-09 07:51:19.687  2513  4092 E HttpOperation: 	at jdm.a(PG:82)
08-09 07:51:19.687  2513  4092 E HttpOperation: 	at jcs.o(PG:406)
08-09 07:51:19.687  2513  4092 E HttpOperation: 	at jcn.a(PG:1379)
08-09 07:51:19.687  2513  4092 E HttpOperation: 	at jcs.i(PG:143)
08-09 07:51:19.687  2513  4092 E HttpOperation: 	at blb.a(PG:3937)
08-09 07:51:19.687  2513  4092 E HttpOperation: 	at czp.a(PG:18188)
08-09 07:51:19.687  2513  4092 E HttpOperation: 	at czp.a(PG:9081)
08-09 07:51:19.687  2513  4092 E HttpOperation: 	at czq.run(PG:1686)
08-09 07:51:19.687  2513  4092 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 07:51:19.687  2513  4092 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 07:51:19.687  2513  4092 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 07:51:19.687  2513  4092 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 07:51:19.687  2513  4092 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:51:19.687  2513  4092 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 07:51:19.687  2513  4092 E HttpOperation: 	at jdj.a(PG:4091)
08-09 07:51:19.687  2513  4092 E HttpOperation: 	at jdj.a(PG:1125)
08-09 07:51:19.687  2513  4092 E HttpOperation: 	at jdm.a(PG:77)
08-09 07:51:19.687  2513  4092 E HttpOperation: 	... 12 more
08-09 07:51:19.687  2513  4092 E HttpOperation: Caused by: faj: BadAuthentication
08-09 07:51:19.687  2513  4092 E HttpOperation: 	at fal.a(PG:38)
08-09 07:51:19.687  2513  4092 E HttpOperation: 	at jdj.a(PG:4089)
08-09 07:51:19.687  2513  4092 E HttpOperation: 	... 14 more
,08-09 07:51:19.718  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-09 07:51:19.718  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-09 07:51:19.718  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 07:51:19.718  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:51:19.728  2513  4092 E HttpOperation: [getmobileexperiments] Unexpected exception
08-09 07:51:19.728  2513  4092 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-09 07:51:19.728  2513  4092 E HttpOperation: 	at jdm.a(PG:82)
08-09 07:51:19.728  2513  4092 E HttpOperation: 	at jcs.o(PG:406)
08-09 07:51:19.728  2513  4092 E HttpOperation: 	at jcn.a(PG:1379)
08-09 07:51:19.728  2513  4092 E HttpOperation: 	at jcs.i(PG:143)
08-09 07:51:19.728  2513  4092 E HttpOperation: 	at hec.a(PG:42)
08-09 07:51:19.728  2513  4092 E HttpOperation: 	at hee.a(PG:102)
08-09 07:51:19.728  2513  4092 E HttpOperation: 	at czr.a(PG:65)
08-09 07:51:19.728  2513  4092 E HttpOperation: 	at kka.a(PG:108)
08-09 07:51:19.728  2513  4092 E HttpOperation: 	at czp.a(PG:19176)
08-09 07:51:19.728  2513  4092 E HttpOperation: 	at czp.a(PG:9081)
08-09 07:51:19.728  2513  4092 E HttpOperation: 	at czq.run(PG:1686)
08-09 07:51:19.728  2513  4092 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 07:51:19.728  2513  4092 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 07:51:19.728  2513  4092 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 07:51:19.728  2513  4092 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 07:51:19.728  2513  4092 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:51:19.728  2513  4092 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 07:51:19.728  2513  4092 E HttpOperation: 	at jdj.a(PG:4091)
08-09 07:51:19.728  2513  4092 E HttpOperation: 	at jdj.a(PG:1125)
08-09 07:51:19.728  2513  4092 E HttpOperation: 	at jdm.a(PG:77)
08-09 07:51:19.728  2513  4092 E HttpOperation: 	... 15 more
08-09 07:51:19.728  2513  4092 E HttpOperation: Caused by: faj: BadAuthentication
08-09 07:51:19.728  2513  4092 E HttpOperation: 	at fal.a(PG:38)
08-09 07:51:19.728  2513  4092 E HttpOperation: 	at jdj.a(PG:4089)
08-09 07:51:19.728  2513  4092 E HttpOperation: 	... 17 more
,08-09 07:51:19.728  2513  4092 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-09 07:51:19.728  2513  4092 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	at jdm.a(PG:82)
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	at jcs.o(PG:406)
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	at jcn.a(PG:1379)
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	at jcs.i(PG:143)
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	at hec.a(PG:42)
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	at hee.a(PG:102)
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	at czr.a(PG:65)
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	at kka.a(PG:108)
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	at czp.a(PG:19176)
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	at czp.a(PG:9081)
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	at czq.run(PG:1686)
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:51:19.728  2513  4092 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	at jdj.a(PG:4091)
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	at jdj.a(PG:1125)
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	at jdm.a(PG:77)
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	... 15 more
08-09 07:51:19.728  2513  4092 E ExperimentLoader: Caused by: faj: BadAuthentication
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	at fal.a(PG:38)
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	at jdj.a(PG:4089)
08-09 07:51:19.728  2513  4092 E ExperimentLoader: 	... 17 more
,08-09 07:51:19.749  1515  2416 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-09 07:51:19.750  1515  2416 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-09 07:51:19.750  1515  2416 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 07:51:19.750  1515  2416 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:51:19.760  1907  4099 V BaseAuthAsyncOperation: access token request failed
,08-09 07:51:19.762  3932  4094 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-09 07:51:19.782  1515  4098 I GCM     : Ack for not saved message 0
,08-09 07:51:19.806   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 129279, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-09 07:51:19.891  1515  2067 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-09 07:51:19.891  1515  2067 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-09 07:51:19.892  1515  2067 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 07:51:19.892  1515  2067 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:51:19.913  3932  4094 E KeepSync: IOException
08-09 07:51:19.913  3932  4094 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-09 07:51:19.913  3932  4094 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-09 07:51:19.913  3932  4094 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-09 07:51:19.913  3932  4094 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-09 07:51:19.913  3932  4094 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-09 07:51:19.913  3932  4094 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-09 07:51:19.913  3932  4094 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-09 07:51:19.913  3932  4094 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-09 07:51:19.913  3932  4094 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-09 07:51:19.913  3932  4094 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-09 07:51:19.913  3932  4094 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-09 07:51:19.913  3932  4094 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-09 07:51:19.913  3932  4094 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-09 07:51:19.913  3932  4094 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-09 07:51:19.913  3932  4094 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-09 07:51:19.913  3932  4094 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-09 07:51:19.913  3932  4094 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-09 07:51:19.913  3932  4094 E KeepSync: 	... 10 more
08-09 07:51:19.913  3932  4094 W KeepSync: Sync result 2
,08-09 07:51:19.919   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 125503, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-09 07:51:20.421   874  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-09 07:51:21.268   874   884 D WifiService: setWifiEnabled: false pid=3662, uid=10000
,08-09 07:51:21.269   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-09 07:51:21.303  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-09 07:51:21.309   874  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-09 07:51:21.309   874  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-09 07:51:21.309   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-09 07:51:21.310   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-09 07:51:21.332   874  2022 D DhcpClient: Clearing IP address
,08-09 07:51:21.332   372   872 D CommandListener: Clearing all IP addresses on wlan0
,08-09 07:51:21.342  1515  4098 V NativeCrypto: Read error: ssl=0x9a0ff600: I/O error during system call, Connection timed out
,08-09 07:51:21.345  1515  4098 V NativeCrypto: SSL shutdown failed: ssl=0x9a0ff600: I/O error during system call, Broken pipe
,08-09 07:51:21.347   372   872 D CommandListener: Setting iface cfg
,08-09 07:51:21.348   874  1384 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
08-09 07:51:21.349   874  4065 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-09 07:51:21.349   874  4065 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.93,2a00:1450:400d:802::200e
,08-09 07:51:21.354   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-09 07:51:21.354   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-09 07:51:21.361   395   395 E Parcel  : Reading a NULL string not supported here.
08-09 07:51:21.368   874  1308 D WifiStateMachine: Start Disconnecting Watchdog 2
08-09 07:51:21.369   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-09 07:51:21.371   372   872 D CommandListener: Clearing all IP addresses on wlan0
08-09 07:51:21.371   874  4065 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:802::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,08-09 07:51:21.375   874  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-09 07:51:21.379   874  4067 D DhcpClient: Receive thread stopped
08-09 07:51:21.380   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-09 07:51:21.384  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 07:51:21.384  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 07:51:21.384  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:21.384  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:21.384  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 07:51:21.384  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 07:51:21.384  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 07:51:21.384  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 07:51:21.384  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 07:51:21.384  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 07:51:21.384  1890  2060 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-09 07:51:21.384  3662  3662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 07:51:21.385  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 07:51:21.385   874  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-09 07:51:21.385  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 07:51:21.385  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:21.385  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:21.385  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 07:51:21.385  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 07:51:21.385  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
08-09 07:51:21.385  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 07:51:21.385  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 07:51:21.385  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 07:51:21.385  3662  3662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
,08-09 07:51:21.401  3932  3932 I art     : Waiting for a blocking GC DisableMovingGc
,08-09 07:51:21.402   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 07:51:21.406  3932  3939 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@e9fb968)
,08-09 07:51:21.408  3932  3932 I art     : WaitForGcToComplete blocked for 6.899ms for cause DisableMovingGc
08-09 07:51:21.408  3932  3932 I art     : Starting a blocking GC DisableMovingGc
,08-09 07:51:21.426   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 07:51:21.426   874  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-09 07:51:21.427   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-09 07:51:21.428   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-09 07:51:21.433  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 07:51:21.434  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 07:51:21.439  1907  1907 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-09 07:51:21.442  1907  1907 D SystemUpdateService: onCreate
,08-09 07:51:21.445  1907  1907 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-09 07:51:21.447  1907  4110 I SystemUpdateService: active receiver: enabled
,08-09 07:51:21.452  1907  4110 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-09 07:51:21.453  1907  4110 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-09 07:51:21.453  1907  4110 I SystemUpdateService: now status is 0 (complete)
08-09 07:51:21.453  1907  4110 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-09 07:51:21.454  1907  4110 I SystemUpdateService: file has been verified
08-09 07:51:21.454  1907  4110 I SystemUpdateService: OTA package size = 12249756
,08-09 07:51:21.455  1907  1907 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-09 07:51:21.461  1907  2411 I iu.UploadsManager: num queued entries: 0
,08-09 07:51:21.461  1907  2411 I iu.UploadsManager: num updated entries: 0
,08-09 07:51:21.464  1907  4110 I SystemUpdateService: showing system update notification
,08-09 07:51:21.465  1907  1907 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-09 07:51:21.466  1907  1907 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-09 07:51:21.466  1907  2411 I iu.SyncManager: NEXT; no task
,08-09 07:51:21.467  3968  3968 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-09 07:51:21.471  3968  3968 D SprintDMHelper: simOperator: 
,08-09 07:51:21.471  3968  3968 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-09 07:51:21.474  1907  1907 D SystemUpdateService: onDestroy
,08-09 07:51:21.498  3903  4114 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-09 07:51:21.507   372   872 E Netd    : netlink response contains error (No such file or directory)
,08-09 07:51:21.508   874  1310 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-09 07:51:21.508   874  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-09 07:51:24.308  3949  3949 D BluetoothAdapterState: make() - Creating AdapterState
08-09 07:51:24.308   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3230790:true
,08-09 07:51:24.313  3949  3949 I bt_bluedroid: init
,08-09 07:51:24.314  3949  4117 I BluetoothAdapterState: Entering OffState
,08-09 07:51:24.316  3949  4118 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-09 07:51:24.316  3949  4118 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-09 07:51:24.316  3949  4118 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-09 07:51:24.316  3949  4118 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-09 07:51:24.317  3949  3949 I bt_bluedroid: get_profile_interface socket
,08-09 07:51:24.319  3949  3949 I bt_bluedroid: get_profile_interface sdp
,08-09 07:51:24.322  3949  4121 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-09 07:51:24.324  3949  4121 D BluetoothAdapterProperties: Name is: Nexus 6
,08-09 07:51:24.324  3949  3960 I bt_bluedroid: config_hci_snoop_log
08-09 07:51:24.326   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-09 07:51:24.335  3949  4117 D BluetoothAdapterState: Current state: OFF, message: 0
,08-09 07:51:24.335  3949  4117 D BluetoothAdapterProperties: Setting state to 14
08-09 07:51:24.336  3949  4117 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-09 07:51:24.340  3949  4117 D BluetoothBondStateMachine: make
,08-09 07:51:24.343  3949  4123 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-09 07:51:24.349  3949  4117 I BluetoothAdapterState: Entering PendingCommandState
,08-09 07:51:24.350  3949  3949 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-09 07:51:24.353  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f3976c
,08-09 07:51:24.354  3949  3949 D BtGatt.DebugUtils: handleDebugAction() action=null,
,08-09 07:51:24.355  3949  3949 D BtGatt.GattService: Received start request. Starting profile...
08-09 07:51:24.355  3949  3949 D BtGatt.GattService: start()
,08-09 07:51:24.355  3949  3949 I bt_bluedroid: get_profile_interface gatt
,08-09 07:51:24.356  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f3976c
08-09 07:51:24.356  3949  3949 D BtGatt.AdvertiseManager: advertise manager created
,08-09 07:51:24.365  3949  3949 V BluetoothAdapterState: isTurningOff()=false
,08-09 07:51:24.365  3949  3949 V BluetoothAdapterState: isTurningOn()=false
,08-09 07:51:24.365  3949  3949 V BluetoothAdapterState: isBleTurningOn()=true
08-09 07:51:24.365  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 07:51:24.365  3949  4117 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-09 07:51:24.366  3949  4117 I bt_bluedroid: enable
,08-09 07:51:24.366  3949  4118 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-09 07:51:24.367  3949  4118 I bt_hci  : start_up
,08-09 07:51:24.375  3949  4118 I bt_vendor: alloc value 0xb39b9189
,08-09 07:51:24.375  3949  4118 I bt_vendor: init
,08-09 07:51:24.375  3949  4118 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-09 07:51:24.375  3949  4118 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-09 07:51:24.485  3949  4118 D bt_hci  : start_up starting async portion
,08-09 07:51:24.487  3949  4126 I bt_hci  : event_finish_startup
08-09 07:51:24.487  3949  4126 I bt_hci_h4: hal_open
,08-09 07:51:24.488  3949  4126 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-09 07:51:24.500  3949  4126 I bt_userial_vendor: device fd = 51 open
,08-09 07:51:24.526  3949  4126 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-09 07:51:24.558  3949  4126 D bt_hwcfg: Chipset BCM4354A2
08-09 07:51:24.558  3949  4126 D bt_hwcfg: Target name = [BCM4354A2]
,08-09 07:51:24.559  3949  4126 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-09 07:51:25.241  3949  4126 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-09 07:51:25.242  3949  4126 D bt_hwcfg: Settlement delay -- 100 ms
,08-09 07:51:25.242  3949  4126 I bt_hwcfg: Setting fw settlement delay to 100 
,08-09 07:51:25.359  3949  4126 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-09 07:51:25.361  3949  4126 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-09 07:51:25.390  3949  4126 I bt_hwcfg: vendor lib fwcfg completed
,08-09 07:51:25.390  3949  4126 I bt_vendor: firmware callback
,08-09 07:51:25.390  3949  4126 I bt_hci  : firmware_config_callback
,08-09 07:51:25.405  3949  4128 I bt_btu  : btu_task pending for preload complete event
,08-09 07:51:25.405  3949  4128 I bt_btu_task: Bluetooth chip preload is complete
,08-09 07:51:25.406  3949  4128 I bt_btu  : btu_task received preload complete event
,08-09 07:51:25.414  3949  4128 I         : BTE_InitTraceLevels -- TRC_HCI
,08-09 07:51:25.415  3949  4128 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-09 07:51:25.415  3949  4128 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-09 07:51:25.415  3949  4128 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-09 07:51:25.415  3949  4128 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-09 07:51:25.415  3949  4128 I         : BTE_InitTraceLevels -- TRC_A2D
,08-09 07:51:25.416  3949  4128 I         : BTE_InitTraceLevels -- TRC_BNEP
08-09 07:51:25.416  3949  4128 I         : BTE_InitTraceLevels -- TRC_BTM
08-09 07:51:25.416  3949  4128 I         : BTE_InitTraceLevels -- TRC_GAP
,08-09 07:51:25.416  3949  4128 I         : BTE_InitTraceLevels -- TRC_PAN
08-09 07:51:25.416  3949  4128 I         : BTE_InitTraceLevels -- TRC_SDP
08-09 07:51:25.417  3949  4128 I         : BTE_InitTraceLevels -- TRC_GATT
,08-09 07:51:25.417  3949  4128 I         : BTE_InitTraceLevels -- TRC_SMP
,08-09 07:51:25.417  3949  4128 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-09 07:51:25.417  3949  4128 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-09 07:51:25.549  3949  4128 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3936d9d
,08-09 07:51:25.549  3949  4128 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3936d9d 
,08-09 07:51:25.577  3949  4121 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-09 07:51:25.579  3949  4121 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-09 07:51:25.579  3949  4121 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-09 07:51:25.581  3949  4121 D BluetoothAdapterProperties: Name is: Nexus 6
,08-09 07:51:25.582  3949  4121 D BluetoothAdapterProperties: Scan Mode:20
08-09 07:51:25.582  3949  4121 D BluetoothAdapterProperties: Discoverable Timeout:120
08-09 07:51:25.582  3949  4121 D bt_hci  : do_postload posting postload work item
08-09 07:51:25.582  3949  4126 I bt_hci  : event_postload
08-09 07:51:25.583  3949  4126 I bt_vendor: sco_config_cb
08-09 07:51:25.583  3949  4126 I bt_hci  : sco_config_callback postload finished.
08-09 07:51:25.583  3949  4121 D bt_bte_conf: Device ID record 1 : primary
08-09 07:51:25.584  3949  4121 D bt_bte_conf:   vendorId            = 000f
08-09 07:51:25.584  3949  4121 D bt_bte_conf:   vendorIdSource      = 0001
,08-09 07:51:25.584  3949  4121 D bt_bte_conf:   product             = 1200
08-09 07:51:25.584  3949  4121 D bt_bte_conf:   version             = 1436
08-09 07:51:25.584  3949  4121 D bt_bte_conf:   clientExecutableURL = 
08-09 07:51:25.584  3949  4121 D bt_bte_conf:   serviceDescription  = 
08-09 07:51:25.584  3949  4121 D bt_bte_conf:   documentationURL    = 
08-09 07:51:25.584  3949  4121 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-09 07:51:25.584  3949  4118 D bt_stack_manager: event_start_up_stack finished
08-09 07:51:25.585  3949  4117 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3,
,08-09 07:51:25.585  3949  4117 D BluetoothAdapterProperties: Setting state to 15
,08-09 07:51:25.585  3949  4117 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-09 07:51:25.586  3949  4117 I BluetoothAdapterState: Entering BleOnState,
08-09 07:51:25.586  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 07:51:25.592  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-09 07:51:25.593  3949  4126 I bt_vendor: low_power_mode_cb
,08-09 07:51:25.593  3949  4117 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-09 07:51:25.594  3949  4117 D BluetoothAdapterProperties: Setting state to 11,
,08-09 07:51:25.594  3949  4117 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-09 07:51:25.605  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f3976c
08-09 07:51:25.606  3949  3949 D HeadsetService: Received start request. Starting profile...
,08-09 07:51:25.614  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 07:51:25.617  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 07:51:25.619  3949  3949 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-09 07:51:25.620  3949  3949 D HeadsetStateMachine: make
,08-09 07:51:25.627  3949  4117 I BluetoothAdapterState: Entering PendingCommandState
,08-09 07:51:25.631  3949  3949 D HeadsetStateMachine: max_hf_connections = 1
,08-09 07:51:25.631  3949  3949 I bt_bluedroid: get_profile_interface handsfree
,08-09 07:51:25.632  3949  4121 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-09 07:51:25.632  3949  4121 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-09 07:51:25.636  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f3976c
,08-09 07:51:25.636  3949  3949 D A2dpService: Received start request. Starting profile...
,08-09 07:51:25.637  3949  3949 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-09 07:51:25.637  3949  3949 I bt_bluedroid: get_profile_interface avrcp
,08-09 07:51:25.644  3949  3949 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-09 07:51:25.644  3949  3949 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-09 07:51:25.644  3949  3949 D A2dpStateMachine: make
,08-09 07:51:25.645  3949  3949 I bt_bluedroid: get_profile_interface a2dp
,08-09 07:51:25.646  3949  4121 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-09 07:51:25.647  3949  4138 D A2dpStateMachine: Enter Disconnected: -2
08-09 07:51:25.647  3949  3949 I BluetoothHidServiceJni: classInitNative: succeeds
08-09 07:51:25.648  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f3976c
,08-09 07:51:25.649  3949  3949 D HidService: Received start request. Starting profile...
,08-09 07:51:25.650  3949  3949 I bt_bluedroid: get_profile_interface hidhost
08-09 07:51:25.650  3949  3949 D HidService: setHidService(): set to: null
08-09 07:51:25.650  3949  4121 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39183e5
08-09 07:51:25.650  3949  4121 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-09 07:51:25.650  3850  3850 D BluetoothInputDevice: Proxy object connected
,08-09 07:51:25.650  3949  3949 I BluetoothHealthServiceJni: classInitNative: succeeds
08-09 07:51:25.651  3850  3850 D HidProfile: Bluetooth service connected
08-09 07:51:25.651  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f3976c
08-09 07:51:25.652  3949  3949 D HealthService: Received start request. Starting profile...
,08-09 07:51:25.653  3949  3949 I bt_bluedroid: get_profile_interface health
,08-09 07:51:25.655  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 07:51:25.656  3949  3949 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-09 07:51:25.657  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f3976c
,08-09 07:51:25.658  3949  3949 D PanService: Received start request. Starting profile...
,08-09 07:51:25.659  3850  3850 D BluetoothPan: BluetoothPAN Proxy object connected
,08-09 07:51:25.659  3949  3949 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-09 07:51:25.659  3949  3949 I bt_bluedroid: get_profile_interface pan
,08-09 07:51:25.659  3949  4121 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-09 07:51:25.659  3850  3850 D PanProfile: Bluetooth service connected
08-09 07:51:25.662  3949  3949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f3976c
08-09 07:51:25.663  3850  3850 D BluetoothMap: Proxy object connected
08-09 07:51:25.663  3949  3949 D BluetoothMapService: Received start request. Starting profile...
08-09 07:51:25.663  3949  3949 D BluetoothMapService: start()
08-09 07:51:25.663  3850  3850 D MapProfile: Bluetooth service connected
,08-09 07:51:25.663  3850  3850 D BluetoothMap: getConnectedDevices()
,08-09 07:51:25.664  3850  3850 D BluetoothMap: Bluetooth is Not enabled
08-09 07:51:25.665  3949  3949 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-09 07:51:25.665  3949  3949 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-09 07:51:25.665  3949  3949 D BluetoothMapAppObserver: createReceiver()
08-09 07:51:25.666  3949  3949 D BluetoothMapAppObserver: initObservers()
,08-09 07:51:25.666  3949  3949 D BluetoothMapAppObserver: getEnabledAccountItems()
08-09 07:51:25.673  3949  3949 V BluetoothAdapterState: isTurningOff()=false
08-09 07:51:25.673  3949  3949 V BluetoothAdapterState: isTurningOn()=true
08-09 07:51:25.673  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:25.673  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
08-09 07:51:25.675  3949  4136 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-09 07:51:25.676  3949  3949 V BluetoothAdapterState: isTurningOff()=false
08-09 07:51:25.676  3949  3949 V BluetoothAdapterState: isTurningOn()=true
08-09 07:51:25.676  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:25.676  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 07:51:25.676  3949  3949 V BluetoothAdapterState: isTurningOff()=false
08-09 07:51:25.676  3949  3949 V BluetoothAdapterState: isTurningOn()=true
08-09 07:51:25.676  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:25.676  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
08-09 07:51:25.676  3949  3949 V BluetoothAdapterState: isTurningOff()=false
08-09 07:51:25.677  3949  3949 V BluetoothAdapterState: isTurningOn()=true
,08-09 07:51:25.677  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:25.677  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
08-09 07:51:25.679  3949  3949 V BluetoothAdapterState: isTurningOff()=false
08-09 07:51:25.679  3949  3949 V BluetoothAdapterState: isTurningOn()=true
08-09 07:51:25.679  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:25.679  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
08-09 07:51:25.679  3949  3949 V BluetoothAdapterState: isTurningOff()=false
08-09 07:51:25.679  3949  3949 V BluetoothAdapterState: isTurningOn()=true
,08-09 07:51:25.679  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:25.679  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
08-09 07:51:25.679  3949  4117 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-09 07:51:25.680  3949  4117 D BluetoothAdapterProperties: ScanMode =  20
08-09 07:51:25.680  3949  4117 D BluetoothAdapterProperties: State =  11
,08-09 07:51:25.681  3949  4117 D BluetoothAdapterProperties: Setting state to 12
08-09 07:51:25.681  3949  4117 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-09 07:51:25.682  3949  4117 I BluetoothAdapterState: Entering OnState
08-09 07:51:25.682  3850  3863 D BluetoothPan: onBluetoothStateChange on: true
08-09 07:51:25.683  3949  4121 D BluetoothAdapterProperties: Scan Mode:21
08-09 07:51:25.683  1723  1863 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 07:51:25.684  3949  4121 D BluetoothAdapterProperties: Discoverable Timeout:120
08-09 07:51:25.685  1361  1837 D BluetoothPan: onBluetoothStateChange on: true
08-09 07:51:25.687  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 07:51:25.687  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:25.687  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:25.687  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 07:51:25.687  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 07:51:25.687  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 07:51:25.687  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 07:51:25.687  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 07:51:25.689  1361  1835 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-09 07:51:25.690  3662  3662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 07:51:25.690  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
,08-09 07:51:25.690  1361  1361 D PanProfile: Bluetooth service connected
08-09 07:51:25.691  1361  1377 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 07:51:25.691  1361  1361 D BluetoothInputDevice: Proxy object connected
08-09 07:51:25.691  1361  1361 D HidProfile: Bluetooth service connected
08-09 07:51:25.692  3850  3862 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-09 07:51:25.692   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-09 07:51:25.692   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-09 07:51:25.693  1361  1837 D BluetoothA2dp: onBluetoothStateChange: up=true
08-09 07:51:25.694   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 07:51:25.695  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 07:51:25.695  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:25.695  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:25.695  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 07:51:25.695  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 07:51:25.695  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 07:51:25.695  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 07:51:25.695  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 07:51:25.695  3850  3861 D BluetoothPbap: onBluetoothStateChange: up=true
08-09 07:51:25.696  1361  1383 D BluetoothMap: onBluetoothStateChange: up=true
08-09 07:51:25.696  3949  3949 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-09 07:51:25.697  3949  3949 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-09 07:51:25.698  3662  3662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 07:51:25.698  1361  1361 D BluetoothMap: Proxy object connected
08-09 07:51:25.698  1361  1361 D MapProfile: Bluetooth service connected
08-09 07:51:25.698  1361  1361 D BluetoothMap: getConnectedDevices()
08-09 07:51:25.699  1361  1377 D BluetoothPbap: onBluetoothStateChange: up=true
,08-09 07:51:25.699  3949  3949 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 07:51:25.701  3850  3863 D BluetoothMap: onBluetoothStateChange: up=true
,08-09 07:51:25.701   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-09 07:51:25.703   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
,08-09 07:51:25.703  3949  3949 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 07:51:25.707  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 07:51:25.708  3850  3850 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-09 07:51:25.708  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 07:51:25.708  3949  3949 D ObexServerSockets: Succeed to create listening sockets 
,08-09 07:51:25.708  3949  3949 D ObexServerSockets0: startAccept()
,08-09 07:51:25.708  3949  3949 D ObexServerSockets0: prepareForNewConnect()
,08-09 07:51:25.711  3949  3949 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-09 07:51:25.711  3949  3949 D BluetoothSdpJni: SDP Create record success - handle: 0
08-09 07:51:25.711  3850  3850 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-09 07:51:25.712   874   874 D BluetoothA2dp: Proxy object connected
08-09 07:51:25.712  3949  3949 D BluetoothMapService: onReceive
08-09 07:51:25.713  3949  3949 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 07:51:25.713  3949  3949 D BluetoothMapService: STATE_ON
08-09 07:51:25.714  1361  1361 D BluetoothA2dp: Proxy object connected
08-09 07:51:25.714  3949  4146 D ObexServerSockets0: Accepting socket connection...
08-09 07:51:25.715  3949  4145 D ObexServerSockets0: Accepting socket connection...
,08-09 07:51:25.721  3850  3850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-09 07:51:25.724  3850  3850 D BluetoothA2dp: Proxy object connected
,08-09 07:51:25.728  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 07:51:25.735  3850  3850 D DockEventReceiver: finishStartingService: stopping service
,08-09 07:51:25.737  3850  3850 D BluetoothPbap: Proxy object connected
,08-09 07:51:25.738  1361  1361 D BluetoothPbap: Proxy object connected
08-09 07:51:25.738  1361  1361 D PbapServerProfile: Bluetooth service connected
,08-09 07:51:25.738  3850  3850 D PbapServerProfile: Bluetooth service connected
,08-09 07:51:25.744  3949  3949 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-09 07:51:25.744  3949  3949 D ObexServerSockets0: prepareForNewConnect()
,08-09 07:51:25.749  3949  4150 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 07:51:25.763  3949  4154 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 07:51:25.765  3949  4154 I BtOppRfcommListener: Accept thread started.
,08-09 07:51:25.785   874   874 D BluetoothHeadset: Proxy object connected
,08-09 07:51:25.786  1723  1735 D BluetoothHeadset: Proxy object connected
,08-09 07:51:25.787  1361  1835 D BluetoothHeadset: Proxy object connected
,08-09 07:51:25.787  1361  1361 D HeadsetProfile: Bluetooth service connected
08-09 07:51:25.787   874   874 D BluetoothHeadset: Proxy object connected
,08-09 07:51:25.787   874   874 D BluetoothHeadset: Proxy object connected
,08-09 07:51:25.791  1361  1383 D BluetoothHeadset: Proxy object connected
,08-09 07:51:25.791  1361  1361 D HeadsetProfile: Bluetooth service connected
,08-09 07:51:25.793   874   891 D BluetoothHeadset: Proxy object connected
,08-09 07:51:25.795   874   891 D BluetoothHeadset: Proxy object connected
,08-09 07:51:25.802   874   891 D BluetoothHeadset: Proxy object connected
,08-09 07:51:25.818  3850  3861 D BluetoothHeadset: Proxy object connected
,08-09 07:51:25.819  3850  3850 D HeadsetProfile: Bluetooth service connected
,08-09 07:51:27.285  3949  4117 D BluetoothAdapterState: Current state: ON, message: 23
,08-09 07:51:27.286  3949  4117 D BluetoothAdapterProperties: Setting state to 13
,08-09 07:51:27.286  3949  4117 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-09 07:51:27.287  3949  4117 D BluetoothAdapterProperties: onBluetoothDisable()
,08-09 07:51:27.290  3949  4117 I BluetoothAdapterState: Entering PendingCommandState
,08-09 07:51:27.299  3949  3949 D BluetoothMapService: onReceive
08-09 07:51:27.299  3949  3949 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 07:51:27.299  3949  3949 D BluetoothMapService: STATE_TURNING_OFF
08-09 07:51:27.300  3949  3949 D BluetoothMapService: MAP Service closeService in
08-09 07:51:27.300  3949  3949 D BluetoothMapMasInstance0: MAP Service shutdown
08-09 07:51:27.300  3949  3949 D ObexServerSockets0: shutdown(block = true)
,08-09 07:51:27.301  3949  3949 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-09 07:51:27.301  3949  3949 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-09 07:51:27.301  3949  4145 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-09 07:51:27.302  3949  4146 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-09 07:51:27.303  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 07:51:27.303  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 07:51:27.303  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:27.303  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:27.303  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 07:51:27.303  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 07:51:27.303  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 07:51:27.303  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 07:51:27.303  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 07:51:27.304  3949  4121 D BluetoothAdapterProperties: Scan Mode:20
08-09 07:51:27.304  3949  4117 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-09 07:51:27.306  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 07:51:27.306  3662  3662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 07:51:27.306  3949  4132 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-09 07:51:27.307  3949  3949 I BtOppRfcommListener: stopping Accept Thread
08-09 07:51:27.308  3949  4154 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-09 07:51:27.309  3949  4154 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-09 07:51:27.313  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-09 07:51:27.313  3949  3949 D HeadsetService: Received stop request...Stopping profile...
,08-09 07:51:27.313  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 07:51:27.313  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:27.313  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:27.313  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 07:51:27.313  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-09 07:51:27.313  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 07:51:27.313  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 07:51:27.313  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 07:51:27.314  3662  3662 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-09 07:51:27.314  3662  3662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 07:51:27.315   874   874 D BluetoothHeadset: Proxy object disconnected
08-09 07:51:27.316  3850  3861 D BluetoothHeadset: Proxy object disconnected
08-09 07:51:27.316  1723  1737 D BluetoothHeadset: Proxy object disconnected
08-09 07:51:27.316  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 07:51:27.316  3949  3949 D A2dpService: Received stop request...Stopping profile...
08-09 07:51:27.316  3949  4138 D A2dpStateMachine: Exit Disconnected: -1
08-09 07:51:27.317  1361  1837 D BluetoothHeadset: Proxy object disconnected
08-09 07:51:27.317   874   874 D BluetoothHeadset: Proxy object disconnected
08-09 07:51:27.317   874   874 D BluetoothHeadset: Proxy object disconnected
,08-09 07:51:27.318  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 07:51:27.318   874   874 D BluetoothA2dp: Proxy object disconnected
08-09 07:51:27.318  3850  3850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-09 07:51:27.319  3949  3949 D HidService: Received stop request...Stopping profile...
,08-09 07:51:27.319  3949  3949 D HidService: Stopping Bluetooth HidService
08-09 07:51:27.322  3850  3850 D HeadsetProfile: Bluetooth service disconnected
08-09 07:51:27.322  3850  3850 D BluetoothA2dp: Proxy object disconnected
08-09 07:51:27.323  3949  3949 D HealthService: Received stop request...Stopping profile...
08-09 07:51:27.324  3949  3949 V BluetoothAdapterState: isTurningOff()=true
08-09 07:51:27.324  3949  3949 V BluetoothAdapterState: isTurningOn()=false
08-09 07:51:27.324  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:27.324  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
08-09 07:51:27.325   874  1310 D ConnectivityService: handlePromptUnvalidated 101
,08-09 07:51:27.326  1361  1361 D HeadsetProfile: Bluetooth service disconnected
08-09 07:51:27.326  1361  1361 D BluetoothA2dp: Proxy object disconnected
08-09 07:51:27.326  1361  1361 D BluetoothInputDevice: Proxy object disconnected
08-09 07:51:27.326  3949  3949 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-09 07:51:27.326  1361  1361 D HidProfile: Bluetooth service disconnected
,08-09 07:51:27.326  3949  3949 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-09 07:51:27.326  3949  4121 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-09 07:51:27.326  3949  4128 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 07:51:27.327  3949  4128 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 07:51:27.327  3949  4128 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 07:51:27.327  3949  4121 E bt_btif : btif_hf_upstreams_evt: Invalid index 30574
,08-09 07:51:27.327  3949  3949 D PanService: Received stop request...Stopping profile...
08-09 07:51:27.329  3949  3949 V BluetoothAdapterState: isTurningOff()=true
08-09 07:51:27.329  3949  3949 V BluetoothAdapterState: isTurningOn()=false
08-09 07:51:27.329  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:27.329  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
08-09 07:51:27.329  3949  3949 D BluetoothMapService: Received stop request...Stopping profile...
08-09 07:51:27.329  3949  3949 D BluetoothMapService: stop()
08-09 07:51:27.330  3949  3949 D BluetoothMapAppObserver: deinitObservers()
,08-09 07:51:27.330  3949  3949 D BluetoothMapAppObserver: removeReceiver()
08-09 07:51:27.332  3949  4121 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-09 07:51:27.333  3949  4128 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 07:51:27.333  3949  3949 V BluetoothAdapterState: isTurningOff()=true
08-09 07:51:27.333  3949  4128 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-09 07:51:27.333  3949  3949 V BluetoothAdapterState: isTurningOn()=false
,08-09 07:51:27.333  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:27.333  3949  4128 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 07:51:27.333  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
08-09 07:51:27.333  3949  4128 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-09 07:51:27.333  3949  4128 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-09 07:51:27.333  3949  4128 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-09 07:51:27.334  3949  3949 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-09 07:51:27.334  3949  3949 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-09 07:51:27.334  3949  4121 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-09 07:51:27.335  3850  3850 D DockEventReceiver: finishStartingService: stopping service
08-09 07:51:27.337  3949  3949 V BluetoothAdapterState: isTurningOff()=true
08-09 07:51:27.337  3949  3949 V BluetoothAdapterState: isTurningOn()=false
,08-09 07:51:27.337  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:27.337  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 07:51:27.337  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
08-09 07:51:27.337  3949  3949 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-09 07:51:27.337  3949  4121 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-09 07:51:27.338  3949  3949 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-09 07:51:27.338  3949  3949 V BluetoothAdapterState: isTurningOff()=true
08-09 07:51:27.338  3949  3949 V BluetoothAdapterState: isTurningOn()=false
08-09 07:51:27.338  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:27.338  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
08-09 07:51:27.338  3949  3949 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-09 07:51:27.338  3949  3949 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-09 07:51:27.339  3949  3949 D BluetoothMapService: MAP Service closeService in
08-09 07:51:27.339  3949  3949 V BluetoothAdapterState: isTurningOff()=true
08-09 07:51:27.339  3949  3949 V BluetoothAdapterState: isTurningOn()=false
08-09 07:51:27.339  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:27.339  3949  3949 V BluetoothAdapterState: isBleTurningOff()=false
08-09 07:51:27.340  3949  4117 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-09 07:51:27.340  3949  4117 D BluetoothAdapterProperties: Setting state to 15
08-09 07:51:27.340  3949  4117 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-09 07:51:27.340  3850  3850 D BluetoothInputDevice: Proxy object disconnected
08-09 07:51:27.340  3850  3850 D HidProfile: Bluetooth service disconnected
08-09 07:51:27.341  3949  4117 I BluetoothAdapterState: Entering BleOnState
08-09 07:51:27.341  3850  3861 D BluetoothPan: onBluetoothStateChange on: false
08-09 07:51:27.341  3949  3949 D BluetoothMapService: cleanup()
08-09 07:51:27.341  3949  3949 D BluetoothMapService: MAP Service closeService in
08-09 07:51:27.342  1723  1863 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 07:51:27.343  1361  1835 D BluetoothPan: onBluetoothStateChange on: false
08-09 07:51:27.343  1361  1361 D BluetoothMap: Proxy object disconnected
08-09 07:51:27.343  1361  1361 D MapProfile: Bluetooth service disconnected
08-09 07:51:27.344  1361  1361 D BluetoothPbap: Proxy object disconnected
08-09 07:51:27.344  1361  1361 D PbapServerProfile: Bluetooth service disconnected
08-09 07:51:27.344  1361  1383 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-09 07:51:27.343  3850  3850 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-09 07:51:27.344  3850  3850 D PanProfile: Bluetooth service disconnected
08-09 07:51:27.346  1361  1835 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 07:51:27.347  3850  3862 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-09 07:51:27.347   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 07:51:27.347   874   891 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 07:51:27.348  3850  3861 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 07:51:27.348  1361  1377 D BluetoothA2dp: onBluetoothStateChange: up=false
08-09 07:51:27.351   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 07:51:27.352  3850  3863 D BluetoothPbap: onBluetoothStateChange: up=false
08-09 07:51:27.353  1361  1837 D BluetoothMap: onBluetoothStateChange: up=false
08-09 07:51:27.353  1361  1383 D BluetoothPbap: onBluetoothStateChange: up=false
08-09 07:51:27.354  3850  3861 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 07:51:27.356  3850  3862 D BluetoothMap: onBluetoothStateChange: up=false
08-09 07:51:27.353  3850  3850 D BluetoothMap: Proxy object disconnected
08-09 07:51:27.356  3850  3850 D MapProfile: Bluetooth service disconnected
08-09 07:51:27.356   874   891 D BluetoothHeadset: onBluetoothStateChange: up=false
08-09 07:51:27.356  3949  4117 D BluetoothAdapterState: Current state: BLE ON, message,: 20
08-09 07:51:27.357  3949  4117 D BluetoothAdapterProperties: Setting state to 16
08-09 07:51:27.357  3949  4117 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-09 07:51:27.357  3949  4117 D BluetoothAdapterProperties: onBleDisable
08-09 07:51:27.357  3949  4117 I BluetoothAdapterState: Entering PendingCommandState
08-09 07:51:27.358  3949  4118 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-09 07:51:27.359  3949  4121 D BluetoothAdapterProperties: Scan Mode:20
08-09 07:51:27.361  3949  4128 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-09 07:51:27.361  3949  4128 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-09 07:51:27.364  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 07:51:27.365  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 07:51:27.366  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 07:51:27.367  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 07:51:27.372  3850  3850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-09 07:51:27.377  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 07:51:27.378  3850  3850 D DockEventReceiver: finishStartingService: stopping service
,08-09 07:51:27.565  3949  4121 I bt_hci  : shut_down
,08-09 07:51:27.576  3949  4126 D bt_hwcfg: hw_epilog_process
,08-09 07:51:27.577  3949  4126 I bt_vendor: low_power_mode_cb
,08-09 07:51:27.596  3949  4126 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-09 07:51:27.596  3949  4126 I bt_vendor: epilog_cb
08-09 07:51:27.596  3949  4126 I bt_hci  : epilog_finished_callback
,08-09 07:51:27.604  3949  4121 I bt_hci_h4: hal_close
,08-09 07:51:27.606  3949  4121 I bt_userial_vendor: device fd = 51 close
,08-09 07:51:27.722  3949  4118 D bt_stack_manager: event_shut_down_stack finished.
,08-09 07:51:27.723  3949  4117 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-09 07:51:27.729  3949  4117 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-09 07:51:27.730  3949  3949 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-09 07:51:27.731  3949  3949 D BtGatt.GattService: Received stop request...Stopping profile...
,08-09 07:51:27.732  3949  3949 D BtGatt.GattService: stop()
,08-09 07:51:27.732  3949  3949 D BtGatt.AdvertiseManager: advertise clients cleared
,08-09 07:51:27.737  3949  3949 V BluetoothAdapterState: isTurningOff()=false
,08-09 07:51:27.737  3949  3949 V BluetoothAdapterState: isTurningOn()=false
08-09 07:51:27.738  3949  3949 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 07:51:27.738  3949  3949 V BluetoothAdapterState: isBleTurningOff()=true
,08-09 07:51:27.739  3949  4117 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-09 07:51:27.740  3949  4117 D BluetoothAdapterProperties: Setting state to 10
,08-09 07:51:27.740  3949  4117 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-09 07:51:27.742  3949  4117 I BluetoothAdapterState: Entering OffState
08-09 07:51:27.743   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-09 07:51:27.772  3949  3949 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-09 07:51:27.773  3949  3949 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-09 07:51:27.773  3949  4118 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-09 07:51:27.782  3949  4118 D bt_stack_manager: event_clean_up_stack finished.
,08-09 07:51:27.785  3949  3949 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-09 07:51:27.793  3949  3949 I art     : System.exit called, status: 0
,08-09 07:51:27.793  3949  3949 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-09 07:51:27.841   874  1696 D AlarmManagerService: Setting time of day to sec=1470721888
,08-09 07:51:28.813   874  1696 W AlarmManagerService: Unable to set rtc to 1470721888: Invalid argument
,08-09 07:51:28.822   874   887 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 76)
,08-09 07:51:28.823   874   887 W ActivityManager: Failed to update preferences for: com.android.bluetooth
,08-09 07:51:28.839   874   885 I ActivityManager: Process com.android.bluetooth (pid 3949) has died
,08-09 07:51:28.906   874   884 I ActivityManager: Start proc 4161:com.google.android.calendar/u0a37 for broadcast com.google.android.calendar/com.android.calendar.widget.CalendarAppWidgetProvider
,08-09 07:51:28.967  4161  4161 W System  : ClassLoader referenced unknown path: /system/app/CalendarGooglePrebuilt/lib/arm
,08-09 07:51:29.065   874   885 I ActivityManager: Start proc 4176:com.android.providers.calendar/u0a3 for content provider com.android.providers.calendar/.CalendarProvider2
,08-09 07:51:29.125  4176  4176 W System  : ClassLoader referenced unknown path: /system/priv-app/CalendarProvider/lib/arm
,08-09 07:51:29.164   874  1772 I ActivityManager: Start proc 4191:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.deskclock.AlarmInitReceiver
,08-09 07:51:29.165   874  1772 I ActivityManager: Killing 3397:com.android.vending/u0a19 (adj 15): empty #17
,08-09 07:51:29.245   874  1772 I ActivityManager: Killing 3591:com.google.android.apps.docs/u0a46 (adj 15): empty #18
,08-09 07:51:29.354  4176  4176 I CalendarProvider2: Created com.android.providers.calendar.CalendarAlarmManager@65f3e72(com.android.providers.calendar.CalendarProvider2@9c082c3)
,08-09 07:51:29.371  4161  4161 I AnalyticsLogBase: PlayLogger.onLoggerConnected
,08-09 07:51:29.388  4191  4191 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,08-09 07:51:29.414  4191  4191 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-09 07:51:29.414  4191  4191 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-09 07:51:29.414  4191  4191 I GAv4    :   adb logcat -s GAv4
,08-09 07:51:29.435  4191  4191 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-09 07:51:29.440  4191  4191 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-09 07:51:29.454  4191  4207 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-09 07:51:29.525   874  1772 I ActivityManager: Start proc 4210:com.qualcomm.timeservice/1000 for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver
,08-09 07:51:29.581  4210  4210 W System  : ClassLoader referenced unknown path: /system/app/TimeService/lib/arm
,08-09 07:51:29.596  4210  4210 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1470721889595
,08-09 07:51:29.596  4210  4210 D         : TimeServiceNative: User Time to be set is 1470721889596
08-09 07:51:29.596  4210  4210 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-09 07:51:29.596  4210  4210 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-09 07:51:29.596  4210  4210 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1470721889596
08-09 07:51:29.596   392  1001 D QC-time-services: Daemon: Connection accepted:time_genoff
08-09 07:51:29.596  4210  4210 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-09 07:51:29.597   392  4222 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1470721889596
08-09 07:51:29.597   392  4222 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1470721889596, operation = 0
,08-09 07:51:29.598   392  4222 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/26/70 2:1:50
,08-09 07:51:29.598   392  4222 D QC-time-services: Daemon:Value read from RTC seconds = 31024910000
08-09 07:51:29.598   392  4222 D QC-time-services: Daemon:new time 1470721889596 
08-09 07:51:29.599   392  4222 D QC-time-services: Daemon: delta 1439696979596 genoff 1439696979596 
08-09 07:51:29.599   392  4222 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696979596 to memory
,08-09 07:51:29.599   392  4222 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-09 07:51:29.599   392  4222 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-09 07:51:29.610   392  4222 D QC-time-services: Updating the TOD offset
,08-09 07:51:29.610   392  4222 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1439696979596 to memory
08-09 07:51:29.610   392  4222 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-09 07:51:29.610   392  4222 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-09 07:51:29.615   392  4222 E QC-time-services: Daemon:Update to modem bit set
,08-09 07:51:29.615   392  4222 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-09 07:51:29.615   392  4222 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1154757089596
08-09 07:51:29.615  4210  4210 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,08-09 07:51:29.617   874   885 I ActivityManager: Killing 1807:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,08-09 07:51:29.645   392  1001 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-09 07:51:29.651   392   997 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,08-09 07:51:29.663   874  1309 D WifiService: Client connection lost with reason: 4
,08-09 07:51:30.472  4176  4176 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar flg=0x20000000 }
,08-09 07:51:30.476  4176  4176 W ContentResolver: Failed to get type for: content://com.android.calendar (Unknown URL content://com.android.calendar)
,08-09 07:51:31.254  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
,08-09 07:51:31.254  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 07:51:31.414   874  1296 I ActivityManager: Start proc 4227:com.android.vending/u0a19 for service com.android.vending/com.google.android.finsky.services.ContentSyncService
,08-09 07:51:31.490  4227  4227 W System  : ClassLoader referenced unknown path: /system/priv-app/Phonesky/lib/arm
,08-09 07:51:31.615  4227  4227 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-09 07:51:31.764  4227  4227 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
,08-09 07:51:31.798  4227  4227 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-09 07:51:31.800  4227  4227 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-09 07:51:31.861  4227  4262 D Ads     : Skipping gmscore version check
,08-09 07:51:31.868  4227  4227 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,08-09 07:51:31.869  4227  4227 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,08-09 07:51:31.879  4227  4227 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-09 07:51:31.905  4227  4262 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-09 07:51:31.907  4227  4227 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-09 07:51:32.298  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:51:32.313  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:51:32.318  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:51:32.364  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-09 07:51:32.364  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-09 07:51:32.365  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:51:32.365  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:51:32.389  4227  4227 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-09 07:51:32.390  4227  4227 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-09 07:51:32.391  4227  4227 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-09 07:51:32.408   874   884 I ActivityManager: Killing 3723:com.google.android.youtube/u0a86 (adj 15): empty #17
,08-09 07:51:34.160  4161  4184 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-09 07:51:34.262  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-09 07:51:34.262  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1225652 added. We now have 6 listener(s)
08-09 07:51:34.263  3662  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 07:51:34.266  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-09 07:51:34.267  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@757ed23 added. We now have 7 listener(s)
08-09 07:51:34.267  3662  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 07:51:34.269  3662  3713 I System.out: IsBluetoothEnabled
,08-09 07:51:34.278  3662  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 07:51:34.337   874   891 I ActivityManager: Start proc 4269:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-09 07:51:34.455  4269  4269 D AdapterServiceConfig: Adding HeadsetService
,08-09 07:51:34.455  4269  4269 D AdapterServiceConfig: Adding A2dpService
08-09 07:51:34.456  4269  4269 D AdapterServiceConfig: Adding HidService
,08-09 07:51:34.457  4269  4269 D AdapterServiceConfig: Adding HealthService
,08-09 07:51:34.457  4269  4269 D AdapterServiceConfig: Adding PanService
08-09 07:51:34.458  4269  4269 D AdapterServiceConfig: Adding GattService
,08-09 07:51:34.458  4269  4269 D AdapterServiceConfig: Adding BluetoothMapService
,08-09 07:51:34.486   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@653c1dc:true
,08-09 07:51:34.486  4269  4269 D BluetoothAdapterState: make() - Creating AdapterState
,08-09 07:51:34.492  4269  4269 I bt_bluedroid: init
,08-09 07:51:34.493  4269  4281 I BluetoothAdapterState: Entering OffState
,08-09 07:51:34.499  4269  4282 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-09 07:51:34.499  4269  4282 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-09 07:51:34.499  4269  4282 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-09 07:51:34.500  4269  4282 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-09 07:51:34.502  4269  4269 I bt_bluedroid: get_profile_interface socket
,08-09 07:51:34.504  4269  4285 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-09 07:51:34.506  4269  4285 D BluetoothAdapterProperties: Name is: Nexus 6
08-09 07:51:34.507  4269  4269 I bt_bluedroid: get_profile_interface sdp
,08-09 07:51:34.513  4269  4279 I bt_bluedroid: config_hci_snoop_log
,08-09 07:51:34.516   874   891 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-09 07:51:34.523  4269  4281 D BluetoothAdapterState: Current state: OFF, message: 0
,08-09 07:51:34.523  4269  4281 D BluetoothAdapterProperties: Setting state to 14
08-09 07:51:34.524  4269  4281 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-09 07:51:34.528  4269  4281 D BluetoothBondStateMachine: make
,08-09 07:51:34.534  4269  4286 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-09 07:51:34.540  4269  4281 I BluetoothAdapterState: Entering PendingCommandState
,08-09 07:51:34.543  4269  4269 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-09 07:51:34.551  4269  4269 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f3976c
,08-09 07:51:34.553  4269  4269 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-09 07:51:34.555  4269  4269 D BtGatt.GattService: Received start request. Starting profile...
08-09 07:51:34.555  4269  4269 D BtGatt.GattService: start()
08-09 07:51:34.555  4269  4269 I bt_bluedroid: get_profile_interface gatt
,08-09 07:51:34.557  4269  4269 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f3976c
,08-09 07:51:34.558  4269  4269 D BtGatt.AdvertiseManager: advertise manager created
,08-09 07:51:34.566  4269  4269 V BluetoothAdapterState: isTurningOff()=false
08-09 07:51:34.566  4269  4269 V BluetoothAdapterState: isTurningOn()=false
,08-09 07:51:34.567  4269  4269 V BluetoothAdapterState: isBleTurningOn()=true
08-09 07:51:34.567  4269  4269 V BluetoothAdapterState: isBleTurningOff()=false
08-09 07:51:34.567  4269  4281 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-09 07:51:34.568  4269  4281 I bt_bluedroid: enable
08-09 07:51:34.568  4269  4282 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-09 07:51:34.569  4269  4282 I bt_hci  : start_up
,08-09 07:51:34.577  4269  4282 I bt_vendor: alloc value 0xb3a0a189
08-09 07:51:34.577  4269  4282 I bt_vendor: init
08-09 07:51:34.577  4269  4282 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-09 07:51:34.577  4269  4282 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-09 07:51:34.684  4269  4282 D bt_hci  : start_up starting async portion
08-09 07:51:34.684  4269  4289 I bt_hci  : event_finish_startup
,08-09 07:51:34.684  4269  4289 I bt_hci_h4: hal_open
08-09 07:51:34.684  4269  4289 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-09 07:51:34.689  4269  4289 I bt_userial_vendor: device fd = 51 open
,08-09 07:51:34.726  4269  4289 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-09 07:51:34.759  4269  4289 D bt_hwcfg: Chipset BCM4354A2
08-09 07:51:34.760  4269  4289 D bt_hwcfg: Target name = [BCM4354A2]
08-09 07:51:34.761  4269  4289 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-09 07:51:35.433  4269  4289 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-09 07:51:35.434  4269  4289 D bt_hwcfg: Settlement delay -- 100 ms
,08-09 07:51:35.434  4269  4289 I bt_hwcfg: Setting fw settlement delay to 100 
,08-09 07:51:35.551  4269  4289 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-09 07:51:35.552  4269  4289 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-09 07:51:35.582  4269  4289 I bt_hwcfg: vendor lib fwcfg completed
,08-09 07:51:35.582  4269  4289 I bt_vendor: firmware callback
08-09 07:51:35.582  4269  4289 I bt_hci  : firmware_config_callback
,08-09 07:51:35.601  4227  4227 D Finsky  : [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,08-09 07:51:35.605  4269  4292 I bt_btu  : btu_task pending for preload complete event,
08-09 07:51:35.605  4269  4292 I bt_btu_task: Bluetooth chip preload is complete
08-09 07:51:35.606  4269  4292 I bt_btu  : btu_task received preload complete event
,08-09 07:51:35.615  4269  4292 I         : BTE_InitTraceLevels -- TRC_HCI
,08-09 07:51:35.615  4269  4292 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-09 07:51:35.615  4269  4292 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-09 07:51:35.615  4269  4292 I         : BTE_InitTraceLevels -- TRC_AVDT
08-09 07:51:35.616  4269  4292 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-09 07:51:35.616  4269  4292 I         : BTE_InitTraceLevels -- TRC_A2D
,08-09 07:51:35.616  4269  4292 I         : BTE_InitTraceLevels -- TRC_BNEP
08-09 07:51:35.617  4269  4292 I         : BTE_InitTraceLevels -- TRC_BTM
08-09 07:51:35.617  4269  4292 I         : BTE_InitTraceLevels -- TRC_GAP
08-09 07:51:35.617  4269  4292 I         : BTE_InitTraceLevels -- TRC_PAN
08-09 07:51:35.617  4269  4292 I         : BTE_InitTraceLevels -- TRC_SDP
,08-09 07:51:35.618  4269  4292 I         : BTE_InitTraceLevels -- TRC_GATT
08-09 07:51:35.618  4269  4292 I         : BTE_InitTraceLevels -- TRC_SMP
08-09 07:51:35.618  4269  4292 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-09 07:51:35.618  4269  4292 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-09 07:51:35.628  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:51:35.663  1515  2416 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-09 07:51:35.664  1515  2416 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-09 07:51:35.664  1515  2416 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:51:35.664  1515  2416 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:51:35.687  4227  4227 W Finsky  : [1] DailyHygiene$1.onErrorResponse: Unable to preload experiments: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-09 07:51:35.698  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:51:35.737  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-09 07:51:35.738  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-09 07:51:35.738  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 07:51:35.738  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:51:35.743  4269  4292 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3987d9d
08-09 07:51:35.743  4269  4292 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3987d9d 
,08-09 07:51:35.761  4269  4285 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-09 07:51:35.763  4269  4285 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-09 07:51:35.763  4269  4285 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-09 07:51:35.766  4269  4285 D BluetoothAdapterProperties: Name is: Nexus 6
,08-09 07:51:35.770  4269  4285 D BluetoothAdapterProperties: Scan Mode:20
08-09 07:51:35.770  4269  4285 D BluetoothAdapterProperties: Discoverable Timeout:120
08-09 07:51:35.771  4269  4285 D bt_hci  : do_postload posting postload work item
08-09 07:51:35.771  4269  4289 I bt_hci  : event_postload
,08-09 07:51:35.771  4269  4289 I bt_vendor: sco_config_cb
,08-09 07:51:35.771  4269  4289 I bt_hci  : sco_config_callback postload finished.
08-09 07:51:35.772  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:35.776  4269  4285 D bt_bte_conf: Device ID record 1 : primary
08-09 07:51:35.776  4269  4285 D bt_bte_conf:   vendorId            = 000f
08-09 07:51:35.777  4269  4285 D bt_bte_conf:   vendorIdSource      = 0001
08-09 07:51:35.777  4269  4285 D bt_bte_conf:   product             = 1200
08-09 07:51:35.777  4269  4289 I bt_vendor: low_power_mode_cb
08-09 07:51:35.777  4269  4285 D bt_bte_conf:   version             = 1436
08-09 07:51:35.777  4269  4285 D bt_bte_conf:   clientExecutableURL = 
08-09 07:51:35.777  4269  4285 D bt_bte_conf:   serviceDescription  = 
08-09 07:51:35.778  4269  4285 D bt_bte_conf:   documentationURL    = 
,08-09 07:51:35.778  4269  4285 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-09 07:51:35.778  4269  4282 D bt_stack_manager: event_start_up_stack finished
08-09 07:51:35.779  4269  4281 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-09 07:51:35.779  4269  4281 D BluetoothAdapterProperties: Setting state to 15
08-09 07:51:35.779  4269  4281 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-09 07:51:35.780  4269  4281 I BluetoothAdapterState: Entering BleOnState
,08-09 07:51:35.783  4269  4281 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-09 07:51:35.783  4269  4281 D BluetoothAdapterProperties: Setting state to 11
08-09 07:51:35.783  4269  4281 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-09 07:51:35.788  4269  4269 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f3976c
,08-09 07:51:35.790  4269  4269 D HeadsetService: Received start request. Starting profile...
,08-09 07:51:35.791  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:35.794  4269  4269 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-09 07:51:35.794  4269  4269 D HeadsetStateMachine: make
,08-09 07:51:35.801  4269  4281 I BluetoothAdapterState: Entering PendingCommandState
,08-09 07:51:35.804  4269  4269 D HeadsetStateMachine: max_hf_connections = 1
,08-09 07:51:35.806  4269  4269 I bt_bluedroid: get_profile_interface handsfree
08-09 07:51:35.806  4269  4285 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-09 07:51:35.807  4269  4285 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-09 07:51:35.811  4269  4269 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f3976c
08-09 07:51:35.812  4269  4269 D A2dpService: Received start request. Starting profile...
,08-09 07:51:35.813  4269  4269 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-09 07:51:35.813  4269  4269 I bt_bluedroid: get_profile_interface avrcp
,08-09 07:51:35.819  4269  4269 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-09 07:51:35.819  4269  4269 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-09 07:51:35.826  4269  4269 D A2dpStateMachine: make
08-09 07:51:35.826  4227  4301 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-09 07:51:35.826  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-09 07:51:35.827  4269  4269 I bt_bluedroid: get_profile_interface a2dp
08-09 07:51:35.828  4269  4285 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-09 07:51:35.829  4227  4227 W Finsky  : [1] GearheadStateMonitor$3.onConnectionFailed: Could not connect to GMS for Auto connection state: ConnectionResult{statusCode=SERVICE_VERSION_UPDATE_REQUIRED, resolution=null, message=null}
,08-09 07:51:35.829  4269  4302 D A2dpStateMachine: Enter Disconnected: -2
08-09 07:51:35.829  4227  4227 V Finsky  : [1] GearheadStateMonitor.access$100: mIsProjecting:false
,08-09 07:51:35.831  4269  4269 I BluetoothHidServiceJni: classInitNative: succeeds
08-09 07:51:35.832  4269  4269 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f3976c
08-09 07:51:35.832  4269  4269 D HidService: Received start request. Starting profile...
08-09 07:51:35.832  4269  4269 I bt_bluedroid: get_profile_interface hidhost
,08-09 07:51:35.833  4269  4269 D HidService: setHidService(): set to: null
08-09 07:51:35.833  4269  4285 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39693e5
08-09 07:51:35.833  4269  4285 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-09 07:51:35.833  4269  4269 I BluetoothHealthServiceJni: classInitNative: succeeds
08-09 07:51:35.834  4269  4269 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f3976c
08-09 07:51:35.834  4269  4269 D HealthService: Received start request. Starting profile...
,08-09 07:51:35.836  4269  4269 I bt_bluedroid: get_profile_interface health
,08-09 07:51:35.839  4269  4269 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-09 07:51:35.839  4269  4269 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f3976c
08-09 07:51:35.839  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-09 07:51:35.840  4269  4269 D PanService: Received start request. Starting profile...
,08-09 07:51:35.840  4269  4269 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-09 07:51:35.840  4269  4269 I bt_bluedroid: get_profile_interface pan
08-09 07:51:35.841  4269  4285 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-09 07:51:35.843  4269  4269 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f3976c
,08-09 07:51:35.844  4269  4269 D BluetoothMapService: Received start request. Starting profile...
08-09 07:51:35.844  4269  4269 D BluetoothMapService: start()
08-09 07:51:35.846  4269  4269 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-09 07:51:35.847  4269  4269 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-09 07:51:35.847  4269  4269 D BluetoothMapAppObserver: createReceiver()
,08-09 07:51:35.848  4269  4269 D BluetoothMapAppObserver: initObservers()
08-09 07:51:35.848  4269  4269 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-09 07:51:35.851  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-09 07:51:35.851  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-09 07:51:35.851  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 07:51:35.851  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-09 07:51:35.855  4269  4269 V BluetoothAdapterState: isTurningOff()=false
08-09 07:51:35.855  4269  4269 V BluetoothAdapterState: isTurningOn()=true
08-09 07:51:35.855  4269  4269 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:35.855  4269  4299 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-09 07:51:35.856  4269  4269 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 07:51:35.858  4269  4269 V BluetoothAdapterState: isTurningOff()=false
,08-09 07:51:35.858  4269  4269 V BluetoothAdapterState: isTurningOn()=true
08-09 07:51:35.859  4269  4269 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:35.859  4269  4269 V BluetoothAdapterState: isBleTurningOff()=false
08-09 07:51:35.859  4269  4269 V BluetoothAdapterState: isTurningOff()=false
08-09 07:51:35.859  4269  4269 V BluetoothAdapterState: isTurningOn()=true
08-09 07:51:35.859  4269  4269 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 07:51:35.859  4269  4269 V BluetoothAdapterState: isBleTurningOff()=false
08-09 07:51:35.859  4269  4269 V BluetoothAdapterState: isTurningOff()=false
08-09 07:51:35.859  4269  4269 V BluetoothAdapterState: isTurningOn()=true
08-09 07:51:35.859  4269  4269 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:35.859  4269  4269 V BluetoothAdapterState: isBleTurningOff()=false
08-09 07:51:35.859  4269  4269 V BluetoothAdapterState: isTurningOff()=false
08-09 07:51:35.860  4269  4269 V BluetoothAdapterState: isTurningOn()=true
,08-09 07:51:35.860  4269  4269 V BluetoothAdapterState: isBleTurningOn()=false
,08-09 07:51:35.860  4269  4269 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 07:51:35.861  4269  4269 V BluetoothAdapterState: isTurningOff()=false
,08-09 07:51:35.861  4269  4269 V BluetoothAdapterState: isTurningOn()=true
08-09 07:51:35.861  4269  4269 V BluetoothAdapterState: isBleTurningOn()=false
08-09 07:51:35.863  4269  4269 V BluetoothAdapterState: isBleTurningOff()=false
,08-09 07:51:35.864  4269  4281 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,08-09 07:51:35.864  4269  4281 D BluetoothAdapterProperties: ScanMode =  20
08-09 07:51:35.864  4269  4281 D BluetoothAdapterProperties: State =  11
08-09 07:51:35.866  4269  4285 D BluetoothAdapterProperties: Scan Mode:21
08-09 07:51:35.866  4269  4285 D BluetoothAdapterProperties: Discoverable Timeout:120
08-09 07:51:35.866  4269  4281 D BluetoothAdapterProperties: Setting state to 12
08-09 07:51:35.866  4269  4281 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-09 07:51:35.867  4227  4227 W Finsky  : [1] LibraryUpdateListener.onErrorResponse: Library replication failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.,
08-09 07:51:35.867  4269  4281 I BluetoothAdapterState: Entering OnState
08-09 07:51:35.867  3850  3862 D BluetoothPan: onBluetoothStateChange on: true
,08-09 07:51:35.869  1723  1737 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-09 07:51:35.869  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 07:51:35.869  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:35.869  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:35.869  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 07:51:35.869  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 07:51:35.869  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 07:51:35.869  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 07:51:35.869  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-09 07:51:35.869  1361  1383 D BluetoothPan: onBluetoothStateChange on: true
08-09 07:51:35.870  3850  3850 D BluetoothPan: BluetoothPAN Proxy object connected
,08-09 07:51:35.870  3850  3850 D PanProfile: Bluetooth service connected
08-09 07:51:35.871  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
08-09 07:51:35.871  1361  1361 D PanProfile: Bluetooth service connected
08-09 07:51:35.871  3662  3662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-09 07:51:35.871  1361  1837 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-09 07:51:35.873  1361  1377 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 07:51:35.873  1361  1361 D BluetoothInputDevice: Proxy object connected
08-09 07:51:35.873  1361  1361 D HidProfile: Bluetooth service connected
08-09 07:51:35.874  4269  4269 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-09 07:51:35.874  3850  3863 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-09 07:51:35.875  4269  4269 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-09 07:51:35.875   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 07:51:35.875  3850  3850 D BluetoothInputDevice: Proxy object connected
08-09 07:51:35.875  3850  3850 D HidProfile: Bluetooth service connected
08-09 07:51:35.875   874   891 D BluetoothA2dp: onBluetoothStateChange: up=true
08-09 07:51:35.876  4269  4269 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 07:51:35.876  3850  3861 D BluetoothA2dp: onBluetoothStateChange: up=true
08-09 07:51:35.878  4269  4269 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-09 07:51:35.879  1361  1383 D BluetoothA2dp: onBluetoothStateChange: up=true
08-09 07:51:35.880  4269  4269 D ObexServerSockets: Succeed to create listening sockets 
08-09 07:51:35.880  4269  4269 D ObexServerSockets0: startAccept()
08-09 07:51:35.880  4269  4269 D ObexServerSockets0: prepareForNewConnect()
,08-09 07:51:35.880   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 07:51:35.881  3850  3862 D BluetoothPbap: onBluetoothStateChange: up=true
,08-09 07:51:35.881  4269  4269 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-09 07:51:35.881  4269  4269 D BluetoothSdpJni: SDP Create record success - handle: 0
08-09 07:51:35.882  4269  4308 D ObexServerSockets0: Accepting socket connection...
,08-09 07:51:35.882  1361  1837 D BluetoothMap: onBluetoothStateChange: up=true
,08-09 07:51:35.883  4269  4309 D ObexServerSockets0: Accepting socket connection...
08-09 07:51:35.883   874   874 D BluetoothA2dp: Proxy object connected
08-09 07:51:35.883  1361  1361 D BluetoothA2dp: Proxy object connected
,08-09 07:51:35.885  3850  3850 D BluetoothA2dp: Proxy object connected
,08-09 07:51:35.885  1361  1383 D BluetoothPbap: onBluetoothStateChange: up=true
,08-09 07:51:35.885  1361  1361 D BluetoothMap: Proxy object connected
,08-09 07:51:35.885  1361  1361 D MapProfile: Bluetooth service connected
08-09 07:51:35.885  1361  1361 D BluetoothMap: getConnectedDevices()
,08-09 07:51:35.886  3850  3861 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 07:51:35.887  3850  3862 D BluetoothMap: onBluetoothStateChange: up=true
08-09 07:51:35.888   874   891 D BluetoothHeadset: onBluetoothStateChange: up=true
08-09 07:51:35.889   874   874 I Telecom : BluetoothPhoneService: queryPhoneState
08-09 07:51:35.889  3850  3850 D BluetoothMap: Proxy object connected
08-09 07:51:35.890  3850  3850 D MapProfile: Bluetooth service connected
08-09 07:51:35.890  3850  3850 D BluetoothMap: getConnectedDevices()
08-09 07:51:35.890  4269  4269 D BluetoothMapService: onReceive
08-09 07:51:35.890  4269  4269 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-09 07:51:35.890  4269  4269 D BluetoothMapService: STATE_ON
08-09 07:51:35.891  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:35.895  3850  3850 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-09 07:51:35.911  4269  4269 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-09 07:51:35.911  4269  4269 D ObexServerSockets0: prepareForNewConnect()
,08-09 07:51:35.915  1515  1515 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-09 07:51:35.939  3850  3850 D DockEventReceiver: finishStartingService: stopping service
,08-09 07:51:35.940  3850  3850 D BluetoothPbap: Proxy object connected
08-09 07:51:35.940  1361  1361 D BluetoothPbap: Proxy object connected
08-09 07:51:35.940  3850  3850 D PbapServerProfile: Bluetooth service connected
08-09 07:51:35.940  1361  1361 D PbapServerProfile: Bluetooth service connected
,08-09 07:51:35.943  4269  4312 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 07:51:35.963  4269  4318 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-09 07:51:35.964  4269  4318 I BtOppRfcommListener: Accept thread started.
,08-09 07:51:35.971   874   874 D BluetoothHeadset: Proxy object connected
08-09 07:51:35.971  3850  3861 D BluetoothHeadset: Proxy object connected
08-09 07:51:35.972  1723  1863 D BluetoothHeadset: Proxy object connected
08-09 07:51:35.972  3850  3850 D HeadsetProfile: Bluetooth service connected
08-09 07:51:35.972  1361  1837 D BluetoothHeadset: Proxy object connected
08-09 07:51:35.972   874   874 D BluetoothHeadset: Proxy object connected
08-09 07:51:35.972  1361  1361 D HeadsetProfile: Bluetooth service connected
08-09 07:51:35.972   874   874 D BluetoothHeadset: Proxy object connected
08-09 07:51:35.974  1361  1377 D BluetoothHeadset: Proxy object connected
08-09 07:51:35.975  1361  1361 D HeadsetProfile: Bluetooth service connected
08-09 07:51:35.975   874   891 D BluetoothHeadset: Proxy object connected
,08-09 07:51:35.980   874   891 D BluetoothHeadset: Proxy object connected
,08-09 07:51:35.987  3850  3863 D BluetoothHeadset: Proxy object connected
,08-09 07:51:35.987  3850  3850 D HeadsetProfile: Bluetooth service connected
,08-09 07:51:35.989   874   891 D BluetoothHeadset: Proxy object connected
,08-09 07:51:36.051  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:51:36.072  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-09 07:51:36.073  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-09 07:51:36.073  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:51:36.073  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:51:36.089  4227  4227 W Finsky  : [1] UpdateChecker$1$2.onErrorResponse: Update check failed: com.android.volley.AuthFailureError: User needs to (re)enter credentials.
,08-09 07:51:36.090  4227  4227 D Finsky  : [1] WearSupportService.startHygiene: disabled
08-09 07:51:36.092  4227  4227 D Finsky  : [1] DailyHygiene.access$600: Logging device features
,08-09 07:51:36.096  4227  4227 D Finsky  : [1] DailyHygiene.reschedule: Scheduling new run in 868 minutes (failures=5)
,08-09 07:51:36.102  4227  4319 W GooglePlayServicesUtil: Google Play services out of date.  Requires 8296000 but found 8186438
,08-09 07:51:36.113   874  1688 I ActivityManager: Killing 3468:com.google.android.apps.books/u0a34 (adj 15): empty #17
,08-09 07:51:36.300  3662  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 07:51:36.300  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:36.300  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:36.300  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-09 07:51:36.300  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 07:51:36.300  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 07:51:36.300  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 07:51:36.300  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 07:51:36.307  3662  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-09 07:51:36.311  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-09 07:51:36.312  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6c2d220 added. We now have 8 listener(s)
08-09 07:51:36.312  3662  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 07:51:36.318   874   884 D WifiService: setWifiEnabled: false pid=3662, uid=10000
,08-09 07:51:36.318   874   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-09 07:51:36.328  3662  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 07:51:36.329   874  1385 D WifiService: setWifiEnabled: true pid=3662, uid=10000
,08-09 07:51:36.329   874  1385 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-09 07:51:36.345   874  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-09 07:51:36.356  3662  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 07:51:36.356  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:36.356  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:36.356  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:51:36.356  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 07:51:36.356  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 07:51:36.356  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 07:51:36.356  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 07:51:36.361  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 07:51:36.361  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:36.361  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:36.361  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:51:36.361  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 07:51:36.361  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-09 07:51:36.361  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-09 07:51:36.361  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-09 07:51:36.364  3662  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 07:51:36.368  3662  3662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-09 07:51:36.371  3662  3713 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-09 07:51:36.371  3662  3713 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-09 07:51:36.373  3662  3713 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@538be58 Bundle[{}]
08-09 07:51:36.374  3662  3713 I io.jxcore.node.LifeCycleMonitor: start: OK
08-09 07:51:36.374  3662  3713 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-09 07:51:36.375  3662  3713 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-09 07:51:36.375  3662  3713 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-09 07:51:36.376  3662  3713 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-09 07:51:36.377  3662  3713 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-09 07:51:36.378   874  1308 D WifiConfigStore: loaded 0 passpoint configs
08-09 07:51:36.379   874  1308 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-09 07:51:36.379   874  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-09 07:51:36.380   874  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-09 07:51:36.381   874  1308 W WifiConfigStore: Upgrading network 2 to android.uid.system:1000
08-09 07:51:36.382   874  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-09 07:51:36.382   874  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 3
08-09 07:51:36.382  3662  3713 I System.out: Running OutgoingSocketThread
08-09 07:51:36.382   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-09 07:51:36.382   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-09 07:51:36.382   874  1308 E WifiConfigStore: found sortedWifiConfigurations : "ktwtestwifi"WPA_EAP
08-09 07:51:36.383  3662  4326 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 419)
08-09 07:51:36.384  3662  4326 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40774
08-09 07:51:36.384  3662  4326 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-09 07:51:36.395   372   872 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-09 07:51:36.395   874  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=1.23 rxSuccessRate=0.95 delta 1000 -> 1000
08-09 07:51:36.396   372   872 D CommandListener: Setting iface cfg
08-09 07:51:36.396   874  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
08-09 07:51:36.396   874  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-09 07:51:36.398   874  1307 D WifiNative-HAL: p2pGetDeviceAddress
08-09 07:51:36.398   874  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
08-09 07:51:36.404   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-09 07:51:36.404   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-09 07:51:36.414   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-09 07:51:36.442   874  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-09 07:51:36.444  1460  1460 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-09 07:51:36.863  1460  1460 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-09 07:51:36.870  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-EAP-SUCCESS EAP authentication completed successfully (based on lower layer success)
,08-09 07:51:36.913  1460  1460 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-09 07:51:36.916  1460  1460 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-09 07:51:36.922   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-09 07:51:36.931   874  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-09 07:51:36.932   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-09 07:51:36.932   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-09 07:51:36.954   874  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-09 07:51:36.970   372   872 D CommandListener: Setting iface cfg
,08-09 07:51:36.971   874  1308 D WifiStateMachine: Start Dhcp Watchdog 3
,08-09 07:51:36.993   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-09 07:51:36.993   874  1310 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,08-09 07:51:36.997   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-09 07:51:37.013   874  4330 D DhcpClient: Receive thread started
,08-09 07:51:37.097   874  1308 E native  : do suspend false
,08-09 07:51:37.118   874  2022 D DhcpClient: Broadcasting DHCPDISCOVER
,08-09 07:51:37.131   874  4330 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,08-09 07:51:37.132   874  2022 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,08-09 07:51:37.135   874  2022 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-09 07:51:37.148   874  4330 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-09 07:51:37.149   874  2022 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-09 07:51:37.154   372   872 D CommandListener: Setting iface cfg
,08-09 07:51:37.167   874  2022 D DhcpClient: Scheduling renewal in 86399s
,08-09 07:51:37.172   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-09 07:51:37.185   874  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-09 07:51:37.189   874  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-09 07:51:37.190   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-09 07:51:37.192   874  1310 D ConnectivityService: Adding iface wlan0 to network 102
,08-09 07:51:37.202   874  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-09 07:51:37.257   874  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-09 07:51:37.258   874  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-09 07:51:37.262   874  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-09 07:51:37.264   874  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-09 07:51:37.267   874  1310 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-09 07:51:37.282   874  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-09 07:51:37.296   874  1310 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-09 07:51:37.296   874  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
08-09 07:51:37.297   874  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-09 07:51:37.297   874  1310 D ConnectivityService:    accepting network in place of null
08-09 07:51:37.297   874  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-09 07:51:37.298   874  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -36]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-09 07:51:37.299   874  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-09 07:51:37.309   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=146185, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 07:51:37.347   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 07:51:37.377   874  4327 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.85,2a00:1450:400d:807::200e
,08-09 07:51:37.379   372   872 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-09 07:51:37.382   874  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true,
08-09 07:51:37.382   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-09 07:51:37.384   874  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-09 07:51:37.385  3662  3713 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 420)
08-09 07:51:37.385  3662  3713 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 420)
,08-09 07:51:37.386   874   891 D Tethering: MasterInitialState.processMessage what=3
,08-09 07:51:37.406  3662  3713 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 425)
,08-09 07:51:37.407  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-09 07:51:37.407  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:37.407  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:37.407  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:51:37.407  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 07:51:37.407  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 07:51:37.407  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 07:51:37.407  3662  3662 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 07:51:37.407  3662  3713 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-09 07:51:37.407  3662  3713 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 426)
08-09 07:51:37.409  3662  3662 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 07:51:37.409  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-09 07:51:37.409  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b967d9 added. We now have 2 listener(s)
08-09 07:51:37.411  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-09 07:51:37.411  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 07:51:37.411  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 07:51:37.411  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-09 07:51:37.411  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46b859e added. We now have 9 listener(s)
08-09 07:51:37.411  3662  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 07:51:37.411  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 07:51:37.412  1907  1907 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-09 07:51:37.413  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 07:51:37.417  3662  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 07:51:37.417  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:37.417  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:37.417  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:51:37.417  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 07:51:37.417  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 07:51:37.417  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 07:51:37.417  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 07:51:37.418  3662  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-09 07:51:37.418  3662  3713 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-09 07:51:37.418  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 07:51:37.419  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c52f04c added. We now have 3 listener(s)
,08-09 07:51:37.420  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-09 07:51:37.420  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-09 07:51:37.420  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 07:51:37.420  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-09 07:51:37.421  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-09 07:51:37.421  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4fa895 added. We now have 10 listener(s)
,08-09 07:51:37.421  3662  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 07:51:37.421  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 07:51:37.421  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-09 07:51:37.421  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 07:51:37.421  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-09 07:51:37.421  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 07:51:37.421  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 07:51:37.421  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-09 07:51:37.421  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b967d9 removed from the list
08-09 07:51:37.421  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:37.422  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46b859e removed from the list
,08-09 07:51:37.422  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:37.422  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
,08-09 07:51:37.422  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:37.423  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 07:51:37.423  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 07:51:37.423   874  4327 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 09 Aug 2016 05:51:37 GMT], X-Android-Received-Millis=[1470721897422], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470721897415]}
08-09 07:51:37.423  1907  1907 D SystemUpdateService: onCreate
,08-09 07:51:37.423   874  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-09 07:51:37.423   874  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-09 07:51:37.423  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-09 07:51:37.423  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-09 07:51:37.424  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:37.424   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-09 07:51:37.424  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46b859e not in the list
,08-09 07:51:37.424  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:37.424  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:37.424   874  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-09 07:51:37.425  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:37.426  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-09 07:51:37.426  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:37.426  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4fa895 removed from the list
08-09 07:51:37.426  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:37.426  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:37.426  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 07:51:37.426  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 07:51:37.426  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c52f04c removed from the list
08-09 07:51:37.427  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 07:51:37.427  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e865daa added. We now have 2 listener(s)
08-09 07:51:37.428  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-09 07:51:37.428  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-09 07:51:37.428  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 07:51:37.429  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 07:51:37.429  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3bdd9b added. We now have 9 listener(s)
08-09 07:51:37.429  3662  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 07:51:37.429  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 07:51:37.429  1907  1907 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-09 07:51:37.431  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 07:51:37.434  3662  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 07:51:37.434  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:37.434  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:37.434  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:51:37.434  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 07:51:37.434  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 07:51:37.434  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 07:51:37.434  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 07:51:37.435  3662  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 07:51:37.436  3662  3713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 07:51:37.436  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-09 07:51:37.436  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cf3911 added. We now have 3 listener(s)
08-09 07:51:37.437  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:37.438  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-09 07:51:37.438  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 07:51:37.438  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 07:51:37.438  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-09 07:51:37.438  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c4aa76 added. We now have 10 listener(s)
08-09 07:51:37.438  3662  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 07:51:37.438  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-09 07:51:37.438  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:37.438  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 07:51:37.440  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 07:51:37.440  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 07:51:37.440  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 07:51:37.443  3662  3713 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-09 07:51:37.443  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-09 07:51:37.448  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-09 07:51:37.448  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-09 07:51:37.449  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-09 07:51:37.451  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-09 07:51:37.451  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-09 07:51:37.451  3662  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-09 07:51:37.452  3662  3713 D BluetoothAdapter: STATE_ON
,08-09 07:51:37.454  4269  4279 D BtGatt.GattService: registerClient() - UUID=d78e89c6-d067-4bdb-b3f8-c71cdddd813e
,08-09 07:51:37.455  4269  4285 D BtGatt.GattService: onClientRegistered() - UUID=d78e89c6-d067-4bdb-b3f8-c71cdddd813e, clientIf=5
08-09 07:51:37.455  3662  3673 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-09 07:51:37.456  4269  4310 D BtGatt.GattService: start scan with filters
,08-09 07:51:37.458  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-09 07:51:37.458  4269  4288 D BtGatt.ScanManager: handling starting scan
08-09 07:51:37.458  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-09 07:51:37.458  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-09 07:51:37.459  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-09 07:51:37.459  1907  1907 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-09 07:51:37.460  4269  4288 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2f3976c
,08-09 07:51:37.461  4269  4285 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-09 07:51:37.461  4269  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:37.461  4269  4288 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-09 07:51:37.461  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-09 07:51:37.462  3662  3662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-09 07:51:37.462  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-09 07:51:37.463  4269  4285 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-09 07:51:37.463  4269  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:37.463  4269  4288 D BtGatt.ScanManager: Starting BLE batch scan
08-09 07:51:37.463  4269  4288 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-09 07:51:37.463  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-09 07:51:37.465  4269  4285 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-09 07:51:37.465  4269  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-09 07:51:37.465  1907  2411 I iu.UploadsManager: num queued entries: 0
08-09 07:51:37.465  3662  3713 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-09 07:51:37.465  1907  2411 I iu.UploadsManager: num updated entries: 0
08-09 07:51:37.466  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:37.466  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-09 07:51:37.466  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:37.466  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 07:51:37.466  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-09 07:51:37.466  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-09 07:51:37.466  4269  4285 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-09 07:51:37.466  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-09 07:51:37.466  4269  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:37.466  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-09 07:51:37.466  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-09 07:51:37.466  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-09 07:51:37.467  3662  3713 D BluetoothAdapter: STATE_ON
08-09 07:51:37.467  4269  4298 D BtGatt.GattService: stopScan() - queue size =1
,08-09 07:51:37.468  4269  4280 D BtGatt.GattService: unregisterClient() - clientIf=5
08-09 07:51:37.468  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-09 07:51:37.468  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-09 07:51:37.468  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-09 07:51:37.468  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-09 07:51:37.468  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-09 07:51:37.469  4269  4285 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-09 07:51:37.469  4269  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:37.469  4269  4288 D BtGatt.ScanManager: stopping BLe Batch
,08-09 07:51:37.469  1907  4341 I SystemUpdateService: active receiver: enabled
,08-09 07:51:37.471  4269  4285 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-09 07:51:37.471  4269  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:37.471  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 07:51:37.471  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-09 07:51:37.472  4269  4288 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-09 07:51:37.472  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-09 07:51:37.472  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 07:51:37.472  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 07:51:37.472  4269  4285 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-09 07:51:37.472  4269  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-09 07:51:37.473  3662  3662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 07:51:37.473  3662  3662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 07:51:37.473  3662  3662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-09 07:51:37.475  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 07:51:37.475  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:37.475  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-09 07:51:37.475  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:37.475  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:37.475  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 07:51:37.475  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 07:51:37.475  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e865daa removed from the list
,08-09 07:51:37.475  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:37.475  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3bdd9b removed from the list
08-09 07:51:37.475  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:37.476  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:37.477  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:37.477  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:37.478  1907  1907 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-09 07:51:37.478  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:37.478  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:37.478  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:37.478  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3bdd9b not in the list
08-09 07:51:37.478  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:37.478  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:37.479  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:37.479  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:37.479  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:37.479  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c4aa76 removed from the list
08-09 07:51:37.479  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:37.479  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:37.479  1907  1907 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-09 07:51:37.479  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:37.479  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 07:51:37.479  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cf3911 removed from the list
08-09 07:51:37.480  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 07:51:37.480  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f802 added. We now have 2 listener(s)
08-09 07:51:37.481  3968  3968 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-09 07:51:37.481  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-09 07:51:37.481  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 07:51:37.481  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 07:51:37.482  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 07:51:37.482  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ae6513 added. We now have 9 listener(s)
08-09 07:51:37.482  3662  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 07:51:37.482  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 07:51:37.484  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 07:51:37.487  3662  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 07:51:37.487  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:37.487  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:37.487  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:51:37.487  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 07:51:37.487  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 07:51:37.487  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 07:51:37.487  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 07:51:37.487  3968  3968 D SprintDMHelper: simOperator: 
08-09 07:51:37.487  3968  3968 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-09 07:51:37.488  3662  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 07:51:37.489  3662  3713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 07:51:37.489  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 07:51:37.489  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@136f949 added. We now have 3 listener(s)
08-09 07:51:37.490  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:37.490  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-09 07:51:37.490  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 07:51:37.490  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 07:51:37.490  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 07:51:37.491  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd2924e added. We now have 10 listener(s)
08-09 07:51:37.491  3662  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 07:51:37.491  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 07:51:37.491  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 07:51:37.491  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 07:51:37.491  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 07:51:37.492  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 07:51:37.492  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 07:51:37.492  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:37.493  3662  3713 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-09 07:51:37.494  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-09 07:51:37.497  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-09 07:51:37.497  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-09 07:51:37.497  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-09 07:51:37.500  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-09 07:51:37.500  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-09 07:51:37.500  3662  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-09 07:51:37.501  3662  3713 D BluetoothAdapter: STATE_ON
08-09 07:51:37.502  4269  4280 D BtGatt.GattService: registerClient() - UUID=18ed3c79-8537-4eba-9b2d-3effcfecfbb9
08-09 07:51:37.502  4269  4285 D BtGatt.GattService: onClientRegistered() - UUID=18ed3c79-8537-4eba-9b2d-3effcfecfbb9, clientIf=5
08-09 07:51:37.503  3662  3673 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-09 07:51:37.503  4269  4310 D BtGatt.GattService: start scan with filters
08-09 07:51:37.505  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-09 07:51:37.505  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-09 07:51:37.505  4269  4288 D BtGatt.ScanManager: handling starting scan
08-09 07:51:37.505  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-09 07:51:37.505  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-09 07:51:37.506  1907  4344 I MDM     : [228] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-09 07:51:37.507  4269  4285 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-09 07:51:37.507  4269  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:37.507  1907  4344 W BaseAppContext: Using Auth Proxy for data requests.
08-09 07:51:37.507  4269  4288 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-09 07:51:37.508  1907  4344 V GoogleAuthProtoRequest: [228] a.<init>: mAccountName set to: thalitester@gmail.com
08-09 07:51:37.509  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-09 07:51:37.509  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-09 07:51:37.509  4269  4285 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-09 07:51:37.509  3662  3662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-09 07:51:37.509  4269  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:37.510  4269  4288 D BtGatt.ScanManager: Starting BLE batch scan
08-09 07:51:37.510  4269  4288 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-09 07:51:37.510  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-09 07:51:37.511  4269  4285 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-09 07:51:37.511  4269  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:37.512  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 07:51:37.512  3662  3713 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-09 07:51:37.512  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 07:51:37.512  4269  4285 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-09 07:51:37.513  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:37.513  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 07:51:37.513  4269  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:37.513  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:37.513  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:37.513  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-09 07:51:37.513  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 07:51:37.513  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c8f802 removed from the list
08-09 07:51:37.513  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:37.513  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ae6513 removed from the list
08-09 07:51:37.513  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:37.513  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 07:51:37.514  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:37.514  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-09 07:51:37.514  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:37.514  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 07:51:37.515  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:37.515  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:37.515  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:37.515  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9ae6513 not in the list
08-09 07:51:37.515  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-09 07:51:37.515  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-09 07:51:37.515  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-09 07:51:37.515  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-09 07:51:37.515  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-09 07:51:37.516  3662  3713 D BluetoothAdapter: STATE_ON
08-09 07:51:37.516  4269  4279 D BtGatt.GattService: stopScan() - queue size =1
08-09 07:51:37.517  4269  4298 D BtGatt.GattService: unregisterClient() - clientIf=5
08-09 07:51:37.517  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 07:51:37.517  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-09 07:51:37.517  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-09 07:51:37.517  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-09 07:51:37.517  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-09 07:51:37.518  4269  4285 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-09 07:51:37.518  4269  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:37.518  4269  4288 D BtGatt.ScanManager: stopping BLe Batch
08-09 07:51:37.518  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 07:51:37.519  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-09 07:51:37.519  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-09 07:51:37.519  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 07:51:37.519  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:37.520  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:37.520  3662  3662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 07:51:37.520  4269  4285 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-09 07:51:37.520  3662  3662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 07:51:37.520  4269  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:37.520  3662  3662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 07:51:37.520  4269  4288 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-09 07:51:37.520  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:37.520  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:37.520  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd2924e removed from the list
08-09 07:51:37.520  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:37.520  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:37.521  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:37.521  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 07:51:37.521  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@136f949 removed from the list
08-09 07:51:37.521  4269  4285 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-09 07:51:37.521  4269  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:37.521  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 07:51:37.521  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c9855a added. We now have 2 listener(s)
08-09 07:51:37.523  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-09 07:51:37.523  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 07:51:37.523  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 07:51:37.523  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 07:51:37.523  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50b638b added. We now have 9 listener(s)
08-09 07:51:37.523  3662  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 07:51:37.524  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 07:51:37.526  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 07:51:37.532  1907  4341 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-09 07:51:37.532  3662  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 07:51:37.532  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:37.532  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:37.532  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:51:37.532  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 07:51:37.532  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 07:51:37.532  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 07:51:37.532  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-09 07:51:37.532  1907  2411 I iu.SyncManager: NEXT; no task
08-09 07:51:37.535  3662  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 07:51:37.535  3662  3713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 07:51:37.535  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 07:51:37.535  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35f8881 added. We now have 3 listener(s)
08-09 07:51:37.538  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:37.538  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-09 07:51:37.538  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 07:51:37.538  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 07:51:37.539  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 07:51:37.539  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9d26 added. We now have 10 listener(s)
08-09 07:51:37.539  3662  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 07:51:37.539  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 07:51:37.539  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-09 07:51:37.539  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-09 07:51:37.539  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-09 07:51:37.539  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-09 07:51:37.540  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:37.542  1907  4341 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
08-09 07:51:37.543  3662  3713 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-09 07:51:37.543  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-09 07:51:37.547  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-09 07:51:37.547  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-09 07:51:37.547  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-09 07:51:37.547  1907  4341 I SystemUpdateService: now status is 0 (complete)
08-09 07:51:37.547  1907  4341 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-09 07:51:37.548  1907  4341 I SystemUpdateService: file has been verified
08-09 07:51:37.549  1907  4341 I SystemUpdateService: OTA package size = 12249756
08-09 07:51:37.550  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-09 07:51:37.550  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-09 07:51:37.550  3662  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-09 07:51:37.551  3662  3713 D BluetoothAdapter: STATE_ON
08-09 07:51:37.552  4269  4279 D BtGatt.GattService: registerClient() - UUID=2dbd033f-7dd5-497c-862a-dd5940261b4a
08-09 07:51:37.552  4269  4285 D BtGatt.GattService: onClientRegistered() - UUID=2dbd033f-7dd5-497c-862a-dd5940261b4a, clientIf=5
08-09 07:51:37.553  3662  3673 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-09 07:51:37.553  4269  4298 D BtGatt.GattService: start scan with filters
08-09 07:51:37.553  1515  2416 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-09 07:51:37.553  1515  2416 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-09 07:51:37.555  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-09 07:51:37.556  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-09 07:51:37.556  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-09 07:51:37.556  4269  4288 D BtGatt.ScanManager: handling starting scan
08-09 07:51:37.556  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-09 07:51:37.554  1515  2416 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 07:51:37.556  1515  2416 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:51:37.558  4269  4285 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-09 07:51:37.558  4269  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-09 07:51:37.558  4269  4288 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-09 07:51:37.559  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-09 07:51:37.559  3662  3662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-09 07:51:37.559  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-09 07:51:37.559  4269  4285 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-09 07:51:37.559  4269  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:37.560  4269  4288 D BtGatt.ScanManager: Starting BLE batch scan
08-09 07:51:37.560  4269  4288 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-09 07:51:37.560  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-09 07:51:37.561  4269  4285 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-09 07:51:37.561  4269  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-09 07:51:37.562  4269  4285 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-09 07:51:37.562  4269  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-09 07:51:37.564  1907  4341 I SystemUpdateService: showing system update notification
08-09 07:51:37.565  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-09 07:51:37.565  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:37.565  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 07:51:37.565  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-09 07:51:37.566  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:37.566  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-09 07:51:37.566  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 07:51:37.566  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c9855a removed from the list
08-09 07:51:37.566  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:37.566  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50b638b removed from the list
08-09 07:51:37.566  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
,08-09 07:51:37.566  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 07:51:37.566  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:37.567  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-09 07:51:37.567  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 07:51:37.567  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-09 07:51:37.567  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:37.567  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:37.568  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:37.568  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50b638b not in the list
,08-09 07:51:37.568  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-09 07:51:37.568  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-09 07:51:37.568  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-09 07:51:37.568  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-09 07:51:37.568  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-09 07:51:37.569  3662  3713 D BluetoothAdapter: STATE_ON
08-09 07:51:37.570  4269  4279 D BtGatt.GattService: stopScan() - queue size =1
08-09 07:51:37.570  4269  4310 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-09 07:51:37.570  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-09 07:51:37.570  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-09 07:51:37.571  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-09 07:51:37.571  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-09 07:51:37.571  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-09 07:51:37.571  4269  4285 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-09 07:51:37.571  4269  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:37.571  4269  4288 D BtGatt.ScanManager: stopping BLe Batch
08-09 07:51:37.571  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-09 07:51:37.572  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-09 07:51:37.572  3662  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-09 07:51:37.572  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-09 07:51:37.572  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 07:51:37.573  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:37.573  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-09 07:51:37.573  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:37.573  3662  3662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 07:51:37.573  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a9d26 removed from the list
08-09 07:51:37.573  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:37.573  3662  3662 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-09 07:51:37.573  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:37.573  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-09 07:51:37.573  3662  3662 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-09 07:51:37.573  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 07:51:37.573  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@35f8881 removed from the list
08-09 07:51:37.574  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 07:51:37.574  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@df365b2 added. We now have 2 listener(s)
,08-09 07:51:37.574  4269  4285 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-09 07:51:37.574  4269  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:37.574  4269  4288 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-09 07:51:37.575  1907  4344 E MDM     : [228] SitrepService.a: Error sending sitrep.
,08-09 07:51:37.575  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-09 07:51:37.575  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-09 07:51:37.575  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 07:51:37.575  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 07:51:37.575  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34ab903 added. We now have 9 listener(s)
08-09 07:51:37.575  3662  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-09 07:51:37.575  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-09 07:51:37.576  4269  4285 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-09 07:51:37.576  4269  4285 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-09 07:51:37.577  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-09 07:51:37.580  3662  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-09 07:51:37.580  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-09 07:51:37.580  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-09 07:51:37.580  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-09 07:51:37.580  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-09 07:51:37.580  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-09 07:51:37.580  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-09 07:51:37.580  3662  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-09 07:51:37.582  3662  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-09 07:51:37.582  3662  3713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-09 07:51:37.582  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-09 07:51:37.582  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab3c6b9 added. We now have 3 listener(s)
,08-09 07:51:37.583  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-09 07:51:37.583  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-09 07:51:37.583  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-09 07:51:37.583  3903  4346 I Babel   : connection state changed from DISCONNECTED to CONNECTED
08-09 07:51:37.583  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-09 07:51:37.583  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12e2afe added. We now have 10 listener(s)
08-09 07:51:37.583  3662  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-09 07:51:37.584  3662  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-09 07:51:37.584  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-09 07:51:37.584  3662  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-09 07:51:37.584  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:37.584  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:37.584  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-09 07:51:37.584  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 07:51:37.584  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@df365b2 removed from the list
08-09 07:51:37.584  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:37.584  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34ab903 removed from the list
,08-09 07:51:37.584  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:37.584  3662  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-09 07:51:37.584  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:37.585  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-09 07:51:37.585  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:37.585  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:37.585  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:37.585  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-09 07:51:37.585  3662  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34ab903 not in the list
08-09 07:51:37.585  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:37.585  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:37.586  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-09 07:51:37.586  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-09 07:51:37.586  3662  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-09 07:51:37.586  3662  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12e2afe removed from the list
,08-09 07:51:37.586  3662  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-09 07:51:37.586  3662  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-09 07:51:37.586  3662  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-09 07:51:37.586  3662  3662 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-09 07:51:37.586  3662  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-09 07:51:37.586  3662  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab3c6b9 removed from the list
,08-09 07:51:37.587  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-09 07:51:37.587  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-09 07:51:37.587  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-09 07:51:37.587  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 07:51:37.587  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-09 07:51:37.587  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-09 07:51:37.591  3662  4353 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 433, name: My test thread name)
08-09 07:51:37.591  3662  4353 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 433, thread name: My test thread name)
08-09 07:51:37.591  3662  4353 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 433, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-09 07:51:37.592  3662  4354 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 435, name: My test thread name)
,08-09 07:51:37.592  3662  4354 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 435, thread name: My test thread name)
08-09 07:51:37.593  3662  4354 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 435, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-09 07:51:37.593  1907  1907 D SystemUpdateService: onDestroy
08-09 07:51:37.594  3662  3713 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-09 07:51:37.594  3662  3713 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-09 07:51:37.594  3662  3713 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-09 07:51:37.594  3662  3713 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-09 07:51:37.594  3662  3713 D com.test.thalitest.ThaliTestRunner: Total duration: 22711 ms
,08-09 07:51:37.595  3662  3713 I jxcore-log: Total number of executed tests:  80
08-09 07:51:37.595  3662  3713 I jxcore-log: 
08-09 07:51:37.595  3662  3713 I jxcore-log: Number of passed tests:  80
08-09 07:51:37.595  3662  3713 I jxcore-log: 
,08-09 07:51:37.596  3662  3713 I jxcore-log: Number of failed tests:  0
08-09 07:51:37.596  3662  3713 I jxcore-log: 
08-09 07:51:37.596  3662  3713 I jxcore-log: Number of ignored tests:  0
08-09 07:51:37.596  3662  3713 I jxcore-log: 
,08-09 07:51:37.596  3662  3713 I jxcore-log: Total duration:  22711
08-09 07:51:37.596  3662  3713 I jxcore-log: 
,08-09 07:51:37.599  3662  3713 I jxcore-log: Unit Test app is loaded
08-09 07:51:37.599  3662  3713 I jxcore-log: 
,08-09 07:51:37.604  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"00:1f:27:54:70:c0"}
08-09 07:51:37.604  3662  3713 I jxcore-log: 
,08-09 07:51:37.608  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"00:1f:27:54:70:c0"}
08-09 07:51:37.608  3662  3713 I jxcore-log: 
,08-09 07:51:37.608  3662  3662 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-09 07:51:37.609  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"00:1f:27:54:70:c0"}
08-09 07:51:37.609  3662  3713 I jxcore-log: 
,08-09 07:51:37.609  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"00:1f:27:54:70:c0"}
08-09 07:51:37.609  3662  3713 I jxcore-log: 
,08-09 07:51:37.610  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"00:1f:27:54:70:c0"}
08-09 07:51:37.610  3662  3713 I jxcore-log: 
08-09 07:51:37.611  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"00:1f:27:54:70:c0"}
08-09 07:51:37.611  3662  3713 I jxcore-log: 
,08-09 07:51:37.613  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-09 07:51:37.613  3662  3713 I jxcore-log: 
,08-09 07:51:37.615  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-09 07:51:37.615  3662  3713 I jxcore-log: 
,08-09 07:51:37.616  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 07:51:37.616  3662  3713 I jxcore-log: 
08-09 07:51:37.616  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 07:51:37.616  3662  3713 I jxcore-log: 
08-09 07:51:37.617  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-09 07:51:37.617  3662  3713 I jxcore-log: 
,08-09 07:51:37.618  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-09 07:51:37.618  3662  3713 I jxcore-log: 
,08-09 07:51:37.619  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-09 07:51:37.619  3662  3713 I jxcore-log: 
08-09 07:51:37.620  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 07:51:37.620  3662  3713 I jxcore-log: 
08-09 07:51:37.620  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 07:51:37.620  3662  3713 I jxcore-log: 
08-09 07:51:37.621  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 07:51:37.621  3662  3713 I jxcore-log: 
08-09 07:51:37.622  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 07:51:37.622  3662  3713 I jxcore-log: 
08-09 07:51:37.622  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 07:51:37.622  3662  3713 I jxcore-log: 
,08-09 07:51:37.623  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 07:51:37.623  3662  3713 I jxcore-log: 
,08-09 07:51:37.624  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 07:51:37.624  3662  3713 I jxcore-log: 
08-09 07:51:37.624  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-09 07:51:37.624  3662  3713 I jxcore-log: 
08-09 07:51:37.625  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 07:51:37.625  3662  3713 I jxcore-log: 
08-09 07:51:37.625  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-09 07:51:37.625  3662  3713 I jxcore-log: 
08-09 07:51:37.626  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-09 07:51:37.626  3662  3713 I jxcore-log: 
,08-09 07:51:37.626  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-09 07:51:37.626  3662  3713 I jxcore-log: 
,08-09 07:51:37.628  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 07:51:37.628  3662  3713 I jxcore-log: 
,08-09 07:51:37.629  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 07:51:37.629  3662  3713 I jxcore-log: 
08-09 07:51:37.630  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 07:51:37.630  3662  3713 I jxcore-log: 
08-09 07:51:37.630  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 07:51:37.630  3662  3713 I jxcore-log: 
08-09 07:51:37.631  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 07:51:37.631  3662  3713 I jxcore-log: 
,08-09 07:51:37.632  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-09 07:51:37.632  3662  3713 I jxcore-log: 
,08-09 07:51:37.634  3662  3713 I jxcore-log: My device name is: motorola-Nexus 6
08-09 07:51:37.634  3662  3713 I jxcore-log: 
,08-09 07:51:37.749  1515  4351 I GCM     : Ack for not saved message 0
,08-09 07:51:37.974  3662  3662 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-09 07:51:38.021  3662  3662 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-09 07:51:38.074  3662  3662 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-09 07:51:38.383   874  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-09 07:51:39.935  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-09 07:51:39.935  3662  3713 I jxcore-log: 
,08-09 07:51:40.015   874  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-09 07:51:40.267   874  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 13 -> obsolete
,08-09 07:51:40.585  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-09 07:51:40.585  3662  3713 I jxcore-log: 
,08-09 07:51:40.610  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-09 07:51:40.610  3662  3713 I jxcore-log: 
,08-09 07:51:41.300   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-09 07:51:41.308  1659  1659 I Keyboard.Facilitator: onFinishInput()
,08-09 07:51:41.312   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-09 07:51:41.312   874   894 I Adreno  : Build Date                       : 10/20/15
08-09 07:51:41.312   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-09 07:51:41.312   874   894 I Adreno  : Local Branch                     : M14
08-09 07:51:41.312   874   894 I Adreno  : Remote Branch                    : 
08-09 07:51:41.312   874   894 I Adreno  : Remote Branch                    : 
08-09 07:51:41.312   874   894 I Adreno  : Reconstruct Branch               : 
,08-09 07:51:41.335   283  1299 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (272 us)
,08-09 07:51:41.912  3662  3662 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-09 07:51:41.913  3662  3662 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-09 07:51:41.951   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-09 07:51:41.953  3662  3662 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@538be58 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@35e25f, 16908290=android.view.AbsSavedState$1@35e25f}, android:focusedViewId=100}]}]
,08-09 07:51:41.953  3662  3662 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-09 07:51:41.954  3662  3662 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-09 07:51:41.954  3662  3662 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-09 07:51:41.956   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-09 07:51:41.962   283   283 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
,08-09 07:51:41.962   283   283 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-09 07:51:41.963   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-09 07:51:42.110  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-09 07:51:42.110  3662  3713 I jxcore-log: 
,08-09 07:51:42.186   283   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-09 07:51:42.188   283   283 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-09 07:51:42.191   874  1334 D SurfaceControl: Excessive delay in setPowerMode(): 229ms
,08-09 07:51:42.195   874   894 I DreamManagerService: Entering dreamland.
,08-09 07:51:42.196   874   894 I PowerManagerService: Dozing...
,08-09 07:51:42.196   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-09 07:51:42.261   376  1279 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-09 07:51:42.262   376  1279 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-09 07:51:42.272   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-09 07:51:42.283  1711  4360 D NfcService: Discovery configuration equal, not updating.
08-09 07:51:42.286   874  1308 E native  : do suspend false
,08-09 07:51:42.302   874  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-09 07:51:42.315   874  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-09 07:51:42.320   874  1308 E native  : do suspend true
,08-09 07:51:42.389  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-09 07:51:42.389  3662  3713 I jxcore-log: 
,08-09 07:51:42.393   376  3675 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-09 07:51:42.393   376  3675 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-09 07:51:42.394  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-09 07:51:42.394  3662  3713 I jxcore-log: 
,08-09 07:51:42.416  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-09 07:51:42.416  3662  3713 I jxcore-log: 
,08-09 07:51:42.421  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-09 07:51:42.421  3662  3713 I jxcore-log: 
,08-09 07:51:42.776   874  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,08-09 07:51:43.107  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-09 07:51:43.107  3662  3713 I jxcore-log: 
,08-09 07:51:43.119  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-09 07:51:43.119  3662  3713 I jxcore-log: 
,08-09 07:51:43.129  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-09 07:51:43.129  3662  3713 I jxcore-log: 
,08-09 07:51:43.136  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-09 07:51:43.136  3662  3713 I jxcore-log: 
,08-09 07:51:43.185  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-09 07:51:43.185  3662  3713 I jxcore-log: 
,08-09 07:51:43.240  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-09 07:51:43.240  3662  3713 I jxcore-log: 
,08-09 07:51:43.247  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-09 07:51:43.247  3662  3713 I jxcore-log: 
,08-09 07:51:43.412  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-09 07:51:43.412  3662  3713 I jxcore-log: 
,08-09 07:51:43.440  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-09 07:51:43.440  3662  3713 I jxcore-log: 
,08-09 07:51:43.446  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-09 07:51:43.446  3662  3713 I jxcore-log: 
,08-09 07:51:43.452  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js,
08-09 07:51:43.452  3662  3713 I jxcore-log: ,
,08-09 07:51:43.471  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js,
08-09 07:51:43.471  3662  3713 I jxcore-log: ,
,08-09 07:51:43.556  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js,
08-09 07:51:43.556  3662  3713 I jxcore-log: 
,08-09 07:51:43.568  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js,
08-09 07:51:43.568  3662  3713 I jxcore-log: 
,08-09 07:51:43.596  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js,
08-09 07:51:43.596  3662  3713 I jxcore-log: 
,08-09 07:51:43.608  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
,08-09 07:51:43.608  3662  3713 I jxcore-log: 
,08-09 07:51:43.627  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-09 07:51:43.627  3662  3713 I jxcore-log: 
,08-09 07:51:43.664  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-09 07:51:43.664  3662  3713 I jxcore-log: 
,08-09 07:51:43.670  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-09 07:51:43.670  3662  3713 I jxcore-log: 
,08-09 07:51:43.892  3662  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-09 07:51:43.892  3662  3713 I jxcore-log: 
,08-09 07:51:43.902  3662  3713 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-09 07:51:43.903  3662  3713 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-09 07:51:43.903  3662  3713 I jxcore-log: 
,08-09 07:51:43.947  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-09 07:51:43.947  3662  3713 I jxcore-log: 
,08-09 07:51:43.947  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-09 07:51:43.947  3662  3713 I jxcore-log: 
,08-09 07:51:43.948  3662  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-09 07:51:43.948  3662  3713 I jxcore-log: 
08-09 07:51:43.948  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-09 07:51:43.948  3662  3713 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,08-09 07:51:43.949  3662  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-09 07:51:43.949  3662  3713 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,08-09 07:51:45.301   874  1310 D ConnectivityService: handlePromptUnvalidated 102
,08-09 07:51:47.690  1890  2328 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-09 07:51:51.468   874  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 16 -> obsolete
,08-09 07:51:56.071   874  1385 I ActivityManager: Start proc 4366:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-09 07:51:56.083  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:51:56.085  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:51:56.095  3735  4365 V GoogleAuthProtoRequest: [323] a.<init>: mAccountName set to: thalitester@gmail.com
,08-09 07:51:56.114  4366  4366 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-09 07:51:56.142  1515  2416 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-09 07:51:56.151  1515  2416 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-09 07:51:56.151  1515  2416 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:51:56.151  1515  2416 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:51:56.185  4366  4378 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-09 07:51:56.257  3735  4365 W ExperimentUpdateService: [323] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-09 07:51:56.257  3735  4365 W ExperimentUpdateService: [323] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-09 07:51:56.257  3735  4365 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-09 07:51:56.257  3735  4365 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-09 07:51:56.257  3735  4365 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-09 07:51:56.257  3735  4365 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-09 07:51:56.257  3735  4365 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-09 07:51:56.257  3735  4365 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-09 07:51:56.257  3735  4365 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-09 07:51:56.257  3735  4365 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-09 07:51:56.257  3735  4365 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-09 07:51:56.257  3735  4365 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-09 07:51:56.402  4366  4378 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-09 07:51:56.428  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:51:56.480  4366  4378 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-09 07:51:56.481  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-09 07:51:56.481  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-09 07:51:56.482  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:51:56.482  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:51:56.516  4227  4227 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-09 07:51:56.517  4227  4227 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-09 07:51:56.517  4227  4227 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-09 07:51:56.521  4366  4366 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-09 07:51:56.770  4366  4366 W InstanceID/Rpc: Found 10011
,08-09 07:51:56.911  4406  4406 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads570984464.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads570984464.dex
,08-09 07:51:56.916  1515  1997 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-09 07:51:56.987  4406  4406 I dex2oat : dex2oat took 76.065ms (threads: 4) arena alloc=271KB java alloc=33KB native alloc=1515KB free=1556KB
,08-09 07:51:57.030   874  1738 I ActivityManager: Killing 4176:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-09 07:51:57.260   874  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 13, 16 -> obsolete
,08-09 07:52:07.740  3932  4449 V KeepSync: Connecting to GoogleApiClient
,08-09 07:52:07.741   874  1769 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-09 07:52:07.769  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:52:07.771  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:52:07.825  1515  2416 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-09 07:52:07.825  1515  2416 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-09 07:52:07.825  1515  2416 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:52:07.825  1515  2416 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:52:07.850  2513  4450 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-09 07:52:07.850  2513  4450 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-09 07:52:07.850  2513  4450 E HttpOperation: 	at jdm.a(PG:82)
08-09 07:52:07.850  2513  4450 E HttpOperation: 	at jcs.o(PG:406)
08-09 07:52:07.850  2513  4450 E HttpOperation: 	at jcn.a(PG:1379)
08-09 07:52:07.850  2513  4450 E HttpOperation: 	at jcs.i(PG:143)
08-09 07:52:07.850  2513  4450 E HttpOperation: 	at blb.a(PG:3937)
08-09 07:52:07.850  2513  4450 E HttpOperation: 	at czp.a(PG:18188)
08-09 07:52:07.850  2513  4450 E HttpOperation: 	at czp.a(PG:9081)
08-09 07:52:07.850  2513  4450 E HttpOperation: 	at czq.run(PG:1686)
08-09 07:52:07.850  2513  4450 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 07:52:07.850  2513  4450 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 07:52:07.850  2513  4450 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 07:52:07.850  2513  4450 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 07:52:07.850  2513  4450 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:52:07.850  2513  4450 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 07:52:07.850  2513  4450 E HttpOperation: 	at jdj.a(PG:4091)
08-09 07:52:07.850  2513  4450 E HttpOperation: 	at jdj.a(PG:1125)
08-09 07:52:07.850  2513  4450 E HttpOperation: 	at jdm.a(PG:77)
08-09 07:52:07.850  2513  4450 E HttpOperation: 	... 12 more
08-09 07:52:07.850  2513  4450 E HttpOperation: Caused by: faj: BadAuthentication
08-09 07:52:07.850  2513  4450 E HttpOperation: 	at fal.a(PG:38)
08-09 07:52:07.850  2513  4450 E HttpOperation: 	at jdj.a(PG:4089)
08-09 07:52:07.850  2513  4450 E HttpOperation: 	... 14 more
,08-09 07:52:07.881  1515  2067 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-09 07:52:07.881  1515  2067 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-09 07:52:07.881  1515  2067 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 07:52:07.881  1515  2067 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:52:07.931  1907  4451 V BaseAuthAsyncOperation: access token request failed
,08-09 07:52:07.932  3932  4449 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-09 07:52:08.001  1515  2416 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-09 07:52:08.001  1515  2416 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-09 07:52:08.002  1515  2416 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 07:52:08.002  1515  2416 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:52:08.021  2513  4450 E HttpOperation: [getmobileexperiments] Unexpected exception
08-09 07:52:08.021  2513  4450 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-09 07:52:08.021  2513  4450 E HttpOperation: 	at jdm.a(PG:82)
08-09 07:52:08.021  2513  4450 E HttpOperation: 	at jcs.o(PG:406)
08-09 07:52:08.021  2513  4450 E HttpOperation: 	at jcn.a(PG:1379)
08-09 07:52:08.021  2513  4450 E HttpOperation: 	at jcs.i(PG:143)
08-09 07:52:08.021  2513  4450 E HttpOperation: 	at hec.a(PG:42)
08-09 07:52:08.021  2513  4450 E HttpOperation: 	at hee.a(PG:102)
08-09 07:52:08.021  2513  4450 E HttpOperation: 	at czr.a(PG:65)
08-09 07:52:08.021  2513  4450 E HttpOperation: 	at kka.a(PG:108)
08-09 07:52:08.021  2513  4450 E HttpOperation: 	at czp.a(PG:19176)
08-09 07:52:08.021  2513  4450 E HttpOperation: 	at czp.a(PG:9081)
08-09 07:52:08.021  2513  4450 E HttpOperation: ,	at czq.run(PG:1686)
08-09 07:52:08.021  2513  4450 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 07:52:08.021  2513  4450 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 07:52:08.021  2513  4450 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 07:52:08.021  2513  4450 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 07:52:08.021  2513  4450 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:52:08.021  2513  4450 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 07:52:08.021  2513  4450 E HttpOperation: 	at jdj.a(PG:4091)
08-09 07:52:08.021  2513  4450 E HttpOperation: 	at jdj.a(PG:1125)
08-09 07:52:08.021  2513  4450 E HttpOperation: 	at jdm.a(PG:77)
08-09 07:52:08.021  2513  4450 E HttpOperation: 	... 15 more
08-09 07:52:08.021  2513  4450 E HttpOperation: Caused by: faj: BadAuthentication
08-09 07:52:08.021  2513  4450 E HttpOperation: 	at fal.a(PG:38)
08-09 07:52:08.021  2513  4450 E HttpOperation: 	at jdj.a(PG:4089)
08-09 07:52:08.021  2513  4450 E HttpOperation: 	... 17 more
,08-09 07:52:08.022  2513  4450 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-09 07:52:08.022  2513  4450 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	at jdm.a(PG:82)
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	at jcs.o(PG:406)
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	at jcn.a(PG:1379)
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	at jcs.i(PG:143)
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	at hec.a(PG:42)
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	at hee.a(PG:102)
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	at czr.a(PG:65)
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	at kka.a(PG:108)
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	at czp.a(PG:19176)
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	at czp.a(PG:9081)
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	at czq.run(PG:1686)
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:52:08.022  2513  4450 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	at jdj.a(PG:4091)
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	at jdj.a(PG:1125)
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	at jdm.a(PG:77)
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	... 15 more
08-09 07:52:08.022  2513  4450 E ExperimentLoader: Caused by: faj: BadAuthentication
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	at fal.a(PG:38)
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	at jdj.a(PG:4089)
08-09 07:52:08.022  2513  4450 E ExperimentLoader: 	... 17 more
,08-09 07:52:08.082  1515  1958 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-09 07:52:08.083  1515  1958 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-09 07:52:08.083  1515  1958 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:52:08.083  1515  1958 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:52:08.103  3932  4449 E KeepSync: IOException
08-09 07:52:08.103  3932  4449 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-09 07:52:08.103  3932  4449 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-09 07:52:08.103  3932  4449 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-09 07:52:08.103  3932  4449 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-09 07:52:08.103  3932  4449 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-09 07:52:08.103  3932  4449 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-09 07:52:08.103  3932  4449 E KeepSync: 	,at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-09 07:52:08.103  3932  4449 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-09 07:52:08.103  3932  4449 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-09 07:52:08.103  3932  4449 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-09 07:52:08.103  3932  4449 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-09 07:52:08.103  3932  4449 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-09 07:52:08.103  3932  4449 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-09 07:52:08.103  3932  4449 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-09 07:52:08.103  3932  4449 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-09 07:52:08.103  3932  4449 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-09 07:52:08.103  3932  4449 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-09 07:52:08.103  3932  4449 E KeepSync: 	... 10 more
08-09 07:52:08.103  3932  4449 W KeepSync: Sync result 2
,08-09 07:52:08.112   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 161864, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-09 07:52:08.184   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 160685, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-09 07:52:16.726  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,08-09 07:52:16.740  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:52:16.743  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:52:16.790  1515  2067 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-09 07:52:16.790  1515  2067 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-09 07:52:16.791  1515  2067 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:52:16.791  1515  2067 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:52:16.843  4227  4227 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-09 07:52:16.844  4227  4227 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-09 07:52:16.845  4227  4227 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-09 07:52:27.226   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=196103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 07:52:33.347   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=202224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-09 07:52:37.158  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:52:37.166  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:52:37.168  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:52:37.214  1515  1958 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-09 07:52:37.214  1515  1958 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-09 07:52:37.215  1515  1958 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 07:52:37.215  1515  1958 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:52:37.264  4227  4227 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-09 07:52:37.265  4227  4227 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-09 07:52:37.267  4227  4227 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-09 07:52:39.361  3932  4457 V KeepSync: Connecting to GoogleApiClient
,08-09 07:52:39.361   874   885 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-09 07:52:39.400  1515  2067 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-09 07:52:39.400  1515  2067 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-09 07:52:39.400  1515  2067 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:52:39.401  1515  2067 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:52:39.441  2513  4456 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-09 07:52:39.441  2513  4456 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-09 07:52:39.441  2513  4456 E HttpOperation: 	at jdm.a(PG:82)
08-09 07:52:39.441  2513  4456 E HttpOperation: 	at jcs.o(PG:406)
08-09 07:52:39.441  2513  4456 E HttpOperation: 	at jcn.a(PG:1379)
08-09 07:52:39.441  2513  4456 E HttpOperation: 	at jcs.i(PG:143)
08-09 07:52:39.441  2513  4456 E HttpOperation: 	at blb.a(PG:3937)
08-09 07:52:39.441  2513  4456 E HttpOperation: 	at czp.a(PG:18188)
08-09 07:52:39.441  2513  4456 E HttpOperation: 	at czp.a(PG:9081)
08-09 07:52:39.441  2513  4456 E HttpOperation: 	at czq.run(PG:1686)
08-09 07:52:39.441  2513  4456 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 07:52:39.441  2513  4456 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 07:52:39.441  2513  4456 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 07:52:39.441  2513  4456 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 07:52:39.441  2513  4456 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:52:39.441  2513  4456 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 07:52:39.441  2513  4456 E HttpOperation: 	at jdj.a(PG:4091)
08-09 07:52:39.441  2513  4456 E HttpOperation: 	at jdj.a(PG:1125)
08-09 07:52:39.441  2513  4456 E HttpOperation: 	at jdm.a(PG:77)
08-09 07:52:39.441  2513  4456 E HttpOperation: 	... 12 more
08-09 07:52:39.441  2513  4456 E HttpOperation: Caused by: faj: BadAuthentication
08-09 07:52:39.441  2513  4456 E HttpOperation: 	at fal.a(PG:38)
08-09 07:52:39.441  2513  4456 E HttpOperation: 	at jdj.a(PG:4089)
08-09 07:52:39.441  2513  4456 E HttpOperation: 	... 14 more
,08-09 07:52:39.482  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-09 07:52:39.482  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-09 07:52:39.482  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:52:39.482  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:52:39.495  1515  2067 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-09 07:52:39.495  1515  2067 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-09 07:52:39.495  1515  2067 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:52:39.495  1515  2067 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:52:39.531  1907  4458 V BaseAuthAsyncOperation: access token request failed
,08-09 07:52:39.535  3932  4457 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-09 07:52:39.539  2513  4456 E HttpOperation: [getmobileexperiments] Unexpected exception
08-09 07:52:39.539  2513  4456 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-09 07:52:39.539  2513  4456 E HttpOperation: 	at jdm.a(PG:82)
08-09 07:52:39.539  2513  4456 E HttpOperation: 	at jcs.o(PG:406)
08-09 07:52:39.539  2513  4456 E HttpOperation: 	at jcn.a(PG:1379)
08-09 07:52:39.539  2513  4456 E HttpOperation: 	at jcs.i(PG:143)
08-09 07:52:39.539  2513  4456 E HttpOperation: 	at hec.a(PG:42)
08-09 07:52:39.539  2513  4456 E HttpOperation: 	at hee.a(PG:102)
08-09 07:52:39.539  2513  4456 E HttpOperation: 	at czr.a(PG:65)
08-09 07:52:39.539  2513  4456 E HttpOperation: 	at kka.a(PG:108)
08-09 07:52:39.539  2513  4456 E HttpOperation: 	at czp.a(PG:19176)
08-09 07:52:39.539  2513  4456 E HttpOperation: 	at czp.a(PG:9081)
08-09 07:52:39.539  2513  4456 E HttpOperation: 	at czq.run(PG:1686)
08-09 07:52:39.539  2513  4456 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 07:52:39.539  2513  4456 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 07:52:39.539  2513  4456 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 07:52:39.539  2513  4456 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 07:52:39.539  2513  4456 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:52:39.539  2513  4456 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 07:52:39.539  2513  4456 E HttpOperation: 	at jdj.a(PG:4091)
08-09 07:52:39.539  2513  4456 E HttpOperation: 	at jdj.a(PG:1125)
08-09 07:52:39.539  2513  4456 E HttpOperation: 	at jdm.a(PG:77)
08-09 07:52:39.539  2513  4456 E HttpOperation: 	... 15 more
08-09 07:52:39.539  2513  4456 E HttpOperation: Caused by: faj: BadAuthentication
08-09 07:52:39.539  2513  4456 E HttpOperation: 	at fal.a(PG:38)
08-09 07:52:39.539  2513  4456 E HttpOperation: 	at jdj.a(PG:4089)
08-09 07:52:39.539  2513  4456 E HttpOperation: 	... 17 more
08-09 07:52:39.539  2513  4456 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-09 07:52:39.539  2513  4456 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	at jdm.a(PG:82)
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	at jcs.o(PG:406)
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	at jcn.a(PG:1379)
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	at jcs.i(PG:143)
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	at hec.a(PG:42)
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	at hee.a(PG:102)
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	at czr.a(PG:65)
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	at kka.a(PG:108)
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	at czp.a(PG:19176)
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	at czp.a(PG:9081)
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	at czq.run(PG:1686)
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:52:39.539  2513  4456 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	at jdj.a(PG:4091)
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	at jdm.a(PG:77)
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	... 15 more
08-09 07:52:39.539  2513  4456 E ExperimentLoader: Caused by: faj: BadAuthentication
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	at fal.a(PG:38)
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	at jdj.a(PG:4089)
08-09 07:52:39.539  2513  4456 E ExperimentLoader: 	... 17 more
,08-09 07:52:39.667  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-09 07:52:39.667  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-09 07:52:39.667  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 07:52:39.667  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:52:39.690  3932  4457 E KeepSync: IOException
08-09 07:52:39.690  3932  4457 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-09 07:52:39.690  3932  4457 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-09 07:52:39.690  3932  4457 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-09 07:52:39.690  3932  4457 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-09 07:52:39.690  3932  4457 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-09 07:52:39.690  3932  4457 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-09 07:52:39.690  3932  4457 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-09 07:52:39.690  3932  4457 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-09 07:52:39.690  3932  4457 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-09 07:52:39.690  3932  4457 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-09 07:52:39.690  3932  4457 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-09 07:52:39.690  3932  4457 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-09 07:52:39.690  3932  4457 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-09 07:52:39.690  3932  4457 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-09 07:52:39.690  3932  4457 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-09 07:52:39.690  3932  4457 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-09 07:52:39.690  3932  4457 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-09 07:52:39.690  3932  4457 E KeepSync: 	... 10 more
08-09 07:52:39.690  3932  4457 W KeepSync: Sync result 2
,08-09 07:52:39.697   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 207995, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-09 07:52:39.711   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 208006, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-09 07:52:41.332  1659  1702 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-09 07:52:41.333  1659  1702 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-09 07:52:41.366  1515  1515 I ConfigService: onCreate
,08-09 07:52:46.437  1515  1515 I ConfigService: onDestroy
,08-09 07:52:57.471  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:52:57.473  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:52:57.485  3735  4462 V GoogleAuthProtoRequest: [324] a.<init>: mAccountName set to: thalitester@gmail.com
,08-09 07:52:57.575  1515  1958 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-09 07:52:57.575  1515  1958 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-09 07:52:57.575  1515  1958 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:52:57.575  1515  1958 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:52:57.597  3735  4462 W ExperimentUpdateService: [324] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-09 07:52:57.598  3735  4462 W ExperimentUpdateService: [324] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-09 07:52:57.598  3735  4462 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-09 07:52:57.598  3735  4462 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-09 07:52:57.598  3735  4462 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-09 07:52:57.598  3735  4462 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-09 07:52:57.598  3735  4462 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-09 07:52:57.598  3735  4462 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-09 07:52:57.598  3735  4462 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-09 07:52:57.598  3735  4462 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-09 07:52:57.598  3735  4462 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-09 07:52:57.598  3735  4462 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-09 07:52:57.702  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:52:57.728  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-09 07:52:57.728  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-09 07:52:57.728  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:52:57.728  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:52:57.762  4227  4227 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-09 07:52:57.762  4227  4227 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-09 07:52:57.762  4227  4227 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-09 07:53:07.628   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=236504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 07:53:14.348   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=243224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-09 07:53:17.580   874   886 I ActivityManager: Start proc 4465:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-09 07:53:17.674  4465  4465 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-09 07:53:17.818  4465  4465 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-09 07:53:17.842  4465  4465 I BooksApp: Created application version: 3.6.9 (30609)
,08-09 07:53:17.944  4465  4482 I BooksSync: Starting books sync for 61035162, extras: ade
,08-09 07:53:18.108  4465  4488 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-09 07:53:18.138  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:53:18.141  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:53:18.176  1515  2416 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-09 07:53:18.176  1515  2416 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-09 07:53:18.176  1515  2416 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:53:18.176  1515  2416 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:53:18.227  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:53:18.229  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:53:18.251  1515  1958 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-09 07:53:18.251  1515  1958 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-09 07:53:18.251  1515  1958 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:53:18.251  1515  1958 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:53:18.267  4465  4488 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-09 07:53:18.269  4465  4482 E BooksSync: Soft error
08-09 07:53:18.269  4465  4482 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-09 07:53:18.269  4465  4482 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-09 07:53:18.269  4465  4482 E BooksSync: Sync error
08-09 07:53:18.269  4465  4482 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-09 07:53:18.269  4465  4482 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-09 07:53:18.269  4465  4482 I BooksSync: Finished books sync
,08-09 07:53:18.274   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 246271, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-09 07:53:18.276   874  1682 I ActivityManager: Killing 4191:com.google.android.deskclock/u0a44 (adj 15): empty #17
,08-09 07:53:22.832  4465  4480 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-09 07:53:27.896  4227  4240 D Finsky  : [365] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-09 07:53:27.917  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:53:27.928  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:53:27.931  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:53:27.978  1515  2416 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-09 07:53:27.978  1515  2416 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,08-09 07:53:27.978  1515  2416 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:53:27.979  1515  2416 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:53:28.020  4227  4240 D Finsky  : [365] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-09 07:53:44.240   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=273117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 07:53:48.544  3932  4495 V KeepSync: Connecting to GoogleApiClient
,08-09 07:53:48.545   874  1773 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-09 07:53:48.590  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:53:48.592  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:53:48.630  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-09 07:53:48.631  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-09 07:53:48.631  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:53:48.631  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:53:48.648  2513  4496 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-09 07:53:48.648  2513  4496 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-09 07:53:48.648  2513  4496 E HttpOperation: 	at jdm.a(PG:82)
08-09 07:53:48.648  2513  4496 E HttpOperation: 	at jcs.o(PG:406)
08-09 07:53:48.648  2513  4496 E HttpOperation: 	at jcn.a(PG:1379)
08-09 07:53:48.648  2513  4496 E HttpOperation: 	at jcs.i(PG:143)
08-09 07:53:48.648  2513  4496 E HttpOperation: 	at blb.a(PG:3937)
08-09 07:53:48.648  2513  4496 E HttpOperation: 	at czp.a(PG:18188)
08-09 07:53:48.648  2513  4496 E HttpOperation: 	at czp.a(PG:9081)
08-09 07:53:48.648  2513  4496 E HttpOperation: 	at czq.run(PG:1686)
08-09 07:53:48.648  2513  4496 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 07:53:48.648  2513  4496 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 07:53:48.648  2513  4496 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 07:53:48.648  2513  4496 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 07:53:48.648  2513  4496 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:53:48.648  2513  4496 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 07:53:48.648  2513  4496 E HttpOperation: 	at jdj.a(PG:4091)
08-09 07:53:48.648  2513  4496 E HttpOperation: 	at jdj.a(PG:1125)
08-09 07:53:48.648  2513  4496 E HttpOperation: 	at jdm.a(PG:77)
08-09 07:53:48.648  2513  4496 E HttpOperation: 	... 12 more
08-09 07:53:48.648  2513  4496 E HttpOperation: Caused by: faj: BadAuthentication
08-09 07:53:48.648  2513  4496 E HttpOperation: 	at fal.a(PG:38)
08-09 07:53:48.648  2513  4496 E HttpOperation: 	at jdj.a(PG:4089)
08-09 07:53:48.648  2513  4496 E HttpOperation: 	... 14 more
,08-09 07:53:48.695  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-09 07:53:48.695  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-09 07:53:48.695  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:53:48.695  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:53:48.723  1907  4497 V BaseAuthAsyncOperation: access token request failed
,08-09 07:53:48.725  1515  2067 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-09 07:53:48.725  1515  2067 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-09 07:53:48.725  1515  2067 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:53:48.725  1515  2067 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-09 07:53:48.726  3932  4495 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-09 07:53:48.757  2513  4496 E HttpOperation: [getmobileexperiments] Unexpected exception
08-09 07:53:48.757  2513  4496 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-09 07:53:48.757  2513  4496 E HttpOperation: 	at jdm.a(PG:82)
08-09 07:53:48.757  2513  4496 E HttpOperation: 	at jcs.o(PG:406)
08-09 07:53:48.757  2513  4496 E HttpOperation: 	at jcn.a(PG:1379)
08-09 07:53:48.757  2513  4496 E HttpOperation: 	at jcs.i(PG:143)
08-09 07:53:48.757  2513  4496 E HttpOperation: 	at hec.a(PG:42)
08-09 07:53:48.757  2513  4496 E HttpOperation: 	at hee.a(PG:102)
08-09 07:53:48.757  2513  4496 E HttpOperation: 	at czr.a(PG:65)
08-09 07:53:48.757  2513  4496 E HttpOperation: 	at kka.a(PG:108)
08-09 07:53:48.757  2513  4496 E HttpOperation: 	at czp.a(PG:19176)
08-09 07:53:48.757  2513  4496 E HttpOperation: 	at czp.a(PG:9081)
08-09 07:53:48.757  2513  4496 E HttpOperation: 	at czq.run(PG:1686)
08-09 07:53:48.757  2513  4496 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 07:53:48.757  2513  4496 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 07:53:48.757  2513  4496 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 07:53:48.757  2513  4496 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 07:53:48.757  2513  4496 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:53:48.757  2513  4496 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 07:53:48.757  2513  4496 E HttpOperation: 	at jdj.a(PG:4091)
08-09 07:53:48.757  2513  4496 E HttpOperation: 	at jdj.a(PG:1125)
08-09 07:53:48.757  2513  4496 E HttpOperation: 	at jdm.a(PG:77)
08-09 07:53:48.757  2513  4496 E HttpOperation: 	... 15 more
08-09 07:53:48.757  2513  4496 E HttpOperation: Caused by: faj: BadAuthentication
08-09 07:53:48.757  2513  4496 E HttpOperation: 	at fal.a(PG:38)
08-09 07:53:48.757  2513  4496 E HttpOperation: 	at jdj.a(PG:4089)
08-09 07:53:48.757  2513  4496 E HttpOperation: 	... 17 more
,08-09 07:53:48.757  2513  4496 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-09 07:53:48.757  2513  4496 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	at jdm.a(PG:82)
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	at jcs.o(PG:406)
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	at jcn.a(PG:1379)
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	at jcs.i(PG:143)
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	at hec.a(PG:42)
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	at hee.a(PG:102)
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	at czr.a(PG:65)
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	at kka.a(PG:108)
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	at czp.a(PG:19176)
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	at czp.a(PG:9081)
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	at czq.run(PG:1686)
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:53:48.757  2513  4496 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	at jdj.a(PG:4091)
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	at jdj.a(PG:1125)
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	at jdm.a(PG:77)
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	... 15 more
08-09 07:53:48.757  2513  4496 E ExperimentLoader: Caused by: faj: BadAuthentication
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	at fal.a(PG:38)
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	at jdj.a(PG:4089)
08-09 07:53:48.757  2513  4496 E ExperimentLoader: 	... 17 more
,08-09 07:53:48.815  1515  1958 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-09 07:53:48.815  1515  1958 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-09 07:53:48.815  1515  1958 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 07:53:48.815  1515  1958 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:53:48.833  3932  4495 E KeepSync: IOException
08-09 07:53:48.833  3932  4495 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-09 07:53:48.833  3932  4495 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-09 07:53:48.833  3932  4495 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-09 07:53:48.833  3932  4495 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-09 07:53:48.833  3932  4495 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-09 07:53:48.833  3932  4495 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-09 07:53:48.833  3932  4495 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-09 07:53:48.833  3932  4495 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-09 07:53:48.833  3932  4495 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-09 07:53:48.833  3932  4495 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-09 07:53:48.833  3932  4495 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-09 07:53:48.833  3932  4495 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-09 07:53:48.833  3932  4495 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-09 07:53:48.833  3932  4495 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-09 07:53:48.833  3932  4495 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
,08-09 07:53:48.833  3932  4495 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-09 07:53:48.833  3932  4495 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-09 07:53:48.833  3932  4495 E KeepSync: 	... 10 more
08-09 07:53:48.833  3932  4495 W KeepSync: Sync result 2
,08-09 07:53:48.842   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 270623, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-09 07:53:48.957   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 270442, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-09 07:53:50.267   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=279144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-09 07:54:19.127  4465  4504 I BooksSync: Starting books sync for 61035162, extras: ade
,08-09 07:54:19.157  4465  4505 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-09 07:54:19.172  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:54:19.174  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:54:19.218  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-09 07:54:19.218  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-09 07:54:19.218  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:54:19.218  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:54:19.276  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:54:19.281  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:54:19.330  1515  1958 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-09 07:54:19.330  1515  1958 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-09 07:54:19.330  1515  1958 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:54:19.330  1515  1958 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:54:19.366  4465  4505 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-09 07:54:19.367  4465  4504 E BooksSync: Soft error
08-09 07:54:19.367  4465  4504 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-09 07:54:19.367  4465  4504 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-09 07:54:19.367  4465  4504 E BooksSync: Sync error
08-09 07:54:19.367  4465  4504 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-09 07:54:19.367  4465  4504 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-09 07:54:19.367  4465  4504 I BooksSync: Finished books sync
,08-09 07:54:19.381   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 279460, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-09 07:54:20.187   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=309063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 07:54:26.214   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=315090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-09 07:54:56.134   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=345011, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 07:54:57.746  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:54:57.748  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:54:57.758  3735  4508 V GoogleAuthProtoRequest: [325] a.<init>: mAccountName set to: thalitester@gmail.com
,08-09 07:54:57.786  1515  2067 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-09 07:54:57.786  1515  2067 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-09 07:54:57.786  1515  2067 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:54:57.787  1515  2067 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:54:57.802  3735  4508 W ExperimentUpdateService: [325] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-09 07:54:57.802  3735  4508 W ExperimentUpdateService: [325] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-09 07:54:57.802  3735  4508 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-09 07:54:57.802  3735  4508 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-09 07:54:57.802  3735  4508 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-09 07:54:57.802  3735  4508 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-09 07:54:57.802  3735  4508 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-09 07:54:57.802  3735  4508 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-09 07:54:57.802  3735  4508 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-09 07:54:57.802  3735  4508 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-09 07:54:57.802  3735  4508 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-09 07:54:57.802  3735  4508 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-09 07:55:02.240   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=351117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-09 07:55:24.181  4465  4519 I BooksSync: Starting books sync for 61035162, extras: ade
,08-09 07:55:24.223  4465  4520 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-09 07:55:24.246  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:55:24.250  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:55:24.304  1515  1958 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-09 07:55:24.304  1515  1958 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-09 07:55:24.304  1515  1958 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 07:55:24.305  1515  1958 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:55:24.361  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:55:24.367  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:55:24.423  1515  1958 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-09 07:55:24.423  1515  1958 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-09 07:55:24.423  1515  1958 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 07:55:24.424  1515  1958 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:55:24.452  4465  4520 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-09 07:55:24.453  4465  4519 E BooksSync: Soft error
08-09 07:55:24.453  4465  4519 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-09 07:55:24.453  4465  4519 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-09 07:55:24.455  4465  4519 E BooksSync: Sync error
08-09 07:55:24.455  4465  4519 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-09 07:55:24.455  4465  4519 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-09 07:55:24.455  4465  4519 I BooksSync: Finished books sync
,08-09 07:55:24.468   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 372876, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-09 07:55:54.716  3932  4523 V KeepSync: Connecting to GoogleApiClient
08-09 07:55:54.716   874  1769 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-09 07:55:54.778  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:55:54.782  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:55:54.858  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-09 07:55:54.858  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-09 07:55:54.858  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 07:55:54.858  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:55:54.887  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-09 07:55:54.887  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-09 07:55:54.887  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:55:54.887  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:55:54.913  2513  4524 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-09 07:55:54.913  2513  4524 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-09 07:55:54.913  2513  4524 E HttpOperation: 	at jdm.a(PG:82)
08-09 07:55:54.913  2513  4524 E HttpOperation: 	at jcs.o(PG:406)
08-09 07:55:54.913  2513  4524 E HttpOperation: 	at jcn.a(PG:1379)
08-09 07:55:54.913  2513  4524 E HttpOperation: 	at jcs.i(PG:143)
08-09 07:55:54.913  2513  4524 E HttpOperation: 	at blb.a(PG:3937)
08-09 07:55:54.913  2513  4524 E HttpOperation: 	at czp.a(PG:18188)
08-09 07:55:54.913  2513  4524 E HttpOperation: 	at czp.a(PG:9081)
08-09 07:55:54.913  2513  4524 E HttpOperation: 	at czq.run(PG:1686)
08-09 07:55:54.913  2513  4524 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 07:55:54.913  2513  4524 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 07:55:54.913  2513  4524 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 07:55:54.913  2513  4524 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 07:55:54.913  2513  4524 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:55:54.913  2513  4524 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 07:55:54.913  2513  4524 E HttpOperation: 	at jdj.a(PG:4091)
08-09 07:55:54.913  2513  4524 E HttpOperation: 	at jdj.a(PG:1125)
08-09 07:55:54.913  2513  4524 E HttpOperation: 	at jdm.a(PG:77)
08-09 07:55:54.913  2513  4524 E HttpOperation: 	... 12 more
08-09 07:55:54.913  2513  4524 E HttpOperation: Caused by: faj: BadAuthentication
08-09 07:55:54.913  2513  4524 E HttpOperation: 	at fal.a(PG:38)
08-09 07:55:54.913  2513  4524 E HttpOperation: 	at jdj.a(PG:4089)
08-09 07:55:54.913  2513  4524 E HttpOperation: 	... 14 more
,08-09 07:55:54.920  1907  4525 V BaseAuthAsyncOperation: access token request failed
,08-09 07:55:54.921  3932  4523 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-09 07:55:54.977  1515  1958 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-09 07:55:54.977  1515  1958 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-09 07:55:54.977  1515  1958 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:55:54.977  1515  1958 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:55:55.007  2513  4524 E HttpOperation: [getmobileexperiments] Unexpected exception
08-09 07:55:55.007  2513  4524 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-09 07:55:55.007  2513  4524 E HttpOperation: 	at jdm.a(PG:82)
08-09 07:55:55.007  2513  4524 E HttpOperation: 	at jcs.o(PG:406)
08-09 07:55:55.007  2513  4524 E HttpOperation: 	at jcn.a(PG:1379)
08-09 07:55:55.007  2513  4524 E HttpOperation: 	at jcs.i(PG:143)
08-09 07:55:55.007  2513  4524 E HttpOperation: 	at hec.a(PG:42)
08-09 07:55:55.007  2513  4524 E HttpOperation: 	at hee.a(PG:102)
08-09 07:55:55.007  2513  4524 E HttpOperation: 	at czr.a(PG:65)
08-09 07:55:55.007  2513  4524 E HttpOperation: 	at kka.a(PG:108)
08-09 07:55:55.007  2513  4524 E HttpOperation: 	at czp.a(PG:19176)
08-09 07:55:55.007  2513  4524 E HttpOperation: 	at czp.a(PG:9081)
08-09 07:55:55.007  2513  4524 E HttpOperation: 	at czq.run(PG:1686)
08-09 07:55:55.007  2513  4524 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 07:55:55.007  2513  4524 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 07:55:55.007  2513  4524 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 07:55:55.007  2513  4524 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 07:55:55.007  2513  4524 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:55:55.007  2513  4524 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 07:55:55.007  2513  4524 E HttpOperation: 	at jdj.a(PG:4091)
08-09 07:55:55.007  2513  4524 E HttpOperation: 	at jdj.a(PG:1125)
08-09 07:55:55.007  2513  4524 E HttpOperation: 	at jdm.a(PG:77)
08-09 07:55:55.007  2513  4524 E HttpOperation: 	... 15 more
08-09 07:55:55.007  2513  4524 E HttpOperation: Caused by: faj: BadAuthentication
08-09 07:55:55.007  2513  4524 E HttpOperation: 	at fal.a(PG:38)
08-09 07:55:55.007  2513  4524 E HttpOperation: 	at jdj.a(PG:4089)
08-09 07:55:55.007  2513  4524 E HttpOperation: 	... 17 more
,08-09 07:55:55.007  2513  4524 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-09 07:55:55.007  2513  4524 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	at jdm.a(PG:82)
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	at jcs.o(PG:406)
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	at jcn.a(PG:1379)
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	at jcs.i(PG:143)
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	at hec.a(PG:42)
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	at hee.a(PG:102)
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	at czr.a(PG:65)
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	at kka.a(PG:108)
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	at czp.a(PG:19176)
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	at czp.a(PG:9081)
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	at czq.run(PG:1686)
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-09 07:55:55.007  2513  4524 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	at jdj.a(PG:4091)
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	at jdj.a(PG:1125)
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	at jdm.a(PG:77)
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	... 15 more
08-09 07:55:55.007  2513  4524 E ExperimentLoader: Caused by: faj: BadAuthentication
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	at fal.a(PG:38)
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	at jdj.a(PG:4089)
08-09 07:55:55.007  2513  4524 E ExperimentLoader: 	... 17 more
,08-09 07:55:55.097  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-09 07:55:55.097  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-09 07:55:55.097  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:55:55.097  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:55:55.118  3932  4523 E KeepSync: IOException
08-09 07:55:55.118  3932  4523 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-09 07:55:55.118  3932  4523 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-09 07:55:55.118  3932  4523 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-09 07:55:55.118  3932  4523 E KeepSync: ,	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-09 07:55:55.118  3932  4523 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-09 07:55:55.118  3932  4523 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-09 07:55:55.118  3932  4523 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-09 07:55:55.118  3932  4523 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-09 07:55:55.118  3932  4523 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-09 07:55:55.118  3932  4523 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-09 07:55:55.118  3932  4523 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
,08-09 07:55:55.118  3932  4523 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-09 07:55:55.118  3932  4523 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-09 07:55:55.118  3932  4523 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-09 07:55:55.118  3932  4523 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-09 07:55:55.118  3932  4523 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-09 07:55:55.118  3932  4523 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-09 07:55:55.118  3932  4523 E KeepSync: 	... 10 more
08-09 07:55:55.118  3932  4523 W KeepSync: Sync result 2
,08-09 07:55:55.133   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 401787, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-09 07:55:55.151   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 401570, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-09 07:56:31.945  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:56:31.958  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:56:31.959  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:56:32.017  1515  2067 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-09 07:56:32.017  1515  2067 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-09 07:56:32.017  1515  2067 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 07:56:32.017  1515  2067 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:56:32.032  1515  2067 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-09 07:56:32.032  1515  2067 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-09 07:56:32.032  1515  2067 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-09 07:56:32.032  1515  2067 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-09 07:56:32.032  1515  2067 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-09 07:56:32.032  1515  2067 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-09 07:56:32.032  1515  2067 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-09 07:56:32.041  4227  4258 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-09 07:56:32.041  4227  4258 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-09 07:56:32.041  4227  4258 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-09 07:56:32.041  4227  4258 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-09 07:56:32.041  4227  4258 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-09 07:56:32.041  4227  4258 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-09 07:56:32.041  4227  4258 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-09 07:57:33.757  4465  4535 I BooksSync: Starting books sync for 61035162, extras: ade
,08-09 07:57:33.782  4465  4536 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-09 07:57:33.794  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:57:33.797  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:57:33.827  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-09 07:57:33.827  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-09 07:57:33.827  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 07:57:33.827  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:57:33.850  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:57:33.852  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:57:33.890  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-09 07:57:33.890  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-09 07:57:33.890  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 07:57:33.890  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:57:33.915  4465  4536 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-09 07:57:33.916  4465  4535 E BooksSync: Soft error
08-09 07:57:33.916  4465  4535 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-09 07:57:33.916  4465  4535 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-09 07:57:33.916  4465  4535 E BooksSync: Sync error
08-09 07:57:33.916  4465  4535 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-09 07:57:33.916  4465  4535 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-09 07:57:33.916  4465  4535 I BooksSync: Finished books sync
,08-09 07:57:33.930   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 502581, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-09 07:58:57.918  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:58:57.920  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 07:58:57.929  3735  4541 V GoogleAuthProtoRequest: [326] a.<init>: mAccountName set to: thalitester@gmail.com
,08-09 07:58:57.953  1515  1958 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-09 07:58:57.954  1515  1958 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-09 07:58:57.954  1515  1958 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 07:58:57.954  1515  1958 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 07:58:57.970  3735  4541 W ExperimentUpdateService: [326] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-09 07:58:57.970  3735  4541 W ExperimentUpdateService: [326] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-09 07:58:57.970  3735  4541 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-09 07:58:57.970  3735  4541 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-09 07:58:57.970  3735  4541 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-09 07:58:57.970  3735  4541 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-09 07:58:57.970  3735  4541 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-09 07:58:57.970  3735  4541 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-09 07:58:57.970  3735  4541 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-09 07:58:57.970  3735  4541 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-09 07:58:57.970  3735  4541 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-09 07:58:57.970  3735  4541 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-09 08:00:02.681   874   874 I ActivityManager: Start proc 4548:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,08-09 08:00:02.751  4548  4548 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
,08-09 08:00:02.853  4548  4548 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-09 08:00:02.853  4548  4548 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-09 08:00:02.853  4548  4548 I GAv4    :   adb logcat -s GAv4
,08-09 08:00:02.872  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 08:00:02.877  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 08:00:02.883  4548  4548 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-09 08:00:02.906  4548  4548 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-09 08:00:02.940  4548  4566 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-09 08:00:02.956  1515  2416 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-09 08:00:02.956  1515  2416 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-09 08:00:02.956  1515  2416 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 08:00:02.957  1515  2416 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 08:00:02.983  2513  4562 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-09 08:00:02.983  2513  4562 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-09 08:00:02.983  2513  4562 E HttpOperation: 	at jdm.a(PG:82)
08-09 08:00:02.983  2513  4562 E HttpOperation: 	at jcs.o(PG:406)
08-09 08:00:02.983  2513  4562 E HttpOperation: 	at jcn.a(PG:1379)
08-09 08:00:02.983  2513  4562 E HttpOperation: 	at jcs.i(PG:143)
08-09 08:00:02.983  2513  4562 E HttpOperation: 	at blb.a(PG:3937)
08-09 08:00:02.983  2513  4562 E HttpOperation: 	at czp.a(PG:18188)
08-09 08:00:02.983  2513  4562 E HttpOperation: 	at czp.a(PG:9081)
08-09 08:00:02.983  2513  4562 E HttpOperation: 	at czq.run(PG:1686)
08-09 08:00:02.983  2513  4562 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 08:00:02.983  2513  4562 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 08:00:02.983  2513  4562 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 08:00:02.983  2513  4562 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 08:00:02.983  2513  4562 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-09 08:00:02.983  2513  4562 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 08:00:02.983  2513  4562 E HttpOperation: 	at jdj.a(PG:4091)
08-09 08:00:02.983  2513  4562 E HttpOperation: 	at jdj.a(PG:1125)
08-09 08:00:02.983  2513  4562 E HttpOperation: 	at jdm.a(PG:77)
08-09 08:00:02.983  2513  4562 E HttpOperation: 	... 12 more
08-09 08:00:02.983  2513  4562 E HttpOperation: Caused by: faj: BadAuthentication
08-09 08:00:02.983  2513  4562 E HttpOperation: 	at fal.a(PG:38)
08-09 08:00:02.983  2513  4562 E HttpOperation: 	at jdj.a(PG:4089)
08-09 08:00:02.983  2513  4562 E HttpOperation: 	... 14 more
,08-09 08:00:03.066  1515  2067 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-09 08:00:03.067  1515  2067 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-09 08:00:03.067  1515  2067 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 08:00:03.067  1515  2067 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 08:00:03.083  2513  4562 E HttpOperation: [getmobileexperiments] Unexpected exception
08-09 08:00:03.083  2513  4562 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-09 08:00:03.083  2513  4562 E HttpOperation: 	at jdm.a(PG:82)
08-09 08:00:03.083  2513  4562 E HttpOperation: 	at jcs.o(PG:406)
08-09 08:00:03.083  2513  4562 E HttpOperation: 	at jcn.a(PG:1379)
08-09 08:00:03.083  2513  4562 E HttpOperation: 	at jcs.i(PG:143)
08-09 08:00:03.083  2513  4562 E HttpOperation: 	at hec.a(PG:42)
08-09 08:00:03.083  2513  4562 E HttpOperation: 	at hee.a(PG:102)
08-09 08:00:03.083  2513  4562 E HttpOperation: 	at czr.a(PG:65)
08-09 08:00:03.083  2513  4562 E HttpOperation: 	at kka.a(PG:108)
08-09 08:00:03.083  2513  4562 E HttpOperation: 	at czp.a(PG:19176)
08-09 08:00:03.083  2513  4562 E HttpOperation: 	at czp.a(PG:9081)
08-09 08:00:03.083  2513  4562 E HttpOperation: 	at czq.run(PG:1686)
08-09 08:00:03.083  2513  4562 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 08:00:03.083  2513  4562 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 08:00:03.083  2513  4562 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 08:00:03.083  2513  4562 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 08:00:03.083  2513  4562 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-09 08:00:03.083  2513  4562 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 08:00:03.083  2513  4562 E HttpOperation: 	at jdj.a(PG:4091)
08-09 08:00:03.083  2513  4562 E HttpOperation: 	at jdj.a(PG:1125)
08-09 08:00:03.083  2513  4562 E HttpOperation: 	at jdm.a(PG:77)
08-09 08:00:03.083  2513  4562 E HttpOperation: 	... 15 more
08-09 08:00:03.083  2513  4562 E HttpOperation: Caused by: faj: BadAuthentication
08-09 08:00:03.083  2513  4562 E HttpOperation: 	at fal.a(PG:38)
08-09 08:00:03.083  2513  4562 E HttpOperation: 	at jdj.a(PG:4089)
08-09 08:00:03.083  2513  4562 E HttpOperation: 	... 17 more
,08-09 08:00:03.083  2513  4562 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-09 08:00:03.083  2513  4562 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	at jdm.a(PG:82)
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	at jcs.o(PG:406)
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	at jcn.a(PG:1379)
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	at jcs.i(PG:143)
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	at hec.a(PG:42)
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	at hee.a(PG:102)
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	at czr.a(PG:65)
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	at kka.a(PG:108)
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	at czp.a(PG:19176)
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	at czp.a(PG:9081)
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	at czq.run(PG:1686)
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-09 08:00:03.083  2513  4562 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	at jdj.a(PG:4091)
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	at jdj.a(PG:1125)
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	at jdm.a(PG:77)
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	... 15 more
08-09 08:00:03.083  2513  4562 E ExperimentLoader: Caused by: faj: BadAuthentication
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	at fal.a(PG:38)
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	at jdj.a(PG:4089)
08-09 08:00:03.083  2513  4562 E ExperimentLoader: 	... 17 more
,08-09 08:00:03.246   874  1777 I ActivityManager: Killing 4210:com.qualcomm.timeservice/1000 (adj 15): empty #17
08-09 08:00:03.246   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 651500, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-09 08:00:03.435  3932  4568 V KeepSync: Connecting to GoogleApiClient
08-09 08:00:03.436   874  1385 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-09 08:00:03.516  1515  2067 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-09 08:00:03.516  1515  2067 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-09 08:00:03.516  1515  2067 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 08:00:03.516  1515  2067 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 08:00:03.541  1907  4569 V BaseAuthAsyncOperation: access token request failed
,08-09 08:00:03.542  3932  4568 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-09 08:00:03.602  1515  1526 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-09 08:00:03.602  1515  1526 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-09 08:00:03.602  1515  1526 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 08:00:03.602  1515  1526 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 08:00:03.620  3932  4568 E KeepSync: IOException
08-09 08:00:03.620  3932  4568 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-09 08:00:03.620  3932  4568 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-09 08:00:03.620  3932  4568 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-09 08:00:03.620  3932  4568 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-09 08:00:03.620  3932  4568 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-09 08:00:03.620  3932  4568 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-09 08:00:03.620  3932  4568 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-09 08:00:03.620  3932  4568 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-09 08:00:03.620  3932  4568 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-09 08:00:03.620  3932  4568 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-09 08:00:03.620  3932  4568 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-09 08:00:03.620  3932  4568 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-09 08:00:03.620  3932  4568 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-09 08:00:03.620  3932  4568 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-09 08:00:03.620  3932  4568 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-09 08:00:03.620  3932  4568 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-09 08:00:03.620  3932  4568 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-09 08:00:03.620  3932  4568 E KeepSync: 	... 10 more
,08-09 08:00:03.620  3932  4568 W KeepSync: Sync result 2
,08-09 08:00:03.632   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 652147, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-09 08:01:52.490  4465  4575 I BooksSync: Starting books sync for 61035162, extras: ade
,08-09 08:01:52.547  4465  4576 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-09 08:01:52.571  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 08:01:52.577  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 08:01:52.641  1515  2067 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-09 08:01:52.641  1515  2067 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-09 08:01:52.642  1515  2067 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 08:01:52.642  1515  2067 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 08:01:52.699  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 08:01:52.705  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 08:01:52.761  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-09 08:01:52.761  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-09 08:01:52.761  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 08:01:52.761  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 08:01:52.797  4465  4576 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-09 08:01:52.798  4465  4575 E BooksSync: Soft error
08-09 08:01:52.798  4465  4575 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-09 08:01:52.798  4465  4575 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-09 08:01:52.798  4465  4575 E BooksSync: Sync error
08-09 08:01:52.798  4465  4575 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-09 08:01:52.798  4465  4575 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-09 08:01:52.798  4465  4575 I BooksSync: Finished books sync
,08-09 08:01:52.812   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 761279, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-09 08:04:17.254   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=906130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:04:35.360   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=924237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:04:42.320   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=931197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:05:00.441   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=949317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:05:07.387   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=956263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:05:25.494   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=974370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:05:32.453   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=981330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:05:50.561   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=999437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:05:57.520   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1006397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:06:15.627   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1024504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:06:22.587   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1031463, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:06:40.681   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1049557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:06:47.627   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1056503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:06:58.039  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 08:06:58.040  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 08:06:58.048  3735  4590 V GoogleAuthProtoRequest: [327] a.<init>: mAccountName set to: thalitester@gmail.com
,08-09 08:06:58.079  1515  2067 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-09 08:06:58.079  1515  2067 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-09 08:06:58.079  1515  2067 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 08:06:58.079  1515  2067 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 08:06:58.095  3735  4590 W ExperimentUpdateService: [327] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-09 08:06:58.096  3735  4590 W ExperimentUpdateService: [327] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-09 08:06:58.096  3735  4590 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-09 08:06:58.096  3735  4590 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-09 08:06:58.096  3735  4590 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-09 08:06:58.096  3735  4590 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-09 08:06:58.096  3735  4590 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-09 08:06:58.096  3735  4590 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-09 08:06:58.096  3735  4590 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-09 08:06:58.096  3735  4590 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-09 08:06:58.096  3735  4590 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-09 08:06:58.096  3735  4590 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-09 08:07:02.854   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1071730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:07:12.694   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1081570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:07:30.787   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1099664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:07:37.734   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1106610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:07:55.841   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1124717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:08:02.800   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1131677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:08:18.604  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 08:08:18.613  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 08:08:18.654  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-09 08:08:18.655  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-09 08:08:18.655  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 08:08:18.655  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 08:08:18.675  2513  4597 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-09 08:08:18.675  2513  4597 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-09 08:08:18.675  2513  4597 E HttpOperation: 	at jdm.a(PG:82)
08-09 08:08:18.675  2513  4597 E HttpOperation: 	at jcs.o(PG:406)
08-09 08:08:18.675  2513  4597 E HttpOperation: 	at jcn.a(PG:1379)
08-09 08:08:18.675  2513  4597 E HttpOperation: 	at jcs.i(PG:143)
08-09 08:08:18.675  2513  4597 E HttpOperation: 	at blb.a(PG:3937)
08-09 08:08:18.675  2513  4597 E HttpOperation: 	at czp.a(PG:18188)
08-09 08:08:18.675  2513  4597 E HttpOperation: 	at czp.a(PG:9081)
08-09 08:08:18.675  2513  4597 E HttpOperation: 	at czq.run(PG:1686)
08-09 08:08:18.675  2513  4597 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 08:08:18.675  2513  4597 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 08:08:18.675  2513  4597 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 08:08:18.675  2513  4597 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 08:08:18.675  2513  4597 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-09 08:08:18.675  2513  4597 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 08:08:18.675  2513  4597 E HttpOperation: 	at jdj.a(PG:4091)
08-09 08:08:18.675  2513  4597 E HttpOperation: 	at jdj.a(PG:1125)
08-09 08:08:18.675  2513  4597 E HttpOperation: 	at jdm.a(PG:77)
08-09 08:08:18.675  2513  4597 E HttpOperation: 	... 12 more
08-09 08:08:18.675  2513  4597 E HttpOperation: Caused by: faj: BadAuthentication
08-09 08:08:18.675  2513  4597 E HttpOperation: 	at fal.a(PG:38)
08-09 08:08:18.675  2513  4597 E HttpOperation: 	at jdj.a(PG:4089)
08-09 08:08:18.675  2513  4597 E HttpOperation: 	... 14 more
,08-09 08:08:18.752  1515  1958 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-09 08:08:18.752  1515  1958 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-09 08:08:18.752  1515  1958 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 08:08:18.753  1515  1958 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 08:08:18.767  2513  4597 E HttpOperation: [getmobileexperiments] Unexpected exception
08-09 08:08:18.767  2513  4597 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-09 08:08:18.767  2513  4597 E HttpOperation: 	at jdm.a(PG:82)
08-09 08:08:18.767  2513  4597 E HttpOperation: 	at jcs.o(PG:406)
08-09 08:08:18.767  2513  4597 E HttpOperation: 	at jcn.a(PG:1379)
08-09 08:08:18.767  2513  4597 E HttpOperation: 	at jcs.i(PG:143)
08-09 08:08:18.767  2513  4597 E HttpOperation: 	at hec.a(PG:42)
08-09 08:08:18.767  2513  4597 E HttpOperation: 	at hee.a(PG:102)
08-09 08:08:18.767  2513  4597 E HttpOperation: 	at czr.a(PG:65)
08-09 08:08:18.767  2513  4597 E HttpOperation: 	at kka.a(PG:108)
08-09 08:08:18.767  2513  4597 E HttpOperation: 	at czp.a(PG:19176)
08-09 08:08:18.767  2513  4597 E HttpOperation: 	at czp.a(PG:9081)
08-09 08:08:18.767  2513  4597 E HttpOperation: 	at czq.run(PG:1686)
08-09 08:08:18.767  2513  4597 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 08:08:18.767  2513  4597 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 08:08:18.767  2513  4597 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 08:08:18.767  2513  4597 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 08:08:18.767  2513  4597 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-09 08:08:18.767  2513  4597 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 08:08:18.767  2513  4597 E HttpOperation: 	at jdj.a(PG:4091)
08-09 08:08:18.767  2513  4597 E HttpOperation: 	at jdj.a(PG:1125)
08-09 08:08:18.767  2513  4597 E HttpOperation: 	at jdm.a(PG:77)
08-09 08:08:18.767  2513  4597 E HttpOperation: 	... 15 more
08-09 08:08:18.767  2513  4597 E HttpOperation: Caused by: faj: BadAuthentication
08-09 08:08:18.767  2513  4597 E HttpOperation: 	at fal.a(PG:38)
08-09 08:08:18.767  2513  4597 E HttpOperation: 	at jdj.a(PG:4089)
08-09 08:08:18.767  2513  4597 E HttpOperation: 	... 17 more
,08-09 08:08:18.768  2513  4597 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-09 08:08:18.768  2513  4597 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	,at jdm.a(PG:82)
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	at jcs.o(PG:406)
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	at jcn.a(PG:1379)
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	at jcs.i(PG:143)
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	at hec.a(PG:42)
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	at hee.a(PG:102)
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	at czr.a(PG:65)
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	at kka.a(PG:108)
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	at czp.a(PG:19176)
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	at czp.a(PG:9081)
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	at czq.run(PG:1686)
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-09 08:08:18.768  2513  4597 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	at jdj.a(PG:4091)
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	at jdj.a(PG:1125)
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	at jdm.a(PG:77)
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	... 15 more,
08-09 08:08:18.768  2513  4597 E ExperimentLoader: Caused by: faj: BadAuthentication
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	at fal.a(PG:38)
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	at jdj.a(PG:4089)
08-09 08:08:18.768  2513  4597 E ExperimentLoader: 	... 17 more
,08-09 08:08:18.891   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 1147067, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,08-09 08:08:20.907   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1149783, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:08:27.867   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1156743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:08:46.001   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1174877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:08:49.066  3932  4604 V KeepSync: Connecting to GoogleApiClient
,08-09 08:08:49.067   874  1738 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-09 08:08:49.115  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 08:08:49.117  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 08:08:49.141  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-09 08:08:49.141  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-09 08:08:49.141  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-09 08:08:49.141  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 08:08:49.157  1907  4605 V BaseAuthAsyncOperation: access token request failed
,08-09 08:08:49.158  3932  4604 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-09 08:08:49.203  1515  2416 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-09 08:08:49.203  1515  2416 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-09 08:08:49.203  1515  2416 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 08:08:49.204  1515  2416 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 08:08:49.222  3932  4604 E KeepSync: IOException
08-09 08:08:49.222  3932  4604 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-09 08:08:49.222  3932  4604 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-09 08:08:49.222  3932  4604 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-09 08:08:49.222  3932  4604 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-09 08:08:49.222  3932  4604 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-09 08:08:49.222  3932  4604 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-09 08:08:49.222  3932  4604 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-09 08:08:49.222  3932  4604 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-09 08:08:49.222  3932  4604 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-09 08:08:49.222  3932  4604 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-09 08:08:49.222  3932  4604 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-09 08:08:49.222  3932  4604 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-09 08:08:49.222  3932  4604 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-09 08:08:49.222  3932  4604 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-09 08:08:49.222  3932  4604 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-09 08:08:49.222  3932  4604 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-09 08:08:49.222  3932  4604 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-09 08:08:49.222  3932  4604 E KeepSync: 	... 10 more
,08-09 08:08:49.223  3932  4604 W KeepSync: Sync result 2
,08-09 08:08:49.230   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1148782, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-09 08:08:53.041   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1181917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:09:11.147   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1200024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:09:14.520   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1203397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:09:29.758   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,08-09 08:09:36.240   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1225117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:09:39.600   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1228477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:10:01.308   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1250184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:10:04.654   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1253530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:10:18.808  1515  1997 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-09 08:10:26.374   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1275250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:10:29.707   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1278584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:10:29.829  4465  4609 I BooksSync: Starting books sync for 61035162, extras: ade
,08-09 08:10:29.895  4465  4610 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-09 08:10:29.920  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 08:10:29.926  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 08:10:29.988  1515  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-09 08:10:29.988  1515  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-09 08:10:29.988  1515  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 08:10:29.989  1515  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 08:10:30.048  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 08:10:30.053  1515  1515 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-09 08:10:30.106  1515  2416 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-09 08:10:30.106  1515  2416 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-09 08:10:30.106  1515  2416 I GLSUser : [GLSUser] Extracting token using key: Auth
08-09 08:10:30.106  1515  2416 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-09 08:10:30.140  4465  4610 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-09 08:10:30.141  4465  4609 E BooksSync: Soft error
08-09 08:10:30.141  4465  4609 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-09 08:10:30.141  4465  4609 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-09 08:10:30.142  4465  4609 E BooksSync: Sync error
08-09 08:10:30.142  4465  4609 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-09 08:10:30.142  4465  4609 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-09 08:10:30.142  4465  4609 I BooksSync: Finished books sync
,08-09 08:10:30.157   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1278634, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-09 08:10:51.427   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1300303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:10:55.374   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1304250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:11:17.094   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1325970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:11:20.440   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1329317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:11:42.161   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1351037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:11:45.507   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1354384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:12:07.227   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1376104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:12:10.573   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1379450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:12:32.294   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1401170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:12:35.633   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1404510, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:12:57.387   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1426263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:13:00.734   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1429610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:13:22.441   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1451317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:13:26.427   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1455303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:13:48.134   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1477010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:13:51.507   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1480383, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-09 08:14:13.227   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1502103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-09 08:14:26.320   874  4328 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1515197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),08-09 08:14:29.395  4622  4622 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-09 08:14:29.399  4622  4622 D AndroidRuntime: CheckJNI is OFF
08-09 08:14:29.435  4622  4622 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-09 08:14:29.477  4622  4622 I Radio-JNI: register_android_hardware_Radio DONE
08-09 08:14:29.499  4622  4622 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-09 08:14:29.512   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-09 08:14:29.512   874   887 I ActivityManager: Killing 3662:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-09 08:14:29.611   874   885 I WindowState: WIN DEATH: Window{e5aae35 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-09 08:14:29.612   874  1777 D GraphicsStats: Buffer count: 2
08-09 08:14:29.614   874  1309 D WifiService: Client connection lost with reason: 4
08-09 08:14:29.661   874   897 W PackageSettings: Skipping PackageSetting{166cf89 com.example.hello/10273} due to missing metadata
08-09 08:14:29.690   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-09 08:14:29.691   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-09 08:14:29.691   874   887 E ActivityManager: Failure starting process com.test.thalitest
08-09 08:14:29.691   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-09 08:14:29.691   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-09 08:14:29.691   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-09 08:14:29.691   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-09 08:14:29.691   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-09 08:14:29.691   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-09 08:14:29.691   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-09 08:14:29.691   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-09 08:14:29.691   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-09 08:14:29.691   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-09 08:14:29.691   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-09 08:14:29.691   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-09 08:14:29.691   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-09 08:14:29.691   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-09 08:14:29.691   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-09 08:14:29.691   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 08:14:29.691   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-09 08:14:29.691   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 08:14:29.691   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-09 08:14:29.691   874   887 I ActivityManager:   Force finishing activity ActivityRecord{55e8812 u0 com.test.thalitest/.MainActivity t4}
08-09 08:14:29.694   874   897 I art     : Starting a blocking GC Explicit
08-09 08:14:29.711   874  1682 W ActivityManager: Spurious death for ProcessRecord{cc69b28 0:com.test.thalitest/u0a0}, curProc for 3662: null
08-09 08:14:29.739   874   897 I art     : Explicit concurrent mark sweep GC freed 43535(3MB) AllocSpace objects, 9(180KB) LOS objects, 33% free, 29MB/43MB, paused 715us total 44.098ms
08-09 08:14:29.762   874   897 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-09 08:14:29.767  4622  4622 I art     : System.exit called, status: 0
08-09 08:14:29.767  4622  4622 I AndroidRuntime: VM exiting with result code 0.
08-09 08:14:29.801   874   897 I ActivityManager: Start proc 4633:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-09 08:14:29.801   874   897 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-09 08:14:29.816   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-09 08:14:29.825  4269  4269 D BluetoothMapAppObserver: onReceive
08-09 08:14:29.825  4269  4269 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-09 08:14:29.829   874  1298 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-09 08:14:29.830  1890  2027 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-09 08:14:29.838  3539  3539 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-09 08:14:29.865  1659  1659 I Keyboard.Facilitator: resetDictionaries() : en_US
08-09 08:14:29.874  1659  4648 I Keyboard.Facilitator.DecoderInitializer: run()
08-09 08:14:29.878  1659  4648 I Decoder : createOrResetDecoder
08-09 08:14:29.897  1723  1723 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-09 08:14:29.914   874   885 I ActivityManager: Start proc 4650:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-09 08:14:29.919   874  1777 I ActivityManager: Killing 4161:com.google.android.calendar/u0a37 (adj 15): empty #17
08-09 08:14:29.937   874  1688 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3662 uid 10000
08-09 08:14:29.939  1659  1659 I Keyboard.Facilitator: onFinishInput()
08-09 08:14:29.951   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-09 08:14:29.954  1515  1515 I ConfigService: onCreate
08-09 08:14:29.981  4650  4650 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-09 08:14:29.984  1515  4662 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-09 08:14:29.984  1515  4662 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 08:14:29.984  1515  4662 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 08:14:29.984  1515  4662 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 08:14:29.984  1515  4662 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 08:14:29.984  1515  4662 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 08:14:29.984  1515  4662 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 08:14:29.984  1515  4662 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 08:14:29.984  1515  4662 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 08:14:29.984  1515  4662 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 08:14:29.984  1515  4662 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 08:14:29.984  1515  4662 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 08:14:29.984  1515  4662 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 08:14:29.984  1515  4662 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 08:14:29.984  1515  4662 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-09 08:14:29.984  1515  4662 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-09 08:14:29.984  1515  4662 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-09 08:14:29.984  1515  4662 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-09 08:14:29.984  1515  4662 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-09 08:14:29.984  1515  4662 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 08:14:29.984  1515  4662 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 08:14:29.984  1515  4662 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 08:14:29.984  1515  4662 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 08:14:29.984  1515  4662 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 08:14:29.984  1515  4662 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 08:14:29.984  1515  4662 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 08:14:29.984  1515  4662 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 08:14:29.984  1515  4662 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 08:14:29.984  1515  4662 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 08:14:29.984  1515  4662 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 08:14:29.984  1515  4662 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 08:14:29.984  1515  4662 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 08:14:29.984  1515  4662 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-09 08:14:29.984  1515  4662 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-09 08:14:29.984  1515  4662 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-09 08:14:29.984  1515  4662 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-09 08:14:29.988  1740  1836 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-09 08:14:29.989   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-09 08:14:29.989   874   886 E PackageManager: Failed to write settings, restoring backup
08-09 08:14:29.989   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-09 08:14:29.989   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-09 08:14:29.989   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-09 08:14:29.989   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-09 08:14:29.989   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-09 08:14:29.989   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 08:14:29.989   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-09 08:14:29.989   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 08:14:29.992  1515  4662 W SQLiteOpenHelper: Opened config.db in read-only mode
08-09 08:14:29.996   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-09 08:14:29.996   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-09 08:14:29.996   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-09 08:14:29.996   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 08:14:29.996   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 08:14:29.996   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-09 08:14:29.996   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-09 08:14:29.996   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-09 08:14:29.996   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-09 08:14:29.996   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-09 08:14:29.996   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-09 08:14:29.996   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-09 08:14:29.996   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-09 08:14:29.996   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-09 08:14:29.996   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 08:14:29.996   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-09 08:14:29.996   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 08:14:29.996   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 08:14:29.996   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 08:14:29.996   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 08:14:29.996   874   887 E DropBoxManagerService: 	... 13 more
08-09 08:14:30.002   874  1384 I ActivityManager: Start proc 4663:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-09 08:14:30.003  1740  1836 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-09 08:14:30.003  1740  1836 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1740
08-09 08:14:30.003  1740  1836 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-09 08:14:30.003  1740  1836 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-09 08:14:30.003  1740  1836 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-09 08:14:30.003  1740  1836 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-09 08:14:30.003  1740  1836 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-09 08:14:30.003  1740  1836 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-09 08:14:30.003  1740  1836 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-09 08:14:30.003  1740  1836 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-09 08:14:30.003  1740  1836 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-09 08:14:30.003  1740  1836 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-09 08:14:30.003  1740  1836 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-09 08:14:30.003  1740  1836 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 08:14:30.005   874  1772 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-09 08:14:30.010   874  4673 E DropBoxManagerService: Can't write: system_app_crash
08-09 08:14:30.010   874  4673 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-09 08:14:30.010   874  4673 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-09 08:14:30.010   874  4673 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 08:14:30.010   874  4673 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 08:14:30.010   874  4673 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-09 08:14:30.010   874  4673 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-09 08:14:30.010   874  4673 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-09 08:14:30.010   874  4673 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 08:14:30.010   874  4673 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 08:14:30.010   874  4673 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 08:14:30.010   874  4673 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 08:14:30.010   874  4673 E DropBoxManagerService: 	... 5 more
08-09 08:14:30.012  1740  1836 I Process : Sending signal. PID: 1740 SIG: 9
08-09 08:14:30.025  1659  4648 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-09 08:14:30.087  1659  4648 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-09 08:14:30.089  1659  4648 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-09 08:14:30.089  1659  4648 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-09 08:14:30.092  1659  4648 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-09 08:14:30.092  1659  4648 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-09 08:14:30.092  1659  4648 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-09 08:14:30.092  1659  4648 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-09 08:14:30.095  1659  4648 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-09 08:14:30.095  1659  4648 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-09 08:14:30.095  1659  4648 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-09 08:14:30.100  1659  4648 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-09 08:14:30.100  1659  4648 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-09 08:14:30.100  1659  4648 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-09 08:14:30.115   874  1297 W InputDispatcher: channel 'cf566b2 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
08-09 08:14:30.115   874  1297 E InputDispatcher: channel 'cf566b2 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
08-09 08:14:30.116   874  1739 D GraphicsStats: Buffer count: 1
08-09 08:14:30.116   874  1682 I WindowState: WIN DEATH: Window{cf566b2 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-09 08:14:30.116   874  1682 W InputDispatcher: Attempted to unregister already unregistered input channel 'cf566b2 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-09 08:14:30.139  4650  4681 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-09 08:14:30.139  4650  4681 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-09 08:14:30.142   874  1385 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1740) has died
08-09 08:14:30.143   874  1385 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-09 08:14:30.145   874  1385 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-09 08:14:30.153  4650  4650 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-09 08:14:30.161   874   887 I ActivityManager: Start proc 4684:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-09 08:14:30.193   874  1384 I ActivityManager: Start proc 4696:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-09 08:14:30.201  1907  4683 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-09 08:14:30.202  1907  4683 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-09 08:14:30.204  4650  4701 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-09 08:14:30.221  4696  4696 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 08:14:30.228  4684  4684 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-09 08:14:30.228  4684  4684 D AndroidRuntime: Shutting down VM
08-09 08:14:30.239  4684  4684 E AndroidRuntime: FATAL EXCEPTION: main
08-09 08:14:30.239  4684  4684 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4684
08-09 08:14:30.239  4684  4684 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-09 08:14:30.239  4684  4684 E AndroidRuntime: 	... 10 more
08-09 08:14:30.241   874  1682 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-09 08:14:30.241  4684  4684 I Process : Sending signal. PID: 4684 SIG: 9
08-09 08:14:30.242   874  4711 E DropBoxManagerService: Can't write: system_app_crash
08-09 08:14:30.242   874  4711 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-09 08:14:30.242   874  4711 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-09 08:14:30.242   874  4711 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-09 08:14:30.242   874  4711 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-09 08:14:30.242   874  4711 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-09 08:14:30.242   874  4711 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-09 08:14:30.242   874  4711 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-09 08:14:30.242   874  4711 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-09 08:14:30.242   874  4711 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-09 08:14:30.242   874  4711 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-09 08:14:30.242   874  4711 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-09 08:14:30.242   874  4711 E DropBoxManagerService: 	... 5 more
08-09 08:14:30.253  1907  4683 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-09 08:14:30.255  1907  4683 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-09 08:14:30.258   874  1738 I ActivityManager: Killing 3850:com.android.settings/1000 (adj 15): empty #17
08-09 08:14:30.262   283   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
