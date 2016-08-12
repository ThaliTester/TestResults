#### Test 7975101549b9187_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-12 13:43:33.751  1751  2350 D Icing   : Loaded CLD2 Version V2.0 - 20141016
08-12 13:43:33.755  1539  2044 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-12 13:43:33.755  1539  2044 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 13:43:33.755  1539  2044 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 13:43:33.755  1539  2044 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-12 13:43:33.765  3698  3732 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
08-12 13:43:33.770  3557  3752 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 13:43:33.770  3557  3752 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 13:43:33.770  3557  3752 E HttpOperation: 	at jdm.a(PG:82)
08-12 13:43:33.770  3557  3752 E HttpOperation: 	at jcs.o(PG:406)
08-12 13:43:33.770  3557  3752 E HttpOperation: 	at jcn.a(PG:1379)
08-12 13:43:33.770  3557  3752 E HttpOperation: 	at jcs.i(PG:143)
,08-12 13:43:33.770  3557  3752 E HttpOperation: 	at hec.a(PG:42)
08-12 13:43:33.770  3557  3752 E HttpOperation: 	at hee.a(PG:102)
08-12 13:43:33.770  3557  3752 E HttpOperation: 	at czr.a(PG:65)
08-12 13:43:33.770  3557  3752 E HttpOperation: 	at kka.a(PG:108)
08-12 13:43:33.770  3557  3752 E HttpOperation: 	at czp.a(PG:19176)
08-12 13:43:33.770  3557  3752 E HttpOperation: 	at czp.a(PG:9081)
08-12 13:43:33.770  3557  3752 E HttpOperation: 	at czq.run(PG:1686)
08-12 13:43:33.770  3557  3752 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 13:43:33.770  3557  3752 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 13:43:33.770  3557  3752 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 13:43:33.770  3557  3752 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 13:43:33.770  3557  3752 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 13:43:33.770  3557  3752 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 13:43:33.770  3557  3752 E HttpOperation: 	at jdj.a(PG:4091)
08-12 13:43:33.770  3557  3752 E HttpOperation: 	at jdj.a(PG:1125)
08-12 13:43:33.770  3557  3752 E HttpOperation: 	at jdm.a(PG:77)
08-12 13:43:33.770  3557  3752 E HttpOperation: 	... 15 more
08-12 13:43:33.770  3557  3752 E HttpOperation: Caused by: faj: BadAuthentication
08-12 13:43:33.770  3557  3752 E HttpOperation: 	at fal.a(PG:38)
08-12 13:43:33.770  3557  3752 E HttpOperation: 	at jdj.a(PG:4089)
08-12 13:43:33.770  3557  3752 E HttpOperation: 	... 17 more
08-12 13:43:33.771  3557  3752 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 13:43:33.771  3557  3752 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	at hec.a(PG:42)
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	at hee.a(PG:102)
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	at czr.a(PG:65)
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	at kka.a(PG:108)
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	at czq.run(PG:1686)
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 13:43:33.771  3557  3752 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	at jdj.a(PG:1125)
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	at jdm.a(PG:77)
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	... 15 more
08-12 13:43:33.771  3557  3752 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	at fal.a(PG:38)
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 13:43:33.771  3557  3752 E ExperimentLoader: 	... 17 more
08-12 13:43:33.785  1751  2350 I Icing   : Indexing done 0A4562BF807829C124E952811A67787B55D6217E
08-12 13:43:33.827  3698  3732 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
08-12 13:43:33.861  3698  3732 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
--------- beginning of system
08-12 13:43:33.933   874   884 I ActivityManager: Killing 3428:com.android.settings/1000 (adj 15): empty #17
08-12 13:43:33.934   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 63394, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
08-12 13:43:34.471  3766  3766 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 13:43:34.476  3766  3766 D AndroidRuntime: CheckJNI is OFF
08-12 13:43:34.519  3766  3766 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-12 13:43:34.570  3766  3766 I Radio-JNI: register_android_hardware_Radio DONE
08-12 13:43:34.593  3766  3766 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-12 13:43:34.597   874  1966 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 13:43:34.620  1997  3762 W SearchService: Abort, client detached.
08-12 13:43:34.631  1997  2333 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@5cf3e86
08-12 13:43:34.631  1997  1997 I HotwordDetector: Closing mic
08-12 13:43:34.632  1997  2345 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-12 13:43:34.643  3766  3766 D AndroidRuntime: Shutting down VM
08-12 13:43:34.696   874   885 I ActivityManager: Start proc 3775:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-12 13:43:34.700   374  2347 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-12 13:43:34.702   374  2347 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-12 13:43:34.709   374  1280 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-12 13:43:34.713  1997  2344 I MicroRecognitionRnrImpl: Detection finished
08-12 13:43:34.715  1997  2338 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-12 13:43:34.778  3775  3775 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-12 13:43:34.813  3775  3775 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-12 13:43:34.822  3775  3775 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 6971-6974)
08-12 13:43:34.822  3775  3775 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 13:43:34.843  3775  3775 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a4f7e7b}
08-12 13:43:34.844  3775  3775 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 13:43:34.844  3775  3775 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 13:43:34.852  3775  3775 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-12 13:43:34.854  3775  3775 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-12 13:43:34.878  3775  3775 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-12 13:43:34.892  3775  3775 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-12 13:43:34.892  3775  3775 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-12 13:43:34.892  3775  3775 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 13:43:34.892  3775  3775 I Adreno  : Build Date                       : 10/20/15
08-12 13:43:34.892  3775  3775 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 13:43:34.892  3775  3775 I Adreno  : Local Branch                     : M14
08-12 13:43:34.892  3775  3775 I Adreno  : Remote Branch                    : 
08-12 13:43:34.892  3775  3775 I Adreno  : Remote Branch                    : 
08-12 13:43:34.892  3775  3775 I Adreno  : Reconstruct Branch               : 
,08-12 13:43:34.974   874   891 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a063f4:true
,08-12 13:43:35.012  3775  3775 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 13:43:35.031  3775  3775 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-12 13:43:35.090  3775  3814 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-12 13:43:35.103  3775  3800 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-12 13:43:35.146  3775  3814 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 13:43:35.200   874   892 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +540ms
,08-12 13:43:35.212  1855  1855 I Keyboard.Facilitator: onFinishInput()
,08-12 13:43:35.259  3775  3775 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3775
,08-12 13:43:35.402  3775  3775 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 13:43:35.512   874   884 I ActivityManager: Killing 2970:com.google.android.calendar/u0a37 (adj 15): empty #17,
,08-12 13:43:35.544   874   884 I ActivityManager: Killing 3127:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-12 13:43:35.671  3775  3817 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1699808976
,08-12 13:43:35.679  3775  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 13:43:35.679  3775  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 13:43:35.679  3775  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 13:43:35.679  3775  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 13:43:35.679  3775  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 13:43:35.679  3775  3817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@88c1e0f added. We now have 1 listener(s)
,08-12 13:43:35.682  3775  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-12 13:43:35.683  3775  3817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-12 13:43:35.683  3775  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-12 13:43:35.683  3775  3817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-12 13:43:35.687  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 13:43:35.687  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 13:43:35.687  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 13:43:35.687  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-12 13:43:35.687  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 13:43:35.687  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 13:43:35.687  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 13:43:35.687  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 13:43:35.687  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 13:43:35.687  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 13:43:35.687  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 13:43:35.687  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 13:43:35.687  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 13:43:35.687  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-12 13:43:35.687  3775  3817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57b6c7a added. We now have 1 listener(s)
,08-12 13:43:35.688  3775  3817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 13:43:35.693   874  1313 D WifiService: New client listening to asynchronous messages
,08-12 13:43:35.701  3775  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-12 13:43:35.701  3775  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-12 13:43:35.702  3775  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 13:43:35.702  3775  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-12 13:43:35.702  3775  3817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-12 13:43:35.708  3775  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 13:43:35.708  3775  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
08-12 13:43:35.717  3775  3817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-12 13:43:35.718  3775  3817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 13:43:35.718  3775  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 13:43:35.718  3775  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 13:43:35.718  3775  3817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 13:43:35.718  3775  3817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 13:43:35.718  3775  3817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 13:43:35.718  3775  3817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 13:43:35.718  3775  3817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 13:43:35.718  3775  3817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-12 13:43:35.718  3775  3817 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 13:43:35.718  3775  3817 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-12 13:43:35.780  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 13:43:35.782  3775  3775 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 13:43:35.784  3775  3775 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 13:43:36.846  3775  3826 W jxcore-log: Initializing JXcore engine
,08-12 13:43:36.847  3775  3826 W jxcore-log: JXcore engine is ready
,08-12 13:43:36.891  3826  3826 W Thread-321: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8934 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-12 13:43:36.891  3826  3826 W Thread-321: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11520]" dev="sockfs" ino=11520 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-12 13:43:36.891  3826  3826 W Thread-321: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 13:43:36.891  3826  3826 W Thread-321: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26470]" dev="sockfs" ino=26470 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-12 13:43:36.905  3775  3826 W jxcore-log: Starting JXcore engine
,08-12 13:43:36.995  3775  3826 W jxcore-log: Platform android
08-12 13:43:36.995  3775  3826 W jxcore-log: 
,08-12 13:43:36.995  3775  3826 W jxcore-log: Process ARCH arm
08-12 13:43:36.995  3775  3826 W jxcore-log: 
,08-12 13:43:37.221  3775  3826 I jxcore-log: JXcore Cordova bridge is ready!
08-12 13:43:37.221  3775  3826 I jxcore-log: 
,08-12 13:43:37.222  3775  3826 W jxcore-log: JXcore engine is started
,08-12 13:43:37.233  3775  3817 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-12 13:43:37.238  3775  3775 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 13:43:37.905  1539  1539 I ConfigService: onDestroy
,08-12 13:43:46.834   874   887 I ActivityManager: Waited long enough for: ServiceRecord{42ba52d u0 com.motorola.android.buacontactadapter/.AuthenticationService}
,08-12 13:43:52.187  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:43:52.193  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:43:52.195  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:43:52.216  1539  1553 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 13:43:52.216  1539  1553 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-12 13:43:52.216  1539  1553 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 13:43:52.216  1539  1553 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:43:52.244  3519  3519 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 13:43:52.245  3519  3519 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-12 13:43:52.245  3519  3519 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 2.
,08-12 13:43:53.185  3775  3826 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 13:43:53.185  3775  3826 I jxcore-log: 
,08-12 13:43:53.188  3775  3826 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 13:43:53.188  3775  3826 I jxcore-log: 
,08-12 13:43:53.197  3775  3826 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 13:43:53.197  3775  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 13:43:53.197  3775  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-12 13:43:53.197  3775  3826 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 13:43:53.197  3775  3826 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 13:43:53.197  3775  3826 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 13:43:53.197  3775  3826 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 13:43:53.197  3775  3826 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 13:43:53.204  3775  3826 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-12 13:43:53.206  3775  3826 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 13:43:53.206  3775  3826 I jxcore-log: 
,08-12 13:43:53.208  3775  3826 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 13:43:53.208  3775  3826 I jxcore-log: 
,08-12 13:43:53.568  3775  3826 I jxcore-log: Unit Test app is loaded
08-12 13:43:53.568  3775  3826 I jxcore-log: 
,08-12 13:43:53.575  3775  3826 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 13:43:53.575  3775  3826 I jxcore-log: 
,08-12 13:43:53.578  3775  3826 I jxcore-log: My device name is: motorola-Nexus 6
08-12 13:43:53.578  3775  3826 I jxcore-log: 
,08-12 13:43:53.580  3775  3826 I jxcore-log: WARN testUtils: myNameCallback not set!
08-12 13:43:53.580  3775  3826 I jxcore-log: 
,08-12 13:43:53.594  3775  3775 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 13:43:55.844  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 13:43:55.844  3775  3826 I jxcore-log: 
,08-12 13:43:56.445  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 13:43:56.445  3775  3826 I jxcore-log: 
,08-12 13:43:56.469  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 13:43:56.469  3775  3826 I jxcore-log: 
,08-12 13:43:57.821  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 13:43:57.821  3775  3826 I jxcore-log: 
,08-12 13:43:58.046  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 13:43:58.046  3775  3826 I jxcore-log: 
,08-12 13:43:58.052  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 13:43:58.052  3775  3826 I jxcore-log: 
,08-12 13:43:58.058  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 13:43:58.058  3775  3826 I jxcore-log: 
,08-12 13:43:58.074  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 13:43:58.074  3775  3826 I jxcore-log: 
,08-12 13:43:58.079  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-12 13:43:58.079  3775  3826 I jxcore-log: 
,08-12 13:43:58.751  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 13:43:58.751  3775  3826 I jxcore-log: 
,08-12 13:43:58.763  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 13:43:58.763  3775  3826 I jxcore-log: 
,08-12 13:43:58.774  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 13:43:58.774  3775  3826 I jxcore-log: 
,08-12 13:43:58.781  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 13:43:58.781  3775  3826 I jxcore-log: 
,08-12 13:43:58.831  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 13:43:58.831  3775  3826 I jxcore-log: 
,08-12 13:43:58.887  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 13:43:58.887  3775  3826 I jxcore-log: 
,08-12 13:43:58.894  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 13:43:58.894  3775  3826 I jxcore-log: 
,08-12 13:43:59.059  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 13:43:59.059  3775  3826 I jxcore-log: 
,08-12 13:43:59.086  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 13:43:59.086  3775  3826 I jxcore-log: 
,08-12 13:43:59.092  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 13:43:59.092  3775  3826 I jxcore-log: 
,08-12 13:43:59.098  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 13:43:59.098  3775  3826 I jxcore-log: 
,08-12 13:43:59.117  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 13:43:59.117  3775  3826 I jxcore-log: 
,08-12 13:43:59.201  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 13:43:59.201  3775  3826 I jxcore-log: 
,08-12 13:43:59.214  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 13:43:59.214  3775  3826 I jxcore-log: 
,08-12 13:43:59.241  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 13:43:59.241  3775  3826 I jxcore-log: 
,08-12 13:43:59.254  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 13:43:59.254  3775  3826 I jxcore-log: 
,08-12 13:43:59.273  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 13:43:59.273  3775  3826 I jxcore-log: 
,08-12 13:43:59.310  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 13:43:59.310  3775  3826 I jxcore-log: 
,08-12 13:43:59.316  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 13:43:59.316  3775  3826 I jxcore-log: 
,08-12 13:43:59.539  3775  3826 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 13:43:59.539  3775  3826 I jxcore-log: 
,08-12 13:43:59.552  3775  3826 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-12 13:43:59.553  3775  3826 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-12 13:43:59.553  3775  3826 I jxcore-log: 
,08-12 13:44:04.042   874   886 I ActivityManager: Start proc 3838:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,08-12 13:44:04.128  3838  3838 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,08-12 13:44:04.234  3838  3838 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,08-12 13:44:04.244  3838  3838 I BooksApp: Created application version: 3.6.9 (30609)
,08-12 13:44:04.321  3838  3855 I BooksSync: Starting books sync for 61035162, extras: ade
,08-12 13:44:04.476  3838  3861 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-12 13:44:04.508  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:44:04.513  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:44:04.549  1539  2313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 13:44:04.549  1539  2313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 13:44:04.549  1539  2313 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 13:44:04.549  1539  2313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:44:04.583  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:44:04.587  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:44:04.623  1539  1555 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 13:44:04.624  1539  1555 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 13:44:04.624  1539  1555 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 13:44:04.624  1539  1555 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:44:04.648  3838  3861 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-12 13:44:04.650  3838  3855 E BooksSync: Soft error
08-12 13:44:04.650  3838  3855 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 13:44:04.650  3838  3855 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 13:44:04.650  3838  3855 E BooksSync: Sync error
08-12 13:44:04.650  3838  3855 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 13:44:04.650  3838  3855 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-12 13:44:04.650  3838  3855 I BooksSync: Finished books sync
,08-12 13:44:04.668   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 66464, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 13:44:04.668   874   884 I ActivityManager: Killing 3222:com.google.android.gm/u0a78 (adj 15): empty #17
,08-12 13:44:08.788   978   978 I kickstart: STATUS: SAHARA_HELLO: hw_info = 0x01030710, pwrup_reason = 0x00004000
,08-12 13:44:08.789   978   978 I kickstart: STATUS: Wrote to /sys/power/wake_lock
,08-12 13:44:08.816   978   978 E kickstart: ERROR: function: open_file:195 filename = /dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2
08-12 13:44:08.816   978   978 I kickstart: STATUS: Opening file '/dev/block/platform/msm_sdcc.1/by-name/mdm1m9kefs2' for writing
,08-12 13:44:09.258  3838  3853 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-12 13:44:09.811   978   978 I kickstart: STATUS: Received file 'm9kefs2'
08-12 13:44:09.811   978   978 I kickstart: STATUS: 950272 bytes transferred in 0.993869 seconds
,08-12 13:44:09.811   978   978 I kickstart: STATUS: Successfully downloaded files from target 
08-12 13:44:09.813   978   978 I kickstart: STATUS: Wrote to /sys/power/wake_unlock
,08-12 13:44:09.815   978   978 I kickstart: STATUS: Sahara protocol completed
,08-12 13:44:10.368   874  1312 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-12 13:44:10.511   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=102663, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 13:44:12.542  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:44:12.559  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:44:12.565  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:44:12.611  1539  3313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-12 13:44:12.611  1539  3313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 13:44:12.611  1539  3313 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 13:44:12.611  1539  3313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:44:12.647  3519  3519 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 13:44:12.648  3519  3519 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-12 13:44:12.648  3519  3519 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-12 13:44:14.328  3519  3529 D Finsky  : [264] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,08-12 13:44:14.354  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:44:14.422  1539  2044 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-12 13:44:14.423  1539  2044 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-12 13:44:14.423  1539  2044 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 13:44:14.424  1539  2044 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:44:14.475  3519  3529 D Finsky  : [264] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,08-12 13:44:19.818   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=111970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 13:44:30.372   874  1312 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-12 13:44:32.950  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:44:32.964  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:44:32.967  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:44:32.998  1539  2261 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 13:44:32.999  1539  2261 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.,
08-12 13:44:32.999  1539  2261 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 13:44:32.999  1539  2261 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:44:33.037  3519  3519 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 13:44:33.037  3519  3519 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-12 13:44:33.038  3519  3519 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-12 13:44:35.086  1539  2313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 13:44:35.086  1539  2313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 13:44:35.087  1539  2313 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 13:44:35.087  1539  2313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:44:35.118  3557  3870 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-12 13:44:35.118  3557  3870 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 13:44:35.118  3557  3870 E HttpOperation: 	at jdm.a(PG:82)
08-12 13:44:35.118  3557  3870 E HttpOperation: 	at jcs.o(PG:406)
08-12 13:44:35.118  3557  3870 E HttpOperation: 	at jcn.a(PG:1379)
08-12 13:44:35.118  3557  3870 E HttpOperation: 	at jcs.i(PG:143)
08-12 13:44:35.118  3557  3870 E HttpOperation: 	at blb.a(PG:3937)
08-12 13:44:35.118  3557  3870 E HttpOperation: 	at czp.a(PG:18188)
08-12 13:44:35.118  3557  3870 E HttpOperation: 	at czp.a(PG:9081)
08-12 13:44:35.118  3557  3870 E HttpOperation: 	at czq.run(PG:1686)
08-12 13:44:35.118  3557  3870 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 13:44:35.118  3557  3870 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 13:44:35.118  3557  3870 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 13:44:35.118  3557  3870 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 13:44:35.118  3557  3870 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 13:44:35.118  3557  3870 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 13:44:35.118  3557  3870 E HttpOperation: 	at jdj.a(PG:4091)
08-12 13:44:35.118  3557  3870 E HttpOperation: 	at jdj.a(PG:1125)
08-12 13:44:35.118  3557  3870 E HttpOperation: 	at jdm.a(PG:77)
08-12 13:44:35.118  3557  3870 E HttpOperation: 	... 12 more
08-12 13:44:35.118  3557  3870 E HttpOperation: Caused by: faj: BadAuthentication
08-12 13:44:35.118  3557  3870 E HttpOperation: 	at fal.a(PG:38)
08-12 13:44:35.118  3557  3870 E HttpOperation: 	at jdj.a(PG:4089)
08-12 13:44:35.118  3557  3870 E HttpOperation: 	... 14 more
,08-12 13:44:35.179  1539  1553 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-12 13:44:35.179  1539  1553 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-12 13:44:35.179  1539  1553 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 13:44:35.179  1539  1553 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:44:35.213  3557  3870 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 13:44:35.213  3557  3870 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 13:44:35.213  3557  3870 E HttpOperation: 	at jdm.a(PG:82)
08-12 13:44:35.213  3557  3870 E HttpOperation: 	at jcs.o(PG:406)
08-12 13:44:35.213  3557  3870 E HttpOperation: 	at jcn.a(PG:1379)
08-12 13:44:35.213  3557  3870 E HttpOperation: 	at jcs.i(PG:143)
08-12 13:44:35.213  3557  3870 E HttpOperation: 	at hec.a(PG:42)
08-12 13:44:35.213  3557  3870 E HttpOperation: 	at hee.a(PG:102)
08-12 13:44:35.213  3557  3870 E HttpOperation: 	at czr.a(PG:65)
08-12 13:44:35.213  3557  3870 E HttpOperation: 	at kka.a(PG:108)
08-12 13:44:35.213  3557  3870 E HttpOperation: 	at czp.a(PG:19176)
08-12 13:44:35.213  3557  3870 E HttpOperation: 	at czp.a(PG:9081)
08-12 13:44:35.213  3557  3870 E HttpOperation: 	at czq.run(PG:1686)
08-12 13:44:35.213  3557  3870 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 13:44:35.213  3557  3870 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 13:44:35.213  3557  3870 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 13:44:35.213  3557  3870 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 13:44:35.213  3557  3870 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 13:44:35.213  3557  3870 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 13:44:35.213  3557  3870 E HttpOperation: 	at jdj.a(PG:4091)
08-12 13:44:35.213  3557  3870 E HttpOperation: 	at jdj.a(PG:1125)
08-12 13:44:35.213  3557  3870 E HttpOperation: 	at jdm.a(PG:77)
08-12 13:44:35.213  3557  3870 E HttpOperation: 	... 15 more
08-12 13:44:35.213  3557  3870 E HttpOperation: Caused by: faj: BadAuthentication
08-12 13:44:35.213  3557  3870 E HttpOperation: 	at fal.a(PG:38)
08-12 13:44:35.213  3557  3870 E HttpOperation: 	at jdj.a(PG:4089)
08-12 13:44:35.213  3557  3870 E HttpOperation: 	... 17 more
08-12 13:44:35.213  3557  3870 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 13:44:35.213  3557  3870 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	at hec.a(PG:42)
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	at hee.a(PG:102)
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	at czr.a(PG:65)
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	at kka.a(PG:108)
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	at czq.run(PG:1686)
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 13:44:35.213  3557  3870 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	at jdm.a(PG:77)
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	... 15 more
08-12 13:44:35.213  3557  3870 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	at fal.a(PG:38)
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 13:44:35.213  3557  3870 E ExperimentLoader: 	... 17 more
,08-12 13:44:35.253  1855  1955 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-12 13:44:35.253  1855  1955 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-12 13:44:35.299  1539  1539 I ConfigService: onCreate
,08-12 13:44:35.416   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 126929, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-12 13:44:40.358  1539  1539 I ConfigService: onDestroy
,08-12 13:44:52.364  1539  2150 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 13:44:57.445   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=149597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 13:44:58.070   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-12 13:44:58.080  1855  1855 I Keyboard.Facilitator: onFinishInput()
,08-12 13:44:58.092   874   894 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-12 13:44:58.092   874   894 I Adreno  : Build Date                       : 10/20/15
08-12 13:44:58.092   874   894 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-12 13:44:58.092   874   894 I Adreno  : Local Branch                     : M14
08-12 13:44:58.092   874   894 I Adreno  : Remote Branch                    : 
08-12 13:44:58.092   874   894 I Adreno  : Remote Branch                    : 
08-12 13:44:58.092   874   894 I Adreno  : Reconstruct Branch               : 
,08-12 13:44:58.138   280  1303 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (622 us)
,08-12 13:44:58.791  3775  3775 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-12 13:44:58.792  3775  3775 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-12 13:44:58.830   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
08-12 13:44:58.833  3775  3775 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4a5129 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@5846e2c, 16908290=android.view.AbsSavedState$1@5846e2c}, android:focusedViewId=100}]}]
08-12 13:44:58.833  3775  3775 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-12 13:44:58.833  3775  3775 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-12 13:44:58.833  3775  3775 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-12 13:44:58.850   874   894 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-12 13:44:58.855   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-12 13:44:58.855   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,08-12 13:44:58.855   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-12 13:44:58.863   874   883 I art     : Background partial concurrent mark sweep GC freed 56249(3MB) AllocSpace objects, 25(548KB) LOS objects, 33% free, 29MB/43MB, paused 5.564ms total 106.714ms
,08-12 13:44:59.079   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-12 13:44:59.083   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-12 13:44:59.091   874  1340 D SurfaceControl: Excessive delay in setPowerMode(): 234ms
,08-12 13:44:59.097   874   894 I DreamManagerService: Entering dreamland.
,08-12 13:44:59.098   874   894 I PowerManagerService: Dozing...
08-12 13:44:59.099   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-12 13:44:59.161   374  1281 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-12 13:44:59.162   374  1281 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-12 13:44:59.185  1906  3879 D NfcService: Discovery configuration equal, not updating.
,08-12 13:44:59.190   874  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-12 13:44:59.212   874  1312 E native  : do suspend false
,08-12 13:44:59.239   874  1312 D WifiConfigStore: No blacklist allowed without epno enabled
,08-12 13:44:59.261   874  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-12 13:44:59.274   874  1312 E native  : do suspend true
,08-12 13:44:59.300   374   374 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-12 13:44:59.301   374   374 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-12 13:44:59.698   874  1312 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-12 13:45:03.561  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:45:03.572  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:45:03.575  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:45:03.640  1539  2313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
08-12 13:45:03.640  1539  2313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-12 13:45:03.641  1539  2313 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 13:45:03.641  1539  2313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:45:03.665  3519  3519 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-12 13:45:03.666  3519  3519 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-12 13:45:03.666  3519  3519 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-12 13:45:04.717  2118  2641 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 13:45:05.312   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=157464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 13:45:05.563  3021  3884 V KeepSync: Connecting to GoogleApiClient
,08-12 13:45:05.566   874  1976 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-12 13:45:05.650  1539  1555 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-12 13:45:05.650  1539  1555 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-12 13:45:05.650  1539  1555 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 13:45:05.650  1539  1555 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:45:05.679  1751  3885 V BaseAuthAsyncOperation: access token request failed
,08-12 13:45:05.682  3021  3884 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-12 13:45:05.791  1539  2313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-12 13:45:05.791  1539  2313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-12 13:45:05.792  1539  2313 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 13:45:05.792  1539  2313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:45:05.835  3021  3884 E KeepSync: IOException
08-12 13:45:05.835  3021  3884 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-12 13:45:05.835  3021  3884 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-12 13:45:05.835  3021  3884 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-12 13:45:05.835  3021  3884 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-12 13:45:05.835  3021  3884 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-12 13:45:05.835  3021  3884 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-12 13:45:05.835  3021  3884 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-12 13:45:05.835  3021  3884 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-12 13:45:05.835  3021  3884 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-12 13:45:05.835  3021  3884 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-12 13:45:05.835  3021  3884 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-12 13:45:05.835  3021  3884 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-12 13:45:05.835  3021  3884 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-12 13:45:05.835  3021  3884 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-12 13:45:05.835  3021  3884 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 13:45:05.835  3021  3884 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 13:45:05.835  3021  3884 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-12 13:45:05.835  3021  3884 E KeepSync: 	... 10 more
,08-12 13:45:05.835  3021  3884 W KeepSync: Sync result 2
,08-12 13:45:05.849   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 128504, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 13:45:10.388   874  1312 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-12 13:45:29.464  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:45:29.652  1539  3887 I VacuumService: Vacuum at: now=1471002329652 tag=VacuumService
,08-12 13:45:29.755  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:45:29.772  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:45:29.775  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:45:29.946  1539  3313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-12 13:45:29.946  1539  3313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-12 13:45:29.946  1539  3313 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 13:45:29.946  1539  3313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:45:29.993  3519  3519 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-12 13:45:29.994  3519  3519 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-12 13:45:29.996  3519  3519 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-12 13:45:30.069  1539  3888 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-12 13:45:30.076  1539  3888 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-12 13:45:30.114  1539  3888 W Uploader:  no longer exists, so no auth token.
,08-12 13:45:31.239  1539  3888 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-12 13:45:31.239  1539  3888 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-12 13:45:31.239  1539  3888 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 13:45:31.239  1539  3888 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:45:31.252  1539  3888 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 13:45:31.252  1539  3888 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 13:45:31.252  1539  3888 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 13:45:31.252  1539  3888 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 13:45:31.252  1539  3888 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 13:45:31.252  1539  3888 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 13:45:31.252  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 13:45:31.252  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 13:45:31.252  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 13:45:31.252  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 13:45:31.252  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 13:45:31.252  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-12 13:45:31.252  1539  3888 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 13:45:31.507  1539  3888 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-12 13:45:31.507  1539  3888 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-12 13:45:31.507  1539  3888 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 13:45:31.507  1539  3888 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:45:31.521  1539  3888 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 13:45:31.521  1539  3888 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 13:45:31.521  1539  3888 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 13:45:31.521  1539  3888 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 13:45:31.521  1539  3888 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 13:45:31.521  1539  3888 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 13:45:31.521  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 13:45:31.521  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 13:45:31.521  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 13:45:31.521  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 13:45:31.521  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 13:45:31.521  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-12 13:45:31.521  1539  3888 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 13:45:31.653  1539  3888 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-12 13:45:31.654  1539  3888 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-12 13:45:31.654  1539  3888 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 13:45:31.654  1539  3888 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:45:31.667  1539  3888 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 13:45:31.667  1539  3888 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 13:45:31.667  1539  3888 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 13:45:31.667  1539  3888 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 13:45:31.667  1539  3888 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 13:45:31.667  1539  3888 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 13:45:31.667  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 13:45:31.667  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 13:45:31.667  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 13:45:31.667  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 13:45:31.667  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 13:45:31.667  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-12 13:45:31.667  1539  3888 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 13:45:32.159  1539  3888 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-12 13:45:32.159  1539  3888 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-12 13:45:32.159  1539  3888 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 13:45:32.159  1539  3888 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:45:32.176  1539  3888 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 13:45:32.176  1539  3888 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 13:45:32.176  1539  3888 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 13:45:32.176  1539  3888 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 13:45:32.176  1539  3888 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-12 13:45:32.176  1539  3888 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-12 13:45:32.176  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-12 13:45:32.176  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-12 13:45:32.176  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-12 13:45:32.176  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-12 13:45:32.176  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-12 13:45:32.176  1539  3888 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-12 13:45:32.176  1539  3888 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-12 13:45:35.951  3838  3901 I BooksSync: Starting books sync for 61035162, extras: ade
,08-12 13:45:35.985  3838  3902 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-12 13:45:36.025  1539  2313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-12 13:45:36.025  1539  2313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-12 13:45:36.025  1539  2313 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 13:45:36.025  1539  2313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:45:36.086  1539  1553 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-12 13:45:36.087  1539  1553 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 13:45:36.087  1539  1553 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 13:45:36.087  1539  1553 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:45:36.112  3838  3902 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-12 13:45:36.114  3838  3901 E BooksSync: Soft error
08-12 13:45:36.114  3838  3901 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 13:45:36.114  3838  3901 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-12 13:45:36.114  3838  3901 E BooksSync: Sync error
08-12 13:45:36.114  3838  3901 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 13:45:36.114  3838  3901 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-12 13:45:36.115  3838  3901 I BooksSync: Finished books sync
,08-12 13:45:36.126   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 160807, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 13:45:58.081  1855  1955 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-12 13:45:58.082  1855  1955 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-12 13:45:58.129  1539  1539 I ConfigService: onCreate
,08-12 13:46:03.196  1539  1539 I ConfigService: onDestroy
,08-12 13:46:09.925   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=222077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 13:46:16.858   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=229011, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 13:46:37.451  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:46:37.453  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:46:37.475  1539  1553 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 13:46:37.475  1539  1553 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-12 13:46:37.475  1539  1553 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 13:46:37.475  1539  1553 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:46:37.489  3557  3907 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-12 13:46:37.489  3557  3907 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 13:46:37.489  3557  3907 E HttpOperation: 	at jdm.a(PG:82)
08-12 13:46:37.489  3557  3907 E HttpOperation: 	at jcs.o(PG:406)
08-12 13:46:37.489  3557  3907 E HttpOperation: 	at jcn.a(PG:1379)
08-12 13:46:37.489  3557  3907 E HttpOperation: 	at jcs.i(PG:143)
08-12 13:46:37.489  3557  3907 E HttpOperation: 	at blb.a(PG:3937)
08-12 13:46:37.489  3557  3907 E HttpOperation: 	at czp.a(PG:18188)
08-12 13:46:37.489  3557  3907 E HttpOperation: 	at czp.a(PG:9081)
08-12 13:46:37.489  3557  3907 E HttpOperation: 	at czq.run(PG:1686)
08-12 13:46:37.489  3557  3907 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 13:46:37.489  3557  3907 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 13:46:37.489  3557  3907 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 13:46:37.489  3557  3907 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 13:46:37.489  3557  3907 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 13:46:37.489  3557  3907 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 13:46:37.489  3557  3907 E HttpOperation: 	at jdj.a(PG:4091)
08-12 13:46:37.489  3557  3907 E HttpOperation: 	at jdj.a(PG:1125)
08-12 13:46:37.489  3557  3907 E HttpOperation: 	at jdm.a(PG:77)
08-12 13:46:37.489  3557  3907 E HttpOperation: 	... 12 more
08-12 13:46:37.489  3557  3907 E HttpOperation: Caused by: faj: BadAuthentication
08-12 13:46:37.489  3557  3907 E HttpOperation: 	at fal.a(PG:38)
08-12 13:46:37.489  3557  3907 E HttpOperation: 	at jdj.a(PG:4089)
08-12 13:46:37.489  3557  3907 E HttpOperation: 	... 14 more
,08-12 13:46:37.523  1539  2313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 13:46:37.523  1539  2313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-12 13:46:37.523  1539  2313 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 13:46:37.523  1539  2313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:46:37.536  3557  3907 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 13:46:37.536  3557  3907 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 13:46:37.536  3557  3907 E HttpOperation: 	at jdm.a(PG:82)
08-12 13:46:37.536  3557  3907 E HttpOperation: 	at jcs.o(PG:406)
08-12 13:46:37.536  3557  3907 E HttpOperation: 	at jcn.a(PG:1379)
08-12 13:46:37.536  3557  3907 E HttpOperation: 	at jcs.i(PG:143)
08-12 13:46:37.536  3557  3907 E HttpOperation: 	at hec.a(PG:42)
08-12 13:46:37.536  3557  3907 E HttpOperation: 	at hee.a(PG:102)
08-12 13:46:37.536  3557  3907 E HttpOperation: 	at czr.a(PG:65)
08-12 13:46:37.536  3557  3907 E HttpOperation: 	at kka.a(PG:108)
08-12 13:46:37.536  3557  3907 E HttpOperation: 	at czp.a(PG:19176)
08-12 13:46:37.536  3557  3907 E HttpOperation: 	at czp.a(PG:9081)
08-12 13:46:37.536  3557  3907 E HttpOperation: 	at czq.run(PG:1686)
08-12 13:46:37.536  3557  3907 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 13:46:37.536  3557  3907 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 13:46:37.536  3557  3907 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 13:46:37.536  3557  3907 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 13:46:37.536  3557  3907 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 13:46:37.536  3557  3907 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 13:46:37.536  3557  3907 E HttpOperation: 	at jdj.a(PG:4091)
08-12 13:46:37.536  3557  3907 E HttpOperation: 	at jdj.a(PG:1125)
08-12 13:46:37.536  3557  3907 E HttpOperation: 	at jdm.a(PG:77)
08-12 13:46:37.536  3557  3907 E HttpOperation: 	... 15 more
08-12 13:46:37.536  3557  3907 E HttpOperation: Caused by: faj: BadAuthentication
08-12 13:46:37.536  3557  3907 E HttpOperation: 	at fal.a(PG:38)
08-12 13:46:37.536  3557  3907 E HttpOperation: 	at jdj.a(PG:4089)
08-12 13:46:37.536  3557  3907 E HttpOperation: 	... 17 more
,08-12 13:46:37.537  3557  3907 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 13:46:37.537  3557  3907 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	at hec.a(PG:42)
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	at hee.a(PG:102)
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	at czr.a(PG:65)
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	at kka.a(PG:108)
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	at czq.run(PG:1686)
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 13:46:37.537  3557  3907 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	at jdj.a(PG:1125)
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	at jdm.a(PG:77)
,08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	... 15 more
08-12 13:46:37.537  3557  3907 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	at fal.a(PG:38)
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 13:46:37.537  3557  3907 E ExperimentLoader: 	... 17 more
,08-12 13:46:37.651   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 249253, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-12 13:47:11.218  3021  3910 V KeepSync: Connecting to GoogleApiClient
,08-12 13:47:11.218   874  1689 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-12 13:47:11.278  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:47:11.280  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:47:11.308  1539  3313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-12 13:47:11.308  1539  3313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.,
,08-12 13:47:11.308  1539  3313 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 13:47:11.308  1539  3313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:47:11.327  1751  3911 V BaseAuthAsyncOperation: access token request failed
,08-12 13:47:11.328  3021  3910 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-12 13:47:11.381  1539  1553 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-12 13:47:11.381  1539  1553 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-12 13:47:11.381  1539  1553 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 13:47:11.381  1539  1553 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:47:11.403  3021  3910 E KeepSync: IOException
08-12 13:47:11.403  3021  3910 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-12 13:47:11.403  3021  3910 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-12 13:47:11.403  3021  3910 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-12 13:47:11.403  3021  3910 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-12 13:47:11.403  3021  3910 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-12 13:47:11.403  3021  3910 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-12 13:47:11.403  3021  3910 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-12 13:47:11.403  3021  3910 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-12 13:47:11.403  3021  3910 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-12 13:47:11.403  3021  3910 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-12 13:47:11.403  3021  3910 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-12 13:47:11.403  3021  3910 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-12 13:47:11.403  3021  3910 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-12 13:47:11.403  3021  3910 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-12 13:47:11.403  3021  3910 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 13:47:11.403  3021  3910 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 13:47:11.403  3021  3910 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-12 13:47:11.403  3021  3910 E KeepSync: 	... 10 more
,08-12 13:47:11.403  3021  3910 W KeepSync: Sync result 2
,08-12 13:47:11.411   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 283243, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 13:47:25.499   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=297651, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 13:47:33.791   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=305944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-12 13:47:44.199  3838  3917 I BooksSync: Starting books sync for 61035162, extras: ade
,08-12 13:47:44.229  3838  3918 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-12 13:47:44.244  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:47:44.246  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:47:44.286  1539  1555 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 13:47:44.287  1539  1555 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-12 13:47:44.287  1539  1555 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 13:47:44.287  1539  1555 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:47:44.326  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:47:44.331  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:47:44.381  1539  1553 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 13:47:44.381  1539  1553 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 13:47:44.381  1539  1553 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 13:47:44.381  1539  1553 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:47:44.412  3838  3918 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-12 13:47:44.413  3838  3917 E BooksSync: Soft error
08-12 13:47:44.413  3838  3917 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 13:47:44.413  3838  3917 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 13:47:44.413  3838  3917 E BooksSync: Sync error
08-12 13:47:44.413  3838  3917 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 13:47:44.413  3838  3917 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 13:47:44.415  3838  3917 I BooksSync: Finished books sync
,08-12 13:47:44.431   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 316251, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 13:48:10.493  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:48:10.507  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:48:10.509  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:48:10.540  1539  3313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-12 13:48:10.540  1539  3313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-12 13:48:10.540  1539  3313 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 13:48:10.540  1539  3313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:48:10.567  1539  3313 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-12 13:48:10.567  1539  3313 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-12 13:48:10.567  1539  3313 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-12 13:48:10.567  1539  3313 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-12 13:48:10.567  1539  3313 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-12 13:48:10.567  1539  3313 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-12 13:48:10.567  1539  3313 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-12 13:48:10.571  3519  3548 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-12 13:48:10.571  3519  3548 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-12 13:48:10.571  3519  3548 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-12 13:48:10.571  3519  3548 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-12 13:48:10.571  3519  3548 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-12 13:48:10.571  3519  3548 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-12 13:48:10.571  3519  3548 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-12 13:50:41.363  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:50:41.368  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:50:41.430  1539  2044 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 13:50:41.431  1539  2044 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-12 13:50:41.431  1539  2044 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 13:50:41.431  1539  2044 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:50:41.462  3557  3940 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-12 13:50:41.462  3557  3940 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 13:50:41.462  3557  3940 E HttpOperation: 	at jdm.a(PG:82)
08-12 13:50:41.462  3557  3940 E HttpOperation: 	at jcs.o(PG:406)
08-12 13:50:41.462  3557  3940 E HttpOperation: 	at jcn.a(PG:1379)
08-12 13:50:41.462  3557  3940 E HttpOperation: 	at jcs.i(PG:143)
08-12 13:50:41.462  3557  3940 E HttpOperation: 	at blb.a(PG:3937)
08-12 13:50:41.462  3557  3940 E HttpOperation: 	at czp.a(PG:18188)
08-12 13:50:41.462  3557  3940 E HttpOperation: 	at czp.a(PG:9081)
08-12 13:50:41.462  3557  3940 E HttpOperation: 	at czq.run(PG:1686)
08-12 13:50:41.462  3557  3940 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 13:50:41.462  3557  3940 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 13:50:41.462  3557  3940 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 13:50:41.462  3557  3940 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 13:50:41.462  3557  3940 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 13:50:41.462  3557  3940 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 13:50:41.462  3557  3940 E HttpOperation: 	at jdj.a(PG:4091)
08-12 13:50:41.462  3557  3940 E HttpOperation: 	at jdj.a(PG:1125)
08-12 13:50:41.462  3557  3940 E HttpOperation: 	at jdm.a(PG:77)
08-12 13:50:41.462  3557  3940 E HttpOperation: 	... 12 more
08-12 13:50:41.462  3557  3940 E HttpOperation: Caused by: faj: BadAuthentication
08-12 13:50:41.462  3557  3940 E HttpOperation: 	at fal.a(PG:38)
08-12 13:50:41.462  3557  3940 E HttpOperation: 	at jdj.a(PG:4089)
08-12 13:50:41.462  3557  3940 E HttpOperation: 	... 14 more
,08-12 13:50:41.527  1539  2313 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-12 13:50:41.527  1539  2313 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-12 13:50:41.527  1539  2313 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 13:50:41.527  1539  2313 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:50:41.555  3557  3940 E HttpOperation: [getmobileexperiments] Unexpected exception
08-12 13:50:41.555  3557  3940 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-12 13:50:41.555  3557  3940 E HttpOperation: 	at jdm.a(PG:82)
08-12 13:50:41.555  3557  3940 E HttpOperation: 	at jcs.o(PG:406)
08-12 13:50:41.555  3557  3940 E HttpOperation: 	at jcn.a(PG:1379)
08-12 13:50:41.555  3557  3940 E HttpOperation: 	at jcs.i(PG:143)
08-12 13:50:41.555  3557  3940 E HttpOperation: 	at hec.a(PG:42)
08-12 13:50:41.555  3557  3940 E HttpOperation: 	at hee.a(PG:102)
08-12 13:50:41.555  3557  3940 E HttpOperation: 	at czr.a(PG:65)
08-12 13:50:41.555  3557  3940 E HttpOperation: 	at kka.a(PG:108)
08-12 13:50:41.555  3557  3940 E HttpOperation: 	at czp.a(PG:19176)
08-12 13:50:41.555  3557  3940 E HttpOperation: 	at czp.a(PG:9081)
08-12 13:50:41.555  3557  3940 E HttpOperation: 	at czq.run(PG:1686)
08-12 13:50:41.555  3557  3940 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 13:50:41.555  3557  3940 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 13:50:41.555  3557  3940 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 13:50:41.555  3557  3940 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 13:50:41.555  3557  3940 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-12 13:50:41.555  3557  3940 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 13:50:41.555  3557  3940 E HttpOperation: 	at jdj.a(PG:4091)
08-12 13:50:41.555  3557  3940 E HttpOperation: 	at jdj.a(PG:1125)
08-12 13:50:41.555  3557  3940 E HttpOperation: 	at jdm.a(PG:77)
08-12 13:50:41.555  3557  3940 E HttpOperation: 	... 15 more
08-12 13:50:41.555  3557  3940 E HttpOperation: Caused by: faj: BadAuthentication
08-12 13:50:41.555  3557  3940 E HttpOperation: 	at fal.a(PG:38)
08-12 13:50:41.555  3557  3940 E HttpOperation: 	at jdj.a(PG:4089)
08-12 13:50:41.555  3557  3940 E HttpOperation: 	... 17 more
08-12 13:50:41.556  3557  3940 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-12 13:50:41.556  3557  3940 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	at jdm.a(PG:82)
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	at jcs.o(PG:406)
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	at jcn.a(PG:1379)
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	at jcs.i(PG:143)
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	at hec.a(PG:42)
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	at hee.a(PG:102)
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	at czr.a(PG:65)
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	at kka.a(PG:108)
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	at czp.a(PG:19176)
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	at czp.a(PG:9081)
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	at czq.run(PG:1686)
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-12 13:50:41.556  3557  3940 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	at jdj.a(PG:4091)
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	at jdm.a(PG:77)
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	... 15 more
08-12 13:50:41.556  3557  3940 E ExperimentLoader: Caused by: faj: BadAuthentication
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	at fal.a(PG:38)
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	at jdj.a(PG:4089)
08-12 13:50:41.556  3557  3940 E ExperimentLoader: 	... 17 more
,08-12 13:50:41.698   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 493172, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-12 13:51:22.020  3021  3943 V KeepSync: Connecting to GoogleApiClient
,08-12 13:51:22.021   874  1934 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-12 13:51:22.085  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:51:22.090  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:51:22.138  1539  2044 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-12 13:51:22.139  1539  2044 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-12 13:51:22.139  1539  2044 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 13:51:22.139  1539  2044 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:51:22.172  1751  3944 V BaseAuthAsyncOperation: access token request failed
,08-12 13:51:22.175  3021  3943 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-12 13:51:22.259  1539  2261 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-12 13:51:22.259  1539  2261 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-12 13:51:22.259  1539  2261 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 13:51:22.260  1539  2261 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:51:22.296  3021  3943 E KeepSync: IOException
08-12 13:51:22.296  3021  3943 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-12 13:51:22.296  3021  3943 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-12 13:51:22.296  3021  3943 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-12 13:51:22.296  3021  3943 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-12 13:51:22.296  3021  3943 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-12 13:51:22.296  3021  3943 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-12 13:51:22.296  3021  3943 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-12 13:51:22.296  3021  3943 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-12 13:51:22.296  3021  3943 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-12 13:51:22.296  3021  3943 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-12 13:51:22.296  3021  3943 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-12 13:51:22.296  3021  3943 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-12 13:51:22.296  3021  3943 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-12 13:51:22.296  3021  3943 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-12 13:51:22.296  3021  3943 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 13:51:22.296  3021  3943 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-12 13:51:22.296  3021  3943 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-12 13:51:22.296  3021  3943 E KeepSync: 	... 10 more
,08-12 13:51:22.296  3021  3943 W KeepSync: Sync result 2
,08-12 13:51:22.310   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 534045, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 13:52:00.479  3838  3946 I BooksSync: Starting books sync for 61035162, extras: ade
,08-12 13:52:00.535  3838  3947 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-12 13:52:00.549  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:52:00.552  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:52:00.581  1539  2261 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 13:52:00.582  1539  2261 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-12 13:52:00.582  1539  2261 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-12 13:52:00.582  1539  2261 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:52:00.606  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:52:00.608  1539  1539 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-12 13:52:00.628  1539  1555 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-12 13:52:00.628  1539  1555 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-12 13:52:00.628  1539  1555 I GLSUser : [GLSUser] Extracting token using key: Auth
08-12 13:52:00.628  1539  1555 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-12 13:52:00.639  3838  3947 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-12 13:52:00.640  3838  3946 E BooksSync: Soft error
08-12 13:52:00.640  3838  3946 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 13:52:00.640  3838  3946 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-12 13:52:00.640  3838  3946 E BooksSync: Sync error
08-12 13:52:00.640  3838  3946 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-12 13:52:00.640  3838  3946 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-12 13:52:00.640  3838  3946 I BooksSync: Finished books sync
,08-12 13:52:00.649   874   886 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 572528, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-12 13:53:40.796   874  1302 I PowerManagerService: Waking up from dozing (uid 1000)...
,08-12 13:53:40.797   874   874 V KeyguardServiceDelegate: onStartedWakingUp()
,08-12 13:53:40.798   874   894 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
08-12 13:53:40.801  1855  1855 I Keyboard.Facilitator: onFinishInput()
,08-12 13:53:40.809   874   894 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@32d1115)
08-12 13:53:40.810  3775  3775 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-12 13:53:40.811  3775  3775 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-12 13:53:40.816   874  1395 V KeyguardServiceDelegate: **** SHOWN CALLED ****
,08-12 13:53:40.819   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
,08-12 13:53:40.822   280   280 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6b24000
,08-12 13:53:40.823   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
08-12 13:53:40.831   874  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-12 13:53:40.837   874  1312 E native  : do suspend false
08-12 13:53:40.839  1906  2032 E BrcmNfcJni: nfaConnectionCallback: unknown event ????
08-12 13:53:40.839  1906  2032 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_TECH_CFG_EVT; status=0x0
08-12 13:53:40.839  1906  2032 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_PROTO_CFG_EVT; status=0x0
08-12 13:53:40.839  1906  2025 D BrcmNfcJni: RoutingManager::commitRouting
08-12 13:53:40.839  1906  2032 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_UPDATED_EVT
08-12 13:53:40.841  2118  2118 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
08-12 13:53:40.845   874  1312 D WifiConfigStore: No blacklist allowed without epno enabled
08-12 13:53:40.852  3775  3775 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-12 13:53:40.852  3775  3775 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
08-12 13:53:40.869   874  1970 I ActivityManager: Start proc 3958:com.google.android.apps.fitness/u0a51 for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider
,08-12 13:53:40.912  3958  3958 W System  : ClassLoader referenced unknown path: /system/app/FitnessPrebuilt/lib/arm
,08-12 13:53:40.928   374  1320 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-12 13:53:40.928   374  1320 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
08-12 13:53:40.929   874   894 I DisplayPowerController: Unblocked screen on after 130 ms
08-12 13:53:40.930   874   894 V KeyguardServiceDelegate: onScreenTurnedOn()
08-12 13:53:40.931   874   894 I DreamManagerService: Gently waking up from dream.
08-12 13:53:40.932   874  1970 I DreamManagerService: Leaving dreamland.
08-12 13:53:40.932   874   889 I DreamController: Stopping dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-12 13:53:40.938   874   884 I ActivityManager: Killing 3070:com.google.android.talk/u0a61 (adj 15): empty #17
,08-12 13:53:41.071   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,08-12 13:53:41.071   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,08-12 13:53:41.072   874  1340 D SurfaceControl: Excessive delay in setPowerMode(): 253ms
,08-12 13:53:41.536  1906  2316 D NfcService: Discovery configuration equal, not updating.
,08-12 13:53:43.864   874  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-12 13:53:49.925   874  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-12 13:54:02.051   874  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-12 13:54:05.085   874  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-12 13:54:20.264   874  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-12 13:54:23.304   874  1314 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,08-12 13:54:40.822  1855  1955 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-12 13:54:40.824  1855  1955 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-12 13:54:40.882  1539  1539 I ConfigService: onCreate
,08-12 13:54:45.987  1539  1539 I ConfigService: onDestroy
,08-12 13:55:40.884  2118  2641 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-12 13:55:41.793   874   894 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-12 13:55:41.801  1855  1855 I Keyboard.Facilitator: onFinishInput()
,08-12 13:55:42.381  3775  3775 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-12 13:55:42.381  3775  3775 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-12 13:55:42.414   874   894 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-12 13:55:42.418  3775  3775 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@4a5129 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@5846e2c, 16908290=android.view.AbsSavedState$1@5846e2c}, android:focusedViewId=100}]}]
,08-12 13:55:42.418  3775  3775 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-12 13:55:42.418  3775  3775 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-12 13:55:42.419  3775  3775 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-12 13:55:42.437   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
,08-12 13:55:42.437   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
08-12 13:55:42.437   874   892 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-12 13:55:42.674   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-12 13:55:42.676   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-12 13:55:42.679   874  1340 D SurfaceControl: Excessive delay in setPowerMode(): 242ms
08-12 13:55:42.683   874   894 I DreamManagerService: Entering dreamland.
08-12 13:55:42.684   874   894 I PowerManagerService: Dozing...
,08-12 13:55:42.684   874   889 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-12 13:55:42.744   874  1312 D WifiConfigStore: Retrieve network priorities after PNO.
,08-12 13:55:42.749   874  1312 E native  : do suspend true
,08-12 13:55:42.875   374  1321 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
08-12 13:55:42.876   374  1321 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-12 13:55:46.868  1751  3995 I EventLogService: Opted in for usage reporting
,08-12 13:55:46.870  1751  3995 I EventLogService: Aggregate from 1471000973034 (log), 1471000973034 (data)
,08-12 13:55:46.959  1751  3995 W EventLogAggregator: Unknown tag: snet_gcore
,08-12 13:55:46.959  1751  3995 W EventLogAggregator: Unknown tag: snet_launch_service
,08-12 13:55:47.016  1751  3995 I ServiceDumpSys: dumping service [account]
,08-12 13:56:41.826  1855  1955 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-12 13:56:41.831  1855  1955 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-12 13:56:41.884  1539  1539 I ConfigService: onCreate
,08-12 13:56:46.981  1539  1539 I ConfigService: onDestroy
,08-12 13:57:24.285   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=896437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 13:57:36.979   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=909130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 13:57:49.365   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=921517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 13:57:56.245   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=928397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 13:58:14.404   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=946557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 13:58:27.085   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=959237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 13:58:39.471   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=971624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 13:58:52.151   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=984304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 13:59:05.018   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=997170, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 13:59:17.658   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1009811, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 13:59:30.032   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1022184, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 13:59:42.725   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1034877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 13:59:55.151   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1047304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 14:00:07.804   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1059957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 14:00:20.191   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1072343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 14:00:32.858   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1085010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 14:00:45.232   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1097384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 14:00:57.925   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1110077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 14:01:10.298   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1122451, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 14:01:22.992   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1135144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 14:01:35.365   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1147517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 14:01:48.044   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1160197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 14:02:00.431   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1172584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 14:02:13.111   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1185263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 14:02:22.698   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1194850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 14:02:38.165   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1210317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 14:02:46.326   874   886 I UsageStatsService: User[0] Flushing usage stats to disk
,08-12 14:02:47.738   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1219890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 14:03:03.231   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1235384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 14:03:12.805   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1244957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 14:03:28.298   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1260450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 14:03:37.871   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1270023, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 14:03:53.351   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1285503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 14:04:02.938   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1295090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 14:04:18.405   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1310557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 14:04:28.005   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1320157, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 14:04:43.471   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1335624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 14:04:53.071   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1345223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 14:05:08.538   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1360690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 14:05:18.138   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1370290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 14:05:33.631   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1385784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 14:05:43.285   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1395437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 14:05:58.778   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1410930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 14:06:08.351   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1420503, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 14:06:23.831   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1435984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 14:06:33.391   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1445543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-12 14:06:48.885   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1461037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-12 14:06:58.458   874  1875 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1470610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),08-12 14:07:05.518  4028  4028 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-12 14:07:05.522  4028  4028 D AndroidRuntime: CheckJNI is OFF
08-12 14:07:05.558  4028  4028 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-12 14:07:05.599  4028  4028 I Radio-JNI: register_android_hardware_Radio DONE
08-12 14:07:05.620  4028  4028 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-12 14:07:05.633   874   887 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-12 14:07:05.633   874   887 I ActivityManager: Killing 3775:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-12 14:07:05.709   874  1313 D WifiService: Client connection lost with reason: 4
08-12 14:07:05.709   874  1976 D GraphicsStats: Buffer count: 2
08-12 14:07:05.710   874  1689 I WindowState: WIN DEATH: Window{a1eb224 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 14:07:05.812   874   898 W PackageSettings: Skipping PackageSetting{1f5fea6 com.example.hello/10273} due to missing metadata
08-12 14:07:05.847   874   887 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-12 14:07:05.847   874   887 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-12 14:07:05.848   874   887 E ActivityManager: Failure starting process com.test.thalitest
08-12 14:07:05.848   874   887 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-12 14:07:05.848   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-12 14:07:05.848   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-12 14:07:05.848   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-12 14:07:05.848   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-12 14:07:05.848   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-12 14:07:05.848   874   887 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-12 14:07:05.848   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-12 14:07:05.848   874   887 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-12 14:07:05.848   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-12 14:07:05.848   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-12 14:07:05.848   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-12 14:07:05.848   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-12 14:07:05.848   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-12 14:07:05.848   874   887 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-12 14:07:05.848   874   887 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 14:07:05.848   874   887 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-12 14:07:05.848   874   887 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 14:07:05.848   874   887 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-12 14:07:05.849   874   887 I ActivityManager:   Force finishing activity ActivityRecord{57a6ff5 u0 com.test.thalitest/.MainActivity t2}
08-12 14:07:05.849   874   898 I art     : Starting a blocking GC Explicit
08-12 14:07:05.885   874  1395 W ActivityManager: Spurious death for ProcessRecord{1863300 0:com.test.thalitest/u0a0}, curProc for 3775: null
08-12 14:07:05.900   874   898 I art     : Explicit concurrent mark sweep GC freed 31171(2MB) AllocSpace objects, 8(160KB) LOS objects, 33% free, 28MB/43MB, paused 790us total 50.489ms
08-12 14:07:05.921   874   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-12 14:07:05.927  4028  4028 I art     : System.exit called, status: 0
08-12 14:07:05.927  4028  4028 I AndroidRuntime: VM exiting with result code 0.
08-12 14:07:05.928   874   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-12 14:07:05.979   874   887 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-12 14:07:05.987  2673  2673 D BluetoothMapAppObserver: onReceive
08-12 14:07:05.987  2673  2673 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-12 14:07:05.991  2118  2297 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-12 14:07:05.992   874  1302 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-12 14:07:05.998  3638  3638 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-12 14:07:06.004  1855  1855 I Keyboard.Facilitator: resetDictionaries() : en_US
08-12 14:07:06.008  1855  4041 I Keyboard.Facilitator.DecoderInitializer: run()
08-12 14:07:06.010  1855  4041 I Decoder : createOrResetDecoder
08-12 14:07:06.020  1920  1920 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-12 14:07:06.061  1539  1539 I ConfigService: onCreate
08-12 14:07:06.082  3500  3517 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
08-12 14:07:06.083  3500  3517 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-12 14:07:06.083  3500  3517 E AndroidRuntime: Process: android.process.acore, PID: 3500
08-12 14:07:06.083  3500  3517 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 14:07:06.083  3500  3517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 14:07:06.083  3500  3517 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 14:07:06.083  3500  3517 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 14:07:06.083  3500  3517 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 14:07:06.083  3500  3517 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 14:07:06.083  3500  3517 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-12 14:07:06.083  3500  3517 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
08-12 14:07:06.083  3500  3517 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
08-12 14:07:06.083  3500  3517 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
08-12 14:07:06.083  3500  3517 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-12 14:07:06.083  3500  3517 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 14:07:06.083  3500  3517 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 14:07:06.083  3500  3517 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 14:07:06.088   874   874 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-12 14:07:06.088   874  4046 E DropBoxManagerService: Can't write: system_app_crash
08-12 14:07:06.088   874  4046 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop108.tmp: open failed: EROFS (Read-only file system)
08-12 14:07:06.088   874  4046 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 14:07:06.088   874  4046 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 14:07:06.088   874  4046 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 14:07:06.088   874  4046 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 14:07:06.088   874  4046 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 14:07:06.088   874  4046 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 14:07:06.088   874  4046 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 14:07:06.088   874  4046 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 14:07:06.088   874  4046 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 14:07:06.088   874  4046 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 14:07:06.088   874  4046 E DropBoxManagerService: 	... 5 more
08-12 14:07:06.092  3500  4044 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-12 14:07:06.094  1539  4043 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-12 14:07:06.094  1539  4043 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 14:07:06.094  1539  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 14:07:06.094  1539  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 14:07:06.094  1539  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 14:07:06.094  1539  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 14:07:06.094  1539  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 14:07:06.094  1539  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 14:07:06.094  1539  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 14:07:06.094  1539  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 14:07:06.094  1539  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 14:07:06.094  1539  4043 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 14:07:06.094  1539  4043 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 14:07:06.094  1539  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 14:07:06.094  1539  4043 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-12 14:07:06.094  1539  4043 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-12 14:07:06.094  1539  4043 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-12 14:07:06.094  1539  4043 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-12 14:07:06.094  1539  4043 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-12 14:07:06.094  1539  4043 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 14:07:06.094  1539  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 14:07:06.094  1539  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-12 14:07:06.094  1539  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-12 14:07:06.094  1539  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-12 14:07:06.094  1539  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-12 14:07:06.094  1539  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-12 14:07:06.094  1539  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-12 14:07:06.094  1539  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-12 14:07:06.094  1539  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-12 14:07:06.094  1539  4043 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-12 14:07:06.094  1539  4043 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-12 14:07:06.094  1539  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 14:07:06.094  1539  4043 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-12 14:07:06.094  1539  4043 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-12 14:07:06.094  1539  4043 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-12 14:07:06.094  1539  4043 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-12 14:07:06.096  1539  4043 W SQLiteOpenHelper: Opened config.db in read-only mode
08-12 14:07:06.103  1936  2036 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-12 14:07:06.105   874   886 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-12 14:07:06.106   874   886 E PackageManager: Failed to write settings, restoring backup
08-12 14:07:06.106   874   886 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-12 14:07:06.106   874   886 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-12 14:07:06.106   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-12 14:07:06.106   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-12 14:07:06.106   874   886 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-12 14:07:06.106   874   886 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 14:07:06.106   874   886 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-12 14:07:06.106   874   886 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 14:07:06.107   874   887 E DropBoxManagerService: Can't write: system_server_wtf
08-12 14:07:06.107   874   887 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-12 14:07:06.107   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 14:07:06.107   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 14:07:06.107   874   887 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 14:07:06.107   874   887 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 14:07:06.107   874   887 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 14:07:06.107   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 14:07:06.107   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-12 14:07:06.107   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-12 14:07:06.107   874   887 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-12 14:07:06.107   874   887 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 14:07:06.107   874   887 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 14:07:06.107   874   887 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-12 14:07:06.107   874   887 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 14:07:06.107   874   887 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-12 14:07:06.107   874   887 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 14:07:06.107   874   887 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 14:07:06.107   874   887 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 14:07:06.107   874   887 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 14:07:06.107   874   887 E DropBoxManagerService: 	... 13 more
08-12 14:07:06.116   874  1966 I ActivityManager: Start proc 4047:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-12 14:07:06.116  1936  2036 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-12 14:07:06.116  1936  2036 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1936
08-12 14:07:06.116  1936  2036 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 14:07:06.116  1936  2036 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 14:07:06.116  1936  2036 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 14:07:06.116  1936  2036 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 14:07:06.116  1936  2036 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 14:07:06.116  1936  2036 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 14:07:06.116  1936  2036 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-12 14:07:06.116  1936  2036 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-12 14:07:06.116  1936  2036 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 14:07:06.116  1936  2036 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 14:07:06.116  1936  2036 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 14:07:06.116  1936  2036 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 14:07:06.118   874  1934 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-12 14:07:06.121   874  4055 E DropBoxManagerService: Can't write: system_app_crash
08-12 14:07:06.121   874  4055 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
08-12 14:07:06.121   874  4055 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 14:07:06.121   874  4055 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 14:07:06.121   874  4055 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 14:07:06.121   874  4055 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 14:07:06.121   874  4055 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 14:07:06.121   874  4055 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 14:07:06.121   874  4055 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 14:07:06.121   874  4055 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 14:07:06.121   874  4055 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 14:07:06.121   874  4055 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 14:07:06.121   874  4055 E DropBoxManagerService: 	... 5 more
08-12 14:07:06.122  1936  2036 I Process : Sending signal. PID: 1936 SIG: 9
08-12 14:07:06.145  3500  4044 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
08-12 14:07:06.145  3500  4044 I Process : Sending signal. PID: 3500 SIG: 9
08-12 14:07:06.160  1855  4041 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-12 14:07:06.174  1539  1539 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-12 14:07:06.175  1539  1539 D AndroidRuntime: Shutting down VM
08-12 14:07:06.176  1539  1539 E AndroidRuntime: FATAL EXCEPTION: main
08-12 14:07:06.176  1539  1539 E AndroidRuntime: Process: com.google.process.gapps, PID: 1539
08-12 14:07:06.176  1539  1539 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 14:07:06.176  1539  1539 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-12 14:07:06.176  1539  1539 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-12 14:07:06.176  1539  1539 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-12 14:07:06.176  1539  1539 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 14:07:06.176  1539  1539 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 14:07:06.176  1539  1539 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-12 14:07:06.176  1539  1539 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 14:07:06.176  1539  1539 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-12 14:07:06.176  1539  1539 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-12 14:07:06.176  1539  1539 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 14:07:06.176  1539  1539 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-12 14:07:06.176  1539  1539 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-12 14:07:06.176  1539  1539 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-12 14:07:06.176  1539  1539 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-12 14:07:06.176  1539  1539 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-12 14:07:06.176  1539  1539 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-12 14:07:06.176  1539  1539 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-12 14:07:06.176  1539  1539 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-12 14:07:06.176  1539  1539 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-12 14:07:06.176  1539  1539 E AndroidRuntime: 	... 8 more
08-12 14:07:06.182  1539  1539 I Process : Sending signal. PID: 1539 SIG: 9
08-12 14:07:06.183   874  4062 E DropBoxManagerService: Can't write: system_app_crash
08-12 14:07:06.183   874  4062 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-12 14:07:06.183   874  4062 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 14:07:06.183   874  4062 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 14:07:06.183   874  4062 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 14:07:06.183   874  4062 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 14:07:06.183   874  4062 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 14:07:06.183   874  4062 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 14:07:06.183   874  4062 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 14:07:06.183   874  4062 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 14:07:06.183   874  4062 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 14:07:06.183   874  4062 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 14:07:06.183   874  4062 E DropBoxManagerService: 	... 5 more
08-12 14:07:06.193  1855  4041 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-12 14:07:06.194  1855  4041 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-12 14:07:06.194  1855  4041 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-12 14:07:06.197  1855  4041 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-12 14:07:06.197  1855  4041 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-12 14:07:06.197  1855  4041 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-12 14:07:06.197  1855  4041 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-12 14:07:06.198  1855  4041 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-12 14:07:06.198  1855  4041 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-12 14:07:06.198  1855  4041 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-12 14:07:06.198  1855  4041 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-12 14:07:06.198  1855  4041 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-12 14:07:06.198  1855  4041 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-12 14:07:06.203   874  1934 D GraphicsStats: Buffer count: 1
08-12 14:07:06.203   874  1935 I WindowState: WIN DEATH: Window{2fcf655 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-12 14:07:06.208   874  1691 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1936) has died
08-12 14:07:06.208   874  1691 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-12 14:07:06.239   874  1313 D WifiService: Client connection lost with reason: 4
08-12 14:07:06.245   874  1970 I ActivityManager: Process com.google.process.gapps (pid 1539) has died
08-12 14:07:06.245   874  1970 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
08-12 14:07:06.245   874  1970 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
08-12 14:07:06.245   874  1970 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
08-12 14:07:06.245   874  1970 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.http.GoogleHttpService in 31000ms
08-12 14:07:06.248  3698  3698 W RocketImpressions: ClearcutLogger connection suspended: 1
08-12 14:07:06.258   874  1388 I ActivityManager: Start proc 4066:com.google.process.gapps/u0a11 for service com.google.android.gms/.gcm.http.GoogleHttpService
08-12 14:07:06.266  1751  1751 W RocketImpressions: ClearcutLogger connection suspended: 1
08-12 14:07:06.281   874   884 I ActivityManager: Process android.process.acore (pid 3500) has died
08-12 14:07:06.282   874   884 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 30964ms
08-12 14:07:06.298  1751  1751 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-12 14:07:06.298  1751  1751 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-12 14:07:06.304  1751  1751 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-12 14:07:06.304  1751  1751 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
08-12 14:07:06.313  1751  4081 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-12 14:07:06.325  4066  4066 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
08-12 14:07:06.330   874  1966 I ActivityManager: Start proc 4083:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
08-12 14:07:06.332  1997  4080 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-12 14:07:06.350  1751  4081 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-12 14:07:06.350  1751  4081 E AndroidRuntime: Process: com.google.android.gms, PID: 1751
08-12 14:07:06.350  1751  4081 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 14:07:06.350  1751  4081 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 14:07:06.350  1751  4081 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 14:07:06.350  1751  4081 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 14:07:06.350  1751  4081 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 14:07:06.350  1751  4081 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 14:07:06.350  1751  4081 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-12 14:07:06.350  1751  4081 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-12 14:07:06.350  1751  4081 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-12 14:07:06.350  1751  4081 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-12 14:07:06.350  1751  4081 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-12 14:07:06.350  1751  4081 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-12 14:07:06.350  1751  4081 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-12 14:07:06.350  1751  4081 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-12 14:07:06.350  1751  4081 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-12 14:07:06.350  1751  4081 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-12 14:07:06.350  1751  4081 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-12 14:07:06.350  1751  4081 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-12 14:07:06.350  1751  4081 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
08-12 14:07:06.355   874  4094 E DropBoxManagerService: Can't write: system_app_crash
08-12 14:07:06.355   874  4094 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-12 14:07:06.355   874  4094 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 14:07:06.355   874  4094 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 14:07:06.355   874  4094 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 14:07:06.355   874  4094 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 14:07:06.355   874  4094 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 14:07:06.355   874  4094 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 14:07:06.355   874  4094 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 14:07:06.355   874  4094 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 14:07:06.355   874  4094 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 14:07:06.355   874  4094 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 14:07:06.355   874  4094 E DropBoxManagerService: 	... 5 more
08-12 14:07:06.357  1751  4081 I Process : Sending signal. PID: 1751 SIG: 9
08-12 14:07:06.383  1997  4080 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-12 14:07:06.389   278   278 E lowmemorykiller: Error writing /proc/1751/oom_score_adj; errno=22
08-12 14:07:06.399  4066  4066 I MultiDex: VM with version 2.1.0 has multidex support
08-12 14:07:06.400  4066  4066 I MultiDex: install
08-12 14:07:06.400  4066  4066 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-12 14:07:06.403  1997  4080 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-12 14:07:06.404  1997  4080 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-12 14:07:06.404  1997  4080 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1997
08-12 14:07:06.404  1997  4080 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 14:07:06.404  1997  4080 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 14:07:06.404  1997  4080 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-12 14:07:06.404  1997  4080 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 14:07:06.404  1997  4080 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 14:07:06.404  1997  4080 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 14:07:06.404  1997  4080 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-12 14:07:06.404  1997  4080 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-12 14:07:06.404  1997  4080 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-12 14:07:06.404  1997  4080 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-12 14:07:06.404  1997  4080 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-12 14:07:06.404  1997  4080 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-12 14:07:06.404  1997  4080 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-12 14:07:06.404  1997  4080 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-12 14:07:06.404  1997  4080 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-12 14:07:06.404  1997  4080 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-12 14:07:06.404  1997  4080 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 14:07:06.404  1997  4080 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-12 14:07:06.404  1997  4080 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 14:07:06.406   874  1978 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
08-12 14:07:06.406   874  1978 I ActivityManager: Killing 1997:com.google.android.googlequicksearchbox:search/u0a28 (adj 5): crash
08-12 14:07:06.410   874  4096 E DropBoxManagerService: Can't write: system_app_crash
08-12 14:07:06.410   874  4096 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-12 14:07:06.410   874  4096 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-12 14:07:06.410   874  4096 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 14:07:06.410   874  4096 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 14:07:06.410   874  4096 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 14:07:06.410   874  4096 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-12 14:07:06.410   874  4096 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-12 14:07:06.410   874  4096 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 14:07:06.410   874  4096 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 14:07:06.410   874  4096 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 14:07:06.410   874  4096 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-12 14:07:06.410   874  4096 E DropBoxManagerService: 	... 5 more
08-12 14:07:06.435   280   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
