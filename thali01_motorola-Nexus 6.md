#### Test 79751015c29d5b7_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-10 09:30:53.704   875  1308 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-10 09:30:54.380  3654  3654 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-10 09:30:54.384  3654  3654 D AndroidRuntime: CheckJNI is OFF
08-10 09:30:54.420  3654  3654 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-10 09:30:54.458  3654  3654 I Radio-JNI: register_android_hardware_Radio DONE
08-10 09:30:54.475  3654  3654 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-10 09:30:54.479   875  1822 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-10 09:30:54.538  1797  1811 W SearchService: Abort, client detached.
08-10 09:30:54.542  3654  3654 D AndroidRuntime: Shutting down VM
08-10 09:30:54.551  1797  1797 I HotwordDetector: Closing mic
08-10 09:30:54.552  1797  2141 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@fc141fd
08-10 09:30:54.552  1797  2164 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-10 09:30:54.560   875  2068 I ActivityManager: Start proc 3663:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-10 09:30:54.607   374  2166 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-10 09:30:54.608   374  2166 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-10 09:30:54.613   374  1279 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-10 09:30:54.614  1797  2163 I MicroRecognitionRnrImpl: Detection finished
08-10 09:30:54.615  1797  2156 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-10 09:30:54.650  3663  3663 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-10 09:30:54.671  3663  3663 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-10 09:30:54.678  3663  3663 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3286-3288)
08-10 09:30:54.678  3663  3663 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 09:30:54.691  3663  3663 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {29bfccb}
08-10 09:30:54.691  3663  3663 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 09:30:54.691  3663  3663 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-10 09:30:54.697  3663  3663 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-10 09:30:54.698  3663  3663 E SysUtils: ApplicationContext is null in ApplicationStatus
08-10 09:30:54.713  3663  3663 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-10 09:30:54.725  3663  3663 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 09:30:54.725  3663  3663 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 09:30:54.725  3663  3663 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 09:30:54.725  3663  3663 I Adreno  : Build Date                       : 10/20/15
08-10 09:30:54.725  3663  3663 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 09:30:54.725  3663  3663 I Adreno  : Local Branch                     : M14
08-10 09:30:54.725  3663  3663 I Adreno  : Remote Branch                    : 
08-10 09:30:54.725  3663  3663 I Adreno  : Remote Branch                    : 
08-10 09:30:54.725  3663  3663 I Adreno  : Reconstruct Branch               : 
08-10 09:30:54.784   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d245cf2:true
,08-10 09:30:54.836  3663  3663 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-10 09:30:54.852  3663  3663 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-10 09:30:54.934  3663  3702 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-10 09:30:54.948  3663  3688 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-10 09:30:54.992  3663  3702 I OpenGLRenderer: Initialized EGL, version 1.4
,08-10 09:30:55.104   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +561ms
,08-10 09:30:55.110  1641  1641 I Keyboard.Facilitator: onFinishInput()
,08-10 09:30:55.171  3663  3663 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3663
,08-10 09:30:55.303  3663  3663 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-10 09:30:55.361   875  1374 I ActivityManager: Killing 3073:com.google.android.gm/u0a78 (adj 15): empty #17
,08-10 09:30:55.404   875  1374 I ActivityManager: Killing 2949:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,08-10 09:30:55.484  3663  3705 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1681458896
,08-10 09:30:55.490  3663  3705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-10 09:30:55.490  3663  3705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-10 09:30:55.490  3663  3705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-10 09:30:55.490  3663  3705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-10 09:30:55.490  3663  3705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-10 09:30:55.490  3663  3705 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e651b5f added. We now have 1 listener(s)
,08-10 09:30:55.494  3663  3705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-10 09:30:55.496  3663  3705 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 09:30:55.496  3663  3705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 09:30:55.496  3663  3705 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 09:30:55.499  3663  3705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-10 09:30:55.499  3663  3705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-10 09:30:55.499  3663  3705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-10 09:30:55.499  3663  3705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-10 09:30:55.499  3663  3705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-10 09:30:55.499  3663  3705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-10 09:30:55.499  3663  3705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-10 09:30:55.499  3663  3705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-10 09:30:55.499  3663  3705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-10 09:30:55.499  3663  3705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-10 09:30:55.499  3663  3705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-10 09:30:55.499  3663  3705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-10 09:30:55.499  3663  3705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-10 09:30:55.499  3663  3705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-10 09:30:55.499  3663  3705 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fd460a added. We now have 1 listener(s)
08-10 09:30:55.499  3663  3705 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 09:30:55.501   875  1309 D WifiService: New client listening to asynchronous messages
,08-10 09:30:55.502  3663  3705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 09:30:55.503  3663  3705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-10 09:30:55.503  3663  3705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-10 09:30:55.503  3663  3705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-10 09:30:55.503  3663  3705 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-10 09:30:55.505  3663  3705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 09:30:55.505  3663  3705 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-10 09:30:55.512  3663  3705 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-10 09:30:55.512  3663  3705 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 09:30:55.512  3663  3705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:30:55.512  3663  3705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:30:55.512  3663  3705 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:30:55.512  3663  3705 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 09:30:55.512  3663  3705 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 09:30:55.512  3663  3705 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 09:30:55.512  3663  3705 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 09:30:55.513  3663  3705 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-10 09:30:55.513  3663  3705 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 09:30:55.513  3663  3705 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-10 09:30:55.612  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:30:55.614  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:30:55.616  3663  3663 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-10 09:30:56.518  3663  3713 W jxcore-log: Initializing JXcore engine
,08-10 09:30:56.519  3663  3713 W jxcore-log: JXcore engine is ready
,08-10 09:30:56.557  3713  3713 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8984 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-10 09:30:56.557  3713  3713 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9612]" dev="sockfs" ino=9612 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-10 09:30:56.557  3713  3713 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-10 09:30:56.557  3713  3713 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25131]" dev="sockfs" ino=25131 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-10 09:30:56.573  3663  3713 W jxcore-log: Starting JXcore engine
,08-10 09:30:56.670  3663  3713 W jxcore-log: Platform android
08-10 09:30:56.670  3663  3713 W jxcore-log: 
08-10 09:30:56.672  3663  3713 W jxcore-log: Process ARCH arm
08-10 09:30:56.672  3663  3713 W jxcore-log: 
,08-10 09:30:56.984  3663  3713 I jxcore-log: JXcore Cordova bridge is ready!
08-10 09:30:56.984  3663  3713 I jxcore-log: 
08-10 09:30:56.984  3663  3713 W jxcore-log: JXcore engine is started
,08-10 09:30:56.992  3663  3705 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-10 09:30:56.996  3663  3663 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-10 09:30:58.820  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:30:58.824  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:30:58.877  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 09:30:58.877  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-10 09:30:58.877  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 09:30:58.878  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:30:58.895  3426  3716 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 09:30:58.895  3426  3716 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 09:30:58.895  3426  3716 E HttpOperation: 	at jdm.a(PG:82)
08-10 09:30:58.895  3426  3716 E HttpOperation: 	at jcs.o(PG:406)
08-10 09:30:58.895  3426  3716 E HttpOperation: 	at jcn.a(PG:1379)
08-10 09:30:58.895  3426  3716 E HttpOperation: 	at jcs.i(PG:143)
08-10 09:30:58.895  3426  3716 E HttpOperation: 	at blb.a(PG:3937)
08-10 09:30:58.895  3426  3716 E HttpOperation: 	at czp.a(PG:18188)
08-10 09:30:58.895  3426  3716 E HttpOperation: 	at czp.a(PG:9081)
08-10 09:30:58.895  3426  3716 E HttpOperation: 	at czq.run(PG:1686)
08-10 09:30:58.895  3426  3716 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:30:58.895  3426  3716 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:30:58.895  3426  3716 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:30:58.895  3426  3716 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:30:58.895  3426  3716 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:30:58.895  3426  3716 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:30:58.895  3426  3716 E HttpOperation: 	at jdj.a(PG:4091)
08-10 09:30:58.895  3426  3716 E HttpOperation: 	at jdj.a(PG:1125)
08-10 09:30:58.895  3426  3716 E HttpOperation: 	at jdm.a(PG:77)
08-10 09:30:58.895  3426  3716 E HttpOperation: 	... 12 more
08-10 09:30:58.895  3426  3716 E HttpOperation: Caused by: faj: BadAuthentication
08-10 09:30:58.895  3426  3716 E HttpOperation: 	at fal.a(PG:38)
08-10 09:30:58.895  3426  3716 E HttpOperation: 	at jdj.a(PG:4089)
08-10 09:30:58.895  3426  3716 E HttpOperation: 	... 14 more
,08-10 09:30:58.975  1520  1941 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 09:30:58.975  1520  1941 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 09:30:58.975  1520  1941 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:30:58.975  1520  1941 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:30:58.990  3426  3716 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 09:30:58.990  3426  3716 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 09:30:58.990  3426  3716 E HttpOperation: 	at jdm.a(PG:82)
08-10 09:30:58.990  3426  3716 E HttpOperation: 	at jcs.o(PG:406)
08-10 09:30:58.990  3426  3716 E HttpOperation: 	at jcn.a(PG:1379)
08-10 09:30:58.990  3426  3716 E HttpOperation: 	at jcs.i(PG:143)
08-10 09:30:58.990  3426  3716 E HttpOperation: 	at hec.a(PG:42)
08-10 09:30:58.990  3426  3716 E HttpOperation: 	at hee.a(PG:102)
08-10 09:30:58.990  3426  3716 E HttpOperation: 	at czr.a(PG:65)
08-10 09:30:58.990  3426  3716 E HttpOperation: 	at kka.a(PG:108)
08-10 09:30:58.990  3426  3716 E HttpOperation: 	at czp.a(PG:19176)
08-10 09:30:58.990  3426  3716 E HttpOperation: ,	at czp.a(PG:9081)
08-10 09:30:58.990  3426  3716 E HttpOperation: 	at czq.run(PG:1686)
08-10 09:30:58.990  3426  3716 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:30:58.990  3426  3716 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:30:58.990  3426  3716 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:30:58.990  3426  3716 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:30:58.990  3426  3716 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:30:58.990  3426  3716 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:30:58.990  3426  3716 E HttpOperation: 	at jdj.a(PG:4091)
08-10 09:30:58.990  3426  3716 E HttpOperation: 	at jdj.a(PG:1125)
08-10 09:30:58.990  3426  3716 E HttpOperation: 	at jdm.a(PG:77)
08-10 09:30:58.990  3426  3716 E HttpOperation: 	... 15 more
08-10 09:30:58.990  3426  3716 E HttpOperation: Caused by: faj: BadAuthentication
08-10 09:30:58.990  3426  3716 E HttpOperation: 	at fal.a(PG:38)
08-10 09:30:58.990  3426  3716 E HttpOperation: 	at jdj.a(PG:4089)
08-10 09:30:58.990  3426  3716 E HttpOperation: 	... 17 more
,08-10 09:30:58.990  3426  3716 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 09:30:58.990  3426  3716 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	at hec.a(PG:42)
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	at hee.a(PG:102)
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	at czr.a(PG:65)
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	at kka.a(PG:108)
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:30:58.990  3426  3716 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	... 15 more
08-10 09:30:58.990  3426  3716 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	at fal.a(PG:38)
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 09:30:58.990  3426  3716 E ExperimentLoader: 	... 17 more
,08-10 09:30:59.072   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 127186, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 09:30:59.787  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:30:59.824  1520  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 09:30:59.825  1520  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 09:30:59.825  1520  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:30:59.825  1520  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:30:59.847  3385  3385 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
08-10 09:30:59.847  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-10 09:30:59.847  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-10 09:31:13.283  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-10 09:31:13.283  3663  3713 I jxcore-log: 
,08-10 09:31:13.285  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-10 09:31:13.285  3663  3713 I jxcore-log: 
,08-10 09:31:13.295  3663  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 09:31:13.295  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:13.295  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:13.295  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:13.295  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 09:31:13.295  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 09:31:13.295  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 09:31:13.295  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 09:31:13.299  3663  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 09:31:13.302  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-10 09:31:13.302  3663  3713 I jxcore-log: 
,08-10 09:31:13.304  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-10 09:31:13.304  3663  3713 I jxcore-log: 
,08-10 09:31:13.643  3663  3713 D ExecuteNativeTests: Running unit tests
,08-10 09:31:13.702  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 09:31:13.703  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f added. We now have 2 listener(s)
,08-10 09:31:13.704  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 09:31:13.704  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 09:31:13.704  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 09:31:13.705  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 09:31:13.705  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c added. We now have 2 listener(s)
,08-10 09:31:13.705  3663  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 09:31:13.706  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 09:31:13.709  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 09:31:13.718  3663  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 09:31:13.718  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:13.718  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:13.718  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:13.718  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 09:31:13.718  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 09:31:13.718  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 09:31:13.718  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 09:31:13.724  3663  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-10 09:31:13.725  3663  3713 D io.jxcore.node.ConnectivityMonitor: start: OK,
,08-10 09:31:13.732  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-10 09:31:13.734  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-10 09:31:13.736  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:13.739  3663  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-10 09:31:13.739  3663  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-10 09:31:13.744  3663  3713 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-10 09:31:13.745  3663  3713 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-10 09:31:13.745  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-10 09:31:13.746  3663  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 09:31:13.746  3663  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 09:31:13.747  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-10 09:31:13.748  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:13.748  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 09:31:13.748  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:13.748  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.748  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 09:31:13.749  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 09:31:13.749  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f removed from the list
08-10 09:31:13.749  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 09:31:13.749  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c removed from the list
,08-10 09:31:13.749  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:13.749  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.750  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.750  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.752  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-10 09:31:13.752  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:13.752  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:13.752  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
,08-10 09:31:13.754  3663  3713 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-10 09:31:13.755  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 09:31:13.755  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:13.755  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-10 09:31:13.756  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:13.756  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.756  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.756  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
,08-10 09:31:13.756  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:13.756  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:13.756  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:13.756  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.756  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.756  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 09:31:13.756  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.758  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:13.758  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:13.758  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 09:31:13.758  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
,08-10 09:31:13.763  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-10 09:31:13.763  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 09:31:13.763  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-10 09:31:13.764  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-10 09:31:13.764  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 09:31:13.764  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-10 09:31:13.764  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-10 09:31:13.764  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-10 09:31:13.764  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 09:31:13.764  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 09:31:13.764  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-10 09:31:13.764  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 09:31:13.764  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-10 09:31:13.764  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,08-10 09:31:13.764  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 09:31:13.764  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-10 09:31:13.764  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-10 09:31:13.764  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-10 09:31:13.765  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 09:31:13.765  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-10 09:31:13.765  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 09:31:13.765  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 09:31:13.765  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-10 09:31:13.765  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-10 09:31:13.765  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 09:31:13.765  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 09:31:13.765  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-10 09:31:13.765  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-10 09:31:13.765  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710],
08-10 09:31:13.765  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 09:31:13.765  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-10 09:31:13.765  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 09:31:13.766  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:13.766  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-10 09:31:13.766  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:13.766  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.766  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.766  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
08-10 09:31:13.766  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:13.766  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:13.766  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:13.766  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.766  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-10 09:31:13.766  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.767  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.768  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:13.768  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:13.768  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:13.768  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:13.769  3663  3713 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-10 09:31:13.770  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 09:31:13.776  3663  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 09:31:13.776  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:13.776  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:13.776  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:13.776  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 09:31:13.776  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 09:31:13.776  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 09:31:13.776  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 09:31:13.778  3663  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 09:31:13.779  3663  3713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 09:31:13.779  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 09:31:13.779  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-10 09:31:13.779  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 09:31:13.779  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 09:31:13.779  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-10 09:31:13.782  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:13.783  3663  3713 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-10 09:31:13.783  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 09:31:13.785  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:13.790  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 09:31:13.792  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-10 09:31:13.792  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-10 09:31:13.795  3663  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-10 09:31:13.798  3663  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,08-10 09:31:13.798  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-10 09:31:13.798  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-10 09:31:13.799  3663  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-10 09:31:13.801  3663  3713 D BluetoothAdapter: STATE_ON
,08-10 09:31:13.806  2561  2768 D BtGatt.GattService: registerClient() - UUID=cf47e3fe-59f8-44cc-a6a7-4f8f3e1d7480
,08-10 09:31:13.807  2561  2612 D BtGatt.GattService: onClientRegistered() - UUID=cf47e3fe-59f8-44cc-a6a7-4f8f3e1d7480, clientIf=5
,08-10 09:31:13.808  3663  3675 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-10 09:31:13.809  2561  2767 D BtGatt.GattService: start scan with filters
,08-10 09:31:13.812  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-10 09:31:13.813  2561  2616 D BtGatt.ScanManager: handling starting scan
08-10 09:31:13.813  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-10 09:31:13.813  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-10 09:31:13.813  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-10 09:31:13.818  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-10 09:31:13.818  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-10 09:31:13.818  3663  3663 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 09:31:13.818  2561  2616 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e34fafd
08-10 09:31:13.819  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-10 09:31:13.821  3663  3713 I io.jxcore.node.ConnectionHelper: start: OK
,08-10 09:31:13.825  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 09:31:13.825  3663  3713 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-10 09:31:13.825  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:13.825  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-10 09:31:13.825  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.825  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 09:31:13.825  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 09:31:13.825  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 09:31:13.826  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 09:31:13.826  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 09:31:13.826  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 09:31:13.826  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-10 09:31:13.827  3663  3713 D BluetoothAdapter: STATE_ON
,08-10 09:31:13.828  2561  2768 D BtGatt.GattService: stopScan() - queue size =1
,08-10 09:31:13.829  2561  2767 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-10 09:31:13.830  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 09:31:13.830  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-10 09:31:13.830  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-10 09:31:13.830  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-10 09:31:13.830  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-10 09:31:13.831  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 09:31:13.831  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-10 09:31:13.832  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 09:31:13.832  2561  2612 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-10 09:31:13.832  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-10 09:31:13.832  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:13.832  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 09:31:13.833  2561  2616 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-10 09:31:13.833  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:13.833  3663  3663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 09:31:13.833  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.833  3663  3663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 09:31:13.833  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 09:31:13.834  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
08-10 09:31:13.834  3663  3663 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 09:31:13.834  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:13.834  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:13.834  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:13.834  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.834  3663  3713 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-10 09:31:13.836  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 09:31:13.844  3663  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 09:31:13.844  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:13.844  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:13.844  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:13.844  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 09:31:13.844  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 09:31:13.844  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 09:31:13.844  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 09:31:13.847  3663  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 09:31:13.848  2561  2612 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-10 09:31:13.848  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:13.848  3663  3713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 09:31:13.848  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 09:31:13.848  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 09:31:13.848  2561  2616 D BtGatt.ScanManager: Starting BLE batch scan
08-10 09:31:13.848  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 09:31:13.848  2561  2616 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-10 09:31:13.848  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 09:31:13.849  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-10 09:31:13.852  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:13.853  3663  3713 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-10 09:31:13.853  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 09:31:13.854  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:13.858  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 09:31:13.859  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-10 09:31:13.859  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-10 09:31:13.862  2561  2612 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-10 09:31:13.863  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:13.863  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-10 09:31:13.863  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-10 09:31:13.863  3663  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-10 09:31:13.864  3663  3713 D BluetoothAdapter: STATE_ON
,08-10 09:31:13.866  2561  2768 D BtGatt.GattService: registerClient() - UUID=e200f944-c461-4413-b46b-7dbb5ef9fc8b
08-10 09:31:13.866  2561  2612 D BtGatt.GattService: onClientRegistered() - UUID=e200f944-c461-4413-b46b-7dbb5ef9fc8b, clientIf=5
,08-10 09:31:13.867  3663  3673 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-10 09:31:13.867  2561  2767 D BtGatt.GattService: start scan with filters
08-10 09:31:13.869  2561  2612 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-10 09:31:13.869  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 09:31:13.870  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-10 09:31:13.870  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-10 09:31:13.870  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-10 09:31:13.870  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-10 09:31:13.872  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 09:31:13.873  3663  3663 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-10 09:31:13.875  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-10 09:31:13.877  2561  2612 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-10 09:31:13.877  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:13.877  2561  2616 D BtGatt.ScanManager: stopping BLe Batch
,08-10 09:31:13.883  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-10 09:31:13.888  3663  3713 I io.jxcore.node.ConnectionHelper: start: OK
,08-10 09:31:13.891  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 09:31:13.891  3663  3713 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-10 09:31:13.891  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-10 09:31:13.892  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-10 09:31:13.892  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 09:31:13.892  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-10 09:31:13.892  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-10 09:31:13.892  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-10 09:31:13.892  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
,08-10 09:31:13.892  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-10 09:31:13.892  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 09:31:13.892  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-10 09:31:13.892  2561  2612 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-10 09:31:13.892  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 09:31:13.893  2561  2616 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-10 09:31:13.894  3663  3713 D BluetoothAdapter: STATE_ON
,08-10 09:31:13.895  2561  2768 D BtGatt.GattService: stopScan() - queue size =0
08-10 09:31:13.895  2561  2576 D BtGatt.GattService: unregisterClient() - clientIf=5
08-10 09:31:13.896  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 09:31:13.896  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-10 09:31:13.896  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-10 09:31:13.896  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-10 09:31:13.896  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-10 09:31:13.897  2561  2612 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-10 09:31:13.897  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:13.898  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 09:31:13.898  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-10 09:31:13.898  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 09:31:13.898  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 09:31:13.898  2561  2616 D BtGatt.ScanManager: handling starting scan
08-10 09:31:13.899  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 09:31:13.900  3663  3663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 09:31:13.900  3663  3663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 09:31:13.900  3663  3663 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-10 09:31:13.900  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:13.900  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 09:31:13.900  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 09:31:13.900  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
08-10 09:31:13.900  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:13.900  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:13.900  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:13.901  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 09:31:13.901  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.901  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.903  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:13.903  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 09:31:13.903  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 09:31:13.903  2561  2612 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-10 09:31:13.903  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:13.903  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:13.903  2561  2616 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-10 09:31:13.904  3663  3713 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-10 09:31:13.905  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 09:31:13.910  2561  2612 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-10 09:31:13.910  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:13.910  2561  2616 D BtGatt.ScanManager: Starting BLE batch scan
08-10 09:31:13.910  2561  2616 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-10 09:31:13.910  3663  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 09:31:13.910  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:13.910  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:13.910  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:13.910  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 09:31:13.910  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 09:31:13.910  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 09:31:13.910  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 09:31:13.913  3663  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 09:31:13.914  3663  3713 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-10 09:31:13.915  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 09:31:13.915  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 09:31:13.915  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 09:31:13.915  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 09:31:13.915  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-10 09:31:13.916  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:13.920  2561  2612 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-10 09:31:13.920  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 09:31:13.920  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:13.921  3663  3713 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-10 09:31:13.921  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-10 09:31:13.925  2561  2612 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-10 09:31:13.925  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 09:31:13.929  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 09:31:13.930  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-10 09:31:13.930  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-10 09:31:13.933  2561  2612 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-10 09:31:13.933  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:13.934  2561  2616 D BtGatt.ScanManager: stopping BLe Batch
,08-10 09:31:13.939  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-10 09:31:13.939  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-10 09:31:13.940  3663  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-10 09:31:13.940  3663  3713 D BluetoothAdapter: STATE_ON
,08-10 09:31:13.950  2561  2576 D BtGatt.GattService: registerClient() - UUID=0253482e-7c94-487d-b227-b41db937a016
,08-10 09:31:13.950  2561  2612 D BtGatt.GattService: onClientRegistered() - UUID=0253482e-7c94-487d-b227-b41db937a016, clientIf=5
08-10 09:31:13.951  3663  3675 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-10 09:31:13.951  2561  2574 D BtGatt.GattService: start scan with filters
,08-10 09:31:13.951  2561  2612 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-10 09:31:13.952  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 09:31:13.952  2561  2616 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-10 09:31:13.953  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-10 09:31:13.954  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-10 09:31:13.954  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-10 09:31:13.954  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-10 09:31:13.957  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 09:31:13.957  2561  2612 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-10 09:31:13.957  3663  3663 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 09:31:13.957  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:13.957  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-10 09:31:13.958  2561  2616 D BtGatt.ScanManager: handling starting scan
08-10 09:31:13.959  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-10 09:31:13.961  3663  3713 I io.jxcore.node.ConnectionHelper: start: OK
,08-10 09:31:13.961  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 09:31:13.961  3663  3713 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-10 09:31:13.961  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-10 09:31:13.961  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-10 09:31:13.962  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.962  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-10 09:31:13.962  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 09:31:13.962  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 09:31:13.962  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 09:31:13.962  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 09:31:13.962  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-10 09:31:13.963  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-10 09:31:13.963  2561  2612 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-10 09:31:13.964  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:13.964  3663  3713 D BluetoothAdapter: STATE_ON
,08-10 09:31:13.964  2561  2616 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-10 09:31:13.964  2561  2574 D BtGatt.GattService: stopScan() - queue size =1
08-10 09:31:13.965  2561  2767 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-10 09:31:13.965  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 09:31:13.965  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-10 09:31:13.965  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-10 09:31:13.966  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-10 09:31:13.966  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-10 09:31:13.967  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 09:31:13.967  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-10 09:31:13.967  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 09:31:13.967  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-10 09:31:13.968  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 09:31:13.969  3663  3663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 09:31:13.969  3663  3663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 09:31:13.969  3663  3663 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 09:31:13.969  2561  2612 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-10 09:31:13.970  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 09:31:13.970  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:13.970  3663  3713 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-10 09:31:13.970  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:13.970  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 09:31:13.970  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 09:31:13.970  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.970  2561  2616 D BtGatt.ScanManager: Starting BLE batch scan
08-10 09:31:13.970  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 09:31:13.970  2561  2616 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-10 09:31:13.970  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
08-10 09:31:13.970  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 09:31:13.971  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
,08-10 09:31:13.971  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 09:31:13.971  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.971  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 09:31:13.971  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.972  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:13.972  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:13.972  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 09:31:13.972  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:13.973  3663  3713 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-10 09:31:13.973  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 09:31:13.974  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:13.974  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 09:31:13.974  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 09:31:13.974  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.974  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.974  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
08-10 09:31:13.974  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:13.974  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:13.974  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 09:31:13.974  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.974  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.974  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.975  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 09:31:13.975  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:13.976  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:13.976  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 09:31:13.976  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
,08-10 09:31:13.977  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 09:31:13.977  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 09:31:13.977  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:13.977  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 09:31:13.977  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:13.977  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.977  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 09:31:13.977  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
08-10 09:31:13.978  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:13.978  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:13.978  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 09:31:13.978  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.978  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.978  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 09:31:13.978  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.979  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:13.979  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 09:31:13.979  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:13.979  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:13.980  3663  3713 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-10 09:31:13.980  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 09:31:13.980  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:13.980  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 09:31:13.980  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:13.980  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.981  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.981  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
08-10 09:31:13.981  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 09:31:13.981  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:13.981  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:13.981  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 09:31:13.981  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.981  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.981  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.981  2561  2612 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-10 09:31:13.981  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:13.982  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:13.983  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:13.983  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 09:31:13.983  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:13.984  3663  3713 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-10 09:31:13.984  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 09:31:13.984  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:13.984  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 09:31:13.984  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 09:31:13.984  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.984  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.984  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
08-10 09:31:13.984  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:13.985  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:13.985  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:13.985  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 09:31:13.985  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.985  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.985  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.986  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:13.986  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 09:31:13.986  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:13.986  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:13.987  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 09:31:13.987  2561  2612 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-10 09:31:13.987  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 09:31:13.988  3663  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-10 09:31:13.989  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 09:31:13.989  3663  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 09:31:13.992  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-10 09:31:13.992  3663  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-10 09:31:13.992  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 09:31:13.992  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:13.992  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 09:31:13.992  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:13.993  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.993  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 09:31:13.993  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
08-10 09:31:13.993  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:13.993  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:13.993  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:13.993  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.993  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:13.993  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:13.993  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 09:31:13.994  2561  2612 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-10 09:31:13.994  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:13.994  2561  2616 D BtGatt.ScanManager: stopping BLe Batch
08-10 09:31:13.999  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:13.999  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:13.999  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 09:31:14.000  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
,08-10 09:31:14.000  2561  2612 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-10 09:31:14.000  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:14.000  2561  2616 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-10 09:31:14.005  3663  3713 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 09:31:14.005  3663  3713 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,08-10 09:31:14.005  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-10 09:31:14.006  2561  2612 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-10 09:31:14.006  2561  2612 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 09:31:14.008  3663  3713 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-10 09:31:14.009  3663  3713 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-10 09:31:14.009  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-10 09:31:14.009  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-10 09:31:14.009  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,08-10 09:31:14.009  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-10 09:31:14.009  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-10 09:31:14.009  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-10 09:31:14.009  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-10 09:31:14.009  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-10 09:31:14.009  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-10 09:31:14.009  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-10 09:31:14.009  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-10 09:31:14.009  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-10 09:31:14.010  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-10 09:31:14.010  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-10 09:31:14.010  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-10 09:31:14.010  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,08-10 09:31:14.010  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-10 09:31:14.010  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-10 09:31:14.010  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-10 09:31:14.010  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-10 09:31:14.010  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-10 09:31:14.010  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-10 09:31:14.010  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-10 09:31:14.010  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-10 09:31:14.010  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-10 09:31:14.010  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-10 09:31:14.010  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-10 09:31:14.010  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-10 09:31:14.010  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-10 09:31:14.010  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,08-10 09:31:14.010  3663  3713 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-10 09:31:14.011  3663  3713 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 09:31:14.011  3663  3713 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-10 09:31:14.011  3663  3713 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 09:31:14.011  3663  3713 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 09:31:14.011  3663  3713 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-10 09:31:14.011  3663  3713 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 09:31:14.011  3663  3713 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-10 09:31:14.011  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-10 09:31:14.014  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-10 09:31:14.014  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-10 09:31:14.015  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-10 09:31:14.015  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-10 09:31:14.015  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-10 09:31:14.015  3663  3713 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-10 09:31:14.015  3663  3713 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-10 09:31:14.015  3663  3713 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-10 09:31:14.016  3663  3728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
08-10 09:31:14.016  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 09:31:14.016  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:14.016  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 09:31:14.016  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:14.016  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.016  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.016  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-10 09:31:14.017  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
08-10 09:31:14.017  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:14.017  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:14.017  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:14.018  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.018  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.018  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.018  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.018  3663  3728 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 09:31:14.019  3663  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
08-10 09:31:14.019  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:14.019  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:14.019  3663  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 393)
08-10 09:31:14.019  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:14.019  3663  3729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 393)
08-10 09:31:14.019  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:14.020  3663  3713 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-10 09:31:14.020  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 09:31:14.020  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:14.020  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 09:31:14.020  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:14.020  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.020  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.020  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
08-10 09:31:14.020  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:14.021  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:14.021  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:14.021  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.021  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.021  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.021  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.022  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:14.022  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:14.022  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:14.022  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:14.022  3663  3713 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-10 09:31:14.022  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 09:31:14.021  3663  3728 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
08-10 09:31:14.023  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:14.023  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 09:31:14.023  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:14.023  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.023  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.023  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
08-10 09:31:14.023  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:14.023  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:14.023  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:14.023  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.023  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.023  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.023  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.025  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:14.025  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:14.025  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:14.025  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:14.025  3663  3713 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-10 09:31:14.025  3663  3713 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-10 09:31:14.026  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 09:31:14.026  3663  3713 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-10 09:31:14.026  3663  3713 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-10 09:31:14.026  3663  3713 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-10 09:31:14.026  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 09:31:14.026  3663  3713 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-10 09:31:14.026  3663  3713 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-10 09:31:14.026  3663  3713 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-10 09:31:14.026  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 09:31:14.026  3663  3713 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-10 09:31:14.026  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 09:31:14.026  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:14.026  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 09:31:14.027  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:14.027  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.027  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.027  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
08-10 09:31:14.027  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:14.027  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:14.027  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:14.027  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.027  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.027  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.027  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.028  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:14.028  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:14.028  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:14.029  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:14.029  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:14.029  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.029  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.029  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
08-10 09:31:14.029  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:14.029  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:14.029  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:14.029  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.029  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.030  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:14.030  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:14.030  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:14.030  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.030  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.030  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
08-10 09:31:14.030  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 09:31:14.030  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:14.030  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 09:31:14.030  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:14.030  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.030  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.030  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
08-10 09:31:14.030  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:14.030  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:14.030  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:14.030  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.031  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.031  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.031  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.032  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:14.032  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:14.032  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:14.032  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:14.033  3663  3713 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-10 09:31:14.033  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 09:31:14.034  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-10 09:31:14.034  3663  3713 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-10 09:31:14.034  3663  3713 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-10 09:31:14.035  3663  3663 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-10 09:31:14.035  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-10 09:31:14.035  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-10 09:31:14.035  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:14.035  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-10 09:31:14.035  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-10 09:31:14.035  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-10 09:31:14.035  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.035  3663  3713 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-10 09:31:14.035  3663  3663 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-10 09:31:14.036  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
08-10 09:31:14.036  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:14.036  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 09:31:14.036  3663  3730 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 09:31:14.036  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 09:31:14.036  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 09:31:14.036  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.036  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.037  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 09:31:14.037  3663  3663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 09:31:14.037  3663  3663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 09:31:14.037  3663  3663 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 09:31:14.037  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:14.037  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 09:31:14.037  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:14.037  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 09:31:14.037  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:14.037  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.037  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.037  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
08-10 09:31:14.038  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:14.038  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:14.038  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:14.038  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.038  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.038  3663  3730 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-10 09:31:14.038  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.038  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.038  3663  3730 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-10 09:31:14.038  3663  3730 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-10 09:31:14.038  3663  3663 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-10 09:31:14.038  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:14.039  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:14.039  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:14.039  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:14.040  3663  3713 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-10 09:31:14.040  3663  3713 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-10 09:31:14.040  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-10 09:31:14.041  3663  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-10 09:31:14.041  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 09:31:14.042  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:14.042  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 09:31:14.042  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:14.042  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.042  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.043  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
08-10 09:31:14.043  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:14.043  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:14.043  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:14.043  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.043  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.043  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.043  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.044  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:14.044  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:14.044  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:14.045  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:14.047  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 09:31:14.047  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:14.047  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 09:31:14.047  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:14.047  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.048  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.048  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
08-10 09:31:14.048  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:14.048  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:14.048  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:14.048  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.048  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.048  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.048  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.049  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:14.049  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:14.049  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:14.049  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:14.049  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 09:31:14.049  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:14.049  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 09:31:14.050  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:14.050  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.050  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.050  3663  3713 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@876ae1f not in the list
08-10 09:31:14.050  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:14.050  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:14.050  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:14.050  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.050  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.050  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:14.050  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:14.051  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:14.051  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:14.051  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:14.051  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e8fc56c not in the list
08-10 09:31:14.051  3663  3713 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-10 09:31:14.051  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 09:31:14.052  3663  3713 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-10 09:31:14.052  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-10 09:31:14.052  3663  3713 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-10 09:31:14.052  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-10 09:31:14.053  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-10 09:31:14.053  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-10 09:31:14.054  3663  3713 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-10 09:31:14.054  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 09:31:14.054  3663  3713 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-10 09:31:14.054  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-10 09:31:14.054  3663  3713 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-10 09:31:14.054  3663  3713 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-10 09:31:14.054  3663  3713 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-10 09:31:14.054  3663  3713 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-10 09:31:14.055  3663  3713 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-10 09:31:14.055  3663  3713 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-10 09:31:14.055  3663  3713 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-10 09:31:14.055  3663  3713 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-10 09:31:14.055  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 09:31:14.056  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@521226e added. We now have 2 listener(s)
08-10 09:31:14.056  3663  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 09:31:14.057  3663  3713 D BluetoothAdapter: enable(): BT is already enabled..!
08-10 09:31:14.057   875  2065 D WifiService: setWifiEnabled: true pid=3663, uid=10000
08-10 09:31:14.057   875  2065 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-10 09:31:14.058  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 09:31:14.058  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6ad5d0f added. We now have 3 listener(s)
08-10 09:31:14.058  3663  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 09:31:14.061  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 09:31:14.061  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c5619c added. We now have 4 listener(s)
08-10 09:31:14.062  3663  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 09:31:14.062  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 09:31:14.063  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c7047a5 added. We now have 5 listener(s)
08-10 09:31:14.063  3663  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 09:31:14.064   875  2066 D WifiService: setWifiEnabled: false pid=3663, uid=10000
08-10 09:31:14.064   875  2066 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-10 09:31:14.069  2561  2608 D BluetoothAdapterState: Current state: ON, message: 23
08-10 09:31:14.069  2561  2608 D BluetoothAdapterProperties: Setting state to 13
08-10 09:31:14.069  2561  2608 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-10 09:31:14.069  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 09:31:14.069  2561  2608 D BluetoothAdapterProperties: onBluetoothDisable()
08-10 09:31:14.071  2561  2608 I BluetoothAdapterState: Entering PendingCommandState
08-10 09:31:14.071  2561  2561 D BluetoothMapService: onReceive
08-10 09:31:14.072  2561  2561 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 09:31:14.072  2561  2561 D BluetoothMapService: STATE_TURNING_OFF
08-10 09:31:14.072  2561  2561 D BluetoothMapService: MAP Service closeService in
08-10 09:31:14.072  2561  2561 D BluetoothMapMasInstance0: MAP Service shutdown
08-10 09:31:14.072  2561  2561 D ObexServerSockets0: shutdown(block = true)
08-10 09:31:14.073  2561  2561 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-10 09:31:14.073  2561  2561 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-10 09:31:14.073  2561  2752 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-10 09:31:14.073  2561  2770 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-10 09:31:14.073  2561  2769 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-10 09:31:14.074  2561  2561 I BtOppRfcommListener: stopping Accept Thread
08-10 09:31:14.074  2561  3279 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 09:31:14.074  2561  3279 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-10 09:31:14.075  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 09:31:14.075  3663  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 09:31:14.075  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:14.075  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:14.075  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:14.075  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 09:31:14.075  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 09:31:14.075  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 09:31:14.075  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 09:31:14.076  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 09:31:14.076  3663  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 09:31:14.076  3663  3713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 09:31:14.078  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:14.078  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-10 09:31:14.080  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:14.081   875  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-10 09:31:14.081   875  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-10 09:31:14.081   875  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-10 09:31:14.081   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 09:31:14.082  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 09:31:14.082  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 09:31:14.082  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:14.082  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:14.082  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:14.082  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 09:31:14.082  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 09:31:14.082  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 09:31:14.082  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 09:31:14.083  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 09:31:14.083  3663  3663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 09:31:14.087  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 09:31:14.088   875  1987 D DhcpClient: Clearing IP address
08-10 09:31:14.089   370   873 D CommandListener: Clearing all IP addresses on wlan0
08-10 09:31:14.091   875   888 I ActivityManager: Start proc 3733:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-10 09:31:14.091   370   873 D CommandListener: Setting iface cfg
08-10 09:31:14.091  2561  2612 D BluetoothAdapterProperties: Scan Mode:20
08-10 09:31:14.091  2561  2608 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-10 09:31:14.093  1520  2315 V NativeCrypto: Read error: ssl=0x9b6a2800: I/O error during system call, Connection timed out
,08-10 09:31:14.095  2561  2561 D HeadsetService: Received stop request...Stopping profile...
08-10 09:31:14.096   875   875 D BluetoothHeadset: Proxy object disconnected
08-10 09:31:14.097   875   875 D BluetoothHeadset: Proxy object disconnected
08-10 09:31:14.097  1362  1969 D BluetoothHeadset: Proxy object disconnected
08-10 09:31:14.097   875  1308 D WifiStateMachine: Start Disconnecting Watchdog 1
08-10 09:31:14.097  1362  1362 D HeadsetProfile: Bluetooth service disconnected
08-10 09:31:14.097  1520  2315 V NativeCrypto: SSL shutdown failed: ssl=0x9b6a2800: I/O error during system call, Broken pipe
08-10 09:31:14.098   875  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-10 09:31:14.098   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-10 09:31:14.098   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-10 09:31:14.098  1735  1763 D BluetoothHeadset: Proxy object disconnected
,08-10 09:31:14.099   875   875 D BluetoothHeadset: Proxy object disconnected
08-10 09:31:14.101  2561  2561 D A2dpService: Received stop request...Stopping profile...
08-10 09:31:14.101  2561  2758 D A2dpStateMachine: Exit Disconnected: -1
08-10 09:31:14.097  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 09:31:14.106   441   441 E Parcel  : Reading a NULL string not supported here.
08-10 09:31:14.106   875   875 D BluetoothA2dp: Proxy object disconnected
08-10 09:31:14.106  1362  1362 D BluetoothA2dp: Proxy object disconnected
,08-10 09:31:14.107   875  1988 D DhcpClient: Receive thread stopped
08-10 09:31:14.107  2561  2561 D HidService: Received stop request...Stopping profile...
08-10 09:31:14.107  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 09:31:14.107  2561  2561 D HidService: Stopping Bluetooth HidService
08-10 09:31:14.107  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 09:31:14.107  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:14.107  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:14.107  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:14.107  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 09:31:14.107  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 09:31:14.107  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 09:31:14.107  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 09:31:14.107   875  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-10 09:31:14.108  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 09:31:14.108  1362  1362 D BluetoothInputDevice: Proxy object disconnected
08-10 09:31:14.108  1362  1362 D HidProfile: Bluetooth service disconnected
08-10 09:31:14.108  3663  3663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 09:31:14.111  2561  2561 V BluetoothAdapterState: isTurningOff()=true
08-10 09:31:14.111  2561  2561 V BluetoothAdapterState: isTurningOn()=false
08-10 09:31:14.111  2561  2561 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 09:31:14.111  2561  2561 V BluetoothAdapterState: isBleTurningOff()=false
08-10 09:31:14.112  2561  2561 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-10 09:31:14.112  2561  2561 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 09:31:14.112  2561  2612 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-10 09:31:14.112  2561  2731 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 09:31:14.112  2561  2731 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 09:31:14.112  2561  2731 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 09:31:14.113  2561  2612 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-10 09:31:14.114  2561  2561 D HealthService: Received stop request...Stopping profile...
,08-10 09:31:14.115  2561  2561 D PanService: Received stop request...Stopping profile...
,08-10 09:31:14.117  2561  2561 D BluetoothMapService: Received stop request...Stopping profile...
,08-10 09:31:14.117  2561  2561 D BluetoothMapService: stop()
08-10 09:31:14.118  2561  2561 D BluetoothMapAppObserver: deinitObservers()
08-10 09:31:14.118  2561  2561 D BluetoothMapAppObserver: removeReceiver()
08-10 09:31:14.119  2561  2561 V BluetoothAdapterState: isTurningOff()=true
,08-10 09:31:14.120  2561  2561 V BluetoothAdapterState: isTurningOn()=false
,08-10 09:31:14.120  2561  2561 V BluetoothAdapterState: isBleTurningOn()=false
08-10 09:31:14.120  2561  2561 V BluetoothAdapterState: isBleTurningOff()=false
08-10 09:31:14.122  2561  2612 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-10 09:31:14.122  2561  2731 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 09:31:14.122  2561  2731 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 09:31:14.122  2561  2731 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 09:31:14.122  2561  2731 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 09:31:14.122  2561  2731 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 09:31:14.122  2561  2731 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 09:31:14.123  2561  2561 V BluetoothAdapterState: isTurningOff()=true
08-10 09:31:14.123  2561  2561 V BluetoothAdapterState: isTurningOn()=false
08-10 09:31:14.123  2561  2561 V BluetoothAdapterState: isBleTurningOn()=false
08-10 09:31:14.123  2561  2561 V BluetoothAdapterState: isBleTurningOff()=false
08-10 09:31:14.123  2561  2561 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-10 09:31:14.123  2561  2612 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-10 09:31:14.124  2561  2561 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-10 09:31:14.124  2561  2561 V BluetoothAdapterState: isTurningOff()=true
08-10 09:31:14.124  2561  2561 V BluetoothAdapterState: isTurningOn()=false
08-10 09:31:14.124  2561  2561 V BluetoothAdapterState: isBleTurningOn()=false
08-10 09:31:14.125  2561  2561 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 09:31:14.125  2561  2561 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-10 09:31:14.125  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 09:31:14.125  2561  2612 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-10 09:31:14.125  1362  1362 D PanProfile: Bluetooth service disconnected
08-10 09:31:14.125  1362  1362 D BluetoothMap: Proxy object disconnected
08-10 09:31:14.125  1362  1362 D MapProfile: Bluetooth service disconnected
08-10 09:31:14.125  2561  2561 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 09:31:14.126  2561  2561 V BluetoothAdapterState: isTurningOff()=true
08-10 09:31:14.126  2561  2561 V BluetoothAdapterState: isTurningOn()=false
08-10 09:31:14.126  2561  2561 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 09:31:14.126  2561  2561 V BluetoothAdapterState: isBleTurningOff()=false
08-10 09:31:14.126  2561  2561 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-10 09:31:14.126  2561  2561 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-10 09:31:14.127  2561  2561 D BluetoothMapService: MAP Service closeService in
08-10 09:31:14.127  2561  2561 V BluetoothAdapterState: isTurningOff()=true
08-10 09:31:14.128  2561  2561 V BluetoothAdapterState: isTurningOn()=false
08-10 09:31:14.128  2561  2561 V BluetoothAdapterState: isBleTurningOn()=false
08-10 09:31:14.129  2561  2561 V BluetoothAdapterState: isBleTurningOff()=false
08-10 09:31:14.130  2561  2608 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-10 09:31:14.130  2561  2608 D BluetoothAdapterProperties: Setting state to 15
,08-10 09:31:14.131  2561  2608 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-10 09:31:14.131  2561  2608 I BluetoothAdapterState: Entering BleOnState
08-10 09:31:14.131   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 09:31:14.131  1362  1377 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 09:31:14.132   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 09:31:14.132  1362  1376 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 09:31:14.134  1735  1870 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 09:31:14.135   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 09:31:14.135  1362  1377 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 09:31:14.136  1362  1969 D BluetoothPan: onBluetoothStateChange on: false
08-10 09:31:14.136  1362  1376 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-10 09:31:14.137  2561  2561 D BluetoothMapService: cleanup()
08-10 09:31:14.137  2561  2561 D BluetoothMapService: MAP Service closeService in
08-10 09:31:14.137  1362  1377 D BluetoothMap: onBluetoothStateChange: up=false
08-10 09:31:14.137   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 09:31:14.138  2561  2608 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-10 09:31:14.138  2561  2608 D BluetoothAdapterProperties: Setting state to 16
08-10 09:31:14.138  2561  2608 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-10 09:31:14.138  2561  2608 D BluetoothAdapterProperties: onBleDisable
,08-10 09:31:14.138  2561  2609 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-10 09:31:14.138  2561  2608 I BluetoothAdapterState: Entering PendingCommandState
08-10 09:31:14.139  2561  2612 D BluetoothAdapterProperties: Scan Mode:20
08-10 09:31:14.140  2561  2731 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-10 09:31:14.140  2561  2731 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 09:31:14.142  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 09:31:14.142  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 09:31:14.142  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:14.142  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:14.142  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:14.142  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 09:31:14.142  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 09:31:14.142  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 09:31:14.142  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 09:31:14.147  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 09:31:14.147  3663  3663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-10 09:31:14.147   370   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-10 09:31:14.149  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 09:31:14.149  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 09:31:14.149  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:14.149  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:14.149  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:14.149  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 09:31:14.149  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 09:31:14.149  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 09:31:14.149  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 09:31:14.150  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:14.151  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:14.171  3733  3733 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-10 09:31:14.179   370   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 09:31:14.179   370   873 D CommandListener: Clearing all IP addresses on wlan0
08-10 09:31:14.180   875  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-10 09:31:14.180   875  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-10 09:31:14.181   875   892 D Tethering: MasterInitialState.processMessage what=3
08-10 09:31:14.185   875  1308 D WifiConfigStore: Retrieve network priorities after PNO.
08-10 09:31:14.185  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 09:31:14.187  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 09:31:14.187  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 09:31:14.187  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:14.187  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:14.187  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 09:31:14.187  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 09:31:14.187  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 09:31:14.187  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 09:31:14.187  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 09:31:14.187  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 09:31:14.187  3663  3663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 09:31:14.187  3265  3265 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@5c6cbd and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-10 09:31:14.189  1905  2083 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 09:31:14.191  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 09:31:14.191  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 09:31:14.191  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:14.191  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:14.191  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 09:31:14.191  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 09:31:14.191  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 09:31:14.191  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 09:31:14.191  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 09:31:14.192  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 09:31:14.192  3663  3663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 09:31:14.193  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-10 09:31:14.193  3733  3733 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 09:31:14.198   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7308b12:true
,08-10 09:31:14.199   875  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-10 09:31:14.201  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 09:31:14.213   875  1374 I ActivityManager: Start proc 3751:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-10 09:31:14.240   370   873 E Netd    : netlink response contains error (No such file or directory)
,08-10 09:31:14.241  3733  3733 D LocalBluetoothProfileManager: Adding local MAP profile
,08-10 09:31:14.242  3733  3733 D BluetoothMap: Create BluetoothMap proxy object
,08-10 09:31:14.249  3733  3733 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-10 09:31:14.251  3751  3751 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-10 09:31:14.264  3733  3733 D DockEventReceiver: finishStartingService: stopping service
,08-10 09:31:14.271   875   886 I ActivityManager: Killing 2852:com.google.android.calendar/u0a37 (adj 15): empty #17
,08-10 09:31:14.350  2561  2612 I bt_hci  : shut_down
,08-10 09:31:14.353  2561  2617 I bt_vendor: low_power_mode_cb
,08-10 09:31:14.361  2561  2617 D bt_hwcfg: hw_epilog_process
,08-10 09:31:14.381  2561  2617 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-10 09:31:14.381  2561  2617 I bt_vendor: epilog_cb
08-10 09:31:14.381  2561  2617 I bt_hci  : epilog_finished_callback
,08-10 09:31:14.384  2561  2612 I bt_hci_h4: hal_close
,08-10 09:31:14.384  2561  2612 I bt_userial_vendor: device fd = 51 close
,08-10 09:31:14.397  3751  3751 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at java.io.File.exists(File.java:361)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-10 09:31:14.397  3751  3751 D StrictMode: StrictMode policy violation; ~duration=90 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 09:31:14.397  3751  3751 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-10 09:31:14.397  3751  3751 D StrictMode: 	,at libcore.io.IoBridge.open(IoBridge.java:441)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 09:31:14.397  3751  3751 D StrictMode: StrictMode policy violation; ~duration=89 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
,08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.r.e.b(PG:170)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 09:31:14.397  3751  3751 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.r.k.d(PG:583)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.r.e.b(PG:170)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693),
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 09:31:14.397  3751  3751 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at java.io.File.exists(File.java:361)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.os.Handler.dispatchMessage(H,andler.java:102)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 09:31:14.397  3751  3751 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 09:31:14.398  3751  3751 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 09:31:14.398  3751  3751 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at java.io.File.exists(File.java:361)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 09:31:14.398  3751  3751 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-10 09:31:14.398  3751  3751 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-10 09:,31:14.398  3751  3751 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 09:31:14.398  3751  3751 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 09:31:14.409  3733  3733 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-10 09:31:14.416  3733  3733 D DockEventReceiver: finishStartingService: stopping service
08-10 09:31:14.419  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-10 09:31:14.421   875  2065 I ActivityManager: Killing 3265:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-10 09:31:14.504  2561  2609 D bt_stack_manager: event_shut_down_stack finished.
,08-10 09:31:14.504  2561  2608 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-10 09:31:14.506  2561  2608 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-10 09:31:14.506  2561  2561 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 09:31:14.506  2561  2561 D BtGatt.GattService: Received stop request...Stopping profile...
08-10 09:31:14.506  2561  2561 D BtGatt.GattService: stop()
08-10 09:31:14.507  2561  2561 D BtGatt.AdvertiseManager: advertise clients cleared
,08-10 09:31:14.508  2561  2561 V BluetoothAdapterState: isTurningOff()=false,
08-10 09:31:14.508  2561  2561 V BluetoothAdapterState: isTurningOn()=false
08-10 09:31:14.508  2561  2561 V BluetoothAdapterState: isBleTurningOn()=false
08-10 09:31:14.508  2561  2561 V BluetoothAdapterState: isBleTurningOff()=true
08-10 09:31:14.508  2561  2608 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-10 09:31:14.508  2561  2608 D BluetoothAdapterProperties: Setting state to 10
,08-10 09:31:14.509  2561  2608 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-10 09:31:14.509  2561  2608 I BluetoothAdapterState: Entering OffState
08-10 09:31:14.509   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-10 09:31:14.532  2561  2561 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-10 09:31:14.533  2561  2561 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-10 09:31:14.534  1887  1887 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-10 09:31:14.535  2561  2609 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-10 09:31:14.533  2561  2561 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-10 09:31:14.538  3663  3663 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 09:31:14.539  2561  2609 D bt_stack_manager: event_clean_up_stack finished.
,08-10 09:31:14.540  2561  2561 I art     : System.exit called, status: 0,
08-10 09:31:14.540  2561  2561 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-10 09:31:14.543  1887  1887 D SystemUpdateService: onCreate
,08-10 09:31:14.549  1887  1887 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-10 09:31:14.557  1887  3785 I SystemUpdateService: active receiver: enabled
,08-10 09:31:14.569  1887  1887 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-10 09:31:14.574  1887  2345 I iu.UploadsManager: num queued entries: 0
,08-10 09:31:14.574  1887  2345 I iu.UploadsManager: num updated entries: 0
,08-10 09:31:14.579  1887  1887 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-10 09:31:14.580  1887  2345 I iu.SyncManager: NEXT; no task
,08-10 09:31:14.582  1887  1887 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-10 09:31:14.585  1887  3785 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 09:31:14.588  1887  3785 I SystemUpdateService: network: null; metered: false; mobile allowed: true
08-10 09:31:14.588  1887  3785 I SystemUpdateService: now status is 0 (complete)
08-10 09:31:14.588  1887  3785 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-10 09:31:14.588  1887  3785 I SystemUpdateService: file has been verified
08-10 09:31:14.588  1887  3785 I SystemUpdateService: OTA package size = 12249756
,08-10 09:31:14.603  1887  3785 I SystemUpdateService: showing system update notification
,08-10 09:31:14.643   875  1796 I ActivityManager: Start proc 3788:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-10 09:31:14.647   875  1693 I ActivityManager: Process com.android.bluetooth (pid 2561) has died
,08-10 09:31:14.701  1887  1887 D SystemUpdateService: onDestroy
,08-10 09:31:14.712  3788  3788 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-10 09:31:14.714  3751  3770 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-10 09:31:14.722  3788  3788 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-10 09:31:14.729  3788  3788 D SprintDMHelper: simOperator: 
,08-10 09:31:14.729  3788  3788 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-10 09:31:14.746   875  1374 I ActivityManager: Start proc 3802:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-10 09:31:14.753   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ba4bbe:true
,08-10 09:31:14.837  3345  3816 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-10 09:31:14.856   875  1393 I ActivityManager: Start proc 3817:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-10 09:31:14.866   875  1393 I ActivityManager: Killing 3310:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-10 09:31:14.931  3817  3817 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-10 09:31:14.993  3817  3817 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-10 09:31:14.993  3817  3817 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-10 09:31:14.993  3817  3817 I GAv4    :   adb logcat -s GAv4
,08-10 09:31:15.008  3817  3817 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-10 09:31:15.015  3817  3817 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-10 09:31:15.041  3817  3834 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-10 09:31:15.156  3817  3817 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-10 09:31:15.198  3817  3817 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-10 09:31:15.210  3817  3817 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 3815-3821)
08-10 09:31:15.210  3817  3817 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-10 09:31:15.219  3817  3817 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {cb19a4f}
,08-10 09:31:15.220  3817  3817 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 09:31:15.220  3817  3817 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-10 09:31:15.228  3817  3817 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-10 09:31:15.230  3817  3817 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-10 09:31:15.246  3817  3817 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-10 09:31:15.260  3817  3817 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 09:31:15.261  3817  3817 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-10 09:31:15.261  3817  3817 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 09:31:15.261  3817  3817 I Adreno  : Build Date                       : 10/20/15
08-10 09:31:15.261  3817  3817 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 09:31:15.261  3817  3817 I Adreno  : Local Branch                     : M14
08-10 09:31:15.261  3817  3817 I Adreno  : Remote Branch                    : 
08-10 09:31:15.261  3817  3817 I Adreno  : Remote Branch                    : 
08-10 09:31:15.261  3817  3817 I Adreno  : Reconstruct Branch               : 
,08-10 09:31:15.331  3817  3817 I NSApplication: Starting up...
,08-10 09:31:15.344  3817  3863 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-10 09:31:15.378   875   885 I ActivityManager: Start proc 3868:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-10 09:31:15.380   875   885 I ActivityManager: Killing 1680:android.process.acore/u0a5 (adj 15): empty #17
,08-10 09:31:15.451  3868  3868 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-10 09:31:15.628   875  1622 I ActivityManager: Killing 3520:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-10 09:31:15.715   875  1374 I ActivityManager: Start proc 3882:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-10 09:31:15.786  3882  3882 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-10 09:31:15.833  3882  3882 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-10 09:31:15.883   875  1822 I ActivityManager: Killing 3533:com.android.musicfx/u0a18 (adj 15): empty #17
,08-10 09:31:17.078   875  2069 D WifiService: setWifiEnabled: true pid=3663, uid=10000
,08-10 09:31:17.079   875  2069 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 09:31:17.094   875  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-10 09:31:17.104  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 09:31:17.104  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 09:31:17.104  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:17.104  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:17.104  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:17.104  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 09:31:17.104  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 09:31:17.104  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 09:31:17.104  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 09:31:17.105  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 09:31:17.105  3663  3663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 09:31:17.108  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 09:31:17.109  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 09:31:17.109  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:17.109  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:17.109  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:17.109  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 09:31:17.109  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 09:31:17.109  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 09:31:17.109  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 09:31:17.109  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 09:31:17.110  3663  3663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 09:31:17.131   875  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-10 09:31:17.132   875  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-10 09:31:17.133   875  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-10 09:31:17.134   875  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-10 09:31:17.134   875  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-10 09:31:17.134   875  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-10 09:31:17.134   875  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-10 09:31:17.146   370   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-10 09:31:17.146   875  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=4.06 rxSuccessRate=8.31 delta 1000 -> 1000
,08-10 09:31:17.147   370   873 D CommandListener: Setting iface cfg
08-10 09:31:17.148   875  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
08-10 09:31:17.148   875  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-10 09:31:17.154   875  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-10 09:31:17.154   875  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-10 09:31:17.154   875  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-10 09:31:17.154   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 09:31:17.161   875  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-10 09:31:17.228   875  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-10 09:31:17.231  1470  1470 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-10 09:31:17.642  1470  1470 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-10 09:31:17.686  1470  1470 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-10 09:31:17.688  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-10 09:31:17.694   875  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 09:31:17.712   875  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-10 09:31:17.713   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 09:31:17.713   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-10 09:31:17.742   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 09:31:17.757   370   873 D CommandListener: Setting iface cfg
08-10 09:31:17.758   875  1308 D WifiStateMachine: Start Dhcp Watchdog 2
,08-10 09:31:17.785   875  1310 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,08-10 09:31:17.786   875  3915 D DhcpClient: Receive thread started
,08-10 09:31:17.793   875  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-10 09:31:17.890   875  1308 E native  : do suspend false
,08-10 09:31:17.913   875  1987 D DhcpClient: Broadcasting DHCPDISCOVER
,08-10 09:31:17.932   875  3915 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172676, domain null
08-10 09:31:17.933   875  1987 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172676 seconds
08-10 09:31:17.936   875  1987 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-10 09:31:17.949   875  3915 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-10 09:31:17.950   875  1987 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-10 09:31:17.958   370   873 D CommandListener: Setting iface cfg
,08-10 09:31:17.970   875  1987 D DhcpClient: Scheduling renewal in 86399s
,08-10 09:31:17.974   875  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-10 09:31:17.989   875  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-10 09:31:17.992   875  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-10 09:31:17.992   875  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-10 09:31:17.993   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-10 09:31:17.996   875  1310 D ConnectivityService: Adding iface wlan0 to network 101
08-10 09:31:18.011   875  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-10 09:31:18.054   875  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-10 09:31:18.054   875  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,08-10 09:31:18.055   875  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-10 09:31:18.056   875  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-10 09:31:18.057   875  1310 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-10 09:31:18.063   875  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-10 09:31:18.067   875  1310 D ConnectivityService: scheduleUnvalidatedPrompt 101
08-10 09:31:18.068   875  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-10 09:31:18.068   875  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-10 09:31:18.068   875  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-10 09:31:18.069   875  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-10 09:31:18.069   875  1310 D ConnectivityService:    accepting network in place of null
08-10 09:31:18.070   875  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-10 09:31:18.075   875  3914 D NetlinkSocketObserver: NeighborEvent{elapsedMs=146686, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:31:18.100   370   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 09:31:18.138   370   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 09:31:18.146   875  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-10 09:31:18.147   875  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 09:31:18.155   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-10 09:31:18.156   875  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-10 09:31:18.163  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 09:31:18.164  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 09:31:18.164  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:18.164  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:18.164  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:18.164  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 09:31:18.164  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 09:31:18.164  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 09:31:18.164  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 09:31:18.164  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 09:31:18.164  3663  3663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 09:31:18.170  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 09:31:18.170  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 09:31:18.170  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-10 09:31:18.170  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:18.170  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:18.170  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 09:31:18.170  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 09:31:18.170  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 09:31:18.170  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 09:31:18.170  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 09:31:18.170  3663  3663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 09:31:18.185  1887  1887 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-10 09:31:18.188  1887  1887 D SystemUpdateService: onCreate
,08-10 09:31:18.191  1887  1887 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-10 09:31:18.194  1887  3927 I SystemUpdateService: active receiver: enabled
,08-10 09:31:18.200  1887  3927 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 09:31:18.202  1887  3927 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-10 09:31:18.203  1887  3927 I SystemUpdateService: now status is 0 (complete)
,08-10 09:31:18.203  1887  3927 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-10 09:31:18.203  1887  3927 I SystemUpdateService: file has been verified
08-10 09:31:18.203  1887  3927 I SystemUpdateService: OTA package size = 12249756
,08-10 09:31:18.207  1887  3927 I SystemUpdateService: showing system update notification
,08-10 09:31:18.211  1887  1887 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-10 09:31:18.213  1887  2345 I iu.UploadsManager: num queued entries: 0
08-10 09:31:18.213  1887  2345 I iu.UploadsManager: num updated entries: 0
,08-10 09:31:18.218  1887  2345 I iu.SyncManager: NEXT; no task
,08-10 09:31:18.220  1887  1887 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-10 09:31:18.220  1887  3931 I MDM     : [211] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
08-10 09:31:18.220  1887  3931 W BaseAppContext: Using Auth Proxy for data requests.
,08-10 09:31:18.222  1887  1887 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-10 09:31:18.222  1887  3931 V GoogleAuthProtoRequest: [211] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 09:31:18.225  3788  3788 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-10 09:31:18.225  1887  1887 D SystemUpdateService: onDestroy
,08-10 09:31:18.231  3788  3788 D SprintDMHelper: simOperator: 
,08-10 09:31:18.231  3788  3788 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-10 09:31:18.231  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 09:31:18.232  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:31:18.265  1520  1941 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-10 09:31:18.265  1520  1941 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-10 09:31:18.265  1520  1941 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:31:18.265  1520  1941 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:31:18.281  1887  3931 E MDM     : [211] SitrepService.a: Error sending sitrep.
,08-10 09:31:18.389   875  3913 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.78,2a00:1450:4001:805::200e
,08-10 09:31:18.438  3345  3933 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-10 09:31:18.468   875  3913 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 07:31:18 GMT], X-Android-Received-Millis=[1470814278466], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470814278434]}
,08-10 09:31:18.471   875  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-10 09:31:18.473   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
08-10 09:31:18.474   875  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-10 09:31:18.481   875  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-10 09:31:19.145   875  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-10 09:31:19.792   875  1622 I ActivityManager: Killing 2047:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-10 09:31:20.089   875   885 D WifiService: setWifiEnabled: false pid=3663, uid=10000
08-10 09:31:20.089   875   885 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 09:31:20.126  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-10 09:31:20.139   875  1308 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-10 09:31:20.139   875  1308 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-10 09:31:20.140   875  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-10 09:31:20.140   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 09:31:20.168   875  1987 D DhcpClient: Clearing IP address
08-10 09:31:20.168   370   873 D CommandListener: Clearing all IP addresses on wlan0
,08-10 09:31:20.172   370   873 D CommandListener: Setting iface cfg
08-10 09:31:20.178  1520  3938 V NativeCrypto: Read error: ssl=0x9afab600: I/O error during system call, Connection timed out
,08-10 09:31:20.184  1520  3938 V NativeCrypto: SSL shutdown failed: ssl=0x9afab600: I/O error during system call, Broken pipe
,08-10 09:31:20.188   875  3915 D DhcpClient: Receive thread stopped
,08-10 09:31:20.193   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-10 09:31:20.194   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-10 09:31:20.194   875  1308 D WifiStateMachine: Start Disconnecting Watchdog 2
,08-10 09:31:20.196   875  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-10 09:31:20.202   441   441 E Parcel  : Reading a NULL string not supported here.
08-10 09:31:20.203   370   873 D CommandListener: Clearing all IP addresses on wlan0
08-10 09:31:20.209   875  1310 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-10 09:31:20.213   875  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 09:31:20.216  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 09:31:20.217  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 09:31:20.217  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:20.217  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:20.217  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 09:31:20.217  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 09:31:20.217  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 09:31:20.217  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 09:31:20.217  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 09:31:20.217  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 09:31:20.217  3663  3663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 09:31:20.218  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 09:31:20.218  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 09:31:20.218  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:20.218  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:20.218  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 09:31:20.218  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 09:31:20.218  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 09:31:20.218  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 09:31:20.218  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 09:31:20.218  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 09:31:20.218  3663  3663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 09:31:20.219  1905  2083 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-10 09:31:20.220   875  1308 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-10 09:31:20.247   370   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 09:31:20.270   370   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 09:31:20.271   875  1310 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-10 09:31:20.271   875  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 09:31:20.275  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:20.276   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-10 09:31:20.276  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:20.283  1887  1887 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-10 09:31:20.286  1887  1887 D SystemUpdateService: onCreate
,08-10 09:31:20.289  1887  1887 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-10 09:31:20.297  1887  1887 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-10 09:31:20.302  1887  3949 I SystemUpdateService: active receiver: enabled
,08-10 09:31:20.301  1887  2345 I iu.UploadsManager: num queued entries: 0
,08-10 09:31:20.304  1887  2345 I iu.UploadsManager: num updated entries: 0
,08-10 09:31:20.304  1887  2345 I iu.SyncManager: NEXT; no task
,08-10 09:31:20.306  1887  1887 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-10 09:31:20.309  1887  1887 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-10 09:31:20.311  3788  3788 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-10 09:31:20.315  3788  3788 D SprintDMHelper: simOperator: 
,08-10 09:31:20.315  3788  3788 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-10 09:31:20.336  3345  3953 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-10 09:31:20.345  1887  3949 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 09:31:20.351  1887  3949 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-10 09:31:20.351  1887  3949 I SystemUpdateService: now status is 0 (complete)
08-10 09:31:20.351  1887  3949 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-10 09:31:20.351  1887  3949 I SystemUpdateService: file has been verified
08-10 09:31:20.352   370   873 E Netd    : netlink response contains error (No such file or directory)
08-10 09:31:20.351  1887  3949 I SystemUpdateService: OTA package size = 12249756
,08-10 09:31:20.360  1887  3949 I SystemUpdateService: showing system update notification
,08-10 09:31:20.368  1887  1887 D SystemUpdateService: onDestroy
,08-10 09:31:21.563   875   895 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-10 09:31:21.573  1641  1641 I Keyboard.Facilitator: onFinishInput()
,08-10 09:31:21.580   875   895 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-10 09:31:21.580   875   895 I Adreno  : Build Date                       : 10/20/15
08-10 09:31:21.580   875   895 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-10 09:31:21.580   875   895 I Adreno  : Local Branch                     : M14
08-10 09:31:21.580   875   895 I Adreno  : Remote Branch                    : 
08-10 09:31:21.580   875   895 I Adreno  : Remote Branch                    : 
08-10 09:31:21.580   875   895 I Adreno  : Reconstruct Branch               : 
,08-10 09:31:21.611   280  1300 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (269 us)
,08-10 09:31:22.268  3663  3663 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-10 09:31:22.268  3663  3663 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-10 09:31:22.308   875   895 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-10 09:31:22.313   875   895 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-10 09:31:22.314  3663  3663 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@85b49f9 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@96cbb2b, 16908290=android.view.AbsSavedState$1@96cbb2b}, android:focusedViewId=100}]}]
,08-10 09:31:22.314  3663  3663 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,08-10 09:31:22.314  3663  3663 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-10 09:31:22.314  3663  3663 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-10 09:31:22.319   875   893 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-10 09:31:22.319   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
,08-10 09:31:22.320   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-10 09:31:22.342   875   884 I art     : Background partial concurrent mark sweep GC freed 58524(3MB) AllocSpace objects, 9(240KB) LOS objects, 33% free, 28MB/43MB, paused 1.070ms total 100.085ms
,08-10 09:31:22.556   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-10 09:31:22.561   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-10 09:31:22.567   875  1331 D SurfaceControl: Excessive delay in setPowerMode(): 248ms
,08-10 09:31:22.571   875   895 I DreamManagerService: Entering dreamland.
,08-10 09:31:22.572   875   895 I PowerManagerService: Dozing...
08-10 09:31:22.573   875   890 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-10 09:31:22.616   374   374 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,08-10 09:31:22.616   374   374 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-10 09:31:22.621   875  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 09:31:22.624   875  1308 E native  : do suspend false
,08-10 09:31:22.627  1724  3958 D NfcService: Discovery configuration equal, not updating.
,08-10 09:31:22.644   875  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 09:31:22.648   875  1308 E native  : do suspend true
,08-10 09:31:22.760   374  1491 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-10 09:31:22.760   374  1491 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-10 09:31:23.146   875   892 I ActivityManager: Start proc 3962:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-10 09:31:23.270  3962  3962 D AdapterServiceConfig: Adding HeadsetService
,08-10 09:31:23.270  3962  3962 D AdapterServiceConfig: Adding A2dpService
08-10 09:31:23.270  3962  3962 D AdapterServiceConfig: Adding HidService
,08-10 09:31:23.270  3962  3962 D AdapterServiceConfig: Adding HealthService
,08-10 09:31:23.271  3962  3962 D AdapterServiceConfig: Adding PanService
,08-10 09:31:23.271  3962  3962 D AdapterServiceConfig: Adding GattService
08-10 09:31:23.271  3962  3962 D AdapterServiceConfig: Adding BluetoothMapService
,08-10 09:31:23.286   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1950978:true
08-10 09:31:23.287  3962  3962 D BluetoothAdapterState: make() - Creating AdapterState
,08-10 09:31:23.292  3962  3962 I bt_bluedroid: init
,08-10 09:31:23.293  3962  3974 I BluetoothAdapterState: Entering OffState
,08-10 09:31:23.299  3962  3975 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-10 09:31:23.299  3962  3975 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-10 09:31:23.299  3962  3975 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-10 09:31:23.300  3962  3975 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-10 09:31:23.303  3962  3962 I bt_bluedroid: get_profile_interface socket
,08-10 09:31:23.306  3962  3962 I bt_bluedroid: get_profile_interface sdp
,08-10 09:31:23.313  3962  3973 I bt_bluedroid: config_hci_snoop_log
08-10 09:31:23.314  3962  3978 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 09:31:23.316  3962  3978 D BluetoothAdapterProperties: Name is: Nexus 6
08-10 09:31:23.317   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-10 09:31:23.323  3962  3974 D BluetoothAdapterState: Current state: OFF, message: 0
,08-10 09:31:23.324  3962  3974 D BluetoothAdapterProperties: Setting state to 14
08-10 09:31:23.324  3962  3974 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-10 09:31:23.328  3962  3974 D BluetoothBondStateMachine: make
,08-10 09:31:23.332  3962  3979 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-10 09:31:23.340  3962  3974 I BluetoothAdapterState: Entering PendingCommandState
08-10 09:31:23.341  3962  3962 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-10 09:31:23.345  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e34fafd
,08-10 09:31:23.346  3962  3962 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 09:31:23.347  3962  3962 D BtGatt.GattService: Received start request. Starting profile...
,08-10 09:31:23.347  3962  3962 D BtGatt.GattService: start()
08-10 09:31:23.347  3962  3962 I bt_bluedroid: get_profile_interface gatt
,08-10 09:31:23.349  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e34fafd
,08-10 09:31:23.349  3962  3962 D BtGatt.AdvertiseManager: advertise manager created
,08-10 09:31:23.366  3962  3962 V BluetoothAdapterState: isTurningOff()=false
,08-10 09:31:23.367  3962  3962 V BluetoothAdapterState: isTurningOn()=false
08-10 09:31:23.367  3962  3962 V BluetoothAdapterState: isBleTurningOn()=true
08-10 09:31:23.367  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 09:31:23.369  3962  3974 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-10 09:31:23.370  3962  3974 I bt_bluedroid: enable
,08-10 09:31:23.370  3962  3975 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-10 09:31:23.371  3962  3975 I bt_hci  : start_up
,08-10 09:31:23.379  3962  3975 I bt_vendor: alloc value 0xb3a6d189
,08-10 09:31:23.379  3962  3975 I bt_vendor: init
,08-10 09:31:23.380  3962  3975 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-10 09:31:23.380  3962  3975 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-10 09:31:23.488  3962  3975 D bt_hci  : start_up starting async portion
,08-10 09:31:23.489  3962  3982 I bt_hci  : event_finish_startup
,08-10 09:31:23.489  3962  3982 I bt_hci_h4: hal_open
,08-10 09:31:23.489  3962  3982 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-10 09:31:23.498  3962  3982 I bt_userial_vendor: device fd = 51 open
,08-10 09:31:23.530  3962  3982 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 09:31:23.562  3962  3982 D bt_hwcfg: Chipset BCM4354A2
,08-10 09:31:23.562  3962  3982 D bt_hwcfg: Target name = [BCM4354A2]
,08-10 09:31:23.563  3962  3982 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-10 09:31:24.217  3962  3982 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-10 09:31:24.218  3962  3982 D bt_hwcfg: Settlement delay -- 100 ms
,08-10 09:31:24.218  3962  3982 I bt_hwcfg: Setting fw settlement delay to 100 
,08-10 09:31:24.335  3962  3982 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 09:31:24.336  3962  3982 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-10 09:31:24.365  3962  3982 I bt_hwcfg: vendor lib fwcfg completed
,08-10 09:31:24.366  3962  3982 I bt_vendor: firmware callback
08-10 09:31:24.366  3962  3982 I bt_hci  : firmware_config_callback
,08-10 09:31:24.377  3962  3984 I bt_btu  : btu_task pending for preload complete event
,08-10 09:31:24.377  3962  3984 I bt_btu_task: Bluetooth chip preload is complete
,08-10 09:31:24.377  3962  3984 I bt_btu  : btu_task received preload complete event
,08-10 09:31:24.390  3962  3984 I         : BTE_InitTraceLevels -- TRC_HCI
,08-10 09:31:24.390  3962  3984 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-10 09:31:24.390  3962  3984 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-10 09:31:24.390  3962  3984 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-10 09:31:24.391  3962  3984 I         : BTE_InitTraceLevels -- TRC_AVRC
08-10 09:31:24.391  3962  3984 I         : BTE_InitTraceLevels -- TRC_A2D
,08-10 09:31:24.391  3962  3984 I         : BTE_InitTraceLevels -- TRC_BNEP
08-10 09:31:24.392  3962  3984 I         : BTE_InitTraceLevels -- TRC_BTM
,08-10 09:31:24.392  3962  3984 I         : BTE_InitTraceLevels -- TRC_GAP
08-10 09:31:24.392  3962  3984 I         : BTE_InitTraceLevels -- TRC_PAN
08-10 09:31:24.392  3962  3984 I         : BTE_InitTraceLevels -- TRC_SDP
,08-10 09:31:24.393  3962  3984 I         : BTE_InitTraceLevels -- TRC_GATT
08-10 09:31:24.393  3962  3984 I         : BTE_InitTraceLevels -- TRC_SMP
,08-10 09:31:24.393  3962  3984 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-10 09:31:24.393  3962  3984 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-10 09:31:24.528  3962  3984 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39ead9d
,08-10 09:31:24.528  3962  3984 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39ead9d 
,08-10 09:31:24.548  3962  3978 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-10 09:31:24.551  3962  3978 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-10 09:31:24.552  3962  3978 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 09:31:24.554  3962  3978 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 09:31:24.562  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:24.558  3962  3978 D BluetoothAdapterProperties: Scan Mode:20
,08-10 09:31:24.564  3962  3978 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-10 09:31:24.565  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:24.565  3962  3978 D bt_hci  : do_postload posting postload work item
08-10 09:31:24.566  3962  3982 I bt_hci  : event_postload
08-10 09:31:24.566  3962  3982 I bt_vendor: sco_config_cb
,08-10 09:31:24.566  3962  3982 I bt_hci  : sco_config_callback postload finished.
,08-10 09:31:24.568  3962  3978 D bt_bte_conf: Device ID record 1 : primary
08-10 09:31:24.568  3962  3978 D bt_bte_conf:   vendorId            = 000f
,08-10 09:31:24.569  3962  3978 D bt_bte_conf:   vendorIdSource      = 0001
08-10 09:31:24.569  3962  3978 D bt_bte_conf:   product             = 1200
,08-10 09:31:24.569  3962  3978 D bt_bte_conf:   version             = 1436
,08-10 09:31:24.569  3962  3978 D bt_bte_conf:   clientExecutableURL = 
08-10 09:31:24.569  3962  3978 D bt_bte_conf:   serviceDescription  = 
,08-10 09:31:24.570  3962  3978 D bt_bte_conf:   documentationURL    = 
08-10 09:31:24.570  3962  3978 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-10 09:31:24.570  3962  3975 D bt_stack_manager: event_start_up_stack finished
08-10 09:31:24.571  3962  3974 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-10 09:31:24.572  3962  3974 D BluetoothAdapterProperties: Setting state to 15
08-10 09:31:24.572  3962  3974 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-10 09:31:24.573  3962  3974 I BluetoothAdapterState: Entering BleOnState
08-10 09:31:24.574  3962  3982 I bt_vendor: low_power_mode_cb
,08-10 09:31:24.578  3962  3974 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-10 09:31:24.578  3962  3974 D BluetoothAdapterProperties: Setting state to 11
,08-10 09:31:24.579  3962  3974 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-10 09:31:24.588  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:24.590  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:24.590  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e34fafd
08-10 09:31:24.591  3962  3962 D HeadsetService: Received start request. Starting profile...
,08-10 09:31:24.593  3962  3962 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-10 09:31:24.593  3962  3962 D HeadsetStateMachine: make
,08-10 09:31:24.601  3962  3962 D HeadsetStateMachine: max_hf_connections = 1
,08-10 09:31:24.601  3962  3962 I bt_bluedroid: get_profile_interface handsfree
08-10 09:31:24.601  3962  3978 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-10 09:31:24.602  3962  3978 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-10 09:31:24.605  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e34fafd
,08-10 09:31:24.607  3962  3962 D A2dpService: Received start request. Starting profile...
08-10 09:31:24.607  3962  3962 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-10 09:31:24.607  3962  3974 I BluetoothAdapterState: Entering PendingCommandState
08-10 09:31:24.607  3962  3962 I bt_bluedroid: get_profile_interface avrcp
,08-10 09:31:24.613  3962  3962 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-10 09:31:24.613  3962  3962 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-10 09:31:24.613  3962  3962 D A2dpStateMachine: make
,08-10 09:31:24.614  3962  3962 I bt_bluedroid: get_profile_interface a2dp
,08-10 09:31:24.615  3962  3978 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-10 09:31:24.616  3962  3993 D A2dpStateMachine: Enter Disconnected: -2
,08-10 09:31:24.618  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 09:31:24.620  3962  3962 I BluetoothHidServiceJni: classInitNative: succeeds
,08-10 09:31:24.621  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e34fafd
,08-10 09:31:24.622  3733  3733 D BluetoothInputDevice: Proxy object connected
,08-10 09:31:24.622  3962  3962 D HidService: Received start request. Starting profile...
08-10 09:31:24.622  3962  3962 I bt_bluedroid: get_profile_interface hidhost
08-10 09:31:24.623  3962  3978 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39cc3e5
08-10 09:31:24.623  3962  3962 D HidService: setHidService(): set to: null
,08-10 09:31:24.623  3733  3733 D HidProfile: Bluetooth service connected
08-10 09:31:24.623  3962  3978 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,08-10 09:31:24.624  3962  3962 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-10 09:31:24.625  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e34fafd
,08-10 09:31:24.625  3962  3962 D HealthService: Received start request. Starting profile...
,08-10 09:31:24.627  3962  3962 I bt_bluedroid: get_profile_interface health
,08-10 09:31:24.627  3962  3962 V BluetoothAdapterState: isTurningOff()=false
08-10 09:31:24.628  3962  3962 V BluetoothAdapterState: isTurningOn()=true
08-10 09:31:24.628  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-10 09:31:24.628  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 09:31:24.630  3962  3991 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-10 09:31:24.630  3962  3962 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-10 09:31:24.631  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e34fafd
,08-10 09:31:24.632  3733  3733 D BluetoothPan: BluetoothPAN Proxy object connected
,08-10 09:31:24.633  3962  3962 D PanService: Received start request. Starting profile...
08-10 09:31:24.633  3733  3733 D PanProfile: Bluetooth service connected
08-10 09:31:24.633  3962  3962 D BluetoothPanServiceJni: initializeNative(L110): pan
08-10 09:31:24.633  3962  3962 I bt_bluedroid: get_profile_interface pan
,08-10 09:31:24.634  3962  3978 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-10 09:31:24.637  3962  3962 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e34fafd
,08-10 09:31:24.638  3962  3962 D BluetoothMapService: Received start request. Starting profile...
,08-10 09:31:24.638  3962  3962 D BluetoothMapService: start()
08-10 09:31:24.638  3733  3733 D BluetoothMap: Proxy object connected
08-10 09:31:24.638  3733  3733 D MapProfile: Bluetooth service connected
08-10 09:31:24.638  3733  3733 D BluetoothMap: getConnectedDevices()
08-10 09:31:24.639  3733  3733 D BluetoothMap: Bluetooth is Not enabled
,08-10 09:31:24.640  3962  3962 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-10 09:31:24.640  3962  3962 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-10 09:31:24.640  3962  3962 D BluetoothMapAppObserver: createReceiver()
,08-10 09:31:24.641  3962  3962 D BluetoothMapAppObserver: initObservers()
08-10 09:31:24.641  3962  3962 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-10 09:31:24.647  3962  3962 V BluetoothAdapterState: isTurningOff()=false
,08-10 09:31:24.647  3962  3962 V BluetoothAdapterState: isTurningOn()=true
08-10 09:31:24.647  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-10 09:31:24.647  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 09:31:24.649  3962  3962 V BluetoothAdapterState: isTurningOff()=false
,08-10 09:31:24.649  3962  3962 V BluetoothAdapterState: isTurningOn()=true
08-10 09:31:24.649  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 09:31:24.649  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 09:31:24.649  3962  3962 V BluetoothAdapterState: isTurningOff()=false
08-10 09:31:24.649  3962  3962 V BluetoothAdapterState: isTurningOn()=true
,08-10 09:31:24.650  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 09:31:24.650  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
08-10 09:31:24.650  3962  3962 V BluetoothAdapterState: isTurningOff()=false
08-10 09:31:24.650  3962  3962 V BluetoothAdapterState: isTurningOn()=true
08-10 09:31:24.650  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-10 09:31:24.650  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 09:31:24.650  3962  3962 V BluetoothAdapterState: isTurningOff()=false
08-10 09:31:24.650  3962  3962 V BluetoothAdapterState: isTurningOn()=true
08-10 09:31:24.650  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-10 09:31:24.650  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 09:31:24.650  3962  3974 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-10 09:31:24.650  3962  3974 D BluetoothAdapterProperties: ScanMode =  20
08-10 09:31:24.650  3962  3974 D BluetoothAdapterProperties: State =  11
08-10 09:31:24.651  3962  3974 D BluetoothAdapterProperties: Setting state to 12
,08-10 09:31:24.651  3962  3974 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-10 09:31:24.652  3733  3744 D BluetoothPan: onBluetoothStateChange on: true
08-10 09:31:24.652  3962  3978 D BluetoothAdapterProperties: Scan Mode:21
08-10 09:31:24.652  3962  3978 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-10 09:31:24.652  3733  3746 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-10 09:31:24.652  3962  3974 I BluetoothAdapterState: Entering OnState
08-10 09:31:24.652   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 09:31:24.653  1362  1376 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 09:31:24.653   875   875 D BluetoothA2dp: Proxy object connected
,08-10 09:31:24.654   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 09:31:24.654  3733  3744 D BluetoothPbap: onBluetoothStateChange: up=true
,08-10 09:31:24.655  1362  1377 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-10 09:31:24.655  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 09:31:24.655  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:24.655  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:24.655  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 09:31:24.655  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 09:31:24.655  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 09:31:24.655  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 09:31:24.655  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 09:31:24.657  1362  1362 D BluetoothInputDevice: Proxy object connected
08-10 09:31:24.657  1362  1362 D HidProfile: Bluetooth service connected
,08-10 09:31:24.657  1735  1763 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 09:31:24.657  3663  3663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 09:31:24.657   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 09:31:24.657  1362  1376 D BluetoothPbap: onBluetoothStateChange: up=true
,08-10 09:31:24.658  1362  1969 D BluetoothPan: onBluetoothStateChange on: true
08-10 09:31:24.659  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 09:31:24.659  1362  1362 D PanProfile: Bluetooth service connected
08-10 09:31:24.660  1362  1376 D BluetoothA2dp: onBluetoothStateChange: up=true
08-10 09:31:24.660  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 09:31:24.660  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:24.660  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:24.660  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 09:31:24.660  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 09:31:24.660  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 09:31:24.660  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 09:31:24.660  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 09:31:24.661  1362  1362 D BluetoothA2dp: Proxy object connected
08-10 09:31:24.661  3733  3746 D BluetoothMap: onBluetoothStateChange: up=true
,08-10 09:31:24.661  1362  1969 D BluetoothMap: onBluetoothStateChange: up=true
08-10 09:31:24.662   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 09:31:24.662  3663  3663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 09:31:24.664   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
08-10 09:31:24.665  3962  3962 D BluetoothMapService: onReceive
08-10 09:31:24.665  3962  3962 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 09:31:24.665  3962  3962 D BluetoothMapService: STATE_ON
,08-10 09:31:24.665  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 09:31:24.666  1362  1362 D BluetoothMap: Proxy object connected
08-10 09:31:24.666  1362  1362 D MapProfile: Bluetooth service connected
08-10 09:31:24.666  1362  1362 D BluetoothMap: getConnectedDevices()
08-10 09:31:24.666  3733  3733 D LocalBluetoothProfileManager: Adding local A2DP profile
08-10 09:31:24.666  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 09:31:24.668  3962  3962 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-10 09:31:24.669  3962  3962 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-10 09:31:24.670  3962  3962 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 09:31:24.672  3962  3962 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 09:31:24.672  3733  3733 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-10 09:31:24.673  3962  3962 D ObexServerSockets: Succeed to create listening sockets 
08-10 09:31:24.673  3962  3962 D ObexServerSockets0: startAccept()
08-10 09:31:24.673  3962  3962 D ObexServerSockets0: prepareForNewConnect()
08-10 09:31:24.678  3962  3962 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-10 09:31:24.678  3962  3962 D BluetoothSdpJni: SDP Create record success - handle: 0
08-10 09:31:24.678  3733  3733 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-10 09:31:24.679  3962  4000 D ObexServerSockets0: Accepting socket connection...
,08-10 09:31:24.679  3962  4001 D ObexServerSockets0: Accepting socket connection...
,08-10 09:31:24.683  3733  3733 D BluetoothA2dp: Proxy object connected
08-10 09:31:24.684  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 09:31:24.688  3733  3733 D DockEventReceiver: finishStartingService: stopping service
,08-10 09:31:24.691  3733  3733 D BluetoothPbap: Proxy object connected
,08-10 09:31:24.691  3962  3962 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-10 09:31:24.691  3962  3962 D ObexServerSockets0: prepareForNewConnect()
08-10 09:31:24.692  3733  3733 D PbapServerProfile: Bluetooth service connected
08-10 09:31:24.692  1362  1362 D BluetoothPbap: Proxy object connected
,08-10 09:31:24.692  1362  1362 D PbapServerProfile: Bluetooth service connected
,08-10 09:31:24.699  3962  4005 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 09:31:24.712  3962  4009 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 09:31:24.715  3962  4009 I BtOppRfcommListener: Accept thread started.
,08-10 09:31:24.756   875   875 D BluetoothHeadset: Proxy object connected
,08-10 09:31:24.756   875   875 D BluetoothHeadset: Proxy object connected
08-10 09:31:24.757  1362  1969 D BluetoothHeadset: Proxy object connected
,08-10 09:31:24.757  1362  1362 D HeadsetProfile: Bluetooth service connected
08-10 09:31:24.757  1735  1755 D BluetoothHeadset: Proxy object connected
,08-10 09:31:24.757   875   875 D BluetoothHeadset: Proxy object connected
08-10 09:31:24.758  1735  1755 D BluetoothHeadset: Proxy object connected
08-10 09:31:24.758   875   892 D BluetoothHeadset: Proxy object connected
,08-10 09:31:24.762   875   892 D BluetoothHeadset: Proxy object connected
,08-10 09:31:24.774  3733  3744 D BluetoothHeadset: Proxy object connected
,08-10 09:31:24.775  3733  3733 D HeadsetProfile: Bluetooth service connected
,08-10 09:31:26.073   875  1310 D ConnectivityService: handlePromptUnvalidated 101
,08-10 09:31:26.106  3962  3974 D BluetoothAdapterState: Current state: ON, message: 23
,08-10 09:31:26.106  3962  3974 D BluetoothAdapterProperties: Setting state to 13
08-10 09:31:26.107  3962  3974 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-10 09:31:26.108  3962  3974 D BluetoothAdapterProperties: onBluetoothDisable()
08-10 09:31:26.110  3962  3974 I BluetoothAdapterState: Entering PendingCommandState
,08-10 09:31:26.117  3962  3962 D BluetoothMapService: onReceive
08-10 09:31:26.118  3962  3962 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-10 09:31:26.118  3962  3962 D BluetoothMapService: STATE_TURNING_OFF
08-10 09:31:26.119  3962  3962 D BluetoothMapService: MAP Service closeService in
08-10 09:31:26.119  3962  3962 D BluetoothMapMasInstance0: MAP Service shutdown
08-10 09:31:26.119  3962  3962 D ObexServerSockets0: shutdown(block = true)
08-10 09:31:26.120  3962  4000 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-10 09:31:26.122  3962  3978 D BluetoothAdapterProperties: Scan Mode:20
08-10 09:31:26.123  3962  3974 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-10 09:31:26.124  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-10 09:31:26.125  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 09:31:26.125  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:26.125  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:26.125  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 09:31:26.125  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 09:31:26.125  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 09:31:26.125  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 09:31:26.125  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 09:31:26.125  3962  3962 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-10 09:31:26.126  3962  4001 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-10 09:31:26.126  3962  3986 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-10 09:31:26.126  3962  3962 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-10 09:31:26.127  3733  3733 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-10 09:31:26.127  3962  3962 I BtOppRfcommListener: stopping Accept Thread
,08-10 09:31:26.127  3962  4009 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-10 09:31:26.129  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 09:31:26.129  3962  4009 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-10 09:31:26.130  3663  3663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 09:31:26.134  3962  3962 D HeadsetService: Received stop request...Stopping profile...
,08-10 09:31:26.136   875   875 D BluetoothHeadset: Proxy object disconnected
,08-10 09:31:26.136   875   875 D BluetoothHeadset: Proxy object disconnected
08-10 09:31:26.137  1362  1376 D BluetoothHeadset: Proxy object disconnected
,08-10 09:31:26.137  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 09:31:26.137  3962  3962 D A2dpService: Received stop request...Stopping profile...
08-10 09:31:26.137  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 09:31:26.137  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:26.137  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:26.137  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 09:31:26.137  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-10 09:31:26.137  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 09:31:26.137  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 09:31:26.137  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 09:31:26.138  3962  3993 D A2dpStateMachine: Exit Disconnected: -1
,08-10 09:31:26.138  3663  3663 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-10 09:31:26.138  3663  3663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 09:31:26.140  1735  1763 D BluetoothHeadset: Proxy object disconnected
08-10 09:31:26.141  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:26.141   875   875 D BluetoothHeadset: Proxy object disconnected
,08-10 09:31:26.141  3733  3744 D BluetoothHeadset: Proxy object disconnected
08-10 09:31:26.141  3962  3962 D HidService: Received stop request...Stopping profile...
08-10 09:31:26.141  3962  3962 D HidService: Stopping Bluetooth HidService
,08-10 09:31:26.142   875   875 D BluetoothA2dp: Proxy object disconnected
08-10 09:31:26.142  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 09:31:26.143  3962  3962 D HealthService: Received stop request...Stopping profile...
08-10 09:31:26.143  1362  1362 D HeadsetProfile: Bluetooth service disconnected
08-10 09:31:26.144  1362  1362 D BluetoothA2dp: Proxy object disconnected
,08-10 09:31:26.144  1362  1362 D BluetoothInputDevice: Proxy object disconnected
08-10 09:31:26.144  1362  1362 D HidProfile: Bluetooth service disconnected
08-10 09:31:26.144  3733  3733 D DockEventReceiver: finishStartingService: stopping service
,08-10 09:31:26.145  3962  3962 D PanService: Received stop request...Stopping profile...
08-10 09:31:26.145  1362  1362 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 09:31:26.145  1362  1362 D PanProfile: Bluetooth service disconnected
,08-10 09:31:26.146  3733  3733 D BluetoothA2dp: Proxy object disconnected
08-10 09:31:26.146  3733  3733 D HeadsetProfile: Bluetooth service disconnected
08-10 09:31:26.147  3733  3733 D BluetoothInputDevice: Proxy object disconnected
08-10 09:31:26.147  3733  3733 D HidProfile: Bluetooth service disconnected
08-10 09:31:26.147  3733  3733 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-10 09:31:26.147  3733  3733 D PanProfile: Bluetooth service disconnected
08-10 09:31:26.147  3962  3962 D BluetoothMapService: Received stop request...Stopping profile...
08-10 09:31:26.147  3962  3962 D BluetoothMapService: stop()
08-10 09:31:26.148  3962  3962 D BluetoothMapAppObserver: deinitObservers()
,08-10 09:31:26.148  3962  3962 D BluetoothMapAppObserver: removeReceiver()
08-10 09:31:26.150  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 09:31:26.153  3733  3733 D BluetoothMap: Proxy object disconnected
,08-10 09:31:26.153  3733  3733 D MapProfile: Bluetooth service disconnected
08-10 09:31:26.154  1362  1362 D BluetoothMap: Proxy object disconnected
08-10 09:31:26.154  1362  1362 D MapProfile: Bluetooth service disconnected
,08-10 09:31:26.155  3962  3962 V BluetoothAdapterState: isTurningOff()=true
,08-10 09:31:26.155  3962  3962 V BluetoothAdapterState: isTurningOn()=false
08-10 09:31:26.155  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-10 09:31:26.155  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 09:31:26.156  3962  3962 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-10 09:31:26.157  3962  3978 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-10 09:31:26.157  3962  3984 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 09:31:26.157  3962  3984 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 09:31:26.157  3962  3962 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-10 09:31:26.157  3962  3984 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 09:31:26.157  3962  3978 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
08-10 09:31:26.157  3962  3962 V BluetoothAdapterState: isTurningOff()=true
,08-10 09:31:26.157  3962  3962 V BluetoothAdapterState: isTurningOn()=false
08-10 09:31:26.158  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-10 09:31:26.158  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
08-10 09:31:26.159  3962  3962 V BluetoothAdapterState: isTurningOff()=true
,08-10 09:31:26.159  3962  3962 V BluetoothAdapterState: isTurningOn()=false
08-10 09:31:26.159  3962  3984 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 09:31:26.159  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 09:31:26.159  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
08-10 09:31:26.159  3962  3984 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-10 09:31:26.159  3962  3984 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 09:31:26.159  3962  3984 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-10 09:31:26.159  3962  3962 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-10 09:31:26.159  3962  3984 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-10 09:31:26.159  3962  3962 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-10 09:31:26.159  3962  3984 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-10 09:31:26.160  3962  3978 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-10 09:31:26.160  3962  3962 V BluetoothAdapterState: isTurningOff()=true
08-10 09:31:26.160  3962  3962 V BluetoothAdapterState: isTurningOn()=false
08-10 09:31:26.160  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-10 09:31:26.160  3962  3978 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-10 09:31:26.160  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
08-10 09:31:26.160  3962  3962 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-10 09:31:26.160  3962  3978 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-10 09:31:26.160  3962  3962 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-10 09:31:26.161  3962  3962 V BluetoothAdapterState: isTurningOff()=true
08-10 09:31:26.161  3962  3962 V BluetoothAdapterState: isTurningOn()=false
08-10 09:31:26.161  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-10 09:31:26.161  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
08-10 09:31:26.161  3962  3962 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-10 09:31:26.161  3962  3962 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-10 09:31:26.163  3733  3733 D BluetoothPbap: Proxy object disconnected
08-10 09:31:26.163  3733  3733 D PbapServerProfile: Bluetooth service disconnected
08-10 09:31:26.164  1362  1362 D BluetoothPbap: Proxy object disconnected
08-10 09:31:26.164  1362  1362 D PbapServerProfile: Bluetooth service disconnected
08-10 09:31:26.164  3962  3962 D BluetoothMapService: MAP Service closeService in
08-10 09:31:26.164  3962  3962 V BluetoothAdapterState: isTurningOff()=true
,08-10 09:31:26.165  3962  3962 V BluetoothAdapterState: isTurningOn()=false
08-10 09:31:26.165  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-10 09:31:26.165  3962  3962 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 09:31:26.165  3962  3974 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-10 09:31:26.165  3962  3974 D BluetoothAdapterProperties: Setting state to 15
08-10 09:31:26.165  3962  3974 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-10 09:31:26.166  3962  3974 I BluetoothAdapterState: Entering BleOnState
08-10 09:31:26.166  3733  3746 D BluetoothPan: onBluetoothStateChange on: false
08-10 09:31:26.167  3962  3962 D BluetoothMapService: cleanup()
08-10 09:31:26.167  3962  3962 D BluetoothMapService: MAP Service closeService in
,08-10 09:31:26.169  3733  3744 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-10 09:31:26.170   875   892 D BluetoothA2dp: onBluetoothStateChange: up=false
08-10 09:31:26.170  1362  1969 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-10 09:31:26.170   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 09:31:26.171  3733  3746 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-10 09:31:26.172  3733  3744 D BluetoothPbap: onBluetoothStateChange: up=false
,08-10 09:31:26.172  1362  1376 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-10 09:31:26.173  1735  1755 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 09:31:26.174   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 09:31:26.174  1362  1377 D BluetoothPbap: onBluetoothStateChange: up=false
08-10 09:31:26.175  1362  1969 D BluetoothPan: onBluetoothStateChange on: false
08-10 09:31:26.177  3733  3746 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 09:31:26.177  1362  1376 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-10 09:31:26.178  3733  3744 D BluetoothMap: onBluetoothStateChange: up=false
,08-10 09:31:26.178  1362  1377 D BluetoothMap: onBluetoothStateChange: up=false
08-10 09:31:26.179   875   892 D BluetoothHeadset: onBluetoothStateChange: up=false
08-10 09:31:26.179  3962  3974 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-10 09:31:26.179  3962  3974 D BluetoothAdapterProperties: Setting state to 16
08-10 09:31:26.179  3962  3974 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-10 09:31:26.180  3962  3974 D BluetoothAdapterProperties: onBleDisable
,08-10 09:31:26.180  3962  3974 I BluetoothAdapterState: Entering PendingCommandState
08-10 09:31:26.180  3962  3975 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-10 09:31:26.183  3962  3984 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-10 09:31:26.183  3962  3984 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-10 09:31:26.184  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 09:31:26.185  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 09:31:26.186  3962  3978 D BluetoothAdapterProperties: Scan Mode:20
08-10 09:31:26.187  3733  3733 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-10 09:31:26.188  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 09:31:26.189  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:26.193  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 09:31:26.195  3733  3733 D DockEventReceiver: finishStartingService: stopping service
,08-10 09:31:26.384  3962  3978 I bt_hci  : shut_down
,08-10 09:31:26.385  3962  3982 D bt_hwcfg: hw_epilog_process
,08-10 09:31:26.387  3962  3982 I bt_vendor: low_power_mode_cb
,08-10 09:31:26.409  3962  3982 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-10 09:31:26.409  3962  3982 I bt_vendor: epilog_cb
08-10 09:31:26.409  3962  3982 I bt_hci  : epilog_finished_callback
,08-10 09:31:26.419  3962  3978 I bt_hci_h4: hal_close
,08-10 09:31:26.420  3962  3978 I bt_userial_vendor: device fd = 51 close
,08-10 09:31:26.547  3962  3975 D bt_stack_manager: event_shut_down_stack finished.
,08-10 09:31:26.549  3962  3974 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-10 09:31:26.555  3962  3974 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-10 09:31:26.555  3962  3962 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 09:31:26.557  3962  3962 D BtGatt.GattService: Received stop request...Stopping profile...
08-10 09:31:26.557  3962  3962 D BtGatt.GattService: stop()
08-10 09:31:26.558  3962  3962 D BtGatt.AdvertiseManager: advertise clients cleared
,08-10 09:31:26.564  3962  3962 V BluetoothAdapterState: isTurningOff()=false
,08-10 09:31:26.565  3962  3962 V BluetoothAdapterState: isTurningOn()=false
08-10 09:31:26.565  3962  3962 V BluetoothAdapterState: isBleTurningOn()=false
08-10 09:31:26.565  3962  3962 V BluetoothAdapterState: isBleTurningOff()=true
,08-10 09:31:26.566  3962  3974 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-10 09:31:26.567  3962  3974 D BluetoothAdapterProperties: Setting state to 10
08-10 09:31:26.567  3962  3974 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-10 09:31:26.570  3962  3974 I BluetoothAdapterState: Entering OffState
,08-10 09:31:26.572   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-10 09:31:26.613  3962  3962 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-10 09:31:26.613  3962  3962 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-10 09:31:26.614  3962  3962 I BluetoothServiceJni: cleanupNative: return from cleanup
08-10 09:31:26.615  3962  3975 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-10 09:31:26.618  3962  3975 D bt_stack_manager: event_clean_up_stack finished.
,08-10 09:31:26.619  3962  3962 I art     : System.exit called, status: 0
08-10 09:31:26.620  3962  3962 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-10 09:31:26.686   875   886 I ActivityManager: Process com.android.bluetooth (pid 3962) has died
,08-10 09:31:26.871  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:31:26.889  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:31:26.897  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:31:26.952  1520  2112 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 09:31:26.953  1520  2112 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-10 09:31:26.953  1520  2112 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:31:26.953  1520  2112 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:31:26.959  1905  2490 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-10 09:31:26.994  3385  3385 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 09:31:26.995  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-10 09:31:26.996  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-10 09:31:29.103  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
,08-10 09:31:29.104  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 09:31:32.112  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 09:31:32.112  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@294fb88 added. We now have 6 listener(s)
,08-10 09:31:32.113  3663  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 09:31:32.119  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 09:31:32.119  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@142b921 added. We now have 7 listener(s)
08-10 09:31:32.119  3663  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 09:31:32.121  3663  3713 I System.out: IsBluetoothEnabled
,08-10 09:31:32.134  3663  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:32.185   875   892 I ActivityManager: Start proc 4020:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-10 09:31:32.311  4020  4020 D AdapterServiceConfig: Adding HeadsetService
,08-10 09:31:32.311  4020  4020 D AdapterServiceConfig: Adding A2dpService
,08-10 09:31:32.311  4020  4020 D AdapterServiceConfig: Adding HidService
08-10 09:31:32.311  4020  4020 D AdapterServiceConfig: Adding HealthService
08-10 09:31:32.312  4020  4020 D AdapterServiceConfig: Adding PanService
,08-10 09:31:32.313  4020  4020 D AdapterServiceConfig: Adding GattService
08-10 09:31:32.313  4020  4020 D AdapterServiceConfig: Adding BluetoothMapService
,08-10 09:31:32.333   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@743865a:true
,08-10 09:31:32.333  4020  4020 D BluetoothAdapterState: make() - Creating AdapterState
,08-10 09:31:32.342  4020  4020 I bt_bluedroid: init
,08-10 09:31:32.343  4020  4032 I BluetoothAdapterState: Entering OffState
,08-10 09:31:32.349  4020  4033 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-10 09:31:32.350  4020  4033 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-10 09:31:32.350  4020  4033 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-10 09:31:32.350  4020  4033 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-10 09:31:32.352  4020  4020 I bt_bluedroid: get_profile_interface socket
,08-10 09:31:32.359  4020  4020 I bt_bluedroid: get_profile_interface sdp
08-10 09:31:32.359  4020  4036 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 09:31:32.363  4020  4036 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 09:31:32.367  4020  4031 I bt_bluedroid: config_hci_snoop_log
,08-10 09:31:32.371   875   892 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-10 09:31:32.384  4020  4032 D BluetoothAdapterState: Current state: OFF, message: 0
,08-10 09:31:32.384  4020  4032 D BluetoothAdapterProperties: Setting state to 14
,08-10 09:31:32.385  4020  4032 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-10 09:31:32.390  4020  4032 D BluetoothBondStateMachine: make
,08-10 09:31:32.395  4020  4037 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-10 09:31:32.404  4020  4032 I BluetoothAdapterState: Entering PendingCommandState
,08-10 09:31:32.407  4020  4020 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-10 09:31:32.414  4020  4020 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e34fafd
,08-10 09:31:32.416  4020  4020 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-10 09:31:32.417  4020  4020 D BtGatt.GattService: Received start request. Starting profile...
,08-10 09:31:32.418  4020  4020 D BtGatt.GattService: start()
,08-10 09:31:32.420  4020  4020 I bt_bluedroid: get_profile_interface gatt
,08-10 09:31:32.423  4020  4020 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e34fafd
,08-10 09:31:32.423  4020  4020 D BtGatt.AdvertiseManager: advertise manager created
,08-10 09:31:32.436  4020  4020 V BluetoothAdapterState: isTurningOff()=false
,08-10 09:31:32.437  4020  4020 V BluetoothAdapterState: isTurningOn()=false
08-10 09:31:32.437  4020  4020 V BluetoothAdapterState: isBleTurningOn()=true
08-10 09:31:32.437  4020  4020 V BluetoothAdapterState: isBleTurningOff()=false
08-10 09:31:32.437  4020  4032 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-10 09:31:32.438  4020  4032 I bt_bluedroid: enable
08-10 09:31:32.438  4020  4033 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-10 09:31:32.439  4020  4033 I bt_hci  : start_up
,08-10 09:31:32.458  4020  4033 I bt_vendor: alloc value 0xb3a6d189
,08-10 09:31:32.458  4020  4033 I bt_vendor: init
,08-10 09:31:32.458  4020  4033 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-10 09:31:32.458  4020  4033 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-10 09:31:32.567  4020  4033 D bt_hci  : start_up starting async portion
,08-10 09:31:32.568  4020  4040 I bt_hci  : event_finish_startup
08-10 09:31:32.568  4020  4040 I bt_hci_h4: hal_open
,08-10 09:31:32.569  4020  4040 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-10 09:31:32.580  4020  4040 I bt_userial_vendor: device fd = 51 open
,08-10 09:31:32.610  4020  4040 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 09:31:32.642  4020  4040 D bt_hwcfg: Chipset BCM4354A2
,08-10 09:31:32.642  4020  4040 D bt_hwcfg: Target name = [BCM4354A2]
08-10 09:31:32.643  4020  4040 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-10 09:31:33.308  4020  4040 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-10 09:31:33.309  4020  4040 D bt_hwcfg: Settlement delay -- 100 ms
08-10 09:31:33.310  4020  4040 I bt_hwcfg: Setting fw settlement delay to 100 
,08-10 09:31:33.426  4020  4040 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-10 09:31:33.427  4020  4040 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-10 09:31:33.457  4020  4040 I bt_hwcfg: vendor lib fwcfg completed
08-10 09:31:33.457  4020  4040 I bt_vendor: firmware callback
,08-10 09:31:33.458  4020  4040 I bt_hci  : firmware_config_callback
,08-10 09:31:33.468  4020  4042 I bt_btu  : btu_task pending for preload complete event
,08-10 09:31:33.468  4020  4042 I bt_btu_task: Bluetooth chip preload is complete
08-10 09:31:33.469  4020  4042 I bt_btu  : btu_task received preload complete event
,08-10 09:31:33.481  4020  4042 I         : BTE_InitTraceLevels -- TRC_HCI
,08-10 09:31:33.481  4020  4042 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-10 09:31:33.481  4020  4042 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-10 09:31:33.481  4020  4042 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-10 09:31:33.482  4020  4042 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-10 09:31:33.482  4020  4042 I         : BTE_InitTraceLevels -- TRC_A2D
08-10 09:31:33.482  4020  4042 I         : BTE_InitTraceLevels -- TRC_BNEP
08-10 09:31:33.483  4020  4042 I         : BTE_InitTraceLevels -- TRC_BTM
08-10 09:31:33.483  4020  4042 I         : BTE_InitTraceLevels -- TRC_GAP
,08-10 09:31:33.483  4020  4042 I         : BTE_InitTraceLevels -- TRC_PAN
08-10 09:31:33.483  4020  4042 I         : BTE_InitTraceLevels -- TRC_SDP
08-10 09:31:33.484  4020  4042 I         : BTE_InitTraceLevels -- TRC_GATT
,08-10 09:31:33.484  4020  4042 I         : BTE_InitTraceLevels -- TRC_SMP
08-10 09:31:33.484  4020  4042 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-10 09:31:33.484  4020  4042 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-10 09:31:33.619  4020  4042 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39ead9d
,08-10 09:31:33.619  4020  4042 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39ead9d 
,08-10 09:31:33.648  4020  4036 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-10 09:31:33.649  4020  4036 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-10 09:31:33.650  4020  4036 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-10 09:31:33.652  4020  4036 D BluetoothAdapterProperties: Name is: Nexus 6
,08-10 09:31:33.655  4020  4036 D BluetoothAdapterProperties: Scan Mode:20
,08-10 09:31:33.656  4020  4036 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-10 09:31:33.656  4020  4036 D bt_hci  : do_postload posting postload work item
08-10 09:31:33.657  4020  4040 I bt_hci  : event_postload
08-10 09:31:33.657  4020  4040 I bt_vendor: sco_config_cb
,08-10 09:31:33.657  4020  4040 I bt_hci  : sco_config_callback postload finished.
,08-10 09:31:33.661  4020  4036 D bt_bte_conf: Device ID record 1 : primary
,08-10 09:31:33.661  4020  4036 D bt_bte_conf:   vendorId            = 000f
,08-10 09:31:33.661  4020  4036 D bt_bte_conf:   vendorIdSource      = 0001
,08-10 09:31:33.661  4020  4036 D bt_bte_conf:   product             = 1200
08-10 09:31:33.661  4020  4036 D bt_bte_conf:   version             = 1436
,08-10 09:31:33.662  4020  4036 D bt_bte_conf:   clientExecutableURL = 
,08-10 09:31:33.662  4020  4036 D bt_bte_conf:   serviceDescription  = 
08-10 09:31:33.661  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 09:31:33.662  4020  4036 D bt_bte_conf:   documentationURL    = 
08-10 09:31:33.662  4020  4036 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-10 09:31:33.663  4020  4033 D bt_stack_manager: event_start_up_stack finished
,08-10 09:31:33.665  4020  4032 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-10 09:31:33.665  4020  4032 D BluetoothAdapterProperties: Setting state to 15
08-10 09:31:33.665  4020  4032 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-10 09:31:33.666  4020  4040 I bt_vendor: low_power_mode_cb
08-10 09:31:33.667  4020  4032 I BluetoothAdapterState: Entering BleOnState
08-10 09:31:33.673  4020  4032 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-10 09:31:33.673  4020  4032 D BluetoothAdapterProperties: Setting state to 11
08-10 09:31:33.674  4020  4032 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-10 09:31:33.681  4020  4020 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e34fafd
08-10 09:31:33.683  4020  4020 D HeadsetService: Received start request. Starting profile...
08-10 09:31:33.687  4020  4020 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-10 09:31:33.687  4020  4020 D HeadsetStateMachine: make
,08-10 09:31:33.690  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:33.709  4020  4020 D HeadsetStateMachine: max_hf_connections = 1
,08-10 09:31:33.709  4020  4020 I bt_bluedroid: get_profile_interface handsfree
08-10 09:31:33.709  4020  4036 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-10 09:31:33.710  4020  4036 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-10 09:31:33.711  4020  4032 I BluetoothAdapterState: Entering PendingCommandState,
08-10 09:31:33.714  4020  4020 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e34fafd
,08-10 09:31:33.715  4020  4020 D A2dpService: Received start request. Starting profile...
,08-10 09:31:33.716  4020  4020 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-10 09:31:33.717  4020  4020 I bt_bluedroid: get_profile_interface avrcp
,08-10 09:31:33.724  4020  4020 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-10 09:31:33.724  4020  4020 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-10 09:31:33.725  4020  4020 D A2dpStateMachine: make
,08-10 09:31:33.727  4020  4020 I bt_bluedroid: get_profile_interface a2dp
,08-10 09:31:33.728  4020  4036 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-10 09:31:33.730  4020  4020 I BluetoothHidServiceJni: classInitNative: succeeds
08-10 09:31:33.730  4020  4051 D A2dpStateMachine: Enter Disconnected: -2
,08-10 09:31:33.732  4020  4020 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e34fafd
08-10 09:31:33.733  4020  4020 D HidService: Received start request. Starting profile...
08-10 09:31:33.733  4020  4020 I bt_bluedroid: get_profile_interface hidhost
08-10 09:31:33.733  4020  4020 D HidService: setHidService(): set to: null
08-10 09:31:33.733  4020  4036 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39cc3e5
08-10 09:31:33.733  4020  4036 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-10 09:31:33.734  4020  4020 I BluetoothHealthServiceJni: classInitNative: succeeds
08-10 09:31:33.735  4020  4020 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e34fafd
08-10 09:31:33.736  4020  4020 D HealthService: Received start request. Starting profile...
08-10 09:31:33.736  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 09:31:33.739  4020  4020 I bt_bluedroid: get_profile_interface health
,08-10 09:31:33.743  4020  4020 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-10 09:31:33.745  4020  4020 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e34fafd
,08-10 09:31:33.746  4020  4020 D PanService: Received start request. Starting profile...
,08-10 09:31:33.747  4020  4020 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-10 09:31:33.747  4020  4020 I bt_bluedroid: get_profile_interface pan
,08-10 09:31:33.748  4020  4036 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan,
,08-10 09:31:33.757  4020  4020 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e34fafd
,08-10 09:31:33.758  4020  4020 D BluetoothMapService: Received start request. Starting profile...
,08-10 09:31:33.758  4020  4020 D BluetoothMapService: start()
,08-10 09:31:33.763  4020  4020 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-10 09:31:33.763  4020  4020 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-10 09:31:33.764  4020  4020 D BluetoothMapAppObserver: createReceiver()
08-10 09:31:33.765  4020  4020 D BluetoothMapAppObserver: initObservers()
08-10 09:31:33.765  4020  4020 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-10 09:31:33.772  4020  4048 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-10 09:31:33.772  4020  4020 V BluetoothAdapterState: isTurningOff()=false
08-10 09:31:33.772  4020  4020 V BluetoothAdapterState: isTurningOn()=true
08-10 09:31:33.773  4020  4020 V BluetoothAdapterState: isBleTurningOn()=false
08-10 09:31:33.773  4020  4020 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 09:31:33.775  4020  4020 V BluetoothAdapterState: isTurningOff()=false
,08-10 09:31:33.775  4020  4020 V BluetoothAdapterState: isTurningOn()=true
08-10 09:31:33.776  4020  4020 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 09:31:33.776  4020  4020 V BluetoothAdapterState: isBleTurningOff()=false
08-10 09:31:33.776  4020  4020 V BluetoothAdapterState: isTurningOff()=false
08-10 09:31:33.776  4020  4020 V BluetoothAdapterState: isTurningOn()=true
,08-10 09:31:33.776  4020  4020 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 09:31:33.776  4020  4020 V BluetoothAdapterState: isBleTurningOff()=false
08-10 09:31:33.777  4020  4020 V BluetoothAdapterState: isTurningOff()=false
08-10 09:31:33.777  4020  4020 V BluetoothAdapterState: isTurningOn()=true,
08-10 09:31:33.777  4020  4020 V BluetoothAdapterState: isBleTurningOn()=false
,08-10 09:31:33.777  4020  4020 V BluetoothAdapterState: isBleTurningOff()=false
08-10 09:31:33.778  4020  4020 V BluetoothAdapterState: isTurningOff()=false
,08-10 09:31:33.778  4020  4020 V BluetoothAdapterState: isTurningOn()=true
,08-10 09:31:33.778  4020  4020 V BluetoothAdapterState: isBleTurningOn()=false
08-10 09:31:33.778  4020  4020 V BluetoothAdapterState: isBleTurningOff()=false
08-10 09:31:33.778  4020  4020 V BluetoothAdapterState: isTurningOff()=false
08-10 09:31:33.779  4020  4020 V BluetoothAdapterState: isTurningOn()=true
08-10 09:31:33.779  4020  4020 V BluetoothAdapterState: isBleTurningOn()=false
08-10 09:31:33.779  4020  4020 V BluetoothAdapterState: isBleTurningOff()=false
,08-10 09:31:33.780  4020  4032 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-10 09:31:33.780  4020  4032 D BluetoothAdapterProperties: ScanMode =  20
08-10 09:31:33.780  4020  4032 D BluetoothAdapterProperties: State =  11
,08-10 09:31:33.781  4020  4036 D BluetoothAdapterProperties: Scan Mode:21
,08-10 09:31:33.782  4020  4032 D BluetoothAdapterProperties: Setting state to 12
,08-10 09:31:33.782  4020  4036 D BluetoothAdapterProperties: Discoverable Timeout:120
08-10 09:31:33.782  4020  4032 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-10 09:31:33.783  4020  4032 I BluetoothAdapterState: Entering OnState
,08-10 09:31:33.783  3733  3746 D BluetoothPan: onBluetoothStateChange on: true
08-10 09:31:33.786  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 09:31:33.786  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:33.786  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:33.786  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 09:31:33.786  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
,08-10 09:31:33.786  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 09:31:33.786  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 09:31:33.786  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-10 09:31:33.786  3733  3744 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-10 09:31:33.789  3663  3663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-10 09:31:33.789  3733  3733 D BluetoothPan: BluetoothPAN Proxy object connected
,08-10 09:31:33.789  3733  3733 D PanProfile: Bluetooth service connected
08-10 09:31:33.789   875   892 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-10 09:31:33.790  1362  1969 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 09:31:33.791   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true,
08-10 09:31:33.791  4020  4020 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-10 09:31:33.791  3733  3744 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-10 09:31:33.792  4020  4020 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-10 09:31:33.798  3733  3746 D BluetoothPbap: onBluetoothStateChange: up=true
,08-10 09:31:33.798  4020  4020 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 09:31:33.797  3733  3733 D BluetoothInputDevice: Proxy object connected
08-10 09:31:33.799  3733  3733 D HidProfile: Bluetooth service connected,
08-10 09:31:33.801  4020  4020 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-10 09:31:33.801  1362  1376 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-10 09:31:33.803  4020  4020 D ObexServerSockets: Succeed to create listening sockets 
08-10 09:31:33.803  4020  4020 D ObexServerSockets0: startAccept()
,08-10 09:31:33.803  4020  4020 D ObexServerSockets0: prepareForNewConnect()
,08-10 09:31:33.804  1362  1362 D BluetoothInputDevice: Proxy object connected
,08-10 09:31:33.804  1362  1362 D HidProfile: Bluetooth service connected
,08-10 09:31:33.804  1735  1755 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 09:31:33.805   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 09:31:33.805  1362  1969 D BluetoothPbap: onBluetoothStateChange: up=true
08-10 09:31:33.805  4020  4020 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-10 09:31:33.806  4020  4020 D BluetoothSdpJni: SDP Create record success - handle: 0
,08-10 09:31:33.807   875   875 D BluetoothA2dp: Proxy object connected
08-10 09:31:33.807  4020  4057 D ObexServerSockets0: Accepting socket connection...
08-10 09:31:33.808  3733  3733 D BluetoothA2dp: Proxy object connected
,08-10 09:31:33.808  4020  4058 D ObexServerSockets0: Accepting socket connection...
08-10 09:31:33.808  1362  1377 D BluetoothPan: onBluetoothStateChange on: true
,08-10 09:31:33.811  1362  1362 D BluetoothPan: BluetoothPAN Proxy object connected
08-10 09:31:33.811  1362  1362 D PanProfile: Bluetooth service connected
,08-10 09:31:33.811  3733  3744 D BluetoothHeadset: onBluetoothStateChange: up=true
08-10 09:31:33.812  1362  1969 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-10 09:31:33.814  1362  1362 D BluetoothA2dp: Proxy object connected
08-10 09:31:33.815  3733  3746 D BluetoothMap: onBluetoothStateChange: up=true
,08-10 09:31:33.818  1362  1377 D BluetoothMap: onBluetoothStateChange: up=true
,08-10 09:31:33.819  3733  3733 D BluetoothMap: Proxy object connected
,08-10 09:31:33.819  3733  3733 D MapProfile: Bluetooth service connected
08-10 09:31:33.819  3733  3733 D BluetoothMap: getConnectedDevices()
,08-10 09:31:33.820  1362  1362 D BluetoothMap: Proxy object connected
,08-10 09:31:33.821  1362  1362 D MapProfile: Bluetooth service connected
,08-10 09:31:33.821  1362  1362 D BluetoothMap: getConnectedDevices()
08-10 09:31:33.821   875   892 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-10 09:31:33.823   875   875 I Telecom : BluetoothPhoneService: queryPhoneState
,08-10 09:31:33.824  4020  4020 D BluetoothMapService: onReceive
,08-10 09:31:33.824  4020  4020 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-10 09:31:33.826  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 09:31:33.826  4020  4020 D BluetoothMapService: STATE_ON
,08-10 09:31:33.832  3733  3733 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-10 09:31:33.839  1520  1520 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-10 09:31:33.841  3733  3733 D DockEventReceiver: finishStartingService: stopping service
,08-10 09:31:33.848  3733  3733 D BluetoothPbap: Proxy object connected
,08-10 09:31:33.848  3733  3733 D PbapServerProfile: Bluetooth service connected
,08-10 09:31:33.852  1362  1362 D BluetoothPbap: Proxy object connected
,08-10 09:31:33.852  1362  1362 D PbapServerProfile: Bluetooth service connected
,08-10 09:31:33.854  4020  4020 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-10 09:31:33.854  4020  4020 D ObexServerSockets0: prepareForNewConnect()
08-10 09:31:33.857  4020  4064 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 09:31:33.872  4020  4068 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-10 09:31:33.873  4020  4068 I BtOppRfcommListener: Accept thread started.
,08-10 09:31:33.892   875   875 D BluetoothHeadset: Proxy object connected
,08-10 09:31:33.892   875   875 D BluetoothHeadset: Proxy object connected
,08-10 09:31:33.892  1362  1969 D BluetoothHeadset: Proxy object connected
08-10 09:31:33.893  1362  1362 D HeadsetProfile: Bluetooth service connected
08-10 09:31:33.893  1735  1870 D BluetoothHeadset: Proxy object connected
08-10 09:31:33.893   875   875 D BluetoothHeadset: Proxy object connected
,08-10 09:31:33.894  3733  3744 D BluetoothHeadset: Proxy object connected
08-10 09:31:33.895  3733  3733 D HeadsetProfile: Bluetooth service connected
,08-10 09:31:33.905  1735  1852 D BluetoothHeadset: Proxy object connected
,08-10 09:31:33.905   875   892 D BluetoothHeadset: Proxy object connected
,08-10 09:31:33.912  3733  3746 D BluetoothHeadset: Proxy object connected
,08-10 09:31:33.912  3733  3733 D HeadsetProfile: Bluetooth service connected
,08-10 09:31:33.922   875   892 D BluetoothHeadset: Proxy object connected
,08-10 09:31:34.158  3663  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 09:31:34.158  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:34.158  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:34.158  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-10 09:31:34.158  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 09:31:34.158  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 09:31:34.158  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 09:31:34.158  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 09:31:34.165  3663  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-10 09:31:34.169  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 09:31:34.170  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e571146 added. We now have 8 listener(s)
08-10 09:31:34.170  3663  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 09:31:34.176   875  2065 D WifiService: setWifiEnabled: false pid=3663, uid=10000
,08-10 09:31:34.176   875  2065 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 09:31:34.188  3663  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:34.190   875  1622 D WifiService: setWifiEnabled: true pid=3663, uid=10000
08-10 09:31:34.190   875  1622 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-10 09:31:34.204   875  1308 D WifiConfigStore: Loading config and enabling all networks 
,08-10 09:31:34.221  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 09:31:34.221  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:34.221  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:34.221  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:34.221  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 09:31:34.221  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 09:31:34.221  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 09:31:34.221  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 09:31:34.228  3663  3663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 09:31:34.240   875  1308 D WifiConfigStore: loaded 0 passpoint configs
,08-10 09:31:34.241   875  1308 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-10 09:31:34.242   875  1308 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-10 09:31:34.243   875  1308 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-10 09:31:34.243   875  1308 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-10 09:31:34.243   875  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-10 09:31:34.243   875  1308 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-10 09:31:34.257   370   873 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-10 09:31:34.257   875  1308 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.09 rxSuccessRate=0.15 delta 1000 -> 1000
,08-10 09:31:34.258   370   873 D CommandListener: Setting iface cfg
08-10 09:31:34.259   875  1307 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
,08-10 09:31:34.260   875  1307 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-10 09:31:34.260   875  1308 E native  : do suspend true
,08-10 09:31:34.275   875  1308 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-10 09:31:34.275   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 09:31:34.276   875  1307 D WifiNative-HAL: p2pGetDeviceAddress
,08-10 09:31:34.284   875  1308 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-10 09:31:34.285   875  1307 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-10 09:31:34.359   875  1308 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-10 09:31:35.071  1470  1470 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-10 09:31:35.122   875  1308 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-10 09:31:35.125  1470  1470 E wpa_supplicant: PNO: In assoc process
,08-10 09:31:35.126   875  1308 E WifiStateMachine:  Fail to set up pno, want true now false
,08-10 09:31:35.209  3663  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 09:31:35.209  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:35.209  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:35.209  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:35.209  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 09:31:35.209  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-10 09:31:35.209  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-10 09:31:35.209  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-10 09:31:35.213  3663  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-10 09:31:35.217  3663  3713 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-10 09:31:35.218  3663  3713 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-10 09:31:35.221  3663  3713 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@85b49f9 Bundle[{}]
,08-10 09:31:35.226  3663  3713 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-10 09:31:35.226  3663  3713 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-10 09:31:35.228  3663  3713 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-10 09:31:35.230  3663  3713 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-10 09:31:35.232  3663  3713 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-10 09:31:35.233  3663  3713 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-10 09:31:35.246  3663  3713 I System.out: Running OutgoingSocketThread
,08-10 09:31:35.250  3663  4075 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 423)
,08-10 09:31:35.261  3663  4075 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40736
,08-10 09:31:35.262  3663  4075 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-10 09:31:35.505  1470  1470 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-10 09:31:35.550  1470  1470 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-10 09:31:35.551  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-10 09:31:35.557   875  1308 D WifiConfigStore: Retrieve network priorities after PNO.
,08-10 09:31:35.570   875  1308 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-10 09:31:35.571   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-10 09:31:35.571   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-10 09:31:35.594   875  1308 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-10 09:31:35.618   370   873 D CommandListener: Setting iface cfg
08-10 09:31:35.620   875  1308 D WifiStateMachine: Start Dhcp Watchdog 3
08-10 09:31:35.638   875  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-10 09:31:35.664   875  4078 D DhcpClient: Receive thread started
,08-10 09:31:35.751   875  1308 E native  : do suspend false
,08-10 09:31:35.773   875  1987 D DhcpClient: Broadcasting DHCPDISCOVER
,08-10 09:31:35.787   875  4078 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172782, domain null
,08-10 09:31:35.788   875  1987 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172782 seconds
,08-10 09:31:35.794   875  1987 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-10 09:31:35.807   875  4078 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-10 09:31:35.808   875  1987 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-10 09:31:35.815   370   873 D CommandListener: Setting iface cfg
,08-10 09:31:35.827   875  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-10 09:31:35.829   875  1987 D DhcpClient: Scheduling renewal in 86399s
,08-10 09:31:35.832   875  1308 E native  : do suspend true
,08-10 09:31:35.859   875  1308 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-10 09:31:35.863   875  1308 D WifiConfigStore: No blacklist allowed without epno enabled
,08-10 09:31:35.865   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-10 09:31:35.867   875  1310 D ConnectivityService: Adding iface wlan0 to network 102
,08-10 09:31:35.880   875  1308 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-10 09:31:35.921   875  1310 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-10 09:31:35.921   875  1310 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-10 09:31:35.924   875  1310 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-10 09:31:35.927   875  1310 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-10 09:31:35.930   875  1310 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-10 09:31:35.941   875  1310 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-10 09:31:35.945   875  1310 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-10 09:31:35.945   875  1310 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102],
,08-10 09:31:35.946   875  1310 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,08-10 09:31:35.946   875  1310 D ConnectivityService:    accepting network in place of null
,08-10 09:31:35.946   875  1308 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: [],
,08-10 09:31:35.948   875  1310 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-10 09:31:35.949   875  1308 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-10 09:31:35.958   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=164568, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:31:36.007   370   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 09:31:36.028   875  4076 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:805::200e
,08-10 09:31:36.051   370   873 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-10 09:31:36.055   875  1310 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-10 09:31:36.055   875  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-10 09:31:36.058   875  1310 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-10 09:31:36.059   875   892 D Tethering: MasterInitialState.processMessage what=3
,08-10 09:31:36.082  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-10 09:31:36.082  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:36.082  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:36.082  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:36.082  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 09:31:36.082  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 09:31:36.082  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 09:31:36.082  3663  3663 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 09:31:36.085  3663  3663 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 09:31:36.094  1887  1887 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-10 09:31:36.104  1887  1887 D SystemUpdateService: onCreate
,08-10 09:31:36.120  1887  1887 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-10 09:31:36.127  1887  4087 I SystemUpdateService: active receiver: enabled
,08-10 09:31:36.129  1887  4087 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-10 09:31:36.139  1887  4087 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-10 09:31:36.139  1887  4087 I SystemUpdateService: now status is 0 (complete)
08-10 09:31:36.140  1887  4087 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-10 09:31:36.141  1887  4087 I SystemUpdateService: file has been verified
,08-10 09:31:36.162  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:31:36.170  1887  4087 I SystemUpdateService: OTA package size = 12249756
,08-10 09:31:36.174  1887  1887 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-10 09:31:36.175  1887  2345 I iu.UploadsManager: num queued entries: 0
,08-10 09:31:36.175  1887  2345 I iu.UploadsManager: num updated entries: 0
,08-10 09:31:36.199  1887  4087 I SystemUpdateService: showing system update notification
,08-10 09:31:36.201  1887  4091 I MDM     : [217] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-10 09:31:36.201  1887  4091 W BaseAppContext: Using Auth Proxy for data requests.
,08-10 09:31:36.204  1887  4091 V GoogleAuthProtoRequest: [217] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 09:31:36.204  3616  4092 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 09:31:36.218  1887  2345 I iu.SyncManager: NEXT; no task
,08-10 09:31:36.222  1887  1887 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-10 09:31:36.224  1887  1887 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-10 09:31:36.226  3788  3788 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-10 09:31:36.237  3788  3788 D SprintDMHelper: simOperator: 
08-10 09:31:36.237  3788  3788 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-10 09:31:36.249  3663  3713 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 424)
,08-10 09:31:36.249  3663  3713 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 424)
,08-10 09:31:36.254  3663  3713 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 429)
,08-10 09:31:36.256  3663  3713 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-10 09:31:36.256  3663  3713 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 430)
,08-10 09:31:36.260  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-10 09:31:36.261  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@479df07 added. We now have 2 listener(s)
,08-10 09:31:36.265  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 09:31:36.265  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-10 09:31:36.265  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 09:31:36.265  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 09:31:36.266  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@424834 added. We now have 9 listener(s)
,08-10 09:31:36.266  3663  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 09:31:36.266  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 09:31:36.267   875  4076 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 10 Aug 2016 07:31:36 GMT], X-Android-Received-Millis=[1470814296267], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470814296236]}
,08-10 09:31:36.268   875  1310 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-10 09:31:36.269  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 09:31:36.268   875  1310 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-10 09:31:36.269   875  1310 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-10 09:31:36.273  3663  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 09:31:36.273  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:36.273  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:36.273  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:36.273  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 09:31:36.273  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 09:31:36.273  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 09:31:36.273  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 09:31:36.274   875  1310 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-10 09:31:36.274  3663  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 09:31:36.274  3663  3713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 09:31:36.275  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 09:31:36.275  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@762fbd2 added. We now have 3 listener(s)
,08-10 09:31:36.276  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 09:31:36.276  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 09:31:36.276  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 09:31:36.277  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 09:31:36.277  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b64a3 added. We now have 10 listener(s)
08-10 09:31:36.277  3663  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 09:31:36.277  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 09:31:36.278  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:36.278  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 09:31:36.278  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:36.278  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:36.278  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-10 09:31:36.278  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 09:31:36.278  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@479df07 removed from the list
08-10 09:31:36.278  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:36.278  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@424834 removed from the list
08-10 09:31:36.278  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 09:31:36.279  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:36.279  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 09:31:36.279  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:36.279  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:36.280  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:36.280  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:36.280  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:36.280  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@424834 not in the list
08-10 09:31:36.281  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:36.281  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 09:31:36.281  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:36.281  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:36.281  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:36.282  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@44b64a3 removed from the list
08-10 09:31:36.282  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:36.282  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:36.282  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:36.282  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-10 09:31:36.282  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@762fbd2 removed from the list
08-10 09:31:36.282  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 09:31:36.282  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 09:31:36.283  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b3a0 added. We now have 2 listener(s)
,08-10 09:31:36.286  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 09:31:36.286  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 09:31:36.286  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 09:31:36.286  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 09:31:36.286  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6786b59 added. We now have 9 listener(s)
08-10 09:31:36.287  3663  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 09:31:36.287  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 09:31:36.289  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 09:31:36.295  3663  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 09:31:36.295  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:36.295  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:36.295  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:36.295  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 09:31:36.295  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 09:31:36.295  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 09:31:36.295  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 09:31:36.296  3663  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 09:31:36.297  3663  3713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 09:31:36.297  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 09:31:36.297  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c25a7ff added. We now have 3 listener(s)
,08-10 09:31:36.298  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 09:31:36.298  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 09:31:36.298  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 09:31:36.299  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 09:31:36.299  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37269cc added. We now have 10 listener(s)
08-10 09:31:36.299  3663  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 09:31:36.299  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 09:31:36.299  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 09:31:36.299  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 09:31:36.299  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 09:31:36.299  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-10 09:31:36.300  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:36.304  3663  3713 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-10 09:31:36.304  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 09:31:36.305  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:36.307  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 09:31:36.308  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-10 09:31:36.308  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-10 09:31:36.311  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-10 09:31:36.311  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-10 09:31:36.311  3663  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-10 09:31:36.312  3663  3713 D BluetoothAdapter: STATE_ON
,08-10 09:31:36.315  4020  4060 D BtGatt.GattService: registerClient() - UUID=c2f78ff7-1086-4aa8-ace7-57cc32ca9406
,08-10 09:31:36.316  4020  4036 D BtGatt.GattService: onClientRegistered() - UUID=c2f78ff7-1086-4aa8-ace7-57cc32ca9406, clientIf=5
,08-10 09:31:36.316  3663  3673 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-10 09:31:36.317  4020  4031 D BtGatt.GattService: start scan with filters
,08-10 09:31:36.320  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-10 09:31:36.320  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-10 09:31:36.320  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-10 09:31:36.320  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-10 09:31:36.320  4020  4039 D BtGatt.ScanManager: handling starting scan
,08-10 09:31:36.322  4020  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e34fafd
,08-10 09:31:36.323  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 09:31:36.323  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-10 09:31:36.323  3663  3663 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-10 09:31:36.326  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-10 09:31:36.326  4020  4036 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-10 09:31:36.326  4020  4036 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 09:31:36.327  4020  4039 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-10 09:31:36.327  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 09:31:36.329  3663  3713 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-10 09:31:36.329  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:36.329  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-10 09:31:36.329  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-10 09:31:36.329  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:36.329  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 09:31:36.329  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-10 09:31:36.329  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 09:31:36.329  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 09:31:36.329  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 09:31:36.330  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 09:31:36.330  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-10 09:31:36.330  3663  3713 D BluetoothAdapter: STATE_ON
,08-10 09:31:36.331  4020  4031 D BtGatt.GattService: stopScan() - queue size =1
08-10 09:31:36.332  4020  4059 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-10 09:31:36.333  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-10 09:31:36.333  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-10 09:31:36.333  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-10 09:31:36.333  4020  4036 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-10 09:31:36.334  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-10 09:31:36.334  4020  4036 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:36.334  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-10 09:31:36.334  4020  4039 D BtGatt.ScanManager: Starting BLE batch scan
08-10 09:31:36.334  4020  4039 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-10 09:31:36.335  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 09:31:36.335  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-10 09:31:36.335  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 09:31:36.336  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 09:31:36.336  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 09:31:36.337  3663  3663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 09:31:36.337  3663  3663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 09:31:36.337  3663  3663 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-10 09:31:36.343  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-10 09:31:36.344  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:36.344  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 09:31:36.344  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:36.344  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:36.344  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 09:31:36.345  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 09:31:36.345  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5d5b3a0 removed from the list
,08-10 09:31:36.345  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:36.345  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6786b59 removed from the list
,08-10 09:31:36.345  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:36.345  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:36.346  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:36.346  4020  4036 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-10 09:31:36.346  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 09:31:36.346  4020  4036 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:36.347  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:36.348  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:36.348  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:36.348  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6786b59 not in the list
08-10 09:31:36.348  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:36.348  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-10 09:31:36.349  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:36.349  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:36.349  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:36.349  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37269cc removed from the list
08-10 09:31:36.350  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:36.350  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:36.350  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:36.350  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-10 09:31:36.350  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c25a7ff removed from the list
08-10 09:31:36.351  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 09:31:36.351  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64256b8 added. We now have 2 listener(s)
08-10 09:31:36.352  4020  4036 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-10 09:31:36.352  4020  4036 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 09:31:36.355  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 09:31:36.355  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 09:31:36.355  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 09:31:36.355  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 09:31:36.355  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afb2c91 added. We now have 9 listener(s)
08-10 09:31:36.355  3663  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 09:31:36.356  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-10 09:31:36.359  4020  4036 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-10 09:31:36.359  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 09:31:36.359  4020  4036 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:36.360  4020  4039 D BtGatt.ScanManager: stopping BLe Batch
,08-10 09:31:36.364  3663  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 09:31:36.364  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:36.364  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:36.364  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:36.364  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 09:31:36.364  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 09:31:36.364  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 09:31:36.364  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 09:31:36.365  4020  4036 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-10 09:31:36.366  4020  4036 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:36.366  4020  4039 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5,
08-10 09:31:36.366  3663  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 09:31:36.366  3663  3713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 09:31:36.366  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 09:31:36.366  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37297f7 added. We now have 3 listener(s)
,08-10 09:31:36.368  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 09:31:36.370  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 09:31:36.371  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 09:31:36.372  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 09:31:36.372  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 09:31:36.372  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 09:31:36.372  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2222664 added. We now have 10 listener(s)
08-10 09:31:36.372  4020  4036 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-10 09:31:36.372  3663  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 09:31:36.372  4020  4036 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:36.372  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-10 09:31:36.374  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 09:31:36.374  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-10 09:31:36.374  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 09:31:36.374  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 09:31:36.374  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-10 09:31:36.376  3663  3713 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-10 09:31:36.376  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-10 09:31:36.379  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 09:31:36.380  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-10 09:31:36.380  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-10 09:31:36.383  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-10 09:31:36.383  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-10 09:31:36.383  3663  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-10 09:31:36.383  3663  3713 D BluetoothAdapter: STATE_ON
,08-10 09:31:36.384  1520  4099 I VacuumService: Vacuum at: now=1470814296384 tag=VacuumService
,08-10 09:31:36.385  4020  4060 D BtGatt.GattService: registerClient() - UUID=32ccd1d5-5904-4274-b53c-f6a21e0725e1
,08-10 09:31:36.385  4020  4036 D BtGatt.GattService: onClientRegistered() - UUID=32ccd1d5-5904-4274-b53c-f6a21e0725e1, clientIf=5
08-10 09:31:36.386  3663  3673 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-10 09:31:36.386  4020  4031 D BtGatt.GattService: start scan with filters
,08-10 09:31:36.388  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-10 09:31:36.388  4020  4039 D BtGatt.ScanManager: handling starting scan
,08-10 09:31:36.388  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-10 09:31:36.388  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-10 09:31:36.388  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-10 09:31:36.390  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 09:31:36.390  3663  3663 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 09:31:36.391  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-10 09:31:36.392  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-10 09:31:36.394  4020  4036 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-10 09:31:36.394  4020  4036 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:36.394  4020  4039 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-10 09:31:36.395  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 09:31:36.395  3663  3713 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-10 09:31:36.395  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 09:31:36.395  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:36.395  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-10 09:31:36.396  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:36.396  3345  4095 I Babel   : connection state changed from DISCONNECTED to CONNECTED
08-10 09:31:36.396  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 09:31:36.396  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-10 09:31:36.396  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-10 09:31:36.396  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@64256b8 removed from the list
,08-10 09:31:36.396  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:36.396  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afb2c91 removed from the list
08-10 09:31:36.396  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:36.396  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 09:31:36.397  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-10 09:31:36.397  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-10 09:31:36.397  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:36.397  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 09:31:36.398  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:36.398  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 09:31:36.398  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 09:31:36.398  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@afb2c91 not in the list
08-10 09:31:36.398  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-10 09:31:36.398  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-10 09:31:36.398  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 09:31:36.398  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-10 09:31:36.398  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-10 09:31:36.399  4020  4036 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-10 09:31:36.399  3663  3713 D BluetoothAdapter: STATE_ON
,08-10 09:31:36.399  4020  4036 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:36.399  4020  4039 D BtGatt.ScanManager: Starting BLE batch scan
,08-10 09:31:36.400  4020  4039 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-10 09:31:36.400  4020  4031 D BtGatt.GattService: stopScan() - queue size =1
08-10 09:31:36.400  4020  4059 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-10 09:31:36.401  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-10 09:31:36.401  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-10 09:31:36.401  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
08-10 09:31:36.401  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-10 09:31:36.401  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-10 09:31:36.402  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,08-10 09:31:36.402  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-10 09:31:36.402  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 09:31:36.402  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-10 09:31:36.403  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:36.403  3663  3663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-10 09:31:36.403  3663  3663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 09:31:36.404  3663  3663 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-10 09:31:36.404  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-10 09:31:36.404  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:36.404  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-10 09:31:36.404  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2222664 removed from the list
,08-10 09:31:36.404  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:36.404  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:36.404  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:36.404  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-10 09:31:36.404  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37297f7 removed from the list
,08-10 09:31:36.405  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 09:31:36.405  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0d44d0 added. We now have 2 listener(s)
,08-10 09:31:36.406  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-10 09:31:36.407  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 09:31:36.407  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-10 09:31:36.407  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 09:31:36.407  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7ddcc9 added. We now have 9 listener(s)
,08-10 09:31:36.407  3663  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-10 09:31:36.407  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 09:31:36.410  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 09:31:36.413  4020  4036 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-10 09:31:36.413  4020  4036 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 09:31:36.415  3663  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 09:31:36.415  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:36.415  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:36.415  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:36.415  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 09:31:36.415  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 09:31:36.415  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 09:31:36.415  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-10 09:31:36.416  3663  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 09:31:36.416  3663  3713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 09:31:36.418  4020  4036 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-10 09:31:36.418  4020  4036 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:36.417  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 09:31:36.418  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7e8eef added. We now have 3 listener(s)
,08-10 09:31:36.418  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 09:31:36.420  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 09:31:36.420  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 09:31:36.420  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 09:31:36.420  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-10 09:31:36.420  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 09:31:36.420  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@349ddfc added. We now have 10 listener(s)
08-10 09:31:36.420  3663  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 09:31:36.420  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 09:31:36.420  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-10 09:31:36.420  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-10 09:31:36.421  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 09:31:36.421  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-10 09:31:36.423  3663  3713 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-10 09:31:36.423  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-10 09:31:36.427  4020  4036 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-10 09:31:36.427  4020  4036 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:36.428  4020  4039 D BtGatt.ScanManager: stopping BLe Batch
,08-10 09:31:36.429  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-10 09:31:36.430  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-10 09:31:36.430  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-10 09:31:36.433  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-10 09:31:36.433  4020  4036 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-10 09:31:36.433  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-10 09:31:36.433  4020  4036 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:36.433  3663  3713 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-10 09:31:36.433  4020  4039 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-10 09:31:36.434  3663  3713 D BluetoothAdapter: STATE_ON
,08-10 09:31:36.435  4020  4060 D BtGatt.GattService: registerClient() - UUID=93fe1cd0-540e-4586-ac3c-352efb7745b4
,08-10 09:31:36.436  4020  4036 D BtGatt.GattService: onClientRegistered() - UUID=93fe1cd0-540e-4586-ac3c-352efb7745b4, clientIf=5
08-10 09:31:36.436  3663  3675 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-10 09:31:36.436  4020  4059 D BtGatt.GattService: start scan with filters
,08-10 09:31:36.438  4020  4036 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-10 09:31:36.438  4020  4036 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 09:31:36.439  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-10 09:31:36.439  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-10 09:31:36.439  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-10 09:31:36.439  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-10 09:31:36.439  4020  4039 D BtGatt.ScanManager: handling starting scan
,08-10 09:31:36.443  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-10 09:31:36.444  3663  3663 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-10 09:31:36.444  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-10 09:31:36.445  4020  4036 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-10 09:31:36.445  4020  4036 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 09:31:36.445  4020  4039 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-10 09:31:36.446  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-10 09:31:36.450  4020  4036 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-10 09:31:36.450  4020  4036 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-10 09:31:36.450  4020  4039 D BtGatt.ScanManager: Starting BLE batch scan
08-10 09:31:36.450  4020  4039 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-10 09:31:36.452  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-10 09:31:36.452  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-10 09:31:36.452  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 09:31:36.452  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-10 09:31:36.452  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-10 09:31:36.452  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-10 09:31:36.452  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 09:31:36.452  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a0d44d0 removed from the list
08-10 09:31:36.452  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:36.453  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7ddcc9 removed from the list
,08-10 09:31:36.453  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:36.453  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 09:31:36.453  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:36.453  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-10 09:31:36.453  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:36.453  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 09:31:36.454  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:36.454  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:36.454  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:36.454  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b7ddcc9 not in the list
08-10 09:31:36.454  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-10 09:31:36.454  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-10 09:31:36.454  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-10 09:31:36.454  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-10 09:31:36.454  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-10 09:31:36.455  3663  3713 D BluetoothAdapter: STATE_ON
08-10 09:31:36.455  4020  4060 D BtGatt.GattService: stopScan() - queue size =1
,08-10 09:31:36.456  4020  4031 D BtGatt.GattService: unregisterClient() - clientIf=5
08-10 09:31:36.456  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-10 09:31:36.456  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-10 09:31:36.456  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-10 09:31:36.456  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-10 09:31:36.456  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-10 09:31:36.457  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 09:31:36.457  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-10 09:31:36.457  3663  3713 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-10 09:31:36.458  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-10 09:31:36.458  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:36.459  3663  3663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 09:31:36.459  3663  3663 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-10 09:31:36.459  3663  3663 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-10 09:31:36.459  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:36.459  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:36.459  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:36.459  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@349ddfc removed from the list
08-10 09:31:36.459  4020  4036 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-10 09:31:36.459  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:36.460  4020  4036 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:36.460  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:36.460  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:36.460  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 09:31:36.460  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a7e8eef removed from the list
08-10 09:31:36.460  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 09:31:36.460  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f54dde8 added. We now have 2 listener(s)
08-10 09:31:36.462  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 09:31:36.462  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 09:31:36.462  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 09:31:36.462  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 09:31:36.462  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f5c01 added. We now have 9 listener(s)
08-10 09:31:36.462  366,3  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 09:31:36.463  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 09:31:36.464  4020  4036 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-10 09:31:36.464  4020  4036 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:36.465  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 09:31:36.468  3663  3713 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 09:31:36.468  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 09:31:36.468  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-10 09:31:36.468  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 09:31:36.468  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 09:31:36.468  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 09:31:36.468  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 09:31:36.468  3663  3713 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 09:31:36.470  3663  3713 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 09:31:36.470  4020  4036 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-10 09:31:36.470  4020  4036 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:36.470  4020  4039 D BtGatt.ScanManager: stopping BLe Batch
08-10 09:31:36.470  3663  3713 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 09:31:36.471  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-10 09:31:36.471  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b436ce7 added. We now have 3 listener(s)
08-10 09:31:36.472  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 09:31:36.473  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-10 09:31:36.473  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 09:31:36.473  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 09:31:36.474  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-10 09:31:36.474  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88df094 added. We now have 10 listener(s)
08-10 09:31:36.474  3663  3713 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 09:31:36.474  3663  3713 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-10 09:31:36.474  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:36.474  3663  3663 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 09:31:36.474  3663  3713 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-10 09:31:36.474  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:36.474  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:36.474  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-10 09:31:36.474  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 09:31:36.474  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f54dde8 removed from the list
08-10 09:31:36.474  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:36.474  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f5c01 removed from the list
08-10 09:31:36.475  3663  3713 D io.jxcore.node.ConnectivityMonitor: stop
08-10 09:31:36.475  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:36.475  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:36.475  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:36.476  4020  4036 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-10 09:31:36.476  4020  4036 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:36.476  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:36.476  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:36.476  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:36.476  4020  4039 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-10 09:31:36.476  3663  3713 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2f5c01 not in the list
08-10 09:31:36.476  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:36.479  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:36.479  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-10 09:31:36.479  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-10 09:31:36.479  3663  3713 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-10 09:31:36.480  3663  3713 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88df094 removed from the list
08-10 09:31:36.480  3663  3713 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-10 09:31:36.480  3663  3713 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-10 09:31:36.480  3663  3713 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-10 09:31:36.480  3663  3713 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-10 09:31:36.480  3663  3713 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b436ce7 removed from the list
08-10 09:31:36.481  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-10 09:31:36.481  4020  4036 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-10 09:31:36.481  4020  4036 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-10 09:31:36.481  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-10 09:31:36.481  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-10 09:31:36.481  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 09:31:36.481  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-10 09:31:36.481  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:36.486  3663  4107 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: My test thread name)
08-10 09:31:36.486  3663  4107 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 437, thread name: My test thread name)
08-10 09:31:36.486  3663  4107 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 437, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-10 09:31:36.488  3663  4108 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: My test thread name)
08-10 09:31:36.488  3663  4108 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: My test thread name)
08-10 09:31:36.488  3663  4108 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-10 09:31:36.489  3663  3713 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-10 09:31:36.490  3663  3713 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-10 09:31:36.490  3663  3713 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-10 09:31:36.490  3663  3713 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-10 09:31:36.490  3663  3713 D com.test.thalitest.ThaliTestRunner: Total duration: 22789 ms
08-10 09:31:36.491  3663  3713 I jxcore-log: Total number of executed tests:  80
08-10 09:31:36.491  3663  3713 I jxcore-log: 
08-10 09:31:36.491  3663  3713 I jxcore-log: Number of passed tests:  80
08-10 09:31:36.491  3663  3713 I jxcore-log: 
08-10 09:31:36.492  3663  3713 I jxcore-log: Number of failed tests:  0
08-10 09:31:36.492  3663  3713 I jxcore-log: 
08-10 09:31:36.492  3663  3713 I jxcore-log: Number of ignored tests:  0
08-10 09:31:36.492  3663  3713 I jxcore-log: 
08-10 09:31:36.492  3663  3713 I jxcore-log: Total duration:  22789
08-10 09:31:36.492  3663  3713 I jxcore-log: 
08-10 09:31:36.494  3663  3713 I jxcore-log: Unit Test app is loaded
08-10 09:31:36.494  3663  3713 I jxcore-log: 
08-10 09:31:36.494  3616  4106 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
08-10 09:31:36.501  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 09:31:36.501  3663  3713 I jxcore-log: 
08-10 09:31:36.504  3663  3663 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-10 09:31:36.506  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 09:31:36.506  3663  3713 I jxcore-log: 
08-10 09:31:36.507  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 09:31:36.507  3663  3713 I jxcore-log: 
08-10 09:31:36.508  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 09:31:36.508  3663  3713 I jxcore-log: 
08-10 09:31:36.509  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 09:31:36.509  3663  3713 I jxcore-log: 
08-10 09:31:36.510  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 09:31:36.510  3663  3713 I jxcore-log: 
08-10 09:31:36.513  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 09:31:36.513  3663  3713 I jxcore-log: 
08-10 09:31:36.514  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 09:31:36.514  3663  3713 I jxcore-log: 
,08-10 09:31:36.520  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 09:31:36.520  3663  3713 I jxcore-log: 
08-10 09:31:36.521  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 09:31:36.521  3663  3713 I jxcore-log: 
08-10 09:31:36.523  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 09:31:36.523  3663  3713 I jxcore-log: 
08-10 09:31:36.524  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-10 09:31:36.524  3663  3713 I jxcore-log: 
08-10 09:31:36.525  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 09:31:36.525  3663  3713 I jxcore-log: 
08-10 09:31:36.526  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-10 09:31:36.526  3663  3713 I jxcore-log: 
08-10 09:31:36.527  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 09:31:36.527  3663  3713 I jxcore-log: 
08-10 09:31:36.528  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 09:31:36.528  3663  3713 I jxcore-log: 
08-10 09:31:36.529  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 09:31:36.529  3663  3713 I jxcore-log: 
08-10 09:31:36.530  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 09:31:36.530  3663  3713 I jxcore-log: 
08-10 09:31:36.531  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 09:31:36.531  3663  3713 I jxcore-log: 
08-10 09:31:36.532  1520  1941 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-10 09:31:36.532  1520  1941 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 09:31:36.532  1520  1941 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:31:36.532  1520  1941 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-10 09:31:36.532  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 09:31:36.532  3663  3713 I jxcore-log: 
08-10 09:31:36.533  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 09:31:36.533  3663  3713 I jxcore-log: 
08-10 09:31:36.534  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-10 09:31:36.534  3663  3713 I jxcore-log: 
08-10 09:31:36.535  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 09:31:36.535  3663  3713 I jxcore-log: 
08-10 09:31:36.536  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-10 09:31:36.536  3663  3713 I jxcore-log: 
08-10 09:31:36.537  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-10 09:31:36.537  3663  3713 I jxcore-log: 
08-10 09:31:36.538  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-10 09:31:36.538  3663  3713 I jxcore-log: 
08-10 09:31:36.538  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 09:31:36.538  3663  3713 I jxcore-log: 
08-10 09:31:36.539  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 09:31:36.539  3663  3713 I jxcore-log: 
08-10 09:31:36.540  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 09:31:36.540  3663  3713 I jxcore-log: 
08-10 09:31:36.541  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 09:31:36.541  3663  3713 I jxcore-log: 
08-10 09:31:36.542  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 09:31:36.542  3663  3713 I jxcore-log: 
08-10 09:31:36.543  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 09:31:36.543  3663  3713 I jxcore-log: 
08-10 09:31:36.546  3663  3713 I jxcore-log: My device name is: motorola-Nexus 6
08-10 09:31:36.546  3663  3713 I jxcore-log: 
08-10 09:31:36.556  1520  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-10 09:31:36.556  1520  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 09:31:36.556  1520  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 09:31:36.556  1520  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:31:36.583  3616  4106 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 09:31:36.584  3616  4092 E BooksSync: Soft error
08-10 09:31:36.584  3616  4092 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 09:31:36.584  3616  4092 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 09:31:36.584  3616  4092 E BooksSync: Sync error
08-10 09:31:36.584  3616  4092 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 09:31:36.584  3616  4092 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 09:31:36.584  3616  4092 I BooksSync: Finished books sync
,08-10 09:31:36.596   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 158904, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 09:31:36.614  1887  1887 D SystemUpdateService: onDestroy
,08-10 09:31:36.628  1520  2112 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-10 09:31:36.629  1520  2112 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-10 09:31:36.629  1520  2112 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:31:36.630  1520  2112 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:31:36.667  1887  4091 E MDM     : [217] SitrepService.a: Error sending sitrep.
,08-10 09:31:36.672  1520  4100 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-10 09:31:36.679  1520  4100 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-10 09:31:36.701  1520  4100 W Uploader:  no longer exists, so no auth token.
,08-10 09:31:36.728  3010  4093 V KeepSync: Connecting to GoogleApiClient
08-10 09:31:36.729   875  2065 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 09:31:36.771  1520  1941 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-10 09:31:36.771  1520  1941 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-10 09:31:36.771  1520  1941 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 09:31:36.771  1520  1941 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:31:36.783  1887  4112 V BaseAuthAsyncOperation: access token request failed
,08-10 09:31:36.784  3010  4093 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 09:31:36.827  1520  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-10 09:31:36.827  1520  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-10 09:31:36.827  1520  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:31:36.827  1520  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:31:36.838  3663  3663 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 09:31:36.845  3010  4093 E KeepSync: IOException
08-10 09:31:36.845  3010  4093 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 09:31:36.845  3010  4093 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 09:31:36.845  3010  4093 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 09:31:36.845  3010  4093 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 09:31:36.845  3010  4093 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 09:31:36.845  3010  4093 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 09:31:36.845  3010  4093 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 09:31:36.845  3010  4093 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 09:31:36.845  3010  4093 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 09:31:36.845  3010  4093 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 09:31:36.845  3010  4093 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 09:31:36.845  3010  4093 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 09:31:36.845  3010  4093 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 09:31:36.845  3010  4093 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 09:31:36.845  3010  4093 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 09:31:36.845  3010  4093 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 09:31:36.845  3010  4093 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 09:31:36.845  3010  4093 E KeepSync: 	... 10 more
08-10 09:31:36.845  3010  4093 W KeepSync: Sync result 2
,08-10 09:31:36.866   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 160103, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 09:31:36.903  3663  3663 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 09:31:36.960  3663  3663 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-10 09:31:37.055   875  1310 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-10 09:31:37.064  1520  4100 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-10 09:31:37.064  1520  4100 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-10 09:31:37.064  1520  4100 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:31:37.064  1520  4100 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:31:37.082  1520  4100 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 09:31:37.082  1520  4100 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 09:31:37.082  1520  4100 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 09:31:37.082  1520  4100 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 09:31:37.082  1520  4100 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-10 09:31:37.082  1520  4100 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-10 09:31:37.082  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-10 09:31:37.082  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-10 09:31:37.082  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-10 09:31:37.082  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-10 09:31:37.082  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-10 09:31:37.082  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-10 09:31:37.082  1520  4100 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-10 09:31:38.057   875  1308 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 15 -> obsolete
,08-10 09:31:38.061  1520  4100 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-10 09:31:38.061  1520  4100 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-10 09:31:38.061  1520  4100 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:31:38.061  1520  4100 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:31:38.076  1520  4100 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 09:31:38.076  1520  4100 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 09:31:38.076  1520  4100 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 09:31:38.076  1520  4100 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 09:31:38.076  1520  4100 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-10 09:31:38.076  1520  4100 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-10 09:31:38.076  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-10 09:31:38.076  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-10 09:31:38.076  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-10 09:31:38.076  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-10 09:31:38.076  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-10 09:31:38.076  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-10 09:31:38.076  1520  4100 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-10 09:31:38.204  1520  4100 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-10 09:31:38.204  1520  4100 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-10 09:31:38.204  1520  4100 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 09:31:38.204  1520  4100 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:31:38.221  1520  4100 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 09:31:38.221  1520  4100 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 09:31:38.221  1520  4100 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 09:31:38.221  1520  4100 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 09:31:38.221  1520  4100 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-10 09:31:38.221  1520  4100 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-10 09:31:38.221  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-10 09:31:38.221  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-10 09:31:38.221  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-10 09:31:38.221  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-10 09:31:38.221  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-10 09:31:38.221  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-10 09:31:38.221  1520  4100 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-10 09:31:38.357  1520  4100 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-10 09:31:38.357  1520  4100 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-10 09:31:38.357  1520  4100 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-10 09:31:38.357  1520  4100 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:31:38.376  1520  4100 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 09:31:38.376  1520  4100 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-10 09:31:38.376  1520  4100 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 09:31:38.376  1520  4100 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 09:31:38.376  1520  4100 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-10 09:31:38.376  1520  4100 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-10 09:31:38.376  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-10 09:31:38.376  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-10 09:31:38.376  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-10 09:31:38.376  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-10 09:31:38.376  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-10 09:31:38.376  1520  4100 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-10 09:31:38.376  1520  4100 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-10 09:31:39.050  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-10 09:31:39.050  3663  3713 I jxcore-log: 
,08-10 09:31:39.680  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-10 09:31:39.680  3663  3713 I jxcore-log: 
,08-10 09:31:39.705  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-10 09:31:39.705  3663  3713 I jxcore-log: 
,08-10 09:31:41.078  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-10 09:31:41.078  3663  3713 I jxcore-log: 
,08-10 09:31:41.349  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-10 09:31:41.349  3663  3713 I jxcore-log: 
,08-10 09:31:41.354  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-10 09:31:41.354  3663  3713 I jxcore-log: 
,08-10 09:31:41.371  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-10 09:31:41.371  3663  3713 I jxcore-log: 
,08-10 09:31:41.376  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-10 09:31:41.376  3663  3713 I jxcore-log: 
,08-10 09:31:42.058  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-10 09:31:42.058  3663  3713 I jxcore-log: 
,08-10 09:31:42.071  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-10 09:31:42.071  3663  3713 I jxcore-log: 
,08-10 09:31:42.080  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-10 09:31:42.080  3663  3713 I jxcore-log: 
,08-10 09:31:42.088  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-10 09:31:42.088  3663  3713 I jxcore-log: 
,08-10 09:31:42.137  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-10 09:31:42.137  3663  3713 I jxcore-log: 
,08-10 09:31:42.193  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-10 09:31:42.193  3663  3713 I jxcore-log: 
,08-10 09:31:42.201  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-10 09:31:42.201  3663  3713 I jxcore-log: 
,08-10 09:31:42.367  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-10 09:31:42.367  3663  3713 I jxcore-log: 
,08-10 09:31:42.394  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-10 09:31:42.394  3663  3713 I jxcore-log: 
,08-10 09:31:42.400  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-10 09:31:42.400  3663  3713 I jxcore-log: 
,08-10 09:31:42.406  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-10 09:31:42.406  3663  3713 I jxcore-log: 
,08-10 09:31:42.425  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-10 09:31:42.425  3663  3713 I jxcore-log: 
,08-10 09:31:42.510  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-10 09:31:42.510  3663  3713 I jxcore-log: 
,08-10 09:31:42.522  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-10 09:31:42.522  3663  3713 I jxcore-log: 
,08-10 09:31:42.550  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-10 09:31:42.550  3663  3713 I jxcore-log: 
,08-10 09:31:42.562  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-10 09:31:42.562  3663  3713 I jxcore-log: 
,08-10 09:31:42.581  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-10 09:31:42.581  3663  3713 I jxcore-log: 
,08-10 09:31:42.618  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-10 09:31:42.618  3663  3713 I jxcore-log: 
,08-10 09:31:42.624  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-10 09:31:42.624  3663  3713 I jxcore-log: 
,08-10 09:31:42.843  3663  3713 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-10 09:31:42.843  3663  3713 I jxcore-log: 
,08-10 09:31:42.853  3663  3713 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,08-10 09:31:42.855  3663  3713 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
08-10 09:31:42.855  3663  3713 I jxcore-log: 
,08-10 09:31:42.904  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-10 09:31:42.904  3663  3713 I jxcore-log: 
,08-10 09:31:42.904  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-10 09:31:42.904  3663  3713 I jxcore-log: 
,08-10 09:31:42.905  3663  3713 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-10 09:31:42.905  3663  3713 I jxcore-log: 
,08-10 09:31:42.905  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-10 09:31:42.905  3663  3713 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
08-10 09:31:42.905  3663  3713 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-10 09:31:42.905  3663  3713 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,08-10 09:31:43.947   875  1310 D ConnectivityService: handlePromptUnvalidated 102
,08-10 09:31:53.039  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:31:53.049  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:31:53.052  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:31:53.110  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-10 09:31:53.110  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.,
08-10 09:31:53.110  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:31:53.111  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:31:53.162  3385  3385 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-10 09:31:53.163  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-10 09:31:53.164  3385  3385 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-10 09:31:59.267   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=187877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:32:08.750   875  1622 I ActivityManager: Start proc 4121:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-10 09:32:08.839  4121  4121 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-10 09:32:08.880   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=197490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 09:32:08.924  4121  4133 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-10 09:32:09.031  4121  4133 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-10 09:32:09.083  4121  4133 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-10 09:32:09.154  4121  4121 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-10 09:32:09.357  4121  4121 W InstanceID/Rpc: Found 10011
,08-10 09:32:09.446  4150  4150 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-132691627.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-132691627.dex
,08-10 09:32:09.520  3010  4190 V KeepSync: Connecting to GoogleApiClient
,08-10 09:32:09.521   875  2068 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 09:32:09.553  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:32:09.554  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:32:09.574  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-10 09:32:09.574  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-10 09:32:09.574  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 09:32:09.574  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:32:09.586  1887  4201 V BaseAuthAsyncOperation: access token request failed
,08-10 09:32:09.587  3010  4190 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 09:32:09.660  4150  4150 I dex2oat : dex2oat took 240.777ms (threads: 4) arena alloc=297KB java alloc=29KB native alloc=1386KB free=1685KB
,08-10 09:32:09.700  1520  1941 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-10 09:32:09.701  1520  1941 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 09:32:09.701  1520  1941 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:32:09.701  1520  1941 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:32:09.717  3010  4190 E KeepSync: IOException
08-10 09:32:09.717  3010  4190 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 09:32:09.717  3010  4190 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 09:32:09.717  3010  4190 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 09:32:09.717  3010  4190 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 09:32:09.717  3010  4190 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 09:32:09.717  3010  4190 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 09:32:09.717  3010  4190 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 09:32:09.717  3010  4190 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 09:32:09.717  3010  4190 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 09:32:09.717  3010  4190 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 09:32:09.717  3010  4190 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 09:32:09.717  3010  4190 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 09:32:09.717  3010  4190 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 09:32:09.717  3010  4190 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 09:32:09.717  3010  4190 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 09:32:09.717  3010  4190 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 09:32:09.717  3010  4190 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 09:32:09.717  3010  4190 E KeepSync: 	... 10 more
08-10 09:32:09.718  3010  4190 W KeepSync: Sync result 2
,08-10 09:32:09.735   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 197968, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 09:32:09.806  3616  4204 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 09:32:09.830  3616  4205 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 09:32:09.879  1520  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 09:32:09.879  1520  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-10 09:32:09.879  1520  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 09:32:09.879  1520  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:32:09.931  1520  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 09:32:09.931  1520  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 09:32:09.931  1520  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:32:09.931  1520  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:32:09.952  3616  4205 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 09:32:09.953  3616  4204 E BooksSync: Soft error
08-10 09:32:09.953  3616  4204 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 09:32:09.953  3616  4204 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 09:32:09.953  3616  4204 E BooksSync: Sync error
08-10 09:32:09.953  3616  4204 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 09:32:09.953  3616  4204 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 09:32:09.954  3616  4204 I BooksSync: Finished books sync
,08-10 09:32:09.966   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 197998, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 09:32:10.139   875  1622 I ActivityManager: Killing 3486:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-10 09:32:21.614  1641  1767 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-10 09:32:21.615  1641  1767 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-10 09:32:21.666  1520  1520 I ConfigService: onCreate
,08-10 09:32:26.749  1520  1520 I ConfigService: onDestroy
,08-10 09:32:42.877  1887  4210 I EventLogService: Opted in for usage reporting
,08-10 09:32:42.880  1887  4210 I EventLogService: Aggregate from 1470812562716 (log), 1470812562716 (data)
,08-10 09:32:42.953  1887  4210 W EventLogAggregator: Unknown tag: snet_gcore
,08-10 09:32:42.953  1887  4210 W EventLogAggregator: Unknown tag: snet_launch_service
,08-10 09:32:43.007  1887  4210 I ServiceDumpSys: dumping service [account]
,08-10 09:32:44.774   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=233384, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:32:54.373   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=242983, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 09:33:04.473  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:33:04.474  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:33:04.538  1520  1941 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-10 09:33:04.538  1520  1941 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 09:33:04.539  1520  1941 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:33:04.539  1520  1941 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:33:04.555  3426  4215 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 09:33:04.555  3426  4215 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 09:33:04.555  3426  4215 E HttpOperation: 	at jdm.a(PG:82)
08-10 09:33:04.555  3426  4215 E HttpOperation: 	,at jcs.o(PG:406)
08-10 09:33:04.555  3426  4215 E HttpOperation: 	at jcn.a(PG:1379)
08-10 09:33:04.555  3426  4215 E HttpOperation: 	at jcs.i(PG:143)
08-10 09:33:04.555  3426  4215 E HttpOperation: 	at blb.a(PG:3937)
08-10 09:33:04.555  3426  4215 E HttpOperation: 	at czp.a(PG:18188)
08-10 09:33:04.555  3426  4215 E HttpOperation: 	at czp.a(PG:9081)
08-10 09:33:04.555  3426  4215 E HttpOperation: 	at czq.run(PG:1686)
08-10 09:33:04.555  3426  4215 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:33:04.555  3426  4215 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:33:04.555  3426  4215 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:33:04.555  3426  4215 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:33:04.555  3426  4215 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:33:04.555  3426  4215 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:33:04.555  3426  4215 E HttpOperation: 	at jdj.a(PG:4091)
08-10 09:33:04.555  3426  4215 E HttpOperation: 	at jdj.a(PG:1125)
08-10 09:33:04.555  3426  4215 E HttpOperation: 	at jdm.a(PG:77)
08-10 09:33:04.555  3426  4215 E HttpOperation: 	... 12 more
08-10 09:33:04.555  3426  4215 E HttpOperation: Caused by: faj: BadAuthentication
08-10 09:33:04.555  3426  4215 E HttpOperation: 	at fal.a(PG:38)
08-10 09:33:04.555  3426  4215 E HttpOperation: 	at jdj.a(PG:4089)
08-10 09:33:04.555  3426  4215 E HttpOperation: 	... 14 more
,08-10 09:33:04.595  1520  1941 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 09:33:04.596  1520  1941 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 09:33:04.596  1520  1941 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 09:33:04.596  1520  1941 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:33:04.609  3426  4215 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 09:33:04.609  3426  4215 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 09:33:04.609  3426  4215 E HttpOperation: 	at jdm.a(PG:82)
08-10 09:33:04.609  3426  4215 E HttpOperation: 	at jcs.o(PG:406)
08-10 09:33:04.609  3426  4215 E HttpOperation: 	at jcn.a(PG:1379)
08-10 09:33:04.609  3426  4215 E HttpOperation: 	at jcs.i(PG:143)
08-10 09:33:04.609  3426  4215 E HttpOperation: 	at hec.a(PG:42)
08-10 09:33:04.609  3426  4215 E HttpOperation: 	at hee.a(PG:102)
08-10 09:33:04.609  3426  4215 E HttpOperation: 	at czr.a(PG:65)
08-10 09:33:04.609  3426  4215 E HttpOperation: 	at kka.a(PG:108)
08-10 09:33:04.609  3426  4215 E HttpOperation: 	at czp.a(PG:19176)
08-10 09:33:04.609  3426  4215 E HttpOperation: 	at czp.a(PG:9081)
08-10 09:33:04.609  3426  4215 E HttpOperation: 	at czq.run(PG:1686)
08-10 09:33:04.609  3426  4215 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:33:04.609  3426  4215 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:33:04.609  3426  4215 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:33:04.609  3426  4215 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:33:04.609  3426  4215 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:33:04.609  3426  4215 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:33:04.609  3426  4215 E HttpOperation: 	at jdj.a(PG:4091)
08-10 09:33:04.609  3426  4215 E HttpOperation: 	at jdj.a(PG:1125)
08-10 09:33:04.609  3426  4215 E HttpOperation: 	at jdm.a(PG:77)
08-10 09:33:04.609  3426  4215 E HttpOperation: 	... 15 more
08-10 09:33:04.609  3426  4215 E HttpOperation: Caused by: faj: BadAuthentication
08-10 09:33:04.609  3426  4215 E HttpOperation: 	at fal.a(PG:38)
08-10 09:33:04.609  3426  4215 E HttpOperation: 	at jdj.a(PG:4089)
08-10 09:33:04.609  3426  4215 E HttpOperation: 	... 17 more
,08-10 09:33:04.609  3426  4215 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 09:33:04.609  3426  4215 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	at hec.a(PG:42)
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	at hee.a(PG:102)
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	at czr.a(PG:65)
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	at kka.a(PG:108)
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:33:04.609  3426  4215 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	... 15 more
08-10 09:33:04.609  3426  4215 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	at fal.a(PG:38)
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 09:33:04.609  3426  4215 E ExperimentLoader: 	... 17 more
,08-10 09:33:04.791   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 252890, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 09:33:13.013  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:33:13.015  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:33:13.042  3882  4217 V GoogleAuthProtoRequest: [346] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 09:33:13.063  1520  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-10 09:33:13.063  1520  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-10 09:33:13.063  1520  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:33:13.063  1520  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:33:13.076  3882  4217 W ExperimentUpdateService: [346] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-10 09:33:13.076  3882  4217 W ExperimentUpdateService: [346] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 09:33:13.076  3882  4217 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 09:33:13.076  3882  4217 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-10 09:33:13.076  3882  4217 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-10 09:33:13.076  3882  4217 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-10 09:33:13.076  3882  4217 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-10 09:33:13.076  3882  4217 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-10 09:33:13.076  3882  4217 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-10 09:33:13.076  3882  4217 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-10 09:33:13.076  3882  4217 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-10 09:33:13.076  3882  4217 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-10 09:33:15.067   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=263677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:33:24.680   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=273290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 09:33:35.086  3616  4220 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 09:33:35.126  3616  4221 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 09:33:35.140  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:33:35.142  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:33:35.169  1520  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 09:33:35.170  1520  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 09:33:35.170  1520  1533 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-10 09:33:35.170  1520  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:33:35.184  3010  4219 V KeepSync: Connecting to GoogleApiClient
,08-10 09:33:35.184   875  1796 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 09:33:35.192  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:33:35.199  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:33:35.242  1520  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 09:33:35.242  1520  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-10 09:33:35.243  1520  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:33:35.243  1520  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:33:35.270  3616  4221 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 09:33:35.271  3616  4220 E BooksSync: Soft error
08-10 09:33:35.271  3616  4220 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 09:33:35.271  3616  4220 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 09:33:35.271  3616  4220 E BooksSync: Sync error
08-10 09:33:35.271  3616  4220 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 09:33:35.271  3616  4220 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 09:33:35.271  3616  4220 I BooksSync: Finished books sync
,08-10 09:33:35.276  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:33:35.278   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 264159, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 09:33:35.280  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:33:35.301  1520  1941 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-10 09:33:35.301  1520  1941 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-10 09:33:35.301  1520  1941 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:33:35.301  1520  1941 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:33:35.314  1887  4222 V BaseAuthAsyncOperation: access token request failed
,08-10 09:33:35.315  3010  4219 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 09:33:35.374  1520  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-10 09:33:35.374  1520  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-10 09:33:35.374  1520  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:33:35.374  1520  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:33:35.398  3010  4219 E KeepSync: IOException
08-10 09:33:35.398  3010  4219 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 09:33:35.398  3010  4219 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 09:33:35.398  3010  4219 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 09:33:35.398  3010  4219 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 09:33:35.398  3010  4219 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 09:33:35.398  3010  4219 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 09:33:35.398  3010  4219 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 09:33:35.398  3010  4219 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 09:33:35.398  3010  4219 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 09:33:35.398  3010  4219 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 09:33:35.398  3010  4219 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 09:33:35.398  3010  4219 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 09:33:35.398  3010  4219 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 09:33:35.398  3010  4219 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 09:33:35.398  3010  4219 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 09:33:35.398  3010  4219 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 09:33:35.398  3010  4219 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 09:33:35.398  3010  4219 E KeepSync: 	... 10 more
08-10 09:33:35.398  3010  4219 W KeepSync: Sync result 2
,08-10 09:33:35.405   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 263327, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 09:33:43.243  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:33:43.245  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:33:43.260  3882  4231 V GoogleAuthProtoRequest: [347] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 09:33:43.304  1520  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-10 09:33:43.304  1520  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-10 09:33:43.304  1520  1533 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-10 09:33:43.304  1520  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:33:43.328  3882  4231 W ExperimentUpdateService: [347] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-10 09:33:43.329  3882  4231 W ExperimentUpdateService: [347] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 09:33:43.329  3882  4231 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 09:33:43.329  3882  4231 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-10 09:33:43.329  3882  4231 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-10 09:33:43.329  3882  4231 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-10 09:33:43.329  3882  4231 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-10 09:33:43.329  3882  4231 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-10 09:33:43.329  3882  4231 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-10 09:33:43.329  3882  4231 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-10 09:33:43.329  3882  4231 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-10 09:33:43.329  3882  4231 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-10 09:33:45.360   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=293970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:33:54.987   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=303597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-10 09:34:05.686  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:34:05.687  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:34:05.718  1520  2112 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 09:34:05.719  1520  2112 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-10 09:34:05.719  1520  2112 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 09:34:05.719  1520  2112 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:34:05.734  3426  4242 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 09:34:05.734  3426  4242 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 09:34:05.734  3426  4242 E HttpOperation: 	at jdm.a(PG:82)
08-10 09:34:05.734  3426  4242 E HttpOperation: 	at jcs.o(PG:406)
08-10 09:34:05.734  3426  4242 E HttpOperation: 	at jcn.a(PG:1379)
08-10 09:34:05.734  3426  4242 E HttpOperation: 	at jcs.i(PG:143)
08-10 09:34:05.734  3426  4242 E HttpOperation: 	at blb.a(PG:3937)
08-10 09:34:05.734  3426  4242 E HttpOperation: 	at czp.a(PG:18188)
08-10 09:34:05.734  3426  4242 E HttpOperation: 	at czp.a(PG:9087)
08-10 09:34:05.734  3426  4242 E HttpOperation: 	at czq.run(PG:1686)
08-10 09:34:05.734  3426  4242 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:34:05.734  3426  4242 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:34:05.734  3426  4242 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:34:05.734  3426  4242 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:34:05.734  3426  4242 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:34:05.734  3426  4242 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:34:05.734  3426  4242 E HttpOperation: 	at jdj.a(PG:4091)
08-10 09:34:05.734  3426  4242 E HttpOperation: 	at jdj.a(PG:1125)
08-10 09:34:05.734  3426  4242 E HttpOperation: 	at jdm.a(PG:77)
08-10 09:34:05.734  3426  4242 E HttpOperation: 	... 12 more
08-10 09:34:05.734  3426  4242 E HttpOperation: Caused by: faj: BadAuthentication
08-10 09:34:05.734  3426  4242 E HttpOperation: 	at fal.a(PG:38)
08-10 09:34:05.734  3426  4242 E HttpOperation: 	at jdj.a(PG:4089)
08-10 09:34:05.734  3426  4242 E HttpOperation: 	... 14 more
,08-10 09:34:05.980  1520  2112 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 09:34:05.980  1520  2112 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-10 09:34:05.980  1520  2112 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 09:34:05.980  1520  2112 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:34:05.996  3426  4245 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 09:34:05.996  3426  4245 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 09:34:05.996  3426  4245 E HttpOperation: 	at jdm.a(PG:82)
08-10 09:34:05.996  3426  4245 E HttpOperation: 	at jcs.o(PG:406)
08-10 09:34:05.996  3426  4245 E HttpOperation: 	at jcn.a(PG:1379)
08-10 09:34:05.996  3426  4245 E HttpOperation: 	at jcs.i(PG:143)
08-10 09:34:05.996  3426  4245 E HttpOperation: 	at blb.a(PG:3937)
08-10 09:34:05.996  3426  4245 E HttpOperation: 	at czp.a(PG:18188)
08-10 09:34:05.996  3426  4245 E HttpOperation: 	at czp.a(PG:9081)
08-10 09:34:05.996  3426  4245 E HttpOperation: 	at czq.run(PG:1686)
08-10 09:34:05.996  3426  4245 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:34:05.996  3426  4245 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:34:05.996  3426  4245 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:34:05.996  3426  4245 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:34:05.996  3426  4245 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:34:05.996  3426  4245 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:34:05.996  3426  4245 E HttpOperation: 	at jdj.a(PG:4091)
08-10 09:34:05.996  3426  4245 E HttpOperation: 	at jdj.a(PG:1125)
08-10 09:34:05.996  3426  4245 E HttpOperation: 	at jdm.a(PG:77)
08-10 09:34:05.996  3426  4245 E HttpOperation: 	... 12 more
08-10 09:34:05.996  3426  4245 E HttpOperation: Caused by: faj: BadAuthentication
08-10 09:34:05.996  3426  4245 E HttpOperation: 	at fal.a(PG:38)
08-10 09:34:05.996  3426  4245 E HttpOperation: 	at jdj.a(PG:4089)
08-10 09:34:05.996  3426  4245 E HttpOperation: 	... 14 more
,08-10 09:34:06.036  1520  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-10 09:34:06.036  1520  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-10 09:34:06.036  1520  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:34:06.036  1520  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:34:06.069  3426  4245 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 09:34:06.069  3426  4245 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 09:34:06.069  3426  4245 E HttpOperation: 	at jdm.a(PG:82)
08-10 09:34:06.069  3426  4245 E HttpOperation: 	at jcs.o(PG:406)
08-10 09:34:06.069  3426  4245 E HttpOperation: 	at jcn.a(PG:1379)
08-10 09:34:06.069  3426  4245 E HttpOperation: 	at jcs.i(PG:143)
08-10 09:34:06.069  3426  4245 E HttpOperation: 	at hec.a(PG:42)
08-10 09:34:06.069  3426  4245 E HttpOperation: 	at hee.a(PG:102)
08-10 09:34:06.069  3426  4245 E HttpOperation: 	at czr.a(PG:65)
08-10 09:34:06.069  3426  4245 E HttpOperation: 	at kka.a(PG:108)
08-10 09:34:06.069  3426  4245 E HttpOperation: 	at czp.a(PG:19176)
08-10 09:34:06.069  3426  4245 E HttpOperation: 	at czp.a(PG:9081)
08-10 09:34:06.069  3426  4245 E HttpOperation: 	at czq.run(PG:1686)
08-10 09:34:06.069  3426  4245 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:34:06.069  3426  4245 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:34:06.069  3426  4245 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:34:06.069  3426  4245 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:34:06.069  3426  4245 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:34:06.069  3426  4245 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:34:06.069  3426  4245 E HttpOperation: 	at jdj.a(PG:4091)
08-10 09:34:06.069  3426  4245 E HttpOperation: 	at jdj.a(PG:1125)
08-10 09:34:06.069  3426  4245 E HttpOperation: 	at jdm.a(PG:77)
08-10 09:34:06.069  3426  4245 E HttpOperation: 	... 15 more
08-10 09:34:06.069  3426  4245 E HttpOperation: Caused by: faj: BadAuthentication
08-10 09:34:06.069  3426  4245 E HttpOperation: 	at fal.a(PG:38)
08-10 09:34:06.069  3426  4245 E HttpOperation: 	at jdj.a(PG:4089)
08-10 09:34:06.069  3426  4245 E HttpOperation: 	... 17 more
08-10 09:34:06.070  3426  4245 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 09:34:06.070  3426  4245 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	at hec.a(PG:42)
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	at hee.a(PG:102)
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	at czr.a(PG:65)
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	at kka.a(PG:108)
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:34:06.070  3426  4245 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	... 15 more
08-10 09:34:06.070  3426  4245 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	at fal.a(PG:38)
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 09:34:06.070  3426  4245 E ExperimentLoader: 	... 17 more
,08-10 09:34:06.237   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 253403, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 09:34:17.107   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=325717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:34:22.387   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=330997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:34:33.534  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:34:33.542  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:34:33.547  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:34:33.585  1520  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,08-10 09:34:33.585  1520  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-10 09:34:33.586  1520  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:34:33.586  1520  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:34:33.614  1520  2046 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.,
08-10 09:34:33.614  1520  2046 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-10 09:34:33.614  1520  2046 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-10 09:34:33.614  1520  2046 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-10 09:34:33.614  1520  2046 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-10 09:34:33.614  1520  2046 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-10 09:34:33.614  1520  2046 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453),
,08-10 09:34:33.618  3385  3415 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-10 09:34:33.618  3385  3415 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-10 09:34:33.618  3385  3415 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
,08-10 09:34:33.618  3385  3415 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-10 09:34:33.618  3385  3415 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-10 09:34:33.618  3385  3415 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-10 09:34:33.618  3385  3415 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-10 09:34:38.464  1520  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-10 09:34:38.465  1520  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 09:34:38.465  1520  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:34:38.465  1520  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:34:38.480  3426  4251 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 09:34:38.480  3426  4251 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 09:34:38.480  3426  4251 E HttpOperation: 	at jdm.a(PG:82)
08-10 09:34:38.480  3426  4251 E HttpOperation: 	at jcs.o(PG:406)
08-10 09:34:38.480  3426  4251 E HttpOperation: 	at jcn.a(PG:1379)
08-10 09:34:38.480  3426  4251 E HttpOperation: 	at jcs.i(PG:143)
08-10 09:34:38.480  3426  4251 E HttpOperation: 	at blb.a(PG:3937)
08-10 09:34:38.480  3426  4251 E HttpOperation: 	at czp.a(PG:18188)
08-10 09:34:38.480  3426  4251 E HttpOperation: 	at czp.a(PG:9081)
08-10 09:34:38.480  3426  4251 E HttpOperation: 	at czq.run(PG:1686)
08-10 09:34:38.480  3426  4251 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:34:38.480  3426  4251 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:34:38.480  3426  4251 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:34:38.480  3426  4251 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:34:38.480  3426  4251 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:34:38.480  3426  4251 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:34:38.480  3426  4251 E HttpOperation: 	at jdj.a(PG:4091)
08-10 09:34:38.480  3426  4251 E HttpOperation: 	at jdj.a(PG:1125)
08-10 09:34:38.480  3426  4251 E HttpOperation: 	at jdm.a(PG:77)
08-10 09:34:38.480  3426  4251 E HttpOperation: 	... 12 more
08-10 09:34:38.480  3426  4251 E HttpOperation: Caused by: faj: BadAuthentication
08-10 09:34:38.480  3426  4251 E HttpOperation: 	at fal.a(PG:38)
08-10 09:34:38.480  3426  4251 E HttpOperation: 	at jdj.a(PG:4089)
08-10 09:34:38.480  3426  4251 E HttpOperation: 	... 14 more
,08-10 09:34:38.527  1520  2112 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 09:34:38.527  1520  2112 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 09:34:38.527  1520  2112 I GLSUser : [GLSUser] Extracting token using key: Auth,
08-10 09:34:38.527  1520  2112 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:34:38.542  3426  4251 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 09:34:38.542  3426  4251 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 09:34:38.542  3426  4251 E HttpOperation: 	at jdm.a(PG:82)
08-10 09:34:38.542  3426  4251 E HttpOperation: 	at jcs.o(PG:406)
08-10 09:34:38.542  3426  4251 E HttpOperation: 	at jcn.a(PG:1379)
08-10 09:34:38.542  3426  4251 E HttpOperation: 	at jcs.i(PG:143)
08-10 09:34:38.542  3426  4251 E HttpOperation: 	at hec.a(PG:42)
08-10 09:34:38.542  3426  4251 E HttpOperation: 	at hee.a(PG:102)
08-10 09:34:38.542  3426  4251 E HttpOperation: 	at czr.a(PG:65)
08-10 09:34:38.542  3426  4251 E HttpOperation: 	at kka.a(PG:108)
08-10 09:34:38.542  3426  4251 E HttpOperation: 	at czp.a(PG:19176)
08-10 09:34:38.542  3426  4251 E HttpOperation: 	at czp.a(PG:9081)
08-10 09:34:38.542  3426  4251 E HttpOperation: 	at czq.run(PG:1686)
08-10 09:34:38.542  3426  4251 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:34:38.542  3426  4251 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:34:38.542  3426  4251 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:34:38.542  3426  4251 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:34:38.542  3426  4251 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:34:38.542  3426  4251 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:34:38.542  3426  4251 E HttpOperation: 	at jdj.a(PG:4091)
08-10 09:34:38.542  3426  4251 E HttpOperation: 	at jdj.a(PG:1125)
08-10 09:34:38.542  3426  4251 E HttpOperation: 	at jdm.a(PG:77)
08-10 09:34:38.542  3426  4251 E HttpOperation: 	... 15 more
08-10 09:34:38.542  3426  4251 E HttpOperation: Caused by: faj: BadAuthentication
08-10 09:34:38.542  3426  4251 E HttpOperation: 	at fal.a(PG:38)
08-10 09:34:38.542  3426  4251 E HttpOperation: 	at jdj.a(PG:4089)
08-10 09:34:38.542  3426  4251 E HttpOperation: 	... 17 more
,08-10 09:34:38.542  3426  4251 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token,
08-10 09:34:38.542  3426  4251 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	at hec.a(PG:42)
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	at hee.a(PG:102)
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	at czr.a(PG:65)
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	at kka.a(PG:108)
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:34:38.542  3426  4251 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	... 15 more
08-10 09:34:38.542  3426  4251 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	at fal.a(PG:38)
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 09:34:38.542  3426  4251 E ExperimentLoader: 	... 17 more
,08-10 09:34:38.687   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 346827, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 09:34:43.407  3882  4253 V GoogleAuthProtoRequest: [348] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 09:34:43.425  1520  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-10 09:34:43.425  1520  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-10 09:34:43.425  1520  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:34:43.426  1520  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:34:43.440  3882  4253 W ExperimentUpdateService: [348] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
08-10 09:34:43.440  3882  4253 W ExperimentUpdateService: [348] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 09:34:43.440  3882  4253 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 09:34:43.440  3882  4253 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-10 09:34:43.440  3882  4253 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-10 09:34:43.440  3882  4253 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-10 09:34:43.440  3882  4253 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-10 09:34:43.440  3882  4253 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-10 09:34:43.440  3882  4253 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-10 09:34:43.440  3882  4253 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-10 09:34:43.440  3882  4253 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-10 09:34:43.440  3882  4253 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-10 09:35:06.747   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=375357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:35:16.147   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=384757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:35:31.867   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=400477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:35:41.240   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=409850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:35:42.911  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:35:42.915  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:35:42.951  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 09:35:42.952  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-10 09:35:42.952  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:35:42.952  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:35:42.967  3426  4258 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 09:35:42.967  3426  4258 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 09:35:42.967  3426  4258 E HttpOperation: 	at jdm.a(PG:82)
08-10 09:35:42.967  3426  4258 E HttpOperation: 	at jcs.o(PG:406)
08-10 09:35:42.967  3426  4258 E HttpOperation: 	at jcn.a(PG:1379)
08-10 09:35:42.967  3426  4258 E HttpOperation: 	at jcs.i(PG:143)
08-10 09:35:42.967  3426  4258 E HttpOperation: 	at blb.a(PG:3937)
08-10 09:35:42.967  3426  4258 E HttpOperation: 	at czp.a(PG:18188)
08-10 09:35:42.967  3426  4258 E HttpOperation: 	at czp.a(PG:9081)
08-10 09:35:42.967  3426  4258 E HttpOperation: 	at czq.run(PG:1686)
08-10 09:35:42.967  3426  4258 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:35:42.967  3426  4258 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:35:42.967  3426  4258 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:35:42.967  3426  4258 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:35:42.967  3426  4258 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:35:42.967  3426  4258 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:35:42.967  3426  4258 E HttpOperation: 	at jdj.a(PG:4091)
08-10 09:35:42.967  3426  4258 E HttpOperation: 	at jdj.a(PG:1125)
08-10 09:35:42.967  3426  4258 E HttpOperation: 	at jdm.a(PG:77)
08-10 09:35:42.967  3426  4258 E HttpOperation: 	... 12 more
08-10 09:35:42.967  3426  4258 E HttpOperation: Caused by: faj: BadAuthentication
08-10 09:35:42.967  3426  4258 E HttpOperation: 	at fal.a(PG:38)
08-10 09:35:42.967  3426  4258 E HttpOperation: 	at jdj.a(PG:4089)
08-10 09:35:42.967  3426  4258 E HttpOperation: 	... 14 more
,08-10 09:35:43.051  1520  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-10 09:35:43.051  1520  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 09:35:43.051  1520  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:35:43.051  1520  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:35:43.077  3426  4258 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 09:35:43.077  3426  4258 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 09:35:43.077  3426  4258 E HttpOperation: 	at jdm.a(PG:82)
08-10 09:35:43.077  3426  4258 E HttpOperation: 	at jcs.o(PG:406)
08-10 09:35:43.077  3426  4258 E HttpOperation: 	at jcn.a(PG:1379)
08-10 09:35:43.077  3426  4258 E HttpOperation: 	at jcs.i(PG:143)
08-10 09:35:43.077  3426  4258 E HttpOperation: 	at hec.a(PG:42)
08-10 09:35:43.077  3426  4258 E HttpOperation: 	at hee.a(PG:102)
08-10 09:35:43.077  3426  4258 E HttpOperation: 	at czr.a(PG:65)
08-10 09:35:43.077  3426  4258 E HttpOperation: 	at kka.a(PG:108)
08-10 09:35:43.077  3426  4258 E HttpOperation: 	at czp.a(PG:19176)
08-10 09:35:43.077  3426  4258 E HttpOperation: 	at czp.a(PG:9081)
08-10 09:35:43.077  3426  4258 E HttpOperation: 	at czq.run(PG:1686)
08-10 09:35:43.077  3426  4258 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:35:43.077  3426  4258 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:35:43.077  3426  4258 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:35:43.077  3426  4258 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:35:43.077  3426  4258 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:35:43.077  3426  4258 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:35:43.077  3426  4258 E HttpOperation: 	at jdj.a(PG:4091)
08-10 09:35:43.077  3426  4258 E HttpOperation: 	at jdj.a(PG:1125)
08-10 09:35:43.077  3426  4258 E HttpOperation: 	at jdm.a(PG:77)
08-10 09:35:43.077  3426  4258 E HttpOperation: 	... 15 more
08-10 09:35:43.077  3426  4258 E HttpOperation: Caused by: faj: BadAuthentication
08-10 09:35:43.077  3426  4258 E HttpOperation: 	at fal.a(PG:38)
08-10 09:35:43.077  3426  4258 E HttpOperation: 	at jdj.a(PG:4089)
08-10 09:35:43.077  3426  4258 E HttpOperation: 	... 17 more
08-10 09:35:43.077  3426  4258 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 09:35:43.077  3426  4258 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	at hec.a(PG:42)
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	at hee.a(PG:102)
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	at czr.a(PG:65)
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	at kka.a(PG:108)
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:35:43.077  3426  4258 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	... 15 more
08-10 09:35:43.077  3426  4258 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	at fal.a(PG:38)
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 09:35:43.077  3426  4258 E ExperimentLoader: 	... 17 more
,08-10 09:35:43.167   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 411256, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 09:35:56.933   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=425543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:36:06.293   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=434903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:36:13.368  3616  4263 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 09:36:13.416  3616  4264 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 09:36:13.437  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:36:13.439  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:36:13.456  3010  4262 V KeepSync: Connecting to GoogleApiClient,
08-10 09:36:13.457   875   885 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 09:36:13.508  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-10 09:36:13.508  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 09:36:13.508  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 09:36:13.508  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:36:13.563  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:36:13.569  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:36:13.643  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-10 09:36:13.643  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-10 09:36:13.643  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:36:13.644  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:36:13.646  1520  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 09:36:13.646  1520  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 09:36:13.646  1520  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:36:13.646  1520  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:36:13.690  3616  4264 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 09:36:13.691  3616  4263 E BooksSync: Soft error
08-10 09:36:13.691  3616  4263 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 09:36:13.691  3616  4263 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 09:36:13.691  3616  4263 E BooksSync: Sync error
08-10 09:36:13.691  3616  4263 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 09:36:13.691  3616  4263 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-10 09:36:13.691  3616  4263 I BooksSync: Finished books sync
,08-10 09:36:13.693  1887  4265 V BaseAuthAsyncOperation: access token request failed
08-10 09:36:13.695  3010  4262 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 09:36:13.715   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 415052, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 09:36:13.764  1520  2112 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-10 09:36:13.764  1520  2112 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 09:36:13.764  1520  2112 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:36:13.764  1520  2112 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:36:13.785  3010  4262 E KeepSync: IOException
08-10 09:36:13.785  3010  4262 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 09:36:13.785  3010  4262 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 09:36:13.785  3010  4262 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 09:36:13.785  3010  4262 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 09:36:13.785  3010  4262 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 09:36:13.785  3010  4262 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 09:36:13.785  3010  4262 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 09:36:13.785  3010  4262 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 09:36:13.785  3010  4262 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 09:36:13.785  3010  4262 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
,08-10 09:36:13.785  3010  4262 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 09:36:13.785  3010  4262 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 09:36:13.785  3010  4262 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 09:36:13.785  3010  4262 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 09:36:13.785  3010  4262 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 09:36:13.785  3010  4262 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 09:36:13.785  3010  4262 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 09:36:13.785  3010  4262 E KeepSync: 	... 10 more
08-10 09:36:13.785  3010  4262 W KeepSync: Sync result 2
,08-10 09:36:13.804   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 413980, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 09:36:22.000   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=450610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:36:31.373   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=459984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:36:43.639  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:36:43.640  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:36:43.651  3882  4267 V GoogleAuthProtoRequest: [349] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 09:36:43.675  1520  2112 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-10 09:36:43.675  1520  2112 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-10 09:36:43.675  1520  2112 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:36:43.675  1520  2112 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:36:43.688  3882  4267 W ExperimentUpdateService: [349] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-10 09:36:43.688  3882  4267 W ExperimentUpdateService: [349] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 09:36:43.688  3882  4267 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 09:36:43.688  3882  4267 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-10 09:36:43.688  3882  4267 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-10 09:36:43.688  3882  4267 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-10 09:36:43.688  3882  4267 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
,08-10 09:36:43.688  3882  4267 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-10 09:36:43.688  3882  4267 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-10 09:36:43.688  3882  4267 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-10 09:36:43.688  3882  4267 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-10 09:36:43.688  3882  4267 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-10 09:36:47.067   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=475677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:36:56.427   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=485037, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:37:12.453   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=501063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:37:19.866   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=508477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:37:37.520   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=526130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:37:46.934   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=535544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:37:51.394  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:37:51.398  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:37:51.436  1520  2112 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-10 09:37:51.436  1520  2112 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 09:37:51.436  1520  2112 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:37:51.436  1520  2112 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:37:51.464  3426  4272 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 09:37:51.464  3426  4272 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 09:37:51.464  3426  4272 E HttpOperation: 	at jdm.a(PG:82)
08-10 09:37:51.464  3426  4272 E HttpOperation: 	at jcs.o(PG:406)
08-10 09:37:51.464  3426  4272 E HttpOperation: 	at jcn.a(PG:1379)
08-10 09:37:51.464  3426  4272 E HttpOperation: 	at jcs.i(PG:143)
08-10 09:37:51.464  3426  4272 E HttpOperation: 	at blb.a(PG:3937)
08-10 09:37:51.464  3426  4272 E HttpOperation: 	at czp.a(PG:18188)
08-10 09:37:51.464  3426  4272 E HttpOperation: 	at czp.a(PG:9081)
08-10 09:37:51.464  3426  4272 E HttpOperation: 	at czq.run(PG:1686)
08-10 09:37:51.464  3426  4272 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:37:51.464  3426  4272 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:37:51.464  3426  4272 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:37:51.464  3426  4272 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:37:51.464  3426  4272 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:37:51.464  3426  4272 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:37:51.464  3426  4272 E HttpOperation: 	at jdj.a(PG:4091)
08-10 09:37:51.464  3426  4272 E HttpOperation: 	at jdj.a(PG:1125)
08-10 09:37:51.464  3426  4272 E HttpOperation: 	at jdm.a(PG:77)
08-10 09:37:51.464  3426  4272 E HttpOperation: 	... 12 more
08-10 09:37:51.464  3426  4272 E HttpOperation: Caused by: faj: BadAuthentication
08-10 09:37:51.464  3426  4272 E HttpOperation: 	at fal.a(PG:38)
08-10 09:37:51.464  3426  4272 E HttpOperation: 	at jdj.a(PG:4089)
08-10 09:37:51.464  3426  4272 E HttpOperation: 	... 14 more
,08-10 09:37:51.546  1520  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-10 09:37:51.546  1520  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 09:37:51.547  1520  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:37:51.547  1520  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:37:51.581  3426  4272 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 09:37:51.581  3426  4272 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 09:37:51.581  3426  4272 E HttpOperation: 	at jdm.a(PG:82)
08-10 09:37:51.581  3426  4272 E HttpOperation: 	at jcs.o(PG:406)
08-10 09:37:51.581  3426  4272 E HttpOperation: 	at jcn.a(PG:1379)
08-10 09:37:51.581  3426  4272 E HttpOperation: 	at jcs.i(PG:143)
08-10 09:37:51.581  3426  4272 E HttpOperation: 	at hec.a(PG:42)
08-10 09:37:51.581  3426  4272 E HttpOperation: 	at hee.a(PG:102)
08-10 09:37:51.581  3426  4272 E HttpOperation: 	at czr.a(PG:65)
08-10 09:37:51.581  3426  4272 E HttpOperation: 	at kka.a(PG:108)
08-10 09:37:51.581  3426  4272 E HttpOperation: 	at czp.a(PG:19176)
08-10 09:37:51.581  3426  4272 E HttpOperation: 	at czp.a(PG:9081)
08-10 09:37:51.581  3426  4272 E HttpOperation: 	at czq.run(PG:1686)
08-10 09:37:51.581  3426  4272 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:37:51.581  3426  4272 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:37:51.581  3426  4272 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:37:51.581  3426  4272 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:37:51.581  3426  4272 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:37:51.581  3426  4272 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:37:51.581  3426  4272 E HttpOperation: 	at jdj.a(PG:4091)
08-10 09:37:51.581  3426  4272 E HttpOperation: 	at jdj.a(PG:1125)
08-10 09:37:51.581  3426  4272 E HttpOperation: 	at jdm.a(PG:77)
08-10 09:37:51.581  3426  4272 E HttpOperation: 	... 15 more
08-10 09:37:51.581  3426  4272 E HttpOperation: Caused by: faj: BadAuthentication
08-10 09:37:51.581  3426  4272 E HttpOperation: 	at fal.a(PG:38)
08-10 09:37:51.581  3426  4272 E HttpOperation: 	at jdj.a(PG:4089)
08-10 09:37:51.581  3426  4272 E HttpOperation: 	... 17 more
08-10 09:37:51.581  3426  4272 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 09:37:51.581  3426  4272 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	at hec.a(PG:42)
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	at hee.a(PG:102)
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	at czr.a(PG:65)
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	at kka.a(PG:108)
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:37:51.581  3426  4272 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	... 15 more
08-10 09:37:51.581  3426  4272 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	at fal.a(PG:38)
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 09:37:51.581  3426  4272 E ExperimentLoader: 	... 17 more
,08-10 09:37:51.699   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 539694, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 09:38:02.640   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=551251, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:38:11.987   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=560597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:38:27.654   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=576264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:38:37.040   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=585650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:38:52.720   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=601330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:39:02.107   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=610717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:39:17.787   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=626397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:39:27.174   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=635784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:39:42.854   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=651464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:39:52.240   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=660850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:40:07.920   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=676530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:40:17.294   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=685904, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:40:32.987   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=701597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:40:33.981  3010  4287 V KeepSync: Connecting to GoogleApiClient
,08-10 09:40:33.981   875  2065 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 09:40:34.041  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:40:34.043  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:40:34.073  1520  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-10 09:40:34.074  1520  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-10 09:40:34.074  1520  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 09:40:34.074  1520  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:40:34.104  1887  4288 V BaseAuthAsyncOperation: access token request failed
08-10 09:40:34.105  3010  4287 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 09:40:34.174  1520  1941 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-10 09:40:34.174  1520  1941 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 09:40:34.174  1520  1941 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 09:40:34.174  1520  1941 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:40:34.213  3010  4287 E KeepSync: IOException
08-10 09:40:34.213  3010  4287 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 09:40:34.213  3010  4287 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 09:40:34.213  3010  4287 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 09:40:34.213  3010  4287 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 09:40:34.213  3010  4287 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 09:40:34.213  3010  4287 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 09:40:34.213  3010  4287 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 09:40:34.213  3010  4287 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 09:40:34.213  3010  4287 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 09:40:34.213  3010  4287 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 09:40:34.213  3010  4287 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 09:40:34.213  3010  4287 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 09:40:34.213  3010  4287 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 09:40:34.213  3010  4287 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 09:40:34.213  3010  4287 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 09:40:34.213  3010  4287 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 09:40:34.213  3010  4287 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 09:40:34.213  3010  4287 E KeepSync: 	... 10 more
,08-10 09:40:34.213  3010  4287 W KeepSync: Sync result 2
,08-10 09:40:34.233   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 702342, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 09:40:42.347   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=710957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:40:43.804  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:40:43.806  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:40:43.824  3882  4289 V GoogleAuthProtoRequest: [350] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 09:40:43.882  1520  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-10 09:40:43.882  1520  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-10 09:40:43.882  1520  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 09:40:43.883  1520  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:40:43.922  3882  4289 W ExperimentUpdateService: [350] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-10 09:40:43.923  3882  4289 W ExperimentUpdateService: [350] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 09:40:43.923  3882  4289 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 09:40:43.923  3882  4289 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-10 09:40:43.923  3882  4289 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-10 09:40:43.923  3882  4289 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-10 09:40:43.923  3882  4289 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-10 09:40:43.923  3882  4289 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-10 09:40:43.923  3882  4289 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-10 09:40:43.923  3882  4289 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-10 09:40:43.923  3882  4289 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-10 09:40:43.923  3882  4289 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-10 09:40:58.054   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=726664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:41:04.366  3616  4292 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 09:41:04.397  3616  4293 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 09:41:04.410  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:41:04.412  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:41:04.459  1520  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-10 09:41:04.460  1520  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 09:41:04.460  1520  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 09:41:04.460  1520  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:41:04.516  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:41:04.519  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:41:04.547  1520  2046 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 09:41:04.547  1520  2046 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-10 09:41:04.547  1520  2046 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:41:04.547  1520  2046 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:41:04.567  3616  4293 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 09:41:04.568  3616  4292 E BooksSync: Soft error
08-10 09:41:04.568  3616  4292 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 09:41:04.568  3616  4292 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 09:41:04.568  3616  4292 E BooksSync: Sync error
08-10 09:41:04.568  3616  4292 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 09:41:04.568  3616  4292 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 09:41:04.568  3616  4292 I BooksSync: Finished books sync
,08-10 09:41:04.580   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 704654, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 09:41:07.400   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=736010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:41:23.121   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=751731, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:41:32.453   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=761063, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:41:48.187   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=776797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:41:57.520   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=786130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:42:07.836  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:42:07.837  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:42:07.871  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-10 09:42:07.871  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 09:42:07.871  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:42:07.871  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:42:07.886  3426  4299 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 09:42:07.886  3426  4299 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 09:42:07.886  3426  4299 E HttpOperation: 	at jdm.a(PG:82)
08-10 09:42:07.886  3426  4299 E HttpOperation: 	at jcs.o(PG:406)
08-10 09:42:07.886  3426  4299 E HttpOperation: 	at jcn.a(PG:1379)
08-10 09:42:07.886  3426  4299 E HttpOperation: 	at jcs.i(PG:143)
08-10 09:42:07.886  3426  4299 E HttpOperation: 	at blb.a(PG:3937)
08-10 09:42:07.886  3426  4299 E HttpOperation: 	at czp.a(PG:18188)
08-10 09:42:07.886  3426  4299 E HttpOperation: 	at czp.a(PG:9081)
08-10 09:42:07.886  3426  4299 E HttpOperation: 	at czq.run(PG:1686)
08-10 09:42:07.886  3426  4299 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:42:07.886  3426  4299 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:42:07.886  3426  4299 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:42:07.886  3426  4299 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:42:07.886  3426  4299 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:42:07.886  3426  4299 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:42:07.886  3426  4299 E HttpOperation: 	at jdj.a(PG:4091)
08-10 09:42:07.886  3426  4299 E HttpOperation: 	at jdj.a(PG:1125)
08-10 09:42:07.886  3426  4299 E HttpOperation: 	at jdm.a(PG:77)
08-10 09:42:07.886  3426  4299 E HttpOperation: 	... 12 more
08-10 09:42:07.886  3426  4299 E HttpOperation: Caused by: faj: BadAuthentication
08-10 09:42:07.886  3426  4299 E HttpOperation: 	at fal.a(PG:38)
08-10 09:42:07.886  3426  4299 E HttpOperation: 	at jdj.a(PG:4089)
08-10 09:42:07.886  3426  4299 E HttpOperation: 	... 14 more
,08-10 09:42:07.953  1520  1941 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 09:42:07.954  1520  1941 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 09:42:07.954  1520  1941 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:42:07.954  1520  1941 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:42:07.995  3426  4299 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 09:42:07.995  3426  4299 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 09:42:07.995  3426  4299 E HttpOperation: 	at jdm.a(PG:82)
08-10 09:42:07.995  3426  4299 E HttpOperation: 	at jcs.o(PG:406)
08-10 09:42:07.995  3426  4299 E HttpOperation: 	at jcn.a(PG:1379)
08-10 09:42:07.995  3426  4299 E HttpOperation: 	at jcs.i(PG:143)
08-10 09:42:07.995  3426  4299 E HttpOperation: 	at hec.a(PG:42)
08-10 09:42:07.995  3426  4299 E HttpOperation: 	at hee.a(PG:102)
08-10 09:42:07.995  3426  4299 E HttpOperation: 	at czr.a(PG:65)
08-10 09:42:07.995  3426  4299 E HttpOperation: 	at kka.a(PG:108)
08-10 09:42:07.995  3426  4299 E HttpOperation: 	at czp.a(PG:19176)
08-10 09:42:07.995  3426  4299 E HttpOperation: 	at czp.a(PG:9081)
08-10 09:42:07.995  3426  4299 E HttpOperation: 	at czq.run(PG:1686)
08-10 09:42:07.995  3426  4299 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
,08-10 09:42:07.995  3426  4299 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:42:07.995  3426  4299 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:42:07.995  3426  4299 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:42:07.995  3426  4299 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:42:07.995  3426  4299 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:42:07.995  3426  4299 E HttpOperation: 	at jdj.a(PG:4091)
08-10 09:42:07.995  3426  4299 E HttpOperation: 	at jdj.a(PG:1125)
08-10 09:42:07.995  3426  4299 E HttpOperation: 	at jdm.a(PG:77)
08-10 09:42:07.995  3426  4299 E HttpOperation: 	... 15 more
08-10 09:42:07.995  3426  4299 E HttpOperation: Caused by: faj: BadAuthentication
08-10 09:42:07.995  3426  4299 E HttpOperation: 	at fal.a(PG:38)
08-10 09:42:07.995  3426  4299 E HttpOperation: 	at jdj.a(PG:4089)
08-10 09:42:07.995  3426  4299 E HttpOperation: 	... 17 more
08-10 09:42:07.995  3426  4299 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 09:42:07.995  3426  4299 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	at hec.a(PG:42)
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	at hee.a(PG:102)
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	at czr.a(PG:65)
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	at kka.a(PG:108)
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:42:07.995  3426  4299 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	... 15 more
08-10 09:42:07.995  3426  4299 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	at fal.a(PG:38)
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 09:42:07.995  3426  4299 E ExperimentLoader: 	... 17 more
,08-10 09:42:08.119   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 796142, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 09:42:13.200   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=801810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:42:22.587   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=811197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:42:38.266   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=826877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:42:47.640   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=836250, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:43:03.334   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=851944, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:43:04.535  1520  2022 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-10 09:43:12.693   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=861303, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:43:28.400   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=877011, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:43:37.760   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=886371, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:43:51.974   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=900584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:44:02.814   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=911424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:44:17.040   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=925650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:44:27.867   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=936477, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:44:42.107   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=950717, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:44:52.934   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=961544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:45:07.173   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=975783, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:45:17.987   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=986597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:45:32.187   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1000797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:45:43.040   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1011650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:45:57.253   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1025864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:46:08.094   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1036704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:46:22.320   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1050930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:46:33.146   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1061757, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:46:47.387   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1075997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:46:58.213   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1086823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:47:12.453   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1101064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:47:23.267   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1111877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:47:37.894   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1126504, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:47:48.507   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1137117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:48:02.960   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1151570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:48:13.787   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1162397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:48:28.027   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1176637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:48:38.854   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1187464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:48:44.128  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:48:44.129  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:48:44.139  3882  4319 V GoogleAuthProtoRequest: [351] a.<init>: mAccountName set to: thalitester@gmail.com
,08-10 09:48:44.167  1520  1533 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-10 09:48:44.167  1520  1533 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-10 09:48:44.167  1520  1533 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:48:44.167  1520  1533 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:48:44.189  3882  4319 W ExperimentUpdateService: [351] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-10 09:48:44.189  3882  4319 W ExperimentUpdateService: [351] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 09:48:44.189  3882  4319 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-10 09:48:44.189  3882  4319 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-10 09:48:44.189  3882  4319 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-10 09:48:44.189  3882  4319 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-10 09:48:44.189  3882  4319 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-10 09:48:44.189  3882  4319 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-10 09:48:44.189  3882  4319 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-10 09:48:44.189  3882  4319 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-10 09:48:44.189  3882  4319 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-10 09:48:44.189  3882  4319 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-10 09:48:48.400   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1197010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:49:03.906   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1212516, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:49:09.717   875   887 I UsageStatsService: User[0] Flushing usage stats to disk
,08-10 09:49:13.440   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1222050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:49:14.222  3010  4321 V KeepSync: Connecting to GoogleApiClient
08-10 09:49:14.222   875  2068 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-10 09:49:14.299  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:49:14.301  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:49:14.321  1520  1941 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-10 09:49:14.321  1520  1941 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-10 09:49:14.321  1520  1941 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:49:14.321  1520  1941 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:49:14.334  1887  4322 V BaseAuthAsyncOperation: access token request failed
,08-10 09:49:14.335  3010  4321 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-10 09:49:14.392  1520  2112 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-10 09:49:14.393  1520  2112 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-10 09:49:14.393  1520  2112 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-10 09:49:14.393  1520  2112 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:49:14.406  3010  4321 E KeepSync: IOException
08-10 09:49:14.406  3010  4321 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-10 09:49:14.406  3010  4321 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-10 09:49:14.406  3010  4321 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-10 09:49:14.406  3010  4321 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-10 09:49:14.406  3010  4321 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-10 09:49:14.406  3010  4321 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-10 09:49:14.406  3010  4321 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-10 09:49:14.406  3010  4321 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-10 09:49:14.406  3010  4321 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-10 09:49:14.406  3010  4321 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-10 09:49:14.406  3010  4321 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-10 09:49:14.406  3010  4321 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-10 09:49:14.406  3010  4321 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-10 09:49:14.406  3010  4321 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-10 09:49:14.406  3010  4321 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 09:49:14.406  3010  4321 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-10 09:49:14.406  3010  4321 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-10 09:49:14.406  3010  4321 E KeepSync: 	... 10 more
,08-10 09:49:14.406  3010  4321 W KeepSync: Sync result 2
,08-10 09:49:14.413   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1222700, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 09:49:28.961   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1237570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:49:39.173   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1247783, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:49:49.315  3616  4324 I BooksSync: Starting books sync for 61035162, extras: ade
,08-10 09:49:49.348  3616  4325 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-10 09:49:49.359  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:49:49.364  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:49:49.394  1520  2112 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 09:49:49.394  1520  2112 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 09:49:49.395  1520  2112 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:49:49.395  1520  2112 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:49:49.428  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:49:49.430  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:49:49.459  1520  1532 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-10 09:49:49.459  1520  1532 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-10 09:49:49.459  1520  1532 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:49:49.459  1520  1532 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:49:49.478  3616  4325 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-10 09:49:49.480  3616  4324 E BooksSync: Soft error
08-10 09:49:49.480  3616  4324 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 09:49:49.480  3616  4324 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 09:49:49.480  3616  4324 E BooksSync: Sync error
08-10 09:49:49.480  3616  4324 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-10 09:49:49.480  3616  4324 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-10 09:49:49.480  3616  4324 I BooksSync: Finished books sync
,08-10 09:49:49.485   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1257847, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-10 09:49:54.680   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1263290, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:50:04.240   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1272850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:50:19.747   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1288357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:50:29.280   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1297890, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:50:40.109  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:50:40.112  1520  1520 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-10 09:50:40.149  1520  2112 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-10 09:50:40.149  1520  2112 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-10 09:50:40.149  1520  2112 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:50:40.149  1520  2112 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:50:40.175  3426  4330 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-10 09:50:40.175  3426  4330 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 09:50:40.175  3426  4330 E HttpOperation: 	at jdm.a(PG:82)
08-10 09:50:40.175  3426  4330 E HttpOperation: 	at jcs.o(PG:406)
08-10 09:50:40.175  3426  4330 E HttpOperation: 	at jcn.a(PG:1379)
08-10 09:50:40.175  3426  4330 E HttpOperation: 	at jcs.i(PG:143)
08-10 09:50:40.175  3426  4330 E HttpOperation: 	at blb.a(PG:3937)
08-10 09:50:40.175  3426  4330 E HttpOperation: 	at czp.a(PG:18188)
08-10 09:50:40.175  3426  4330 E HttpOperation: 	at czp.a(PG:9081)
08-10 09:50:40.175  3426  4330 E HttpOperation: 	at czq.run(PG:1686)
08-10 09:50:40.175  3426  4330 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:50:40.175  3426  4330 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:50:40.175  3426  4330 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:50:40.175  3426  4330 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:50:40.175  3426  4330 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:50:40.175  3426  4330 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:50:40.175  3426  4330 E HttpOperation: 	at jdj.a(PG:4091)
08-10 09:50:40.175  3426  4330 E HttpOperation: 	at jdj.a(PG:1125)
08-10 09:50:40.175  3426  4330 E HttpOperation: 	at jdm.a(PG:77)
08-10 09:50:40.175  3426  4330 E HttpOperation: 	... 12 more
08-10 09:50:40.175  3426  4330 E HttpOperation: Caused by: faj: BadAuthentication
08-10 09:50:40.175  3426  4330 E HttpOperation: 	at fal.a(PG:38)
08-10 09:50:40.175  3426  4330 E HttpOperation: 	at jdj.a(PG:4089)
08-10 09:50:40.175  3426  4330 E HttpOperation: 	... 14 more
,08-10 09:50:40.279  1520  1941 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-10 09:50:40.280  1520  1941 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-10 09:50:40.280  1520  1941 I GLSUser : [GLSUser] Extracting token using key: Auth
08-10 09:50:40.280  1520  1941 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-10 09:50:40.321  3426  4330 E HttpOperation: [getmobileexperiments] Unexpected exception
08-10 09:50:40.321  3426  4330 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-10 09:50:40.321  3426  4330 E HttpOperation: 	at jdm.a(PG:82)
08-10 09:50:40.321  3426  4330 E HttpOperation: 	at jcs.o(PG:406)
08-10 09:50:40.321  3426  4330 E HttpOperation: 	at jcn.a(PG:1379)
08-10 09:50:40.321  3426  4330 E HttpOperation: 	at jcs.i(PG:143)
08-10 09:50:40.321  3426  4330 E HttpOperation: 	at hec.a(PG:42)
08-10 09:50:40.321  3426  4330 E HttpOperation: 	at hee.a(PG:102)
08-10 09:50:40.321  3426  4330 E HttpOperation: 	at czr.a(PG:65)
08-10 09:50:40.321  3426  4330 E HttpOperation: 	at kka.a(PG:108)
08-10 09:50:40.321  3426  4330 E HttpOperation: 	at czp.a(PG:19176)
08-10 09:50:40.321  3426  4330 E HttpOperation: 	at czp.a(PG:9081)
08-10 09:50:40.321  3426  4330 E HttpOperation: 	at czq.run(PG:1686)
08-10 09:50:40.321  3426  4330 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:50:40.321  3426  4330 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:50:40.321  3426  4330 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:50:40.321  3426  4330 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:50:40.321  3426  4330 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:50:40.321  3426  4330 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:50:40.321  3426  4330 E HttpOperation: 	at jdj.a(PG:4091)
08-10 09:50:40.321  3426  4330 E HttpOperation: 	at jdj.a(PG:1125)
08-10 09:50:40.321  3426  4330 E HttpOperation: 	at jdm.a(PG:77)
08-10 09:50:40.321  3426  4330 E HttpOperation: 	... 15 more
08-10 09:50:40.321  3426  4330 E HttpOperation: Caused by: faj: BadAuthentication
08-10 09:50:40.321  3426  4330 E HttpOperation: 	at fal.a(PG:38)
08-10 09:50:40.321  3426  4330 E HttpOperation: 	at jdj.a(PG:4089)
08-10 09:50:40.321  3426  4330 E HttpOperation: 	... 17 more
,08-10 09:50:40.321  3426  4330 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-10 09:50:40.321  3426  4330 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	at jdm.a(PG:82)
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	at jcs.o(PG:406)
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	at jcn.a(PG:1379)
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	at jcs.i(PG:143)
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	at hec.a(PG:42)
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	at hee.a(PG:102)
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	at czr.a(PG:65)
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	at kka.a(PG:108)
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	at czp.a(PG:19176)
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	at czp.a(PG:9081)
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	at czq.run(PG:1686)
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:50:40.321  3426  4330 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	at jdj.a(PG:4091)
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	at jdj.a(PG:1125)
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	at jdm.a(PG:77)
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	... 15 more
08-10 09:50:40.321  3426  4330 E ExperimentLoader: Caused by: faj: BadAuthentication
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	at fal.a(PG:38)
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	at jdj.a(PG:4089)
08-10 09:50:40.321  3426  4330 E ExperimentLoader: 	... 17 more
,08-10 09:50:40.461   875   887 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1308394, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-10 09:50:44.814   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1313424, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:50:54.347   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1322957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:51:09.880   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1338490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:51:19.414   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1348024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:51:34.933   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1363543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:51:44.480   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1373090, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:52:00.014   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1388623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:52:09.573   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1398183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:52:25.080   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1413690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:52:34.613   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1423224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:52:50.133   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1438743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:52:59.653   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1448263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:53:15.187   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1463797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:53:24.720   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1473330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:53:40.240   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1488850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:53:42.953   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1491563, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-10 09:54:05.307   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1513917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-10 09:54:08.013   875  4077 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1516623, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,TIME-OUT KILL (timeout was 1400000ms),08-10 09:54:25.476  4340  4340 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-10 09:54:25.480  4340  4340 D AndroidRuntime: CheckJNI is OFF
08-10 09:54:25.517  4340  4340 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-10 09:54:25.559  4340  4340 I Radio-JNI: register_android_hardware_Radio DONE
08-10 09:54:25.581  4340  4340 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-10 09:54:25.593   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-10 09:54:25.594   875   888 I ActivityManager: Killing 3663:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
08-10 09:54:25.724   875   898 W PackageSettings: Skipping PackageSetting{a0fa936 com.example.hello/10273} due to missing metadata
08-10 09:54:25.736   875  1309 D WifiService: Client connection lost with reason: 4
08-10 09:54:25.736   875  1693 D GraphicsStats: Buffer count: 2
08-10 09:54:25.736   875  1622 I WindowState: WIN DEATH: Window{e29e6a2 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-10 09:54:25.768   875   888 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-10 09:54:25.769   875   888 W PackageManager: Package com.test.thalitest is missing; assuming frozen
08-10 09:54:25.771   875   888 E ActivityManager: Failure starting process com.test.thalitest
08-10 09:54:25.771   875   888 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-10 09:54:25.771   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-10 09:54:25.771   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-10 09:54:25.771   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-10 09:54:25.771   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-10 09:54:25.771   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-10 09:54:25.771   875   888 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-10 09:54:25.771   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-10 09:54:25.771   875   888 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-10 09:54:25.771   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-10 09:54:25.771   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-10 09:54:25.771   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-10 09:54:25.771   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-10 09:54:25.771   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-10 09:54:25.771   875   888 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-10 09:54:25.771   875   888 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 09:54:25.771   875   888 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-10 09:54:25.771   875   888 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 09:54:25.771   875   888 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-10 09:54:25.771   875   898 I art     : Starting a blocking GC Explicit
08-10 09:54:25.773   875   888 I ActivityManager:   Force finishing activity ActivityRecord{a010bdb u0 com.test.thalitest/.MainActivity t8}
08-10 09:54:25.791   875   886 W ActivityManager: Spurious death for ProcessRecord{ce4175a 0:com.test.thalitest/u0a0}, curProc for 3663: null
08-10 09:54:25.832   875   898 I art     : Explicit concurrent mark sweep GC freed 32928(2MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 29MB/43MB, paused 789us total 59.902ms
08-10 09:54:25.856   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-10 09:54:25.863  4340  4340 I art     : System.exit called, status: 0
08-10 09:54:25.864  4340  4340 I AndroidRuntime: VM exiting with result code 0.
08-10 09:54:25.871   875   898 I ActivityManager: Start proc 4353:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-10 09:54:25.871   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-10 09:54:25.888   875   888 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-10 09:54:25.897   875  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-10 09:54:25.897  1641  1641 I Keyboard.Facilitator: resetDictionaries() : en_US
08-10 09:54:25.900  4020  4020 D BluetoothMapAppObserver: onReceive
08-10 09:54:25.901  4020  4020 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-10 09:54:25.903  1905  2031 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-10 09:54:25.908  1641  4366 I Keyboard.Facilitator.DecoderInitializer: run()
08-10 09:54:25.910  1641  4366 I Decoder : createOrResetDecoder
08-10 09:54:25.912  3506  3506 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-10 09:54:25.940  1735  1735 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-10 09:54:25.960   875  1796 I ActivityManager: Start proc 4369:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-10 09:54:25.986   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-10 09:54:25.998  1520  1520 I ConfigService: onCreate
08-10 09:54:26.002   875  2065 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3663 uid 10000
08-10 09:54:26.003   875   886 I ActivityManager: Killing 3558:com.google.android.apps.docs/u0a46 (adj 15): empty #17
08-10 09:54:26.005  1641  1641 I Keyboard.Facilitator: onFinishInput()
08-10 09:54:26.014  1520  4382 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-10 09:54:26.014  1520  4382 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 09:54:26.014  1520  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 09:54:26.014  1520  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 09:54:26.014  1520  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 09:54:26.014  1520  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 09:54:26.014  1520  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 09:54:26.014  1520  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 09:54:26.014  1520  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 09:54:26.014  1520  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 09:54:26.014  1520  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 09:54:26.014  1520  4382 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 09:54:26.014  1520  4382 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 09:54:26.014  1520  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 09:54:26.014  1520  4382 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 09:54:26.014  1520  4382 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-10 09:54:26.014  1520  4382 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-10 09:54:26.014  1520  4382 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:54:26.014  1520  4382 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-10 09:54:26.014  1520  4382 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 09:54:26.014  1520  4382 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 09:54:26.014  1520  4382 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 09:54:26.014  1520  4382 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 09:54:26.014  1520  4382 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 09:54:26.014  1520  4382 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 09:54:26.014  1520  4382 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 09:54:26.014  1520  4382 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 09:54:26.014  1520  4382 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 09:54:26.014  1520  4382 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 09:54:26.014  1520  4382 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 09:54:26.014  1520  4382 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 09:54:26.014  1520  4382 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 09:54:26.014  1520  4382 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 09:54:26.014  1520  4382 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-10 09:54:26.014  1520  4382 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-10 09:54:26.014  1520  4382 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-10 09:54:26.018  1520  4382 W SQLiteOpenHelper: Opened config.db in read-only mode
08-10 09:54:26.023  4369  4369 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-10 09:54:26.064  4369  4384 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-10 09:54:26.064  4369  4384 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 09:54:26.082  4369  4384 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
--------- beginning of crash
08-10 09:54:26.087  4369  4384 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
08-10 09:54:26.087  4369  4384 E AndroidRuntime: Process: android.process.acore, PID: 4369
08-10 09:54:26.087  4369  4384 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-10 09:54:26.087  4369  4384 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-10 09:54:26.087  4369  4384 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-10 09:54:26.087  4369  4384 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-10 09:54:26.087  4369  4384 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-10 09:54:26.087  4369  4384 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.executeSql(SQLiteDatabase.java:1676)
08-10 09:54:26.087  4369  4384 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.execSQL(SQLiteDatabase.java:1605)
08-10 09:54:26.087  4369  4384 E AndroidRuntime: 	at com.android.providers.contacts.ContactsDatabaseHelper.onOpen(ContactsDatabaseHelper.java:1084)
08-10 09:54:26.087  4369  4384 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:266)
08-10 09:54:26.087  4369  4384 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-10 09:54:26.087  4369  4384 E AndroidRuntime: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-10 09:54:26.087  4369  4384 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-10 09:54:26.087  4369  4384 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-10 09:54:26.087  4369  4384 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-10 09:54:26.087  4369  4384 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 09:54:26.087  4369  4384 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 09:54:26.087  4369  4384 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 09:54:26.097   875  4386 E DropBoxManagerService: Can't write: system_app_crash
08-10 09:54:26.097   875  4386 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-10 09:54:26.097   875  4386 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 09:54:26.097   875  4386 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 09:54:26.097   875  4386 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 09:54:26.097   875  4386 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 09:54:26.097   875  4386 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 09:54:26.097   875  4386 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 09:54:26.097   875  4386 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 09:54:26.097   875  4386 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 09:54:26.097   875  4386 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 09:54:26.097   875  4386 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 09:54:26.097   875  4386 E DropBoxManagerService: 	... 5 more
08-10 09:54:26.097  1744  1824 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-10 09:54:26.098   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-10 09:54:26.098   875   887 E PackageManager: Failed to write settings, restoring backup
08-10 09:54:26.098   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-10 09:54:26.098   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-10 09:54:26.098   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-10 09:54:26.098   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-10 09:54:26.098   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-10 09:54:26.098   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 09:54:26.098   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-10 09:54:26.098   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 09:54:26.099  4369  4369 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-10 09:54:26.105  1641  4366 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-10 09:54:26.129   875   888 I ActivityManager: Start proc 4387:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-10 09:54:26.131   875   888 E DropBoxManagerService: Can't write: system_server_wtf
08-10 09:54:26.131   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-10 09:54:26.131   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 09:54:26.131   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 09:54:26.131   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 09:54:26.131   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 09:54:26.131   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 09:54:26.131   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 09:54:26.131   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-10 09:54:26.131   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-10 09:54:26.131   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-10 09:54:26.131   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 09:54:26.131   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 09:54:26.131   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-10 09:54:26.131   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 09:54:26.131   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-10 09:54:26.131   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 09:54:26.131   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 09:54:26.131   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 09:54:26.131   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 09:54:26.131   875   888 E DropBoxManagerService: 	... 13 more
08-10 09:54:26.151   875  1693 I ActivityManager: Start proc 4399:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-10 09:54:26.152  1744  1824 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-10 09:54:26.152  1744  1824 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1744
08-10 09:54:26.152  1744  1824 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-10 09:54:26.152  1744  1824 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-10 09:54:26.152  1744  1824 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-10 09:54:26.152  1744  1824 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-10 09:54:26.152  1744  1824 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-10 09:54:26.152  1744  1824 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-10 09:54:26.152  1744  1824 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-10 09:54:26.152  1744  1824 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-10 09:54:26.152  1744  1824 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 09:54:26.152  1744  1824 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 09:54:26.152  1744  1824 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 09:54:26.152  1744  1824 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-10 09:54:26.152   875  1622 I ActivityManager: Killing 1797:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
08-10 09:54:26.160  1641  4366 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-10 09:54:26.162  1641  4366 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-10 09:54:26.162  1641  4366 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-10 09:54:26.170  1641  4366 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-10 09:54:26.170  1641  4366 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-10 09:54:26.170  1641  4366 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-10 09:54:26.170  1641  4366 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-10 09:54:26.171  1641  4366 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-10 09:54:26.171  1641  4366 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-10 09:54:26.171  1641  4366 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-10 09:54:26.171  1641  4366 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-10 09:54:26.171  1641  4366 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-10 09:54:26.171  1641  4366 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-10 09:54:26.180   875  1309 D WifiService: Client connection lost with reason: 4
08-10 09:54:26.226   875  1796 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-10 09:54:26.229  4369  4384 I Process : Sending signal. PID: 4369 SIG: 9
08-10 09:54:26.237   875  4412 E DropBoxManagerService: Can't write: system_app_crash
08-10 09:54:26.237   875  4412 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-10 09:54:26.237   875  4412 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 09:54:26.237   875  4412 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 09:54:26.237   875  4412 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 09:54:26.237   875  4412 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 09:54:26.237   875  4412 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 09:54:26.237   875  4412 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 09:54:26.237   875  4412 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 09:54:26.237   875  4412 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 09:54:26.237   875  4412 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 09:54:26.237   875  4412 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 09:54:26.237   875  4412 E DropBoxManagerService: 	... 5 more
08-10 09:54:26.243  1744  1824 I Process : Sending signal. PID: 1744 SIG: 9
08-10 09:54:26.256  4387  4387 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-10 09:54:26.281  1520  1520 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-10 09:54:26.284  1520  1520 D AndroidRuntime: Shutting down VM
08-10 09:54:26.284  1520  1520 E AndroidRuntime: FATAL EXCEPTION: main
08-10 09:54:26.284  1520  1520 E AndroidRuntime: Process: com.google.process.gapps, PID: 1520
08-10 09:54:26.284  1520  1520 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-10 09:54:26.284  1520  1520 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-10 09:54:26.284  1520  1520 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-10 09:54:26.284  1520  1520 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-10 09:54:26.284  1520  1520 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 09:54:26.284  1520  1520 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-10 09:54:26.284  1520  1520 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-10 09:54:26.284  1520  1520 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 09:54:26.284  1520  1520 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-10 09:54:26.284  1520  1520 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-10 09:54:26.284  1520  1520 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-10 09:54:26.284  1520  1520 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-10 09:54:26.284  1520  1520 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-10 09:54:26.284  1520  1520 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-10 09:54:26.284  1520  1520 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-10 09:54:26.284  1520  1520 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-10 09:54:26.284  1520  1520 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-10 09:54:26.284  1520  1520 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-10 09:54:26.284  1520  1520 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-10 09:54:26.284  1520  1520 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-10 09:54:26.284  1520  1520 E AndroidRuntime: 	... 8 more
08-10 09:54:26.289  1520  1520 I Process : Sending signal. PID: 1520 SIG: 9
08-10 09:54:26.293   875  4416 E DropBoxManagerService: Can't write: system_app_crash
08-10 09:54:26.293   875  4416 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-10 09:54:26.293   875  4416 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-10 09:54:26.293   875  4416 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 09:54:26.293   875  4416 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 09:54:26.293   875  4416 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 09:54:26.293   875  4416 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-10 09:54:26.293   875  4416 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-10 09:54:26.293   875  4416 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 09:54:26.293   875  4416 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 09:54:26.293   875  4416 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 09:54:26.293   875  4416 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-10 09:54:26.293   875  4416 E DropBoxManagerService: 	... 5 more
08-10 09:54:26.354   875  1309 D WifiService: Client connection lost with reason: 4
08-10 09:54:26.361   875  1374 I WindowState: WIN DEATH: Window{5c3adcf u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-10 09:54:26.361   875   886 D GraphicsStats: Buffer count: 1
08-10 09:54:26.381   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
