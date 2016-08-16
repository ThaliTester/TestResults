#### Test 80761374304f7b9_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-16 11:20:43.171   873  1315 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-16 11:20:43.839  3790  3790 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-16 11:20:43.844  3790  3790 D AndroidRuntime: CheckJNI is OFF
08-16 11:20:43.886  3790  3790 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-16 11:20:43.936  3790  3790 I Radio-JNI: register_android_hardware_Radio DONE
08-16 11:20:43.957  3790  3790 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 11:20:43.961   873  2019 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 11:20:44.003  2070  2087 W SearchService: Abort, client detached.
08-16 11:20:44.008  2070  2070 I HotwordDetector: Closing mic
08-16 11:20:44.009  2070  2326 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@7ab3452
08-16 11:20:44.009  2070  2348 E AudioRecord-JNI: Error -4 during AudioRecord native read
08-16 11:20:44.017  3790  3790 D AndroidRuntime: Shutting down VM
08-16 11:20:44.039   873  1946 I ActivityManager: Start proc 3799:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-16 11:20:44.057   377  2350 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
08-16 11:20:44.058   377  2350 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
08-16 11:20:44.062   377  1287 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
08-16 11:20:44.074  2070  2344 I MicroRecognitionRnrImpl: Detection finished
08-16 11:20:44.075  2070  2335 I MicroRecognitionRnrImpl: Stopping hotword detection.
08-16 11:20:44.141  3799  3799 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-16 11:20:44.163  3799  3799 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-16 11:20:44.170  3799  3799 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2816-2819)
08-16 11:20:44.171  3799  3799 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 11:20:44.183  3799  3799 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5d3ed31}
08-16 11:20:44.184  3799  3799 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 11:20:44.184  3799  3799 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 11:20:44.190  3799  3799 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-16 11:20:44.192  3799  3799 E SysUtils: ApplicationContext is null in ApplicationStatus
08-16 11:20:44.206  3799  3799 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-16 11:20:44.216  3799  3799 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 11:20:44.217  3799  3799 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 11:20:44.217  3799  3799 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 11:20:44.217  3799  3799 I Adreno  : Build Date                       : 10/20/15
08-16 11:20:44.217  3799  3799 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 11:20:44.217  3799  3799 I Adreno  : Local Branch                     : M14
08-16 11:20:44.217  3799  3799 I Adreno  : Remote Branch                    : 
08-16 11:20:44.217  3799  3799 I Adreno  : Remote Branch                    : 
08-16 11:20:44.217  3799  3799 I Adreno  : Reconstruct Branch               : 
,08-16 11:20:44.275   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@59cbd06:true
,08-16 11:20:44.319  3799  3799 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-16 11:20:44.332  3799  3799 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-16 11:20:44.390  3799  3838 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-16 11:20:44.408  3799  3824 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-16 11:20:44.457  3799  3838 I OpenGLRenderer: Initialized EGL, version 1.4
,08-16 11:20:44.513   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +496ms
,08-16 11:20:44.525  1886  1886 I Keyboard.Facilitator: onFinishInput()
,08-16 11:20:44.602  3799  3799 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3799
,08-16 11:20:44.723  3799  3799 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 11:20:44.862  3799  3841 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1678313168
,08-16 11:20:44.866   873  1626 I ActivityManager: Killing 2972:com.google.android.calendar/u0a37 (adj 15): empty #17
08-16 11:20:44.868  3799  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 11:20:44.868  3799  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 11:20:44.868  3799  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 11:20:44.868  3799  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 11:20:44.868  3799  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-16 11:20:44.869  3799  3841 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4cbbdc added. We now have 1 listener(s)
,08-16 11:20:44.872  3799  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-16 11:20:44.873  3799  3841 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 11:20:44.874  3799  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 11:20:44.874  3799  3841 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 11:20:44.877  3799  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 11:20:44.877  3799  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 11:20:44.877  3799  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 11:20:44.877  3799  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-16 11:20:44.877  3799  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 11:20:44.877  3799  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 11:20:44.877  3799  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 11:20:44.877  3799  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 11:20:44.877  3799  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 11:20:44.877  3799  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 11:20:44.877  3799  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 11:20:44.877  3799  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 11:20:44.877  3799  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 11:20:44.877  3799  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-16 11:20:44.877  3799  3841 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a68a6b added. We now have 1 listener(s)
08-16 11:20:44.877  3799  3841 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 11:20:44.879   873  1317 D WifiService: New client listening to asynchronous messages
08-16 11:20:44.881  3799  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 11:20:44.881  3799  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 11:20:44.881  3799  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 11:20:44.881  3799  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 11:20:44.881  3799  3841 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-16 11:20:44.910   873  1626 I ActivityManager: Killing 3207:com.google.android.gm/u0a78 (adj 15): empty #18
,08-16 11:20:44.942  3799  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 11:20:44.942  3799  3841 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-16 11:20:44.948  3799  3841 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-16 11:20:44.948  3799  3841 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:20:44.948  3799  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:20:44.948  3799  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:20:44.948  3799  3841 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:20:44.948  3799  3841 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:20:44.948  3799  3841 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:20:44.948  3799  3841 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:20:44.948  3799  3841 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:20:44.948  3799  3841 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 11:20:44.948  3799  3841 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 11:20:44.949  3799  3841 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 11:20:44.952  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:20:44.954  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:20:45.101  3799  3799 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 11:20:46.067  3799  3850 W jxcore-log: Initializing JXcore engine
,08-16 11:20:46.067  3799  3850 W jxcore-log: JXcore engine is ready
,08-16 11:20:46.136  3850  3850 W Thread-329: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8950 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-16 11:20:46.136  3850  3850 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13228]" dev="sockfs" ino=13228 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-16 11:20:46.136  3850  3850 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-16 11:20:46.136  3850  3850 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27117]" dev="sockfs" ino=27117 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-16 11:20:46.152  3799  3850 W jxcore-log: Starting JXcore engine
,08-16 11:20:46.247  3799  3850 W jxcore-log: Platform android
08-16 11:20:46.247  3799  3850 W jxcore-log: 
,08-16 11:20:46.247  3799  3850 W jxcore-log: Process ARCH arm
08-16 11:20:46.247  3799  3850 W jxcore-log: 
,08-16 11:20:46.537  3799  3850 I jxcore-log: JXcore Cordova bridge is ready!
08-16 11:20:46.537  3799  3850 I jxcore-log: 
08-16 11:20:46.537  3799  3850 W jxcore-log: JXcore engine is started
,08-16 11:20:46.547  3799  3841 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 11:20:46.552  3799  3799 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 11:20:51.605  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:20:51.611  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:20:51.645  1516  1912 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 11:20:51.645  1516  1912 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 11:20:51.645  1516  1912 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 11:20:51.645  1516  1912 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:20:51.693  3545  3860 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 11:20:51.693  3545  3860 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 11:20:51.693  3545  3860 E HttpOperation: 	at jdm.a(PG:82)
08-16 11:20:51.693  3545  3860 E HttpOperation: 	at jcs.o(PG:406)
08-16 11:20:51.693  3545  3860 E HttpOperation: 	at jcn.a(PG:1379)
08-16 11:20:51.693  3545  3860 E HttpOperation: 	at jcs.i(PG:143)
08-16 11:20:51.693  3545  3860 E HttpOperation: 	at blb.a(PG:3937)
08-16 11:20:51.693  3545  3860 E HttpOperation: 	at czp.a(PG:18188)
08-16 11:20:51.693  3545  3860 E HttpOperation: 	at czp.a(PG:9081)
08-16 11:20:51.693  3545  3860 E HttpOperation: 	at czq.run(PG:1686)
08-16 11:20:51.693  3545  3860 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 11:20:51.693  3545  3860 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 11:20:51.693  3545  3860 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 11:20:51.693  3545  3860 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 11:20:51.693  3545  3860 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 11:20:51.693  3545  3860 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 11:20:51.693  3545  3860 E HttpOperation: 	at jdj.a(PG:4091)
08-16 11:20:51.693  3545  3860 E HttpOperation: 	at jdj.a(PG:1125)
08-16 11:20:51.693  3545  3860 E HttpOperation: 	at jdm.a(PG:77)
08-16 11:20:51.693  3545  3860 E HttpOperation: 	... 12 more
08-16 11:20:51.693  3545  3860 E HttpOperation: Caused by: faj: BadAuthentication
08-16 11:20:51.693  3545  3860 E HttpOperation: 	at fal.a(PG:38)
08-16 11:20:51.693  3545  3860 E HttpOperation: 	at jdj.a(PG:4089)
08-16 11:20:51.693  3545  3860 E HttpOperation: 	... 14 more
,08-16 11:20:51.756  1516  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-16 11:20:51.756  1516  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 11:20:51.756  1516  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 11:20:51.756  1516  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:20:51.800  3545  3860 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 11:20:51.800  3545  3860 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 11:20:51.800  3545  3860 E HttpOperation: 	at jdm.a(PG:82)
08-16 11:20:51.800  3545  3860 E HttpOperation: 	at jcs.o(PG:406)
08-16 11:20:51.800  3545  3860 E HttpOperation: 	at jcn.a(PG:1379)
08-16 11:20:51.800  3545  3860 E HttpOperation: 	at jcs.i(PG:143)
08-16 11:20:51.800  3545  3860 E HttpOperation: 	at hec.a(PG:42)
08-16 11:20:51.800  3545  3860 E HttpOperation: 	at hee.a(PG:102)
08-16 11:20:51.800  3545  3860 E HttpOperation: 	at czr.a(PG:65)
08-16 11:20:51.800  3545  3860 E HttpOperation: 	at kka.a(PG:108)
08-16 11:20:51.800  3545  3860 E HttpOperation: 	at czp.a(PG:19176)
08-16 11:20:51.800  3545  3860 E HttpOperation: 	at czp.a(PG:9081)
08-16 11:20:51.800  3545  3860 E HttpOperation: 	at czq.run(PG:1686)
08-16 11:20:51.800  3545  3860 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 11:20:51.800  3545  3860 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 11:20:51.800  3545  3860 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 11:20:51.800  3545  3860 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 11:20:51.800  3545  3860 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 11:20:51.800  3545  3860 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 11:20:51.800  3545  3860 E HttpOperation: 	at jdj.a(PG:4091)
08-16 11:20:51.800  3545  3860 E HttpOperation: 	at jdj.a(PG:1125)
08-16 11:20:51.800  3545  3860 E HttpOperation: 	at jdm.a(PG:77)
08-16 11:20:51.800  3545  3860 E HttpOperation: 	... 15 more
08-16 11:20:51.800  3545  3860 E HttpOperation: Caused by: faj: BadAuthentication
08-16 11:20:51.800  3545  3860 E HttpOperation: 	at fal.a(PG:38)
08-16 11:20:51.800  3545  3860 E HttpOperation: 	at jdj.a(PG:4089)
08-16 11:20:51.800  3545  3860 E HttpOperation: 	... 17 more
,08-16 11:20:51.800  3545  3860 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 11:20:51.800  3545  3860 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	at hec.a(PG:42)
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	at hee.a(PG:102)
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	at czr.a(PG:65)
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	at kka.a(PG:108)
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 11:20:51.800  3545  3860 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
,08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	... 15 more
08-16 11:20:51.800  3545  3860 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	at fal.a(PG:38)
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 11:20:51.800  3545  3860 E ExperimentLoader: 	... 17 more
,08-16 11:20:51.884   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 130108, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-16 11:20:51.919  3605  3862 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 11:20:51.931  3605  3863 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 11:20:51.957  1516  2435 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 11:20:51.957  1516  2435 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 11:20:51.957  1516  2435 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 11:20:51.957  1516  2435 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:20:52.006  1516  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 11:20:52.006  1516  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-16 11:20:52.006  1516  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 11:20:52.007  1516  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:20:52.024  3605  3863 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 11:20:52.024  3605  3862 E BooksSync: Soft error
08-16 11:20:52.024  3605  3862 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 11:20:52.024  3605  3862 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 11:20:52.025  3605  3862 E BooksSync: Sync error
08-16 11:20:52.025  3605  3862 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 11:20:52.025  3605  3862 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 11:20:52.025  3605  3862 I BooksSync: Finished books sync
,08-16 11:20:52.031   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 130506, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 11:20:54.196   873  2019 I ActivityManager: Start proc 3866:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,08-16 11:20:54.224   873  2052 I ActivityManager: Start proc 3878:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,08-16 11:20:54.243  3866  3866 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,08-16 11:20:54.257  3878  3878 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,08-16 11:20:54.288  3878  3878 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-16 11:20:54.306  3866  3892 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-16 11:20:54.333  3878  3907 V GoogleAuthProtoRequest: [325] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 11:20:54.372  3866  3892 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,08-16 11:20:54.381  1516  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-16 11:20:54.381  1516  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-16 11:20:54.381  1516  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 11:20:54.381  1516  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:20:54.406  3866  3892 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-16 11:20:54.407  3878  3907 W ExperimentUpdateService: [325] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
08-16 11:20:54.407  3878  3907 W ExperimentUpdateService: [325] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 11:20:54.407  3878  3907 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 11:20:54.407  3878  3907 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-16 11:20:54.407  3878  3907 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-16 11:20:54.407  3878  3907 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-16 11:20:54.407  3878  3907 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-16 11:20:54.407  3878  3907 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-16 11:20:54.407  3878  3907 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-16 11:20:54.407  3878  3907 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-16 11:20:54.407  3878  3907 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-16 11:20:54.407  3878  3907 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-16 11:20:54.458  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:20:54.459  3866  3866 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,08-16 11:20:54.483  1516  2189 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 11:20:54.483  1516  2189 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 11:20:54.483  1516  2189 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 11:20:54.483  1516  2189 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION,
,08-16 11:20:54.499  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 11:20:54.499  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 11:20:54.500  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
,08-16 11:20:54.537  3933  3933 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads28666611.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads28666611.dex
,08-16 11:20:54.567  3933  3933 I dex2oat : dex2oat took 31.477ms (threads: 4) arena alloc=103KB java alloc=41KB native alloc=1515KB free=1812KB
,08-16 11:20:54.603  3866  3866 W InstanceID/Rpc: Found 10011
,08-16 11:20:54.652   873  1946 I ActivityManager: Killing 3557:com.google.process.gapps/u0a99 (adj 15): empty #17
,08-16 11:20:54.683   873  1946 I ActivityManager: Killing 2277:com.google.android.talk/u0a61 (adj 15): empty #18
,08-16 11:20:54.768  1516  3975 I VacuumService: Vacuum at: now=1471339254768 tag=VacuumService
,08-16 11:20:54.870  1516  3976 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,08-16 11:20:54.872  1516  3976 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-16 11:20:55.215  1516  3976 W Uploader:  no longer exists, so no auth token.
,08-16 11:20:55.856  1516  3976 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-16 11:20:55.856  1516  3976 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
,08-16 11:20:55.857  1516  3976 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 11:20:55.857  1516  3976 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:20:55.883  1516  3976 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 11:20:55.883  1516  3976 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 11:20:55.883  1516  3976 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 11:20:55.883  1516  3976 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 11:20:55.883  1516  3976 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-16 11:20:55.883  1516  3976 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-16 11:20:55.883  1516  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-16 11:20:55.883  1516  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-16 11:20:55.883  1516  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-16 11:20:55.883  1516  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-16 11:20:55.883  1516  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-16 11:20:55.883  1516  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-16 11:20:55.883  1516  3976 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-16 11:20:56.147  1516  3976 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-16 11:20:56.147  1516  3976 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-16 11:20:56.148  1516  3976 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 11:20:56.148  1516  3976 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:20:56.189  1516  3976 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 11:20:56.189  1516  3976 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 11:20:56.189  1516  3976 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 11:20:56.189  1516  3976 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 11:20:56.189  1516  3976 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-16 11:20:56.189  1516  3976 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-16 11:20:56.189  1516  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-16 11:20:56.189  1516  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-16 11:20:56.189  1516  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-16 11:20:56.189  1516  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-16 11:20:56.189  1516  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-16 11:20:56.189  1516  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-16 11:20:56.189  1516  3976 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-16 11:20:56.672  1516  3976 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog
,08-16 11:20:56.673  1516  3976 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud.
08-16 11:20:56.673  1516  3976 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 11:20:56.673  1516  3976 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:20:56.714  1516  3976 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.
08-16 11:20:56.714  1516  3976 E Uploader: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-16 11:20:56.714  1516  3976 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-16 11:20:56.714  1516  3976 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-16 11:20:56.714  1516  3976 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:588)
08-16 11:20:56.714  1516  3976 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:515)
08-16 11:20:56.714  1516  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:622)
08-16 11:20:56.714  1516  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:414)
08-16 11:20:56.714  1516  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:332)
08-16 11:20:56.714  1516  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.i.a(SourceFile:264)
08-16 11:20:56.714  1516  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:100)
08-16 11:20:56.714  1516  3976 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:68)
08-16 11:20:56.714  1516  3976 E Uploader: 	at com.google.android.gms.gcm.al.run(SourceFile:135)
,08-16 11:20:59.668   873  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=138317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 11:21:03.049  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 11:21:03.049  3799  3850 I jxcore-log: 
,08-16 11:21:03.052  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 11:21:03.052  3799  3850 I jxcore-log: 
,08-16 11:21:03.064  3799  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:21:03.064  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:03.064  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:03.064  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:21:03.064  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:21:03.064  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:21:03.064  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:21:03.064  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:21:03.067  3799  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 11:21:03.069  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 11:21:03.069  3799  3850 I jxcore-log: 
,08-16 11:21:03.071  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 11:21:03.071  3799  3850 I jxcore-log: 
,08-16 11:21:03.175   873  1315 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2447
,08-16 11:21:03.419  3799  3850 I jxcore-log: Running unit tests
08-16 11:21:03.419  3799  3850 I jxcore-log: 
,08-16 11:21:03.420  3799  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 11:21:03.420  3799  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48da017 added. We now have 2 listener(s)
,08-16 11:21:03.421  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 11:21:03.421  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 11:21:03.421  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 11:21:03.421  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 11:21:03.421  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fde5c04 added. We now have 2 listener(s)
,08-16 11:21:03.421  3799  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 11:21:03.422  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 11:21:03.424  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 11:21:03.430  3799  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:21:03.430  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:03.430  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:03.430  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:21:03.430  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:21:03.430  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:21:03.430  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:21:03.430  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:21:03.431  3799  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 11:21:03.432  3799  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 11:21:03.432  3799  3850 D ExecuteNativeTests: Running unit tests
,08-16 11:21:03.438  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:21:03.443  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:21:05.967  1516  2199 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-16 11:21:08.492  3799  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 11:21:08.492  3799  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 added. We now have 3 listener(s)
,08-16 11:21:08.499  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 11:21:08.500  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 11:21:08.500  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 11:21:08.502  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 11:21:08.503  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 added. We now have 3 listener(s)
,08-16 11:21:08.504  3799  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 11:21:08.505  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 11:21:08.514  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 11:21:08.524  3799  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:21:08.524  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:08.524  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:08.524  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:21:08.524  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:21:08.524  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:21:08.524  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:21:08.524  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:21:08.526  3799  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:21:08.526  3799  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 11:21:08.530  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 11:21:08.532  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:21:08.532  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 11:21:08.532  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 11:21:08.532  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 11:21:08.534  3799  3850 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-16 11:21:08.535  3799  3850 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-16 11:21:08.535  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-16 11:21:08.535  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 11:21:08.535  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 11:21:08.535  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 11:21:08.535  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 11:21:08.536  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 11:21:08.536  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:21:08.536  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 11:21:08.537  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:08.537  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 11:21:08.537  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 11:21:08.537  3799  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 removed from the list
08-16 11:21:08.537  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:08.537  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 removed from the list
08-16 11:21:08.542  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:21:08.542  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:21:08.542  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:08.543  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:08.543  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:08.544  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:21:08.544  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:21:08.544  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:08.544  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:08.549  3799  3850 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 11:21:08.549  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:21:08.549  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 11:21:08.549  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:21:08.550  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:21:08.551  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:08.551  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:08.551  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
08-16 11:21:08.551  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:08.551  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:08.552  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:21:08.552  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:08.552  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:08.552  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:08.552  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:08.553  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:21:08.553  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:21:08.554  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:08.554  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:08.560  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 11:21:08.560  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 11:21:08.560  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 11:21:08.561  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 11:21:08.561  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 11:21:08.561  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 11:21:08.561  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 11:21:08.561  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 11:21:08.561  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 11:21:08.561  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 11:21:08.561  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 11:21:08.561  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 11:21:08.561  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 11:21:08.561  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 11:21:08.562  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 11:21:08.562  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 11:21:08.562  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 11:21:08.562  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 11:21:08.562  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 11:21:08.562  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 11:21:08.562  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 11:21:08.562  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 11:21:08.562  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 11:21:08.562  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 11:21:08.562  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 11:21:08.562  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 11:21:08.563  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 11:21:08.563  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 11:21:08.563  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 11:21:08.563  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 11:21:08.563  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 11:21:08.563  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:21:08.563  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:21:08.563  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:21:08.563  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:21:08.563  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:08.564  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:08.564  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
08-16 11:21:08.564  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:08.564  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:08.564  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:21:08.564  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:08.564  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:08.564  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:08.564  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:08.566  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:21:08.566  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:21:08.566  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:08.566  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:08.567  3799  3850 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 11:21:08.570  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:21:08.575  3799  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:21:08.575  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:08.575  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:08.575  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:21:08.575  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:21:08.575  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:21:08.575  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:21:08.575  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:21:08.579  3799  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:21:08.579  3799  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 11:21:08.579  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 11:21:08.579  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 11:21:08.580  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 11:21:08.580  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:21:08.580  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 11:21:08.585  3799  3850 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 11:21:08.585  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 11:21:08.585  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:21:08.594  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:21:08.596  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 11:21:08.598  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 11:21:08.598  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 11:21:08.603  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-16 11:21:08.606  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-16 11:21:08.606  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 11:21:08.607  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 11:21:08.607  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 11:21:08.609  3799  3850 D BluetoothAdapter: STATE_ON
08-16 11:21:08.613  2702  2716 D BtGatt.GattService: registerClient() - UUID=ca436a28-dc1d-416f-bcb0-753bc8809c5a
08-16 11:21:08.616  2702  2752 D BtGatt.GattService: onClientRegistered() - UUID=ca436a28-dc1d-416f-bcb0-753bc8809c5a, clientIf=5
08-16 11:21:08.619  3799  3811 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 11:21:08.621  2702  2894 D BtGatt.GattService: start scan with filters
08-16 11:21:08.628  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 11:21:08.628  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 11:21:08.628  2702  2755 D BtGatt.ScanManager: handling starting scan
08-16 11:21:08.628  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 11:21:08.629  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 11:21:08.633  2702  2755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf87833
,08-16 11:21:08.634  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
,08-16 11:21:08.635  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 11:21:08.635  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 11:21:08.639  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 11:21:08.643  2702  2752 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 11:21:08.643  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:21:08.644  2702  2755 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-16 11:21:08.649  3799  3850 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 11:21:08.655  2702  2752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 11:21:08.655  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:21:08.655  2702  2755 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 11:21:08.656  2702  2755 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 11:21:08.680  2702  2752 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 11:21:08.680  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:21:08.696  2702  2752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 11:21:08.697  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:21:09.137  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
08-16 11:21:09.138  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 11:21:09.138  3799  3799 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 11:21:10.201  2702  2702 D BtGatt.ScanManager: awakened up at time 148850
08-16 11:21:10.203  2702  2755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 11:21:10.255  2702  2752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
08-16 11:21:10.256  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:21:10.256  2702  2752 D BtGatt.GattService: current time is 148905659529
,08-16 11:21:10.258  2702  2752 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -85, 27, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -83, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -90, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -89, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -83, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 11:21:10.262  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 11:21:10.265  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 11:21:10.265  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 11:21:10.266  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 11:21:10.267  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 11:21:11.288   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,08-16 11:21:11.301  1886  1886 I Keyboard.Facilitator: onFinishInput()
,08-16 11:21:11.317   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 11:21:11.317   873   893 I Adreno  : Build Date                       : 10/20/15
08-16 11:21:11.317   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 11:21:11.317   873   893 I Adreno  : Local Branch                     : M14
08-16 11:21:11.317   873   893 I Adreno  : Remote Branch                    : 
08-16 11:21:11.317   873   893 I Adreno  : Remote Branch                    : 
08-16 11:21:11.317   873   893 I Adreno  : Reconstruct Branch               : 
,08-16 11:21:11.357   282   305 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (199 us)
,08-16 11:21:11.758  2702  2702 D BtGatt.ScanManager: awakened up at time 150407
,08-16 11:21:11.761  2702  2755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 11:21:11.790  2702  2752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-16 11:21:11.790  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 11:21:11.792  2702  2752 D BtGatt.GattService: current time is 150440952964
08-16 11:21:11.792  2702  2752 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -83, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -95, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -82, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 11:21:11.793  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 11:21:11.794  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 11:21:11.794  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 11:21:12.001  3799  3799 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 11:21:12.001  3799  3799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-16 11:21:12.041   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,08-16 11:21:12.043  3799  3799 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b8648f Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@50dafcc, 16908290=android.view.AbsSavedState$1@50dafcc}, android:focusedViewId=100}]}]
,08-16 11:21:12.044  3799  3799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-16 11:21:12.045  3799  3799 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 11:21:12.045  3799  3799 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
08-16 11:21:12.048   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,08-16 11:21:12.054   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
,08-16 11:21:12.055   282   282 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
08-16 11:21:12.055   282   282 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,08-16 11:21:12.306   282   338 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-16 11:21:12.309   282   282 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,08-16 11:21:12.314   873  1343 D SurfaceControl: Excessive delay in setPowerMode(): 261ms
,08-16 11:21:12.317   873   893 I DreamManagerService: Entering dreamland.
,08-16 11:21:12.318   873   893 I PowerManagerService: Dozing...,
,08-16 11:21:12.320   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,08-16 11:21:12.372   377  1325 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
08-16 11:21:12.373   377  1325 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,08-16 11:21:12.379  2702  2702 D BtGatt.ScanManager: awakened up at time 151028
,08-16 11:21:12.381  2702  2755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 11:21:12.383   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 11:21:12.406   873  1315 E native  : do suspend false
,08-16 11:21:12.407  1985  3990 D NfcService: Discovery configuration equal, not updating.
,08-16 11:21:12.416  2702  2752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-16 11:21:12.416  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:21:12.416  2702  2752 D BtGatt.GattService: current time is 151065641411
,08-16 11:21:12.417  2702  2752 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -89, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -79, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -82, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -95, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -82, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 0]
,08-16 11:21:12.418  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 11:21:12.418  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-16 11:21:12.419  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-16 11:21:12.419  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 11:21:12.420  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74]
,08-16 11:21:12.427   873  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 11:21:12.446   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 11:21:12.459   873  1315 E native  : do suspend true
,08-16 11:21:12.505   377  1288 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,08-16 11:21:12.506   377  1288 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,08-16 11:21:12.889   873  1315 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 12, 13 -> obsolete
,08-16 11:21:13.659  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 11:21:13.660  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 11:21:13.660  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 11:21:13.660  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 11:21:13.661  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 11:21:13.661  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 11:21:13.661  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 11:21:13.662  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 11:21:13.662  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 11:21:13.664  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 11:21:13.664  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 11:21:13.667  3799  3850 D BluetoothAdapter: STATE_ON
08-16 11:21:13.669  2702  2894 D BtGatt.GattService: stopScan() - queue size =1
,08-16 11:21:13.671  2702  2715 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 11:21:13.674  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:21:13.674  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 11:21:13.674  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-16 11:21:13.675  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 11:21:13.675  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 11:21:13.679  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 11:21:13.680  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 11:21:13.683  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 11:21:13.683  2702  2702 D BtGatt.ScanManager: awakened up at time 152332
08-16 11:21:13.683  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 11:21:13.688  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 11:21:13.691  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 11:21:13.691  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 11:21:13.692  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:13.692  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
08-16 11:21:13.692  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 11:21:13.692  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
08-16 11:21:13.692  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 11:21:13.692  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:21:13.693  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:13.693  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:21:13.693  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:13.693  2702  2752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-16 11:21:13.693  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 11:21:13.694  2702  2755 D BtGatt.ScanManager: stopping BLe Batch
,08-16 11:21:13.708  2702  2752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 11:21:13.708  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 11:21:13.708  2702  2755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 11:21:13.715  2702  2752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 11:21:13.716  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:21:14.193  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 11:21:14.362   873  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=153010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 11:21:16.732  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:21:16.752  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:21:16.759  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:21:16.843  1516  2435 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 11:21:16.843  1516  2435 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-16 11:21:16.843  1516  2435 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 11:21:16.844  1516  2435 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:21:16.901  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 11:21:16.902  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 11:21:16.903  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,08-16 11:21:17.071  1853  2636 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-16 11:21:18.694  3799  3850 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 11:21:18.701  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 11:21:18.716  3799  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:21:18.716  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:18.716  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:18.716  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:21:18.716  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:21:18.716  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:21:18.716  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:21:18.716  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:21:18.724  3799  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 11:21:18.725  3799  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 11:21:18.726  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 11:21:18.727  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-16 11:21:18.727  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 11:21:18.727  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:21:18.728  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 11:21:18.734  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:21:18.738  3799  3850 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 11:21:18.738  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 11:21:18.742  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:21:18.751  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 11:21:18.753  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 11:21:18.754  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 11:21:18.765  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 11:21:18.765  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 11:21:18.766  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 11:21:18.768  3799  3850 D BluetoothAdapter: STATE_ON
,08-16 11:21:18.775  2702  2716 D BtGatt.GattService: registerClient() - UUID=d7c89334-545a-4d99-9661-ef1ee6d908f0
,08-16 11:21:18.777  2702  2752 D BtGatt.GattService: onClientRegistered() - UUID=d7c89334-545a-4d99-9661-ef1ee6d908f0, clientIf=5
08-16 11:21:18.778  3799  3809 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 11:21:18.779  2702  2893 D BtGatt.GattService: start scan with filters
,08-16 11:21:18.789  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 11:21:18.789  2702  2755 D BtGatt.ScanManager: handling starting scan
08-16 11:21:18.789  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 11:21:18.789  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 11:21:18.790  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 11:21:18.799  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 11:21:18.801  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 11:21:18.801  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 11:21:18.806  2702  2752 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 11:21:18.807  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 11:21:18.808  2702  2755 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 11:21:18.809  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 11:21:18.821  3799  3850 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 11:21:18.828  2702  2752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 11:21:18.829  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 11:21:18.829  2702  2755 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 11:21:18.830  2702  2755 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 11:21:18.830  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:21:18.830  3799  3850 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-16 11:21:18.831  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 11:21:18.831  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 11:21:18.832  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:18.832  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 11:21:18.832  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 11:21:18.832  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 11:21:18.833  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 11:21:18.833  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 11:21:18.834  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 11:21:18.834  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 11:21:18.837  3799  3850 D BluetoothAdapter: STATE_ON
,08-16 11:21:18.839  2702  2885 D BtGatt.GattService: stopScan() - queue size =1
,08-16 11:21:18.842  2702  2893 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 11:21:18.843  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:21:18.843  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 11:21:18.844  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 11:21:18.844  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 11:21:18.844  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 11:21:18.847  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 11:21:18.848  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 11:21:18.848  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 11:21:18.848  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 11:21:18.850  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 11:21:18.853  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 11:21:18.854  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 11:21:18.854  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 11:21:18.855  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:21:18.855  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:18.855  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 11:21:18.855  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
,08-16 11:21:18.856  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:18.856  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:18.856  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:21:18.856  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:21:18.857  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:18.857  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:21:18.859  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 11:21:18.859  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:21:18.859  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:21:18.859  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
,08-16 11:21:18.860  3799  3850 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 11:21:18.863  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 11:21:18.868  2702  2752 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 11:21:18.868  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 11:21:18.869  3799  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:21:18.869  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:18.869  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:18.869  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:21:18.869  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:21:18.869  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:21:18.869  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:21:18.869  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:21:18.872  3799  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 11:21:18.872  3799  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 11:21:18.874  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 11:21:18.874  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 11:21:18.874  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 11:21:18.874  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:21:18.875  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 11:21:18.877  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:21:18.878  2702  2752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 11:21:18.878  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:21:18.879  3799  3850 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 11:21:18.879  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 11:21:18.880  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:21:18.884  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 11:21:18.886  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 11:21:18.886  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 11:21:18.887  2702  2752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 11:21:18.887  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 11:21:18.888  2702  2755 D BtGatt.ScanManager: stopping BLe Batch
,08-16 11:21:18.892  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 11:21:18.892  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 11:21:18.892  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-16 11:21:18.893  3799  3850 D BluetoothAdapter: STATE_ON
,08-16 11:21:18.895  2702  2752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 11:21:18.895  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 11:21:18.895  2702  2755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 11:21:18.897  2702  2893 D BtGatt.GattService: registerClient() - UUID=2e1c27b4-e7f3-49d0-9bd7-b66223c9087a
,08-16 11:21:18.898  2702  2752 D BtGatt.GattService: onClientRegistered() - UUID=2e1c27b4-e7f3-49d0-9bd7-b66223c9087a, clientIf=5
,08-16 11:21:18.899  3799  3809 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 11:21:18.899  2702  2716 D BtGatt.GattService: start scan with filters
,08-16 11:21:18.901  2702  2752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 11:21:18.902  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:21:18.904  2702  2755 D BtGatt.ScanManager: handling starting scan
08-16 11:21:18.904  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 11:21:18.904  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 11:21:18.904  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-16 11:21:18.905  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 11:21:18.910  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 11:21:18.910  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-16 11:21:18.911  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 11:21:18.914  2702  2752 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 11:21:18.914  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 11:21:18.915  2702  2755 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 11:21:18.915  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,08-16 11:21:18.921  3799  3850 I io.jxcore.node.ConnectionHelper: start: OK
,08-16 11:21:18.921  2702  2752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 11:21:18.922  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 11:21:18.922  2702  2755 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 11:21:18.922  2702  2755 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 11:21:18.933  2702  2752 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 11:21:18.933  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:21:18.940  2702  2752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 11:21:18.940  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:21:19.412  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-16 11:21:19.412  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 11:21:19.413  3799  3799 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 11:21:20.447  2702  2702 D BtGatt.ScanManager: awakened up at time 159096
,08-16 11:21:20.452  2702  2755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 11:21:20.499  2702  2752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
,08-16 11:21:20.499  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:21:20.500  2702  2752 D BtGatt.GattService: current time is 159149265627
,08-16 11:21:20.501  2702  2752 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -86, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -84, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -91, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -80, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -85, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-16 11:21:20.502  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 11:21:20.503  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 11:21:20.504  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-16 11:21:20.505  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 11:21:20.506  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 11:21:22.002  2702  2702 D BtGatt.ScanManager: awakened up at time 160650
,08-16 11:21:22.004  2702  2755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 11:21:22.051  2702  2752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=5
08-16 11:21:22.051  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:21:22.052  2702  2752 D BtGatt.GattService: current time is 160700904819
,08-16 11:21:22.052  2702  2752 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -65, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -97, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -82, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -96, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -89, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
08-16 11:21:22.055  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-16 11:21:22.055  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-16 11:21:22.056  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 11:21:22.057  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-16 11:21:22.058  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 11:21:22.155  3137  3995 V KeepSync: Connecting to GoogleApiClient
,08-16 11:21:22.156   873  2052 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 11:21:22.232  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:21:22.235  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:21:22.267  1516  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-16 11:21:22.267  1516  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-16 11:21:22.267  1516  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 11:21:22.268  1516  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:21:22.294  1718  3996 V BaseAuthAsyncOperation: access token request failed
,08-16 11:21:22.295  3137  3995 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-16 11:21:22.365  1516  1912 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-16 11:21:22.365  1516  1912 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-16 11:21:22.365  1516  1912 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 11:21:22.365  1516  1912 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:21:22.390  3137  3995 E KeepSync: IOException
08-16 11:21:22.390  3137  3995 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 11:21:22.390  3137  3995 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 11:21:22.390  3137  3995 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 11:21:22.390  3137  3995 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 11:21:22.390  3137  3995 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 11:21:22.390  3137  3995 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 11:21:22.390  3137  3995 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 11:21:22.390  3137  3995 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 11:21:22.390  3137  3995 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 11:21:22.390  3137  3995 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 11:21:22.390  3137  3995 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 11:21:22.390  3137  3995 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 11:21:22.390  3137  3995 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 11:21:22.390  3137  3995 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 11:21:22.390  3137  3995 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 11:21:22.390  3137  3995 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 11:21:22.390  3137  3995 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 11:21:22.390  3137  3995 E KeepSync: 	... 10 more
,08-16 11:21:22.390  3137  3995 W KeepSync: Sync result 2
,08-16 11:21:22.403   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 130933, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 11:21:22.555  2702  2702 D BtGatt.ScanManager: awakened up at time 161204
,08-16 11:21:22.559  2702  2755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 11:21:22.601  2702  2752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,08-16 11:21:22.601  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:21:22.602  2702  2752 D BtGatt.GattService: current time is 161251212947
08-16 11:21:22.603  2702  2752 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -83, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -97, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -83, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 11:21:22.603  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 11:21:22.604  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-16 11:21:22.605  2702  2752 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 11:21:23.185   873  1315 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 13 -> obsolete
,08-16 11:21:23.922  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 11:21:23.922  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 11:21:23.923  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 11:21:23.923  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:23.923  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-16 11:21:23.923  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-16 11:21:23.924  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 11:21:23.924  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 11:21:23.924  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 11:21:23.925  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-16 11:21:23.926  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 11:21:23.928  3799  3850 D BluetoothAdapter: STATE_ON
08-16 11:21:23.930  2702  2885 D BtGatt.GattService: stopScan() - queue size =1
08-16 11:21:23.933  2702  2893 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 11:21:23.934  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 11:21:23.935  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-16 11:21:23.935  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 11:21:23.935  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-16 11:21:23.936  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 11:21:23.939  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 11:21:23.940  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 11:21:23.940  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 11:21:23.940  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 11:21:23.942  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 11:21:23.943  2702  2702 D BtGatt.ScanManager: awakened up at time 162592
,08-16 11:21:23.946  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 11:21:23.946  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 11:21:23.946  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 11:21:23.946  2702  2752 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 11:21:23.947  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:21:23.947  2702  2755 D BtGatt.ScanManager: stopping BLe Batch
,08-16 11:21:23.954  2702  2752 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 11:21:23.954  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:21:23.954  2702  2755 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 11:21:23.962  2702  2752 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 11:21:23.962  2702  2752 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:21:24.447  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 11:21:24.448  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 11:21:24.448  3799  3799 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 11:21:28.948  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:21:28.949  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 11:21:28.949  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 11:21:28.950  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:21:28.950  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:28.951  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 11:21:28.951  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
,08-16 11:21:28.951  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:28.952  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
,08-16 11:21:28.952  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:21:28.952  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:28.954  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 11:21:28.954  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:28.958  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 11:21:28.958  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:21:28.958  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:21:28.959  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:28.961  3799  3850 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-16 11:21:28.963  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 11:21:28.963  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:21:28.964  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:21:28.964  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 11:21:28.965  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:28.965  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:28.965  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
,08-16 11:21:28.965  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:28.966  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:28.966  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 11:21:28.966  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:28.967  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:28.967  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:28.967  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:28.970  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:21:28.970  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 11:21:28.970  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:28.971  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
,08-16 11:21:28.973  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-16 11:21:28.974  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:21:28.974  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:21:28.974  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 11:21:28.975  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:21:28.975  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:28.975  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:21:28.976  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
08-16 11:21:28.976  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:28.976  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
,08-16 11:21:28.976  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:21:28.977  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:28.977  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:28.977  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 11:21:28.977  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:21:28.979  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:21:28.979  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 11:21:28.979  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:21:28.980  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:28.981  3799  3850 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-16 11:21:28.981  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:21:28.981  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:21:28.981  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:21:28.981  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:21:28.982  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:28.982  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:28.982  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
08-16 11:21:28.982  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:28.982  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
,08-16 11:21:28.982  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:21:28.982  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:28.982  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:28.982  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:28.982  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:28.984  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:21:28.984  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:21:28.984  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:21:28.984  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:28.985  3799  3850 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 11:21:28.985  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:21:28.986  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:21:28.986  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:21:28.986  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:21:28.986  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 11:21:28.986  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:28.986  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
08-16 11:21:28.986  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:28.986  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:28.987  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:21:28.987  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:28.987  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:28.987  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:28.987  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:21:28.989  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:21:28.989  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:21:28.989  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:28.989  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:28.990  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-16 11:21:28.990  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 11:21:28.990  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 11:21:28.990  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 11:21:28.990  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 11:21:28.991  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 11:21:28.991  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 11:21:28.991  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-16 11:21:28.991  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 11:21:28.991  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:21:28.991  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:21:28.991  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 11:21:28.991  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:21:28.992  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:28.992  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:28.992  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
08-16 11:21:28.992  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:21:28.992  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:28.992  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:21:28.992  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:28.992  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:28.992  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:28.992  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:21:28.994  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:21:28.995  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:21:28.995  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:21:28.995  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:28.997  3799  3850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 11:21:28.998  3799  3850 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 11:21:28.998  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-16 11:21:29.004  3799  3850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-16 11:21:29.004  3799  3850 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-16 11:21:29.004  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,08-16 11:21:29.005  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 11:21:29.005  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 11:21:29.005  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 11:21:29.005  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-16 11:21:29.005  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 11:21:29.006  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 11:21:29.006  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 11:21:29.006  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-16 11:21:29.006  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 11:21:29.006  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 11:21:29.006  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 11:21:29.006  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 11:21:29.006  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 11:21:29.006  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 11:21:29.006  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 11:21:29.006  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 11:21:29.007  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 11:21:29.007  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 11:21:29.007  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 11:21:29.007  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 11:21:29.007  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 11:21:29.007  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 11:21:29.007  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 11:21:29.007  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 11:21:29.007  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 11:21:29.007  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 11:21:29.008  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 11:21:29.008  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 11:21:29.008  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 11:21:29.008  3799  3850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 11:21:29.009  3799  3850 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 11:21:29.009  3799  3850 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 11:21:29.010  3799  3850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 11:21:29.010  3799  3850 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 11:21:29.010  3799  3850 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 11:21:29.010  3799  3850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 11:21:29.010  3799  3850 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 11:21:29.010  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 11:21:29.018  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 11:21:29.019  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 11:21:29.019  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 11:21:29.020  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 11:21:29.020  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 11:21:29.020  3799  3850 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 11:21:29.020  3799  3850 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 11:21:29.021  3799  3850 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 11:21:29.022  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:21:29.022  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:21:29.023  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:21:29.023  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:21:29.023  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:29.023  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:29.023  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 11:21:29.022  3799  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
08-16 11:21:29.025  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
08-16 11:21:29.025  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:21:29.025  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:29.025  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:21:29.025  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:29.025  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:29.025  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:29.025  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:29.032  3799  3999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
08-16 11:21:29.032  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:21:29.032  3799  3998 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 11:21:29.032  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:21:29.033  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:29.033  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:29.035  3799  3850 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 11:21:29.038  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:21:29.038  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:21:29.038  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:21:29.038  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:21:29.038  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:29.038  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:29.038  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
08-16 11:21:29.038  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:29.038  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:29.039  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:21:29.039  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:29.039  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:29.039  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:29.039  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:29.040  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:21:29.041  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:21:29.041  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:29.041  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:29.043  3799  3850 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 11:21:29.044  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:21:29.044  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:21:29.045  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:21:29.045  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:21:29.045  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:29.045  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:29.045  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
08-16 11:21:29.045  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:29.045  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:29.045  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:21:29.045  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:29.046  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:29.046  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:29.046  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:29.047  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:21:29.047  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:21:29.047  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:29.047  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:29.048  3799  3850 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 11:21:29.048  3799  3850 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 11:21:29.048  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 11:21:29.048  3799  3850 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 11:21:29.048  3799  3850 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 11:21:29.048  3799  3850 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 11:21:29.048  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 11:21:29.048  3799  3850 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 11:21:29.049  3799  3850 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 11:21:29.049  3799  3850 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 11:21:29.049  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 11:21:29.049  3799  3850 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 11:21:29.049  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:21:29.049  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:21:29.049  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:21:29.049  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:21:29.050  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:29.050  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:29.050  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
08-16 11:21:29.050  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:29.050  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:29.050  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:21:29.050  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:29.050  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:29.050  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:29.050  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:29.051  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:21:29.052  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:21:29.052  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:29.052  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:29.052  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:21:29.052  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:29.053  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:29.053  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
08-16 11:21:29.053  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:29.053  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:29.053  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:21:29.053  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:29.053  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:21:34.054  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:21:34.054  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
,08-16 11:21:34.055  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:21:34.055  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 11:21:34.055  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:34.057  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
,08-16 11:21:34.057  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:21:34.058  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:21:34.058  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 11:21:34.060  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:21:34.060  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:34.060  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:21:34.061  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
,08-16 11:21:34.061  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:21:34.062  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:34.062  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 11:21:34.062  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:34.062  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:34.063  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 11:21:34.063  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:34.066  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:21:34.066  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 11:21:34.067  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:34.067  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
,08-16 11:21:34.072  3799  3850 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 11:21:34.072  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:21:34.073  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-16 11:21:34.074  3799  3850 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 11:21:34.074  3799  3850 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 11:21:34.075  3799  3799 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 11:21:34.075  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,08-16 11:21:34.075  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 11:21:34.075  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:21:34.075  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 11:21:34.076  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 11:21:34.076  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-16 11:21:34.076  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:34.076  3799  3850 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 11:21:34.076  3799  4000 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 11:21:34.076  3799  3799 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 11:21:34.076  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
08-16 11:21:34.076  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:34.076  3799  4000 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-16 11:21:34.077  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 11:21:34.077  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 11:21:34.077  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 11:21:34.077  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:34.077  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:21:34.078  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 11:21:34.079  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 11:21:34.079  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 11:21:34.079  3799  3799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 11:21:34.079  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 11:21:34.079  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:34.080  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:21:34.080  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:21:34.080  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 11:21:34.081  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:21:34.081  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:34.081  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:34.082  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
08-16 11:21:34.082  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:34.082  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:34.082  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:21:34.082  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:34.083  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:21:34.083  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:34.083  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:21:34.085  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 11:21:34.085  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 11:21:34.085  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:34.085  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
,08-16 11:21:34.087  3799  3850 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-16 11:21:34.087  3799  3850 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed,
08-16 11:21:34.087  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-16 11:21:34.088  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 11:21:34.088  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
08-16 11:21:34.088  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 11:21:34.088  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:21:34.088  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-16 11:21:34.088  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 11:21:34.088  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:34.088  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:21:34.088  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
08-16 11:21:34.088  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:21:34.089  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:34.089  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 11:21:34.089  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:34.089  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:21:34.089  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:34.089  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:34.091  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 11:21:34.091  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:21:34.091  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:21:34.091  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:34.097  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 11:21:34.097  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:21:34.097  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:21:34.097  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-16 11:21:34.097  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:34.097  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-16 11:21:34.097  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
08-16 11:21:34.097  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:34.097  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list,
08-16 11:21:34.098  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:21:34.098  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:34.098  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:34.098  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:34.098  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:34.099  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:21:34.100  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:21:34.100  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:34.100  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:34.101  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:21:34.101  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:21:34.101  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 11:21:34.101  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:21:34.101  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:34.101  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:34.101  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d85f1d2 not in the list
08-16 11:21:34.101  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:34.101  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
08-16 11:21:34.102  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:21:34.102  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:34.102  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:34.102  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:34.102  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:21:34.103  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:21:34.103  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:21:34.103  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:34.103  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c2222a3 not in the list
,08-16 11:21:34.168  2702  2874 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40,
,08-16 11:21:34.168  2702  2881 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,08-16 11:21:34.170  3799  3998 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
,08-16 11:21:34.580  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 11:21:39.107  3799  3850 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,08-16 11:21:39.107  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 11:21:39.108  3799  3850 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 11:21:39.108  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,08-16 11:21:39.109  3799  3850 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,08-16 11:21:39.109  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-16 11:21:39.118  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-16 11:21:39.119  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-16 11:21:39.122  3799  3850 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-16 11:21:39.123  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 11:21:39.123  3799  3850 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 11:21:39.123  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-16 11:21:39.123  3799  3850 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 11:21:39.123  3799  3850 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 11:21:39.124  3799  3850 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 11:21:39.124  3799  3850 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-16 11:21:39.124  3799  3850 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 11:21:39.124  3799  3850 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 11:21:39.125  3799  3850 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 11:21:39.125  3799  3850 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-16 11:21:42.712  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:21:42.714  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:21:42.723  3878  4001 V GoogleAuthProtoRequest: [326] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 11:21:42.831  1516  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-16 11:21:42.831  1516  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-16 11:21:42.831  1516  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 11:21:42.831  1516  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:21:42.891  3878  4001 W ExperimentUpdateService: [326] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-16 11:21:42.892  3878  4001 W ExperimentUpdateService: [326] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 11:21:42.892  3878  4001 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 11:21:42.892  3878  4001 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-16 11:21:42.892  3878  4001 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-16 11:21:42.892  3878  4001 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-16 11:21:42.892  3878  4001 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-16 11:21:42.892  3878  4001 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-16 11:21:42.892  3878  4001 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-16 11:21:42.892  3878  4001 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-16 11:21:42.892  3878  4001 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-16 11:21:42.892  3878  4001 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-16 11:21:43.044  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:21:43.081  1516  1912 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 11:21:43.081  1516  1912 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
08-16 11:21:43.081  1516  1912 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 11:21:43.081  1516  1912 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:21:43.107  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 11:21:43.107  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
08-16 11:21:43.107  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,08-16 11:21:44.127  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 11:21:44.128  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a0a7382 added. We now have 3 listener(s)
08-16 11:21:44.128  3799  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 11:21:44.135  3799  3850 D BluetoothAdapter: enable(): BT is already enabled..!
,08-16 11:21:44.137   873  1626 D WifiService: setWifiEnabled: true pid=3799, uid=10000
,08-16 11:21:44.137   873  1626 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 11:21:47.722   873  1867 D NetlinkSocketObserver: NeighborEvent{elapsedMs=186370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-16 11:21:49.142  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 11:21:49.143  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e30fa93 added. We now have 4 listener(s)
,08-16 11:21:49.143  3799  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 11:21:49.165  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:21:49.165  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e30fa93 removed from the list
,08-16 11:21:49.166  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 11:21:49.166  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 11:21:49.166  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:21:49.170  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 11:21:49.170  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7e5aad0 added. We now have 4 listener(s)
,08-16 11:21:49.170  3799  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 11:21:49.174  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:21:49.175  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7e5aad0 removed from the list
,08-16 11:21:49.175  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:21:49.175  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:21:49.175  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:21:49.178  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 11:21:49.178  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b54ac9 added. We now have 4 listener(s)
08-16 11:21:49.179  3799  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 11:21:49.189   873  1695 D WifiService: setWifiEnabled: false pid=3799, uid=10000
,08-16 11:21:49.190   873  1695 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 11:21:49.204  2702  2748 D BluetoothAdapterState: Current state: ON, message: 23
,08-16 11:21:49.204  2702  2748 D BluetoothAdapterProperties: Setting state to 13
,08-16 11:21:49.204  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:21:49.204  2702  2748 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-16 11:21:49.206  2702  2748 D BluetoothAdapterProperties: onBluetoothDisable()
,08-16 11:21:49.210  2702  2748 I BluetoothAdapterState: Entering PendingCommandState
08-16 11:21:49.211  2702  2752 D BluetoothAdapterProperties: Scan Mode:20
08-16 11:21:49.212  2702  2748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-16 11:21:49.215  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:49.215  3799  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:21:49.215  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:49.215  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:49.215  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:21:49.215  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:21:49.215  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:21:49.215  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:21:49.215  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:21:49.218  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:49.219  3799  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:21:49.219  3799  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 11:21:49.222  2702  2702 D HeadsetService: Received stop request...Stopping profile...
08-16 11:21:49.224  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:21:49.230  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:21:49.233  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 11:21:49.234  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:49.234  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:21:49.234  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:49.234  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:49.234  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:21:49.234  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:21:49.234  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:21:49.234  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:21:49.234  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:21:49.235   873  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 11:21:49.235   873  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,08-16 11:21:49.235   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 11:21:49.235  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:49.235   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 11:21:49.235  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 11:21:49.240  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:49.240  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:21:49.240  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:49.240  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:49.240  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:21:49.240  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:21:49.240  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:21:49.240  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:21:49.240  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:21:49.241  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 11:21:49.241  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 11:21:49.242   873   886 I ActivityManager: Start proc 4006:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-16 11:21:49.244  2702  2702 D BluetoothMapService: onReceive
08-16 11:21:49.244   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 11:21:49.244  2702  2702 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 11:21:49.244   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 11:21:49.244  2702  2702 D BluetoothMapService: STATE_TURNING_OFF
08-16 11:21:49.245  2702  2702 V BluetoothAdapterState: isTurningOff()=true
08-16 11:21:49.245  2702  2702 V BluetoothAdapterState: isTurningOn()=false
,08-16 11:21:49.245  2702  2702 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 11:21:49.245  2702  2702 V BluetoothAdapterState: isBleTurningOff()=false
08-16 11:21:49.245  1998  2014 D BluetoothHeadset: Proxy object disconnected
,08-16 11:21:49.245   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 11:21:49.245  2702  2702 D A2dpService: Received stop request...Stopping profile...
08-16 11:21:49.245  1374  1392 D BluetoothHeadset: Proxy object disconnected
08-16 11:21:49.246  2702  2887 D A2dpStateMachine: Exit Disconnected: -1
,08-16 11:21:49.247  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:21:49.250   873   873 D BluetoothA2dp: Proxy object disconnected
,08-16 11:21:49.250   873  1315 E native  : do suspend true
,08-16 11:21:49.251  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:21:49.252  1374  1374 D HeadsetProfile: Bluetooth service disconnected
,08-16 11:21:49.252  2702  2702 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-16 11:21:49.252  2702  2752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-16 11:21:49.252  2702  2874 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 11:21:49.252  1374  1374 D BluetoothA2dp: Proxy object disconnected
,08-16 11:21:49.253  2702  2874 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 11:21:49.253  2702  2874 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 11:21:49.252  2702  2702 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 11:21:49.253  2702  2752 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-16 11:21:49.253  2702  2702 D BluetoothMapService: MAP Service closeService in
08-16 11:21:49.253  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:21:49.253  2702  2702 D BluetoothMapMasInstance0: MAP Service shutdown
08-16 11:21:49.253  2702  2702 D ObexServerSockets0: shutdown(block = true)
08-16 11:21:49.254  2702  2895 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-16 11:21:49.255  2702  2702 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-16 11:21:49.255  2702  2896 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-16 11:21:49.256  2702  2881 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-16 11:21:49.256  2702  2702 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 11:21:49.256  2702  2702 I BtOppRfcommListener: stopping Accept Thread
08-16 11:21:49.256  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:21:49.257  2702  3411 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-16 11:21:49.258  2702  3411 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 11:21:49.261  2702  2702 D HidService: Received stop request...Stopping profile...
,08-16 11:21:49.261  2702  2702 D HidService: Stopping Bluetooth HidService
08-16 11:21:49.262  1374  1374 D BluetoothInputDevice: Proxy object disconnected
,08-16 11:21:49.262  1374  1374 D HidProfile: Bluetooth service disconnected
,08-16 11:21:49.263  2702  2702 D HealthService: Received stop request...Stopping profile...
08-16 11:21:49.265  2702  2702 D PanService: Received stop request...Stopping profile...
08-16 11:21:49.266   373   871 D CommandListener: Clearing all IP addresses on wlan0
08-16 11:21:49.266   873  1882 D DhcpClient: Clearing IP address
,08-16 11:21:49.269   373   871 D CommandListener: Setting iface cfg
,08-16 11:21:49.269  1374  1374 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 11:21:49.269  1374  1374 D PanProfile: Bluetooth service disconnected
08-16 11:21:49.270  2702  2702 D BluetoothMapService: Received stop request...Stopping profile...
,08-16 11:21:49.270  2702  2702 D BluetoothMapService: stop()
08-16 11:21:49.270   873  1898 D DhcpClient: Receive thread stopped
08-16 11:21:49.270  2702  2702 D BluetoothMapAppObserver: deinitObservers()
08-16 11:21:49.270  2702  2702 D BluetoothMapAppObserver: removeReceiver()
,08-16 11:21:49.271  1374  1374 D BluetoothMap: Proxy object disconnected
,08-16 11:21:49.271  1374  1374 D MapProfile: Bluetooth service disconnected
08-16 11:21:49.271  1516  2420 V NativeCrypto: Read error: ssl=0xaeced000: I/O error during system call, Connection timed out
08-16 11:21:49.272  2702  2702 V BluetoothAdapterState: isTurningOff()=true
08-16 11:21:49.272  2702  2702 V BluetoothAdapterState: isTurningOn()=false
08-16 11:21:49.272  2702  2702 V BluetoothAdapterState: isBleTurningOn()=false
08-16 11:21:49.272  2702  2702 V BluetoothAdapterState: isBleTurningOff()=false
08-16 11:21:49.273  2702  2752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-16 11:21:49.273  2702  2874 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 11:21:49.273  1516  2420 V NativeCrypto: SSL shutdown failed: ssl=0xaeced000: I/O error during system call, Broken pipe
08-16 11:21:49.273  2702  2874 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 11:21:49.273  2702  2874 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 11:21:49.273  2702  2874 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 11:21:49.273  2702  2874 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 11:21:49.273  2702  2874 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 11:21:49.275  2702  2702 V BluetoothAdapterState: isTurningOff()=true
08-16 11:21:49.275  2702  2702 V BluetoothAdapterState: isTurningOn()=false
08-16 11:21:49.275  2702  2702 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 11:21:49.275  2702  2702 V BluetoothAdapterState: isBleTurningOff()=false
08-16 11:21:49.275  2702  2702 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 11:21:49.275  2702  2702 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 11:21:49.275  2702  2752 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 11:21:49.276  2702  2702 V BluetoothAdapterState: isTurningOff()=true
08-16 11:21:49.276  2702  2702 V BluetoothAdapterState: isTurningOn()=false
08-16 11:21:49.276  2702  2702 V BluetoothAdapterState: isBleTurningOn()=false
08-16 11:21:49.276  2702  2702 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 11:21:49.276  2702  2702 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 11:21:49.276  2702  2702 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 11:21:49.277  2702  2702 V BluetoothAdapterState: isTurningOff()=true
08-16 11:21:49.277  2702  2702 V BluetoothAdapterState: isTurningOn()=false
,08-16 11:21:49.277  2702  2702 V BluetoothAdapterState: isBleTurningOn()=false
08-16 11:21:49.277  2702  2702 V BluetoothAdapterState: isBleTurningOff()=false
08-16 11:21:49.278  2702  2752 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-16 11:21:49.283   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-16 11:21:49.283   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,08-16 11:21:49.288  2702  2702 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,08-16 11:21:49.288  2702  2702 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 11:21:49.290   401   401 E Parcel  : Reading a NULL string not supported here.
08-16 11:21:49.291  2702  2702 D BluetoothMapService: MAP Service closeService in
08-16 11:21:49.291  2702  2702 V BluetoothAdapterState: isTurningOff()=true
,08-16 11:21:49.291  2702  2702 V BluetoothAdapterState: isTurningOn()=false
,08-16 11:21:49.291  2702  2702 V BluetoothAdapterState: isBleTurningOn()=false
08-16 11:21:49.291  2702  2702 V BluetoothAdapterState: isBleTurningOff()=false
08-16 11:21:49.292  2702  2702 D BluetoothMapService: cleanup()
08-16 11:21:49.292  2702  2702 D BluetoothMapService: MAP Service closeService in
08-16 11:21:49.292   873  1315 D WifiStateMachine: Start Disconnecting Watchdog 1
08-16 11:21:49.292   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 11:21:49.292   873  1315 E native  : do suspend true
08-16 11:21:49.293  2702  2748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-16 11:21:49.293  2702  2748 D BluetoothAdapterProperties: Setting state to 15
,08-16 11:21:49.293  2702  2748 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 11:21:49.293   873  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 11:21:49.295   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 11:21:49.295  1374  1392 D BluetoothMap: onBluetoothStateChange: up=false
08-16 11:21:49.296  2702  2748 I BluetoothAdapterState: Entering BleOnState
08-16 11:21:49.296  1374  1391 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 11:21:49.296  1374  2067 D BluetoothPan: onBluetoothStateChange on: false
08-16 11:21:49.297  1998  2011 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 11:21:49.297   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 11:21:49.297  1374  1392 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 11:21:49.298  1374  1391 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 11:21:49.298   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 11:21:49.298   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 11:21:49.298  1374  2067 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-16 11:21:49.300  2702  2748 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 11:21:49.301  2702  2748 D BluetoothAdapterProperties: Setting state to 16
08-16 11:21:49.301  2702  2748 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-16 11:21:49.303  2702  2748 D BluetoothAdapterProperties: onBleDisable
08-16 11:21:49.303  2702  2749 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-16 11:21:49.303  2702  2748 I BluetoothAdapterState: Entering PendingCommandState
08-16 11:21:49.304  2702  2874 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-16 11:21:49.304  2702  2874 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 11:21:49.305  2702  2752 D BluetoothAdapterProperties: Scan Mode:20
08-16 11:21:49.306  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:49.306  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:21:49.306  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:49.306  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:49.306  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:21:49.306  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:21:49.306  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:21:49.306  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:21:49.306  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:21:49.307  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 11:21:49.307  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:21:49.309  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:49.309  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:21:49.309  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:49.309  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:49.309  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:21:49.309  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:21:49.309  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:21:49.309  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:21:49.309  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:21:49.309  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 11:21:49.309  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:21:49.314  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:49.314  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:21:49.314  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:49.314  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:49.314  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:21:49.314  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:21:49.314  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:21:49.314  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:21:49.314  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:21:49.314  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:49.315  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:21:49.315  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:21:49.316  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:21:49.318  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:21:49.328   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 11:21:49.346   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 11:21:49.346   373   871 D CommandListener: Clearing all IP addresses on wlan0
08-16 11:21:49.347   873  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 11:21:49.347   873  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 11:21:49.349   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-16 11:21:49.349   873   890 D Tethering: MasterInitialState.processMessage what=3
08-16 11:21:49.352  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:21:49.353  3401  3401 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@7b0ff3 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-16 11:21:49.353  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:21:49.356  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:21:49.364  4006  4006 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-16 11:21:49.366   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 11:21:49.368  1853  2303 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 11:21:49.369  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:49.369  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:21:49.369  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:49.369  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:49.369  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:21:49.369  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:21:49.369  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:21:49.369  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:21:49.369  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 11:21:49.370  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:49.370  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 11:21:49.371  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:49.371  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:21:49.371  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:49.371  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:49.371  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:21:49.371  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:21:49.371  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:21:49.371  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:21:49.371  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:21:49.371   873  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-16 11:21:49.372  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:49.372  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 11:21:49.373  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:49.373  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:21:49.373  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:49.373  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:49.373  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:21:49.373  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:21:49.373  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:21:49.373  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:21:49.373  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 11:21:49.374  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:49.374  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 11:21:49.382  4006  4006 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 11:21:49.386   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e857b7:true
,08-16 11:21:49.387  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 11:21:49.400   373   871 E Netd    : netlink response contains error (No such file or directory)
08-16 11:21:49.400   873  1626 I ActivityManager: Start proc 4027:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-16 11:21:49.401   873  1318 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-16 11:21:49.408  4006  4006 D LocalBluetoothProfileManager: Adding local MAP profile
,08-16 11:21:49.410  4006  4006 D BluetoothMap: Create BluetoothMap proxy object
,08-16 11:21:49.415  4006  4006 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-16 11:21:49.428  4027  4027 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-16 11:21:49.430  4006  4006 D DockEventReceiver: finishStartingService: stopping service
,08-16 11:21:49.438   873  1927 I ActivityManager: Killing 3401:com.google.android.music:main/u0a66 (adj 15): empty #17
,08-16 11:21:49.504  2702  2752 I bt_hci  : shut_down
,08-16 11:21:49.505  2702  2756 D bt_hwcfg: hw_epilog_process
08-16 11:21:49.506  2702  2756 I bt_vendor: low_power_mode_cb
,08-16 11:21:49.528  2702  2756 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-16 11:21:49.528  2702  2756 I bt_vendor: epilog_cb
,08-16 11:21:49.528  2702  2756 I bt_hci  : epilog_finished_callback
,08-16 11:21:49.534  2702  2752 I bt_hci_h4: hal_close
,08-16 11:21:49.534  2702  2752 I bt_userial_vendor: device fd = 51 close
,08-16 11:21:49.660  2702  2749 D bt_stack_manager: event_shut_down_stack finished.
,08-16 11:21:49.661  2702  2748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 11:21:49.662  2702  2748 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 11:21:49.663  2702  2702 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 11:21:49.665  2702  2702 D BtGatt.GattService: Received stop request...Stopping profile...
,08-16 11:21:49.665  2702  2702 D BtGatt.GattService: stop()
,08-16 11:21:49.665  4027  4027 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 11:21:49.665  4027  4027 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 11:21:49.665  4027  4027 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 11:21:49.665  2702  2702 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 11:21:49.666  4027  4027 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 11:21:49.666  4027  4027 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 11:21:49.666  4027  4027 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 11:21:49.666  4027  4027 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.j,ava:290)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.r.k.d(PG:583)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.r.e.b(PG:170)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 11:21:49.666  4027  4027 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-,16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 11:21:49.666  4027  4027 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at java.io.File.exists(File.java:361)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 11:21:49.666  4027  4027 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 11:21:49.666  4027  4027 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 11:21:49.673  4006  4006 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-16 11:21:49.678  2702  2702 V BluetoothAdapterState: isTurningOff()=false
08-16 11:21:49.678  2702  2702 V BluetoothAdapterState: isTurningOn()=false
08-16 11:21:49.678  2702  2702 V BluetoothAdapterState: isBleTurningOn()=false
08-16 11:21:49.678  2702  2702 V BluetoothAdapterState: isBleTurningOff()=true
08-16 11:21:49.679  2702  2748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-16 11:21:49.679  2702  2748 D BluetoothAdapterProperties: Setting state to 10
08-16 11:21:49.679  2702  2748 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-16 11:21:49.681  2702  2748 I BluetoothAdapterState: Entering OffState
08-16 11:21:49.682   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-16 11:21:49.686  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 11:21:49.695  2702  2702 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-16 11:21:49.695  2702  2702 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 11:21:49.695  2702  2702 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 11:21:49.696  2702  2749 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-16 11:21:49.698  2702  2749 D bt_stack_manager: event_clean_up_stack finished.
08-16 11:21:49.699  2702  2702 I art     : System.exit called, status: 0
08-16 11:21:49.699  2702  2702 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 11:21:49.724   873  2978 I ActivityManager: Start proc 4058:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
08-16 11:21:49.725  4006  4006 D DockEventReceiver: finishStartingService: stopping service
08-16 11:21:49.733   873  2978 I ActivityManager: Killing 3451:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-16 11:21:49.787   873  2024 I ActivityManager: Process com.android.bluetooth (pid 2702) has died
,08-16 11:21:49.832  4058  4058 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-16 11:21:50.143  4058  4078 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-16 11:21:50.143  4058  4078 I Babel_SMS: MmsConfig.loadMmsSettings
,08-16 11:21:50.146  4058  4078 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 11:21:50.146  4058  4078 I Babel_SMS: MmsConfig.loadFromDatabase
,08-16 11:21:50.180  4058  4078 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-16 11:21:50.180  4058  4078 I Babel_SMS: MmsConfig.loadFromResources,
,08-16 11:21:50.181  4058  4078 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-16 11:21:50.182  4058  4078 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-16 11:21:50.201  4058  4058 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 11:21:50.203  4058  4058 I Babel_Crash: startup - clean
,08-16 11:21:50.242  4027  4046 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-16 11:21:50.272  4058  4058 I Babel_telephony: TeleModule.launchCompleted
,08-16 11:21:50.277   873  2978 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 11:21:50.285  4058  4058 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-16 11:21:50.292  4058  4058 W Babel   : BAM#gBA: invalid account id: -1
,08-16 11:21:50.292  4058  4058 W Babel   : BAM#gBA: invalid account id: -1
,08-16 11:21:50.292  4058  4058 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-16 11:21:50.300   873  1380 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-16 11:21:50.315  4058  4083 I Babel   : deleted: false for 0
,08-16 11:21:50.351  1718  1718 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 11:21:50.356  1718  1718 D SystemUpdateService: onCreate
,08-16 11:21:50.371  1718  1718 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 11:21:50.393  1718  4085 I SystemUpdateService: active receiver: enabled
,08-16 11:21:50.396  1718  4085 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 11:21:50.398  1718  4085 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-16 11:21:50.398  1718  4085 I SystemUpdateService: now status is 0 (complete)
,08-16 11:21:50.398  1718  4085 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 11:21:50.398  1718  4085 I SystemUpdateService: file has been verified
,08-16 11:21:50.398  1718  4085 I SystemUpdateService: OTA package size = 12249756
,08-16 11:21:50.403  1718  4085 I SystemUpdateService: showing system update notification
,08-16 11:21:50.419  1718  1718 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-16 11:21:50.420  1718  1718 D SystemUpdateService: onDestroy
,08-16 11:21:50.423  1718  2396 I iu.UploadsManager: num queued entries: 0
,08-16 11:21:50.423  1718  2396 I iu.UploadsManager: num updated entries: 0
,08-16 11:21:50.424  1718  2396 I iu.SyncManager: NEXT; no task
,08-16 11:21:50.425  4058  4058 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 11:21:50.427  1718  1718 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 11:21:50.429  1718  1718 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 11:21:50.442   873  2019 I ActivityManager: Start proc 4087:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-16 11:21:50.478  4087  4087 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-16 11:21:50.482  4087  4087 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 11:21:50.492   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f708a1:true
,08-16 11:21:50.497  4087  4087 D SprintDMHelper: simOperator: 
,08-16 11:21:50.497  4087  4087 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 11:21:50.498  4058  4058 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-16 11:21:50.514  4058  4058 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 11:21:50.517  4058  4058 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 11:21:50.520  4058  4058 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 11:21:50.520   873   883 I ActivityManager: Start proc 4099:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-16 11:21:50.539  4058  4058 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 11:21:50.552   873  1380 I ActivityManager: Killing 3491:android.process.acore/u0a5 (adj 15): empty #17
,08-16 11:21:50.599  4058  4058 I vclib   : onServiceConnected
,08-16 11:21:50.716   873  1948 I ActivityManager: Start proc 4114:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-16 11:21:50.720  4058  4113 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-16 11:21:50.725   873  1946 I ActivityManager: Killing 3685:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-16 11:21:50.788  4114  4114 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-16 11:21:50.840  4114  4114 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-16 11:21:50.840  4114  4114 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-16 11:21:50.840  4114  4114 I GAv4    :   adb logcat -s GAv4
,08-16 11:21:50.854  4114  4114 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-16 11:21:50.859  4114  4114 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-16 11:21:50.869  4114  4131 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-16 11:21:50.989  4114  4114 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-16 11:21:51.020  4114  4114 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-16 11:21:51.041  4114  4114 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 9677-9687)
,08-16 11:21:51.041  4114  4114 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 11:21:51.053  4114  4114 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3122155}
,08-16 11:21:51.053  4114  4114 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 11:21:51.054  4114  4114 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 11:21:51.061  4114  4114 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-16 11:21:51.062  4114  4114 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-16 11:21:51.083  4114  4114 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-16 11:21:51.096  4114  4114 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-16 11:21:51.096  4114  4114 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-16 11:21:51.096  4114  4114 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-16 11:21:51.096  4114  4114 I Adreno  : Build Date                       : 10/20/15
08-16 11:21:51.096  4114  4114 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-16 11:21:51.096  4114  4114 I Adreno  : Local Branch                     : M14
08-16 11:21:51.096  4114  4114 I Adreno  : Remote Branch                    : 
08-16 11:21:51.096  4114  4114 I Adreno  : Remote Branch                    : 
08-16 11:21:51.096  4114  4114 I Adreno  : Reconstruct Branch               : 
,08-16 11:21:51.149  4114  4114 I NSApplication: Starting up...
,08-16 11:21:51.163  4114  4160 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 11:21:51.200   873  1626 I ActivityManager: Start proc 4165:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-16 11:21:51.204   873  1626 I ActivityManager: Killing 3702:com.android.musicfx/u0a18 (adj 15): empty #17
,08-16 11:21:51.328  4165  4165 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-16 11:21:51.553   873   884 I ActivityManager: Killing 1929:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-16 11:21:54.222   873  1927 D WifiService: setWifiEnabled: true pid=3799, uid=10000
,08-16 11:21:54.223   873  1927 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 11:21:54.237   873  1315 D WifiConfigStore: Loading config and enabling all networks 
,08-16 11:21:54.249  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 11:21:54.249  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:21:54.249  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:54.249  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:54.249  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:21:54.249  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:21:54.249  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:21:54.249  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:21:54.249  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 11:21:54.250  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 11:21:54.250  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 11:21:54.253  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 11:21:54.254  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:21:54.254  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:54.254  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:54.254  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:21:54.254  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:21:54.254  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:21:54.254  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:21:54.254  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:21:54.254  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 11:21:54.254  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:21:54.258  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:54.258  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:21:54.258  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:54.258  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:54.258  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:21:54.258  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:21:54.258  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:21:54.258  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:21:54.258  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:21:54.258  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:54.259  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 11:21:54.283   873  1315 D WifiConfigStore: loaded 0 passpoint configs
,08-16 11:21:54.284   873  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-16 11:21:54.284   873  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-16 11:21:54.285   873  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-16 11:21:54.286   873  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-16 11:21:54.286   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-16 11:21:54.286   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 11:21:54.299   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-16 11:21:54.299   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 11:21:54.300   373   871 D CommandListener: Setting iface cfg
,08-16 11:21:54.300   873  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '127 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 127 Failed to set address (No such device)'
08-16 11:21:54.301   873  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 11:21:54.310   873  1315 E native  : do suspend true
,08-16 11:21:54.310   873  1313 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 11:21:54.317   873  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 11:21:54.327   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 11:21:55.158   873  1695 I ActivityManager: Killing 3648:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-16 11:21:55.715   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 11:21:55.750   873  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.69 rxSuccessRate=9.31 delta 1000 -> 994
,08-16 11:21:55.752   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 11:21:55.752   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 11:21:55.778   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 11:21:55.857   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 11:21:55.858  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 11:21:56.273  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 11:21:56.315  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 11:21:56.318  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 11:21:56.323   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 11:21:56.335   873  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 11:21:56.336   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 11:21:56.336   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 11:21:56.358   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 11:21:56.372   373   871 D CommandListener: Setting iface cfg
,08-16 11:21:56.373   873  1315 D WifiStateMachine: Start Dhcp Watchdog 2
,08-16 11:21:56.380   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 11:21:56.418   873  4194 D DhcpClient: Receive thread started
,08-16 11:21:56.499   873  1315 E native  : do suspend false
,08-16 11:21:56.517   873  1882 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 11:21:56.529   873  4194 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172627, domain null
,08-16 11:21:56.529   873  1882 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172627 seconds
,08-16 11:21:56.532   873  1882 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 11:21:56.543   873  4194 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 11:21:56.544   873  1882 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 11:21:56.548   373   871 D CommandListener: Setting iface cfg
,08-16 11:21:56.556   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
08-16 11:21:56.556   873  1882 D DhcpClient: Scheduling renewal in 86399s
,08-16 11:21:56.559   873  1315 E native  : do suspend true
,08-16 11:21:56.576   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 11:21:56.579   873  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 11:21:56.581   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 11:21:56.585   873  1318 D ConnectivityService: Adding iface wlan0 to network 101
,08-16 11:21:56.592   873  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 11:21:56.660   873  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 11:21:56.660   873  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-16 11:21:56.663   873  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-16 11:21:56.665   873  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-16 11:21:56.667   873  1318 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-16 11:21:56.681   873  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 11:21:56.689   873  1318 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-16 11:21:56.689   873  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
08-16 11:21:56.689   873  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,08-16 11:21:56.689   873  1318 D ConnectivityService:    accepting network in place of null
08-16 11:21:56.689   873  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-16 11:21:56.690   873  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 11:21:56.691   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 11:21:56.707   873  4193 D NetlinkSocketObserver: NeighborEvent{elapsedMs=195355, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 11:21:56.743   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 11:21:56.778   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 11:21:56.785   873  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-16 11:21:56.785   873  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 11:21:56.789   873  4190 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.198.142,2a00:1450:4001:812::200e
08-16 11:21:56.790   873   890 D Tethering: MasterInitialState.processMessage what=3
08-16 11:21:56.795   873  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-16 11:21:56.800  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:56.800  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:21:56.800  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:56.800  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:56.800  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:21:56.800  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:21:56.800  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:21:56.800  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:21:56.800  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:21:56.800  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:56.800  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 11:21:56.804  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 11:21:56.805  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:21:56.805  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:56.805  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:56.805  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:21:56.805  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:21:56.805  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:21:56.805  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:21:56.805  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:21:56.805  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:56.805  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:21:56.808  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 11:21:56.808  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:21:56.808  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:56.808  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:56.808  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:21:56.808  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:21:56.808  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:21:56.808  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:21:56.808  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:21:56.808  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-16 11:21:56.808  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 11:21:56.827  1718  1718 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 11:21:56.831  1718  1718 D SystemUpdateService: onCreate
,08-16 11:21:56.834  1718  1718 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 11:21:56.859  1718  1718 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 11:21:56.864  1718  4204 I SystemUpdateService: active receiver: enabled
,08-16 11:21:56.870  1718  2396 I iu.UploadsManager: num queued entries: 0
,08-16 11:21:56.870  1718  2396 I iu.UploadsManager: num updated entries: 0
,08-16 11:21:56.873  1718  1718 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 11:21:56.874  1718  1718 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 11:21:56.874   873  4190 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 09:21:56 GMT], X-Android-Received-Millis=[1471339316873], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471339316844]}
,08-16 11:21:56.877  4087  4087 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
08-16 11:21:56.877   873  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
08-16 11:21:56.877   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-16 11:21:56.878   873  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-16 11:21:56.884   873  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 11:21:56.885  1718  4206 I MDM     : [178] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-16 11:21:56.885  1718  4206 W BaseAppContext: Using Auth Proxy for data requests.
08-16 11:21:56.887  1718  4206 V GoogleAuthProtoRequest: [178] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 11:21:56.894  4087  4087 D SprintDMHelper: simOperator: 
,08-16 11:21:56.894  4087  4087 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 11:21:56.904  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:21:56.906  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:21:56.913  1718  4204 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 11:21:56.923  1718  2396 I iu.SyncManager: NEXT; no task
,08-16 11:21:56.925  1718  4204 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 11:21:56.925  1718  4204 I SystemUpdateService: now status is 0 (complete)
,08-16 11:21:56.931  1718  4204 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-16 11:21:56.931  1718  4204 I SystemUpdateService: file has been verified
08-16 11:21:56.931  1718  4204 I SystemUpdateService: OTA package size = 12249756
,08-16 11:21:56.959  1718  4204 I SystemUpdateService: showing system update notification
,08-16 11:21:56.984  1516  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-16 11:21:56.984  1516  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-16 11:21:56.984  1516  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 11:21:56.984  1516  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:21:57.022  1718  1718 D SystemUpdateService: onDestroy
,08-16 11:21:57.025  4058  4212 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 11:21:57.034  1718  4206 E MDM     : [178] SitrepService.a: Error sending sitrep.
,08-16 11:21:57.786   873  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 11:21:59.229   873  1928 D WifiService: setWifiEnabled: false pid=3799, uid=10000
08-16 11:21:59.229   873  1928 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 11:21:59.267  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-16 11:21:59.277   873  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-16 11:21:59.277   873  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-16 11:21:59.278   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 11:21:59.278   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 11:21:59.300   873  1315 E native  : do suspend true
,08-16 11:21:59.316   873  1882 D DhcpClient: Clearing IP address
,08-16 11:21:59.316   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-16 11:21:59.321   373   871 D CommandListener: Setting iface cfg
,08-16 11:21:59.329  1516  4218 V NativeCrypto: Read error: ssl=0x9b451000: I/O error during system call, Connection timed out
,08-16 11:21:59.335  1516  4218 V NativeCrypto: SSL shutdown failed: ssl=0x9b451000: I/O error during system call, Broken pipe
,08-16 11:21:59.337   873  4194 D DhcpClient: Receive thread stopped
,08-16 11:21:59.346   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-16 11:21:59.347   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-16 11:21:59.352   873  1315 D WifiStateMachine: Start Disconnecting Watchdog 2
08-16 11:21:59.353   401   401 E Parcel  : Reading a NULL string not supported here.
,08-16 11:21:59.357   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-16 11:21:59.357   873  1315 E native  : do suspend true
,08-16 11:21:59.366   873  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-16 11:21:59.420   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 11:21:59.455   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 11:21:59.456   373   871 D CommandListener: Clearing all IP addresses on wlan0
,08-16 11:21:59.458   873  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 11:21:59.458   873  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 11:21:59.463   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 11:21:59.464   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 11:21:59.484  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:59.485  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:21:59.485  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:59.485  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:59.485  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:21:59.485  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:21:59.485  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:21:59.485  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:21:59.485  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 11:21:59.485  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 11:21:59.485  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:21:59.487  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:59.487  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:21:59.487  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:59.487  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:59.487  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:21:59.487  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:21:59.487  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:21:59.487  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:21:59.487  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:21:59.488  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:59.488  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:21:59.491  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:59.491  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:21:59.491  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:59.491  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:59.491  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:21:59.491  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:21:59.491  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:21:59.491  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:21:59.491  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 11:21:59.492  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:59.492  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:21:59.492   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
08-16 11:21:59.495  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:59.495  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:21:59.495  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:59.495  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:59.495  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:21:59.495  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:21:59.495  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:21:59.495  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:21:59.495  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:21:59.495  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:59.495  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:21:59.496  1853  2303 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 11:21:59.496  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:59.496  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:21:59.496  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:59.496  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:59.496  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:21:59.496  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:21:59.496  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:21:59.496  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:21:59.496  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:21:59.496  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:59.496  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:21:59.497  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 11:21:59.497  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:21:59.497  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:21:59.497  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:21:59.497  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:21:59.497  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:21:59.497  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:21:59.497  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:21:59.497  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:21:59.497  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:21:59.497  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:21:59.499   873  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-16 11:21:59.508  1718  1718 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 11:21:59.517  1718  1718 D SystemUpdateService: onCreate
,08-16 11:21:59.520  1718  1718 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 11:21:59.533  1718  1718 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-16 11:21:59.542  1718  4228 I SystemUpdateService: active receiver: enabled
,08-16 11:21:59.543  1718  1718 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
08-16 11:21:59.537  1718  2396 I iu.UploadsManager: num queued entries: 0
08-16 11:21:59.544  1718  1718 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 11:21:59.547  4087  4087 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 11:21:59.552  4087  4087 D SprintDMHelper: simOperator: 
,08-16 11:21:59.552  4087  4087 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 11:21:59.556   373   871 E Netd    : netlink response contains error (No such file or directory)
,08-16 11:21:59.557   873  1318 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-16 11:21:59.555  1718  2396 I iu.UploadsManager: num updated entries: 0
,08-16 11:21:59.575  4058  4232 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-16 11:21:59.590  1718  4228 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-16 11:21:59.605  1718  2396 I iu.SyncManager: NEXT; no task
,08-16 11:21:59.609  1718  4228 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-16 11:21:59.609  1718  4228 I SystemUpdateService: now status is 0 (complete)
,08-16 11:21:59.609  1718  4228 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-16 11:21:59.609  1718  4228 I SystemUpdateService: file has been verified
,08-16 11:21:59.609  1718  4228 I SystemUpdateService: OTA package size = 12249756
,08-16 11:21:59.614  1718  4228 I SystemUpdateService: showing system update notification
,08-16 11:21:59.623  1718  1718 D SystemUpdateService: onDestroy
,08-16 11:22:04.285   873   890 I ActivityManager: Start proc 4235:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 11:22:04.405  4235  4235 D AdapterServiceConfig: Adding HeadsetService
08-16 11:22:04.406  4235  4235 D AdapterServiceConfig: Adding A2dpService
08-16 11:22:04.407  4235  4235 D AdapterServiceConfig: Adding HidService
,08-16 11:22:04.408  4235  4235 D AdapterServiceConfig: Adding HealthService
08-16 11:22:04.409  4235  4235 D AdapterServiceConfig: Adding PanService
,08-16 11:22:04.410  4235  4235 D AdapterServiceConfig: Adding GattService
08-16 11:22:04.411  4235  4235 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 11:22:04.438   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e312c3c:true
,08-16 11:22:04.438  4235  4235 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 11:22:04.444  4235  4235 I bt_bluedroid: init
,08-16 11:22:04.444  4235  4247 I BluetoothAdapterState: Entering OffState
,08-16 11:22:04.449  4235  4248 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-16 11:22:04.450  4235  4248 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-16 11:22:04.450  4235  4248 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 11:22:04.450  4235  4248 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 11:22:04.452  4235  4235 I bt_bluedroid: get_profile_interface socket
08-16 11:22:04.455  4235  4251 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 11:22:04.456  4235  4235 I bt_bluedroid: get_profile_interface sdp
08-16 11:22:04.458  4235  4251 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 11:22:04.462  4235  4246 I bt_bluedroid: config_hci_snoop_log
,08-16 11:22:04.465   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 11:22:04.476  4235  4247 D BluetoothAdapterState: Current state: OFF, message: 0
,08-16 11:22:04.477  4235  4247 D BluetoothAdapterProperties: Setting state to 14
08-16 11:22:04.477  4235  4247 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 11:22:04.481  4235  4247 D BluetoothBondStateMachine: make
,08-16 11:22:04.488  4235  4252 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 11:22:04.494  4235  4247 I BluetoothAdapterState: Entering PendingCommandState
,08-16 11:22:04.498  4235  4235 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 11:22:04.506  4235  4235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf87833
,08-16 11:22:04.509  4235  4235 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 11:22:04.510  4235  4235 D BtGatt.GattService: Received start request. Starting profile...
,08-16 11:22:04.510  4235  4235 D BtGatt.GattService: start()
08-16 11:22:04.510  4235  4235 I bt_bluedroid: get_profile_interface gatt
08-16 11:22:04.512  4235  4235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf87833
08-16 11:22:04.512  4235  4235 D BtGatt.AdvertiseManager: advertise manager created
,08-16 11:22:04.525  4235  4235 V BluetoothAdapterState: isTurningOff()=false
,08-16 11:22:04.525  4235  4235 V BluetoothAdapterState: isTurningOn()=false
,08-16 11:22:04.526  4235  4235 V BluetoothAdapterState: isBleTurningOn()=true
,08-16 11:22:04.526  4235  4235 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 11:22:04.527  4235  4247 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,08-16 11:22:04.528  4235  4247 I bt_bluedroid: enable
,08-16 11:22:04.528  4235  4248 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-16 11:22:04.529  4235  4248 I bt_hci  : start_up
,08-16 11:22:04.552  4235  4248 I bt_vendor: alloc value 0xb3a71189
,08-16 11:22:04.552  4235  4248 I bt_vendor: init
,08-16 11:22:04.552  4235  4248 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-16 11:22:04.552  4235  4248 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 11:22:04.659  4235  4248 D bt_hci  : start_up starting async portion
08-16 11:22:04.659  4235  4255 I bt_hci  : event_finish_startup
08-16 11:22:04.659  4235  4255 I bt_hci_h4: hal_open
08-16 11:22:04.660  4235  4255 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 11:22:04.665  4235  4255 I bt_userial_vendor: device fd = 51 open
,08-16 11:22:04.694   873  1318 D ConnectivityService: handlePromptUnvalidated 101
,08-16 11:22:04.700  4235  4255 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 11:22:04.733  4235  4255 D bt_hwcfg: Chipset BCM4354A2
08-16 11:22:04.733  4235  4255 D bt_hwcfg: Target name = [BCM4354A2]
,08-16 11:22:04.734  4235  4255 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 11:22:05.393  4235  4255 I bt_hwcfg: bt vendor lib: set UART baud 115200
08-16 11:22:05.394  4235  4255 D bt_hwcfg: Settlement delay -- 100 ms
,08-16 11:22:05.395  4235  4255 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 11:22:05.511  4235  4255 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 11:22:05.513  4235  4255 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 11:22:05.542  4235  4255 I bt_hwcfg: vendor lib fwcfg completed
,08-16 11:22:05.542  4235  4255 I bt_vendor: firmware callback
,08-16 11:22:05.542  4235  4255 I bt_hci  : firmware_config_callback
,08-16 11:22:05.555  4235  4257 I bt_btu  : btu_task pending for preload complete event
,08-16 11:22:05.556  4235  4257 I bt_btu_task: Bluetooth chip preload is complete
,08-16 11:22:05.556  4235  4257 I bt_btu  : btu_task received preload complete event
,08-16 11:22:05.566  4235  4257 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 11:22:05.566  4235  4257 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 11:22:05.566  4235  4257 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 11:22:05.567  4235  4257 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-16 11:22:05.567  4235  4257 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 11:22:05.567  4235  4257 I         : BTE_InitTraceLevels -- TRC_A2D
,08-16 11:22:05.568  4235  4257 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 11:22:05.568  4235  4257 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 11:22:05.568  4235  4257 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 11:22:05.569  4235  4257 I         : BTE_InitTraceLevels -- TRC_PAN
,08-16 11:22:05.569  4235  4257 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 11:22:05.569  4235  4257 I         : BTE_InitTraceLevels -- TRC_GATT
,08-16 11:22:05.570  4235  4257 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 11:22:05.570  4235  4257 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 11:22:05.570  4235  4257 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 11:22:05.705  4235  4257 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39eed9d
,08-16 11:22:05.706  4235  4257 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39eed9d 
,08-16 11:22:05.717  4235  4251 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 11:22:05.719  4235  4251 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 11:22:05.720  4235  4251 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61,
,08-16 11:22:05.725  4235  4251 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 11:22:05.731  4235  4251 D BluetoothAdapterProperties: Scan Mode:20,
,08-16 11:22:05.731  4235  4251 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 11:22:05.732  4235  4251 D bt_hci  : do_postload posting postload work item
08-16 11:22:05.732  4235  4255 I bt_hci  : event_postload
08-16 11:22:05.732  4235  4255 I bt_vendor: sco_config_cb
08-16 11:22:05.733  4235  4255 I bt_hci  : sco_config_callback postload finished.
08-16 11:22:05.735  4235  4251 D bt_bte_conf: Device ID record 1 : primary
08-16 11:22:05.735  4235  4251 D bt_bte_conf:   vendorId            = 000f
08-16 11:22:05.735  4235  4251 D bt_bte_conf:   vendorIdSource      = 0001
08-16 11:22:05.735  4235  4251 D bt_bte_conf:   product             = 1200
,08-16 11:22:05.735  4235  4251 D bt_bte_conf:   version             = 1436
08-16 11:22:05.736  4235  4251 D bt_bte_conf:   clientExecutableURL = 
08-16 11:22:05.736  4235  4251 D bt_bte_conf:   serviceDescription  = 
,08-16 11:22:05.736  4235  4251 D bt_bte_conf:   documentationURL    = 
,08-16 11:22:05.736  4235  4251 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-16 11:22:05.737  4235  4248 D bt_stack_manager: event_start_up_stack finished
08-16 11:22:05.738  4235  4247 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-16 11:22:05.738  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:22:05.738  4235  4247 D BluetoothAdapterProperties: Setting state to 15
,08-16 11:22:05.739  4235  4247 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-16 11:22:05.740  4235  4247 I BluetoothAdapterState: Entering BleOnState
,08-16 11:22:05.745  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:22:05.747  4235  4255 I bt_vendor: low_power_mode_cb
08-16 11:22:05.748  4235  4247 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-16 11:22:05.748  4235  4247 D BluetoothAdapterProperties: Setting state to 11
08-16 11:22:05.748  4235  4247 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-16 11:22:05.748  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:22:05.753  4235  4235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf87833
,08-16 11:22:05.754  4235  4235 D HeadsetService: Received start request. Starting profile...
08-16 11:22:05.760  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:22:05.763  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:22:05.765  4235  4235 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 11:22:05.765  4235  4235 D HeadsetStateMachine: make
08-16 11:22:05.765  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:22:05.768  4235  4247 I BluetoothAdapterState: Entering PendingCommandState
,08-16 11:22:05.777  4235  4235 D HeadsetStateMachine: max_hf_connections = 1
08-16 11:22:05.777  4235  4235 I bt_bluedroid: get_profile_interface handsfree
08-16 11:22:05.777  4235  4251 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-16 11:22:05.777  4235  4251 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-16 11:22:05.782  4235  4235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf87833
,08-16 11:22:05.782  4235  4235 D A2dpService: Received start request. Starting profile...
,08-16 11:22:05.783  4235  4235 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 11:22:05.783  4235  4235 I bt_bluedroid: get_profile_interface avrcp
,08-16 11:22:05.788  4235  4235 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 11:22:05.788  4235  4235 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 11:22:05.789  4235  4235 D A2dpStateMachine: make
,08-16 11:22:05.790  4235  4235 I bt_bluedroid: get_profile_interface a2dp
08-16 11:22:05.790  4235  4251 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 11:22:05.792  4235  4266 D A2dpStateMachine: Enter Disconnected: -2
,08-16 11:22:05.792  4235  4235 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 11:22:05.793  4235  4235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf87833
,08-16 11:22:05.795  4235  4235 D HidService: Received start request. Starting profile...
,08-16 11:22:05.795  4006  4006 D BluetoothInputDevice: Proxy object connected
08-16 11:22:05.795  4235  4235 I bt_bluedroid: get_profile_interface hidhost
08-16 11:22:05.795  4235  4235 D HidService: setHidService(): set to: null
08-16 11:22:05.795  4235  4251 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39d03e5
08-16 11:22:05.795  4235  4251 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 11:22:05.795  4006  4006 D HidProfile: Bluetooth service connected
,08-16 11:22:05.796  4235  4235 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 11:22:05.796  4235  4235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf87833
08-16 11:22:05.797  4235  4235 D HealthService: Received start request. Starting profile...
08-16 11:22:05.798  4235  4235 I bt_bluedroid: get_profile_interface health
,08-16 11:22:05.800  4235  4235 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 11:22:05.801  4235  4235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf87833
,08-16 11:22:05.802  4006  4006 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 11:22:05.802  4235  4235 D PanService: Received start request. Starting profile...
08-16 11:22:05.802  4235  4235 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 11:22:05.802  4235  4235 I bt_bluedroid: get_profile_interface pan
08-16 11:22:05.802  4006  4006 D PanProfile: Bluetooth service connected
,08-16 11:22:05.803  4235  4251 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 11:22:05.806  4235  4235 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf87833
,08-16 11:22:05.807  4235  4235 D BluetoothMapService: Received start request. Starting profile...
08-16 11:22:05.807  4235  4235 D BluetoothMapService: start()
08-16 11:22:05.807  4006  4006 D BluetoothMap: Proxy object connected
08-16 11:22:05.808  4006  4006 D MapProfile: Bluetooth service connected
08-16 11:22:05.808  4006  4006 D BluetoothMap: getConnectedDevices()
08-16 11:22:05.808  4006  4006 D BluetoothMap: Bluetooth is Not enabled
,08-16 11:22:05.810  4235  4235 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 11:22:05.810  4235  4235 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-16 11:22:05.810  4235  4235 D BluetoothMapAppObserver: createReceiver()
,08-16 11:22:05.812  4235  4235 D BluetoothMapAppObserver: initObservers()
,08-16 11:22:05.812  4235  4235 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 11:22:05.821  4235  4264 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-16 11:22:05.821  4235  4235 V BluetoothAdapterState: isTurningOff()=false
,08-16 11:22:05.821  4235  4235 V BluetoothAdapterState: isTurningOn()=true
,08-16 11:22:05.821  4235  4235 V BluetoothAdapterState: isBleTurningOn()=false
08-16 11:22:05.822  4235  4235 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 11:22:05.822  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 11:22:05.823  4235  4235 V BluetoothAdapterState: isTurningOff()=false
,08-16 11:22:05.823  4235  4235 V BluetoothAdapterState: isTurningOn()=true
,08-16 11:22:05.823  4235  4235 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 11:22:05.824  4235  4235 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 11:22:05.824  4235  4235 V BluetoothAdapterState: isTurningOff()=false
,08-16 11:22:05.824  4235  4235 V BluetoothAdapterState: isTurningOn()=true
08-16 11:22:05.824  4235  4235 V BluetoothAdapterState: isBleTurningOn()=false
08-16 11:22:05.824  4235  4235 V BluetoothAdapterState: isBleTurningOff()=false
08-16 11:22:05.824  4235  4235 V BluetoothAdapterState: isTurningOff()=false
08-16 11:22:05.824  4235  4235 V BluetoothAdapterState: isTurningOn()=true
08-16 11:22:05.824  4235  4235 V BluetoothAdapterState: isBleTurningOn()=false
08-16 11:22:05.824  4235  4235 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 11:22:05.825  4235  4235 V BluetoothAdapterState: isTurningOff()=false
08-16 11:22:05.825  4235  4235 V BluetoothAdapterState: isTurningOn()=true
08-16 11:22:05.825  4235  4235 V BluetoothAdapterState: isBleTurningOn()=false
08-16 11:22:05.825  4235  4235 V BluetoothAdapterState: isBleTurningOff()=false
08-16 11:22:05.825  4235  4235 V BluetoothAdapterState: isTurningOff()=false
08-16 11:22:05.825  4235  4235 V BluetoothAdapterState: isTurningOn()=true
,08-16 11:22:05.825  4235  4235 V BluetoothAdapterState: isBleTurningOn()=false
08-16 11:22:05.825  4235  4235 V BluetoothAdapterState: isBleTurningOff()=false
08-16 11:22:05.826  4235  4247 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 11:22:05.826  4235  4247 D BluetoothAdapterProperties: ScanMode =  20
08-16 11:22:05.826  4235  4247 D BluetoothAdapterProperties: State =  11
,08-16 11:22:05.826  4235  4247 D BluetoothAdapterProperties: Setting state to 12
08-16 11:22:05.827  4235  4247 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 11:22:05.827   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 11:22:05.828  4235  4247 I BluetoothAdapterState: Entering OnState
08-16 11:22:05.828  4235  4251 D BluetoothAdapterProperties: Scan Mode:21
08-16 11:22:05.828  4006  4016 D BluetoothPan: onBluetoothStateChange on: true
,08-16 11:22:05.828  4235  4251 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 11:22:05.828  1374  1391 D BluetoothMap: onBluetoothStateChange: up=true
08-16 11:22:05.831  1374  1374 D BluetoothMap: Proxy object connected
08-16 11:22:05.831  1374  1374 D MapProfile: Bluetooth service connected
08-16 11:22:05.831  1374  1374 D BluetoothMap: getConnectedDevices()
08-16 11:22:05.831  4006  4017 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 11:22:05.833  1374  1392 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 11:22:05.836  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:22:05.836  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:22:05.836  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:22:05.836  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:22:05.836  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:22:05.836  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:22:05.836  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:22:05.836  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 11:22:05.836  4006  4016 D BluetoothMap: onBluetoothStateChange: up=true
08-16 11:22:05.836  1374  1374 D BluetoothInputDevice: Proxy object connected
08-16 11:22:05.836  1374  1374 D HidProfile: Bluetooth service connected
08-16 11:22:05.837  1374  1391 D BluetoothPan: onBluetoothStateChange on: true
08-16 11:22:05.838  4235  4235 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 11:22:05.839  4235  4235 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 11:22:05.839  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:22:05.842  4235  4235 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 11:22:05.843  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:22:05.843  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:22:05.843  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:22:05.843  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:22:05.843  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:22:05.843  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:22:05.843  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:22:05.843  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:22:05.843  1374  1374 D BluetoothPan: BluetoothPAN Proxy object connected
,08-16 11:22:05.843  1374  1374 D PanProfile: Bluetooth service connected
08-16 11:22:05.844  1998  2011 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 11:22:05.845  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:22:05.845  4006  4017 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 11:22:05.846   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 11:22:05.846  1374  1392 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 11:22:05.848  4235  4235 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 11:22:05.848  1374  2067 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 11:22:05.849  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:22:05.849  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:22:05.849  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:22:05.849  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:22:05.849  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:22:05.849  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:22:05.849  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:22:05.849  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:22:05.849   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true,
08-16 11:22:05.850  4235  4235 D ObexServerSockets: Succeed to create listening sockets 
08-16 11:22:05.850   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 11:22:05.850  4235  4235 D ObexServerSockets0: startAccept()
,08-16 11:22:05.850  4235  4235 D ObexServerSockets0: prepareForNewConnect()
08-16 11:22:05.850  1374  1391 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 11:22:05.851  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 11:22:05.852  4235  4235 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-16 11:22:05.852  4235  4235 D BluetoothSdpJni: SDP Create record success - handle: 0
08-16 11:22:05.853  4235  4272 D ObexServerSockets0: Accepting socket connection...
08-16 11:22:05.853  4235  4273 D ObexServerSockets0: Accepting socket connection...
,08-16 11:22:05.853   873   873 D BluetoothA2dp: Proxy object connected
,08-16 11:22:05.854  1374  1374 D BluetoothA2dp: Proxy object connected
,08-16 11:22:05.855  4235  4235 D BluetoothMapService: onReceive
08-16 11:22:05.855  4235  4235 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:22:05.856  4235  4235 D BluetoothMapService: STATE_ON
08-16 11:22:05.858   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 11:22:05.861  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:22:05.861  4006  4006 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 11:22:05.862  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:22:05.863  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:22:05.865  4006  4006 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-16 11:22:05.871  4006  4006 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 11:22:05.873  4006  4006 D BluetoothA2dp: Proxy object connected
,08-16 11:22:05.876  4235  4235 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 11:22:05.877  4235  4235 D ObexServerSockets0: prepareForNewConnect()
,08-16 11:22:05.879  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 11:22:05.885  4006  4006 D DockEventReceiver: finishStartingService: stopping service
,08-16 11:22:05.886  1374  1374 D BluetoothPbap: Proxy object connected
08-16 11:22:05.886  1374  1374 D PbapServerProfile: Bluetooth service connected
,08-16 11:22:05.888  4006  4006 D BluetoothPbap: Proxy object connected
,08-16 11:22:05.894  4006  4006 D PbapServerProfile: Bluetooth service connected
,08-16 11:22:05.899  4235  4279 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 11:22:05.913  4235  4283 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 11:22:05.914  4235  4283 I BtOppRfcommListener: Accept thread started.
,08-16 11:22:05.929   873   873 D BluetoothHeadset: Proxy object connected
,08-16 11:22:05.929   873   873 D BluetoothHeadset: Proxy object connected
08-16 11:22:05.929  1998  2014 D BluetoothHeadset: Proxy object connected
,08-16 11:22:05.930   873   873 D BluetoothHeadset: Proxy object connected
08-16 11:22:05.930  1374  2067 D BluetoothHeadset: Proxy object connected
08-16 11:22:05.930  1374  1374 D HeadsetProfile: Bluetooth service connected
,08-16 11:22:05.944  1998  2078 D BluetoothHeadset: Proxy object connected
,08-16 11:22:05.946   873   890 D BluetoothHeadset: Proxy object connected
,08-16 11:22:05.950  1374  1391 D BluetoothHeadset: Proxy object connected
,08-16 11:22:05.950  1374  1374 D HeadsetProfile: Bluetooth service connected
08-16 11:22:05.950   873   890 D BluetoothHeadset: Proxy object connected
,08-16 11:22:05.968  4006  4016 D BluetoothHeadset: Proxy object connected
,08-16 11:22:05.969  4006  4006 D HeadsetProfile: Bluetooth service connected
,08-16 11:22:08.762  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:22:08.777  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:22:08.783  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:22:08.859  1516  2189 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,08-16 11:22:08.859  1516  2189 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
,08-16 11:22:08.860  1516  2189 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 11:22:08.860  1516  2189 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:22:08.916  3508  3508 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,08-16 11:22:08.919  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,08-16 11:22:08.922  3508  3508 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,08-16 11:22:09.247  4235  4247 D BluetoothAdapterState: Current state: ON, message: 23
,08-16 11:22:09.248  4235  4247 D BluetoothAdapterProperties: Setting state to 13
,08-16 11:22:09.248  4235  4247 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 11:22:09.250  4235  4247 D BluetoothAdapterProperties: onBluetoothDisable()
,08-16 11:22:09.255  4235  4247 I BluetoothAdapterState: Entering PendingCommandState
,08-16 11:22:09.261  4235  4235 D BluetoothMapService: onReceive
,08-16 11:22:09.262  4235  4235 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 11:22:09.262  4235  4235 D BluetoothMapService: STATE_TURNING_OFF
08-16 11:22:09.263  4235  4235 D BluetoothMapService: MAP Service closeService in,
08-16 11:22:09.263  4235  4235 D BluetoothMapMasInstance0: MAP Service shutdown
,08-16 11:22:09.263  4235  4235 D ObexServerSockets0: shutdown(block = true)
08-16 11:22:09.265  4235  4272 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-16 11:22:09.267  4235  4235 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 11:22:09.267  4235  4259 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-16 11:22:09.267  4235  4235 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-16 11:22:09.267  4235  4273 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,08-16 11:22:09.268  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 11:22:09.269  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:22:09.269  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:22:09.269  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:22:09.269  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:22:09.269  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:22:09.269  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:22:09.269  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:22:09.269  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:22:09.270  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 11:22:09.270  4235  4251 D BluetoothAdapterProperties: Scan Mode:20
,08-16 11:22:09.270  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:22:09.271  4235  4235 I BtOppRfcommListener: stopping Accept Thread
08-16 11:22:09.272  4235  4247 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-16 11:22:09.272  4235  4283 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 11:22:09.275  4235  4283 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-16 11:22:09.276  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:22:09.276  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:22:09.276  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:22:09.276  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:22:09.276  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:22:09.276  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:22:09.276  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:22:09.276  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:22:09.276  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:22:09.278  4006  4006 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 11:22:09.280  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:22:09.280  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:22:09.283  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:22:09.283  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:22:09.283  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:22:09.283  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:22:09.283  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:22:09.283  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 11:22:09.283  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:22:09.283  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:22:09.283  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 11:22:09.283  3799  3799 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 11:22:09.283  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:22:09.286  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:22:09.286  4235  4235 D HeadsetService: Received stop request...Stopping profile...
,08-16 11:22:09.287  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:22:09.288  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:22:09.289   873   873 D BluetoothHeadset: Proxy object disconnected
,08-16 11:22:09.289  4006  4016 D BluetoothHeadset: Proxy object disconnected
08-16 11:22:09.290   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 11:22:09.290  1998  2011 D BluetoothHeadset: Proxy object disconnected
08-16 11:22:09.290   873   873 D BluetoothHeadset: Proxy object disconnected
08-16 11:22:09.291  1374  2067 D BluetoothHeadset: Proxy object disconnected
08-16 11:22:09.291  4235  4235 D A2dpService: Received stop request...Stopping profile...
,08-16 11:22:09.291  4235  4266 D A2dpStateMachine: Exit Disconnected: -1
08-16 11:22:09.292   873   873 D BluetoothA2dp: Proxy object disconnected
08-16 11:22:09.294  4235  4235 D HidService: Received stop request...Stopping profile...
08-16 11:22:09.294  4235  4235 D HidService: Stopping Bluetooth HidService
,08-16 11:22:09.295  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 11:22:09.296  4235  4235 D HealthService: Received stop request...Stopping profile...
08-16 11:22:09.297  4235  4235 D PanService: Received stop request...Stopping profile...
08-16 11:22:09.298  1374  1374 D HeadsetProfile: Bluetooth service disconnected
,08-16 11:22:09.298  1374  1374 D BluetoothA2dp: Proxy object disconnected
08-16 11:22:09.298  1374  1374 D BluetoothInputDevice: Proxy object disconnected
08-16 11:22:09.298  1374  1374 D HidProfile: Bluetooth service disconnected
08-16 11:22:09.298  1374  1374 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 11:22:09.298  1374  1374 D PanProfile: Bluetooth service disconnected
08-16 11:22:09.299  4235  4235 D BluetoothMapService: Received stop request...Stopping profile...
08-16 11:22:09.299  4235  4235 D BluetoothMapService: stop()
08-16 11:22:09.300  4235  4235 D BluetoothMapAppObserver: deinitObservers()
,08-16 11:22:09.300  4235  4235 D BluetoothMapAppObserver: removeReceiver()
08-16 11:22:09.301  1374  1374 D BluetoothMap: Proxy object disconnected
08-16 11:22:09.301  1374  1374 D MapProfile: Bluetooth service disconnected
08-16 11:22:09.301  4235  4235 V BluetoothAdapterState: isTurningOff()=true
08-16 11:22:09.301  4235  4235 V BluetoothAdapterState: isTurningOn()=false
08-16 11:22:09.301  4235  4235 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 11:22:09.301  4235  4235 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 11:22:09.304  4235  4235 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 11:22:09.304  4235  4235 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 11:22:09.304  4235  4251 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-16 11:22:09.304  4235  4257 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 11:22:09.304  4006  4006 D DockEventReceiver: finishStartingService: stopping service
,08-16 11:22:09.304  4235  4257 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 11:22:09.304  4235  4257 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 11:22:09.304  4235  4251 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-16 11:22:09.307  4006  4006 D HeadsetProfile: Bluetooth service disconnected
,08-16 11:22:09.307  1374  1374 D BluetoothPbap: Proxy object disconnected
08-16 11:22:09.307  1374  1374 D PbapServerProfile: Bluetooth service disconnected
08-16 11:22:09.307  4006  4006 D BluetoothA2dp: Proxy object disconnected
08-16 11:22:09.308  4006  4006 D BluetoothInputDevice: Proxy object disconnected
08-16 11:22:09.308  4235  4235 V BluetoothAdapterState: isTurningOff()=true
08-16 11:22:09.308  4006  4006 D HidProfile: Bluetooth service disconnected
08-16 11:22:09.308  4235  4235 V BluetoothAdapterState: isTurningOn()=false
,08-16 11:22:09.308  4235  4235 V BluetoothAdapterState: isBleTurningOn()=false
08-16 11:22:09.308  4235  4235 V BluetoothAdapterState: isBleTurningOff()=false
08-16 11:22:09.309  4006  4006 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 11:22:09.309  4006  4006 D PanProfile: Bluetooth service disconnected
08-16 11:22:09.309  4006  4006 D BluetoothMap: Proxy object disconnected
,08-16 11:22:09.309  4006  4006 D MapProfile: Bluetooth service disconnected
08-16 11:22:09.309  4235  4257 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 11:22:09.309  4235  4235 V BluetoothAdapterState: isTurningOff()=true
08-16 11:22:09.309  4235  4257 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-16 11:22:09.309  4235  4235 V BluetoothAdapterState: isTurningOn()=false
08-16 11:22:09.309  4235  4235 V BluetoothAdapterState: isBleTurningOn()=false
08-16 11:22:09.309  4235  4235 V BluetoothAdapterState: isBleTurningOff()=false
08-16 11:22:09.309  4235  4257 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 11:22:09.309  4235  4257 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 11:22:09.309  4235  4257 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-16 11:22:09.310  4235  4257 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 11:22:09.309  4006  4006 D BluetoothPbap: Proxy object disconnected
08-16 11:22:09.310  4235  4251 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-16 11:22:09.310  4006  4006 D PbapServerProfile: Bluetooth service disconnected
,08-16 11:22:09.311  4235  4235 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 11:22:09.312  4235  4251 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-16 11:22:09.312  4235  4235 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 11:22:09.312  4235  4235 V BluetoothAdapterState: isTurningOff()=true
08-16 11:22:09.312  4235  4235 V BluetoothAdapterState: isTurningOn()=false
08-16 11:22:09.312  4235  4235 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 11:22:09.312  4235  4235 V BluetoothAdapterState: isBleTurningOff()=false
08-16 11:22:09.313  4235  4235 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 11:22:09.313  4235  4251 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-16 11:22:09.313  4235  4235 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 11:22:09.314  4235  4235 V BluetoothAdapterState: isTurningOff()=true
,08-16 11:22:09.314  4235  4235 V BluetoothAdapterState: isTurningOn()=false
,08-16 11:22:09.314  4235  4235 V BluetoothAdapterState: isBleTurningOn()=false
08-16 11:22:09.314  4235  4235 V BluetoothAdapterState: isBleTurningOff()=false
08-16 11:22:09.316  4235  4235 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 11:22:09.316  4235  4235 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 11:22:09.317  4235  4235 D BluetoothMapService: MAP Service closeService in
,08-16 11:22:09.317  4235  4235 V BluetoothAdapterState: isTurningOff()=true
08-16 11:22:09.318  4235  4235 V BluetoothAdapterState: isTurningOn()=false
08-16 11:22:09.318  4235  4235 V BluetoothAdapterState: isBleTurningOn()=false
08-16 11:22:09.318  4235  4235 V BluetoothAdapterState: isBleTurningOff()=false
08-16 11:22:09.318  4235  4247 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-16 11:22:09.318  4235  4247 D BluetoothAdapterProperties: Setting state to 15
08-16 11:22:09.318  4235  4247 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-16 11:22:09.319  4235  4235 D BluetoothMapService: cleanup()
08-16 11:22:09.319  4235  4235 D BluetoothMapService: MAP Service closeService in
08-16 11:22:09.320   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 11:22:09.320  4235  4247 I BluetoothAdapterState: Entering BleOnState
08-16 11:22:09.320  4006  4017 D BluetoothPan: onBluetoothStateChange on: false
,08-16 11:22:09.321  1374  1392 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 11:22:09.322  4006  4016 D BluetoothPbap: onBluetoothStateChange: up=false
,08-16 11:22:09.323  1374  1391 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 11:22:09.324  4006  4017 D BluetoothMap: onBluetoothStateChange: up=false
,08-16 11:22:09.324  1374  2067 D BluetoothPan: onBluetoothStateChange on: false
,08-16 11:22:09.325  1998  2014 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 11:22:09.325  4006  4016 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 11:22:09.326   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 11:22:09.326  1374  1392 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 11:22:09.327  1374  1391 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 11:22:09.327   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 11:22:09.327   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 11:22:09.327  4006  4017 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-16 11:22:09.328  4006  4016 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 11:22:09.328  1374  2067 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 11:22:09.329  4235  4247 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-16 11:22:09.329  4235  4247 D BluetoothAdapterProperties: Setting state to 16
08-16 11:22:09.329  4235  4247 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,08-16 11:22:09.331  4235  4247 D BluetoothAdapterProperties: onBleDisable
,08-16 11:22:09.331  4235  4247 I BluetoothAdapterState: Entering PendingCommandState
,08-16 11:22:09.331  4235  4248 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,08-16 11:22:09.332  4235  4251 D BluetoothAdapterProperties: Scan Mode:20
08-16 11:22:09.333  4235  4257 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-16 11:22:09.333  4235  4257 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-16 11:22:09.333  4006  4006 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 11:22:09.334  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:22:09.337  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:22:09.339  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:22:09.340  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:22:09.341  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:22:09.342  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:22:09.342  4006  4006 D DockEventReceiver: finishStartingService: stopping service
,08-16 11:22:09.343  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 11:22:09.538  4235  4251 I bt_hci  : shut_down
,08-16 11:22:09.539  4235  4255 D bt_hwcfg: hw_epilog_process
,08-16 11:22:09.540  4235  4255 I bt_vendor: low_power_mode_cb
,08-16 11:22:09.560  4235  4255 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-16 11:22:09.560  4235  4255 I bt_vendor: epilog_cb
08-16 11:22:09.561  4235  4255 I bt_hci  : epilog_finished_callback
,08-16 11:22:09.570  4235  4251 I bt_hci_h4: hal_close
,08-16 11:22:09.572  4235  4251 I bt_userial_vendor: device fd = 51 close
,08-16 11:22:09.698  4235  4248 D bt_stack_manager: event_shut_down_stack finished.
,08-16 11:22:09.699  4235  4247 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-16 11:22:09.707  4235  4247 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-16 11:22:09.708  4235  4235 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-16 11:22:09.711  4235  4235 D BtGatt.GattService: Received stop request...Stopping profile...
,08-16 11:22:09.711  4235  4235 D BtGatt.GattService: stop()
08-16 11:22:09.711  4235  4235 D BtGatt.AdvertiseManager: advertise clients cleared
,08-16 11:22:09.717  4235  4235 V BluetoothAdapterState: isTurningOff()=false
,08-16 11:22:09.717  4235  4235 V BluetoothAdapterState: isTurningOn()=false
,08-16 11:22:09.717  4235  4235 V BluetoothAdapterState: isBleTurningOn()=false
08-16 11:22:09.718  4235  4235 V BluetoothAdapterState: isBleTurningOff()=true
08-16 11:22:09.718  4235  4247 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-16 11:22:09.719  4235  4247 D BluetoothAdapterProperties: Setting state to 10
08-16 11:22:09.719  4235  4247 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-16 11:22:09.725  4235  4247 I BluetoothAdapterState: Entering OffState
08-16 11:22:09.725   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-16 11:22:09.742  4235  4235 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-16 11:22:09.742  4235  4235 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-16 11:22:09.742  4235  4235 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 11:22:09.744  4235  4248 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-16 11:22:09.747  4235  4248 D bt_stack_manager: event_clean_up_stack finished.
,08-16 11:22:09.749  4235  4235 I art     : System.exit called, status: 0
08-16 11:22:09.749  4235  4235 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-16 11:22:09.789   873  1695 I ActivityManager: Process com.android.bluetooth (pid 4235) has died
,08-16 11:22:11.342  1886  1960 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-16 11:22:11.342  1886  1960 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-16 11:22:11.391  1516  1516 I ConfigService: onCreate
,08-16 11:22:14.244  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:22:14.244  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:22:16.485  1516  1516 I ConfigService: onDestroy
,08-16 11:22:19.249  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:22:19.250  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b54ac9 removed from the list
,08-16 11:22:19.250  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:22:19.251  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:22:19.251  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:22:19.255  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 11:22:19.255  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d66acef added. We now have 4 listener(s)
08-16 11:22:19.257  3799  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 11:22:19.259  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:22:19.260  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d66acef removed from the list
,08-16 11:22:19.261  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:22:19.262  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 11:22:19.263  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:22:19.266  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 11:22:19.266  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d42a3fc added. We now have 4 listener(s)
08-16 11:22:19.266  3799  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 11:22:21.271  3799  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:22:21.323   873   890 I ActivityManager: Start proc 4294:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-16 11:22:21.465  4294  4294 D AdapterServiceConfig: Adding HeadsetService
08-16 11:22:21.465  4294  4294 D AdapterServiceConfig: Adding A2dpService
08-16 11:22:21.465  4294  4294 D AdapterServiceConfig: Adding HidService
08-16 11:22:21.465  4294  4294 D AdapterServiceConfig: Adding HealthService
08-16 11:22:21.466  4294  4294 D AdapterServiceConfig: Adding PanService
,08-16 11:22:21.466  4294  4294 D AdapterServiceConfig: Adding GattService
,08-16 11:22:21.466  4294  4294 D AdapterServiceConfig: Adding BluetoothMapService
,08-16 11:22:21.479   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@61a277e:true
08-16 11:22:21.479  4294  4294 D BluetoothAdapterState: make() - Creating AdapterState
,08-16 11:22:21.484  4294  4294 I bt_bluedroid: init
,08-16 11:22:21.485  4294  4306 I BluetoothAdapterState: Entering OffState
,08-16 11:22:21.488  4294  4307 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 11:22:21.488  4294  4307 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 11:22:21.488  4294  4307 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 11:22:21.488  4294  4307 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-16 11:22:21.489  4294  4294 I bt_bluedroid: get_profile_interface socket
,08-16 11:22:21.492  4294  4294 I bt_bluedroid: get_profile_interface sdp
,08-16 11:22:21.494  4294  4305 I bt_bluedroid: config_hci_snoop_log
08-16 11:22:21.495  4294  4310 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-16 11:22:21.495   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-16 11:22:21.498  4294  4310 D BluetoothAdapterProperties: Name is: Nexus 6
,08-16 11:22:21.513  4294  4306 D BluetoothAdapterState: Current state: OFF, message: 0
08-16 11:22:21.513  4294  4306 D BluetoothAdapterProperties: Setting state to 14
,08-16 11:22:21.514  4294  4306 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-16 11:22:21.518  4294  4306 D BluetoothBondStateMachine: make
,08-16 11:22:21.521  4294  4311 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-16 11:22:21.528  4294  4306 I BluetoothAdapterState: Entering PendingCommandState
,08-16 11:22:21.528  4294  4294 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-16 11:22:21.531  4294  4294 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf87833
,08-16 11:22:21.531  4294  4294 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 11:22:21.532  4294  4294 D BtGatt.GattService: Received start request. Starting profile...
08-16 11:22:21.532  4294  4294 D BtGatt.GattService: start()
08-16 11:22:21.532  4294  4294 I bt_bluedroid: get_profile_interface gatt
,08-16 11:22:21.533  4294  4294 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf87833
08-16 11:22:21.533  4294  4294 D BtGatt.AdvertiseManager: advertise manager created
,08-16 11:22:21.541  4294  4294 V BluetoothAdapterState: isTurningOff()=false
08-16 11:22:21.541  4294  4294 V BluetoothAdapterState: isTurningOn()=false
08-16 11:22:21.541  4294  4294 V BluetoothAdapterState: isBleTurningOn()=true
08-16 11:22:21.541  4294  4294 V BluetoothAdapterState: isBleTurningOff()=false
08-16 11:22:21.542  4294  4306 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-16 11:22:21.542  4294  4306 I bt_bluedroid: enable
,08-16 11:22:21.542  4294  4307 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-16 11:22:21.542  4294  4307 I bt_hci  : start_up
,08-16 11:22:21.548  4294  4307 I bt_vendor: alloc value 0xb3a71189
08-16 11:22:21.548  4294  4307 I bt_vendor: init
08-16 11:22:21.548  4294  4307 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-16 11:22:21.549  4294  4307 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-16 11:22:21.656  4294  4307 D bt_hci  : start_up starting async portion
,08-16 11:22:21.657  4294  4314 I bt_hci  : event_finish_startup
08-16 11:22:21.658  4294  4314 I bt_hci_h4: hal_open
08-16 11:22:21.658  4294  4314 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-16 11:22:21.670  4294  4314 I bt_userial_vendor: device fd = 51 open
,08-16 11:22:21.700  4294  4314 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 11:22:21.731  4294  4314 D bt_hwcfg: Chipset BCM4354A2
08-16 11:22:21.731  4294  4314 D bt_hwcfg: Target name = [BCM4354A2]
,08-16 11:22:21.732  4294  4314 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-16 11:22:22.600  4294  4314 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-16 11:22:22.601  4294  4314 D bt_hwcfg: Settlement delay -- 100 ms
,08-16 11:22:22.602  4294  4314 I bt_hwcfg: Setting fw settlement delay to 100 
,08-16 11:22:22.720  4294  4314 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-16 11:22:22.722  4294  4314 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-16 11:22:22.749  4294  4314 I bt_hwcfg: vendor lib fwcfg completed
,08-16 11:22:22.750  4294  4314 I bt_vendor: firmware callback
08-16 11:22:22.750  4294  4314 I bt_hci  : firmware_config_callback
,08-16 11:22:22.763  4294  4316 I bt_btu  : btu_task pending for preload complete event
08-16 11:22:22.764  4294  4316 I bt_btu_task: Bluetooth chip preload is complete
08-16 11:22:22.764  4294  4316 I bt_btu  : btu_task received preload complete event
,08-16 11:22:22.774  4294  4316 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 11:22:22.774  4294  4316 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 11:22:22.775  4294  4316 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 11:22:22.775  4294  4316 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 11:22:22.775  4294  4316 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 11:22:22.776  4294  4316 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 11:22:22.776  4294  4316 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 11:22:22.776  4294  4316 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 11:22:22.776  4294  4316 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 11:22:22.777  4294  4316 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 11:22:22.777  4294  4316 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 11:22:22.777  4294  4316 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 11:22:22.778  4294  4316 I         : BTE_InitTraceLevels -- TRC_SMP
,08-16 11:22:22.778  4294  4316 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-16 11:22:22.778  4294  4316 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 11:22:22.935  4294  4316 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39eed9d
08-16 11:22:22.935  4294  4316 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39eed9d ,
,08-16 11:22:22.945  4294  4310 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-16 11:22:22.948  4294  4310 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-16 11:22:22.949  4294  4310 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-16 11:22:22.951  4294  4310 D BluetoothAdapterProperties: Name is: Nexus 6
08-16 11:22:22.954  4294  4310 D BluetoothAdapterProperties: Scan Mode:20
08-16 11:22:22.956  4294  4310 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-16 11:22:22.956  4294  4310 D bt_hci  : do_postload posting postload work item
,08-16 11:22:22.957  4294  4314 I bt_hci  : event_postload
08-16 11:22:22.957  4294  4314 I bt_vendor: sco_config_cb
08-16 11:22:22.957  4294  4314 I bt_hci  : sco_config_callback postload finished.
,08-16 11:22:22.960  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:22:22.964  4294  4310 D bt_bte_conf: Device ID record 1 : primary
08-16 11:22:22.964  4294  4310 D bt_bte_conf:   vendorId            = 000f
,08-16 11:22:22.965  4294  4310 D bt_bte_conf:   vendorIdSource      = 0001
08-16 11:22:22.965  4294  4310 D bt_bte_conf:   product             = 1200
08-16 11:22:22.965  4294  4310 D bt_bte_conf:   version             = 1436
08-16 11:22:22.965  4294  4310 D bt_bte_conf:   clientExecutableURL = 
08-16 11:22:22.965  4294  4310 D bt_bte_conf:   serviceDescription  = 
08-16 11:22:22.966  4294  4310 D bt_bte_conf:   documentationURL    = 
08-16 11:22:22.966  4294  4314 I bt_vendor: low_power_mode_cb
08-16 11:22:22.966  4294  4310 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-16 11:22:22.966  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:22:22.966  4294  4307 D bt_stack_manager: event_start_up_stack finished
08-16 11:22:22.967  4294  4306 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,08-16 11:22:22.967  4294  4306 D BluetoothAdapterProperties: Setting state to 15
08-16 11:22:22.967  4294  4306 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-16 11:22:22.968  4294  4306 I BluetoothAdapterState: Entering BleOnState
,08-16 11:22:22.975  4294  4306 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-16 11:22:22.976  4294  4306 D BluetoothAdapterProperties: Setting state to 11
08-16 11:22:22.976  4294  4306 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-16 11:22:22.986  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:22:22.989  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:22:22.992  4294  4294 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf87833
,08-16 11:22:22.994  4294  4294 D HeadsetService: Received start request. Starting profile...
,08-16 11:22:22.999  4294  4294 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 11:22:23.000  4294  4294 D HeadsetStateMachine: make
,08-16 11:22:23.001  4294  4306 I BluetoothAdapterState: Entering PendingCommandState
,08-16 11:22:23.008  4294  4294 D HeadsetStateMachine: max_hf_connections = 1
,08-16 11:22:23.008  4294  4294 I bt_bluedroid: get_profile_interface handsfree
08-16 11:22:23.008  4294  4310 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,08-16 11:22:23.008  4294  4310 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-16 11:22:23.012  4294  4294 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf87833
,08-16 11:22:23.012  4294  4294 D A2dpService: Received start request. Starting profile...
,08-16 11:22:23.013  4294  4294 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 11:22:23.013  4294  4294 I bt_bluedroid: get_profile_interface avrcp
,08-16 11:22:23.020  4294  4294 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 11:22:23.020  4294  4294 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-16 11:22:23.020  4294  4294 D A2dpStateMachine: make
,08-16 11:22:23.021  4294  4294 I bt_bluedroid: get_profile_interface a2dp
,08-16 11:22:23.022  4294  4310 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-16 11:22:23.025  4294  4325 D A2dpStateMachine: Enter Disconnected: -2
,08-16 11:22:23.027  4294  4294 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 11:22:23.028  4294  4294 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf87833
08-16 11:22:23.029  4294  4294 D HidService: Received start request. Starting profile...
08-16 11:22:23.029  4294  4294 I bt_bluedroid: get_profile_interface hidhost
08-16 11:22:23.029  4294  4294 D HidService: setHidService(): set to: null
08-16 11:22:23.029  4294  4310 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39d03e5
08-16 11:22:23.029  4294  4310 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-16 11:22:23.030  4294  4294 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 11:22:23.031  4294  4294 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf87833
,08-16 11:22:23.031  4294  4294 D HealthService: Received start request. Starting profile...
,08-16 11:22:23.030  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 11:22:23.034  4294  4294 I bt_bluedroid: get_profile_interface health
,08-16 11:22:23.035  4294  4294 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-16 11:22:23.037  4294  4294 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf87833
,08-16 11:22:23.038  4294  4294 D PanService: Received start request. Starting profile...
,08-16 11:22:23.039  4294  4294 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 11:22:23.039  4294  4294 I bt_bluedroid: get_profile_interface pan
,08-16 11:22:23.040  4294  4310 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-16 11:22:23.044  4294  4294 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf87833
,08-16 11:22:23.045  4294  4294 D BluetoothMapService: Received start request. Starting profile...
,08-16 11:22:23.045  4294  4294 D BluetoothMapService: start()
,08-16 11:22:23.048  4294  4294 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-16 11:22:23.050  4294  4294 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-16 11:22:23.050  4294  4294 D BluetoothMapAppObserver: createReceiver()
,08-16 11:22:23.051  4294  4294 D BluetoothMapAppObserver: initObservers()
,08-16 11:22:23.051  4294  4294 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-16 11:22:23.061  4294  4294 V BluetoothAdapterState: isTurningOff()=false
,08-16 11:22:23.062  4294  4294 V BluetoothAdapterState: isTurningOn()=true
08-16 11:22:23.062  4294  4294 V BluetoothAdapterState: isBleTurningOn()=false
08-16 11:22:23.062  4294  4294 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 11:22:23.064  4294  4294 V BluetoothAdapterState: isTurningOff()=false
,08-16 11:22:23.064  4294  4294 V BluetoothAdapterState: isTurningOn()=true
08-16 11:22:23.064  4294  4294 V BluetoothAdapterState: isBleTurningOn()=false
08-16 11:22:23.064  4294  4294 V BluetoothAdapterState: isBleTurningOff()=false
,08-16 11:22:23.064  4294  4294 V BluetoothAdapterState: isTurningOff()=false
08-16 11:22:23.064  4294  4294 V BluetoothAdapterState: isTurningOn()=true
08-16 11:22:23.064  4294  4294 V BluetoothAdapterState: isBleTurningOn()=false,
08-16 11:22:23.064  4294  4323 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5,
08-16 11:22:23.064  4294  4294 V BluetoothAdapterState: isBleTurningOff()=false
08-16 11:22:23.064  4294  4294 V BluetoothAdapterState: isTurningOff()=false
08-16 11:22:23.065  4294  4294 V BluetoothAdapterState: isTurningOn()=true
08-16 11:22:23.065  4294  4294 V BluetoothAdapterState: isBleTurningOn()=false
,08-16 11:22:23.065  4294  4294 V BluetoothAdapterState: isBleTurningOff()=false
08-16 11:22:23.067  4294  4294 V BluetoothAdapterState: isTurningOff()=false
,08-16 11:22:23.067  4294  4294 V BluetoothAdapterState: isTurningOn()=true
08-16 11:22:23.067  4294  4294 V BluetoothAdapterState: isBleTurningOn()=false
08-16 11:22:23.067  4294  4294 V BluetoothAdapterState: isBleTurningOff()=false
08-16 11:22:23.067  4294  4294 V BluetoothAdapterState: isTurningOff()=false
08-16 11:22:23.067  4294  4294 V BluetoothAdapterState: isTurningOn()=true
08-16 11:22:23.067  4294  4294 V BluetoothAdapterState: isBleTurningOn()=false
08-16 11:22:23.068  4294  4294 V BluetoothAdapterState: isBleTurningOff()=false
08-16 11:22:23.068  4294  4306 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-16 11:22:23.068  4294  4306 D BluetoothAdapterProperties: ScanMode =  20
08-16 11:22:23.068  4294  4306 D BluetoothAdapterProperties: State =  11
,08-16 11:22:23.071  4294  4310 D BluetoothAdapterProperties: Scan Mode:21
08-16 11:22:23.072  4294  4310 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 11:22:23.072  4294  4306 D BluetoothAdapterProperties: Setting state to 12
,08-16 11:22:23.072  4294  4306 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 11:22:23.072   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 11:22:23.072  4294  4306 I BluetoothAdapterState: Entering OnState
08-16 11:22:23.072  4006  4016 D BluetoothPan: onBluetoothStateChange on: true
,08-16 11:22:23.075  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:22:23.075  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:22:23.075  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:22:23.075  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:22:23.075  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:22:23.075  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:22:23.075  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:22:23.075  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 11:22:23.076  1374  2067 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 11:22:23.078  4006  4017 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 11:22:23.076  4006  4006 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 11:22:23.079  4006  4006 D PanProfile: Bluetooth service connected
08-16 11:22:23.079  1374  1374 D BluetoothMap: Proxy object connected
08-16 11:22:23.079  1374  1374 D MapProfile: Bluetooth service connected
08-16 11:22:23.079  1374  1374 D BluetoothMap: getConnectedDevices()
08-16 11:22:23.079  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:22:23.081  1374  1391 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 11:22:23.081  4294  4294 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-16 11:22:23.081  4294  4294 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-16 11:22:23.083  4294  4294 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 11:22:23.083  4006  4016 D BluetoothMap: onBluetoothStateChange: up=true
08-16 11:22:23.084  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:22:23.084  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:22:23.084  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:22:23.084  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:22:23.084  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:22:23.084  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:22:23.084  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:22:23.084  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 11:22:23.086  4294  4294 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 11:22:23.087  1374  2067 D BluetoothPan: onBluetoothStateChange on: true
08-16 11:22:23.087  4006  4006 D BluetoothMap: Proxy object connected
08-16 11:22:23.087  4006  4006 D MapProfile: Bluetooth service connected
,08-16 11:22:23.087  4006  4006 D BluetoothMap: getConnectedDevices()
08-16 11:22:23.088  4294  4294 D ObexServerSockets: Succeed to create listening sockets 
08-16 11:22:23.088  4294  4294 D ObexServerSockets0: startAccept()
08-16 11:22:23.088  4294  4294 D ObexServerSockets0: prepareForNewConnect()
08-16 11:22:23.088  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 11:22:23.089  1374  1374 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 11:22:23.089  1374  1374 D PanProfile: Bluetooth service connected
08-16 11:22:23.089  1998  2078 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 11:22:23.090  4006  4017 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-16 11:22:23.091  4294  4294 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-16 11:22:23.091  4294  4294 D BluetoothSdpJni: SDP Create record success - handle: 0
08-16 11:22:23.093  4294  4332 D ObexServerSockets0: Accepting socket connection...
08-16 11:22:23.093  1374  1374 D BluetoothInputDevice: Proxy object connected
08-16 11:22:23.093  1374  1374 D HidProfile: Bluetooth service connected
08-16 11:22:23.093  4294  4333 D ObexServerSockets0: Accepting socket connection...
,08-16 11:22:23.094   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 11:22:23.094  1374  1392 D BluetoothPbap: onBluetoothStateChange: up=true
,08-16 11:22:23.096  1374  2067 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 11:22:23.096  4006  4006 D BluetoothInputDevice: Proxy object connected
08-16 11:22:23.097  4006  4006 D HidProfile: Bluetooth service connected
08-16 11:22:23.097   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 11:22:23.098   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 11:22:23.098  4006  4016 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 11:22:23.099  4006  4330 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 11:22:23.099   873   873 D BluetoothA2dp: Proxy object connected
,08-16 11:22:23.102  1374  1391 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-16 11:22:23.104  1374  1374 D BluetoothA2dp: Proxy object connected
,08-16 11:22:23.104  4006  4006 D BluetoothA2dp: Proxy object connected
,08-16 11:22:23.106   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,08-16 11:22:23.109  4294  4294 D BluetoothMapService: onReceive
,08-16 11:22:23.109  4294  4294 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 11:22:23.110  4294  4294 D BluetoothMapService: STATE_ON
08-16 11:22:23.110  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:22:23.112  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:22:23.116  4006  4006 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-16 11:22:23.123  4006  4006 D DockEventReceiver: finishStartingService: stopping service
,08-16 11:22:23.124  1516  1516 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 11:22:23.142  4006  4006 D BluetoothPbap: Proxy object connected
08-16 11:22:23.143  4006  4006 D PbapServerProfile: Bluetooth service connected
,08-16 11:22:23.143  1374  1374 D BluetoothPbap: Proxy object connected
08-16 11:22:23.143  1374  1374 D PbapServerProfile: Bluetooth service connected
,08-16 11:22:23.147  4294  4294 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-16 11:22:23.147  4294  4294 D ObexServerSockets0: prepareForNewConnect()
,08-16 11:22:23.152  4294  4339 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 11:22:23.166  4294  4343 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 11:22:23.167  4294  4343 I BtOppRfcommListener: Accept thread started.
,08-16 11:22:23.173   873   873 D BluetoothHeadset: Proxy object connected
,08-16 11:22:23.174  4006  4017 D BluetoothHeadset: Proxy object connected
,08-16 11:22:23.174   873   873 D BluetoothHeadset: Proxy object connected
08-16 11:22:23.174  4006  4006 D HeadsetProfile: Bluetooth service connected
08-16 11:22:23.174  1998  3193 D BluetoothHeadset: Proxy object connected
,08-16 11:22:23.174   873   873 D BluetoothHeadset: Proxy object connected
08-16 11:22:23.175  1374  1391 D BluetoothHeadset: Proxy object connected
08-16 11:22:23.175  1374  1374 D HeadsetProfile: Bluetooth service connected
,08-16 11:22:23.190  1998  2011 D BluetoothHeadset: Proxy object connected
,08-16 11:22:23.194   873   890 D BluetoothHeadset: Proxy object connected
,08-16 11:22:23.198  1374  1392 D BluetoothHeadset: Proxy object connected
,08-16 11:22:23.198  1374  1374 D HeadsetProfile: Bluetooth service connected
08-16 11:22:23.198   873   890 D BluetoothHeadset: Proxy object connected
,08-16 11:22:23.199  4006  4330 D BluetoothHeadset: Proxy object connected
08-16 11:22:23.199  4006  4006 D HeadsetProfile: Bluetooth service connected
,08-16 11:22:23.278  3799  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:22:23.278  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:22:23.278  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:22:23.278  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 11:22:23.278  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:22:23.278  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:22:23.278  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:22:23.278  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 11:22:23.282  3799  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 11:22:23.282  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:22:23.283  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d42a3fc removed from the list
,08-16 11:22:23.283  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:22:23.283  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 11:22:23.284  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:22:23.286  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 11:22:23.286  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@43eca85 added. We now have 4 listener(s)
,08-16 11:22:23.286  3799  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 11:22:23.290   873  1626 D WifiService: setWifiEnabled: false pid=3799, uid=10000,
08-16 11:22:23.290   873  1626 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 11:22:23.297  3799  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:22:23.297   873  2052 D WifiService: setWifiEnabled: true pid=3799, uid=10000
,08-16 11:22:23.298   873  2052 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 11:22:23.310   873  1315 D WifiConfigStore: Loading config and enabling all networks 
,08-16 11:22:23.322  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:22:23.322  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:22:23.322  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:22:23.322  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:22:23.322  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:22:23.322  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:22:23.322  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:22:23.322  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 11:22:23.327  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 11:22:23.329   873  1315 D WifiConfigStore: loaded 0 passpoint configs
,08-16 11:22:23.330   873  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-16 11:22:23.331   873  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-16 11:22:23.332   873  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,08-16 11:22:23.332   873  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-16 11:22:23.333   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-16 11:22:23.333   873  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-16 11:22:23.337  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:22:23.337  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:22:23.337  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:22:23.337  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:22:23.337  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:22:23.337  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:22:23.337  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:22:23.337  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 11:22:23.344  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 11:22:23.346   373   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-16 11:22:23.347   373   871 D CommandListener: Setting iface cfg
,08-16 11:22:23.347   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-16 11:22:23.348   873  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '152 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 152 Failed to set address (No such device)'
08-16 11:22:23.348   873  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-16 11:22:23.351   873  1313 D WifiNative-HAL: p2pGetDeviceAddress
,08-16 11:22:23.351   873  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-16 11:22:23.409   873  1315 E native  : do suspend true
,08-16 11:22:23.447   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 11:22:24.822   873  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-16 11:22:24.961   873  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.38 rxSuccessRate=10.81 delta 1000 -> 994
,08-16 11:22:24.963   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-16 11:22:24.963   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 11:22:24.984   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-16 11:22:25.059   873  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-16 11:22:25.062  1463  1463 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-16 11:22:25.321  3799  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:22:25.321  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:22:25.321  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:22:25.321  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:22:25.321  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:22:25.321  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 11:22:25.321  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 11:22:25.321  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 11:22:25.329  3799  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 11:22:25.330  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:22:25.330  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@43eca85 removed from the list
,08-16 11:22:25.330  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:22:25.331  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:22:25.331  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:22:25.493  1463  1463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 11:22:25.539  1463  1463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-16 11:22:25.540  1463  1463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-16 11:22:25.551   873  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,08-16 11:22:25.562   873  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-16 11:22:25.563   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 11:22:25.563   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-16 11:22:25.584   873  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-16 11:22:25.603   373   871 D CommandListener: Setting iface cfg
,08-16 11:22:25.607   873  1315 D WifiStateMachine: Start Dhcp Watchdog 3
,08-16 11:22:25.613   873  4351 D DhcpClient: Receive thread started
,08-16 11:22:25.618   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-16 11:22:25.709   873  1315 E native  : do suspend false
,08-16 11:22:25.733   873  1882 D DhcpClient: Broadcasting DHCPDISCOVER
,08-16 11:22:25.746   873  4351 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172771, domain null
,08-16 11:22:25.748   873  1882 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172771 seconds
,08-16 11:22:25.751   873  1882 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-16 11:22:25.765   873  4351 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-16 11:22:25.766   873  1882 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-16 11:22:25.771   373   871 D CommandListener: Setting iface cfg
,08-16 11:22:25.782   873  1882 D DhcpClient: Scheduling renewal in 86399s
,08-16 11:22:25.783   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-16 11:22:25.788   873  1315 E native  : do suspend true
,08-16 11:22:25.806   873  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-16 11:22:25.808   873  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,08-16 11:22:25.809   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 11:22:25.811   873  1318 D ConnectivityService: Adding iface wlan0 to network 102
,08-16 11:22:25.819   873  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-16 11:22:25.853   873  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-16 11:22:25.854   873  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-16 11:22:25.857   873  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-16 11:22:25.860   873  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-16 11:22:25.863   873  1318 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-16 11:22:25.875   873  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 11:22:25.885   873  1318 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-16 11:22:25.885   873  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-16 11:22:25.886   873  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-16 11:22:25.886   873  1318 D ConnectivityService:    accepting network in place of null
,08-16 11:22:25.886   873  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-16 11:22:25.888   873  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-16 11:22:25.888   873  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-16 11:22:25.898   873  4350 D NetlinkSocketObserver: NeighborEvent{elapsedMs=224546, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-16 11:22:25.941   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 11:22:25.971   873  4349 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.46,2a00:1450:4001:812::200e
,08-16 11:22:25.990   373   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-16 11:22:25.998   873  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-16 11:22:25.999   873  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 11:22:26.004   873  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,08-16 11:22:26.005   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-16 11:22:26.021  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:22:26.021  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:22:26.021  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:22:26.021  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:22:26.021  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:22:26.021  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:22:26.021  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:22:26.021  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:22:26.024  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 11:22:26.029  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 11:22:26.029  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:22:26.029  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:22:26.029  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:22:26.029  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:22:26.029  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:22:26.029  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:22:26.029  3799  3799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:22:26.031  3799  3799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 11:22:26.039  1718  1718 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-16 11:22:26.046  1718  1718 D SystemUpdateService: onCreate
,08-16 11:22:26.050  1718  1718 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-16 11:22:26.075  1718  4360 I SystemUpdateService: active receiver: enabled
,08-16 11:22:26.078  1718  1718 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-16 11:22:26.083  1718  2396 I iu.UploadsManager: num queued entries: 0
,08-16 11:22:26.085  1718  4360 I SystemUpdateService: Already downloaded, skipping offpeak checks.
08-16 11:22:26.086  1718  2396 I iu.UploadsManager: num updated entries: 0
,08-16 11:22:26.087  1718  2396 I iu.SyncManager: NEXT; no task
,08-16 11:22:26.093  1718  4360 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-16 11:22:26.093  1718  4360 I SystemUpdateService: now status is 0 (complete)
08-16 11:22:26.093  1718  4360 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-16 11:22:26.093  1718  4360 I SystemUpdateService: file has been verified
08-16 11:22:26.093  1718  4360 I SystemUpdateService: OTA package size = 12249756
,08-16 11:22:26.099  1718  4360 I SystemUpdateService: showing system update notification
,08-16 11:22:26.101  1718  1718 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-16 11:22:26.105  1718  1718 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-16 11:22:26.107  4087  4087 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-16 11:22:26.111  1718  4362 I MDM     : [184] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-16 11:22:26.111  1718  4362 W BaseAppContext: Using Auth Proxy for data requests.
,08-16 11:22:26.113  1718  4362 V GoogleAuthProtoRequest: [184] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 11:22:26.118  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:22:26.119  4087  4087 D SprintDMHelper: simOperator: ,
,08-16 11:22:26.119  4087  4087 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-16 11:22:26.142  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:22:26.180  1718  1718 D SystemUpdateService: onDestroy
,08-16 11:22:26.193  1516  1528 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
08-16 11:22:26.194  1516  1528 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-16 11:22:26.194  1516  1528 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 11:22:26.194  1516  1528 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:22:26.209  1718  4362 E MDM     : [184] SitrepService.a: Error sending sitrep.
,08-16 11:22:26.279   873  4349 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 09:22:26 GMT], X-Android-Received-Millis=[1471339346278], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1471339346212]}
,08-16 11:22:26.282   873  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-16 11:22:26.283   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,08-16 11:22:26.283   873  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-16 11:22:26.290   873  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-16 11:22:26.997   873  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-16 11:22:27.345  4058  4365 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-16 11:22:30.345  3799  4372 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,08-16 11:22:30.346  3799  4372 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 11:22:33.355  3799  4373 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-16 11:22:33.356  3799  4372 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-16 11:22:33.356  3799  4373 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-16 11:22:33.356  3799  4372 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 11:22:33.358  3799  4372 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 11:22:33.359  3799  4373 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 11:22:33.359  3799  4372 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 11:22:33.362  3799  4373 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 11:22:33.363  3799  4375 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 422, name: OutgoingSocketThread/Sender)
,08-16 11:22:33.365  3799  4373 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-16 11:22:33.365  3799  4372 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-16 11:22:33.365  3799  4376 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 423, name: IncomingSocketThread/Sender)
,08-16 11:22:33.369  3799  4377 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: IncomingSocketThread/Receiver)
,08-16 11:22:33.371  3799  4378 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 424, name: OutgoingSocketThread/Receiver)
,08-16 11:22:33.371  3799  4377 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 425, thread name: IncomingSocketThread/Receiver)
08-16 11:22:33.371  3799  4377 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 11:22:33.372  3799  4377 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 425, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-16 11:22:33.373  3799  4378 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 424, thread name: OutgoingSocketThread/Receiver)
08-16 11:22:33.373  3799  4378 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 11:22:33.373  3799  4378 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 424, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,08-16 11:22:33.892   873  1318 D ConnectivityService: handlePromptUnvalidated 102
,08-16 11:22:41.355  3799  3850 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-16 11:22:41.358  3799  3850 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-16 11:22:41.366  3799  3850 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b8648f Bundle[{}]
,08-16 11:22:41.368  3799  3850 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 11:22:41.369  3799  3850 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-16 11:22:41.372  3799  3850 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-16 11:22:41.374  3799  3850 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 11:22:41.376  3799  3850 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-16 11:22:41.377  3799  3850 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 11:22:44.802   873  4350 D NetlinkSocketObserver: NeighborEvent{elapsedMs=243451, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 11:22:51.395  3799  3850 I System.out: Running OutgoingSocketThread
,08-16 11:22:51.400  3799  4382 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,08-16 11:22:51.400  3799  4382 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 11:22:54.409  3799  4383 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-16 11:22:54.409  3799  4383 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 11:22:54.410  3799  4383 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 11:22:54.410  3799  4382 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-16 11:22:54.410  3799  4382 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 11:22:54.410  3799  4382 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 11:22:54.411  3799  4383 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 11:22:54.412  3799  4382 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 11:22:54.413  3799  4383 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,08-16 11:22:54.419  3799  4386 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 435, name: OutgoingSocketThread/Sender)
,08-16 11:22:54.420  3799  4382 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-16 11:22:54.425  3799  4388 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: OutgoingSocketThread/Receiver)
,08-16 11:22:54.425  3799  4387 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: IncomingSocketThread/Receiver)
08-16 11:22:54.426  3799  4388 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 437, thread name: OutgoingSocketThread/Receiver)
08-16 11:22:54.426  3799  4388 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 11:22:54.427  3799  4388 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 437, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-16 11:22:54.427  3799  4387 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 436, thread name: IncomingSocketThread/Receiver)
08-16 11:22:54.428  3799  4387 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 11:22:54.428  3799  4387 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 436, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 11:22:54.431  3799  4385 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 434, name: IncomingSocketThread/Sender)
,08-16 11:23:00.908  3605  4389 I BooksSync: Starting books sync for 61035162, extras: ade
,08-16 11:23:00.944  3605  4390 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-16 11:23:00.967  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:23:00.972  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:23:00.997  1516  1527 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 11:23:00.998  1516  1527 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 11:23:00.998  1516  1527 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 11:23:00.998  1516  1527 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:23:01.028  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:23:01.031  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:23:01.062  1516  2189 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-16 11:23:01.062  1516  2189 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-16 11:23:01.062  1516  2189 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 11:23:01.062  1516  2189 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:23:01.086  3605  4390 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-16 11:23:01.087  3605  4389 E BooksSync: Soft error
08-16 11:23:01.087  3605  4389 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 11:23:01.087  3605  4389 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-16 11:23:01.087  3605  4389 E BooksSync: Sync error
08-16 11:23:01.087  3605  4389 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-16 11:23:01.087  3605  4389 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-16 11:23:01.089  3605  4389 I BooksSync: Finished books sync
,08-16 11:23:01.101   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 259272, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-16 11:23:02.413  3799  3850 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 446)
,08-16 11:23:02.415  3799  3850 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 11:23:02.416  3799  3850 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 447)
,08-16 11:23:07.425  3799  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 11:23:07.426  3799  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84ef0da added. We now have 3 listener(s)
,08-16 11:23:07.433  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 11:23:07.433  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-16 11:23:07.434  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 11:23:07.434  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 11:23:07.435  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99b290b added. We now have 4 listener(s)
08-16 11:23:07.435  3799  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 11:23:07.437  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 11:23:07.449  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 11:23:07.468  3799  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:23:07.468  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:23:07.468  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:23:07.468  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:23:07.468  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:23:07.468  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:23:07.468  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:23:07.468  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:23:07.478  3799  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 11:23:07.479  3799  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 11:23:07.480  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:23:07.480  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:23:07.481  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 11:23:07.481  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:23:07.481  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:23:07.482  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 11:23:07.482  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 11:23:07.482  3799  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84ef0da removed from the list
08-16 11:23:07.483  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:23:07.483  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99b290b removed from the list
,08-16 11:23:07.488  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:23:07.488  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:23:07.488  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:23:07.491  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:23:07.491  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:23:07.496  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 11:23:07.496  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:23:07.497  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:23:07.497  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99b290b not in the list
08-16 11:23:07.497  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:23:07.498  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:23:07.499  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:23:07.502  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:23:07.503  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:23:07.503  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:23:07.503  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99b290b not in the list
08-16 11:23:07.503  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:23:07.504  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:23:07.504  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:23:07.505  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84ef0da not in the list
08-16 11:23:07.507  3799  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 11:23:07.507  3799  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a268a01 added. We now have 3 listener(s)
,08-16 11:23:07.514  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 11:23:07.516  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 11:23:07.516  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 11:23:07.517  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 11:23:07.517  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3b40a6 added. We now have 4 listener(s)
08-16 11:23:07.517  3799  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 11:23:07.517  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 11:23:07.523  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:23:07.534  3799  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:23:07.534  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:23:07.534  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:23:07.534  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:23:07.534  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:23:07.534  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:23:07.534  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:23:07.534  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:23:07.539  3799  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:23:07.539  3799  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 11:23:07.541  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 11:23:07.541  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 11:23:07.542  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:23:07.542  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 11:23:07.544  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:23:07.544  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 11:23:07.548  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:23:07.554  3799  3850 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-16 11:23:07.555  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 11:23:07.566  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 11:23:07.568  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-16 11:23:07.568  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 11:23:07.579  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-16 11:23:07.579  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 11:23:07.579  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 11:23:07.582  3799  3850 D BluetoothAdapter: STATE_ON
08-16 11:23:07.590  4294  4335 D BtGatt.GattService: registerClient() - UUID=ec6a8e1c-fc4c-448c-9dff-d118e0c43cdb
08-16 11:23:07.592  4294  4310 D BtGatt.GattService: onClientRegistered() - UUID=ec6a8e1c-fc4c-448c-9dff-d118e0c43cdb, clientIf=5
08-16 11:23:07.593  3799  4022 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-16 11:23:07.596  4294  4334 D BtGatt.GattService: start scan with filters
08-16 11:23:07.606  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-16 11:23:07.606  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-16 11:23:07.607  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 11:23:07.607  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-16 11:23:07.607  4294  4313 D BtGatt.ScanManager: handling starting scan
08-16 11:23:07.613  4294  4313 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bf87833
08-16 11:23:07.618  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-16 11:23:07.618  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 11:23:07.618  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 11:23:07.624  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 11:23:07.630  4294  4310 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 11:23:07.630  4294  4310 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:23:07.632  4294  4313 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0,
,08-16 11:23:07.635  3799  3850 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-16 11:23:07.635  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 11:23:07.635  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 11:23:07.636  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 11:23:07.636  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 11:23:07.636  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 11:23:07.636  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 11:23:07.636  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-16 11:23:07.636  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-16 11:23:07.637  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 11:23:07.638  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-16 11:23:07.640  3799  3850 D BluetoothAdapter: STATE_ON
08-16 11:23:07.642  4294  4322 D BtGatt.GattService: stopScan() - queue size =1
,08-16 11:23:07.645  4294  4335 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 11:23:07.645  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 11:23:07.646  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 11:23:07.646  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 11:23:07.646  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 11:23:07.647  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-16 11:23:07.651  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 11:23:07.652  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 11:23:07.652  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-16 11:23:07.652  4294  4310 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-16 11:23:07.652  4294  4310 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:23:07.652  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 11:23:07.653  4294  4313 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 11:23:07.654  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 11:23:07.654  4294  4313 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-16 11:23:07.657  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 11:23:07.658  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 11:23:07.658  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 11:23:07.687  4294  4310 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-16 11:23:07.688  4294  4310 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:23:07.705  4294  4310 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-16 11:23:07.706  4294  4310 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:23:07.734  4294  4310 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 11:23:07.735  4294  4310 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 11:23:07.736  4294  4313 D BtGatt.ScanManager: stopping BLe Batch
,08-16 11:23:07.759  4294  4310 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-16 11:23:07.759  4294  4310 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 11:23:07.760  4294  4313 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 11:23:07.782  4294  4310 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-16 11:23:07.783  4294  4310 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:23:08.160  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 11:23:08.160  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-16 11:23:08.160  3799  3799 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 11:23:08.615   873  4350 D NetlinkSocketObserver: NeighborEvent{elapsedMs=267264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-16 11:23:10.658  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 11:23:10.658  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:23:10.658  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 11:23:10.659  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:23:10.659  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:23:10.659  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 11:23:10.660  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-16 11:23:10.660  3799  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a268a01 removed from the list
08-16 11:23:10.660  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:23:10.661  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3b40a6 removed from the list
08-16 11:23:10.661  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:23:10.662  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:23:10.663  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 11:23:10.663  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:23:10.667  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 11:23:10.667  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:23:10.668  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:23:10.668  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3b40a6 not in the list
08-16 11:23:10.668  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 11:23:10.668  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:23:10.672  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 11:23:10.672  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:23:10.672  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:23:10.673  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3b40a6 not in the list
08-16 11:23:10.673  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 11:23:10.673  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:23:10.673  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:23:10.674  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a268a01 not in the list
08-16 11:23:10.675  3799  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 11:23:10.676  3799  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65dae83 added. We now have 3 listener(s)
,08-16 11:23:10.677  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 11:23:10.678  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 11:23:10.678  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 11:23:10.678  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 11:23:10.678  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d616800 added. We now have 4 listener(s)
08-16 11:23:10.678  3799  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 11:23:10.678  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 11:23:10.681  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 11:23:10.686  3799  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:23:10.686  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:23:10.686  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:23:10.686  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:23:10.686  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:23:10.686  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:23:10.686  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:23:10.686  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:23:10.688  3799  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 11:23:10.689  3799  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 11:23:10.689  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-16 11:23:10.690  3799  3850 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-16 11:23:10.690  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,08-16 11:23:10.692  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:23:10.692  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-16 11:23:10.692  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-16 11:23:10.692  3799  3850 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 11:23:10.693  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:23:10.693  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 11:23:10.694  3799  3850 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 11:23:10.694  3799  3850 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 11:23:10.694  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 11:23:10.694  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-16 11:23:10.694  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 11:23:10.694  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 11:23:10.695  3799  4391 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 11:23:10.697  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:23:10.697  3799  3799 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 11:23:10.698  3799  4391 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-16 11:23:10.701  3799  3850 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 11:23:10.701  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 11:23:10.706  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 11:23:10.707  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 11:23:10.707  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 11:23:10.709  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-16 11:23:10.710  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 11:23:10.710  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
,08-16 11:23:10.711  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-16 11:23:10.712  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,08-16 11:23:10.712  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-16 11:23:10.712  3799  3850 D BluetoothAdapter: STATE_ON
,08-16 11:23:10.716  4294  4322 D BtGatt.GattService: registerClient() - UUID=6b949451-41d2-4c99-9b0b-3a9d6903ae99
,08-16 11:23:10.716  4294  4310 D BtGatt.GattService: onClientRegistered() - UUID=6b949451-41d2-4c99-9b0b-3a9d6903ae99, clientIf=5
08-16 11:23:10.717  3799  4022 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-16 11:23:10.719  4294  4312 D BtGatt.AdvertiseManager: message : 0
,08-16 11:23:10.721  4294  4312 D BtGatt.AdvertiseManager: starting multi advertising
,08-16 11:23:10.741  4294  4310 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-16 11:23:10.753  4294  4310 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-16 11:23:10.755  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-16 11:23:10.755  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 11:23:10.757  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 11:23:10.759  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-16 11:23:10.760  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
08-16 11:23:10.760  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
08-16 11:23:10.760  3799  3799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-16 11:23:10.760  3799  3799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-16 11:23:10.761  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-16 11:23:10.762  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 11:23:10.763  3799  3799 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-16 11:23:10.763  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-16 11:23:11.264  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,08-16 11:23:11.265  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 11:23:11.265  3799  3799 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 11:23:12.953  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:23:12.957  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:23:12.976  3878  4392 V GoogleAuthProtoRequest: [328] a.<init>: mAccountName set to: thalitester@gmail.com
,08-16 11:23:13.022  1516  2435 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,08-16 11:23:13.023  1516  2435 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-16 11:23:13.023  1516  2435 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 11:23:13.023  1516  2435 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:23:13.058  3878  4392 W ExperimentUpdateService: [328] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
08-16 11:23:13.059  3878  4392 W ExperimentUpdateService: [328] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 11:23:13.059  3878  4392 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-16 11:23:13.059  3878  4392 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-16 11:23:13.059  3878  4392 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-16 11:23:13.059  3878  4392 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-16 11:23:13.059  3878  4392 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-16 11:23:13.059  3878  4392 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-16 11:23:13.059  3878  4392 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-16 11:23:13.059  3878  4392 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-16 11:23:13.059  3878  4392 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-16 11:23:13.059  3878  4392 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-16 11:23:13.763  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 11:23:13.764  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-16 11:23:13.764  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 11:23:13.765  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-16 11:23:13.765  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 11:23:13.765  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 11:23:13.766  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-16 11:23:13.766  3799  4391 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-16 11:23:13.766  3799  4391 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 11:23:13.766  3799  3850 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 11:23:13.767  3799  4391 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 11:23:13.767  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 11:23:13.768  3799  3799 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 11:23:13.768  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 11:23:13.768  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 11:23:13.768  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 11:23:13.769  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 11:23:13.772  3799  3850 D BluetoothAdapter: STATE_ON
08-16 11:23:13.773  3799  3850 D BluetoothLeScanner: could not find callback wrapper
08-16 11:23:13.773  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 11:23:13.774  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-16 11:23:13.776  4294  4312 D BtGatt.AdvertiseManager: message : 1
08-16 11:23:13.778  4294  4312 D BtGatt.AdvertiseManager: stop advertise for client 5
,08-16 11:23:13.788  4294  4310 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-16 11:23:13.789  4294  4310 D BtGatt.GattService: Client app is not null!
08-16 11:23:13.791  4294  4331 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 11:23:13.792  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 11:23:13.792  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,08-16 11:23:13.792  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-16 11:23:13.793  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-16 11:23:13.793  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-16 11:23:13.797  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 11:23:13.797  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 11:23:13.798  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 11:23:13.799  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 11:23:13.802  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 11:23:13.803  3799  3799 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 11:23:13.803  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 11:23:13.803  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 11:23:13.803  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 11:23:13.804  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 11:23:13.804  3799  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65dae83 removed from the list
,08-16 11:23:13.804  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 11:23:13.804  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:23:13.805  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 11:23:13.805  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d616800 removed from the list
,08-16 11:23:13.805  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 11:23:13.805  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:23:13.807  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:23:13.807  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:23:13.810  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:23:13.810  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:23:13.811  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:23:13.811  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d616800 not in the list
,08-16 11:23:13.812  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:23:13.812  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:23:13.815  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 11:23:13.815  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:23:13.815  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:23:13.816  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d616800 not in the list
,08-16 11:23:13.816  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:23:13.816  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:23:13.817  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:23:13.817  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@65dae83 not in the list
08-16 11:23:13.819  3799  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 11:23:13.819  3799  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b205ef5 added. We now have 3 listener(s)
,08-16 11:23:13.827  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-16 11:23:13.828  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 11:23:13.828  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 11:23:13.828  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 11:23:13.829  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35448a added. We now have 4 listener(s)
08-16 11:23:13.829  3799  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 11:23:13.830  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 11:23:13.836  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 11:23:13.847  3799  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:23:13.847  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:23:13.847  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:23:13.847  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:23:13.847  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:23:13.847  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:23:13.847  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:23:13.847  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:23:13.852  3799  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 11:23:13.852  3799  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 11:23:13.853  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 11:23:13.853  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 11:23:13.853  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-16 11:23:13.854  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:23:13.854  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 11:23:13.858  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:23:13.861  3799  3850 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-16 11:23:13.861  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-16 11:23:13.863  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:23:13.869  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 11:23:13.871  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-16 11:23:13.871  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-16 11:23:13.879  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-16 11:23:13.879  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-16 11:23:13.879  3799  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-16 11:23:13.880  3799  3850 D BluetoothAdapter: STATE_ON
,08-16 11:23:13.886  4294  4331 D BtGatt.GattService: registerClient() - UUID=dd731e24-e014-4a04-89fa-114799af0a53
,08-16 11:23:13.887  4294  4310 D BtGatt.GattService: onClientRegistered() - UUID=dd731e24-e014-4a04-89fa-114799af0a53, clientIf=5
,08-16 11:23:13.888  3799  4022 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-16 11:23:13.889  4294  4335 D BtGatt.GattService: start scan with filters
,08-16 11:23:13.896  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-16 11:23:13.896  4294  4313 D BtGatt.ScanManager: handling starting scan
,08-16 11:23:13.896  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-16 11:23:13.896  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-16 11:23:13.897  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-16 11:23:13.908  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 11:23:13.908  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-16 11:23:13.908  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-16 11:23:13.912  4294  4310 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-16 11:23:13.912  4294  4310 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 11:23:13.913  4294  4313 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-16 11:23:13.915  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-16 11:23:13.927  4294  4310 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-16 11:23:13.928  4294  4310 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 11:23:13.928  4294  4313 D BtGatt.ScanManager: Starting BLE batch scan
,08-16 11:23:13.929  4294  4313 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-16 11:23:13.948  4294  4310 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-16 11:23:13.948  4294  4310 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:23:13.958  4294  4310 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-16 11:23:13.958  4294  4310 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:23:14.306  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 11:23:14.410  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-16 11:23:14.410  3799  3799 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-16 11:23:14.411  3799  3799 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 11:23:15.464  4294  4294 D BtGatt.ScanManager: awakened up at time 274113
,08-16 11:23:15.467  4294  4313 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 11:23:15.508  4294  4310 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,08-16 11:23:15.509  4294  4310 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 11:23:15.509  4294  4310 D BtGatt.GattService: current time is 274158493281
08-16 11:23:15.511  4294  4310 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -81, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -94, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 116, -43, -111, -91, -20, -29, 1, -128, -86, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -83, 23, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 35, 97, 126, -92, 22, -56, 1, -128, -78, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -84, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 11:23:15.515  4294  4310 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-16 11:23:15.517  4294  4310 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-16 11:23:15.518  4294  4310 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-16 11:23:15.518  4294  4310 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-16 11:23:15.519  4294  4310 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-16 11:23:15.520  4294  4310 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-16 11:23:16.932  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 11:23:16.932  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 11:23:16.933  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-16 11:23:16.933  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:23:16.933  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 11:23:16.934  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 11:23:16.934  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-16 11:23:16.934  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 11:23:16.935  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 11:23:16.936  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 11:23:16.936  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-16 11:23:16.939  3799  3850 D BluetoothAdapter: STATE_ON
08-16 11:23:16.941  4294  4305 D BtGatt.GattService: stopScan() - queue size =1
,08-16 11:23:16.945  4294  4322 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-16 11:23:16.946  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-16 11:23:16.946  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-16 11:23:16.947  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-16 11:23:16.947  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-16 11:23:16.948  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-16 11:23:16.951  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 11:23:16.951  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-16 11:23:16.951  3799  3850 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 11:23:16.952  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 11:23:16.953  4294  4294 D BtGatt.ScanManager: awakened up at time 275602
08-16 11:23:16.955  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 11:23:16.958  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-16 11:23:16.958  3799  3799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 11:23:16.959  3799  3799 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-16 11:23:16.959  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:23:16.960  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:23:16.960  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 11:23:16.960  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 11:23:16.960  3799  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b205ef5 removed from the list
08-16 11:23:16.961  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-16 11:23:16.961  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35448a removed from the list
08-16 11:23:16.961  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:23:16.961  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:23:16.963  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 11:23:16.963  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:23:16.966  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 11:23:16.966  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:23:16.966  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:23:16.966  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35448a not in the list
,08-16 11:23:16.967  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:23:16.967  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:23:16.969  4294  4310 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-16 11:23:16.969  4294  4310 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 11:23:16.970  4294  4313 D BtGatt.ScanManager: stopping BLe Batch
08-16 11:23:16.970  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:23:16.971  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 11:23:16.971  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:23:16.971  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35448a not in the list
08-16 11:23:16.971  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-16 11:23:16.972  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:23:16.972  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 11:23:16.972  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b205ef5 not in the list
,08-16 11:23:16.974  3799  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 11:23:16.975  3799  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e6cbbd7 added. We now have 3 listener(s)
,08-16 11:23:16.980  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-16 11:23:16.981  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 11:23:16.981  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 11:23:16.981  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 11:23:16.981  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1acc4 added. We now have 4 listener(s)
08-16 11:23:16.982  3799  3850 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 11:23:16.982  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 11:23:16.985  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-16 11:23:16.985  4294  4310 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-16 11:23:16.986  4294  4310 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-16 11:23:16.986  4294  4313 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-16 11:23:16.990  3799  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:23:16.990  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:23:16.990  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-16 11:23:16.990  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:23:16.990  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:23:16.990  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:23:16.990  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:23:16.990  3799  3850 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 11:23:16.993  3799  3850 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 11:23:16.993  4294  4310 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-16 11:23:16.993  3799  3850 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 11:23:16.993  4294  4310 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-16 11:23:16.994  3799  3850 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 11:23:16.994  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 11:23:16.998  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:23:16.998  3799  3850 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 11:23:16.998  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:23:16.999  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 11:23:16.999  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 11:23:16.999  3799  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 11:23:17.000  3799  3850 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e6cbbd7 removed from the list
,08-16 11:23:17.000  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:23:17.000  3799  3799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:23:17.000  3799  3850 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1acc4 removed from the list
,08-16 11:23:17.000  3799  3850 D io.jxcore.node.ConnectivityMonitor: stop
08-16 11:23:17.001  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:23:17.002  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:23:17.002  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:23:17.003  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 11:23:17.004  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 11:23:17.004  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:23:17.004  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1acc4 not in the list
,08-16 11:23:17.004  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:23:17.005  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:23:17.006  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 11:23:17.006  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 11:23:17.006  3799  3850 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 11:23:17.007  3799  3850 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4d1acc4 not in the list
,08-16 11:23:17.007  3799  3850 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 11:23:17.007  3799  3850 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 11:23:17.007  3799  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 11:23:17.008  3799  3850 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e6cbbd7 not in the list
,08-16 11:23:17.460  3799  3799 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 11:23:22.011  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-16 11:23:22.012  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 11:23:22.012  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-16 11:23:22.013  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 11:23:22.013  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 11:23:22.014  3799  3850 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-16 11:23:26.042   873  4350 D NetlinkSocketObserver: NeighborEvent{elapsedMs=284690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-16 11:23:29.039  3799  4398 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 456, name: My test thread name)
,08-16 11:23:31.037  3799  3850 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 456
,08-16 11:23:31.037  3799  3850 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 456, name: My test thread name)
,08-16 11:23:31.046  3799  4399 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 457, name: My test thread name)
,08-16 11:23:31.046  3799  4399 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 457, thread name: My test thread name)
08-16 11:23:31.047  3799  4399 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 457, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,08-16 11:23:31.052  3799  3850 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 11:23:31.061  3799  4400 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 461, name: My test thread name)
,08-16 11:23:31.062  3799  4400 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 461, thread name: My test thread name): Test exception.
08-16 11:23:31.063  3799  4400 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 461, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-16 11:23:31.070  3799  3850 I jxcore-log: Total number of executed tests:  82
08-16 11:23:31.070  3799  3850 I jxcore-log: 
,08-16 11:23:31.071  3799  3850 I jxcore-log: Number of passed tests:  82
08-16 11:23:31.071  3799  3850 I jxcore-log: 
08-16 11:23:31.072  3799  3850 I jxcore-log: Number of failed tests:  0
08-16 11:23:31.072  3799  3850 I jxcore-log: 
08-16 11:23:31.073  3799  3850 I jxcore-log: Number of ignored tests:  0
08-16 11:23:31.073  3799  3850 I jxcore-log: 
,08-16 11:23:31.075  3799  3850 I jxcore-log: Total duration:  147575
08-16 11:23:31.075  3799  3850 I jxcore-log: 
08-16 11:23:31.076  3799  3850 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-16 11:23:31.076  3799  3850 I jxcore-log: 
,08-16 11:23:31.089  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:23:31.089  3799  3850 I jxcore-log: 
,08-16 11:23:31.101  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:23:31.101  3799  3850 I jxcore-log: 
,08-16 11:23:31.104  3799  3799 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-16 11:23:31.105  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:23:31.105  3799  3850 I jxcore-log: 
,08-16 11:23:31.109  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:23:31.109  3799  3850 I jxcore-log: 
,08-16 11:23:31.112  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-16 11:23:31.112  3799  3850 I jxcore-log: 
,08-16 11:23:31.117  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 11:23:31.117  3799  3850 I jxcore-log: 
,08-16 11:23:31.123  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:23:31.123  3799  3850 I jxcore-log: 
,08-16 11:23:31.125  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:23:31.125  3799  3850 I jxcore-log: 
,08-16 11:23:31.126  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-16 11:23:31.126  3799  3850 I jxcore-log: 
,08-16 11:23:31.127  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 11:23:31.127  3799  3850 I jxcore-log: 
,08-16 11:23:31.128  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 11:23:31.128  3799  3850 I jxcore-log: 
,08-16 11:23:31.128  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:23:31.128  3799  3850 I jxcore-log: 
08-16 11:23:31.129  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:23:31.129  3799  3850 I jxcore-log: 
,08-16 11:23:31.130  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:23:31.130  3799  3850 I jxcore-log: 
08-16 11:23:31.131  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 11:23:31.131  3799  3850 I jxcore-log: 
08-16 11:23:31.132  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 11:23:31.132  3799  3850 I jxcore-log: 
08-16 11:23:31.133  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 11:23:31.133  3799  3850 I jxcore-log: 
,08-16 11:23:31.134  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 11:23:31.134  3799  3850 I jxcore-log: 
08-16 11:23:31.135  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 11:23:31.135  3799  3850 I jxcore-log: 
08-16 11:23:31.136  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 11:23:31.136  3799  3850 I jxcore-log: 
08-16 11:23:31.137  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 11:23:31.137  3799  3850 I jxcore-log: 
,08-16 11:23:31.138  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 11:23:31.138  3799  3850 I jxcore-log: 
08-16 11:23:31.138  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 11:23:31.138  3799  3850 I jxcore-log: 
,08-16 11:23:31.139  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:23:31.139  3799  3850 I jxcore-log: 
08-16 11:23:31.140  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:23:31.140  3799  3850 I jxcore-log: 
08-16 11:23:31.141  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:23:31.141  3799  3850 I jxcore-log: 
08-16 11:23:31.142  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 11:23:31.142  3799  3850 I jxcore-log: 
08-16 11:23:31.144  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 11:23:31.144  3799  3850 I jxcore-log: 
,08-16 11:23:31.145  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 11:23:31.145  3799  3850 I jxcore-log: 
08-16 11:23:31.146  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 11:23:31.146  3799  3850 I jxcore-log: 
08-16 11:23:31.147  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 11:23:31.147  3799  3850 I jxcore-log: 
,08-16 11:23:31.147  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 11:23:31.147  3799  3850 I jxcore-log: 
,08-16 11:23:31.148  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 11:23:31.148  3799  3850 I jxcore-log: 
08-16 11:23:31.149  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 11:23:31.149  3799  3850 I jxcore-log: 
08-16 11:23:31.150  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 11:23:31.150  3799  3850 I jxcore-log: 
,08-16 11:23:31.151  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 11:23:31.151  3799  3850 I jxcore-log: 
08-16 11:23:31.152  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 11:23:31.152  3799  3850 I jxcore-log: 
08-16 11:23:31.153  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 11:23:31.153  3799  3850 I jxcore-log: 
,08-16 11:23:31.154  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 11:23:31.154  3799  3850 I jxcore-log: 
,08-16 11:23:31.155  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 11:23:31.155  3799  3850 I jxcore-log: 
,08-16 11:23:31.156  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 11:23:31.156  3799  3850 I jxcore-log: 
08-16 11:23:31.158  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 11:23:31.158  3799  3850 I jxcore-log: 
,08-16 11:23:31.159  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 11:23:31.159  3799  3850 I jxcore-log: 
08-16 11:23:31.159  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 11:23:31.159  3799  3850 I jxcore-log: 
08-16 11:23:31.160  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:23:31.160  3799  3850 I jxcore-log: 
08-16 11:23:31.161  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:23:31.161  3799  3850 I jxcore-log: 
08-16 11:23:31.162  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:23:31.162  3799  3850 I jxcore-log: 
,08-16 11:23:31.163  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:23:31.163  3799  3850 I jxcore-log: 
08-16 11:23:31.164  3799  4398 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 456, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,08-16 11:23:31.164  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 11:23:31.164  3799  3850 I jxcore-log: 
08-16 11:23:31.165  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:23:31.165  3799  3850 I jxcore-log: 
,08-16 11:23:31.166  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
08-16 11:23:31.166  3799  3850 I jxcore-log: 
08-16 11:23:31.167  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:23:31.167  3799  3850 I jxcore-log: 
08-16 11:23:31.167  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 11:23:31.167  3799  3850 I jxcore-log: 
,08-16 11:23:31.169  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
08-16 11:23:31.169  3799  3850 I jxcore-log: 
08-16 11:23:31.169  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 11:23:31.169  3799  3850 I jxcore-log: 
08-16 11:23:31.170  3799  3850 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 11:23:31.170  3799  3850 I jxcore-log: 
,08-16 11:23:31.330  3137  4405 V KeepSync: Connecting to GoogleApiClient
,08-16 11:23:31.332   873  1948 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-16 11:23:31.355  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:23:31.356  1516  1516 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-16 11:23:31.452  1516  2189 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 11:23:31.452  1516  2189 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-16 11:23:31.452  1516  2189 I GLSUser : [GLSUser] Extracting token using key: Auth
08-16 11:23:31.452  1516  2189 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:23:31.474  1516  2985 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-16 11:23:31.474  1516  2985 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-16 11:23:31.474  1516  2985 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 11:23:31.474  1516  2985 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:23:31.487  3545  4404 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-16 11:23:31.487  3545  4404 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 11:23:31.487  3545  4404 E HttpOperation: 	at jdm.a(PG:82)
08-16 11:23:31.487  3545  4404 E HttpOperation: 	at jcs.o(PG:406)
08-16 11:23:31.487  3545  4404 E HttpOperation: 	at jcn.a(PG:1379)
08-16 11:23:31.487  3545  4404 E HttpOperation: 	at jcs.i(PG:143)
08-16 11:23:31.487  3545  4404 E HttpOperation: 	at blb.a(PG:3937)
08-16 11:23:31.487  3545  4404 E HttpOperation: 	at czp.a(PG:18188)
08-16 11:23:31.487  3545  4404 E HttpOperation: 	at czp.a(PG:9081)
08-16 11:23:31.487  3545  4404 E HttpOperation: 	at czq.run(PG:1686)
08-16 11:23:31.487  3545  4404 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 11:23:31.487  3545  4404 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 11:23:31.487  3545  4404 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 11:23:31.487  3545  4404 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 11:23:31.487  3545  4404 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 11:23:31.487  3545  4404 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 11:23:31.487  3545  4404 E HttpOperation: 	at jdj.a(PG:4091)
08-16 11:23:31.487  3545  4404 E HttpOperation: 	at jdj.a(PG:1125)
08-16 11:23:31.487  3545  4404 E HttpOperation: 	at jdm.a(PG:77)
08-16 11:23:31.487  3545  4404 E HttpOperation: 	... 12 more
08-16 11:23:31.487  3545  4404 E HttpOperation: Caused by: faj: BadAuthentication
08-16 11:23:31.487  3545  4404 E HttpOperation: 	at fal.a(PG:38)
08-16 11:23:31.487  3545  4404 E HttpOperation: 	at jdj.a(PG:4089)
08-16 11:23:31.487  3545  4404 E HttpOperation: 	... 14 more
,08-16 11:23:31.512  1718  4406 V BaseAuthAsyncOperation: access token request failed
08-16 11:23:31.518  3137  4405 V KeepSync: GoogleApiClient failed to connect with error code: 4
08-16 11:23:31.521  1516  1912 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-16 11:23:31.521  1516  1912 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-16 11:23:31.521  1516  1912 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 11:23:31.521  1516  1912 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:23:31.533  3545  4404 E HttpOperation: [getmobileexperiments] Unexpected exception
08-16 11:23:31.533  3545  4404 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-16 11:23:31.533  3545  4404 E HttpOperation: 	at jdm.a(PG:82)
08-16 11:23:31.533  3545  4404 E HttpOperation: 	at jcs.o(PG:406)
08-16 11:23:31.533  3545  4404 E HttpOperation: 	at jcn.a(PG:1379)
08-16 11:23:31.533  3545  4404 E HttpOperation: 	at jcs.i(PG:143)
08-16 11:23:31.533  3545  4404 E HttpOperation: 	at hec.a(PG:42)
08-16 11:23:31.533  3545  4404 E HttpOperation: 	at hee.a(PG:102)
08-16 11:23:31.533  3545  4404 E HttpOperation: 	at czr.a(PG:65)
08-16 11:23:31.533  3545  4404 E HttpOperation: 	at kka.a(PG:108)
08-16 11:23:31.533  3545  4404 E HttpOperation: 	at czp.a(PG:19176)
08-16 11:23:31.533  3545  4404 E HttpOperation: 	at czp.a(PG:9081)
08-16 11:23:31.533  3545  4404 E HttpOperation: 	at czq.run(PG:1686)
08-16 11:23:31.533  3545  4404 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 11:23:31.533  3545  4404 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 11:23:31.533  3545  4404 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 11:23:31.533  3545  4404 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 11:23:31.533  3545  4404 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-16 11:23:31.533  3545  4404 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 11:23:31.533  3545  4404 E HttpOperation: 	at jdj.a(PG:4091)
08-16 11:23:31.533  3545  4404 E HttpOperation: 	at jdj.a(PG:1125)
08-16 11:23:31.533  3545  4404 E HttpOperation: 	at jdm.a(PG:77)
08-16 11:23:31.533  3545  4404 E HttpOperation: 	... 15 more
08-16 11:23:31.533  3545  4404 E HttpOperation: Caused by: faj: BadAuthentication
08-16 11:23:31.533  3545  4404 E HttpOperation: 	at fal.a(PG:38)
08-16 11:23:31.533  3545  4404 E HttpOperation: 	at jdj.a(PG:4089)
08-16 11:23:31.533  3545  4404 E HttpOperation: 	... 17 more
,08-16 11:23:31.533  3545  4404 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-16 11:23:31.533  3545  4404 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	at jdm.a(PG:82)
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	at jcs.o(PG:406)
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	at jcn.a(PG:1379)
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	at jcs.i(PG:143)
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	at hec.a(PG:42)
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	at hee.a(PG:102)
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	at czr.a(PG:65)
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	at kka.a(PG:108)
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	at czp.a(PG:19176)
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	at czp.a(PG:9081)
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	at czq.run(PG:1686)
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-16 11:23:31.533  3545  4404 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	at jdj.a(PG:4091)
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	at jdj.a(PG:1125)
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	at jdm.a(PG:77)
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	... 15 more
08-16 11:23:31.533  3545  4404 E ExperimentLoader: Caused by: faj: BadAuthentication
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	at fal.a(PG:38)
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	at jdj.a(PG:4089)
08-16 11:23:31.533  3545  4404 E ExperimentLoader: 	... 17 more
,08-16 11:23:31.670   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 260041, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-16 11:23:31.700  1516  2189 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-16 11:23:31.700  1516  2189 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-16 11:23:31.700  1516  2189 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-16 11:23:31.700  1516  2189 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-16 11:23:31.719  4401  4401 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-16 11:23:31.723  3137  4405 E KeepSync: IOException
08-16 11:23:31.723  3137  4405 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-16 11:23:31.723  3137  4405 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-16 11:23:31.723  3137  4405 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-16 11:23:31.723  3137  4405 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-16 11:23:31.723  3137  4405 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-16 11:23:31.723  3137  4405 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-16 11:23:31.723  3137  4405 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-16 11:23:31.723  3137  4405 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-16 11:23:31.723  3137  4405 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-16 11:23:31.723  3137  4405 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-16 11:23:31.723  3137  4405 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-16 11:23:31.723  3137  4405 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-16 11:23:31.723  3137  4405 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-16 11:23:31.723  3137  4405 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-16 11:23:31.723  3137  4405 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 11:23:31.723  3137  4405 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-16 11:23:31.723  3137  4405 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-16 11:23:31.723  3137  4405 E KeepSync: 	... 10 more
,08-16 11:23:31.723  4401  4401 D AndroidRuntime: CheckJNI is OFF
08-16 11:23:31.723  3137  4405 W KeepSync: Sync result 2
08-16 11:23:31.729   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 289696, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
08-16 11:23:31.756  4401  4401 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-16 11:23:31.793  4401  4401 I Radio-JNI: register_android_hardware_Radio DONE
,08-16 11:23:31.813  4401  4401 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 11:23:31.821   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-16 11:23:31.822   873   886 I ActivityManager: Killing 3799:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-16 11:23:31.915   873  1695 D GraphicsStats: Buffer count: 2
08-16 11:23:31.916   873  1951 I WindowState: WIN DEATH: Window{a9473b6 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-16 11:23:31.916   873  1317 D WifiService: Client connection lost with reason: 4
,08-16 11:23:31.924   873   896 W PackageSettings: Skipping PackageSetting{4db99d4 com.example.hello/10273} due to missing metadata
,08-16 11:23:31.964   873   896 I art     : Starting a blocking GC Explicit
,08-16 11:23:31.972   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-16 11:23:31.972   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-16 11:23:31.973   873   886 E ActivityManager: Failure starting process com.test.thalitest
08-16 11:23:31.973   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-16 11:23:31.973   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-16 11:23:31.973   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-16 11:23:31.973   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-16 11:23:31.973   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-16 11:23:31.973   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-16 11:23:31.973   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-16 11:23:31.973   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-16 11:23:31.973   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-16 11:23:31.973   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-16 11:23:31.973   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-16 11:23:31.973   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-16 11:23:31.973   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-16 11:23:31.973   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-16 11:23:31.973   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-16 11:23:31.973   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 11:23:31.973   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 11:23:31.973   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 11:23:31.973   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-16 11:23:31.973   873   886 I ActivityManager:   Force finishing activity ActivityRecord{fd546df u0 com.test.thalitest/.MainActivity t2}
,08-16 11:23:31.986   873  1948 W ActivityManager: Spurious death for ProcessRecord{bdec096 0:com.test.thalitest/u0a0}, curProc for 3799: null
08-16 11:23:32.004   873   896 I art     : Explicit concurrent mark sweep GC freed 19732(1329KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 29MB/43MB, paused 738us total 39.592ms
,08-16 11:23:32.023   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-16 11:23:32.028  4401  4401 I art     : System.exit called, status: 0
,08-16 11:23:32.028  4401  4401 I AndroidRuntime: VM exiting with result code 0.
,08-16 11:23:32.045   873   896 I ActivityManager: Start proc 4416:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-16 11:23:32.045   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-16 11:23:32.067   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-16 11:23:32.072   873  1306 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-16 11:23:32.073  4294  4294 D BluetoothMapAppObserver: onReceive
08-16 11:23:32.073  4294  4294 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-16 11:23:32.076  1886  1886 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-16 11:23:32.077  3671  3671 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-16 11:23:32.080  1853  2192 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-16 11:23:32.100  1886  4428 I Keyboard.Facilitator.DecoderInitializer: run()
,08-16 11:23:32.124  1886  4428 I Decoder : createOrResetDecoder
,08-16 11:23:32.143  1998  1998 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-16 11:23:32.144   873  1951 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3799 uid 10000
,08-16 11:23:32.145   873  1695 I ActivityManager: Start proc 4432:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-16 11:23:32.146  1886  1886 I Keyboard.Facilitator: onFinishInput()
,08-16 11:23:32.153   873  1312 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,08-16 11:23:32.173   873   884 I ActivityManager: Killing 3724:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-16 11:23:32.175   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 11:23:32.213  4432  4432 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,08-16 11:23:32.229  2013  2094 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-16 11:23:32.231   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,08-16 11:23:32.232   873   885 E PackageManager: Failed to write settings, restoring backup
08-16 11:23:32.232   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-16 11:23:32.232   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-16 11:23:32.232   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-16 11:23:32.232   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-16 11:23:32.232   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-16 11:23:32.232   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 11:23:32.232   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-16 11:23:32.232   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 11:23:32.236   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-16 11:23:32.236   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-16 11:23:32.236   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 11:23:32.236   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 11:23:32.236   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 11:23:32.236   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 11:23:32.236   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 11:23:32.236   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 11:23:32.236   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-16 11:23:32.236   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-16 11:23:32.236   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-16 11:23:32.236   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 11:23:32.236   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 11:23:32.236   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-16 11:23:32.236   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 11:23:32.236   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-16 11:23:32.236   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 11:23:32.236   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 11:23:32.236   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 11:23:32.236   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 11:23:32.236   873   886 E DropBoxManagerService: 	... 13 more
08-16 11:23:32.238  1516  1516 I ConfigService: onCreate
,08-16 11:23:32.242   873  2024 I ActivityManager: Start proc 4444:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
08-16 11:23:32.242  2013  2094 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-16 11:23:32.242  2013  2094 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2013
08-16 11:23:32.242  2013  2094 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 11:23:32.242  2013  2094 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 11:23:32.242  2013  2094 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 11:23:32.242  2013  2094 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 11:23:32.242  2013  2094 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 11:23:32.242  2013  2094 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 11:23:32.242  2013  2094 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-16 11:23:32.242  2013  2094 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-16 11:23:32.242  2013  2094 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 11:23:32.242  2013  2094 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 11:23:32.242  2013  2094 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 11:23:32.242  2013  2094 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-16 11:23:32.245   873  2052 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 11:23:32.245   873  4451 E DropBoxManagerService: Can't write: system_app_crash
08-16 11:23:32.245   873  4451 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-16 11:23:32.245   873  4451 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 11:23:32.245   873  4451 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 11:23:32.245   873  4451 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 11:23:32.245   873  4451 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 11:23:32.245   873  4451 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 11:23:32.245   873  4451 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 11:23:32.245   873  4451 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 11:23:32.245   873  4451 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 11:23:32.245   873  4451 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 11:23:32.245   873  4451 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 11:23:32.245   873  4451 E DropBoxManagerService: 	... 5 more
08-16 11:23:32.248  2013  2094 I Process : Sending signal. PID: 2013 SIG: 9
,08-16 11:23:32.268  1516  4445 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-16 11:23:32.268  1516  4445 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 11:23:32.268  1516  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 11:23:32.268  1516  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 11:23:32.268  1516  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 11:23:32.268  1516  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 11:23:32.268  1516  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 11:23:32.268  1516  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 11:23:32.268  1516  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 11:23:32.268  1516  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 11:23:32.268  1516  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 11:23:32.268  1516  4445 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 11:23:32.268  1516  4445 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 11:23:32.268  1516  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 11:23:32.268  1516  4445 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 11:23:32.268  1516  4445 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-16 11:23:32.268  1516  4445 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-16 11:23:32.268  1516  4445 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,08-16 11:23:32.268  1516  4445 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-16 11:23:32.268  1516  4445 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 11:23:32.268  1516  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 11:23:32.268  1516  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 11:23:32.268  1516  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 11:23:32.268  1516  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 11:23:32.268  1516  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 11:23:32.268  1516  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 11:23:32.268  1516  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 11:23:32.268  1516  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 11:23:32.268  1516  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 11:23:32.268  1516  4445 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 11:23:32.268  1516  4445 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 11:23:32.268  1516  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 11:23:32.268  1516  4445 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-16 11:23:32.268  1516  4445 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-16 11:23:32.268  1516  4445 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-16 11:23:32.268  1516  4445 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-16 11:23:32.270  1516  4445 W SQLiteOpenHelper: Opened config.db in read-only mode
,08-16 11:23:32.289  1886  4428 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-16 11:23:32.320  4432  4432 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,08-16 11:23:32.335   873  1951 D GraphicsStats: Buffer count: 1
,08-16 11:23:32.335   873  2024 I WindowState: WIN DEATH: Window{a167822 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-16 11:23:32.346   873  2052 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2013) has died
,08-16 11:23:32.346   873  2052 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-16 11:23:32.348   873  2052 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-16 11:23:32.358  1886  4428 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-16 11:23:32.360  1886  4428 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,08-16 11:23:32.361  1886  4428 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-16 11:23:32.366  1886  4428 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-16 11:23:32.367  1886  4428 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history,
08-16 11:23:32.367  1886  4428 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-16 11:23:32.367  1886  4428 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-16 11:23:32.370  1886  4428 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-16 11:23:32.370  1886  4428 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,08-16 11:23:32.370  1886  4428 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-16 11:23:32.370   873  1928 I ActivityManager: Start proc 4464:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-16 11:23:32.370  1886  4428 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,08-16 11:23:32.370  1886  4428 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-16 11:23:32.370  1886  4428 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-16 11:23:32.371  4432  4463 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-16 11:23:32.388  4432  4463 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 11:23:32.388  4432  4463 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 11:23:32.388  4432  4463 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-16 11:23:32.388  4432  4463 E AndroidRuntime: Process: android.process.acore, PID: 4432
08-16 11:23:32.388  4432  4463 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 11:23:32.388  4432  4463 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-16 11:23:32.392   873   886 I ActivityManager: Start proc 4475:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 11:23:32.395   873  4482 E DropBoxManagerService: Can't write: system_app_crash
08-16 11:23:32.395   873  4482 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-16 11:23:32.395   873  4482 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 11:23:32.395   873  4482 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 11:23:32.395   873  4482 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 11:23:32.395   873  4482 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 11:23:32.395   873  4482 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 11:23:32.395   873  4482 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 11:23:32.395   873  4482 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 11:23:32.395   873  4482 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 11:23:32.395   873  4482 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 11:23:32.395   873  4482 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 11:23:32.395   873  4482 E DropBoxManagerService: 	... 5 more
08-16 11:23:32.395  4432  4463 I Process : Sending signal. PID: 4432 SIG: 9
08-16 11:23:32.398   280   280 E lowmemorykiller: Error writing /proc/4432/oom_score_adj; errno=22
08-16 11:23:32.412   280   280 E lowmemorykiller: Error writing /proc/4432/oom_score_adj; errno=22
08-16 11:23:32.439  4464  4464 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,08-16 11:23:32.446  4475  4475 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 11:23:32.446  4475  4475 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-16 11:23:32.447  4475  4475 D AndroidRuntime: Shutting down VM
08-16 11:23:32.455  4475  4475 E AndroidRuntime: FATAL EXCEPTION: main
08-16 11:23:32.455  4475  4475 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4475
08-16 11:23:32.455  4475  4475 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-16 11:23:32.455  4475  4475 E AndroidRuntime: 	... 10 more
08-16 11:23:32.457   873  2019 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-16 11:23:32.457  4475  4475 I Process : Sending signal. PID: 4475 SIG: 9
08-16 11:23:32.458   873  4491 E DropBoxManagerService: Can't write: system_app_crash
08-16 11:23:32.458   873  4491 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-16 11:23:32.458   873  4491 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 11:23:32.458   873  4491 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 11:23:32.458   873  4491 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 11:23:32.458   873  4491 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 11:23:32.458   873  4491 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 11:23:32.458   873  4491 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 11:23:32.458   873  4491 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 11:23:32.458   873  4491 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 11:23:32.458   873  4491 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 11:23:32.458   873  4491 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 11:23:32.458   873  4491 E DropBoxManagerService: 	... 5 more
,08-16 11:23:32.462   280   280 E lowmemorykiller: Error writing /proc/4432/oom_score_adj; errno=22
08-16 11:23:32.469   280   280 E lowmemorykiller: Error writing /proc/4432/oom_score_adj; errno=22
08-16 11:23:32.472  1718  4490 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-16 11:23:32.473  1718  4490 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-16 11:23:32.479  1718  4490 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-16 11:23:32.479  1718  4490 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-16 11:23:32.480  1516  1516 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-16 11:23:32.481  1516  1516 D AndroidRuntime: Shutting down VM
08-16 11:23:32.482  1516  1516 E AndroidRuntime: FATAL EXCEPTION: main
08-16 11:23:32.482  1516  1516 E AndroidRuntime: Process: com.google.process.gapps, PID: 1516
08-16 11:23:32.482  1516  1516 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 11:23:32.482  1516  1516 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-16 11:23:32.482  1516  1516 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-16 11:23:32.482  1516  1516 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-16 11:23:32.482  1516  1516 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 11:23:32.482  1516  1516 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-16 11:23:32.482  1516  1516 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-16 11:23:32.482  1516  1516 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 11:23:32.482  1516  1516 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-16 11:23:32.482  1516  1516 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-16 11:23:32.482  1516  1516 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-16 11:23:32.482  1516  1516 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-16 11:23:32.482  1516  1516 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-16 11:23:32.482  1516  1516 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-16 11:23:32.482  1516  1516 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-16 11:23:32.482  1516  1516 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-16 11:23:32.482  1516  1516 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-16 11:23:32.482  1516  1516 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-16 11:23:32.482  1516  1516 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-16 11:23:32.482  1516  1516 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-16 11:23:32.482  1516  1516 E AndroidRuntime: 	... 8 more
08-16 11:23:32.484   280   280 E lowmemorykiller: Error writing /proc/4432/oom_score_adj; errno=22
08-16 11:23:32.485  1516  1516 I Process : Sending signal. PID: 1516 SIG: 9
08-16 11:23:32.485   873  4494 E DropBoxManagerService: Can't write: system_app_crash
08-16 11:23:32.485   873  4494 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
08-16 11:23:32.485   873  4494 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-16 11:23:32.485   873  4494 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-16 11:23:32.485   873  4494 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-16 11:23:32.485   873  4494 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-16 11:23:32.485   873  4494 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-16 11:23:32.485   873  4494 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-16 11:23:32.485   873  4494 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-16 11:23:32.485   873  4494 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-16 11:23:32.485   873  4494 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-16 11:23:32.485   873  4494 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-16 11:23:32.485   873  4494 E DropBoxManagerService: 	... 5 more
08-16 11:23:32.486   873  2978 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4475) has died
08-16 11:23:32.488   873  2978 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-16 11:23:32.496   280   280 E lowmemorykiller: Error writing /proc/4432/oom_score_adj; errno=22
08-16 11:23:32.515   873   886 I ActivityManager: Start proc 4496:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-16 11:23:32.516   873  2019 I ActivityManager: Killing 2070:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17

```
