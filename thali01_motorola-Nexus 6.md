#### Test 85067679198230b_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-14 01:03:28.524   873  1302 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-14 01:03:29.244  3789  3789 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-14 01:03:29.249  3789  3789 D AndroidRuntime: CheckJNI is OFF
09-14 01:03:29.293  3789  3789 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-14 01:03:29.345  3789  3789 I Radio-JNI: register_android_hardware_Radio DONE
09-14 01:03:29.367  3789  3789 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-14 01:03:29.372   873  1404 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-14 01:03:29.407  2024  2035 W SearchService: Abort, client detached.
09-14 01:03:29.408  3789  3789 D AndroidRuntime: Shutting down VM
09-14 01:03:29.417  2024  2350 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@3b14dc
09-14 01:03:29.418  2024  2024 I HotwordDetector: Closing mic
09-14 01:03:29.418  2024  2358 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-14 01:03:29.428   873  1970 I ActivityManager: Start proc 3799:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-14 01:03:29.482   375  2360 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-14 01:03:29.484   375  2360 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-14 01:03:29.491   375  1274 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-14 01:03:29.493  2024  2356 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-14 01:03:29.493  2024  2357 I MicroRecognitionRnrImpl: Detection finished
09-14 01:03:29.521  3799  3799 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-14 01:03:29.548  3799  3799 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-14 01:03:29.556  3799  3799 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 3456-3460)
09-14 01:03:29.556  3799  3799 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-14 01:03:29.573  3799  3799 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {86ec275}
09-14 01:03:29.574  3799  3799 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-14 01:03:29.575  3799  3799 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-14 01:03:29.597  3799  3799 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-14 01:03:29.598  3799  3799 E SysUtils: ApplicationContext is null in ApplicationStatus
09-14 01:03:29.620  3799  3799 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-14 01:03:29.634  3799  3799 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-14 01:03:29.635  3799  3799 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-14 01:03:29.635  3799  3799 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-14 01:03:29.635  3799  3799 I Adreno  : Build Date                       : 10/20/15
09-14 01:03:29.635  3799  3799 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-14 01:03:29.635  3799  3799 I Adreno  : Local Branch                     : M14
09-14 01:03:29.635  3799  3799 I Adreno  : Remote Branch                    : 
09-14 01:03:29.635  3799  3799 I Adreno  : Remote Branch                    : 
09-14 01:03:29.635  3799  3799 I Adreno  : Reconstruct Branch               : 
,09-14 01:03:29.680   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e3a3277:true
,09-14 01:03:29.718  3799  3799 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-14 01:03:29.732  3799  3799 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-14 01:03:29.811  3799  3837 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-14 01:03:29.822  3799  3824 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-14 01:03:29.864  3799  3837 I OpenGLRenderer: Initialized EGL, version 1.4
,09-14 01:03:29.929   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +519ms
,09-14 01:03:29.929  1873  1873 I Keyboard.Facilitator: onFinishInput()
,09-14 01:03:29.991  3799  3799 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3799
,09-14 01:03:30.202  3799  3799 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-14 01:03:30.224   873  2132 I ActivityManager: Killing 2981:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-14 01:03:30.272   873  2132 I ActivityManager: Killing 3197:com.google.android.gm/u0a78 (adj 15): empty #18
,09-14 01:03:30.363  3799  3839 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1695614672
,09-14 01:03:30.368  3799  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-14 01:03:30.368  3799  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-14 01:03:30.368  3799  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-14 01:03:30.368  3799  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-14 01:03:30.368  3799  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-14 01:03:30.368  3799  3839 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5206ae9 added. We now have 1 listener(s)
,09-14 01:03:30.371  3799  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-14 01:03:30.371  3799  3839 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-14 01:03:30.372  3799  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-14 01:03:30.372  3799  3839 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-14 01:03:30.375  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-14 01:03:30.375  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-14 01:03:30.375  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-14 01:03:30.375  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-14 01:03:30.375  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-14 01:03:30.375  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-14 01:03:30.375  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-14 01:03:30.375  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-14 01:03:30.375  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-14 01:03:30.375  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-14 01:03:30.375  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-14 01:03:30.375  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-14 01:03:30.375  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-14 01:03:30.375  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-14 01:03:30.375  3799  3839 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@937da9c added. We now have 1 listener(s)
,09-14 01:03:30.375  3799  3839 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 01:03:30.378   873  1303 D WifiService: New client listening to asynchronous messages
,09-14 01:03:30.379  3799  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 01:03:30.379  3799  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-14 01:03:30.380  3799  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-14 01:03:30.381  3799  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,09-14 01:03:30.381  3799  3839 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-14 01:03:30.383  3799  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 01:03:30.383  3799  3839 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-14 01:03:30.387  3799  3839 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-14 01:03:30.388  3799  3839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 01:03:30.388  3799  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:30.388  3799  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:30.388  3799  3839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:03:30.388  3799  3839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 01:03:30.388  3799  3839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 01:03:30.388  3799  3839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 01:03:30.388  3799  3839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 01:03:30.388  3799  3839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-14 01:03:30.388  3799  3839 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 01:03:30.388  3799  3839 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-14 01:03:30.464  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:03:30.467  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:03:30.469  3799  3799 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-14 01:03:31.506  3799  3847 W jxcore-log: Initializing JXcore engine
,09-14 01:03:31.506  3799  3847 W jxcore-log: JXcore engine is ready
,09-14 01:03:31.549  3847  3847 W Thread-328: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8940 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
09-14 01:03:31.549  3847  3847 W Thread-328: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13174]" dev="sockfs" ino=13174 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-14 01:03:31.549  3847  3847 W Thread-328: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-14 01:03:31.549  3847  3847 W Thread-328: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27239]" dev="sockfs" ino=27239 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-14 01:03:31.563  3799  3847 W jxcore-log: Starting JXcore engine
,09-14 01:03:31.657  3799  3847 W jxcore-log: Platform android
09-14 01:03:31.657  3799  3847 W jxcore-log: 
,09-14 01:03:31.658  3799  3847 W jxcore-log: Process ARCH arm
09-14 01:03:31.658  3799  3847 W jxcore-log: 
,09-14 01:03:32.071  3799  3847 I jxcore-log: JXcore Cordova bridge is ready!
09-14 01:03:32.071  3799  3847 I jxcore-log: 
,09-14 01:03:32.072  3799  3847 W jxcore-log: JXcore engine is started
,09-14 01:03:32.084  3799  3839 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-14 01:03:32.092  3799  3799 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-14 01:03:33.728  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:03:33.730  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:03:33.748  1504  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-14 01:03:33.749  1504  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-14 01:03:33.749  1504  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:03:33.749  1504  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:03:33.765  3556  3851 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-14 01:03:33.765  3556  3851 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-14 01:03:33.765  3556  3851 E HttpOperation: 	at jdm.a(PG:82)
09-14 01:03:33.765  3556  3851 E HttpOperation: 	at jcs.o(PG:406)
09-14 01:03:33.765  3556  3851 E HttpOperation: 	at jcn.a(PG:1379)
09-14 01:03:33.765  3556  3851 E HttpOperation: 	at jcs.i(PG:143)
09-14 01:03:33.765  3556  3851 E HttpOperation: 	at blb.a(PG:3937)
09-14 01:03:33.765  3556  3851 E HttpOperation: 	at czp.a(PG:18188)
09-14 01:03:33.765  3556  3851 E HttpOperation: 	at czp.a(PG:9081)
09-14 01:03:33.765  3556  3851 E HttpOperation: 	at czq.run(PG:1686)
09-14 01:03:33.765  3556  3851 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-14 01:03:33.765  3556  3851 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-14 01:03:33.765  3556  3851 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-14 01:03:33.765  3556  3851 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-14 01:03:33.765  3556  3851 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-14 01:03:33.765  3556  3851 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-14 01:03:33.765  3556  3851 E HttpOperation: 	at jdj.a(PG:4091)
09-14 01:03:33.765  3556  3851 E HttpOperation: 	at jdj.a(PG:1125)
09-14 01:03:33.765  3556  3851 E HttpOperation: 	at jdm.a(PG:77)
09-14 01:03:33.765  3556  3851 E HttpOperation: 	... 12 more
09-14 01:03:33.765  3556  3851 E HttpOperation: Caused by: faj: BadAuthentication
09-14 01:03:33.765  3556  3851 E HttpOperation: 	at fal.a(PG:38)
09-14 01:03:33.765  3556  3851 E HttpOperation: 	at jdj.a(PG:4089)
09-14 01:03:33.765  3556  3851 E HttpOperation: 	... 14 more
,09-14 01:03:33.803  1504  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-14 01:03:33.803  1504  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-14 01:03:33.803  1504  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-14 01:03:33.803  1504  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:03:33.820  3556  3851 E HttpOperation: [getmobileexperiments] Unexpected exception
09-14 01:03:33.820  3556  3851 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-14 01:03:33.820  3556  3851 E HttpOperation: 	at jdm.a(PG:82)
09-14 01:03:33.820  3556  3851 E HttpOperation: 	at jcs.o(PG:406)
09-14 01:03:33.820  3556  3851 E HttpOperation: 	at jcn.a(PG:1379)
09-14 01:03:33.820  3556  3851 E HttpOperation: 	at jcs.i(PG:143)
09-14 01:03:33.820  3556  3851 E HttpOperation: 	at hec.a(PG:42)
09-14 01:03:33.820  3556  3851 E HttpOperation: 	at hee.a(PG:102)
09-14 01:03:33.820  3556  3851 E HttpOperation: 	at czr.a(PG:65)
09-14 01:03:33.820  3556  3851 E HttpOperation: 	at kka.a(PG:108)
09-14 01:03:33.820  3556  3851 E HttpOperation: 	at czp.a(PG:19176)
09-14 01:03:33.820  3556  3851 E HttpOperation: 	at czp.a(PG:9081)
09-14 01:03:33.820  3556  3851 E HttpOperation: 	at czq.run(PG:1686)
09-14 01:03:33.820  3556  3851 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-14 01:03:33.820  3556  3851 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-14 01:03:33.820  3556  3851 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-14 01:03:33.820  3556  3851 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-14 01:03:33.820  3556  3851 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-14 01:03:33.820  3556  3851 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-14 01:03:33.820  3556  3851 E HttpOperation: 	at jdj.a(PG:4091)
09-14 01:03:33.820  3556  3851 E HttpOperation: 	at jdj.a(PG:1125)
09-14 01:03:33.820  3556  3851 E HttpOperation: 	at jdm.a(PG:77)
09-14 01:03:33.820  3556  3851 E HttpOperation: 	... 15 more
09-14 01:03:33.820  3556  3851 E HttpOperation: Caused by: faj: BadAuthentication
09-14 01:03:33.820  3556  3851 E HttpOperation: 	at fal.a(PG:38)
09-14 01:03:33.820  3556  3851 E HttpOperation: 	at jdj.a(PG:4089)
09-14 01:03:33.820  3556  3851 E HttpOperation: 	... 17 more
,09-14 01:03:33.820  3556  3851 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-14 01:03:33.820  3556  3851 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	at jdm.a(PG:82)
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	at jcs.o(PG:406)
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	at jcn.a(PG:1379)
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	at jcs.i(PG:143)
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	at hec.a(PG:42)
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	at hee.a(PG:102)
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	at czr.a(PG:65)
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	at kka.a(PG:108)
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	at czp.a(PG:19176)
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	at czp.a(PG:9081)
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	at czq.run(PG:1686)
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-14 01:03:33.820  3556  3851 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	at jdj.a(PG:4091)
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	at jdj.a(PG:1125)
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	at jdm.a(PG:77)
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	... 15 more
09-14 01:03:33.820  3556  3851 E ExperimentLoader: Caused by: faj: BadAuthentication
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	at fal.a(PG:38)
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	at jdj.a(PG:4089)
09-14 01:03:33.820  3556  3851 E ExperimentLoader: 	... 17 more
,09-14 01:03:33.913   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 127455, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-14 01:03:34.674  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:03:34.720  1504  2211 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-14 01:03:34.720  1504  2211 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-14 01:03:34.721  1504  2211 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-14 01:03:34.721  1504  2211 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:03:34.753  3515  3515 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-14 01:03:34.753  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-14 01:03:34.754  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-14 01:03:46.476  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-14 01:03:46.476  3799  3847 I jxcore-log: 
,09-14 01:03:46.479  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-14 01:03:46.479  3799  3847 I jxcore-log: 
,09-14 01:03:46.492  3799  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 01:03:46.492  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:46.492  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:46.492  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:03:46.492  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 01:03:46.492  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 01:03:46.492  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 01:03:46.492  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 01:03:46.500  3799  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 01:03:46.505  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-14 01:03:46.505  3799  3847 I jxcore-log: 
,09-14 01:03:46.507  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-14 01:03:46.507  3799  3847 I jxcore-log: 
,09-14 01:03:46.868  3799  3847 D ExecuteNativeTests: Running unit tests
,09-14 01:03:46.957  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 01:03:46.958  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d added. We now have 2 listener(s)
09-14 01:03:46.959  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-14 01:03:46.959  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 01:03:46.959  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-14 01:03:46.959  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-14 01:03:46.961  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 added. We now have 2 listener(s)
,09-14 01:03:46.961  3799  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 01:03:46.962  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-14 01:03:46.964  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 01:03:46.971  3799  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 01:03:46.971  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:46.971  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:46.971  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:03:46.971  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 01:03:46.971  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 01:03:46.971  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 01:03:46.971  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 01:03:46.973  3799  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 01:03:46.974  3799  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 01:03:46.976  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-14 01:03:46.976  3799  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-14 01:03:46.976  3799  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 01:03:46.978  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:03:46.979  3799  3847 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-14 01:03:46.979  3799  3847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-14 01:03:46.980  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-14 01:03:46.980  3799  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 01:03:46.980  3799  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 01:03:46.980  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:03:46.980  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 01:03:46.980  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:03:46.981  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:46.981  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:46.981  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 01:03:46.981  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 01:03:46.981  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d removed from the list
09-14 01:03:46.981  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:46.981  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 removed from the list
09-14 01:03:46.983  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:03:46.984  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:03:46.984  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 01:03:46.984  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:46.984  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:46.986  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:03:46.986  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:03:46.986  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:46.986  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:46.987  3799  3847 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-14 01:03:46.988  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:03:46.988  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 01:03:46.988  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-14 01:03:46.988  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:46.988  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:46.988  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:46.988  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
,09-14 01:03:46.988  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:46.989  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:46.989  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 01:03:46.989  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:46.989  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:46.989  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 01:03:46.989  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:46.990  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:03:46.990  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 01:03:46.990  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:46.990  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
,09-14 01:03:46.995  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-14 01:03:46.995  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-14 01:03:46.995  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-14 01:03:46.995  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-14 01:03:46.995  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-14 01:03:46.995  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-14 01:03:46.995  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-14 01:03:46.995  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-14 01:03:46.995  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,09-14 01:03:46.995  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-14 01:03:46.995  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-14 01:03:46.996  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-14 01:03:46.996  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-14 01:03:46.996  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-14 01:03:46.996  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,09-14 01:03:46.996  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-14 01:03:46.996  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-14 01:03:46.996  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-14 01:03:46.996  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-14 01:03:46.996  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-14 01:03:46.996  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-14 01:03:46.996  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-14 01:03:46.996  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-14 01:03:46.996  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-14 01:03:46.996  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-14 01:03:46.996  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-14 01:03:46.997  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-14 01:03:46.997  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-14 01:03:46.997  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-14 01:03:46.997  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-14 01:03:46.997  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-14 01:03:46.997  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:03:46.997  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-14 01:03:46.997  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:03:46.997  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:46.997  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 01:03:46.997  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 01:03:46.997  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
09-14 01:03:46.998  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:46.998  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list,
09-14 01:03:46.998  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop,
09-14 01:03:46.998  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 01:03:46.998  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:46.998  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 01:03:46.998  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:46.999  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 01:03:46.999  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:03:46.999  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:46.999  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
,09-14 01:03:46.999  3799  3847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-14 01:03:47.001  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 01:03:47.006  3799  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-14 01:03:47.006  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:47.006  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:47.006  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:03:47.006  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 01:03:47.006  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 01:03:47.006  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 01:03:47.006  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 01:03:47.008  3799  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 01:03:47.009  3799  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 01:03:47.010  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-14 01:03:47.012  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:03:47.012  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-14 01:03:47.012  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 01:03:47.013  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 01:03:47.013  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 01:03:47.013  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 01:03:47.016  3799  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-14 01:03:47.016  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 01:03:47.021  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 01:03:47.022  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-14 01:03:47.023  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 01:03:47.025  3799  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-14 01:03:47.026  3799  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-14 01:03:47.027  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-14 01:03:47.027  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-14 01:03:47.028  3799  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-14 01:03:47.028  3799  3847 D BluetoothAdapter: STATE_ON
,09-14 01:03:47.032  2669  2679 D BtGatt.GattService: registerClient() - UUID=6a5eee9b-ff51-4e55-92ce-96c47ddb12fe
,09-14 01:03:47.033  2669  2692 D BtGatt.GattService: onClientRegistered() - UUID=6a5eee9b-ff51-4e55-92ce-96c47ddb12fe, clientIf=5
09-14 01:03:47.033  3799  3809 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-14 01:03:47.034  2669  2681 D BtGatt.GattService: start scan with filters
,09-14 01:03:47.037  2669  2696 D BtGatt.ScanManager: handling starting scan
09-14 01:03:47.037  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-14 01:03:47.038  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 01:03:47.038  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-14 01:03:47.038  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-14 01:03:47.039  2669  2696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57c0357
09-14 01:03:47.040  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-14 01:03:47.041  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-14 01:03:47.041  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 01:03:47.042  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 01:03:47.046  2669  2692 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-14 01:03:47.046  3799  3847 I io.jxcore.node.ConnectionHelper: start: OK
,09-14 01:03:47.046  2669  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 01:03:47.046  2669  2696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-14 01:03:47.049  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 01:03:47.049  3799  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-14 01:03:47.049  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-14 01:03:47.049  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-14 01:03:47.049  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.050  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 01:03:47.050  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-14 01:03:47.050  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 01:03:47.050  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-14 01:03:47.050  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 01:03:47.051  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-14 01:03:47.051  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-14 01:03:47.051  3799  3847 D BluetoothAdapter: STATE_ON
,09-14 01:03:47.052  2669  2692 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-14 01:03:47.052  2669  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 01:03:47.052  2669  2681 D BtGatt.GattService: stopScan() - queue size =1
09-14 01:03:47.053  2669  2679 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-14 01:03:47.053  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-14 01:03:47.053  2669  2696 D BtGatt.ScanManager: Starting BLE batch scan
,09-14 01:03:47.053  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 01:03:47.053  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-14 01:03:47.053  2669  2696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-14 01:03:47.053  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-14 01:03:47.053  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-14 01:03:47.054  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 01:03:47.054  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-14 01:03:47.055  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-14 01:03:47.055  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-14 01:03:47.055  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 01:03:47.056  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
,09-14 01:03:47.056  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 01:03:47.056  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 01:03:47.057  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:47.057  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 01:03:47.057  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-14 01:03:47.057  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
09-14 01:03:47.057  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 01:03:47.057  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.057  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:03:47.057  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 01:03:47.058  3799  3847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-14 01:03:47.060  3799  3799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 01:03:47.060  3799  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 01:03:47.063  2669  2692 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-14 01:03:47.063  2669  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 01:03:47.063  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 01:03:47.064  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 01:03:47.064  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 01:03:47.065  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 01:03:47.065  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-14 01:03:47.065  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 01:03:47.068  2669  2692 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 01:03:47.068  2669  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:03:47.069  3799  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 01:03:47.069  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:47.069  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:47.069  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:03:47.069  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 01:03:47.069  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 01:03:47.069  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 01:03:47.069  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 01:03:47.069  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 01:03:47.069  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 01:03:47.069  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 01:03:47.071  3799  3799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 01:03:47.071  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 01:03:47.072  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 01:03:47.072  3799  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 01:03:47.072  3799  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 01:03:47.072  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 01:03:47.073  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-14 01:03:47.074  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 01:03:47.074  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 01:03:47.074  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 01:03:47.074  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 01:03:47.076  2669  2692 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-14 01:03:47.077  2669  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:03:47.077  2669  2696 D BtGatt.ScanManager: stopping BLe Batch
09-14 01:03:47.077  3799  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 01:03:47.079  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-14 01:03:47.079  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 01:03:47.079  3799  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 01:03:47.080  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:03:47.080  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:03:47.082  2669  2692 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-14 01:03:47.082  2669  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:03:47.082  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:03:47.083  2669  2791 D BtGatt.GattService: registerClient() - UUID=e7f48a3b-78b2-411d-a0ca-b5ee8abe59be
09-14 01:03:47.083  2669  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-14 01:03:47.083  2669  2692 D BtGatt.GattService: onClientRegistered() - UUID=e7f48a3b-78b2-411d-a0ca-b5ee8abe59be, clientIf=5
09-14 01:03:47.083  3799  3811 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 01:03:47.084  2669  2681 D BtGatt.GattService: start scan with filters
09-14 01:03:47.086  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-14 01:03:47.086  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 01:03:47.086  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 01:03:47.086  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-14 01:03:47.088  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 01:03:47.088  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 01:03:47.088  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 01:03:47.089  2669  2692 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-14 01:03:47.089  2669  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:03:47.090  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-14 01:03:47.090  2669  2696 D BtGatt.ScanManager: handling starting scan
09-14 01:03:47.092  3799  3847 I io.jxcore.node.ConnectionHelper: start: OK
09-14 01:03:47.094  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:03:47.094  3799  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-14 01:03:47.094  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-14 01:03:47.094  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-14 01:03:47.094  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.094  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 01:03:47.094  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 01:03:47.094  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 01:03:47.094  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 01:03:47.094  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 01:03:47.094  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 01:03:47.094  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-14 01:03:47.095  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:03:47.095  2669  2679 D BtGatt.GattService: stopScan() - queue size =1
09-14 01:03:47.096  2669  2791 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 01:03:47.096  2669  2692 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-14 01:03:47.096  2669  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:03:47.097  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:03:47.097  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 01:03:47.097  2669  2696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-14 01:03:47.097  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-14 01:03:47.097  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-14 01:03:47.097  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-14 01:03:47.098  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 01:03:47.098  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:03:47.098  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 01:03:47.098  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 01:03:47.099  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 01:03:47.099  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:47.100  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 01:03:47.100  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.100  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 01:03:47.100  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
09-14 01:03:47.100  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.100  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.100  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 01:03:47.100  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:03:47.100  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 01:03:47.100  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 01:03:47.101  2669  2692 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-14 01:03:47.101  2669  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:03:47.102  2669  2696 D BtGatt.ScanManager: Starting BLE batch scan
09-14 01:03:47.102  2669  2696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-14 01:03:47.102  3799  3799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 01:03:47.102  3799  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 01:03:47.105  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 01:03:47.105  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 01:03:47.106  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 01:03:47.106  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 01:03:47.106  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.108  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 01:03:47.108  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 01:03:47.108  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 01:03:47.110  3799  3799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 01:03:47.111  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 01:03:47.111  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.111  2669  2692 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-14 01:03:47.111  2669  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:03:47.113  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.113  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 01:03:47.113  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.114  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:03:47.114  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:03:47.114  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:03:47.115  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:03:47.115  3799  3847 D BluetoothLeScanner: could not find callback wrapper
09-14 01:03:47.115  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:03:47.115  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.115  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.115  3799  3847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-14 01:03:47.116  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 01:03:47.117  2669  2692 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 01:03:47.117  2669  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:03:47.121  3799  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 01:03:47.121  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:47.121  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:47.121  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:03:47.121  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 01:03:47.121  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 01:03:47.121  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 01:03:47.121  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 01:03:47.122  2669  2692 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-14 01:03:47.123  2669  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:03:47.123  2669  2696 D BtGatt.ScanManager: stopping BLe Batch
09-14 01:03:47.123  3799  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 01:03:47.123  3799  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 01:03:47.124  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 01:03:47.124  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 01:03:47.125  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 01:03:47.125  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 01:03:47.125  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 01:03:47.125  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:03:47.129  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:03:47.130  2669  2692 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-14 01:03:47.130  2669  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:03:47.130  2669  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-14 01:03:47.128  3799  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 01:03:47.134  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-14 01:03:47.134  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 01:03:47.134  3799  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 01:03:47.135  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:03:47.136  2669  2692 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-14 01:03:47.136  2669  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:03:47.138  2669  2681 D BtGatt.GattService: registerClient() - UUID=8e9056b5-a5ac-43a0-9189-9618f1d4c2f3
09-14 01:03:47.138  2669  2692 D BtGatt.GattService: onClientRegistered() - UUID=8e9056b5-a5ac-43a0-9189-9618f1d4c2f3, clientIf=5
09-14 01:03:47.139  3799  3811 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 01:03:47.139  2669  2679 D BtGatt.GattService: start scan with filters
09-14 01:03:47.142  2669  2696 D BtGatt.ScanManager: handling starting scan
09-14 01:03:47.143  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-14 01:03:47.143  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 01:03:47.143  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 01:03:47.143  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-14 01:03:47.145  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 01:03:47.145  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 01:03:47.146  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 01:03:47.147  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-14 01:03:47.149  2669  2692 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-14 01:03:47.149  2669  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:03:47.149  3799  3847 I io.jxcore.node.ConnectionHelper: start: OK
09-14 01:03:47.149  2669  2696 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-14 01:03:47.149  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:03:47.149  3799  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-14 01:03:47.150  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-14 01:03:47.150  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-14 01:03:47.150  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.150  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 01:03:47.150  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 01:03:47.150  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 01:03:47.150  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 01:03:47.150  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 01:03:47.150  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 01:03:47.150  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-14 01:03:47.151  3799  3847 D BluetoothAdapter: STATE_ON
,09-14 01:03:47.151  2669  2791 D BtGatt.GattService: stopScan() - queue size =1
09-14 01:03:47.152  2669  2681 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 01:03:47.152  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:03:47.152  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 01:03:47.152  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-14 01:03:47.152  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-14 01:03:47.152  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-14 01:03:47.153  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 01:03:47.153  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:03:47.153  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 01:03:47.153  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 01:03:47.154  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 01:03:47.154  2669  2692 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-14 01:03:47.154  2669  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:03:47.155  2669  2696 D BtGatt.ScanManager: Starting BLE batch scan
09-14 01:03:47.155  2669  2696 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-14 01:03:47.155  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 01:03:47.155  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 01:03:47.155  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 01:03:47.156  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:03:47.156  3799  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-14 01:03:47.156  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 01:03:47.156  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:03:47.156  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:47.156  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.156  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 01:03:47.158  3799  3799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 01:03:47.158  3799  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 01:03:47.160  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
09-14 01:03:47.160  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.160  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.160  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:03:47.160  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 01:03:47.162  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 01:03:47.162  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 01:03:47.162  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 01:03:47.163  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 01:03:47.163  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.165  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 01:03:47.165  2669  2692 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-14 01:03:47.165  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 01:03:47.165  2669  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:03:47.165  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 01:03:47.167  3799  3799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 01:03:47.167  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 01:03:47.168  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.170  2669  2692 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 01:03:47.170  2669  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:03:47.170  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 01:03:47.170  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.170  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.171  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:03:47.172  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:03:47.172  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:03:47.172  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:03:47.172  3799  3847 D BluetoothLeScanner: could not find callback wrapper
09-14 01:03:47.172  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:03:47.172  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.172  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.173  3799  3847 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-14 01:03:47.173  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:03:47.174  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 01:03:47.174  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:03:47.174  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:47.174  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.174  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.174  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
09-14 01:03:47.174  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.174  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.174  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:03:47.174  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.174  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.174  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.174  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.175  2669  2692 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-14 01:03:47.176  2669  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:03:47.176  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:03:47.176  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:03:47.176  2669  2696 D BtGatt.ScanManager: stopping BLe Batch
09-14 01:03:47.176  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:03:47.177  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:03:47.177  3799  3847 D BluetoothLeScanner: could not find callback wrapper
09-14 01:03:47.177  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:03:47.177  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.177  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.178  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-14 01:03:47.178  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:03:47.178  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 01:03:47.178  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:03:47.178  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:47.178  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.178  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.178  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
09-14 01:03:47.179  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.179  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.179  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:03:47.179  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.179  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.179  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.179  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.180  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:03:47.180  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:03:47.180  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:03:47.180  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:03:47.180  3799  3847 D BluetoothLeScanner: could not find callback wrapper
09-14 01:03:47.180  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:03:47.181  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.181  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.181  3799  3847 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-14 01:03:47.181  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:03:47.181  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 01:03:47.181  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:03:47.182  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:47.182  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.182  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.182  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
09-14 01:03:47.182  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.182  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.182  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:03:47.182  2669  2692 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-14 01:03:47.182  2669  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:03:47.182  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.182  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.182  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.182  2669  2696 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-14 01:03:47.182  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.184  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:03:47.184  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:03:47.184  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:03:47.184  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:03:47.184  3799  3847 D BluetoothLeScanner: could not find callback wrapper
09-14 01:03:47.184  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:03:47.184  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.185  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.185  3799  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-14 01:03:47.185  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:03:47.185  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 01:03:47.185  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:03:47.186  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:47.186  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.186  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.186  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
09-14 01:03:47.186  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.186  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.186  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:03:47.186  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.186  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.186  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.186  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.187  2669  2692 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-14 01:03:47.187  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:03:47.187  2669  2692 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:03:47.187  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:03:47.187  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:03:47.188  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:03:47.188  3799  3847 D BluetoothLeScanner: could not find callback wrapper
09-14 01:03:47.188  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:03:47.188  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.188  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.189  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-14 01:03:47.190  3799  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 01:03:47.190  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-14 01:03:47.190  3799  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 01:03:47.190  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-14 01:03:47.191  3799  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-14 01:03:47.191  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:03:47.191  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 01:03:47.191  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:03:47.191  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:47.191  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.191  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.191  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
09-14 01:03:47.191  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.191  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.191  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:03:47.191  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.192  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.192  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.192  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.193  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:03:47.193  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:03:47.193  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:03:47.193  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:03:47.193  3799  3847 D BluetoothLeScanner: could not find callback wrapper
09-14 01:03:47.193  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:03:47.193  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.194  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.194  3799  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 01:03:47.194  3799  3847 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-14 01:03:47.194  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-14 01:03:47.197  3799  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 01:03:47.198  3799  3847 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-14 01:03:47.198  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-14 01:03:47.198  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-14 01:03:47.198  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-14 01:03:47.198  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-14 01:03:47.198  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-14 01:03:47.198  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-14 01:03:47.198  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-14 01:03:47.198  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-14 01:03:47.198  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-14 01:03:47.198  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-14 01:03:47.198  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-14 01:03:47.198  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-14 01:03:47.199  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-14 01:03:47.199  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-14 01:03:47.199  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-14 01:03:47.199  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-14 01:03:47.199  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-14 01:03:47.199  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-14 01:03:47.199  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-14 01:03:47.199  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-14 01:03:47.199  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-14 01:03:47.199  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-14 01:03:47.199  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-14 01:03:47.199  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-14 01:03:47.199  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-14 01:03:47.199  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-14 01:03:47.200  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-14 01:03:47.200  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-14 01:03:47.200  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-14 01:03:47.200  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-14 01:03:47.200  3799  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-14 01:03:47.200  3799  3847 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-14 01:03:47.200  3799  3847 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-14 01:03:47.200  3799  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 01:03:47.200  3799  3847 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-14 01:03:47.201  3799  3847 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-14 01:03:47.201  3799  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 01:03:47.201  3799  3847 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-14 01:03:47.201  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-14 01:03:47.204  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-14 01:03:47.205  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-14 01:03:47.205  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-14 01:03:47.205  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-14 01:03:47.205  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-14 01:03:47.205  3799  3847 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-14 01:03:47.206  3799  3847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-14 01:03:47.206  3799  3847 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-14 01:03:47.206  3799  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 392)
09-14 01:03:47.207  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:03:47.207  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 01:03:47.207  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:03:47.207  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:47.207  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.207  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.207  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-14 01:03:47.207  3799  3863 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 01:03:47.208  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
09-14 01:03:47.208  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.208  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.208  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:03:47.208  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.208  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.208  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.208  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.208  3799  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 392
09-14 01:03:47.208  3799  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 392)
09-14 01:03:47.209  3799  3864 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 392)
09-14 01:03:47.209  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:03:47.209  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:03:47.209  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:03:47.210  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:03:47.210  3799  3847 D BluetoothLeScanner: could not find callback wrapper
09-14 01:03:47.210  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:03:47.210  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.210  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.211  3799  3847 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-14 01:03:47.211  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:03:47.211  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 01:03:47.212  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:03:47.212  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:47.212  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.212  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 01:03:47.212  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
09-14 01:03:47.212  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.212  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.212  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:03:47.212  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.212  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.212  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.212  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.214  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:03:47.214  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:03:47.214  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:03:47.214  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:03:47.214  3799  3847 D BluetoothLeScanner: could not find callback wrapper
09-14 01:03:47.214  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:03:47.214  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.214  3799  3863 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 392)
09-14 01:03:47.215  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.215  3799  3847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-14 01:03:47.215  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:03:47.215  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 01:03:47.216  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:03:47.216  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:47.216  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.216  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.216  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
09-14 01:03:47.216  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.216  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.216  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:03:47.216  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.216  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.216  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.216  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.218  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:03:47.218  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:03:47.218  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:03:47.219  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:03:47.219  3799  3847 D BluetoothLeScanner: could not find callback wrapper
09-14 01:03:47.219  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:03:47.219  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.219  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.220  3799  3847 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-14 01:03:47.220  3799  3847 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-14 01:03:47.220  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-14 01:03:47.220  3799  3847 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-14 01:03:47.220  3799  3847 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-14 01:03:47.220  3799  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-14 01:03:47.220  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-14 01:03:47.220  3799  3847 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-14 01:03:47.220  3799  3847 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-14 01:03:47.220  3799  3847 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-14 01:03:47.221  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-14 01:03:47.221  3799  3847 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-14 01:03:47.221  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:03:47.221  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 01:03:47.221  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:03:47.221  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:47.221  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.221  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.221  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
09-14 01:03:47.221  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.221  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.221  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:03:47.221  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.222  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.222  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.222  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.223  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:03:47.223  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:03:47.223  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:03:47.224  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:03:47.224  3799  3847 D BluetoothLeScanner: could not find callback wrapper
09-14 01:03:47.224  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:03:47.224  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.224  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.225  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:47.225  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.225  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.225  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
09-14 01:03:47.225  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.225  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.225  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:03:47.225  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.225  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.225  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.225  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.225  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:47.225  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.225  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.226  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
09-14 01:03:47.226  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:03:47.226  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 01:03:47.226  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:03:47.226  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:47.226  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.226  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.226  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
09-14 01:03:47.226  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.226  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.226  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:03:47.226  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.226  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.227  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.227  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.228  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:03:47.228  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:03:47.228  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:03:47.229  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:03:47.229  3799  3847 D BluetoothLeScanner: could not find callback wrapper
09-14 01:03:47.229  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:03:47.229  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.229  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.230  3799  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-14 01:03:47.230  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 01:03:47.231  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-14 01:03:47.232  3799  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-14 01:03:47.232  3799  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-14 01:03:47.232  3799  3799 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-14 01:03:47.233  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-14 01:03:47.233  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-14 01:03:47.233  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:47.233  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-14 01:03:47.233  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-14 01:03:47.233  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-14 01:03:47.234  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.234  3799  3847 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-14 01:03:47.234  3799  3865 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 01:03:47.234  3799  3799 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-14 01:03:47.234  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
09-14 01:03:47.234  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.234  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 01:03:47.234  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 01:03:47.234  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 01:03:47.235  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 01:03:47.235  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:03:47.235  3799  3847 D BluetoothLeScanner: could not find callback wrapper
09-14 01:03:47.235  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:03:47.235  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:03:47.235  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 01:03:47.235  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.235  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.236  3799  3865 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-14 01:03:47.236  3799  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-14 01:03:47.236  3799  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-14 01:03:47.236  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 01:03:47.236  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 01:03:47.236  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 01:03:47.236  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 01:03:47.237  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.237  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:03:47.237  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 01:03:47.238  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:03:47.238  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:47.238  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.238  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 01:03:47.238  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
09-14 01:03:47.238  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.238  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.238  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:03:47.238  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.239  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 01:03:47.239  3799  3799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 01:03:47.239  3799  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 01:03:47.243  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-14 01:03:47.244  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 01:03:47.244  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 01:03:47.244  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 01:03:47.245  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.247  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 01:03:47.247  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 01:03:47.247  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 01:03:47.250  3799  3799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 01:03:47.250  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 01:03:47.250  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.253  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 01:03:47.253  3799  3799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-14 01:03:47.253  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.253  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.254  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:03:47.254  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:03:47.254  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:03:47.256  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:03:47.256  3799  3847 D BluetoothLeScanner: could not find callback wrapper
09-14 01:03:47.256  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:03:47.256  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.256  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.257  3799  3847 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-14 01:03:47.257  3799  3847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-14 01:03:47.258  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-14 01:03:47.258  3799  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-14 01:03:47.258  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:03:47.258  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 01:03:47.258  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:03:47.258  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:47.258  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.258  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.258  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
09-14 01:03:47.258  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.259  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.259  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:03:47.259  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.259  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.259  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.259  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.260  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:03:47.260  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:03:47.260  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:03:47.261  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:03:47.261  3799  3847 D BluetoothLeScanner: could not find callback wrapper
09-14 01:03:47.261  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:03:47.261  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.261  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.264  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:03:47.264  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 01:03:47.264  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:03:47.264  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:47.264  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.264  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.264  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
09-14 01:03:47.264  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.264  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.264  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:03:47.264  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.265  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.265  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.265  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.265  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:03:47.265  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:03:47.265  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:03:47.266  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:03:47.266  3799  3847 D BluetoothLeScanner: could not find callback wrapper
09-14 01:03:47.266  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:03:47.266  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.266  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.267  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:03:47.267  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 01:03:47.267  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:03:47.267  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:03:47.267  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.267  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.268  3799  3847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e68471d not in the list
09-14 01:03:47.268  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.268  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
,09-14 01:03:47.268  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:03:47.268  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.268  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.268  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:03:47.268  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:03:47.269  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:03:47.269  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:03:47.269  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:03:47.269  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:03:47.269  3799  3847 D BluetoothLeScanner: could not find callback wrapper
09-14 01:03:47.270  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:03:47.270  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:03:47.270  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@57f4d92 not in the list
09-14 01:03:47.270  3799  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-14 01:03:47.270  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-14 01:03:47.271  3799  3847 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-14 01:03:47.271  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-14 01:03:47.271  3799  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-14 01:03:47.271  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-14 01:03:47.272  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-14 01:03:47.272  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-14 01:03:47.273  3799  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-14 01:03:47.273  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-14 01:03:47.273  3799  3847 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-14 01:03:47.273  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-14 01:03:47.273  3799  3847 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-14 01:03:47.274  3799  3847 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-14 01:03:47.274  3799  3847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-14 01:03:47.274  3799  3847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-14 01:03:47.274  3799  3847 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-14 01:03:47.275  3799  3847 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-14 01:03:47.275  3799  3847 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-14 01:03:47.275  3799  3847 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-14 01:03:47.276  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 01:03:47.276  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9f08da8 added. We now have 2 listener(s)
09-14 01:03:47.276  3799  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 01:03:47.278  3799  3847 D BluetoothAdapter: enable(): BT is already enabled..!
09-14 01:03:47.278   873  2132 D WifiService: setWifiEnabled: true pid=3799, uid=10000
09-14 01:03:47.278   873  2132 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-14 01:03:47.280  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 01:03:47.280  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e85b0c1 added. We now have 3 listener(s)
09-14 01:03:47.280  3799  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 01:03:47.284  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 01:03:47.284  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10d4066 added. We now have 4 listener(s)
09-14 01:03:47.285  3799  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 01:03:47.286  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 01:03:47.287  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@127afa7 added. We now have 5 listener(s)
09-14 01:03:47.287  3799  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 01:03:47.289   873  2206 D WifiService: setWifiEnabled: false pid=3799, uid=10000
09-14 01:03:47.290   873  2206 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-14 01:03:47.294  2669  2687 D BluetoothAdapterState: Current state: ON, message: 23
09-14 01:03:47.294  2669  2687 D BluetoothAdapterProperties: Setting state to 13
09-14 01:03:47.294  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 01:03:47.294  2669  2687 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-14 01:03:47.295  2669  2687 D BluetoothAdapterProperties: onBluetoothDisable()
09-14 01:03:47.295  2669  2687 I BluetoothAdapterState: Entering PendingCommandState
09-14 01:03:47.296  2669  2692 D BluetoothAdapterProperties: Scan Mode:20
09-14 01:03:47.297  2669  2687 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-14 01:03:47.298  2669  2669 D BluetoothMapService: onReceive
09-14 01:03:47.298  2669  2669 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-14 01:03:47.298  2669  2669 D BluetoothMapService: STATE_TURNING_OFF
09-14 01:03:47.298  2669  2669 D BluetoothMapService: MAP Service closeService in
09-14 01:03:47.298  2669  2669 D BluetoothMapMasInstance0: MAP Service shutdown
09-14 01:03:47.299  2669  2669 D ObexServerSockets0: shutdown(block = true)
09-14 01:03:47.299  2669  2669 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-14 01:03:47.299  2669  2669 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-14 01:03:47.299  2669  2811 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-14 01:03:47.300  2669  2786 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-14 01:03:47.300  2669  2812 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-14 01:03:47.301  2669  2669 I BtOppRfcommListener: stopping Accept Thread
09-14 01:03:47.301  2669  3410 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-14 01:03:47.301  2669  3410 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-14 01:03:47.303  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 01:03:47.303  3799  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 01:03:47.303  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:47.303  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:47.303  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:03:47.303  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 01:03:47.303  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 01:03:47.303  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 01:03:47.303  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 01:03:47.304  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 01:03:47.305  3799  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 01:03:47.305  3799  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 01:03:47.308  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-14 01:03:47.308  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:03:47.311  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:03:47.312   873  1302 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-14 01:03:47.312   873  1302 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-14 01:03:47.312   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-14 01:03:47.312   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 01:03:47.316  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 01:03:47.316  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 01:03:47.316  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:47.316  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:47.316  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:03:47.316  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 01:03:47.316  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 01:03:47.316  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 01:03:47.316  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 01:03:47.317  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 01:03:47.317  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 01:03:47.319  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:03:47.321   873   886 I ActivityManager: Start proc 3868:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-14 01:03:47.323  2669  2669 D HeadsetService: Received stop request...Stopping profile...
09-14 01:03:47.323   873  1906 D DhcpClient: Clearing IP address
09-14 01:03:47.323   371   871 D CommandListener: Clearing all IP addresses on wlan0
09-14 01:03:47.325  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:03:47.325   873   873 D BluetoothHeadset: Proxy object disconnected
,09-14 01:03:47.325   873   873 D BluetoothHeadset: Proxy object disconnected
09-14 01:03:47.325  1357  1376 D BluetoothHeadset: Proxy object disconnected
09-14 01:03:47.326   873   873 D BluetoothHeadset: Proxy object disconnected
09-14 01:03:47.326  1944  2138 D BluetoothHeadset: Proxy object disconnected
,09-14 01:03:47.327   371   871 D CommandListener: Setting iface cfg
09-14 01:03:47.329  1504  2501 V NativeCrypto: Read error: ssl=0x9b05c000: I/O error during system call, Connection timed out
09-14 01:03:47.330  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:03:47.330  1504  2501 V NativeCrypto: SSL shutdown failed: ssl=0x9b05c000: I/O error during system call, Broken pipe
09-14 01:03:47.333  2669  2669 D A2dpService: Received stop request...Stopping profile...
09-14 01:03:47.334   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-14 01:03:47.334   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-14 01:03:47.334  2669  2794 D A2dpStateMachine: Exit Disconnected: -1
,09-14 01:03:47.336   873   873 D BluetoothA2dp: Proxy object disconnected
,09-14 01:03:47.336   452   452 E Parcel  : Reading a NULL string not supported here.
09-14 01:03:47.336   873  1917 D DhcpClient: Receive thread stopped
,09-14 01:03:47.337  2669  2669 D HidService: Received stop request...Stopping profile...
09-14 01:03:47.337  2669  2669 D HidService: Stopping Bluetooth HidService
09-14 01:03:47.338  1357  1357 D HeadsetProfile: Bluetooth service disconnected
,09-14 01:03:47.338   873  1302 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-14 01:03:47.339  1357  1357 D BluetoothA2dp: Proxy object disconnected
,09-14 01:03:47.339   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-14 01:03:47.340   873  1304 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,09-14 01:03:47.342   371   871 D CommandListener: Clearing all IP addresses on wlan0
09-14 01:03:47.344  2669  2669 V BluetoothAdapterState: isTurningOff()=true
09-14 01:03:47.344  2669  2669 V BluetoothAdapterState: isTurningOn()=false
09-14 01:03:47.344  2669  2669 V BluetoothAdapterState: isBleTurningOn()=false
09-14 01:03:47.344  2669  2669 V BluetoothAdapterState: isBleTurningOff()=false
09-14 01:03:47.343  1357  1357 D BluetoothInputDevice: Proxy object disconnected
09-14 01:03:47.344  1357  1357 D HidProfile: Bluetooth service disconnected
09-14 01:03:47.346  2669  2669 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-14 01:03:47.346  2669  2669 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-14 01:03:47.346  2669  2769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 01:03:47.346  2669  2769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 01:03:47.346  2669  2769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-14 01:03:47.346  2669  2692 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-14 01:03:47.346  2669  2692 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-14 01:03:47.355  2669  2669 D HealthService: Received stop request...Stopping profile...
,09-14 01:03:47.358  2669  2669 D PanService: Received stop request...Stopping profile...
,09-14 01:03:47.359  2669  2669 D BluetoothMapService: Received stop request...Stopping profile...
,09-14 01:03:47.359  2669  2669 D BluetoothMapService: stop()
,09-14 01:03:47.360  2669  2669 D BluetoothMapAppObserver: deinitObservers()
,09-14 01:03:47.360  2669  2669 D BluetoothMapAppObserver: removeReceiver()
,09-14 01:03:47.361  2669  2669 V BluetoothAdapterState: isTurningOff()=true
09-14 01:03:47.361  2669  2669 V BluetoothAdapterState: isTurningOn()=false
,09-14 01:03:47.361  2669  2669 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 01:03:47.361  2669  2669 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 01:03:47.362  2669  2669 V BluetoothAdapterState: isTurningOff()=true
09-14 01:03:47.362  2669  2669 V BluetoothAdapterState: isTurningOn()=false
,09-14 01:03:47.362  2669  2669 V BluetoothAdapterState: isBleTurningOn()=false
09-14 01:03:47.362  2669  2669 V BluetoothAdapterState: isBleTurningOff()=false
09-14 01:03:47.362  2669  2669 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-14 01:03:47.362  2669  2669 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-14 01:03:47.363  2669  2669 V BluetoothAdapterState: isTurningOff()=true
09-14 01:03:47.363  2669  2669 V BluetoothAdapterState: isTurningOn()=false
09-14 01:03:47.363  2669  2669 V BluetoothAdapterState: isBleTurningOn()=false
09-14 01:03:47.363  2669  2669 V BluetoothAdapterState: isBleTurningOff()=false
09-14 01:03:47.363  2669  2669 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-14 01:03:47.363  2669  2692 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-14 01:03:47.363  2669  2692 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-14 01:03:47.363  2669  2692 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-14 01:03:47.363  2669  2769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 01:03:47.364  2669  2769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 01:03:47.364  2669  2769 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-14 01:03:47.364  2669  2769 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 01:03:47.364  2669  2769 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-14 01:03:47.364  2669  2769 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 01:03:47.365  2669  2669 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-14 01:03:47.366  2669  2669 V BluetoothAdapterState: isTurningOff()=true
09-14 01:03:47.366  2669  2669 V BluetoothAdapterState: isTurningOn()=false
09-14 01:03:47.366  2669  2669 V BluetoothAdapterState: isBleTurningOn()=false
09-14 01:03:47.366  2669  2669 V BluetoothAdapterState: isBleTurningOff()=false
09-14 01:03:47.366  2669  2669 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-14 01:03:47.367  2669  2669 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-14 01:03:47.368  2669  2669 D BluetoothMapService: MAP Service closeService in
09-14 01:03:47.368  2669  2669 V BluetoothAdapterState: isTurningOff()=true
09-14 01:03:47.368  2669  2669 V BluetoothAdapterState: isTurningOn()=false
09-14 01:03:47.368  2669  2669 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 01:03:47.368  2669  2669 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 01:03:47.368  2669  2669 D BluetoothMapService: cleanup()
,09-14 01:03:47.368  2669  2669 D BluetoothMapService: MAP Service closeService in
09-14 01:03:47.369  2669  2687 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-14 01:03:47.369  2669  2687 D BluetoothAdapterProperties: Setting state to 15
09-14 01:03:47.369  2669  2687 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-14 01:03:47.369   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-14 01:03:47.370  1357  1376 D BluetoothPan: onBluetoothStateChange on: false
,09-14 01:03:47.371   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 01:03:47.371   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 01:03:47.371  1357  1386 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 01:03:47.371  2669  2687 I BluetoothAdapterState: Entering BleOnState
09-14 01:03:47.371  1357  2073 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 01:03:47.372   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 01:03:47.372  1944  1963 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 01:03:47.372   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 01:03:47.372  1357  3798 D BluetoothMap: onBluetoothStateChange: up=false
09-14 01:03:47.373  1357  1376 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-14 01:03:47.373  1357  1386 D BluetoothPbap: onBluetoothStateChange: up=false
09-14 01:03:47.374  2669  2687 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-14 01:03:47.374  2669  2687 D BluetoothAdapterProperties: Setting state to 16
09-14 01:03:47.374  2669  2687 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-14 01:03:47.375  2669  2687 D BluetoothAdapterProperties: onBleDisable
,09-14 01:03:47.375  2669  2687 I BluetoothAdapterState: Entering PendingCommandState
09-14 01:03:47.376  2669  2688 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-14 01:03:47.377  2669  2692 D BluetoothAdapterProperties: Scan Mode:20
09-14 01:03:47.377  2669  2769 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-14 01:03:47.377  2669  2769 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 01:03:47.378  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 01:03:47.378  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 01:03:47.378  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:47.378  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:47.378  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:03:47.378  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 01:03:47.378  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 01:03:47.378  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 01:03:47.378  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 01:03:47.379  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 01:03:47.379  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 01:03:47.380  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 01:03:47.380  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 01:03:47.380  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:47.380  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:47.380  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:03:47.380  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 01:03:47.380  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 01:03:47.380  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 01:03:47.380  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 01:03:47.381  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 01:03:47.381  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-14 01:03:47.382  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:03:47.382  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:03:47.398   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-14 01:03:47.399   873  1304 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,09-14 01:03:47.399   873  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-14 01:03:47.402   873   890 D Tethering: MasterInitialState.processMessage what=3
09-14 01:03:47.405   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
09-14 01:03:47.406  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 01:03:47.406  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 01:03:47.406  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:47.406  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:47.406  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 01:03:47.406  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 01:03:47.406  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 01:03:47.406  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 01:03:47.406  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 01:03:47.407  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 01:03:47.407  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 01:03:47.408  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 01:03:47.408  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 01:03:47.408  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:47.408  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:47.408  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 01:03:47.408  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 01:03:47.408  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 01:03:47.408  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 01:03:47.408  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 01:03:47.408   873  1302 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-14 01:03:47.408  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 01:03:47.408  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 01:03:47.409  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:03:47.410  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:03:47.411  3403  3403 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@5206ae9 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-14 01:03:47.414  1887  2317 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-14 01:03:47.431  3868  3868 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-14 01:03:47.439  3868  3868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-14 01:03:47.444  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 01:03:47.446   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@88fb9ff:true
,09-14 01:03:47.449   371   871 E Netd    : netlink response contains error (No such file or directory)
,09-14 01:03:47.450   873  1304 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-14 01:03:47.456   873  2131 I ActivityManager: Start proc 3889:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-14 01:03:47.479  3868  3868 D LocalBluetoothProfileManager: Adding local MAP profile
,09-14 01:03:47.482  3868  3868 D BluetoothMap: Create BluetoothMap proxy object
,09-14 01:03:47.489  3868  3868 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-14 01:03:47.493  3889  3889 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-14 01:03:47.502  3868  3868 D DockEventReceiver: finishStartingService: stopping service
,09-14 01:03:47.512   873  1365 I ActivityManager: Killing 3403:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-14 01:03:47.578  2669  2692 I bt_hci  : shut_down
,09-14 01:03:47.579  2669  2697 D bt_hwcfg: hw_epilog_process
,09-14 01:03:47.580  2669  2697 I bt_vendor: low_power_mode_cb
,09-14 01:03:47.610  2669  2697 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-14 01:03:47.610  2669  2697 I bt_vendor: epilog_cb
09-14 01:03:47.610  2669  2697 I bt_hci  : epilog_finished_callback
,09-14 01:03:47.624  2669  2692 I bt_hci_h4: hal_close
,09-14 01:03:47.624  2669  2692 I bt_userial_vendor: device fd = 51 close
,09-14 01:03:47.702  3889  3889 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 01:03:47.702  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at java.io.File.exists(File.java:361)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 01:03:47.702  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 01:03:47.703  3889  3889 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.,f.a.a(PG:48)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 01:03:47.703  3889  3889 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
,09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 01:03:47.703  3889  3889 D StrictMode: 	,at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
,09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
,09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-14 01:03:47.703  3889  3889 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 01:03:47.703  3889  3889 D StrictMode: 	,at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468),
09-14 01:03:47.703  3889  3889 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
,09-14 01:03:47.703  3889  3889 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.r.k.d(PG:1187),
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.r.e.b(PG:170)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 01:03:47.703  3889  3889 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.r.k.d(PG:583)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.r.e.b(PG:170)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared,.i.h.a(PG:251)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 01:03:47.703  3889  3889 D StrictMode: StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at java.io.File.exists(File.java:361)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
,09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-14 01:03:47.703  3889  3889 D StrictMode: StrictMode policy violation; ~duration=60 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at java.io.File.exists(File.java:361)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703),
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 01:03:47.703  3889  3889 D StrictMode: 	,at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 01:03:47.703  3889  3889 D StrictMode: 	,at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 01:03:47.703  3889  3889 D StrictMode: 	,at android.app.ActivityThread.main(ActivityThread.java:5417)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 01:03:47.703  3889  3889 D StrictMode: StrictMode policy violation; ~duration=59 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-14 01:03:47.703  3889  3889 D StrictMode: 	,at java.io.File.lastModified(File.java:569)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174),
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 01:03:47.703  3889  3889 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 01:03:47.710  3868  3868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-14 01:03:47.719  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-14 01:03:47.728  3868  3868 D DockEventReceiver: finishStartingService: stopping service
,09-14 01:03:47.748   873   884 I ActivityManager: Killing 3569:com.google.process.gapps/u0a99 (adj 15): empty #17
09-14 01:03:47.749  2669  2688 D bt_stack_manager: event_shut_down_stack finished.
09-14 01:03:47.749  2669  2687 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-14 01:03:47.754  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 01:03:47.789  2669  2669 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-14 01:03:47.790  2669  2687 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-14 01:03:47.790  2669  2669 D BtGatt.GattService: Received stop request...Stopping profile...
,09-14 01:03:47.790  2669  2669 D BtGatt.GattService: stop()
,09-14 01:03:47.791  2669  2669 D BtGatt.AdvertiseManager: advertise clients cleared
,09-14 01:03:47.798  1699  1699 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-14 01:03:47.800  2669  2669 V BluetoothAdapterState: isTurningOff()=false
,09-14 01:03:47.800  2669  2669 V BluetoothAdapterState: isTurningOn()=false
09-14 01:03:47.800  2669  2669 V BluetoothAdapterState: isBleTurningOn()=false
09-14 01:03:47.800  2669  2669 V BluetoothAdapterState: isBleTurningOff()=true
,09-14 01:03:47.801  2669  2687 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-14 01:03:47.802  2669  2687 D BluetoothAdapterProperties: Setting state to 10
,09-14 01:03:47.802  2669  2687 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-14 01:03:47.803  2669  2687 I BluetoothAdapterState: Entering OffState
,09-14 01:03:47.804   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
09-14 01:03:47.813  1699  1699 D SystemUpdateService: onCreate
,09-14 01:03:47.823  1699  1699 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-14 01:03:47.833  2669  2669 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-14 01:03:47.833  2669  2669 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-14 01:03:47.833  2669  2669 I BluetoothServiceJni: cleanupNative: return from cleanup
09-14 01:03:47.835  2669  2688 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-14 01:03:47.838  2669  2688 D bt_stack_manager: event_clean_up_stack finished.
,09-14 01:03:47.841  1699  3920 I SystemUpdateService: active receiver: enabled
,09-14 01:03:47.848  1699  1699 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-14 01:03:47.849  2669  2669 I art     : System.exit called, status: 0
09-14 01:03:47.849  2669  2669 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-14 01:03:47.860  1699  2467 I iu.UploadsManager: num queued entries: 0
,09-14 01:03:47.860  1699  2467 I iu.UploadsManager: num updated entries: 0
09-14 01:03:47.861  1699  2467 I iu.SyncManager: NEXT; no task
,09-14 01:03:47.870  1699  1699 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-14 01:03:47.871  1699  1699 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-14 01:03:47.875  1699  3920 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-14 01:03:47.882  1699  3920 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-14 01:03:47.882  1699  3920 I SystemUpdateService: now status is 0 (complete)
09-14 01:03:47.882  1699  3920 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-14 01:03:47.882  1699  3920 I SystemUpdateService: file has been verified
09-14 01:03:47.882  1699  3920 I SystemUpdateService: OTA package size = 12249756
,09-14 01:03:47.887  1699  3920 I SystemUpdateService: showing system update notification
,09-14 01:03:47.920  3889  3912 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-14 01:03:47.925   873  1991 I ActivityManager: Start proc 3925:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-14 01:03:47.926   873  1404 I ActivityManager: Process com.android.bluetooth (pid 2669) has died
,09-14 01:03:47.932   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c14827e:true
,09-14 01:03:47.959  1699  1699 D SystemUpdateService: onDestroy
,09-14 01:03:47.993  3925  3925 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-14 01:03:47.995  3925  3925 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-14 01:03:48.002  3925  3925 D SprintDMHelper: simOperator: 
,09-14 01:03:48.002  3925  3925 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-14 01:03:48.018   873  1404 I ActivityManager: Start proc 3938:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-14 01:03:48.128   873  2204 I ActivityManager: Start proc 3953:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-14 01:03:48.132   873  1687 I ActivityManager: Killing 3023:com.google.android.keep/u0a79 (adj 15): empty #17
,09-14 01:03:48.204  3953  3953 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-14 01:03:48.270  3953  3953 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-14 01:03:48.270  3953  3953 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-14 01:03:48.270  3953  3953 I GAv4    :   adb logcat -s GAv4
,09-14 01:03:48.282  3953  3953 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-14 01:03:48.290  3953  3953 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-14 01:03:48.326  3953  3970 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.,
,09-14 01:03:48.410  3953  3953 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-14 01:03:48.455  3953  3953 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-14 01:03:48.462  3953  3953 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2363-2366)
09-14 01:03:48.462  3953  3953 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-14 01:03:48.471  3953  3953 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {12ce059}
09-14 01:03:48.472  3953  3953 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-14 01:03:48.472  3953  3953 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-14 01:03:48.479  3953  3953 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-14 01:03:48.481  3953  3953 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-14 01:03:48.495  3953  3953 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-14 01:03:48.506  3953  3953 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-14 01:03:48.506  3953  3953 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-14 01:03:48.506  3953  3953 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
,09-14 01:03:48.506  3953  3953 I Adreno  : Build Date                       : 10/20/15
09-14 01:03:48.506  3953  3953 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-14 01:03:48.506  3953  3953 I Adreno  : Local Branch                     : M14
09-14 01:03:48.506  3953  3953 I Adreno  : Remote Branch                    : 
09-14 01:03:48.506  3953  3953 I Adreno  : Remote Branch                    : ,
09-14 01:03:48.506  3953  3953 I Adreno  : Reconstruct Branch               : 
,09-14 01:03:48.566  3953  3953 I NSApplication: Starting up...
,09-14 01:03:48.573  3953  3999 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-14 01:03:48.611   873  1970 I ActivityManager: Start proc 4004:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-14 01:03:48.615   873  1970 I ActivityManager: Killing 3610:com.google.android.apps.books/u0a34 (adj 15): empty #17
,09-14 01:03:48.737  4004  4004 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-14 01:03:48.903   873   883 I ActivityManager: Killing 3455:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-14 01:03:48.996   873  2204 I ActivityManager: Start proc 4018:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-14 01:03:49.067  4018  4018 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-14 01:03:49.145  4018  4018 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-14 01:03:49.174   873  1687 I ActivityManager: Start proc 4041:com.google.android.keep/u0a79 for broadcast com.google.android.keep/.notification.AlertReceiver
,09-14 01:03:49.176   873  1687 I ActivityManager: Killing 3495:android.process.acore/u0a5 (adj 15): empty #17
,09-14 01:03:49.269  4041  4041 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltKeep/lib/arm
,09-14 01:03:49.532   873  2132 I ActivityManager: Killing 3648:com.android.defcontainer/u0a7 (adj 15): empty #17
,09-14 01:03:50.307   873  2208 D WifiService: setWifiEnabled: true pid=3799, uid=10000
,09-14 01:03:50.308   873  2208 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 01:03:50.322   873  1302 D WifiConfigStore: Loading config and enabling all networks 
,09-14 01:03:50.332  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 01:03:50.333  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 01:03:50.333  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:50.333  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:50.333  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:03:50.333  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 01:03:50.333  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 01:03:50.333  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 01:03:50.333  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 01:03:50.333  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 01:03:50.334  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 01:03:50.337  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 01:03:50.337  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 01:03:50.337  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:50.337  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:50.337  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:03:50.337  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 01:03:50.337  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 01:03:50.337  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 01:03:50.337  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 01:03:50.337  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 01:03:50.337  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 01:03:50.348   873  1302 D WifiConfigStore: loaded 0 passpoint configs
09-14 01:03:50.349   873  1302 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-14 01:03:50.350   873  1302 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-14 01:03:50.351   873  1302 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-14 01:03:50.351   873  1302 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2,
09-14 01:03:50.351   873  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-14 01:03:50.352   873  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-14 01:03:50.372   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-14 01:03:50.373   873  1302 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.75 rxSuccessRate=14.00 delta 1000 -> 994
,09-14 01:03:50.375   371   871 D CommandListener: Setting iface cfg
,09-14 01:03:50.376   873  1300 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-14 01:03:50.376   873  1300 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-14 01:03:50.381   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-14 01:03:50.381   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 01:03:50.383   873  1300 D WifiNative-HAL: p2pGetDeviceAddress
09-14 01:03:50.384   873  1300 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62,
,09-14 01:03:50.390   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-14 01:03:50.454   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-14 01:03:50.455  1453  1453 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-14 01:03:50.878  1453  1453 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-14 01:03:50.922  1453  1453 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-14 01:03:50.923  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-14 01:03:50.934   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,09-14 01:03:50.948   873  1302 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-14 01:03:50.949   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 01:03:50.949   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-14 01:03:50.982   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 01:03:51.006   371   871 D CommandListener: Setting iface cfg
,09-14 01:03:51.008   873  1302 D WifiStateMachine: Start Dhcp Watchdog 2
,09-14 01:03:51.028   873  1304 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-14 01:03:51.030   873  4071 D DhcpClient: Receive thread started
,09-14 01:03:51.036   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-14 01:03:51.127   873  1302 E native  : do suspend false
,09-14 01:03:51.145   873  1906 D DhcpClient: Broadcasting DHCPDISCOVER
,09-14 01:03:51.160   873  4071 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172677, domain null
,09-14 01:03:51.161   873  1906 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172677 seconds
,09-14 01:03:51.164   873  1906 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-14 01:03:51.177   873  4071 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-14 01:03:51.178   873  1906 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-14 01:03:51.183   371   871 D CommandListener: Setting iface cfg
,09-14 01:03:51.194   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-14 01:03:51.195   873  1906 D DhcpClient: Scheduling renewal in 86399s
,09-14 01:03:51.203   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-14 01:03:51.204   873  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,09-14 01:03:51.205   873  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 01:03:51.205   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-14 01:03:51.214   873  1304 D ConnectivityService: Adding iface wlan0 to network 101
,09-14 01:03:51.215   873  1302 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-14 01:03:51.253   873  1304 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-14 01:03:51.254   873  1304 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-14 01:03:51.255   873  1304 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101,
09-14 01:03:51.256   873  1304 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-14 01:03:51.257   873  1304 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-14 01:03:51.266   873  1304 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 01:03:51.270   873  1304 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-14 01:03:51.270   873  1304 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-14 01:03:51.270   873  1304 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-14 01:03:51.270   873  1304 D ConnectivityService:    accepting network in place of null
,09-14 01:03:51.270   873  1302 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-14 01:03:51.271   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-14 01:03:51.271   873  1304 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-14 01:03:51.281   873  4070 D NetlinkSocketObserver: NeighborEvent{elapsedMs=145185, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-14 01:03:51.304   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 01:03:51.333   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 01:03:51.345   873  1304 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-14 01:03:51.345   873  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-14 01:03:51.348   873  4069 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-14 01:03:51.353   873  1304 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
09-14 01:03:51.358   873   890 D Tethering: MasterInitialState.processMessage what=3
09-14 01:03:51.360  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 01:03:51.360  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 01:03:51.360  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:51.360  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:51.360  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:03:51.360  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 01:03:51.360  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 01:03:51.360  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 01:03:51.360  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 01:03:51.360  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 01:03:51.360  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 01:03:51.367  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 01:03:51.367  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 01:03:51.367  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:51.367  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:51.367  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:03:51.367  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 01:03:51.367  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 01:03:51.367  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 01:03:51.367  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 01:03:51.367  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 01:03:51.367  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 01:03:51.378  1699  1699 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-14 01:03:51.382  1699  1699 D SystemUpdateService: onCreate
,09-14 01:03:51.385  1699  1699 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-14 01:03:51.388  1699  4082 I SystemUpdateService: active receiver: enabled
,09-14 01:03:51.392  1699  4082 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-14 01:03:51.396  1699  4082 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-14 01:03:51.396  1699  4082 I SystemUpdateService: now status is 0 (complete)
09-14 01:03:51.396  1699  4082 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-14 01:03:51.396  1699  4082 I SystemUpdateService: file has been verified
09-14 01:03:51.396  1699  4082 I SystemUpdateService: OTA package size = 12249756
,09-14 01:03:51.401  1699  4082 I SystemUpdateService: showing system update notification
,09-14 01:03:51.404   873  4069 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 23:03:51 GMT], X-Android-Received-Millis=[1473807831404], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473807831383]}
,09-14 01:03:51.405   873  1304 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-14 01:03:51.405   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-14 01:03:51.405   873  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-14 01:03:51.406   873  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-14 01:03:51.410  1699  1699 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-14 01:03:51.415  1699  2467 I iu.UploadsManager: num queued entries: 0
,09-14 01:03:51.415  1699  1699 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-14 01:03:51.417  1699  1699 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-14 01:03:51.419  1699  2467 I iu.UploadsManager: num updated entries: 0
,09-14 01:03:51.419  1699  4087 I MDM     : [173] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-14 01:03:51.420  1699  4087 W BaseAppContext: Using Auth Proxy for data requests.
,09-14 01:03:51.420  1699  2467 I iu.SyncManager: NEXT; no task
09-14 01:03:51.421  1699  4087 V GoogleAuthProtoRequest: [173] a.<init>: mAccountName set to: thalitester@gmail.com
09-14 01:03:51.421  3925  3925 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-14 01:03:51.425  1699  1699 D SystemUpdateService: onDestroy
,09-14 01:03:51.429  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:03:51.432  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:03:51.435  3925  3925 D SprintDMHelper: simOperator: 
09-14 01:03:51.435  3925  3925 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-14 01:03:51.495   873   885 I ActivityManager: Start proc 4091:com.google.android.apps.books/u0a34 for service com.google.android.apps.books/.service.SyncService
,09-14 01:03:51.523  1504  2971 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-14 01:03:51.524  1504  2971 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-14 01:03:51.524  1504  2971 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-14 01:03:51.525  1504  2971 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:03:51.546  4091  4091 W System  : ClassLoader referenced unknown path: /system/app/Books/lib/arm
,09-14 01:03:51.549  1699  4087 E MDM     : [173] SitrepService.a: Error sending sitrep.
,09-14 01:03:51.576  2304  4090 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-14 01:03:51.596  4041  4104 V KeepSync: Connecting to GoogleApiClient
,09-14 01:03:51.598   873   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-14 01:03:51.625  4091  4091 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,09-14 01:03:51.635  4091  4091 I BooksApp: Created application version: 3.6.9 (30609)
,09-14 01:03:51.645  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-14 01:03:51.646  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-14 01:03:51.646  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:03:51.646  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:03:51.670  1699  4114 V BaseAuthAsyncOperation: access token request failed
,09-14 01:03:51.673  4041  4104 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-14 01:03:51.748  4091  4116 I BooksSync: Starting books sync for 61035162, extras: ade
,09-14 01:03:51.877  1504  2211 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-14 01:03:51.877  1504  2211 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-14 01:03:51.878  1504  2211 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-14 01:03:51.878  1504  2211 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:03:51.901  4091  4122 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-14 01:03:51.929  4041  4104 E KeepSync: IOException
09-14 01:03:51.929  4041  4104 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-14 01:03:51.929  4041  4104 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-14 01:03:51.929  4041  4104 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-14 01:03:51.929  4041  4104 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-14 01:03:51.929  4041  4104 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-14 01:03:51.929  4041  4104 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-14 01:03:51.929  4041  4104 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-14 01:03:51.929  4041  4104 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-14 01:03:51.929  4041  4104 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-14 01:03:51.929  4041  4104 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-14 01:03:51.929  4041  4104 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-14 01:03:51.929  4041  4104 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-14 01:03:51.929  4041  4104 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-14 01:03:51.929  4041  4104 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-14 01:03:51.929  4041  4104 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-14 01:03:51.929  4041  4104 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-14 01:03:51.929  4041  4104 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-14 01:03:51.929  4041  4104 E KeepSync: 	... 10 more
,09-14 01:03:51.929  4041  4104 W KeepSync: Sync result 2
,09-14 01:03:51.937   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 128465, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-14 01:03:51.955  1504  1997 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-14 01:03:51.955  1504  1997 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-14 01:03:51.955  1504  1997 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:03:51.955  1504  1997 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:03:51.982  1504  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-14 01:03:51.982  1504  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-14 01:03:51.982  1504  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-14 01:03:51.982  1504  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:03:51.993  4091  4122 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-14 01:03:51.995  4091  4116 E BooksSync: Soft error
09-14 01:03:51.995  4091  4116 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-14 01:03:51.995  4091  4116 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-14 01:03:51.995  4091  4116 E BooksSync: Sync error
09-14 01:03:51.995  4091  4116 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-14 01:03:51.995  4091  4116 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-14 01:03:51.996  4091  4116 I BooksSync: Finished books sync
,09-14 01:03:52.007   873  1404 I ActivityManager: Killing 3683:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-14 01:03:52.012   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 128002, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-14 01:03:52.344   873  1304 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-14 01:03:53.054   873  2206 I ActivityManager: Killing 3700:com.android.musicfx/u0a18 (adj 15): empty #17
,09-14 01:03:53.315   873   883 D WifiService: setWifiEnabled: false pid=3799, uid=10000
09-14 01:03:53.316   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 01:03:53.347  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-14 01:03:53.351   873  1302 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-14 01:03:53.352   873  1302 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-14 01:03:53.352   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-14 01:03:53.353   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 01:03:53.373   873  1906 D DhcpClient: Clearing IP address
09-14 01:03:53.374   371   871 D CommandListener: Clearing all IP addresses on wlan0
,09-14 01:03:53.380   371   871 D CommandListener: Setting iface cfg
,09-14 01:03:53.394   873  4071 D DhcpClient: Receive thread stopped
,09-14 01:03:53.400   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-14 01:03:53.401   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
09-14 01:03:53.408   452   452 E Parcel  : Reading a NULL string not supported here.
09-14 01:03:53.410   873  1302 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-14 01:03:53.411   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-14 01:03:53.417   371   871 D CommandListener: Clearing all IP addresses on wlan0
,09-14 01:03:53.421   873  1304 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-14 01:03:53.426   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,09-14 01:03:53.431  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 01:03:53.431  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 01:03:53.431  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:53.431  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:53.431  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 01:03:53.431  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 01:03:53.431  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 01:03:53.431  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 01:03:53.431  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 01:03:53.431  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 01:03:53.431  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 01:03:53.433   873  1302 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-14 01:03:53.433  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 01:03:53.433  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 01:03:53.433  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:53.433  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:53.433  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 01:03:53.433  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 01:03:53.433  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 01:03:53.433  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 01:03:53.433  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 01:03:53.433  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 01:03:53.434  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 01:03:53.436  1887  2317 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-14 01:03:53.460   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 01:03:53.486   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 01:03:53.487   873  1304 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-14 01:03:53.487   873  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-14 01:03:53.489   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-14 01:03:53.496  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:03:53.497  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:03:53.502  1699  1699 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-14 01:03:53.506  1699  1699 D SystemUpdateService: onCreate
,09-14 01:03:53.511  1699  1699 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-14 01:03:53.525  1699  1699 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-14 01:03:53.527  1699  2467 I iu.UploadsManager: num queued entries: 0
,09-14 01:03:53.528  1699  2467 I iu.UploadsManager: num updated entries: 0
,09-14 01:03:53.531  1699  4132 I SystemUpdateService: active receiver: enabled
,09-14 01:03:53.534  1699  1699 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-14 01:03:53.535  1699  1699 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-14 01:03:53.537  3925  3925 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-14 01:03:53.542  3925  3925 D SprintDMHelper: simOperator: 
09-14 01:03:53.542  3925  3925 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-14 01:03:53.563  1699  2467 I iu.SyncManager: NEXT; no task
,09-14 01:03:53.573  2304  4137 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-14 01:03:53.575  1699  4132 I SystemUpdateService: Already downloaded, skipping offpeak checks.,
,09-14 01:03:53.582  1699  4132 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-14 01:03:53.582  1699  4132 I SystemUpdateService: now status is 0 (complete)
09-14 01:03:53.582  1699  4132 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-14 01:03:53.582  1699  4132 I SystemUpdateService: file has been verified
09-14 01:03:53.582  1699  4132 I SystemUpdateService: OTA package size = 12249756
,09-14 01:03:53.587  1699  4132 I SystemUpdateService: showing system update notification
,09-14 01:03:53.597  1699  1699 D SystemUpdateService: onDestroy
,09-14 01:03:53.613   371   871 E Netd    : netlink response contains error (No such file or directory)
,09-14 01:03:53.615   873  1304 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-14 01:03:54.359  4041  4048 E DataBuffer: Internal data leak within a DataBuffer object detected!  Be sure to explicitly call release() on all DataBuffer extending objects when you are done with them. (com.google.android.gms.reminders.model.RemindersBuffer@8b18cf9)
,09-14 01:03:56.046   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-14 01:03:56.057  1873  1873 I Keyboard.Facilitator: onFinishInput()
,09-14 01:03:56.070   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-14 01:03:56.070   873   893 I Adreno  : Build Date                       : 10/20/15
09-14 01:03:56.070   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-14 01:03:56.070   873   893 I Adreno  : Local Branch                     : M14
09-14 01:03:56.070   873   893 I Adreno  : Remote Branch                    : 
09-14 01:03:56.070   873   893 I Adreno  : Remote Branch                    : 
09-14 01:03:56.070   873   893 I Adreno  : Reconstruct Branch               : 
,09-14 01:03:56.107   280   304 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (331 us)
,09-14 01:03:56.360   873   890 I ActivityManager: Start proc 4143:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-14 01:03:56.477  4143  4143 D AdapterServiceConfig: Adding HeadsetService
,09-14 01:03:56.478  4143  4143 D AdapterServiceConfig: Adding A2dpService
09-14 01:03:56.478  4143  4143 D AdapterServiceConfig: Adding HidService
09-14 01:03:56.478  4143  4143 D AdapterServiceConfig: Adding HealthService
09-14 01:03:56.478  4143  4143 D AdapterServiceConfig: Adding PanService
09-14 01:03:56.479  4143  4143 D AdapterServiceConfig: Adding GattService
09-14 01:03:56.479  4143  4143 D AdapterServiceConfig: Adding BluetoothMapService
,09-14 01:03:56.496  4143  4143 D BluetoothAdapterState: make() - Creating AdapterState
,09-14 01:03:56.496   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@79b62a4:true
,09-14 01:03:56.501  4143  4143 I bt_bluedroid: init
,09-14 01:03:56.502  4143  4155 I BluetoothAdapterState: Entering OffState
,09-14 01:03:56.507  4143  4156 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-14 01:03:56.507  4143  4156 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-14 01:03:56.507  4143  4156 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-14 01:03:56.507  4143  4156 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-14 01:03:56.507  4143  4143 I bt_bluedroid: get_profile_interface socket
09-14 01:03:56.510  4143  4143 I bt_bluedroid: get_profile_interface sdp
09-14 01:03:56.522  4143  4154 I bt_bluedroid: config_hci_snoop_log
09-14 01:03:56.523   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-14 01:03:56.524  4143  4159 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-14 01:03:56.531  4143  4159 D BluetoothAdapterProperties: Name is: Nexus 6
,09-14 01:03:56.532  4143  4155 D BluetoothAdapterState: Current state: OFF, message: 0
09-14 01:03:56.532  4143  4155 D BluetoothAdapterProperties: Setting state to 14
09-14 01:03:56.532  4143  4155 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-14 01:03:56.535  4143  4155 D BluetoothBondStateMachine: make
,09-14 01:03:56.536  4143  4160 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-14 01:03:56.540  4143  4155 I BluetoothAdapterState: Entering PendingCommandState
,09-14 01:03:56.541  4143  4143 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-14 01:03:56.542  4143  4143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57c0357
,09-14 01:03:56.543  4143  4143 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-14 01:03:56.543  4143  4143 D BtGatt.GattService: Received start request. Starting profile...
09-14 01:03:56.544  4143  4143 D BtGatt.GattService: start()
09-14 01:03:56.544  4143  4143 I bt_bluedroid: get_profile_interface gatt
,09-14 01:03:56.544  4143  4143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57c0357
,09-14 01:03:56.545  4143  4143 D BtGatt.AdvertiseManager: advertise manager created
,09-14 01:03:56.549  4143  4143 V BluetoothAdapterState: isTurningOff()=false
,09-14 01:03:56.549  4143  4143 V BluetoothAdapterState: isTurningOn()=false
09-14 01:03:56.549  4143  4143 V BluetoothAdapterState: isBleTurningOn()=true
09-14 01:03:56.549  4143  4143 V BluetoothAdapterState: isBleTurningOff()=false
09-14 01:03:56.550  4143  4155 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-14 01:03:56.550  4143  4155 I bt_bluedroid: enable
09-14 01:03:56.550  4143  4156 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-14 01:03:56.551  4143  4156 I bt_hci  : start_up
,09-14 01:03:56.555  4143  4156 I bt_vendor: alloc value 0xb3a5d189
,09-14 01:03:56.556  4143  4156 I bt_vendor: init
09-14 01:03:56.556  4143  4156 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-14 01:03:56.556  4143  4156 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-14 01:03:56.626  4091  4113 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,09-14 01:03:56.662  4143  4156 D bt_hci  : start_up starting async portion
,09-14 01:03:56.662  4143  4163 I bt_hci  : event_finish_startup
,09-14 01:03:56.663  4143  4163 I bt_hci_h4: hal_open
09-14 01:03:56.663  4143  4163 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-14 01:03:56.668  4143  4163 I bt_userial_vendor: device fd = 51 open
,09-14 01:03:56.703  4143  4163 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-14 01:03:56.736  4143  4163 D bt_hwcfg: Chipset BCM4354A2
,09-14 01:03:56.737  4143  4163 D bt_hwcfg: Target name = [BCM4354A2]
09-14 01:03:56.737  4143  4163 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-14 01:03:56.747  3799  3799 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-14 01:03:56.748  3799  3799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-14 01:03:56.789   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-14 01:03:56.798   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-14 01:03:56.804   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
09-14 01:03:56.804   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
09-14 01:03:56.804   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
09-14 01:03:56.804  3799  3799 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f537df3 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@27b97fd, 16908290=android.view.AbsSavedState$1@27b97fd}, android:focusedViewId=100}]}]
09-14 01:03:56.804  3799  3799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-14 01:03:56.810  3799  3799 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-14 01:03:56.813  3799  3799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-14 01:03:57.032   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-14 01:03:57.036   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-14 01:03:57.043   873  1326 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
,09-14 01:03:57.049   873   893 I DreamManagerService: Entering dreamland.
,09-14 01:03:57.050   873   893 I PowerManagerService: Dozing...
,09-14 01:03:57.051   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-14 01:03:57.098   375  1310 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-14 01:03:57.098   375  1310 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-14 01:03:57.104   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,09-14 01:03:57.108   873  1302 E native  : do suspend false
,09-14 01:03:57.128  1936  4170 D NfcService: Discovery configuration equal, not updating.
,09-14 01:03:57.152   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,09-14 01:03:57.158   873  1302 E native  : do suspend true
,09-14 01:03:57.240   375   375 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-14 01:03:57.240   375   375 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-14 01:03:57.341  4143  4163 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-14 01:03:57.342  4143  4163 D bt_hwcfg: Settlement delay -- 100 ms
09-14 01:03:57.342  4143  4163 I bt_hwcfg: Setting fw settlement delay to 100 
,09-14 01:03:57.459  4143  4163 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-14 01:03:57.461  4143  4163 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-14 01:03:57.489  4143  4163 I bt_hwcfg: vendor lib fwcfg completed
,09-14 01:03:57.489  4143  4163 I bt_vendor: firmware callback
,09-14 01:03:57.490  4143  4163 I bt_hci  : firmware_config_callback
,09-14 01:03:57.501  4143  4174 I bt_btu  : btu_task pending for preload complete event
,09-14 01:03:57.501  4143  4174 I bt_btu_task: Bluetooth chip preload is complete
,09-14 01:03:57.502  4143  4174 I bt_btu  : btu_task received preload complete event
,09-14 01:03:57.514  4143  4174 I         : BTE_InitTraceLevels -- TRC_HCI
,09-14 01:03:57.515  4143  4174 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-14 01:03:57.515  4143  4174 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-14 01:03:57.515  4143  4174 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-14 01:03:57.515  4143  4174 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-14 01:03:57.516  4143  4174 I         : BTE_InitTraceLevels -- TRC_A2D
,09-14 01:03:57.517  4143  4174 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-14 01:03:57.518  4143  4174 I         : BTE_InitTraceLevels -- TRC_BTM
09-14 01:03:57.519  4143  4174 I         : BTE_InitTraceLevels -- TRC_GAP
09-14 01:03:57.519  4143  4174 I         : BTE_InitTraceLevels -- TRC_PAN
09-14 01:03:57.521  4143  4174 I         : BTE_InitTraceLevels -- TRC_SDP
09-14 01:03:57.521  4143  4174 I         : BTE_InitTraceLevels -- TRC_GATT
09-14 01:03:57.521  4143  4174 I         : BTE_InitTraceLevels -- TRC_SMP
09-14 01:03:57.521  4143  4174 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-14 01:03:57.522  4143  4174 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-14 01:03:57.661  4143  4174 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39dad9d
,09-14 01:03:57.662  4143  4174 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39dad9d 
,09-14 01:03:57.671  4143  4159 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-14 01:03:57.671  4143  4159 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-14 01:03:57.672  4143  4159 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-14 01:03:57.676  4143  4159 D BluetoothAdapterProperties: Name is: Nexus 6
,09-14 01:03:57.680  4143  4159 D BluetoothAdapterProperties: Scan Mode:20
,09-14 01:03:57.682  4143  4159 D BluetoothAdapterProperties: Discoverable Timeout:120
09-14 01:03:57.683  4143  4159 D bt_hci  : do_postload posting postload work item
,09-14 01:03:57.684  4143  4163 I bt_hci  : event_postload
,09-14 01:03:57.684  4143  4163 I bt_vendor: sco_config_cb
,09-14 01:03:57.684  4143  4163 I bt_hci  : sco_config_callback postload finished.
,09-14 01:03:57.686  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:03:57.687  4143  4159 D bt_bte_conf: Device ID record 1 : primary
,09-14 01:03:57.687  4143  4159 D bt_bte_conf:   vendorId            = 000f
,09-14 01:03:57.687  4143  4159 D bt_bte_conf:   vendorIdSource      = 0001
09-14 01:03:57.687  4143  4159 D bt_bte_conf:   product             = 1200
09-14 01:03:57.688  4143  4159 D bt_bte_conf:   version             = 1436
09-14 01:03:57.688  4143  4159 D bt_bte_conf:   clientExecutableURL = 
,09-14 01:03:57.688  4143  4159 D bt_bte_conf:   serviceDescription  = 
09-14 01:03:57.688  4143  4159 D bt_bte_conf:   documentationURL    = 
09-14 01:03:57.689  4143  4159 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-14 01:03:57.690  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:03:57.690  4143  4156 D bt_stack_manager: event_start_up_stack finished
,09-14 01:03:57.691  4143  4155 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-14 01:03:57.692  4143  4155 D BluetoothAdapterProperties: Setting state to 15
09-14 01:03:57.692  4143  4155 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-14 01:03:57.693  4143  4163 I bt_vendor: low_power_mode_cb
09-14 01:03:57.695  4143  4155 I BluetoothAdapterState: Entering BleOnState
09-14 01:03:57.699  4143  4155 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-14 01:03:57.699  4143  4155 D BluetoothAdapterProperties: Setting state to 11
09-14 01:03:57.699  4143  4155 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-14 01:03:57.704  4143  4143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57c0357
09-14 01:03:57.705  4143  4143 D HeadsetService: Received start request. Starting profile...
,09-14 01:03:57.708  4143  4143 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-14 01:03:57.708  4143  4143 D HeadsetStateMachine: make
,09-14 01:03:57.716  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:03:57.718  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:03:57.719  4143  4155 I BluetoothAdapterState: Entering PendingCommandState
09-14 01:03:57.722  4143  4143 D HeadsetStateMachine: max_hf_connections = 1
09-14 01:03:57.722  4143  4143 I bt_bluedroid: get_profile_interface handsfree
,09-14 01:03:57.723  4143  4159 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-14 01:03:57.723  4143  4159 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-14 01:03:57.726  4143  4143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57c0357
,09-14 01:03:57.726  4143  4143 D A2dpService: Received start request. Starting profile...
,09-14 01:03:57.727  4143  4143 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-14 01:03:57.727  4143  4143 I bt_bluedroid: get_profile_interface avrcp
,09-14 01:03:57.732  4143  4143 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-14 01:03:57.732  4143  4143 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-14 01:03:57.732  4143  4143 D A2dpStateMachine: make
,09-14 01:03:57.734  4143  4143 I bt_bluedroid: get_profile_interface a2dp
,09-14 01:03:57.734  4143  4159 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-14 01:03:57.735  4143  4183 D A2dpStateMachine: Enter Disconnected: -2
,09-14 01:03:57.736  4143  4143 I BluetoothHidServiceJni: classInitNative: succeeds
,09-14 01:03:57.736  4143  4143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57c0357
,09-14 01:03:57.738  3868  3868 D BluetoothInputDevice: Proxy object connected
,09-14 01:03:57.738  4143  4143 D HidService: Received start request. Starting profile...
09-14 01:03:57.738  4143  4143 I bt_bluedroid: get_profile_interface hidhost
09-14 01:03:57.738  4143  4159 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39bc3e5
09-14 01:03:57.738  4143  4159 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-14 01:03:57.738  4143  4143 D HidService: setHidService(): set to: null
09-14 01:03:57.739  3868  3868 D HidProfile: Bluetooth service connected
,09-14 01:03:57.739  4143  4143 I BluetoothHealthServiceJni: classInitNative: succeeds
09-14 01:03:57.739  4143  4143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57c0357
,09-14 01:03:57.740  4143  4143 D HealthService: Received start request. Starting profile...
,09-14 01:03:57.741  4143  4143 I bt_bluedroid: get_profile_interface health
,09-14 01:03:57.741  4143  4143 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-14 01:03:57.742  4143  4143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57c0357
,09-14 01:03:57.743  3868  3868 D BluetoothPan: BluetoothPAN Proxy object connected
,09-14 01:03:57.743  4143  4143 D PanService: Received start request. Starting profile...
09-14 01:03:57.743  4143  4143 D BluetoothPanServiceJni: initializeNative(L110): pan
09-14 01:03:57.743  4143  4143 I bt_bluedroid: get_profile_interface pan
09-14 01:03:57.743  4143  4159 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-14 01:03:57.743  3868  3868 D PanProfile: Bluetooth service connected
,09-14 01:03:57.747  4143  4143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57c0357
,09-14 01:03:57.748  4143  4143 D BluetoothMapService: Received start request. Starting profile...
,09-14 01:03:57.748  3868  3868 D BluetoothMap: Proxy object connected
09-14 01:03:57.748  4143  4143 D BluetoothMapService: start()
09-14 01:03:57.748  3868  3868 D MapProfile: Bluetooth service connected
09-14 01:03:57.748  3868  3868 D BluetoothMap: getConnectedDevices()
,09-14 01:03:57.749  3868  3868 D BluetoothMap: Bluetooth is Not enabled
09-14 01:03:57.750  4143  4143 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-14 01:03:57.750  4143  4143 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-14 01:03:57.750  4143  4143 D BluetoothMapAppObserver: createReceiver()
,09-14 01:03:57.751  4143  4143 D BluetoothMapAppObserver: initObservers()
09-14 01:03:57.751  4143  4143 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-14 01:03:57.758  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 01:03:57.759  4143  4143 V BluetoothAdapterState: isTurningOff()=false
,09-14 01:03:57.759  4143  4143 V BluetoothAdapterState: isTurningOn()=true
09-14 01:03:57.759  4143  4143 V BluetoothAdapterState: isBleTurningOn()=false
09-14 01:03:57.759  4143  4143 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 01:03:57.761  4143  4143 V BluetoothAdapterState: isTurningOff()=false
09-14 01:03:57.761  4143  4143 V BluetoothAdapterState: isTurningOn()=true
,09-14 01:03:57.761  4143  4143 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 01:03:57.761  4143  4143 V BluetoothAdapterState: isBleTurningOff()=false
09-14 01:03:57.761  4143  4143 V BluetoothAdapterState: isTurningOff()=false
,09-14 01:03:57.761  4143  4180 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-14 01:03:57.761  4143  4143 V BluetoothAdapterState: isTurningOn()=true
09-14 01:03:57.761  4143  4143 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 01:03:57.761  4143  4143 V BluetoothAdapterState: isBleTurningOff()=false
09-14 01:03:57.761  4143  4143 V BluetoothAdapterState: isTurningOff()=false
09-14 01:03:57.761  4143  4143 V BluetoothAdapterState: isTurningOn()=true
09-14 01:03:57.761  4143  4143 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 01:03:57.761  4143  4143 V BluetoothAdapterState: isBleTurningOff()=false
09-14 01:03:57.762  4143  4143 V BluetoothAdapterState: isTurningOff()=false
09-14 01:03:57.762  4143  4143 V BluetoothAdapterState: isTurningOn()=true
,09-14 01:03:57.762  4143  4143 V BluetoothAdapterState: isBleTurningOn()=false
09-14 01:03:57.762  4143  4143 V BluetoothAdapterState: isBleTurningOff()=false
09-14 01:03:57.762  4143  4143 V BluetoothAdapterState: isTurningOff()=false
,09-14 01:03:57.762  4143  4143 V BluetoothAdapterState: isTurningOn()=true
09-14 01:03:57.762  4143  4143 V BluetoothAdapterState: isBleTurningOn()=false
09-14 01:03:57.762  4143  4143 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 01:03:57.762  4143  4155 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-14 01:03:57.762  4143  4155 D BluetoothAdapterProperties: ScanMode =  20
09-14 01:03:57.763  4143  4155 D BluetoothAdapterProperties: State =  11
09-14 01:03:57.764  4143  4159 D BluetoothAdapterProperties: Scan Mode:21
,09-14 01:03:57.764  4143  4155 D BluetoothAdapterProperties: Setting state to 12
09-14 01:03:57.765  4143  4155 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-14 01:03:57.765  4143  4159 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-14 01:03:57.765  1357  1386 D BluetoothPan: onBluetoothStateChange on: true
09-14 01:03:57.765  4143  4155 I BluetoothAdapterState: Entering OnState
09-14 01:03:57.767  1357  1357 D BluetoothPan: BluetoothPAN Proxy object connected
09-14 01:03:57.768  1357  1357 D PanProfile: Bluetooth service connected
,09-14 01:03:57.768  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 01:03:57.768  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:57.768  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:57.768  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 01:03:57.768  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 01:03:57.768  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 01:03:57.768  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 01:03:57.768  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 01:03:57.768  3868  3880 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-14 01:03:57.769   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-14 01:03:57.769   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-14 01:03:57.769  1357  3798 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 01:03:57.769  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 01:03:57.770  1357  1376 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-14 01:03:57.772  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 01:03:57.772  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:57.772  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:57.772  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 01:03:57.772  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 01:03:57.772  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 01:03:57.772  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 01:03:57.772  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 01:03:57.774   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-14 01:03:57.774  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 01:03:57.774  1357  1357 D BluetoothA2dp: Proxy object connected
09-14 01:03:57.775  1944  2138 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 01:03:57.776  3868  3879 D BluetoothPan: onBluetoothStateChange on: true
09-14 01:03:57.777  4143  4143 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-14 01:03:57.777  3868  3880 D BluetoothMap: onBluetoothStateChange: up=true
09-14 01:03:57.777  4143  4143 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-14 01:03:57.778   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-14 01:03:57.779  4143  4143 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 01:03:57.781   873   873 D BluetoothA2dp: Proxy object connected
,09-14 01:03:57.781  1357  1386 D BluetoothMap: onBluetoothStateChange: up=true
09-14 01:03:57.782  4143  4143 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 01:03:57.784  1357  1357 D BluetoothMap: Proxy object connected
09-14 01:03:57.784  1357  1357 D MapProfile: Bluetooth service connected
09-14 01:03:57.784  1357  1357 D BluetoothMap: getConnectedDevices()
09-14 01:03:57.784  3868  3879 D BluetoothPbap: onBluetoothStateChange: up=true
,09-14 01:03:57.785  4143  4143 D ObexServerSockets: Succeed to create listening sockets 
,09-14 01:03:57.785  4143  4143 D ObexServerSockets0: startAccept()
09-14 01:03:57.785  4143  4143 D ObexServerSockets0: prepareForNewConnect()
09-14 01:03:57.785  1357  1376 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-14 01:03:57.787  4143  4143 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-14 01:03:57.787  4143  4143 D BluetoothSdpJni: SDP Create record success - handle: 0
09-14 01:03:57.788  1357  1357 D BluetoothInputDevice: Proxy object connected
,09-14 01:03:57.788  1357  1357 D HidProfile: Bluetooth service connected
09-14 01:03:57.788  4143  4189 D ObexServerSockets0: Accepting socket connection...
09-14 01:03:57.788  4143  4190 D ObexServerSockets0: Accepting socket connection...
09-14 01:03:57.789  1357  3798 D BluetoothPbap: onBluetoothStateChange: up=true
,09-14 01:03:57.793   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,09-14 01:03:57.794  4143  4143 D BluetoothMapService: onReceive
,09-14 01:03:57.795  4143  4143 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-14 01:03:57.795  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:03:57.795  4143  4143 D BluetoothMapService: STATE_ON
09-14 01:03:57.796  3868  3868 D LocalBluetoothProfileManager: Adding local A2DP profile
09-14 01:03:57.796  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:03:57.799  3868  3868 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-14 01:03:57.805  3868  3868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-14 01:03:57.807  3868  3868 D BluetoothA2dp: Proxy object connected
,09-14 01:03:57.809  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 01:03:57.817  3868  3868 D DockEventReceiver: finishStartingService: stopping service
,09-14 01:03:57.821  3868  3868 D BluetoothPbap: Proxy object connected
09-14 01:03:57.821  1357  1357 D BluetoothPbap: Proxy object connected
09-14 01:03:57.821  1357  1357 D PbapServerProfile: Bluetooth service connected
09-14 01:03:57.822  3868  3868 D PbapServerProfile: Bluetooth service connected
,09-14 01:03:57.823  4143  4143 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-14 01:03:57.825  4143  4143 D ObexServerSockets0: prepareForNewConnect()
,09-14 01:03:57.827  4143  4194 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 01:03:57.853  4143  4198 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 01:03:57.854  4143  4198 I BtOppRfcommListener: Accept thread started.
,09-14 01:03:57.870   873   873 D BluetoothHeadset: Proxy object connected
,09-14 01:03:57.870   873   873 D BluetoothHeadset: Proxy object connected
,09-14 01:03:57.871  1357  1386 D BluetoothHeadset: Proxy object connected,
09-14 01:03:57.871  1357  1357 D HeadsetProfile: Bluetooth service connected
09-14 01:03:57.871   873   873 D BluetoothHeadset: Proxy object connected
09-14 01:03:57.871  1944  2141 D BluetoothHeadset: Proxy object connected
,09-14 01:03:57.875   873   890 D BluetoothHeadset: Proxy object connected
,09-14 01:03:57.877  1944  1963 D BluetoothHeadset: Proxy object connected
,09-14 01:03:57.902  3868  3880 D BluetoothHeadset: Proxy object connected
,09-14 01:03:57.903  3868  3868 D HeadsetProfile: Bluetooth service connected
,09-14 01:03:58.746  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:03:58.758  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:03:58.762  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:03:58.813  1504  1997 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-14 01:03:58.813  1504  1997 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,09-14 01:03:58.813  1504  1997 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:03:58.813  1504  1997 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:03:58.841  3515  3515 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-14 01:03:58.841  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-14 01:03:58.842  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-14 01:03:59.276   873  1304 D ConnectivityService: handlePromptUnvalidated 101
,09-14 01:03:59.330  4143  4155 D BluetoothAdapterState: Current state: ON, message: 23
,09-14 01:03:59.330  4143  4155 D BluetoothAdapterProperties: Setting state to 13
09-14 01:03:59.331  4143  4155 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-14 01:03:59.333  4143  4155 D BluetoothAdapterProperties: onBluetoothDisable()
,09-14 01:03:59.340  4143  4155 I BluetoothAdapterState: Entering PendingCommandState
,09-14 01:03:59.344  4143  4143 D BluetoothMapService: onReceive
,09-14 01:03:59.344  4143  4143 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-14 01:03:59.344  4143  4143 D BluetoothMapService: STATE_TURNING_OFF
,09-14 01:03:59.345  4143  4143 D BluetoothMapService: MAP Service closeService in
09-14 01:03:59.345  4143  4143 D BluetoothMapMasInstance0: MAP Service shutdown
09-14 01:03:59.345  4143  4143 D ObexServerSockets0: shutdown(block = true)
09-14 01:03:59.346  4143  4143 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-14 01:03:59.346  4143  4143 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-14 01:03:59.346  4143  4177 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-14 01:03:59.347  4143  4190 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-14 01:03:59.348  4143  4189 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-14 01:03:59.349  4143  4159 D BluetoothAdapterProperties: Scan Mode:20
09-14 01:03:59.350  4143  4155 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-14 01:03:59.356  4143  4143 I BtOppRfcommListener: stopping Accept Thread
,09-14 01:03:59.357  4143  4198 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-14 01:03:59.357  4143  4198 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-14 01:03:59.363  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-14 01:03:59.363  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 01:03:59.363  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:59.363  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:59.363  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 01:03:59.363  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 01:03:59.363  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 01:03:59.363  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 01:03:59.363  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 01:03:59.367  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 01:03:59.367  4143  4143 D HeadsetService: Received stop request...Stopping profile...
09-14 01:03:59.367  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-14 01:03:59.369  3868  3879 D BluetoothHeadset: Proxy object disconnected
,09-14 01:03:59.370   873   873 D BluetoothHeadset: Proxy object disconnected
09-14 01:03:59.370   873   873 D BluetoothHeadset: Proxy object disconnected
09-14 01:03:59.370  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 01:03:59.371  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 01:03:59.371  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:03:59.371  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:03:59.371  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 01:03:59.371  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-14 01:03:59.371  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 01:03:59.371  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 01:03:59.371  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-14 01:03:59.371  1357  1376 D BluetoothHeadset: Proxy object disconnected
,09-14 01:03:59.371   873   873 D BluetoothHeadset: Proxy object disconnected
,09-14 01:03:59.371  1944  1960 D BluetoothHeadset: Proxy object disconnected
09-14 01:03:59.372  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-14 01:03:59.372  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-14 01:03:59.372  4143  4143 V BluetoothAdapterState: isTurningOff()=true
09-14 01:03:59.372  4143  4143 V BluetoothAdapterState: isTurningOn()=false,
09-14 01:03:59.372  4143  4143 V BluetoothAdapterState: isBleTurningOn()=false
09-14 01:03:59.372  4143  4143 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 01:03:59.373  4143  4143 D A2dpService: Received stop request...Stopping profile...
09-14 01:03:59.374  4143  4183 D A2dpStateMachine: Exit Disconnected: -1
09-14 01:03:59.374  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:03:59.371  3868  3868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-14 01:03:59.375  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:03:59.376   873   873 D BluetoothA2dp: Proxy object disconnected
,09-14 01:03:59.378  3868  3868 D HeadsetProfile: Bluetooth service disconnected
09-14 01:03:59.379  3868  3868 D BluetoothA2dp: Proxy object disconnected
,09-14 01:03:59.379  4143  4143 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-14 01:03:59.379  4143  4143 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-14 01:03:59.379  4143  4159 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-14 01:03:59.380  4143  4174 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 01:03:59.380  4143  4174 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-14 01:03:59.380  4143  4174 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 01:03:59.380  4143  4159 E bt_btif : btif_hf_upstreams_evt: Invalid index 65534
,09-14 01:03:59.381  4143  4143 D HidService: Received stop request...Stopping profile...
,09-14 01:03:59.381  4143  4143 D HidService: Stopping Bluetooth HidService
,09-14 01:03:59.382  4143  4143 D HealthService: Received stop request...Stopping profile...,
,09-14 01:03:59.384  4143  4143 D PanService: Received stop request...Stopping profile...
,09-14 01:03:59.386  4143  4143 D BluetoothMapService: Received stop request...Stopping profile...
,09-14 01:03:59.386  1357  1357 D HeadsetProfile: Bluetooth service disconnected
09-14 01:03:59.386  4143  4143 D BluetoothMapService: stop()
,09-14 01:03:59.386  1357  1357 D BluetoothA2dp: Proxy object disconnected
,09-14 01:03:59.386  1357  1357 D BluetoothInputDevice: Proxy object disconnected
,09-14 01:03:59.386  1357  1357 D HidProfile: Bluetooth service disconnected
,09-14 01:03:59.387  1357  1357 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-14 01:03:59.387  1357  1357 D PanProfile: Bluetooth service disconnected
,09-14 01:03:59.387  4143  4143 D BluetoothMapAppObserver: deinitObservers()
,09-14 01:03:59.387  4143  4143 D BluetoothMapAppObserver: removeReceiver()
,09-14 01:03:59.388  1357  1357 D BluetoothMap: Proxy object disconnected
,09-14 01:03:59.388  1357  1357 D MapProfile: Bluetooth service disconnected
,09-14 01:03:59.389  4143  4143 V BluetoothAdapterState: isTurningOff()=true
09-14 01:03:59.389  4143  4143 V BluetoothAdapterState: isTurningOn()=false
,09-14 01:03:59.389  4143  4143 V BluetoothAdapterState: isBleTurningOn()=false
09-14 01:03:59.389  4143  4143 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 01:03:59.389  3868  3868 D DockEventReceiver: finishStartingService: stopping service
09-14 01:03:59.390  4143  4174 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 01:03:59.391  4143  4174 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-14 01:03:59.391  4143  4174 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-14 01:03:59.391  4143  4174 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 01:03:59.391  4143  4174 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-14 01:03:59.391  4143  4174 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-14 01:03:59.391  4143  4159 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-14 01:03:59.392  4143  4143 V BluetoothAdapterState: isTurningOff()=true,
09-14 01:03:59.392  4143  4143 V BluetoothAdapterState: isTurningOn()=false
09-14 01:03:59.392  4143  4143 V BluetoothAdapterState: isBleTurningOn()=false
09-14 01:03:59.392  4143  4143 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 01:03:59.393  4143  4143 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-14 01:03:59.393  4143  4159 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-14 01:03:59.393  3868  3868 D BluetoothInputDevice: Proxy object disconnected
09-14 01:03:59.394  3868  3868 D HidProfile: Bluetooth service disconnected
,09-14 01:03:59.394  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-14 01:03:59.394  3868  3868 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-14 01:03:59.394  3868  3868 D PanProfile: Bluetooth service disconnected
,09-14 01:03:59.394  4143  4143 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-14 01:03:59.394  3868  3868 D BluetoothMap: Proxy object disconnected
09-14 01:03:59.394  3868  3868 D MapProfile: Bluetooth service disconnected
,09-14 01:03:59.394  4143  4143 V BluetoothAdapterState: isTurningOff()=true
09-14 01:03:59.395  4143  4143 V BluetoothAdapterState: isTurningOn()=false
09-14 01:03:59.395  4143  4143 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 01:03:59.395  4143  4143 V BluetoothAdapterState: isBleTurningOff()=false
09-14 01:03:59.395  4143  4143 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-14 01:03:59.395  4143  4159 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-14 01:03:59.396  4143  4143 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-14 01:03:59.396  4143  4143 V BluetoothAdapterState: isTurningOff()=true
09-14 01:03:59.396  4143  4143 V BluetoothAdapterState: isTurningOn()=false
,09-14 01:03:59.397  4143  4143 V BluetoothAdapterState: isBleTurningOn()=false
09-14 01:03:59.397  4143  4143 V BluetoothAdapterState: isBleTurningOff()=false
09-14 01:03:59.397  4143  4143 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-14 01:03:59.397  4143  4143 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-14 01:03:59.398  4143  4143 D BluetoothMapService: MAP Service closeService in
09-14 01:03:59.398  4143  4143 V BluetoothAdapterState: isTurningOff()=true
09-14 01:03:59.398  4143  4143 V BluetoothAdapterState: isTurningOn()=false
09-14 01:03:59.398  4143  4143 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 01:03:59.398  4143  4143 V BluetoothAdapterState: isBleTurningOff()=false
09-14 01:03:59.399  4143  4155 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-14 01:03:59.399  4143  4155 D BluetoothAdapterProperties: Setting state to 15
09-14 01:03:59.399  4143  4155 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-14 01:03:59.400  4143  4155 I BluetoothAdapterState: Entering BleOnState
09-14 01:03:59.400  1357  3798 D BluetoothPan: onBluetoothStateChange on: false
09-14 01:03:59.401  4143  4143 D BluetoothMapService: cleanup()
09-14 01:03:59.401  4143  4143 D BluetoothMapService: MAP Service closeService in
,09-14 01:03:59.401  3868  3880 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-14 01:03:59.401   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 01:03:59.402  3868  3879 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 01:03:59.402   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-14 01:03:59.402  1357  1386 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 01:03:59.402  1357  2073 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 01:03:59.403  1357  1357 D BluetoothPbap: Proxy object disconnected
09-14 01:03:59.403  1357  1357 D PbapServerProfile: Bluetooth service disconnected
,09-14 01:03:59.403  3868  3879 D BluetoothA2dp: onBluetoothStateChange: up=false
09-14 01:03:59.403   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 01:03:59.404  1944  2138 D BluetoothHeadset: onBluetoothStateChange: up=false
09-14 01:03:59.404  3868  3880 D BluetoothPan: onBluetoothStateChange on: false
,09-14 01:03:59.404  3868  3868 D BluetoothPbap: Proxy object disconnected
09-14 01:03:59.404  3868  3868 D PbapServerProfile: Bluetooth service disconnected
09-14 01:03:59.405  3868  3879 D BluetoothMap: onBluetoothStateChange: up=false
09-14 01:03:59.406   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-14 01:03:59.406  1357  3798 D BluetoothMap: onBluetoothStateChange: up=false
09-14 01:03:59.406  3868  3880 D BluetoothPbap: onBluetoothStateChange: up=false
09-14 01:03:59.407  1357  1376 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-14 01:03:59.409  1357  2073 D BluetoothPbap: onBluetoothStateChange: up=false
,09-14 01:03:59.410  4143  4155 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-14 01:03:59.410  4143  4155 D BluetoothAdapterProperties: Setting state to 16
09-14 01:03:59.410  4143  4155 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-14 01:03:59.411  4143  4155 D BluetoothAdapterProperties: onBleDisable
,09-14 01:03:59.411  4143  4155 I BluetoothAdapterState: Entering PendingCommandState
09-14 01:03:59.412  4143  4156 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-14 01:03:59.413  4143  4174 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-14 01:03:59.413  4143  4174 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-14 01:03:59.414  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:03:59.416  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:03:59.417  4143  4159 D BluetoothAdapterProperties: Scan Mode:20
,09-14 01:03:59.418  3868  3868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-14 01:03:59.420  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:03:59.421  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:03:59.423  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 01:03:59.424  3868  3868 D DockEventReceiver: finishStartingService: stopping service
,09-14 01:03:59.614  4143  4159 I bt_hci  : shut_down
,09-14 01:03:59.616  4143  4163 D bt_hwcfg: hw_epilog_process
,09-14 01:03:59.618  4143  4163 I bt_vendor: low_power_mode_cb
,09-14 01:03:59.645  4143  4163 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-14 01:03:59.645  4143  4163 I bt_vendor: epilog_cb
09-14 01:03:59.645  4143  4163 I bt_hci  : epilog_finished_callback
,09-14 01:03:59.652  4143  4159 I bt_hci_h4: hal_close
,09-14 01:03:59.654  4143  4159 I bt_userial_vendor: device fd = 51 close
,09-14 01:03:59.803  4143  4156 D bt_stack_manager: event_shut_down_stack finished.
,09-14 01:03:59.804  4143  4155 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-14 01:03:59.810  4143  4143 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-14 01:03:59.810  4143  4155 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-14 01:03:59.811  4143  4143 D BtGatt.GattService: Received stop request...Stopping profile...
,09-14 01:03:59.812  4143  4143 D BtGatt.GattService: stop()
,09-14 01:03:59.812  4143  4143 D BtGatt.AdvertiseManager: advertise clients cleared
,09-14 01:03:59.815  4143  4143 V BluetoothAdapterState: isTurningOff()=false
,09-14 01:03:59.815  4143  4143 V BluetoothAdapterState: isTurningOn()=false,
,09-14 01:03:59.816  4143  4143 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 01:03:59.816  4143  4143 V BluetoothAdapterState: isBleTurningOff()=true
,09-14 01:03:59.816  4143  4155 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-14 01:03:59.817  4143  4155 D BluetoothAdapterProperties: Setting state to 10
,09-14 01:03:59.817  4143  4155 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-14 01:03:59.818  4143  4155 I BluetoothAdapterState: Entering OffState
,09-14 01:03:59.820   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-14 01:03:59.832  4143  4143 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-14 01:03:59.834  4143  4143 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-14 01:03:59.834  4143  4143 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-14 01:03:59.834  4143  4156 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-14 01:03:59.838  4143  4156 D bt_stack_manager: event_clean_up_stack finished.,
,09-14 01:03:59.843  4143  4143 I art     : System.exit called, status: 0
,09-14 01:03:59.843  4143  4143 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-14 01:03:59.900   873  2132 I ActivityManager: Process com.android.bluetooth (pid 4143) has died
,09-14 01:04:01.724  3515  3526 D Finsky  : [269] ContentFiltersService$1.getContentFiltersAndIntent: Received content filters request from com.google.android.apps.books
,09-14 01:04:01.737  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:04:01.792  1504  2211 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-14 01:04:01.793  1504  2211 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
,09-14 01:04:01.793  1504  2211 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-14 01:04:01.794  1504  2211 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:04:01.846  3515  3526 D Finsky  : [269] DfeContentFilters.logException: Unable to retrieve ContentFilterSettingsResponse: AuthFailureError
,09-14 01:04:02.327  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 01:04:02.327  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 01:04:02.328  1887  2652 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-14 01:04:05.336  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-14 01:04:05.337  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@19cfcf2 added. We now have 6 listener(s)
09-14 01:04:05.337  3799  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 01:04:05.342  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 01:04:05.343  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a159f43 added. We now have 7 listener(s)
09-14 01:04:05.343  3799  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 01:04:05.345  3799  3847 I System.out: IsBluetoothEnabled
,09-14 01:04:05.357  3799  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:04:05.394   873   890 I ActivityManager: Start proc 4212:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-14 01:04:05.501  4212  4212 D AdapterServiceConfig: Adding HeadsetService
,09-14 01:04:05.502  4212  4212 D AdapterServiceConfig: Adding A2dpService
,09-14 01:04:05.502  4212  4212 D AdapterServiceConfig: Adding HidService
09-14 01:04:05.502  4212  4212 D AdapterServiceConfig: Adding HealthService
09-14 01:04:05.502  4212  4212 D AdapterServiceConfig: Adding PanService
09-14 01:04:05.502  4212  4212 D AdapterServiceConfig: Adding GattService
09-14 01:04:05.502  4212  4212 D AdapterServiceConfig: Adding BluetoothMapService
,09-14 01:04:05.515   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b7322e:true
,09-14 01:04:05.515  4212  4212 D BluetoothAdapterState: make() - Creating AdapterState
,09-14 01:04:05.520  4212  4212 I bt_bluedroid: init
,09-14 01:04:05.521  4212  4224 I BluetoothAdapterState: Entering OffState
,09-14 01:04:05.527  4212  4225 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-14 01:04:05.527  4212  4225 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-14 01:04:05.527  4212  4225 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-14 01:04:05.528  4212  4225 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-14 01:04:05.529  4212  4212 I bt_bluedroid: get_profile_interface socket
,09-14 01:04:05.531  4212  4212 I bt_bluedroid: get_profile_interface sdp
09-14 01:04:05.532  4212  4228 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-14 01:04:05.533  4212  4228 D BluetoothAdapterProperties: Name is: Nexus 6
09-14 01:04:05.535  4212  4223 I bt_bluedroid: config_hci_snoop_log
,09-14 01:04:05.538   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-14 01:04:05.547  4212  4224 D BluetoothAdapterState: Current state: OFF, message: 0
,09-14 01:04:05.548  4212  4224 D BluetoothAdapterProperties: Setting state to 14
09-14 01:04:05.548  4212  4224 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-14 01:04:05.552  4212  4224 D BluetoothBondStateMachine: make
,09-14 01:04:05.557  4212  4229 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-14 01:04:05.564  4212  4224 I BluetoothAdapterState: Entering PendingCommandState
,09-14 01:04:05.566  4212  4212 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-14 01:04:05.568  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57c0357
,09-14 01:04:05.569  4212  4212 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-14 01:04:05.569  4212  4212 D BtGatt.GattService: Received start request. Starting profile...
09-14 01:04:05.570  4212  4212 D BtGatt.GattService: start()
09-14 01:04:05.570  4212  4212 I bt_bluedroid: get_profile_interface gatt
,09-14 01:04:05.570  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57c0357
09-14 01:04:05.570  4212  4212 D BtGatt.AdvertiseManager: advertise manager created
,09-14 01:04:05.579  4212  4212 V BluetoothAdapterState: isTurningOff()=false
,09-14 01:04:05.579  4212  4212 V BluetoothAdapterState: isTurningOn()=false
,09-14 01:04:05.579  4212  4212 V BluetoothAdapterState: isBleTurningOn()=true
,09-14 01:04:05.579  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
09-14 01:04:05.580  4212  4224 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-14 01:04:05.581  4212  4224 I bt_bluedroid: enable
,09-14 01:04:05.581  4212  4225 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-14 01:04:05.582  4212  4225 I bt_hci  : start_up
,09-14 01:04:05.601  4212  4225 I bt_vendor: alloc value 0xb3a5d189
09-14 01:04:05.601  4212  4225 I bt_vendor: init
,09-14 01:04:05.601  4212  4225 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-14 01:04:05.602  4212  4225 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-14 01:04:05.712  4212  4225 D bt_hci  : start_up starting async portion
,09-14 01:04:05.712  4212  4232 I bt_hci  : event_finish_startup
09-14 01:04:05.713  4212  4232 I bt_hci_h4: hal_open
09-14 01:04:05.713  4212  4232 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-14 01:04:05.724  4212  4232 I bt_userial_vendor: device fd = 51 open
,09-14 01:04:05.754  4212  4232 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-14 01:04:05.785  4212  4232 D bt_hwcfg: Chipset BCM4354A2
,09-14 01:04:05.786  4212  4232 D bt_hwcfg: Target name = [BCM4354A2]
09-14 01:04:05.787  4212  4232 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-14 01:04:06.451  4212  4232 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-14 01:04:06.452  4212  4232 D bt_hwcfg: Settlement delay -- 100 ms
09-14 01:04:06.452  4212  4232 I bt_hwcfg: Setting fw settlement delay to 100 
,09-14 01:04:06.569  4212  4232 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-14 01:04:06.571  4212  4232 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-14 01:04:06.600  4212  4232 I bt_hwcfg: vendor lib fwcfg completed
,09-14 01:04:06.600  4212  4232 I bt_vendor: firmware callback
,09-14 01:04:06.600  4212  4232 I bt_hci  : firmware_config_callback
,09-14 01:04:06.617  4212  4234 I bt_btu  : btu_task pending for preload complete event
,09-14 01:04:06.618  4212  4234 I bt_btu_task: Bluetooth chip preload is complete
,09-14 01:04:06.618  4212  4234 I bt_btu  : btu_task received preload complete event
,09-14 01:04:06.625  4212  4234 I         : BTE_InitTraceLevels -- TRC_HCI
,09-14 01:04:06.626  4212  4234 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-14 01:04:06.626  4212  4234 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-14 01:04:06.626  4212  4234 I         : BTE_InitTraceLevels -- TRC_AVDT
09-14 01:04:06.626  4212  4234 I         : BTE_InitTraceLevels -- TRC_AVRC
09-14 01:04:06.627  4212  4234 I         : BTE_InitTraceLevels -- TRC_A2D
09-14 01:04:06.627  4212  4234 I         : BTE_InitTraceLevels -- TRC_BNEP
09-14 01:04:06.627  4212  4234 I         : BTE_InitTraceLevels -- TRC_BTM
,09-14 01:04:06.627  4212  4234 I         : BTE_InitTraceLevels -- TRC_GAP
09-14 01:04:06.627  4212  4234 I         : BTE_InitTraceLevels -- TRC_PAN
09-14 01:04:06.628  4212  4234 I         : BTE_InitTraceLevels -- TRC_SDP
09-14 01:04:06.628  4212  4234 I         : BTE_InitTraceLevels -- TRC_GATT
09-14 01:04:06.628  4212  4234 I         : BTE_InitTraceLevels -- TRC_SMP
09-14 01:04:06.628  4212  4234 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-14 01:04:06.628  4212  4234 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-14 01:04:06.768  4212  4234 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39dad9d
,09-14 01:04:06.769  4212  4234 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39dad9d 
,09-14 01:04:06.787  4212  4228 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-14 01:04:06.788  4212  4228 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-14 01:04:06.789  4212  4228 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-14 01:04:06.792  4212  4228 D BluetoothAdapterProperties: Name is: Nexus 6
,09-14 01:04:06.795  4212  4228 D BluetoothAdapterProperties: Scan Mode:20
,09-14 01:04:06.795  4212  4228 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-14 01:04:06.795  4212  4228 D bt_hci  : do_postload posting postload work item
,09-14 01:04:06.796  4212  4232 I bt_hci  : event_postload
,09-14 01:04:06.796  4212  4232 I bt_vendor: sco_config_cb
09-14 01:04:06.796  4212  4232 I bt_hci  : sco_config_callback postload finished.
09-14 01:04:06.800  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:04:06.802  4212  4228 D bt_bte_conf: Device ID record 1 : primary
09-14 01:04:06.802  4212  4228 D bt_bte_conf:   vendorId            = 000f
09-14 01:04:06.803  4212  4228 D bt_bte_conf:   vendorIdSource      = 0001
09-14 01:04:06.803  4212  4228 D bt_bte_conf:   product             = 1200
09-14 01:04:06.803  4212  4228 D bt_bte_conf:   version             = 1436
09-14 01:04:06.803  4212  4228 D bt_bte_conf:   clientExecutableURL = 
09-14 01:04:06.804  4212  4228 D bt_bte_conf:   serviceDescription  = 
,09-14 01:04:06.804  4212  4228 D bt_bte_conf:   documentationURL    = 
09-14 01:04:06.804  4212  4228 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-14 01:04:06.804  4212  4232 I bt_vendor: low_power_mode_cb
,09-14 01:04:06.804  4212  4225 D bt_stack_manager: event_start_up_stack finished
09-14 01:04:06.805  4212  4224 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-14 01:04:06.806  4212  4224 D BluetoothAdapterProperties: Setting state to 15
,09-14 01:04:06.806  4212  4224 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-14 01:04:06.808  4212  4224 I BluetoothAdapterState: Entering BleOnState
09-14 01:04:06.815  4212  4224 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-14 01:04:06.815  4212  4224 D BluetoothAdapterProperties: Setting state to 11
09-14 01:04:06.815  4212  4224 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-14 01:04:06.825  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57c0357
,09-14 01:04:06.827  4212  4212 D HeadsetService: Received start request. Starting profile...
,09-14 01:04:06.831  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:04:06.835  4212  4212 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-14 01:04:06.835  4212  4212 D HeadsetStateMachine: make
,09-14 01:04:06.843  4212  4224 I BluetoothAdapterState: Entering PendingCommandState
,09-14 01:04:06.846  4212  4212 D HeadsetStateMachine: max_hf_connections = 1
09-14 01:04:06.847  4212  4212 I bt_bluedroid: get_profile_interface handsfree
,09-14 01:04:06.847  4212  4228 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-14 01:04:06.847  4212  4228 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-14 01:04:06.851  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57c0357
,09-14 01:04:06.852  4212  4212 D A2dpService: Received start request. Starting profile...
09-14 01:04:06.852  4212  4212 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-14 01:04:06.853  4212  4212 I bt_bluedroid: get_profile_interface avrcp
,09-14 01:04:06.859  4212  4212 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-14 01:04:06.860  4212  4212 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-14 01:04:06.860  4212  4212 D A2dpStateMachine: make
,09-14 01:04:06.861  4212  4212 I bt_bluedroid: get_profile_interface a2dp
09-14 01:04:06.861  4212  4228 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-14 01:04:06.864  4212  4243 D A2dpStateMachine: Enter Disconnected: -2
09-14 01:04:06.864  4212  4212 I BluetoothHidServiceJni: classInitNative: succeeds
,09-14 01:04:06.865  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57c0357
09-14 01:04:06.866  4212  4212 D HidService: Received start request. Starting profile...
09-14 01:04:06.866  4212  4212 I bt_bluedroid: get_profile_interface hidhost
09-14 01:04:06.866  4212  4212 D HidService: setHidService(): set to: null
09-14 01:04:06.867  4212  4228 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39bc3e5
,09-14 01:04:06.867  4212  4228 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-14 01:04:06.867  4212  4212 I BluetoothHealthServiceJni: classInitNative: succeeds
09-14 01:04:06.868  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57c0357
,09-14 01:04:06.868  4212  4212 D HealthService: Received start request. Starting profile...
,09-14 01:04:06.870  4212  4212 I bt_bluedroid: get_profile_interface health
,09-14 01:04:06.870  4212  4212 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-14 01:04:06.871  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57c0357
,09-14 01:04:06.872  4212  4212 D PanService: Received start request. Starting profile...
09-14 01:04:06.872  4212  4212 D BluetoothPanServiceJni: initializeNative(L110): pan
09-14 01:04:06.872  4212  4212 I bt_bluedroid: get_profile_interface pan
,09-14 01:04:06.873  4212  4228 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-14 01:04:06.880  4212  4212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57c0357
,09-14 01:04:06.881  4212  4212 D BluetoothMapService: Received start request. Starting profile...
,09-14 01:04:06.881  4212  4212 D BluetoothMapService: start()
,09-14 01:04:06.884  4212  4212 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-14 01:04:06.885  4212  4212 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-14 01:04:06.885  4212  4212 D BluetoothMapAppObserver: createReceiver()
,09-14 01:04:06.886  4212  4212 D BluetoothMapAppObserver: initObservers()
,09-14 01:04:06.887  4212  4212 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-14 01:04:06.895  4212  4212 V BluetoothAdapterState: isTurningOff()=false
09-14 01:04:06.895  4212  4212 V BluetoothAdapterState: isTurningOn()=true
,09-14 01:04:06.895  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
09-14 01:04:06.895  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
09-14 01:04:06.895  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 01:04:06.897  4212  4241 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-14 01:04:06.897  4212  4212 V BluetoothAdapterState: isTurningOff()=false
,09-14 01:04:06.897  4212  4212 V BluetoothAdapterState: isTurningOn()=true
,09-14 01:04:06.897  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
09-14 01:04:06.897  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
09-14 01:04:06.897  4212  4212 V BluetoothAdapterState: isTurningOff()=false
09-14 01:04:06.897  4212  4212 V BluetoothAdapterState: isTurningOn()=true
09-14 01:04:06.897  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
09-14 01:04:06.897  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 01:04:06.897  4212  4212 V BluetoothAdapterState: isTurningOff()=false
09-14 01:04:06.898  4212  4212 V BluetoothAdapterState: isTurningOn()=true
09-14 01:04:06.898  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
09-14 01:04:06.898  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
,09-14 01:04:06.898  4212  4212 V BluetoothAdapterState: isTurningOff()=false
09-14 01:04:06.898  4212  4212 V BluetoothAdapterState: isTurningOn()=true
09-14 01:04:06.898  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
,09-14 01:04:06.898  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
09-14 01:04:06.898  4212  4212 V BluetoothAdapterState: isTurningOff()=false
,09-14 01:04:06.898  4212  4212 V BluetoothAdapterState: isTurningOn()=true
,09-14 01:04:06.899  4212  4212 V BluetoothAdapterState: isBleTurningOn()=false
09-14 01:04:06.899  4212  4212 V BluetoothAdapterState: isBleTurningOff()=false
09-14 01:04:06.899  4212  4224 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-14 01:04:06.899  4212  4224 D BluetoothAdapterProperties: ScanMode =  20
09-14 01:04:06.899  4212  4224 D BluetoothAdapterProperties: State =  11
,09-14 01:04:06.902  4212  4228 D BluetoothAdapterProperties: Scan Mode:21
09-14 01:04:06.902  4212  4228 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-14 01:04:06.903  4212  4224 D BluetoothAdapterProperties: Setting state to 12
09-14 01:04:06.903  4212  4224 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-14 01:04:06.903  4212  4224 I BluetoothAdapterState: Entering OnState
09-14 01:04:06.903  1357  1376 D BluetoothPan: onBluetoothStateChange on: true
09-14 01:04:06.907  3868  3880 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-14 01:04:06.908  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 01:04:06.908  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:04:06.908  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:04:06.908  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 01:04:06.908  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 01:04:06.908  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 01:04:06.908  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 01:04:06.908  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 01:04:06.908  1357  1357 D BluetoothPan: BluetoothPAN Proxy object connected
09-14 01:04:06.908  1357  1357 D PanProfile: Bluetooth service connected
09-14 01:04:06.909   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 01:04:06.910  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 01:04:06.910  3868  3879 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 01:04:06.911   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-14 01:04:06.911  1357  1386 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 01:04:06.911  3868  3868 D BluetoothInputDevice: Proxy object connected
09-14 01:04:06.912  1357  3798 D BluetoothA2dp: onBluetoothStateChange: up=true
09-14 01:04:06.912  3868  3868 D HidProfile: Bluetooth service connected
09-14 01:04:06.913  4212  4212 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-14 01:04:06.914  3868  3880 D BluetoothA2dp: onBluetoothStateChange: up=true
09-14 01:04:06.914  4212  4212 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-14 01:04:06.916  4212  4212 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 01:04:06.917   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 01:04:06.917  1944  1963 D BluetoothHeadset: onBluetoothStateChange: up=true
09-14 01:04:06.918  4212  4212 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-14 01:04:06.919  3868  4203 D BluetoothPan: onBluetoothStateChange on: true
09-14 01:04:06.920  4212  4212 D ObexServerSockets: Succeed to create listening sockets 
09-14 01:04:06.920  4212  4212 D ObexServerSockets0: startAccept()
,09-14 01:04:06.920  4212  4212 D ObexServerSockets0: prepareForNewConnect()
09-14 01:04:06.922  4212  4212 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-14 01:04:06.922  4212  4212 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-14 01:04:06.923  3868  3880 D BluetoothMap: onBluetoothStateChange: up=true
,09-14 01:04:06.923  4212  4248 D ObexServerSockets0: Accepting socket connection...
09-14 01:04:06.924  1357  1357 D BluetoothA2dp: Proxy object connected
,09-14 01:04:06.925  3868  3868 D BluetoothPan: BluetoothPAN Proxy object connected
,09-14 01:04:06.925  3868  3868 D PanProfile: Bluetooth service connected
,09-14 01:04:06.925  3868  3868 D BluetoothA2dp: Proxy object connected
,09-14 01:04:06.926   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-14 01:04:06.926   873   873 D BluetoothA2dp: Proxy object connected
09-14 01:04:06.926  1357  2073 D BluetoothMap: onBluetoothStateChange: up=true
,09-14 01:04:06.927  4212  4249 D ObexServerSockets0: Accepting socket connection...
,09-14 01:04:06.928  3868  3868 D BluetoothMap: Proxy object connected,
,09-14 01:04:06.929  3868  3868 D MapProfile: Bluetooth service connected
,09-14 01:04:06.929  3868  3868 D BluetoothMap: getConnectedDevices()
09-14 01:04:06.931  1357  1357 D BluetoothMap: Proxy object connected
,09-14 01:04:06.931  1357  1357 D MapProfile: Bluetooth service connected
,09-14 01:04:06.931  1357  1357 D BluetoothMap: getConnectedDevices()
09-14 01:04:06.931  3868  3879 D BluetoothPbap: onBluetoothStateChange: up=true
,09-14 01:04:06.935  1357  3798 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-14 01:04:06.938  1357  1357 D BluetoothInputDevice: Proxy object connected
,09-14 01:04:06.938  1357  1357 D HidProfile: Bluetooth service connected
09-14 01:04:06.938  1357  1386 D BluetoothPbap: onBluetoothStateChange: up=true
,09-14 01:04:06.944   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
09-14 01:04:06.945  4212  4212 D BluetoothMapService: onReceive
09-14 01:04:06.946  4212  4212 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-14 01:04:06.946  4212  4212 D BluetoothMapService: STATE_ON
09-14 01:04:06.946  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:04:06.950  3868  3868 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-14 01:04:06.956  3868  3868 D DockEventReceiver: finishStartingService: stopping service
,09-14 01:04:06.957  1504  1504 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-14 01:04:06.965  3868  3868 D BluetoothPbap: Proxy object connected
,09-14 01:04:06.965  3868  3868 D PbapServerProfile: Bluetooth service connected
,09-14 01:04:06.972  1357  1357 D BluetoothPbap: Proxy object connected
,09-14 01:04:06.973  1357  1357 D PbapServerProfile: Bluetooth service connected
,09-14 01:04:06.980  4212  4212 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-14 01:04:06.980  4212  4212 D ObexServerSockets0: prepareForNewConnect()
,09-14 01:04:06.982  4212  4254 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 01:04:06.999  4212  4258 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-14 01:04:07.001  4212  4258 I BtOppRfcommListener: Accept thread started.
,09-14 01:04:07.011  3868  3880 D BluetoothHeadset: Proxy object connected
,09-14 01:04:07.011   873   890 D BluetoothHeadset: Proxy object connected,
,09-14 01:04:07.012  3868  3868 D HeadsetProfile: Bluetooth service connected
,09-14 01:04:07.012  1357  1376 D BluetoothHeadset: Proxy object connected
09-14 01:04:07.012  1357  1357 D HeadsetProfile: Bluetooth service connected
09-14 01:04:07.012   873   873 D BluetoothHeadset: Proxy object connected,
09-14 01:04:07.012   873   873 D BluetoothHeadset: Proxy object connected
09-14 01:04:07.012  1357  2073 D BluetoothHeadset: Proxy object connected
09-14 01:04:07.012   873   873 D BluetoothHeadset: Proxy object connected
,09-14 01:04:07.013  1944  1960 D BluetoothHeadset: Proxy object connected
09-14 01:04:07.014  1357  1357 D HeadsetProfile: Bluetooth service connected
09-14 01:04:07.017   873   890 D BluetoothHeadset: Proxy object connected
,09-14 01:04:07.019  1944  2138 D BluetoothHeadset: Proxy object connected
,09-14 01:04:07.380  3799  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 01:04:07.380  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:04:07.380  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:04:07.380  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-14 01:04:07.380  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 01:04:07.380  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 01:04:07.380  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 01:04:07.380  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 01:04:07.387  3799  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-14 01:04:07.390  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 01:04:07.391  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@28d69c0 added. We now have 8 listener(s)
09-14 01:04:07.391  3799  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 01:04:07.396   873  2131 D WifiService: setWifiEnabled: false pid=3799, uid=10000
,09-14 01:04:07.397   873  2131 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 01:04:07.410  3799  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:04:07.411   873  1365 D WifiService: setWifiEnabled: true pid=3799, uid=10000
,09-14 01:04:07.411   873  1365 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-14 01:04:07.433   873  1302 D WifiConfigStore: Loading config and enabling all networks 
,09-14 01:04:07.441  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 01:04:07.441  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:04:07.441  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:04:07.441  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:04:07.441  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 01:04:07.441  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 01:04:07.441  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 01:04:07.441  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 01:04:07.447  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 01:04:07.471   873  1302 D WifiConfigStore: loaded 0 passpoint configs
,09-14 01:04:07.472   873  1302 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-14 01:04:07.474   873  1302 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-14 01:04:07.475   873  1302 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-14 01:04:07.476   873  1302 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-14 01:04:07.476   873  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-14 01:04:07.476   873  1302 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK,
,09-14 01:04:07.498   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-14 01:04:07.499   371   871 D CommandListener: Setting iface cfg
,09-14 01:04:07.500   873  1300 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
09-14 01:04:07.500   873  1302 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.16 rxSuccessRate=0.27 delta 1000 -> 1000
09-14 01:04:07.500   873  1300 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-14 01:04:07.500   873  1302 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-14 01:04:07.510   873  1302 E native  : do suspend true
,09-14 01:04:07.517   873  1300 D WifiNative-HAL: p2pGetDeviceAddress
,09-14 01:04:07.518   873  1300 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-14 01:04:07.525   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-14 01:04:07.525   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 01:04:07.536   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-14 01:04:07.623   873  1302 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-14 01:04:07.628  1453  1453 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-14 01:04:08.055  1453  1453 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-14 01:04:08.103  1453  1453 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-14 01:04:08.104  1453  1453 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-14 01:04:08.114   873  1302 D WifiConfigStore: Retrieve network priorities after PNO.
,09-14 01:04:08.131   873  1302 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-14 01:04:08.131   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-14 01:04:08.132   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-14 01:04:08.153   873  1302 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-14 01:04:08.167   371   871 D CommandListener: Setting iface cfg
,09-14 01:04:08.170   873  1302 D WifiStateMachine: Start Dhcp Watchdog 3
,09-14 01:04:08.184   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-14 01:04:08.221   873  4268 D DhcpClient: Receive thread started
,09-14 01:04:08.308   873  1302 E native  : do suspend false
,09-14 01:04:08.328   873  1906 D DhcpClient: Broadcasting DHCPDISCOVER
,09-14 01:04:08.341   873  4268 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-14 01:04:08.344   873  1906 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-14 01:04:08.348   873  1906 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-14 01:04:08.362   873  4268 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-14 01:04:08.364   873  1906 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-14 01:04:08.368   371   871 D CommandListener: Setting iface cfg
,09-14 01:04:08.380   873  1906 D DhcpClient: Scheduling renewal in 86399s
,09-14 01:04:08.381   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-14 01:04:08.385   873  1302 E native  : do suspend true
,09-14 01:04:08.405   873  1302 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-14 01:04:08.407   873  1302 D WifiConfigStore: No blacklist allowed without epno enabled
,09-14 01:04:08.409   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-14 01:04:08.411   873  1304 D ConnectivityService: Adding iface wlan0 to network 102
,09-14 01:04:08.421   873  1302 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-14 01:04:08.430  3799  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 01:04:08.430  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:04:08.430  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:04:08.430  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:04:08.430  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 01:04:08.430  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-14 01:04:08.430  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-14 01:04:08.430  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-14 01:04:08.432  3799  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-14 01:04:08.439  3799  3847 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-14 01:04:08.439  3799  3847 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-14 01:04:08.441  3799  3847 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f537df3 Bundle[{}]
,09-14 01:04:08.442  3799  3847 I io.jxcore.node.LifeCycleMonitor: start: OK
09-14 01:04:08.442  3799  3847 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-14 01:04:08.442  3799  3847 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-14 01:04:08.443  3799  3847 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-14 01:04:08.444  3799  3847 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-14 01:04:08.444  3799  3847 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-14 01:04:08.448  3799  3847 I System.out: Running OutgoingSocketThread
,09-14 01:04:08.449  3799  4271 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 422)
,09-14 01:04:08.450  3799  4271 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 39979
,09-14 01:04:08.450  3799  4271 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-14 01:04:08.469   873  1304 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-14 01:04:08.470   873  1304 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-14 01:04:08.472   873  1304 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-14 01:04:08.474   873  1304 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-14 01:04:08.475   873  1304 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-14 01:04:08.484   873  1304 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-14 01:04:08.491   873  1304 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-14 01:04:08.491   873  1304 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,09-14 01:04:08.491   873  1304 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,09-14 01:04:08.491   873  1304 D ConnectivityService:    accepting network in place of null
,09-14 01:04:08.491   873  1302 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-14 01:04:08.493   873  1304 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-14 01:04:08.493   873  1302 D WifiNative-HAL: stopRssiMonitoring, cmdId 0,
,09-14 01:04:08.504   873  4267 D NetlinkSocketObserver: NeighborEvent{elapsedMs=162408, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-14 01:04:08.534   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 01:04:08.566   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-14 01:04:08.571   873  4266 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-14 01:04:08.575   873  1304 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-14 01:04:08.575   873  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-14 01:04:08.582   873  1304 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-14 01:04:08.585   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-14 01:04:08.605  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-14 01:04:08.605  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:04:08.605  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:04:08.605  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:04:08.605  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 01:04:08.605  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 01:04:08.605  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 01:04:08.605  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 01:04:08.610  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 01:04:08.617  1699  1699 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-14 01:04:08.622  1699  1699 D SystemUpdateService: onCreate
,09-14 01:04:08.627  1699  1699 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-14 01:04:08.633   873  4266 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 13 Sep 2016 23:04:08 GMT], X-Android-Received-Millis=[1473807848633], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473807848607]}
,09-14 01:04:08.635   873  1304 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-14 01:04:08.635   873  1304 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-14 01:04:08.635   873  1304 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-14 01:04:08.636   873  1304 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-14 01:04:08.659  1699  4279 I SystemUpdateService: active receiver: enabled
,09-14 01:04:08.682  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:04:08.691  1699  1699 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-14 01:04:08.694  1699  2467 I iu.UploadsManager: num queued entries: 0
,09-14 01:04:08.694  1699  2467 I iu.UploadsManager: num updated entries: 0
09-14 01:04:08.695  1699  2467 I iu.SyncManager: NEXT; no task
,09-14 01:04:08.701  1699  4279 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-14 01:04:08.703  1699  1699 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-14 01:04:08.718  1699  1699 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-14 01:04:08.727  3925  3925 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-14 01:04:08.737  1699  4282 I MDM     : [180] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-14 01:04:08.737  1699  4282 W BaseAppContext: Using Auth Proxy for data requests.
,09-14 01:04:08.740  3925  3925 D SprintDMHelper: simOperator: 
,09-14 01:04:08.741  3925  3925 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-14 01:04:08.748  1699  4279 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-14 01:04:08.749  1699  4279 I SystemUpdateService: now status is 0 (complete)
,09-14 01:04:08.749  1699  4279 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-14 01:04:08.749  1699  4279 I SystemUpdateService: file has been verified
,09-14 01:04:08.751  1699  4282 V GoogleAuthProtoRequest: [180] a.<init>: mAccountName set to: thalitester@gmail.com
,09-14 01:04:08.749  1699  4279 I SystemUpdateService: OTA package size = 12249756
,09-14 01:04:08.789  1699  4279 I SystemUpdateService: showing system update notification
,09-14 01:04:08.806  1699  1699 D SystemUpdateService: onDestroy
,09-14 01:04:08.878  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:04:08.879  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:04:08.884  2304  4285 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-14 01:04:08.905  1504  4290 I VacuumService: Vacuum at: now=1473807848905 tag=VacuumService
,09-14 01:04:09.035  1504  2211 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-14 01:04:09.036  1504  2211 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-14 01:04:09.036  1504  2211 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-14 01:04:09.036  1504  2211 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:04:09.051  1504  4292 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,09-14 01:04:09.055  1504  4292 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-14 01:04:09.155  1504  4292 W Uploader:  no longer exists, so no auth token.
,09-14 01:04:09.183  1699  4282 E MDM     : [180] SitrepService.a: Error sending sitrep.
,09-14 01:04:09.451  3799  3847 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 423)
,09-14 01:04:09.452  3799  3847 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 423)
,09-14 01:04:09.461  3799  3847 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 428)
,09-14 01:04:09.464  3799  3847 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-14 01:04:09.464  3799  3847 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 429)
,09-14 01:04:09.469  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-14 01:04:09.469  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6eeb6f9 added. We now have 2 listener(s)
,09-14 01:04:09.471  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-14 01:04:09.471  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-14 01:04:09.471  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-14 01:04:09.471  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-14 01:04:09.472  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cf9f63e added. We now have 9 listener(s)
,09-14 01:04:09.472  3799  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 01:04:09.472  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 01:04:09.475  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 01:04:09.484  3799  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 01:04:09.484  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:04:09.484  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:04:09.484  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:04:09.484  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 01:04:09.484  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 01:04:09.484  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 01:04:09.484  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 01:04:09.488  3799  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 01:04:09.489  3799  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 01:04:09.491  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 01:04:09.491  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bf61ec added. We now have 3 listener(s)
09-14 01:04:09.493  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:04:09.497  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-14 01:04:09.497  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 01:04:09.497  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 01:04:09.497  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 01:04:09.498  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dac9b5 added. We now have 10 listener(s)
,09-14 01:04:09.498  3799  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 01:04:09.498  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:04:09.498  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-14 01:04:09.498  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:04:09.498  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 01:04:09.498  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:04:09.499  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 01:04:09.499  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 01:04:09.499  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6eeb6f9 removed from the list
09-14 01:04:09.499  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:04:09.499  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cf9f63e removed from the list
09-14 01:04:09.500  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:04:09.500  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:04:09.500  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:04:09.501  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 01:04:09.502  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 01:04:09.503  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:04:09.503  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:04:09.503  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:04:09.504  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cf9f63e not in the list
,09-14 01:04:09.504  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:04:09.504  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 01:04:09.509  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 01:04:09.509  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:04:09.509  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:04:09.509  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dac9b5 removed from the list
09-14 01:04:09.509  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 01:04:09.510  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:04:09.510  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:04:09.510  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 01:04:09.510  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bf61ec removed from the list
09-14 01:04:09.510  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-14 01:04:09.510  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9b384a added. We now have 2 listener(s)
09-14 01:04:09.512  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-14 01:04:09.512  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 01:04:09.512  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-14 01:04:09.512  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 01:04:09.512  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@979b3bb added. We now have 9 listener(s)
09-14 01:04:09.512  3799  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 01:04:09.513  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 01:04:09.519  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 01:04:09.523  3799  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 01:04:09.523  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:04:09.523  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:04:09.523  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:04:09.523  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 01:04:09.523  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 01:04:09.523  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 01:04:09.523  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 01:04:09.526  3799  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 01:04:09.526  3799  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 01:04:09.526  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 01:04:09.526  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3b4c31 added. We now have 3 listener(s)
,09-14 01:04:09.528  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-14 01:04:09.528  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 01:04:09.528  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 01:04:09.528  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-14 01:04:09.528  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c5c8f16 added. We now have 10 listener(s)
,09-14 01:04:09.528  3799  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 01:04:09.528  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-14 01:04:09.528  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 01:04:09.528  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-14 01:04:09.528  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 01:04:09.529  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 01:04:09.529  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:04:09.531  3799  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 01:04:09.531  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:04:09.531  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 01:04:09.539  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 01:04:09.539  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-14 01:04:09.539  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 01:04:09.544  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-14 01:04:09.544  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 01:04:09.544  3799  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 01:04:09.544  3799  3847 D BluetoothAdapter: STATE_ON
,09-14 01:04:09.547  4212  4250 D BtGatt.GattService: registerClient() - UUID=7624f705-ee80-4612-9cc1-8dc74e9b5901
,09-14 01:04:09.548  4212  4228 D BtGatt.GattService: onClientRegistered() - UUID=7624f705-ee80-4612-9cc1-8dc74e9b5901, clientIf=5
,09-14 01:04:09.549  3799  3811 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-14 01:04:09.551  4212  4222 D BtGatt.GattService: start scan with filters
,09-14 01:04:09.557  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-14 01:04:09.557  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 01:04:09.557  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 01:04:09.557  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-14 01:04:09.558  4212  4231 D BtGatt.ScanManager: handling starting scan
,09-14 01:04:09.560  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-14 01:04:09.560  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-14 01:04:09.560  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-14 01:04:09.560  4212  4231 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@57c0357
09-14 01:04:09.562  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 01:04:09.565  4212  4228 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-14 01:04:09.565  3799  3847 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-14 01:04:09.565  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:04:09.565  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-14 01:04:09.565  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-14 01:04:09.565  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:04:09.565  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 01:04:09.565  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-14 01:04:09.565  4212  4231 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-14 01:04:09.565  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 01:04:09.565  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-14 01:04:09.565  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 01:04:09.565  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-14 01:04:09.566  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-14 01:04:09.566  3799  3847 D BluetoothAdapter: STATE_ON
,09-14 01:04:09.567  4212  4222 D BtGatt.GattService: stopScan() - queue size =1
09-14 01:04:09.568  4212  4240 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 01:04:09.568  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-14 01:04:09.568  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-14 01:04:09.568  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-14 01:04:09.569  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-14 01:04:09.569  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-14 01:04:09.569  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 01:04:09.570  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:04:09.570  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 01:04:09.570  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-14 01:04:09.570  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 01:04:09.571  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 01:04:09.571  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 01:04:09.571  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 01:04:09.574   873  1304 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-14 01:04:09.574  4212  4228 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-14 01:04:09.574  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:04:09.575  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 01:04:09.575  3799  3799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 01:04:09.575  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 01:04:09.575  3799  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 01:04:09.575  4212  4231 D BtGatt.ScanManager: Starting BLE batch scan
09-14 01:04:09.575  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:04:09.575  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 01:04:09.575  4212  4231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-14 01:04:09.575  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:04:09.575  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-14 01:04:09.575  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 01:04:09.575  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d9b384a removed from the list
09-14 01:04:09.576  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:04:09.576  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@979b3bb removed from the list
,09-14 01:04:09.576  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:04:09.576  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 01:04:09.577  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-14 01:04:09.577  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-14 01:04:09.577  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:04:09.577  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 01:04:09.579  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:04:09.579  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:04:09.579  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:04:09.579  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@979b3bb not in the list,
09-14 01:04:09.579  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 01:04:09.586  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-14 01:04:09.587  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 01:04:09.587  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 01:04:09.587  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 01:04:09.589  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-14 01:04:09.589  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 01:04:09.589  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 01:04:09.592  3799  3799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-14 01:04:09.592  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 01:04:09.593  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 01:04:09.594  4212  4228 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-14 01:04:09.594  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 01:04:09.600  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 01:04:09.600  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 01:04:09.600  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 01:04:09.603  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 01:04:09.604  3799  3847 D BluetoothAdapter: STATE_ON
,09-14 01:04:09.604  3799  3847 D BluetoothLeScanner: could not find callback wrapper
,09-14 01:04:09.604  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-14 01:04:09.604  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 01:04:09.604  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-14 01:04:09.604  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 01:04:09.604  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c5c8f16 removed from the list
09-14 01:04:09.604  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:04:09.604  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 01:04:09.604  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:04:09.604  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 01:04:09.605  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3b4c31 removed from the list
,09-14 01:04:09.605  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-14 01:04:09.605  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ae6aee added. We now have 2 listener(s)
09-14 01:04:09.607  4212  4228 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 01:04:09.607  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 01:04:09.608  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-14 01:04:09.608  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 01:04:09.608  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 01:04:09.608  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-14 01:04:09.608  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ec3b8f added. We now have 9 listener(s)
09-14 01:04:09.608  3799  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
09-14 01:04:09.608  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-14 01:04:09.611  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 01:04:09.616  3799  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 01:04:09.616  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:04:09.616  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:04:09.616  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:04:09.616  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 01:04:09.616  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 01:04:09.616  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 01:04:09.616  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 01:04:09.616  4212  4228 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-14 01:04:09.616  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:04:09.617  4212  4231 D BtGatt.ScanManager: stopping BLe Batch
,09-14 01:04:09.618  3799  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 01:04:09.618  3799  3847 D io.jxcore.node.ConnectivityMonitor: start: OK,
09-14 01:04:09.618  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 01:04:09.619  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8128a25 added. We now have 3 listener(s)
,09-14 01:04:09.621  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:04:09.622  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-14 01:04:09.622  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-14 01:04:09.623  4212  4228 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-14 01:04:09.623  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:04:09.623  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:04:09.623  4212  4231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-14 01:04:09.623  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-14 01:04:09.624  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 01:04:09.624  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39a47fa added. We now have 10 listener(s)
09-14 01:04:09.625  3799  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 01:04:09.625  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-14 01:04:09.626  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-14 01:04:09.627  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 01:04:09.627  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-14 01:04:09.627  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 01:04:09.628  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 01:04:09.630  4212  4228 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 01:04:09.631  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 01:04:09.634  3799  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-14 01:04:09.634  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 01:04:09.643  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 01:04:09.644  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 01:04:09.645  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 01:04:09.650  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-14 01:04:09.651  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-14 01:04:09.651  3799  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 01:04:09.652  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:04:09.657  4212  4222 D BtGatt.GattService: registerClient() - UUID=a1815c1d-2545-463b-a6af-e4d01270db2d
09-14 01:04:09.658  4212  4228 D BtGatt.GattService: onClientRegistered() - UUID=a1815c1d-2545-463b-a6af-e4d01270db2d, clientIf=5
09-14 01:04:09.658  3799  3811 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 01:04:09.659  4212  4223 D BtGatt.GattService: start scan with filters
09-14 01:04:09.665  4212  4231 D BtGatt.ScanManager: handling starting scan
09-14 01:04:09.664  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-14 01:04:09.665  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 01:04:09.665  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 01:04:09.665  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-14 01:04:09.672  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 01:04:09.673  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 01:04:09.673  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-14 01:04:09.676  4212  4228 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-14 01:04:09.676  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:04:09.677  4212  4231 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-14 01:04:09.679  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-14 01:04:09.682  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 01:04:09.682  3799  3847 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-14 01:04:09.682  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:04:09.682  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 01:04:09.682  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:04:09.682  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:04:09.682  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:04:09.682  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 01:04:09.682  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 01:04:09.683  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5ae6aee removed from the list
09-14 01:04:09.683  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:04:09.683  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ec3b8f removed from the list
09-14 01:04:09.683  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
09-14 01:04:09.683  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 01:04:09.684  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-14 01:04:09.684  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-14 01:04:09.684  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:04:09.684  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 01:04:09.685  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:04:09.686  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:04:09.686  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:04:09.686  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ec3b8f not in the list
09-14 01:04:09.686  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-14 01:04:09.686  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 01:04:09.686  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-14 01:04:09.686  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 01:04:09.686  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-14 01:04:09.687  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:04:09.689  4212  4240 D BtGatt.GattService: stopScan() - queue size =1
09-14 01:04:09.689  4212  4222 D BtGatt.GattService: unregisterClient() - clientIf=5
09-14 01:04:09.690  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:04:09.690  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 01:04:09.690  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-14 01:04:09.691  4212  4228 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-14 01:04:09.691  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:04:09.691  4212  4231 D BtGatt.ScanManager: Starting BLE batch scan
09-14 01:04:09.692  4212  4231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-14 01:04:09.692  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-14 01:04:09.693  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-14 01:04:09.694  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 01:04:09.695  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:04:09.695  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-14 01:04:09.695  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 01:04:09.696  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:04:09.698  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 01:04:09.698  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 01:04:09.698  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 01:04:09.703  3799  3799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 01:04:09.703  3799  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-14 01:04:09.708  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 01:04:09.708  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 01:04:09.708  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-14 01:04:09.709  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 01:04:09.709  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:04:09.710  4212  4228 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-14 01:04:09.710  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:04:09.711  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 01:04:09.711  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 01:04:09.711  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 01:04:09.716  3799  3799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-14 01:04:09.716  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-14 01:04:09.718  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 01:04:09.721  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-14 01:04:09.721  4212  4228 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 01:04:09.722  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 01:04:09.721  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 01:04:09.723  3799  3847 D BluetoothAdapter: STATE_ON
,09-14 01:04:09.724  3799  3847 D BluetoothLeScanner: could not find callback wrapper
09-14 01:04:09.724  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-14 01:04:09.724  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 01:04:09.724  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-14 01:04:09.724  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:04:09.724  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39a47fa removed from the list
,09-14 01:04:09.724  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:04:09.725  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 01:04:09.725  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 01:04:09.725  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-14 01:04:09.725  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8128a25 removed from the list
09-14 01:04:09.726  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-14 01:04:09.726  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@185dc52 added. We now have 2 listener(s)
09-14 01:04:09.727  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-14 01:04:09.727  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-14 01:04:09.728  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 01:04:09.728  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 01:04:09.728  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88bfb23 added. We now have 9 listener(s)
,09-14 01:04:09.728  3799  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 01:04:09.729  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-14 01:04:09.729  4212  4228 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-14 01:04:09.729  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
09-14 01:04:09.730  4212  4231 D BtGatt.ScanManager: stopping BLe Batch
09-14 01:04:09.731  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 01:04:09.740  4212  4228 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-14 01:04:09.740  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 01:04:09.741  4212  4231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-14 01:04:09.743  3799  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 01:04:09.743  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:04:09.743  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
09-14 01:04:09.743  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:04:09.743  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 01:04:09.743  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 01:04:09.743  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 01:04:09.743  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-14 01:04:09.746  4212  4228 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
09-14 01:04:09.746  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-14 01:04:09.749  3799  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-14 01:04:09.750  3799  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
09-14 01:04:09.750  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 01:04:09.750  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f25d9 added. We now have 3 listener(s)
,09-14 01:04:09.751  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-14 01:04:09.752  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-14 01:04:09.752  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 01:04:09.752  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-14 01:04:09.752  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e816b9e added. We now have 10 listener(s)
09-14 01:04:09.752  3799  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 01:04:09.752  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-14 01:04:09.752  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-14 01:04:09.752  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-14 01:04:09.752  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-14 01:04:09.752  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 01:04:09.754  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:04:09.755  3799  3847 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-14 01:04:09.755  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 01:04:09.756  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:04:09.758  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 01:04:09.758  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-14 01:04:09.758  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 01:04:09.761  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-14 01:04:09.761  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-14 01:04:09.761  3799  3847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-14 01:04:09.761  3799  3847 D BluetoothAdapter: STATE_ON
,09-14 01:04:09.763  4212  4223 D BtGatt.GattService: registerClient() - UUID=c3071815-ba0d-4269-94e3-6575de016c3c
,09-14 01:04:09.763  4212  4228 D BtGatt.GattService: onClientRegistered() - UUID=c3071815-ba0d-4269-94e3-6575de016c3c, clientIf=5
,09-14 01:04:09.764  3799  3809 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-14 01:04:09.764  4212  4240 D BtGatt.GattService: start scan with filters
,09-14 01:04:09.766  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-14 01:04:09.766  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-14 01:04:09.766  4212  4231 D BtGatt.ScanManager: handling starting scan
09-14 01:04:09.766  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-14 01:04:09.766  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-14 01:04:09.768  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-14 01:04:09.768  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-14 01:04:09.768  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-14 01:04:09.770  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-14 01:04:09.771  4212  4228 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-14 01:04:09.771  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:04:09.772  4212  4231 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-14 01:04:09.774  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-14 01:04:09.775  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 01:04:09.775  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:04:09.775  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-14 01:04:09.775  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:04:09.775  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-14 01:04:09.775  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 01:04:09.775  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@185dc52 removed from the list
,09-14 01:04:09.775  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 01:04:09.775  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88bfb23 removed from the list
09-14 01:04:09.775  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 01:04:09.775  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-14 01:04:09.776  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-14 01:04:09.776  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-14 01:04:09.776  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 01:04:09.776  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 01:04:09.777  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:04:09.777  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:04:09.777  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 01:04:09.777  4212  4228 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-14 01:04:09.777  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@88bfb23 not in the list
09-14 01:04:09.777  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-14 01:04:09.777  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:04:09.777  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-14 01:04:09.777  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-14 01:04:09.777  4212  4231 D BtGatt.ScanManager: Starting BLE batch scan
09-14 01:04:09.777  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-14 01:04:09.777  4212  4231 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-14 01:04:09.777  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-14 01:04:09.778  3799  3847 D BluetoothAdapter: STATE_ON
09-14 01:04:09.778  4212  4222 D BtGatt.GattService: stopScan() - queue size =1
,09-14 01:04:09.779  4212  4223 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-14 01:04:09.779  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:04:09.779  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-14 01:04:09.779  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-14 01:04:09.779  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-14 01:04:09.779  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-14 01:04:09.780  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 01:04:09.780  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:04:09.780  3799  3847 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-14 01:04:09.780  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 01:04:09.781  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:04:09.782  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 01:04:09.782  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 01:04:09.782  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-14 01:04:09.785  3799  3799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 01:04:09.785  3799  3799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-14 01:04:09.787  4212  4228 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-14 01:04:09.787  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:04:09.788  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-14 01:04:09.789  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-14 01:04:09.789  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-14 01:04:09.789  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 01:04:09.790  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 01:04:09.791  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-14 01:04:09.792  3799  3847 D BluetoothAdapter: STATE_ON
,09-14 01:04:09.792  3799  3847 D BluetoothLeScanner: could not find callback wrapper
09-14 01:04:09.792  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-14 01:04:09.792  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 01:04:09.792  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-14 01:04:09.793  4212  4228 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-14 01:04:09.793  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 01:04:09.793  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-14 01:04:09.793  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:04:09.793  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 01:04:09.793  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e816b9e removed from the list
09-14 01:04:09.793  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-14 01:04:09.793  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:04:09.793  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-14 01:04:09.793  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 01:04:09.793  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-14 01:04:09.793  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7f25d9 removed from the list
09-14 01:04:09.794  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-14 01:04:09.795  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f15076 added. We now have 2 listener(s)
,09-14 01:04:09.795  3799  3799 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-14 01:04:09.795  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-14 01:04:09.795  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 01:04:09.797  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-14 01:04:09.797  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-14 01:04:09.797  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
09-14 01:04:09.797  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 01:04:09.797  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-14 01:04:09.797  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b876677 added. We now have 9 listener(s)
09-14 01:04:09.797  3799  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-14 01:04:09.798  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-14 01:04:09.800  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-14 01:04:09.803  4212  4228 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-14 01:04:09.803  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:04:09.804  4212  4231 D BtGatt.ScanManager: stopping BLe Batch
,09-14 01:04:09.805  3799  3847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-14 01:04:09.805  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-14 01:04:09.805  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-14 01:04:09.805  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-14 01:04:09.805  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-14 01:04:09.805  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-14 01:04:09.805  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-14 01:04:09.805  3799  3847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-14 01:04:09.807  3799  3847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-14 01:04:09.807  3799  3847 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-14 01:04:09.808  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-14 01:04:09.808  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@756b34d added. We now have 3 listener(s)
,09-14 01:04:09.809  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-14 01:04:09.809  4212  4228 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-14 01:04:09.809  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:04:09.809  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-14 01:04:09.810  4212  4231 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-14 01:04:09.810  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-14 01:04:09.810  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-14 01:04:09.810  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-14 01:04:09.810  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@519fe02 added. We now have 10 listener(s)
09-14 01:04:09.810  3799  3847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-14 01:04:09.810  3799  3847 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-14 01:04:09.810  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-14 01:04:09.810  3799  3847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-14 01:04:09.810  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:04:09.810  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:04:09.810  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-14 01:04:09.810  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-14 01:04:09.811  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1f15076 removed from the list
09-14 01:04:09.811  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-14 01:04:09.811  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b876677 removed from the list
,09-14 01:04:09.812  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-14 01:04:09.813  3799  3847 D io.jxcore.node.ConnectivityMonitor: stop
,09-14 01:04:09.813  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-14 01:04:09.813  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:04:09.813  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:04:09.814  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-14 01:04:09.814  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:04:09.814  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 01:04:09.814  3799  3847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b876677 not in the list
,09-14 01:04:09.814  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:04:09.814  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:04:09.814  4212  4228 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-14 01:04:09.815  4212  4228 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-14 01:04:09.815  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-14 01:04:09.815  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-14 01:04:09.815  3799  3847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-14 01:04:09.815  3799  3847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@519fe02 removed from the list
,09-14 01:04:09.815  3799  3847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-14 01:04:09.815  3799  3847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-14 01:04:09.815  3799  3847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-14 01:04:09.815  3799  3847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-14 01:04:09.816  3799  3847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@756b34d removed from the list
09-14 01:04:09.816  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-14 01:04:09.816  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-14 01:04:09.816  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-14 01:04:09.817  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-14 01:04:09.817  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-14 01:04:09.817  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-14 01:04:09.822  3799  4301 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: My test thread name)
,09-14 01:04:09.822  3799  4301 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 436, thread name: My test thread name)
09-14 01:04:09.822  3799  4301 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 436, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-14 01:04:09.824  3799  4302 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: My test thread name)
,09-14 01:04:09.824  3799  4302 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: My test thread name)
09-14 01:04:09.824  3799  4302 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-14 01:04:09.825  3799  3847 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-14 01:04:09.825  3799  3847 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-14 01:04:09.825  3799  3847 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-14 01:04:09.825  3799  3847 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,09-14 01:04:09.825  3799  3847 D com.test.thalitest.ThaliTestRunner: Total duration: 22870 ms
,09-14 01:04:09.827  3799  3847 I jxcore-log: Total number of executed tests:  80
09-14 01:04:09.827  3799  3847 I jxcore-log: 
,09-14 01:04:09.827  3799  3847 I jxcore-log: Number of passed tests:  80
09-14 01:04:09.827  3799  3847 I jxcore-log: 
09-14 01:04:09.827  3799  3847 I jxcore-log: Number of failed tests:  0
09-14 01:04:09.827  3799  3847 I jxcore-log: 
,09-14 01:04:09.827  3799  3847 I jxcore-log: Number of ignored tests:  0
09-14 01:04:09.827  3799  3847 I jxcore-log: 
09-14 01:04:09.827  3799  3847 I jxcore-log: Total duration:  22870
09-14 01:04:09.827  3799  3847 I jxcore-log: 
,09-14 01:04:09.830  3799  3847 I jxcore-log: Unit Test app is loaded
09-14 01:04:09.830  3799  3847 I jxcore-log: 
,09-14 01:04:09.837  3799  3799 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,09-14 01:04:09.838  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 01:04:09.838  3799  3847 I jxcore-log: 
09-14 01:04:09.842  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 01:04:09.842  3799  3847 I jxcore-log: 
,09-14 01:04:09.843  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 01:04:09.843  3799  3847 I jxcore-log: 
09-14 01:04:09.844  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 01:04:09.844  3799  3847 I jxcore-log: 
09-14 01:04:09.845  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 01:04:09.845  3799  3847 I jxcore-log: 
,09-14 01:04:09.847  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 01:04:09.847  3799  3847 I jxcore-log: 
,09-14 01:04:09.850  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 01:04:09.850  3799  3847 I jxcore-log: 
,09-14 01:04:09.852  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 01:04:09.852  3799  3847 I jxcore-log: 
09-14 01:04:09.853  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 01:04:09.853  3799  3847 I jxcore-log: 
,09-14 01:04:09.854  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 01:04:09.854  3799  3847 I jxcore-log: 
09-14 01:04:09.855  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 01:04:09.855  3799  3847 I jxcore-log: 
09-14 01:04:09.856  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 01:04:09.856  3799  3847 I jxcore-log: 
,09-14 01:04:09.858  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 01:04:09.858  3799  3847 I jxcore-log: 
,09-14 01:04:09.858  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-14 01:04:09.858  3799  3847 I jxcore-log: 
09-14 01:04:09.859  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 01:04:09.859  3799  3847 I jxcore-log: 
,09-14 01:04:09.860  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 01:04:09.860  3799  3847 I jxcore-log: 
09-14 01:04:09.861  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 01:04:09.861  3799  3847 I jxcore-log: 
09-14 01:04:09.862  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
,09-14 01:04:09.862  3799  3847 I jxcore-log: 
09-14 01:04:09.863  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 01:04:09.863  3799  3847 I jxcore-log: 
09-14 01:04:09.864  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 01:04:09.864  3799  3847 I jxcore-log: 
,09-14 01:04:09.865  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 01:04:09.865  3799  3847 I jxcore-log: 
09-14 01:04:09.866  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-14 01:04:09.866  3799  3847 I jxcore-log: 
,09-14 01:04:09.866  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 01:04:09.866  3799  3847 I jxcore-log: 
,09-14 01:04:09.867  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-14 01:04:09.867  3799  3847 I jxcore-log: 
09-14 01:04:09.868  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 01:04:09.868  3799  3847 I jxcore-log: 
,09-14 01:04:09.869  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-14 01:04:09.869  3799  3847 I jxcore-log: 
09-14 01:04:09.870  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 01:04:09.870  3799  3847 I jxcore-log: 
,09-14 01:04:09.871  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 01:04:09.871  3799  3847 I jxcore-log: 
09-14 01:04:09.871  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 01:04:09.871  3799  3847 I jxcore-log: 
,09-14 01:04:09.872  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 01:04:09.872  3799  3847 I jxcore-log: 
,09-14 01:04:09.873  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 01:04:09.873  3799  3847 I jxcore-log: 
,09-14 01:04:09.873  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-14 01:04:09.873  3799  3847 I jxcore-log: 
,09-14 01:04:09.876  3799  3847 I jxcore-log: My device name is: motorola-Nexus 6
09-14 01:04:09.876  3799  3847 I jxcore-log: 
,09-14 01:04:10.101  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 01:04:10.222  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 01:04:10.297  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-14 01:04:10.346  3799  3847 E jxcore  : Error!: Cannot find module './CoordinatedClient'
09-14 01:04:10.346  3799  3847 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w._oldRes","_lineNumber":"802","_columnNumber":"9","_msg":"    at $w._oldRes@module.js:802:9"},{"_fileName":"module.js","_functionName":"$w._resolveFilename","_lineNumber":"1771","_columnNumber":"1","_msg":"    at $w._resolveFilename@module.js:1771:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"362","_columnNumber":"4","_msg":"    at $w._load@module.js:362:4"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedTape.js","_functionName":"","_lineNumber":"12","_columnNumber":"25","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedTape.js:12:25"}]
,09-14 01:04:10.350  3799  3847 E jxcore-log: Error: 
,09-14 01:04:10.350  3799  3847 E jxcore-log: Cannot find module './CoordinatedClient'
09-14 01:04:10.350  3799  3847 E jxcore-log:  (module.js 802:9)
,09-14 01:04:10.350  3799  3847 E jxcore-log: 
09-14 01:04:10.351  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 01:04:10.351  3799  3847 I jxcore-log: 
09-14 01:04:10.352  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 01:04:10.352  3799  3847 I jxcore-log: 
,09-14 01:04:10.353  3799  3847 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-14 01:04:10.353  3799  3847 I jxcore-log: 
,09-14 01:04:10.614  1504  4292 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-14 01:04:10.614  1504  4292 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-14 01:04:10.614  1504  4292 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:04:10.614  1504  4292 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:04:10.630  1504  4292 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-14 01:04:10.630  1504  4292 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-14 01:04:10.630  1504  4292 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-14 01:04:10.630  1504  4292 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-14 01:04:10.630  1504  4292 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-14 01:04:10.630  1504  4292 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-14 01:04:10.630  1504  4292 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-14 01:04:10.630  1504  4292 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-14 01:04:10.630  1504  4292 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-14 01:04:10.630  1504  4292 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-14 01:04:10.630  1504  4292 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-14 01:04:10.630  1504  4292 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-14 01:04:10.630  1504  4292 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-14 01:04:11.257   873  1302 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,09-14 01:04:11.594  1504  4292 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,09-14 01:04:11.594  1504  4292 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,09-14 01:04:11.594  1504  4292 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-14 01:04:11.594  1504  4292 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:04:11.622  1504  4292 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-14 01:04:11.622  1504  4292 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-14 01:04:11.622  1504  4292 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-14 01:04:11.622  1504  4292 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-14 01:04:11.622  1504  4292 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-14 01:04:11.622  1504  4292 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-14 01:04:11.622  1504  4292 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-14 01:04:11.622  1504  4292 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-14 01:04:11.622  1504  4292 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-14 01:04:11.622  1504  4292 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-14 01:04:11.622  1504  4292 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-14 01:04:11.622  1504  4292 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-14 01:04:11.622  1504  4292 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-14 01:04:12.251  1504  4292 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
09-14 01:04:12.251  1504  4292 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
09-14 01:04:12.251  1504  4292 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:04:12.251  1504  4292 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:04:12.275  1504  4292 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
09-14 01:04:12.275  1504  4292 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-14 01:04:12.275  1504  4292 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-14 01:04:12.275  1504  4292 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-14 01:04:12.275  1504  4292 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
09-14 01:04:12.275  1504  4292 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
09-14 01:04:12.275  1504  4292 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
09-14 01:04:12.275  1504  4292 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
09-14 01:04:12.275  1504  4292 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
09-14 01:04:12.275  1504  4292 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
09-14 01:04:12.275  1504  4292 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
09-14 01:04:12.275  1504  4292 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
09-14 01:04:12.275  1504  4292 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,09-14 01:04:12.572  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-14 01:04:12.572  3799  3847 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
,09-14 01:04:12.773  3799  3847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-14 01:04:12.773  3799  3847 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,09-14 01:04:16.497   873  1304 D ConnectivityService: handlePromptUnvalidated 102
,09-14 01:04:27.544  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:04:27.553  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:04:27.555  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:04:27.606  1504  2971 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-14 01:04:27.607  1504  2971 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-14 01:04:27.607  1504  2971 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-14 01:04:27.607  1504  2971 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:04:27.674  3515  3515 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-14 01:04:27.679  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-14 01:04:27.682  3515  3515 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-14 01:04:38.715  4091  4311 I BooksSync: Starting books sync for 61035162, extras: ade
,09-14 01:04:38.770  4091  4314 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-14 01:04:38.814  4041  4312 V KeepSync: Connecting to GoogleApiClient
,09-14 01:04:38.817   873  1991 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-14 01:04:38.818  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:04:38.824  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:04:38.908  1504  2971 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-14 01:04:38.908  1504  2971 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-14 01:04:38.908  1504  2971 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:04:38.909  1504  2971 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:04:38.994  1504  2211 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-14 01:04:38.994  1504  2211 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-14 01:04:39.000  1504  2211 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-14 01:04:39.000  1504  2211 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:04:39.017  1504  2971 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-14 01:04:39.017  1504  2971 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-14 01:04:39.017  1504  2971 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-14 01:04:39.017  1504  2971 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:04:39.025  1699  4315 V BaseAuthAsyncOperation: access token request failed
,09-14 01:04:39.028  4041  4312 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-14 01:04:39.044  4091  4314 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-14 01:04:39.045  4091  4311 E BooksSync: Soft error
09-14 01:04:39.045  4091  4311 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-14 01:04:39.045  4091  4311 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-14 01:04:39.045  4091  4311 E BooksSync: Sync error
09-14 01:04:39.045  4091  4311 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-14 01:04:39.045  4091  4311 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-14 01:04:39.045  4091  4311 I BooksSync: Finished books sync
,09-14 01:04:39.074   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 176882, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-14 01:04:39.126  1504  1997 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-14 01:04:39.127  1504  1997 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-14 01:04:39.127  1504  1997 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:04:39.127  1504  1997 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:04:39.146  4041  4312 E KeepSync: IOException
09-14 01:04:39.146  4041  4312 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-14 01:04:39.146  4041  4312 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-14 01:04:39.146  4041  4312 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-14 01:04:39.146  4041  4312 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-14 01:04:39.146  4041  4312 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-14 01:04:39.146  4041  4312 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-14 01:04:39.146  4041  4312 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-14 01:04:39.146  4041  4312 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-14 01:04:39.146  4041  4312 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-14 01:04:39.146  4041  4312 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-14 01:04:39.146  4041  4312 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-14 01:04:39.146  4041  4312 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-14 01:04:39.146  4041  4312 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-14 01:04:39.146  4041  4312 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-14 01:04:39.146  4041  4312 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-14 01:04:39.146  4041  4312 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-14 01:04:39.146  4041  4312 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-14 01:04:39.146  4041  4312 E KeepSync: 	... 10 more
09-14 01:04:39.146  4041  4312 W KeepSync: Sync result 2
,09-14 01:04:39.152   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 178264, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-14 01:04:44.200   873  4267 D NetlinkSocketObserver: NeighborEvent{elapsedMs=198103, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 01:04:56.098  1873  1911 I Keyboard.Facilitator.LanguageModelFlusher: run()
09-14 01:04:56.099  1873  1911 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-14 01:04:56.136  1504  1504 I ConfigService: onCreate
,09-14 01:05:01.190  1504  1504 I ConfigService: onDestroy
,09-14 01:05:11.199  4041  4318 V KeepSync: Connecting to GoogleApiClient
,09-14 01:05:11.200   873  2131 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-14 01:05:11.249  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:05:11.251  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:05:11.292  1504  2211 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-14 01:05:11.292  1504  2211 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-14 01:05:11.292  1504  2211 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:05:11.293  1504  2211 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:05:11.317  1699  4319 V BaseAuthAsyncOperation: access token request failed
,09-14 01:05:11.319  4041  4318 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-14 01:05:11.390  1504  1997 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-14 01:05:11.391  1504  1997 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-14 01:05:11.391  1504  1997 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:05:11.391  1504  1997 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:05:11.419  4041  4318 E KeepSync: IOException
09-14 01:05:11.419  4041  4318 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-14 01:05:11.419  4041  4318 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-14 01:05:11.419  4041  4318 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-14 01:05:11.419  4041  4318 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-14 01:05:11.419  4041  4318 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-14 01:05:11.419  4041  4318 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-14 01:05:11.419  4041  4318 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-14 01:05:11.419  4041  4318 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-14 01:05:11.419  4041  4318 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-14 01:05:11.419  4041  4318 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-14 01:05:11.419  4041  4318 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-14 01:05:11.419  4041  4318 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-14 01:05:11.419  4041  4318 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-14 01:05:11.419  4041  4318 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-14 01:05:11.419  4041  4318 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-14 01:05:11.419  4041  4318 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-14 01:05:11.419  4041  4318 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-14 01:05:11.419  4041  4318 E KeepSync: 	... 10 more
,09-14 01:05:11.419  4041  4318 W KeepSync: Sync result 2
,09-14 01:05:11.430   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 225006, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-14 01:05:15.174   873  4267 D NetlinkSocketObserver: NeighborEvent{elapsedMs=229077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-14 01:05:41.730  4091  4321 I BooksSync: Starting books sync for 61035162, extras: ade
,09-14 01:05:41.841  4091  4324 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-14 01:05:41.862  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:05:41.864  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:05:41.903  1504  1997 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-14 01:05:41.903  1504  1997 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-14 01:05:41.903  1504  1997 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:05:41.903  1504  1997 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:05:41.947  1504  2211 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-14 01:05:41.947  1504  2211 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-14 01:05:41.947  1504  2211 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:05:41.947  1504  2211 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:05:41.997  3556  4323 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-14 01:05:41.997  3556  4323 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-14 01:05:41.997  3556  4323 E HttpOperation: 	at jdm.a(PG:82)
09-14 01:05:41.997  3556  4323 E HttpOperation: 	at jcs.o(PG:406)
09-14 01:05:41.997  3556  4323 E HttpOperation: 	at jcn.a(PG:1379)
09-14 01:05:41.997  3556  4323 E HttpOperation: 	at jcs.i(PG:143)
09-14 01:05:41.997  3556  4323 E HttpOperation: 	at blb.a(PG:3937)
09-14 01:05:41.997  3556  4323 E HttpOperation: 	at czp.a(PG:18188)
09-14 01:05:41.997  3556  4323 E HttpOperation: 	at czp.a(PG:9081)
09-14 01:05:41.997  3556  4323 E HttpOperation: 	at czq.run(PG:1686)
09-14 01:05:41.997  3556  4323 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-14 01:05:41.997  3556  4323 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-14 01:05:41.997  3556  4323 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-14 01:05:41.997  3556  4323 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-14 01:05:41.997  3556  4323 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-14 01:05:41.997  3556  4323 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-14 01:05:41.997  3556  4323 E HttpOperation: 	at jdj.a(PG:4091)
09-14 01:05:41.997  3556  4323 E HttpOperation: 	at jdj.a(PG:1125)
09-14 01:05:41.997  3556  4323 E HttpOperation: 	at jdm.a(PG:77)
09-14 01:05:41.997  3556  4323 E HttpOperation: 	... 12 more
09-14 01:05:41.997  3556  4323 E HttpOperation: Caused by: faj: BadAuthentication
09-14 01:05:41.997  3556  4323 E HttpOperation: 	at fal.a(PG:38)
09-14 01:05:41.997  3556  4323 E HttpOperation: 	at jdj.a(PG:4089)
09-14 01:05:41.997  3556  4323 E HttpOperation: 	... 14 more
,09-14 01:05:42.010  1504  1997 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-14 01:05:42.011  1504  1997 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-14 01:05:42.011  1504  1997 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-14 01:05:42.011  1504  1997 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:05:42.040  4091  4324 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-14 01:05:42.041  4091  4321 E BooksSync: Soft error
09-14 01:05:42.041  4091  4321 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-14 01:05:42.041  4091  4321 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-14 01:05:42.041  4091  4321 E BooksSync: Sync error
09-14 01:05:42.041  4091  4321 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-14 01:05:42.041  4091  4321 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-14 01:05:42.041  4091  4321 I BooksSync: Finished books sync
,09-14 01:05:42.053  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-14 01:05:42.053  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-14 01:05:42.053  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:05:42.053  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:05:42.057   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 225566, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-14 01:05:42.091  3556  4323 E HttpOperation: [getmobileexperiments] Unexpected exception
09-14 01:05:42.091  3556  4323 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-14 01:05:42.091  3556  4323 E HttpOperation: 	at jdm.a(PG:82)
09-14 01:05:42.091  3556  4323 E HttpOperation: 	at jcs.o(PG:406)
09-14 01:05:42.091  3556  4323 E HttpOperation: 	at jcn.a(PG:1379)
09-14 01:05:42.091  3556  4323 E HttpOperation: 	at jcs.i(PG:143)
09-14 01:05:42.091  3556  4323 E HttpOperation: 	at hec.a(PG:42)
09-14 01:05:42.091  3556  4323 E HttpOperation: 	at hee.a(PG:102)
09-14 01:05:42.091  3556  4323 E HttpOperation: 	at czr.a(PG:65)
09-14 01:05:42.091  3556  4323 E HttpOperation: 	at kka.a(PG:108)
09-14 01:05:42.091  3556  4323 E HttpOperation: 	at czp.a(PG:19176)
09-14 01:05:42.091  3556  4323 E HttpOperation: 	at czp.a(PG:9081)
09-14 01:05:42.091  3556  4323 E HttpOperation: 	at czq.run(PG:1686)
09-14 01:05:42.091  3556  4323 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-14 01:05:42.091  3556  4323 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-14 01:05:42.091  3556  4323 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-14 01:05:42.091  3556  4323 E HttpOperation: 	,at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-14 01:05:42.091  3556  4323 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-14 01:05:42.091  3556  4323 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-14 01:05:42.091  3556  4323 E HttpOperation: 	at jdj.a(PG:4091)
09-14 01:05:42.091  3556  4323 E HttpOperation: 	at jdj.a(PG:1125)
09-14 01:05:42.091  3556  4323 E HttpOperation: 	at jdm.a(PG:77)
09-14 01:05:42.091  3556  4323 E HttpOperation: 	... 15 more
09-14 01:05:42.091  3556  4323 E HttpOperation: Caused by: faj: BadAuthentication
09-14 01:05:42.091  3556  4323 E HttpOperation: 	at fal.a(PG:38)
09-14 01:05:42.091  3556  4323 E HttpOperation: 	at jdj.a(PG:4089)
09-14 01:05:42.091  3556  4323 E HttpOperation: 	... 17 more
,09-14 01:05:42.092  3556  4323 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-14 01:05:42.092  3556  4323 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	at jdm.a(PG:82)
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	at jcs.o(PG:406)
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	at jcn.a(PG:1379)
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	at jcs.i(PG:143)
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	at hec.a(PG:42)
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	at hee.a(PG:102)
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	at czr.a(PG:65)
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	at kka.a(PG:108)
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	at czp.a(PG:19176)
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	at czp.a(PG:9081)
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	at czq.run(PG:1686)
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-14 01:05:42.092  3556  4323 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	at jdj.a(PG:4091)
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	at jdj.a(PG:1125)
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	at jdm.a(PG:77)
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	... 15 more
09-14 01:05:42.092  3556  4323 E ExperimentLoader: Caused by: faj: BadAuthentication
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	at fal.a(PG:38)
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	at jdj.a(PG:4089)
09-14 01:05:42.092  3556  4323 E ExperimentLoader: 	... 17 more
,09-14 01:05:42.215   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 250913, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-14 01:05:47.054   873  4267 D NetlinkSocketObserver: NeighborEvent{elapsedMs=260957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 01:05:53.801   873  4267 D NetlinkSocketObserver: NeighborEvent{elapsedMs=267704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-14 01:06:14.097  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:06:14.099  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:06:14.126  1504  2971 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-14 01:06:14.126  1504  2971 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-14 01:06:14.126  1504  2971 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-14 01:06:14.126  1504  2971 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:06:14.149  3556  4332 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-14 01:06:14.149  3556  4332 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-14 01:06:14.149  3556  4332 E HttpOperation: 	at jdm.a(PG:82)
09-14 01:06:14.149  3556  4332 E HttpOperation: 	at jcs.o(PG:406)
09-14 01:06:14.149  3556  4332 E HttpOperation: 	at jcn.a(PG:1379)
09-14 01:06:14.149  3556  4332 E HttpOperation: 	at jcs.i(PG:143)
09-14 01:06:14.149  3556  4332 E HttpOperation: 	at blb.a(PG:3937)
09-14 01:06:14.149  3556  4332 E HttpOperation: 	at czp.a(PG:18188)
09-14 01:06:14.149  3556  4332 E HttpOperation: 	at czp.a(PG:9081)
09-14 01:06:14.149  3556  4332 E HttpOperation: 	at czq.run(PG:1686)
09-14 01:06:14.149  3556  4332 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-14 01:06:14.149  3556  4332 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-14 01:06:14.149  3556  4332 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-14 01:06:14.149  3556  4332 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-14 01:06:14.149  3556  4332 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-14 01:06:14.149  3556  4332 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-14 01:06:14.149  3556  4332 E HttpOperation: 	at jdj.a(PG:4091)
09-14 01:06:14.149  3556  4332 E HttpOperation: 	at jdj.a(PG:1125)
09-14 01:06:14.149  3556  4332 E HttpOperation: 	at jdm.a(PG:77)
09-14 01:06:14.149  3556  4332 E HttpOperation: 	... 12 more
09-14 01:06:14.149  3556  4332 E HttpOperation: Caused by: faj: BadAuthentication
09-14 01:06:14.149  3556  4332 E HttpOperation: 	at fal.a(PG:38)
09-14 01:06:14.149  3556  4332 E HttpOperation: 	at jdj.a(PG:4089)
09-14 01:06:14.149  3556  4332 E HttpOperation: 	... 14 more
,09-14 01:06:14.193  1504  1997 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-14 01:06:14.193  1504  1997 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-14 01:06:14.193  1504  1997 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:06:14.194  1504  1997 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:06:14.228  3556  4332 E HttpOperation: [getmobileexperiments] Unexpected exception
09-14 01:06:14.228  3556  4332 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-14 01:06:14.228  3556  4332 E HttpOperation: 	at jdm.a(PG:82)
09-14 01:06:14.228  3556  4332 E HttpOperation: 	at jcs.o(PG:406)
09-14 01:06:14.228  3556  4332 E HttpOperation: 	at jcn.a(PG:1379)
09-14 01:06:14.228  3556  4332 E HttpOperation: 	at jcs.i(PG:143)
09-14 01:06:14.228  3556  4332 E HttpOperation: 	at hec.a(PG:42)
09-14 01:06:14.228  3556  4332 E HttpOperation: 	at hee.a(PG:102)
09-14 01:06:14.228  3556  4332 E HttpOperation: 	at czr.a(PG:65)
09-14 01:06:14.228  3556  4332 E HttpOperation: 	at kka.a(PG:108)
09-14 01:06:14.228  3556  4332 E HttpOperation: 	at czp.a(PG:19176)
09-14 01:06:14.228  3556  4332 E HttpOperation: 	at czp.a(PG:9081)
09-14 01:06:14.228  3556  4332 E HttpOperation: 	at czq.run(PG:1686)
09-14 01:06:14.228  3556  4332 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-14 01:06:14.228  3556  4332 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-14 01:06:14.228  3556  4332 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-14 01:06:14.228  3556  4332 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-14 01:06:14.228  3556  4332 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-14 01:06:14.228  3556  4332 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-14 01:06:14.228  3556  4332 E HttpOperation: 	at jdj.a(PG:4091)
09-14 01:06:14.228  3556  4332 E HttpOperation: 	at jdj.a(PG:1125)
09-14 01:06:14.228  3556  4332 E HttpOperation: 	at jdm.a(PG:77)
09-14 01:06:14.228  3556  4332 E HttpOperation: 	... 15 more
09-14 01:06:14.228  3556  4332 E HttpOperation: Caused by: faj: BadAuthentication
09-14 01:06:14.228  3556  4332 E HttpOperation: 	at fal.a(PG:38)
09-14 01:06:14.228  3556  4332 E HttpOperation: 	at jdj.a(PG:4089)
09-14 01:06:14.228  3556  4332 E HttpOperation: 	... 17 more
09-14 01:06:14.229  3556  4332 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-14 01:06:14.229  3556  4332 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	at jdm.a(PG:82)
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	at jcs.o(PG:406)
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	at jcn.a(PG:1379)
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	at jcs.i(PG:143)
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	at hec.a(PG:42)
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	at hee.a(PG:102)
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	at czr.a(PG:65)
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	at kka.a(PG:108)
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	at czp.a(PG:19176)
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	at czp.a(PG:9081)
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	at czq.run(PG:1686)
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-14 01:06:14.229  3556  4332 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	at jdj.a(PG:4091)
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	at jdm.a(PG:77)
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	... 15 more
09-14 01:06:14.229  3556  4332 E ExperimentLoader: Caused by: faj: BadAuthentication
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	at fal.a(PG:38)
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	at jdj.a(PG:4089)
09-14 01:06:14.229  3556  4332 E ExperimentLoader: 	... 17 more
,09-14 01:06:14.417   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 287634, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-14 01:06:25.561   873  4267 D NetlinkSocketObserver: NeighborEvent{elapsedMs=299464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 01:06:44.586  4041  4336 V KeepSync: Connecting to GoogleApiClient
,09-14 01:06:44.586   873   883 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-14 01:06:44.670  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:06:44.674  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:06:44.708  1504  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-14 01:06:44.708  1504  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-14 01:06:44.708  1504  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:06:44.708  1504  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:06:44.722  1699  4337 V BaseAuthAsyncOperation: access token request failed
,09-14 01:06:44.722  4041  4336 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-14 01:06:44.762  1504  1997 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-14 01:06:44.762  1504  1997 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-14 01:06:44.762  1504  1997 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-14 01:06:44.762  1504  1997 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:06:44.774  4041  4336 E KeepSync: IOException
09-14 01:06:44.774  4041  4336 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-14 01:06:44.774  4041  4336 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-14 01:06:44.774  4041  4336 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-14 01:06:44.774  4041  4336 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-14 01:06:44.774  4041  4336 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-14 01:06:44.774  4041  4336 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-14 01:06:44.774  4041  4336 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-14 01:06:44.774  4041  4336 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-14 01:06:44.774  4041  4336 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-14 01:06:44.774  4041  4336 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-14 01:06:44.774  4041  4336 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-14 01:06:44.774  4041  4336 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-14 01:06:44.774  4041  4336 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-14 01:06:44.774  4041  4336 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-14 01:06:44.774  4041  4336 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-14 01:06:44.774  4041  4336 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-14 01:06:44.774  4041  4336 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-14 01:06:44.774  4041  4336 E KeepSync: 	... 10 more
09-14 01:06:44.774  4041  4336 W KeepSync: Sync result 2
,09-14 01:06:44.777   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 289232, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-14 01:06:55.534   873  4267 D NetlinkSocketObserver: NeighborEvent{elapsedMs=329437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-14 01:07:08.592  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:07:08.599  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:07:08.603  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:07:08.634  1504  2971 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-14 01:07:08.634  1504  2971 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-14 01:07:08.634  1504  2971 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:07:08.634  1504  2971 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:07:08.657  1504  2971 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-14 01:07:08.657  1504  2971 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-14 01:07:08.657  1504  2971 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-14 01:07:08.657  1504  2971 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-14 01:07:08.657  1504  2971 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-14 01:07:08.657  1504  2971 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-14 01:07:08.657  1504  2971 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-14 01:07:08.661  3515  3546 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-14 01:07:08.661  3515  3546 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-14 01:07:08.661  3515  3546 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-14 01:07:08.661  3515  3546 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-14 01:07:08.661  3515  3546 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-14 01:07:08.661  3515  3546 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-14 01:07:08.661  3515  3546 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-14 01:07:14.942  4091  4342 I BooksSync: Starting books sync for 61035162, extras: ade
,09-14 01:07:14.983  4091  4343 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-14 01:07:14.998  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:07:15.003  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:07:15.064  1504  2211 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-14 01:07:15.064  1504  2211 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-14 01:07:15.064  1504  2211 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:07:15.065  1504  2211 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:07:15.124  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:07:15.129  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:07:15.184  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-14 01:07:15.184  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-14 01:07:15.184  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:07:15.185  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:07:15.230  4091  4343 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-14 01:07:15.232  4091  4342 E BooksSync: Soft error
09-14 01:07:15.232  4091  4342 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-14 01:07:15.232  4091  4342 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-14 01:07:15.235  4091  4342 E BooksSync: Sync error
09-14 01:07:15.235  4091  4342 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-14 01:07:15.235  4091  4342 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-14 01:07:15.235  4091  4342 I BooksSync: Finished books sync
,09-14 01:07:15.247   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 321139, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-14 01:07:40.654   873  4267 D NetlinkSocketObserver: NeighborEvent{elapsedMs=374557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 01:07:41.949  1504  2090 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-14 01:07:45.631  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:07:45.633  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:07:45.662  1504  2211 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-14 01:07:45.662  1504  2211 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-14 01:07:45.662  1504  2211 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:07:45.662  1504  2211 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:07:45.683  3556  4346 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-14 01:07:45.683  3556  4346 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-14 01:07:45.683  3556  4346 E HttpOperation: 	at jdm.a(PG:82)
09-14 01:07:45.683  3556  4346 E HttpOperation: 	at jcs.o(PG:406)
09-14 01:07:45.683  3556  4346 E HttpOperation: 	at jcn.a(PG:1379)
09-14 01:07:45.683  3556  4346 E HttpOperation: 	at jcs.i(PG:143)
09-14 01:07:45.683  3556  4346 E HttpOperation: 	at blb.a(PG:3937)
09-14 01:07:45.683  3556  4346 E HttpOperation: 	at czp.a(PG:18188)
09-14 01:07:45.683  3556  4346 E HttpOperation: 	at czp.a(PG:9081)
09-14 01:07:45.683  3556  4346 E HttpOperation: 	at czq.run(PG:1686)
09-14 01:07:45.683  3556  4346 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-14 01:07:45.683  3556  4346 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-14 01:07:45.683  3556  4346 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-14 01:07:45.683  3556  4346 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-14 01:07:45.683  3556  4346 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-14 01:07:45.683  3556  4346 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-14 01:07:45.683  3556  4346 E HttpOperation: 	at jdj.a(PG:4091)
09-14 01:07:45.683  3556  4346 E HttpOperation: 	at jdj.a(PG:1125)
09-14 01:07:45.683  3556  4346 E HttpOperation: 	at jdm.a(PG:77)
09-14 01:07:45.683  3556  4346 E HttpOperation: 	... 12 more
09-14 01:07:45.683  3556  4346 E HttpOperation: Caused by: faj: BadAuthentication
09-14 01:07:45.683  3556  4346 E HttpOperation: 	at fal.a(PG:38)
09-14 01:07:45.683  3556  4346 E HttpOperation: 	at jdj.a(PG:4089)
09-14 01:07:45.683  3556  4346 E HttpOperation: 	... 14 more
,09-14 01:07:45.725  1504  2971 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-14 01:07:45.725  1504  2971 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-14 01:07:45.725  1504  2971 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:07:45.725  1504  2971 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:07:45.749  3556  4346 E HttpOperation: [getmobileexperiments] Unexpected exception
09-14 01:07:45.749  3556  4346 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-14 01:07:45.749  3556  4346 E HttpOperation: 	at jdm.a(PG:82)
09-14 01:07:45.749  3556  4346 E HttpOperation: 	at jcs.o(PG:406)
09-14 01:07:45.749  3556  4346 E HttpOperation: 	at jcn.a(PG:1379)
09-14 01:07:45.749  3556  4346 E HttpOperation: 	at jcs.i(PG:143)
09-14 01:07:45.749  3556  4346 E HttpOperation: 	at hec.a(PG:42)
09-14 01:07:45.749  3556  4346 E HttpOperation: 	at hee.a(PG:102)
09-14 01:07:45.749  3556  4346 E HttpOperation: 	at czr.a(PG:65)
09-14 01:07:45.749  3556  4346 E HttpOperation: 	at kka.a(PG:108)
09-14 01:07:45.749  3556  4346 E HttpOperation: 	at czp.a(PG:19176)
09-14 01:07:45.749  3556  4346 E HttpOperation: 	at czp.a(PG:9081)
09-14 01:07:45.749  3556  4346 E HttpOperation: 	at czq.run(PG:1686)
09-14 01:07:45.749  3556  4346 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-14 01:07:45.749  3556  4346 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-14 01:07:45.749  3556  4346 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-14 01:07:45.749  3556  4346 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-14 01:07:45.749  3556  4346 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-14 01:07:45.749  3556  4346 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-14 01:07:45.749  3556  4346 E HttpOperation: 	at jdj.a(PG:4091)
09-14 01:07:45.749  3556  4346 E HttpOperation: 	at jdj.a(PG:1125)
09-14 01:07:45.749  3556  4346 E HttpOperation: 	at jdm.a(PG:77)
09-14 01:07:45.749  3556  4346 E HttpOperation: 	... 15 more
09-14 01:07:45.749  3556  4346 E HttpOperation: Caused by: faj: BadAuthentication
09-14 01:07:45.749  3556  4346 E HttpOperation: 	at fal.a(PG:38)
09-14 01:07:45.749  3556  4346 E HttpOperation: 	at jdj.a(PG:4089)
09-14 01:07:45.749  3556  4346 E HttpOperation: 	... 17 more
09-14 01:07:45.750  3556  4346 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-14 01:07:45.750  3556  4346 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	at jdm.a(PG:82)
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	at jcs.o(PG:406)
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	at jcn.a(PG:1379)
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	at jcs.i(PG:143)
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	at hec.a(PG:42)
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	at hee.a(PG:102)
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	at czr.a(PG:65)
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	at kka.a(PG:108)
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	at czp.a(PG:19176)
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	at czp.a(PG:9081)
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	at czq.run(PG:1686)
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-14 01:07:45.750  3556  4346 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	at jdj.a(PG:4091)
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	at jdm.a(PG:77)
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	... 15 more
09-14 01:07:45.750  3556  4346 E ExperimentLoader: Caused by: faj: BadAuthentication
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	at fal.a(PG:38)
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	at jdj.a(PG:4089)
09-14 01:07:45.750  3556  4346 E ExperimentLoader: 	... 17 more
,09-14 01:07:45.875   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 351353, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-14 01:07:56.761   873  4267 D NetlinkSocketObserver: NeighborEvent{elapsedMs=390664, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-14 01:08:28.547   873  4267 D NetlinkSocketObserver: NeighborEvent{elapsedMs=422450, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 01:08:52.664  4041  4352 V KeepSync: Connecting to GoogleApiClient
,09-14 01:08:52.665   873   884 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-14 01:08:52.742  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:08:52.746  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:08:52.799  1504  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,09-14 01:08:52.799  1504  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-14 01:08:52.800  1504  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-14 01:08:52.800  1504  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:08:52.837  1699  4353 V BaseAuthAsyncOperation: access token request failed
,09-14 01:08:52.839  4041  4352 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-14 01:08:52.960  1504  2971 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-14 01:08:52.960  1504  2971 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-14 01:08:52.960  1504  2971 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:08:52.961  1504  2971 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:08:53.028  4041  4352 E KeepSync: IOException
09-14 01:08:53.028  4041  4352 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-14 01:08:53.028  4041  4352 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-14 01:08:53.028  4041  4352 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-14 01:08:53.028  4041  4352 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-14 01:08:53.028  4041  4352 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-14 01:08:53.028  4041  4352 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-14 01:08:53.028  4041  4352 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-14 01:08:53.028  4041  4352 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-14 01:08:53.028  4041  4352 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-14 01:08:53.028  4041  4352 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-14 01:08:53.028  4041  4352 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-14 01:08:53.028  4041  4352 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-14 01:08:53.028  4041  4352 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-14 01:08:53.028  4041  4352 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-14 01:08:53.028  4041  4352 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-14 01:08:53.028  4041  4352 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-14 01:08:53.028  4041  4352 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-14 01:08:53.028  4041  4352 E KeepSync: 	... 10 more
09-14 01:08:53.028  4041  4352 W KeepSync: Sync result 2
,09-14 01:08:53.043   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 446477, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,09-14 01:09:13.641   873  4267 D NetlinkSocketObserver: NeighborEvent{elapsedMs=467544, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-14 01:09:25.686  4091  4356 I BooksSync: Starting books sync for 61035162, extras: ade
,09-14 01:09:25.726  4091  4357 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-14 01:09:25.742  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:09:25.747  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:09:25.796  1504  2971 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-14 01:09:25.797  1504  2971 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-14 01:09:25.797  1504  2971 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-14 01:09:25.797  1504  2971 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:09:25.840  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:09:25.843  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:09:25.885  1504  2211 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-14 01:09:25.885  1504  2211 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-14 01:09:25.885  1504  2211 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-14 01:09:25.886  1504  2211 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:09:25.911  4091  4357 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-14 01:09:25.914  4091  4356 E BooksSync: Soft error
09-14 01:09:25.914  4091  4356 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-14 01:09:25.914  4091  4356 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-14 01:09:25.916  4091  4356 E BooksSync: Sync error
09-14 01:09:25.916  4091  4356 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-14 01:09:25.916  4091  4356 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-14 01:09:25.916  4091  4356 I BooksSync: Finished books sync
,09-14 01:09:25.930   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 479503, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-14 01:09:45.454   873  4267 D NetlinkSocketObserver: NeighborEvent{elapsedMs=499357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 01:09:56.348  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:09:56.352  1504  1504 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-14 01:09:56.381  1504  1514 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-14 01:09:56.381  1504  1514 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-14 01:09:56.381  1504  1514 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:09:56.382  1504  1514 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:09:56.405  3556  4361 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-14 01:09:56.405  3556  4361 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-14 01:09:56.405  3556  4361 E HttpOperation: 	at jdm.a(PG:82)
09-14 01:09:56.405  3556  4361 E HttpOperation: 	at jcs.o(PG:406)
09-14 01:09:56.405  3556  4361 E HttpOperation: 	at jcn.a(PG:1379)
09-14 01:09:56.405  3556  4361 E HttpOperation: 	at jcs.i(PG:143)
09-14 01:09:56.405  3556  4361 E HttpOperation: 	at blb.a(PG:3937)
09-14 01:09:56.405  3556  4361 E HttpOperation: 	at czp.a(PG:18188)
09-14 01:09:56.405  3556  4361 E HttpOperation: 	at czp.a(PG:9081)
09-14 01:09:56.405  3556  4361 E HttpOperation: 	at czq.run(PG:1686)
09-14 01:09:56.405  3556  4361 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-14 01:09:56.405  3556  4361 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-14 01:09:56.405  3556  4361 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-14 01:09:56.405  3556  4361 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-14 01:09:56.405  3556  4361 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-14 01:09:56.405  3556  4361 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-14 01:09:56.405  3556  4361 E HttpOperation: 	at jdj.a(PG:4091)
09-14 01:09:56.405  3556  4361 E HttpOperation: 	at jdj.a(PG:1125)
09-14 01:09:56.405  3556  4361 E HttpOperation: 	at jdm.a(PG:77)
09-14 01:09:56.405  3556  4361 E HttpOperation: 	... 12 more
09-14 01:09:56.405  3556  4361 E HttpOperation: Caused by: faj: BadAuthentication
09-14 01:09:56.405  3556  4361 E HttpOperation: 	at fal.a(PG:38)
09-14 01:09:56.405  3556  4361 E HttpOperation: 	at jdj.a(PG:4089)
09-14 01:09:56.405  3556  4361 E HttpOperation: 	... 14 more
,09-14 01:09:56.515  1504  2211 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-14 01:09:56.515  1504  2211 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-14 01:09:56.515  1504  2211 I GLSUser : [GLSUser] Extracting token using key: Auth
09-14 01:09:56.515  1504  2211 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-14 01:09:56.542  3556  4361 E HttpOperation: [getmobileexperiments] Unexpected exception
09-14 01:09:56.542  3556  4361 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-14 01:09:56.542  3556  4361 E HttpOperation: 	at jdm.a(PG:82)
09-14 01:09:56.542  3556  4361 E HttpOperation: 	at jcs.o(PG:406)
09-14 01:09:56.542  3556  4361 E HttpOperation: 	at jcn.a(PG:1379)
09-14 01:09:56.542  3556  4361 E HttpOperation: 	at jcs.i(PG:143)
09-14 01:09:56.542  3556  4361 E HttpOperation: 	at hec.a(PG:42)
09-14 01:09:56.542  3556  4361 E HttpOperation: 	at hee.a(PG:102)
09-14 01:09:56.542  3556  4361 E HttpOperation: 	at czr.a(PG:65)
09-14 01:09:56.542  3556  4361 E HttpOperation: 	at kka.a(PG:108)
09-14 01:09:56.542  3556  4361 E HttpOperation: 	at czp.a(PG:19176)
09-14 01:09:56.542  3556  4361 E HttpOperation: 	at czp.a(PG:9081)
09-14 01:09:56.542  3556  4361 E HttpOperation: 	at czq.run(PG:1686)
09-14 01:09:56.542  3556  4361 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-14 01:09:56.542  3556  4361 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-14 01:09:56.542  3556  4361 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-14 01:09:56.542  3556  4361 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-14 01:09:56.542  3556  4361 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-14 01:09:56.542  3556  4361 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-14 01:09:56.542  3556  4361 E HttpOperation: 	at jdj.a(PG:4091)
09-14 01:09:56.542  3556  4361 E HttpOperation: 	at jdj.a(PG:1125)
09-14 01:09:56.542  3556  4361 E HttpOperation: 	at jdm.a(PG:77)
09-14 01:09:56.542  3556  4361 E HttpOperation: 	... 15 more
09-14 01:09:56.542  3556  4361 E HttpOperation: Caused by: faj: BadAuthentication
09-14 01:09:56.542  3556  4361 E HttpOperation: 	at fal.a(PG:38)
09-14 01:09:56.542  3556  4361 E HttpOperation: 	at jdj.a(PG:4089)
09-14 01:09:56.542  3556  4361 E HttpOperation: 	... 17 more
,09-14 01:09:56.542  3556  4361 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-14 01:09:56.542  3556  4361 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	at jdm.a(PG:82)
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	at jcs.o(PG:406)
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	at jcn.a(PG:1379)
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	at jcs.i(PG:143)
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	at hec.a(PG:42)
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	at hee.a(PG:102)
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	at czr.a(PG:65)
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	at kka.a(PG:108)
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	at czp.a(PG:19176)
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	at czp.a(PG:9081)
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	at czq.run(PG:1686)
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-14 01:09:56.542  3556  4361 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	at jdj.a(PG:4091)
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	at jdj.a(PG:1125)
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	at jdm.a(PG:77)
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	... 15 more
09-14 01:09:56.542  3556  4361 E ExperimentLoader: Caused by: faj: BadAuthentication
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	at fal.a(PG:38)
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	at jdj.a(PG:4089)
09-14 01:09:56.542  3556  4361 E ExperimentLoader: 	... 17 more
,09-14 01:09:56.657   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 505842, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-14 01:10:12.654   873  4267 D NetlinkSocketObserver: NeighborEvent{elapsedMs=526557, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-14 01:10:44.441   873  4267 D NetlinkSocketObserver: NeighborEvent{elapsedMs=558344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 01:10:53.054  1504  2090 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-14 01:11:14.148   873  4267 D NetlinkSocketObserver: NeighborEvent{elapsedMs=588051, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-14 01:11:45.881   873  4267 D NetlinkSocketObserver: NeighborEvent{elapsedMs=619784, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 01:12:13.961   873  4267 D NetlinkSocketObserver: NeighborEvent{elapsedMs=647864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-14 01:12:45.721   873  4267 D NetlinkSocketObserver: NeighborEvent{elapsedMs=679624, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 01:19:09.076  1699  4393 I EventLogService: Opted in for usage reporting
,09-14 01:19:09.077  1699  4393 I EventLogService: Aggregate from 1473806675445 (log), 1473806675445 (data)
,09-14 01:19:09.126  1699  4393 W EventLogAggregator: Unknown tag: snet_gcore
,09-14 01:19:09.126  1699  4393 W EventLogAggregator: Unknown tag: snet_launch_service
,09-14 01:19:09.252  1699  4393 I ServiceDumpSys: dumping service [account]
,09-14 01:19:14.067   873  4267 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1067970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-14 01:19:21.534   873  4267 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1075437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-14 01:21:44.350   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms),09-14 01:27:00.317  4421  4421 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-14 01:27:00.322  4421  4421 D AndroidRuntime: CheckJNI is OFF
09-14 01:27:00.365  4421  4421 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-14 01:27:00.414  4421  4421 I Radio-JNI: register_android_hardware_Radio DONE
09-14 01:27:00.437  4421  4421 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-14 01:27:00.451   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-14 01:27:00.452   873   886 I ActivityManager: Killing 3799:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-14 01:27:00.566   873   896 W PackageSettings: Skipping PackageSetting{a01de8 com.example.hello/10273} due to missing metadata
09-14 01:27:00.613   873   896 I art     : Starting a blocking GC Explicit
09-14 01:27:00.633   873  2132 I WindowState: WIN DEATH: Window{666a767 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-14 01:27:00.633   873   884 D GraphicsStats: Buffer count: 2
09-14 01:27:00.634   873  1303 D WifiService: Client connection lost with reason: 4
09-14 01:27:00.673   873   896 I art     : Explicit concurrent mark sweep GC freed 32745(2MB) AllocSpace objects, 10(200KB) LOS objects, 33% free, 29MB/43MB, paused 1.087ms total 59.675ms
09-14 01:27:00.679   873   886 E libprocessgroup: failed to kill 1 processes for processgroup 3799
09-14 01:27:00.680   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-14 01:27:00.680   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-14 01:27:00.681   873   886 E ActivityManager: Failure starting process com.test.thalitest
09-14 01:27:00.681   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-14 01:27:00.681   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-14 01:27:00.681   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-14 01:27:00.681   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-14 01:27:00.681   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-14 01:27:00.681   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-14 01:27:00.681   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-14 01:27:00.681   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-14 01:27:00.681   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-14 01:27:00.681   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-14 01:27:00.681   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-14 01:27:00.681   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-14 01:27:00.681   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-14 01:27:00.681   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-14 01:27:00.681   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-14 01:27:00.681   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 01:27:00.681   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-14 01:27:00.681   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-14 01:27:00.681   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-14 01:27:00.681   873   886 I ActivityManager:   Force finishing activity ActivityRecord{3ff7a1c u0 com.test.thalitest/.MainActivity t4}
09-14 01:27:00.699   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-14 01:27:00.701  4421  4421 I art     : System.exit called, status: 0
09-14 01:27:00.701  4421  4421 I AndroidRuntime: VM exiting with result code 0.
09-14 01:27:00.714   873   896 I ActivityManager: Start proc 4432:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
09-14 01:27:00.714   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-14 01:27:00.724   873  2208 W ActivityManager: Spurious death for ProcessRecord{bcc2fcf 0:com.test.thalitest/u0a0}, curProc for 3799: null
09-14 01:27:00.725   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-14 01:27:00.729  4212  4212 D BluetoothMapAppObserver: onReceive
09-14 01:27:00.729  4212  4212 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-14 01:27:00.733   873  1292 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-14 01:27:00.733  1887  2258 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-14 01:27:00.742  3669  3669 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-14 01:27:00.743  1873  1873 I Keyboard.Facilitator: resetDictionaries() : en_US
09-14 01:27:00.773  1873  4444 I Keyboard.Facilitator.DecoderInitializer: run()
09-14 01:27:00.775  1873  4444 I Decoder : createOrResetDecoder
09-14 01:27:00.786  1944  1944 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-14 01:27:00.793   873   883 I ActivityManager: Start proc 4448:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-14 01:27:00.801   873  2204 I ActivityManager: Killing 2117:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
09-14 01:27:00.818   873   884 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3799 uid 10000
09-14 01:27:00.820  1873  1873 I Keyboard.Facilitator: onFinishInput()
09-14 01:27:00.843   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-14 01:27:00.858  1504  1504 I ConfigService: onCreate
09-14 01:27:00.863   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-14 01:27:00.863  1961  2057 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-14 01:27:00.863   873   885 E PackageManager: Failed to write settings, restoring backup
09-14 01:27:00.863   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-14 01:27:00.863   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-14 01:27:00.863   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-14 01:27:00.863   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-14 01:27:00.863   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-14 01:27:00.863   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 01:27:00.863   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-14 01:27:00.863   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-14 01:27:00.867   873   886 E DropBoxManagerService: Can't write: system_server_wtf
09-14 01:27:00.867   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-14 01:27:00.867   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-14 01:27:00.867   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-14 01:27:00.867   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-14 01:27:00.867   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-14 01:27:00.867   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-14 01:27:00.867   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-14 01:27:00.867   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-14 01:27:00.867   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-14 01:27:00.867   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-14 01:27:00.867   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-14 01:27:00.867   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-14 01:27:00.867   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-14 01:27:00.867   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-14 01:27:00.867   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-14 01:27:00.867   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-14 01:27:00.867   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-14 01:27:00.867   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-14 01:27:00.867   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-14 01:27:00.867   873   886 E DropBoxManagerService: 	... 13 more
09-14 01:27:00.870  1504  4462 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-14 01:27:00.870  1504  4462 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-14 01:27:00.870  1504  4462 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-14 01:27:00.870  1504  4462 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-14 01:27:00.870  1504  4462 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-14 01:27:00.870  1504  4462 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-14 01:27:00.870  1504  4462 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-14 01:27:00.870  1504  4462 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-14 01:27:00.870  1504  4462 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-14 01:27:00.870  1504  4462 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-14 01:27:00.870  1504  4462 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-14 01:27:00.870  1504  4462 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-14 01:27:00.870  1504  4462 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-14 01:27:00.870  1504  4462 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-14 01:27:00.870  1504  4462 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-14 01:27:00.870  1504  4462 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-14 01:27:00.870  1504  4462 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-14 01:27:00.870  1504  4462 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-14 01:27:00.870  1504  4462 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-14 01:27:00.870  1504  4462 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-14 01:27:00.870  1504  4462 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-14 01:27:00.870  1504  4462 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-14 01:27:00.870  1504  4462 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-14 01:27:00.870  1504  4462 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-14 01:27:00.870  1504  4462 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-14 01:27:00.870  1504  4462 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-14 01:27:00.870  1504  4462 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-14 01:27:00.870  1504  4462 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-14 01:27:00.870  1504  4462 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-14 01:27:00.870  1504  4462 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-14 01:27:00.870  1504  4462 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-14 01:27:00.870  1504  4462 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-14 01:27:00.870  1504  4462 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-14 01:27:00.870  1504  4462 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-14 01:27:00.870  1504  4462 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-14 01:27:00.870  1504  4462 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-14 01:27:00.873  4448  4448 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-14 01:27:00.875   873  1993 I ActivityManager: Start proc 4463:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
09-14 01:27:00.876  1504  4462 W SQLiteOpenHelper: Opened config.db in read-only mode
--------- beginning of crash
09-14 01:27:00.876  1961  2057 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-14 01:27:00.876  1961  2057 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1961
09-14 01:27:00.876  1961  2057 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-14 01:27:00.876  1961  2057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-14 01:27:00.876  1961  2057 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-14 01:27:00.876  1961  2057 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-14 01:27:00.876  1961  2057 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-14 01:27:00.876  1961  2057 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-14 01:27:00.876  1961  2057 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-14 01:27:00.876  1961  2057 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-14 01:27:00.876  1961  2057 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-14 01:27:00.876  1961  2057 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-14 01:27:00.876  1961  2057 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-14 01:27:00.876  1961  2057 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-14 01:27:00.878   873  2131 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-14 01:27:00.878   873  4468 E DropBoxManagerService: Can't write: system_app_crash
09-14 01:27:00.878   873  4468 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-14 01:27:00.878   873  4468 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-14 01:27:00.878   873  4468 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-14 01:27:00.878   873  4468 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-14 01:27:00.878   873  4468 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-14 01:27:00.878   873  4468 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-14 01:27:00.878   873  4468 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-14 01:27:00.878   873  4468 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-14 01:27:00.878   873  4468 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-14 01:27:00.878   873  4468 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-14 01:27:00.878   873  4468 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-14 01:27:00.878   873  4468 E DropBoxManagerService: 	... 5 more
09-14 01:27:00.880  1961  2057 I Process : Sending signal. PID: 1961 SIG: 9
09-14 01:27:00.911  1873  4444 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-14 01:27:00.932   873  1365 D GraphicsStats: Buffer count: 1
09-14 01:27:00.932   873   884 I WindowState: WIN DEATH: Window{e673b61 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-14 01:27:00.945  1873  4444 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-14 01:27:00.954   873  1365 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1961) has died
09-14 01:27:00.954   873  1365 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-14 01:27:00.956   873  1365 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-14 01:27:00.958  1873  4444 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-14 01:27:00.958  1873  4444 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-14 01:27:00.959  1873  4444 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-14 01:27:00.960  1873  4444 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-14 01:27:00.960  1873  4444 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-14 01:27:00.960  1873  4444 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-14 01:27:00.970  1873  4444 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-14 01:27:00.970  1873  4444 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-14 01:27:00.971  1873  4444 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-14 01:27:00.971  1873  4444 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-14 01:27:00.971  1873  4444 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-14 01:27:00.971  1873  4444 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-14 01:27:00.980   873   886 I ActivityManager: Start proc 4481:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-14 01:27:00.995  4448  4448 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 01:27:01.032  4481  4481 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 01:27:01.032  4481  4481 D AndroidRuntime: Shutting down VM
09-14 01:27:01.036   873  1687 I ActivityManager: Start proc 4495:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-14 01:27:01.051  4481  4481 E AndroidRuntime: FATAL EXCEPTION: main
09-14 01:27:01.051  4481  4481 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4481
09-14 01:27:01.051  4481  4481 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-14 01:27:01.051  4481  4481 E AndroidRuntime: 	... 10 more
09-14 01:27:01.056  1699  4494 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-14 01:27:01.057  1699  4494 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-14 01:27:01.061   873  2131 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-14 01:27:01.061   873  4506 E DropBoxManagerService: Can't write: system_app_crash
09-14 01:27:01.061   873  4506 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-14 01:27:01.061   873  4506 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-14 01:27:01.061   873  4506 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-14 01:27:01.061   873  4506 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-14 01:27:01.061   873  4506 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-14 01:27:01.061   873  4506 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-14 01:27:01.061   873  4506 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-14 01:27:01.061   873  4506 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-14 01:27:01.061   873  4506 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-14 01:27:01.061   873  4506 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-14 01:27:01.061   873  4506 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-14 01:27:01.061   873  4506 E DropBoxManagerService: 	... 5 more
09-14 01:27:01.061  4448  4500 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-14 01:27:01.062  4481  4481 I Process : Sending signal. PID: 4481 SIG: 9
09-14 01:27:01.072  1699  4494 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
09-14 01:27:01.073  1699  4494 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-14 01:27:01.077  4448  4479 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-14 01:27:01.078  4448  4479 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-14 01:27:01.090  4495  4495 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-14 01:27:01.098   873  2131 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4481) has died
09-14 01:27:01.099   873  2131 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-14 01:27:01.115   873   886 I ActivityManager: Start proc 4511:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-14 01:27:01.121   873  1970 I ActivityManager: Killing 3721:com.google.android.apps.docs/u0a46 (adj 15): empty #17
09-14 01:27:01.134  1504  1504 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-14 01:27:01.135  1504  1504 D AndroidRuntime: Shutting down VM
09-14 01:27:01.136  1504  1504 E AndroidRuntime: FATAL EXCEPTION: main
09-14 01:27:01.136  1504  1504 E AndroidRuntime: Process: com.google.process.gapps, PID: 1504
09-14 01:27:01.136  1504  1504 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-14 01:27:01.136  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-14 01:27:01.136  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-14 01:27:01.136  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-14 01:27:01.136  1504  1504 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 01:27:01.136  1504  1504 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-14 01:27:01.136  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-14 01:27:01.136  1504  1504 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-14 01:27:01.136  1504  1504 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-14 01:27:01.136  1504  1504 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-14 01:27:01.136  1504  1504 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-14 01:27:01.136  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-14 01:27:01.136  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-14 01:27:01.136  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-14 01:27:01.136  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-14 01:27:01.136  1504  1504 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-14 01:27:01.136  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-14 01:27:01.136  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-14 01:27:01.136  1504  1504 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-14 01:27:01.136  1504  1504 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-14 01:27:01.136  1504  1504 E AndroidRuntime: 	... 8 more
09-14 01:27:01.150  4448  4479 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-14 01:27:01.156  4448  4500 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-14 01:27:01.156  4448  4500 E AndroidRuntime: Process: android.process.acore, PID: 4448
09-14 01:27:01.156  4448  4500 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-14 01:27:01.156  4448  4500 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-14 01:27:01.157  4448  4479 I Process : Sending signal. PID: 4448 SIG: 9
09-14 01:27:01.193   873  4524 E DropBoxManagerService: Can't write: system_app_crash
09-14 01:27:01.193   873  4524 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-14 01:27:01.193   873  4524 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-14 01:27:01.193   873  4524 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-14 01:27:01.193   873  4524 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-14 01:27:01.193   873  4524 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-14 01:27:01.193   873  4524 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-14 01:27:01.193   873  4524 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-14 01:27:01.193   873  4524 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-14 01:27:01.193   873  4524 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-14 01:27:01.193   873  4524 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-14 01:27:01.193   873  4524 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-14 01:27:01.193   873  4524 E DropBoxManagerService: 	... 5 more
09-14 01:27:01.194   873  1687 I ActivityManager: Process android.process.acore (pid 4448) has died
09-14 01:27:01.194   873  1687 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
09-14 01:27:01.197   873  4525 E DropBoxManagerService: Can't write: system_app_crash
09-14 01:27:01.197   873  4525 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
09-14 01:27:01.197   873  4525 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-14 01:27:01.197   873  4525 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-14 01:27:01.197   873  4525 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-14 01:27:01.197   873  4525 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-14 01:27:01.197   873  4525 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-14 01:27:01.197   873  4525 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-14 01:27:01.197   873  4525 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-14 01:27:01.197   873  4525 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-14 01:27:01.197   873  4525 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-14 01:27:01.197   873  4525 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-14 01:27:01.197   873  4525 E DropBoxManagerService: 	... 5 more
09-14 01:27:01.197  1504  1504 I Process : Sending signal. PID: 1504 SIG: 9
09-14 01:27:01.217   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
