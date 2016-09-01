#### Test 8359140042466a2_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-01 10:59:17.904   873  1914 D NetlinkSocketObserver: NeighborEvent{elapsedMs=118237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-01 10:59:18.562  3756  3756 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-01 10:59:18.568  3756  3756 D AndroidRuntime: CheckJNI is OFF
09-01 10:59:18.610  3756  3756 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-01 10:59:18.660  3756  3756 I Radio-JNI: register_android_hardware_Radio DONE
09-01 10:59:18.683  3756  3756 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-01 10:59:18.687   873  2015 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-01 10:59:18.717  3756  3756 D AndroidRuntime: Shutting down VM
09-01 10:59:18.720  2138  3717 W SearchService: Abort, client detached.
09-01 10:59:18.734  2138  2348 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@163cda9
09-01 10:59:18.734  2138  2359 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-01 10:59:18.736  2138  2138 I HotwordDetector: Closing mic
09-01 10:59:18.767   873  1960 I ActivityManager: Start proc 3766:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-01 10:59:18.802   375  2361 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-01 10:59:18.803   375  2361 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-01 10:59:18.807   375  1286 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-01 10:59:18.810  2138  2358 I MicroRecognitionRnrImpl: Detection finished
09-01 10:59:18.811  2138  2351 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-01 10:59:18.847  3766  3766 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-01 10:59:18.867  3766  3766 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-01 10:59:18.873  3766  3766 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9204-9206)
09-01 10:59:18.874  3766  3766 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-01 10:59:18.886  3766  3766 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7a518d7}
09-01 10:59:18.886  3766  3766 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-01 10:59:18.887  3766  3766 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-01 10:59:18.893  3766  3766 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-01 10:59:18.894  3766  3766 E SysUtils: ApplicationContext is null in ApplicationStatus
09-01 10:59:18.907  3766  3766 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-01 10:59:18.916  3766  3766 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-01 10:59:18.916  3766  3766 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-01 10:59:18.917  3766  3766 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-01 10:59:18.917  3766  3766 I Adreno  : Build Date                       : 10/20/15
09-01 10:59:18.917  3766  3766 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-01 10:59:18.917  3766  3766 I Adreno  : Local Branch                     : M14
09-01 10:59:18.917  3766  3766 I Adreno  : Remote Branch                    : 
09-01 10:59:18.917  3766  3766 I Adreno  : Remote Branch                    : 
09-01 10:59:18.917  3766  3766 I Adreno  : Reconstruct Branch               : 
,09-01 10:59:18.959   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2ec87f7:true
,09-01 10:59:19.013  3766  3766 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-01 10:59:19.029  3766  3766 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-01 10:59:19.094  3766  3805 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-01 10:59:19.102  3766  3791 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-01 10:59:19.140  3766  3805 I OpenGLRenderer: Initialized EGL, version 1.4
,09-01 10:59:19.189   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +462ms
,09-01 10:59:19.197  1901  1901 I Keyboard.Facilitator: onFinishInput()
,09-01 10:59:19.255  3766  3766 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3766
,09-01 10:59:19.385  3766  3766 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-01 10:59:19.558  3766  3807 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1713768144
,09-01 10:59:19.565  3766  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-01 10:59:19.565  3766  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-01 10:59:19.565  3766  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-01 10:59:19.565  3766  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-01 10:59:19.565  3766  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-01 10:59:19.566  3766  3807 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d073bfa added. We now have 1 listener(s)
,09-01 10:59:19.571  3766  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
09-01 10:59:19.572  3766  3807 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 10:59:19.572  3766  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:19.573  3766  3807 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 10:59:19.577   873  1915 I ActivityManager: Killing 2985:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-01 10:59:19.577  3766  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-01 10:59:19.577  3766  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-01 10:59:19.577  3766  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-01 10:59:19.577  3766  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-01 10:59:19.577  3766  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-01 10:59:19.577  3766  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-01 10:59:19.577  3766  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-01 10:59:19.577  3766  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-01 10:59:19.577  3766  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-01 10:59:19.577  3766  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-01 10:59:19.577  3766  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-01 10:59:19.577  3766  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-01 10:59:19.577  3766  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-01 10:59:19.577  3766  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-01 10:59:19.577  3766  3807 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@63f27a1 added. We now have 1 listener(s)
,09-01 10:59:19.577  3766  3807 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:19.581   873  1317 D WifiService: New client listening to asynchronous messages
,09-01 10:59:19.581  3766  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 10:59:19.581  3766  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-01 10:59:19.582  3766  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-01 10:59:19.582  3766  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-01 10:59:19.582  3766  3807 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-01 10:59:19.629   873  1915 I ActivityManager: Killing 3100:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,09-01 10:59:19.656  3766  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:19.656  3766  3807 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-01 10:59:19.662  3766  3807 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-01 10:59:19.663  3766  3807 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:19.663  3766  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:19.663  3766  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:19.663  3766  3807 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:19.663  3766  3807 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:19.663  3766  3807 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:19.663  3766  3807 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:19.663  3766  3807 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 10:59:19.663  3766  3807 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-01 10:59:19.663  3766  3807 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 10:59:19.664  3766  3807 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-01 10:59:19.773  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:19.776  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:19.779  3766  3766 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-01 10:59:20.528  3766  3814 W jxcore-log: Initializing JXcore engine
,09-01 10:59:20.528  3766  3814 W jxcore-log: JXcore engine is ready
,09-01 10:59:20.566  3814  3814 W Thread-317: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8940 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-01 10:59:20.566  3814  3814 W Thread-317: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10630]" dev="sockfs" ino=10630 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-01 10:59:20.566  3814  3814 W Thread-317: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-01 10:59:20.581  3766  3814 W jxcore-log: Starting JXcore engine
,09-01 10:59:20.566  3814  3814 W Thread-317: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26847]" dev="sockfs" ino=26847 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-01 10:59:20.662  3766  3814 W jxcore-log: Platform android
09-01 10:59:20.662  3766  3814 W jxcore-log: 
,09-01 10:59:20.663  3766  3814 W jxcore-log: Process ARCH arm
09-01 10:59:20.663  3766  3814 W jxcore-log: 
,09-01 10:59:20.923  3766  3814 I jxcore-log: JXcore Cordova bridge is ready!
09-01 10:59:20.923  3766  3814 I jxcore-log: 
,09-01 10:59:20.924  3766  3814 W jxcore-log: JXcore engine is started
,09-01 10:59:20.936  3766  3807 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-01 10:59:20.944  3766  3766 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-01 10:59:22.186   873  1316 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-01 10:59:24.664   873  1914 D NetlinkSocketObserver: NeighborEvent{elapsedMs=124996, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-01 10:59:26.556  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 10:59:26.560  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 10:59:26.620  1503  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-01 10:59:26.620  1503  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-01 10:59:26.621  1503  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 10:59:26.621  1503  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 10:59:26.662  3000  3823 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-01 10:59:26.662  3000  3823 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-01 10:59:26.662  3000  3823 E HttpOperation: 	at jdm.a(PG:82)
09-01 10:59:26.662  3000  3823 E HttpOperation: 	at jcs.o(PG:406)
09-01 10:59:26.662  3000  3823 E HttpOperation: 	at jcn.a(PG:1379)
09-01 10:59:26.662  3000  3823 E HttpOperation: 	at jcs.i(PG:143)
09-01 10:59:26.662  3000  3823 E HttpOperation: 	at blb.a(PG:3937)
09-01 10:59:26.662  3000  3823 E HttpOperation: 	at czp.a(PG:18188)
09-01 10:59:26.662  3000  3823 E HttpOperation: 	at czp.a(PG:9081)
09-01 10:59:26.662  3000  3823 E HttpOperation: 	at czq.run(PG:1686)
09-01 10:59:26.662  3000  3823 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 10:59:26.662  3000  3823 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 10:59:26.662  3000  3823 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 10:59:26.662  3000  3823 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 10:59:26.662  3000  3823 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-01 10:59:26.662  3000  3823 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 10:59:26.662  3000  3823 E HttpOperation: 	at jdj.a(PG:4091)
09-01 10:59:26.662  3000  3823 E HttpOperation: 	at jdj.a(PG:1125)
09-01 10:59:26.662  3000  3823 E HttpOperation: 	at jdm.a(PG:77)
09-01 10:59:26.662  3000  3823 E HttpOperation: 	... 12 more
09-01 10:59:26.662  3000  3823 E HttpOperation: Caused by: faj: BadAuthentication
09-01 10:59:26.662  3000  3823 E HttpOperation: 	at fal.a(PG:38)
09-01 10:59:26.662  3000  3823 E HttpOperation: 	at jdj.a(PG:4089)
09-01 10:59:26.662  3000  3823 E HttpOperation: 	... 14 more
,09-01 10:59:26.752  1503  2983 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-01 10:59:26.753  1503  2983 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,09-01 10:59:26.753  1503  2983 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 10:59:26.753  1503  2983 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 10:59:26.778  3000  3823 E HttpOperation: [getmobileexperiments] Unexpected exception
09-01 10:59:26.778  3000  3823 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-01 10:59:26.778  3000  3823 E HttpOperation: 	at jdm.a(PG:82)
09-01 10:59:26.778  3000  3823 E HttpOperation: 	at jcs.o(PG:406)
09-01 10:59:26.778  3000  3823 E HttpOperation: 	at jcn.a(PG:1379)
09-01 10:59:26.778  3000  3823 E HttpOperation: 	at jcs.i(PG:143)
09-01 10:59:26.778  3000  3823 E HttpOperation: 	at hec.a(PG:42)
09-01 10:59:26.778  3000  3823 E HttpOperation: 	at hee.a(PG:102)
09-01 10:59:26.778  3000  3823 E HttpOperation: 	at czr.a(PG:65)
09-01 10:59:26.778  3000  3823 E HttpOperation: 	at kka.a(PG:108)
09-01 10:59:26.778  3000  3823 E HttpOperation: 	at czp.a(PG:19176)
09-01 10:59:26.778  3000  3823 E HttpOperation: 	at czp.a(PG:9081)
09-01 10:59:26.778  3000  3823 E HttpOperation: 	at czq.run(PG:1686)
09-01 10:59:26.778  3000  3823 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 10:59:26.778  3000  3823 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 10:59:26.778  3000  3823 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 10:59:26.778  3000  3823 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 10:59:26.778  3000  3823 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-01 10:59:26.778  3000  3823 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 10:59:26.778  3000  3823 E HttpOperation: 	at jdj.a(PG:4091)
09-01 10:59:26.778  3000  3823 E HttpOperation: 	at jdj.a(PG:1125)
09-01 10:59:26.778  3000  3823 E HttpOperation: 	at jdm.a(PG:77)
09-01 10:59:26.778  3000  3823 E HttpOperation: 	... 15 more
09-01 10:59:26.778  3000  3823 E HttpOperation: Caused by: faj: BadAuthentication
09-01 10:59:26.778  3000  3823 E HttpOperation: 	at fal.a(PG:38)
09-01 10:59:26.778  3000  3823 E HttpOperation: 	at jdj.a(PG:4089)
09-01 10:59:26.778  3000  3823 E HttpOperation: 	... 17 more
,09-01 10:59:26.778  3000  3823 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-01 10:59:26.778  3000  3823 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	at jdm.a(PG:82)
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	at jcs.o(PG:406)
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	at jcn.a(PG:1379)
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	at jcs.i(PG:143)
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	at hec.a(PG:42)
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	at hee.a(PG:102)
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	at czr.a(PG:65)
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	at kka.a(PG:108)
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	at czp.a(PG:19176)
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	at czp.a(PG:9081)
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	at czq.run(PG:1686)
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-01 10:59:26.778  3000  3823 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	at jdj.a(PG:4091)
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	at jdj.a(PG:1125)
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	at jdm.a(PG:77)
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	... 15 more
09-01 10:59:26.778  3000  3823 E ExperimentLoader: Caused by: faj: BadAuthentication
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	at fal.a(PG:38)
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	at jdj.a(PG:4089)
09-01 10:59:26.778  3000  3823 E ExperimentLoader: 	... 17 more
,09-01 10:59:26.959   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, SERVER, currentRunTime 126655, reason: 10074, SyncResult: stats [ numIoExceptions: 1]
,09-01 10:59:28.958  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 10:59:28.978  1503  1974 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-01 10:59:28.979  1503  1974 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-01 10:59:28.979  1503  1974 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 10:59:28.979  1503  1974 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 10:59:28.991  3502  3502 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-01 10:59:28.992  3502  3502 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-01 10:59:28.992  3502  3502 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 5.
,09-01 10:59:30.921  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-01 10:59:30.921  3766  3814 I jxcore-log: 
,09-01 10:59:30.923  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-01 10:59:30.923  3766  3814 I jxcore-log: 
,09-01 10:59:30.936  3766  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:30.936  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:30.936  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:30.936  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:30.936  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:30.936  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:30.936  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:30.936  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:30.942  3766  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 10:59:30.944  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-01 10:59:30.944  3766  3814 I jxcore-log: 
,09-01 10:59:30.946  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-01 10:59:30.946  3766  3814 I jxcore-log: 
,09-01 10:59:31.473  3766  3814 D executeNativeTests: Running unit tests
,09-01 10:59:31.530  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 10:59:31.531  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb added. We now have 2 listener(s)
,09-01 10:59:31.532  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 10:59:31.532  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:31.532  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 10:59:31.532  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:31.532  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 added. We now have 2 listener(s)
09-01 10:59:31.532  3766  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:31.533  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 10:59:31.535  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:31.554  3766  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:31.554  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:31.554  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:31.554  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:31.554  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:31.554  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:31.554  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:31.554  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:31.559  3766  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 10:59:31.560  3766  3814 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 10:59:31.566  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:31.571  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 10:59:31.571  3766  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-01 10:59:31.572  3766  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 10:59:31.573  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:31.578  3766  3814 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-01 10:59:31.579  3766  3814 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-01 10:59:31.579  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-01 10:59:31.579  3766  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-01 10:59:31.580  3766  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 10:59:31.582  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:31.584  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-01 10:59:31.584  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:31.585  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 10:59:31.586  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.586  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:31.587  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:31.588  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb removed from the list
09-01 10:59:31.588  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.589  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 removed from the list
09-01 10:59:31.590  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:31.590  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.592  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.592  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
09-01 10:59:31.596  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:31.597  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:31.597  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.598  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
,09-01 10:59:31.602  3766  3814 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-01 10:59:31.604  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 10:59:31.604  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:31.604  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:31.604  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:31.605  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.605  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.605  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
09-01 10:59:31.605  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.605  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.605  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 10:59:31.606  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.606  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.606  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.606  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:31.609  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:31.609  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:31.609  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.610  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
,09-01 10:59:31.618  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-01 10:59:31.618  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-01 10:59:31.618  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-01 10:59:31.619  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-01 10:59:31.619  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-01 10:59:31.619  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-01 10:59:31.619  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-01 10:59:31.619  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-01 10:59:31.619  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-01 10:59:31.619  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-01 10:59:31.619  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-01 10:59:31.619  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-01 10:59:31.619  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-01 10:59:31.619  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-01 10:59:31.619  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-01 10:59:31.620  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-01 10:59:31.620  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-01 10:59:31.620  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,09-01 10:59:31.620  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-01 10:59:31.620  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-01 10:59:31.620  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-01 10:59:31.620  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-01 10:59:31.620  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-01 10:59:31.620  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 10:59:31.620  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-01 10:59:31.620  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 10:59:31.620  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-01 10:59:31.620  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 10:59:31.621  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-01 10:59:31.621  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-01 10:59:31.621  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-01 10:59:31.621  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:31.621  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:31.621  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:31.621  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:31.621  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.621  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.621  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
09-01 10:59:31.621  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.621  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.621  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:31.621  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.622  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.622  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.622  3766  3814 D org.thalipr,oject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.623  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:31.623  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:31.623  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.623  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.624  3766  3814 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 10:59:31.625  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:31.639  3766  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:31.639  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:31.639  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:31.639  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:31.639  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:31.639  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:31.639  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:31.639  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 10:59:31.643  3766  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:31.643  3766  3814 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 10:59:31.644  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:31.644  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 10:59:31.644  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 10:59:31.644  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:31.644  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 10:59:31.648  3766  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-01 10:59:31.648  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 10:59:31.649  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:31.653  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 10:59:31.655  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-01 10:59:31.655  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 10:59:31.656  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:31.658  3766  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-01 10:59:31.662  3766  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-01 10:59:31.662  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-01 10:59:31.663  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 10:59:31.663  3766  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 10:59:31.664  3766  3814 D BluetoothAdapter: STATE_ON
09-01 10:59:31.671  2675  2814 D BtGatt.GattService: registerClient() - UUID=e42b29c4-8fa5-4458-8f75-aeb4d150cb78
09-01 10:59:31.672  2675  2695 D BtGatt.GattService: onClientRegistered() - UUID=e42b29c4-8fa5-4458-8f75-aeb4d150cb78, clientIf=5
09-01 10:59:31.673  3766  3777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-01 10:59:31.674  2675  2686 D BtGatt.GattService: start scan with filters
09-01 10:59:31.677  2675  2710 D BtGatt.ScanManager: handling starting scan
09-01 10:59:31.677  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 10:59:31.678  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 10:59:31.678  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 10:59:31.678  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-01 10:59:31.678  2675  2710 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae956a9
09-01 10:59:31.683  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 10:59:31.683  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-01 10:59:31.684  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 10:59:31.686  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-01 10:59:31.686  2675  2695 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-01 10:59:31.686  2675  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:31.687  2675  2710 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-01 10:59:31.690  3766  3814 I io.jxcore.node.ConnectionHelper: start: OK
09-01 10:59:31.692  2675  2695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-01 10:59:31.693  2675  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:31.693  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:31.693  3766  3814 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 10:59:31.694  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:31.694  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 10:59:31.694  2675  2710 D BtGatt.ScanManager: Starting BLE batch scan
09-01 10:59:31.694  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.694  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 10:59:31.694  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 10:59:31.694  2675  2710 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-01 10:59:31.694  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 10:59:31.694  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 10:59:31.695  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 10:59:31.696  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 10:59:31.696  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-01 10:59:31.697  3766  3814 D BluetoothAdapter: STATE_ON
09-01 10:59:31.698  2675  2686 D BtGatt.GattService: stopScan() - queue size =1
09-01 10:59:31.699  2675  3439 D BtGatt.GattService: unregisterClient() - clientIf=5
09-01 10:59:31.699  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 10:59:31.699  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 10:59:31.699  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 10:59:31.699  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 10:59:31.699  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 10:59:31.713  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 10:59:31.714  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 10:59:31.714  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 10:59:31.715  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 10:59:31.716  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:31.718  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:31.719  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:31.719  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 10:59:31.719  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:31.719  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.720  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:31.720  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
09-01 10:59:31.720  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.720  2675  2695 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-01 10:59:31.720  2675  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:31.720  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.720  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:31.721  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.721  3766  3814 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 10:59:31.723  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:31.726  2675  2695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-01 10:59:31.726  2675  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:31.727  3766  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:31.727  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:31.727  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:31.727  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:31.727  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:31.727  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:31.727  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:31.727  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 10:59:31.729  3766  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:31.729  3766  3814 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 10:59:31.729  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:31.729  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 10:59:31.729  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 10:59:31.729  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:31.730  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 10:59:31.733  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:31.733  2675  2695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-01 10:59:31.733  2675  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:31.734  2675  2710 D BtGatt.ScanManager: stopping BLe Batch
09-01 10:59:31.734  3766  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-01 10:59:31.734  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 10:59:31.735  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:31.739  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 10:59:31.739  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-01 10:59:31.740  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 10:59:31.740  2675  2695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-01 10:59:31.740  2675  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:31.741  2675  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-01 10:59:31.743  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-01 10:59:31.743  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 10:59:31.743  3766  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-01 10:59:31.744  3766  3814 D BluetoothAdapter: STATE_ON
09-01 10:59:31.745  2675  2695 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-01 10:59:31.745  2675  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:31.746  2675  2814 D BtGatt.GattService: registerClient() - UUID=948573a0-613f-4a23-9ee8-67411ea75e0c
09-01 10:59:31.747  2675  2695 D BtGatt.GattService: onClientRegistered() - UUID=948573a0-613f-4a23-9ee8-67411ea75e0c, clientIf=5
09-01 10:59:31.747  3766  3778 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-01 10:59:31.747  2675  2686 D BtGatt.GattService: start scan with filters
09-01 10:59:31.751  2675  2710 D BtGatt.ScanManager: handling starting scan
09-01 10:59:31.751  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 10:59:31.751  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 10:59:31.751  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 10:59:31.751  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-01 10:59:31.753  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 10:59:31.754  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-01 10:59:31.754  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 10:59:31.755  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-01 10:59:31.757  2675  2695 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-01 10:59:31.757  2675  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:31.757  2675  2710 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-01 10:59:31.758  3766  3814 I io.jxcore.node.ConnectionHelper: start: OK
09-01 10:59:31.760  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:31.760  3766  3814 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 10:59:31.760  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:31.760  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 10:59:31.760  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.760  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 10:59:31.760  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 10:59:31.761  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 10:59:31.761  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 10:59:31.761  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 10:59:31.761  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 10:59:31.761  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-01 10:59:31.761  3766  3814 D BluetoothAdapter: STATE_ON
09-01 10:59:31.762  2675  2814 D BtGatt.GattService: stopScan() - queue size =1
09-01 10:59:31.762  2675  2686 D BtGatt.GattService: unregisterClient() - clientIf=5
09-01 10:59:31.762  2675  2695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-01 10:59:31.762  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 10:59:31.762  2675  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:31.762  2675  2710 D BtGatt.ScanManager: Starting BLE batch scan
09-01 10:59:31.762  2675  2710 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-01 10:59:31.762  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 10:59:31.763  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 10:59:31.763  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 10:59:31.763  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-01 10:59:31.763  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 10:59:31.763  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 10:59:31.763  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 10:59:31.763  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 10:59:31.764  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:31.764  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:31.764  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:31.764  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 10:59:31.765  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:31.765  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.765  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:31.765  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
09-01 10:59:31.765  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.765  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.765  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:31.765  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.765  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.765  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.766  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:31.766  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:31.766  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.766  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.766  3766  3814 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-01 10:59:31.768  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:31.770  3766  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:31.770  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:31.770  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:31.770  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:31.770  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:31.770  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:31.770  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:31.770  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 10:59:31.772  3766  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:31.772  2675  2695 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-01 10:59:31.772  3766  3814 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 10:59:31.772  2675  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:31.773  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:31.775  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:31.775  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:31.775  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 10:59:31.775  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 10:59:31.775  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:31.775  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 10:59:31.777  2675  2695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-01 10:59:31.777  2675  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:31.778  3766  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-01 10:59:31.778  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 10:59:31.780  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-01 10:59:31.781  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-01 10:59:31.781  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 10:59:31.783  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-01 10:59:31.783  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-01 10:59:31.783  3766  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-01 10:59:31.783  2675  2695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-01 10:59:31.783  2675  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:31.783  3766  3814 D BluetoothAdapter: STATE_ON
09-01 10:59:31.783  2675  2710 D BtGatt.ScanManager: stopping BLe Batch
09-01 10:59:31.785  2675  2686 D BtGatt.GattService: registerClient() - UUID=84e2d2fc-8cb4-4bc9-991f-4e71e2e804e9
09-01 10:59:31.785  2675  2695 D BtGatt.GattService: onClientRegistered() - UUID=84e2d2fc-8cb4-4bc9-991f-4e71e2e804e9, clientIf=5
09-01 10:59:31.786  3766  3777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-01 10:59:31.786  2675  2687 D BtGatt.GattService: start scan with filters
09-01 10:59:31.789  2675  2695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-01 10:59:31.789  2675  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:31.789  2675  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-01 10:59:31.792  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 10:59:31.792  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 10:59:31.792  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 10:59:31.792  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-01 10:59:31.793  2675  2695 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-01 10:59:31.793  2675  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:31.795  2675  2710 D BtGatt.ScanManager: handling starting scan
09-01 10:59:31.798  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 10:59:31.798  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 10:59:31.798  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-01 10:59:31.799  2675  2695 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-01 10:59:31.799  2675  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:31.799  2675  2710 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-01 10:59:31.803  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-01 10:59:31.803  2675  2695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-01 10:59:31.804  2675  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:31.804  2675  2710 D BtGatt.ScanManager: Starting BLE batch scan
09-01 10:59:31.804  2675  2710 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-01 10:59:31.808  3766  3814 I io.jxcore.node.ConnectionHelper: start: OK
09-01 10:59:31.809  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:31.809  3766  3814 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 10:59:31.809  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:31.809  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-01 10:59:31.809  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.809  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 10:59:31.810  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 10:59:31.810  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 10:59:31.810  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 10:59:31.810  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 10:59:31.811  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 10:59:31.811  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-01 10:59:31.811  3766  3814 D BluetoothAdapter: STATE_ON
09-01 10:59:31.812  2675  2814 D BtGatt.GattService: stopScan() - queue size =1
09-01 10:59:31.812  2675  3439 D BtGatt.GattService: unregisterClient() - clientIf=5
09-01 10:59:31.813  2675  2695 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-01 10:59:31.813  2675  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:31.812  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 10:59:31.813  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 10:59:31.813  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 10:59:31.813  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 10:59:31.813  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-01 10:59:31.814  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 10:59:31.814  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 10:59:31.814  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 10:59:31.814  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 10:59:31.814  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:31.815  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:31.815  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:31.815  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 10:59:31.815  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:31.815  3766  3814 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 10:59:31.815  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:31.815  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 10:59:31.815  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:31.816  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.816  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 10:59:31.816  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
09-01 10:59:31.816  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.816  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.816  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 10:59:31.816  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:31.816  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.816  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.817  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:31.817  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:31.817  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 10:59:31.817  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.817  3766  3814 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-01 10:59:31.818  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:31.818  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:31.818  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 10:59:31.818  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:31.818  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:31.818  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.818  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
09-01 10:59:31.818  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.818  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.818  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:31.818  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-01 10:59:31.818  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.818  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.818  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.819  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:31.819  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 10:59:31.819  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.819  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.820  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-01 10:59:31.820  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 10:59:31.820  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:31.820  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:31.820  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:31.820  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:31.820  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.820  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
09-01 10:59:31.820  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.820  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.820  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 10:59:31.820  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.820  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.821  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.821  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.821  2675  2695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-01 10:59:31.821  2675  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:31.821  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 10:59:31.821  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:31.821  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.821  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.822  3766  3814 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-01 10:59:31.822  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:31.822  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-01 10:59:31.822  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:31.822  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:31.822  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.822  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:31.822  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
09-01 10:59:31.822  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.823  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.823  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:31.823  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:31.823  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.823  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.823  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.823  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:31.823  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:31.823  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 10:59:31.823  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
,09-01 10:59:31.824  3766  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-01 10:59:31.824  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:31.824  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:31.824  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:31.824  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 10:59:31.824  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.824  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.824  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
09-01 10:59:31.824  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.825  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.825  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:31.825  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:31.825  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.825  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.825  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.826  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 10:59:31.826  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:31.826  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.826  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.826  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 10:59:31.826  3766  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-01 10:59:31.826  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 10:59:31.826  3766  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 10:59:31.827  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-01 10:59:31.827  3766  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-01 10:59:31.827  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:31.827  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:31.827  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:31.827  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:31.827  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.828  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.828  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
,09-01 10:59:31.828  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.828  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.828  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:31.828  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.828  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.828  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.828  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.829  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:31.829  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 10:59:31.829  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.829  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.830  3766  3814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 10:59:31.830  3766  3814 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-01 10:59:31.830  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-01 10:59:31.831  2675  2695 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-01 10:59:31.832  2675  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:31.832  2675  2710 D BtGatt.ScanManager: stopping BLe Batch
09-01 10:59:31.834  3766  3814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 10:59:31.834  3766  3814 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-01 10:59:31.834  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-01 10:59:31.834  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-01 10:59:31.834  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-01 10:59:31.834  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-01 10:59:31.834  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-01 10:59:31.834  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-01 10:59:31.834  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-01 10:59:31.834  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-01 10:59:31.834  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-01 10:59:31.834  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-01 10:59:31.834  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-01 10:59:31.834  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-01 10:59:31.835  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-01 10:59:31.835  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-01 10:59:31.835  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-01 10:59:31.835  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-01 10:59:31.835  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-01 10:59:31.835  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-01 10:59:31.835  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-01 10:59:31.835  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-01 10:59:31.835  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-01 10:59:31.835  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-01 10:59:31.835  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-01 10:59:31.835  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-01 10:59:31.835  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-01 10:59:31.835  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-01 10:59:31.835  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-01 10:59:31.835  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-01 10:59:31.836  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-01 10:59:31.836  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,09-01 10:59:31.836  3766  3814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-01 10:59:31.836  3766  3814 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 10:59:31.837  3766  3814 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-01 10:59:31.837  3766  3814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 10:59:31.837  3766  3814 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 10:59:31.837  3766  3814 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-01 10:59:31.837  3766  3814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-01 10:59:31.837  3766  3814 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-01 10:59:31.837  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-01 10:59:31.838  2675  2695 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-01 10:59:31.839  2675  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:31.839  2675  2710 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-01 10:59:31.841  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-01 10:59:31.842  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-01 10:59:31.842  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-01 10:59:31.843  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-01 10:59:31.843  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-01 10:59:31.843  3766  3814 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,09-01 10:59:31.843  3766  3814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-01 10:59:31.844  3766  3814 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-01 10:59:31.844  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:31.844  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:31.844  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:31.844  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:31.844  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:31.844  2675  2695 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-01 10:59:31.844  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.845  2675  2695 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:31.845  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-01 10:59:31.845  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
09-01 10:59:31.845  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.845  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.846  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:31.846  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:31.846  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.846  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.846  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.846  3766  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 381)
09-01 10:59:31.847  3766  3830 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 381
09-01 10:59:31.847  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:31.847  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:31.847  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.847  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
,09-01 10:59:31.848  3766  3814 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-01 10:59:31.848  3766  3829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 10:59:31.848  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:31.848  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:31.848  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:31.848  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:31.849  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.849  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:31.849  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
09-01 10:59:31.849  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.849  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.849  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:31.850  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:31.850  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.850  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.851  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.852  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:31.852  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 10:59:31.852  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.852  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.853  3766  3814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-01 10:59:31.853  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 10:59:31.853  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:31.853  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:31.854  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:31.854  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.854  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:31.854  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
09-01 10:59:31.854  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.854  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.854  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:31.854  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:31.855  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.855  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.855  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.856  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:31.856  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:31.856  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 10:59:31.856  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.857  3766  3814 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-01 10:59:31.857  3766  3814 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-01 10:59:31.857  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 10:59:31.857  3766  3814 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-01 10:59:31.857  3766  3814 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-01 10:59:31.857  3766  3814 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-01 10:59:31.857  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 10:59:31.857  3766  3814 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-01 10:59:31.857  3766  3814 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-01 10:59:31.857  3766  3814 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,09-01 10:59:31.857  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 10:59:31.857  3766  3814 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-01 10:59:31.857  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:31.858  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:31.858  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:31.858  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 10:59:31.858  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.858  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.858  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
09-01 10:59:31.858  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.858  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.858  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 10:59:31.858  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.858  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.858  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.858  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.859  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 10:59:31.859  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:31.859  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.859  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.859  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:31.859  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.859  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.860  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
09-01 10:59:31.860  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.860  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.860  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 10:59:31.860  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.860  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.860  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.860  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.860  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:31.860  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.860  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.860  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
09-01 10:59:31.860  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:31.860  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:31.860  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 10:59:31.860  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:31.860  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.860  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.860  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
09-01 10:59:31.860  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.861  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.861  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 10:59:31.861  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.861  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.861  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.861  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.862  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:31.862  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:31.862  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.862  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.863  3766  3814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-01 10:59:31.863  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:31.863  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-01 10:59:31.864  3766  3814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-01 10:59:31.864  3766  3814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-01 10:59:31.864  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-01 10:59:31.864  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 10:59:31.864  3766  3766 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-01 10:59:31.864  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:31.864  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-01 10:59:31.864  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-01 10:59:31.864  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-01 10:59:31.864  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.865  3766  3814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-01 10:59:31.865  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
09-01 10:59:31.865  3766  3766 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-01 10:59:31.865  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.865  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 10:59:31.865  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 10:59:31.865  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 10:59:31.865  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.865  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.865  3766  3831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-01 10:59:31.865  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 10:59:31.866  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.866  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:31.866  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:31.866  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:31.866  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 10:59:31.866  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:31.866  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:31.866  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.866  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.866  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
09-01 10:59:31.866  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.866  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 10:59:31.866  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.866  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:31.866  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.866  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.866  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.866  3766  3831 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-01 10:59:31.866  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.867  3766  3766 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,09-01 10:59:31.867  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:31.867  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:31.867  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.867  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.868  3766  3814 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-01 10:59:31.868  3766  3814 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-01 10:59:31.868  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-01 10:59:31.869  3766  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-01 10:59:31.869  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:31.869  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:31.869  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:31.869  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:31.869  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.869  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.869  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
,09-01 10:59:31.869  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.869  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.869  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:31.869  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.869  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.869  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.869  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.870  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:31.870  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:31.870  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.870  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.874  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:31.875  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:31.875  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:31.875  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 10:59:31.875  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.875  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.875  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
09-01 10:59:31.875  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.875  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.875  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:31.875  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.875  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.875  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.875  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.876  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:31.876  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:31.876  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.876  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.877  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:31.877  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:31.877  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:31.877  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:31.877  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.877  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.877  3766  3814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bec7bbb not in the list
09-01 10:59:31.877  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.877  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
,09-01 10:59:31.877  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:31.877  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.877  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.877  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:31.877  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:31.878  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:31.879  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:31.879  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:31.879  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f05d8d8 not in the list
09-01 10:59:31.879  3766  3814 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-01 10:59:31.879  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 10:59:31.879  3766  3814 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-01 10:59:31.879  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-01 10:59:31.880  3766  3814 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-01 10:59:31.880  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-01 10:59:31.881  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-01 10:59:31.881  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-01 10:59:31.881  3766  3814 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-01 10:59:31.881  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-01 10:59:31.882  3766  3814 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-01 10:59:31.882  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-01 10:59:31.882  3766  3814 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,09-01 10:59:31.882  3766  3814 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-01 10:59:31.882  3766  3814 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-01 10:59:31.882  3766  3814 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-01 10:59:31.882  3766  3814 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-01 10:59:31.882  3766  3814 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-01 10:59:31.883  3766  3814 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-01 10:59:31.883  3766  3814 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-01 10:59:31.883  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:31.883  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e852ffa added. We now have 2 listener(s)
09-01 10:59:31.883  3766  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:31.885  3766  3814 D BluetoothAdapter: enable(): BT is already enabled..!
09-01 10:59:31.885   873  2068 D WifiService: setWifiEnabled: true pid=3766, uid=10000
09-01 10:59:31.885   873  2068 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-01 10:59:31.886  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:31.886  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8afc9ab added. We now have 3 listener(s)
,09-01 10:59:31.886  3766  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:31.890  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:31.890  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@78d2808 added. We now have 4 listener(s)
09-01 10:59:31.890  3766  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:31.891  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:31.891  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@77caba1 added. We now have 5 listener(s)
09-01 10:59:31.891  3766  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:31.894   873  1401 D WifiService: setWifiEnabled: false pid=3766, uid=10000
,09-01 10:59:31.894   873  1401 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 10:59:31.903  2675  2691 D BluetoothAdapterState: Current state: ON, message: 23
09-01 10:59:31.903  2675  2691 D BluetoothAdapterProperties: Setting state to 13
09-01 10:59:31.903  2675  2691 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-01 10:59:31.904  2675  2691 D BluetoothAdapterProperties: onBluetoothDisable()
,09-01 10:59:31.907  2675  2691 I BluetoothAdapterState: Entering PendingCommandState
09-01 10:59:31.907  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:31.908  2675  2695 D BluetoothAdapterProperties: Scan Mode:20
09-01 10:59:31.908  2675  2691 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-01 10:59:31.909  2675  2675 D HeadsetService: Received stop request...Stopping profile...
,09-01 10:59:31.911  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-01 10:59:31.912   873  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-01 10:59:31.912   873  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-01 10:59:31.912   873  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-01 10:59:31.913   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 10:59:31.915  1361  1373 D BluetoothHeadset: Proxy object disconnected
09-01 10:59:31.915   873   873 D BluetoothHeadset: Proxy object disconnected
09-01 10:59:31.915  2675  2675 V BluetoothAdapterState: isTurningOff()=true
09-01 10:59:31.916  2675  2675 V BluetoothAdapterState: isTurningOn()=false
,09-01 10:59:31.916  2675  2675 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 10:59:31.916  1361  1361 D HeadsetProfile: Bluetooth service disconnected
,09-01 10:59:31.916  2675  2675 V BluetoothAdapterState: isBleTurningOff()=false
09-01 10:59:31.917   873   873 D BluetoothHeadset: Proxy object disconnected
09-01 10:59:31.917   873   873 D BluetoothHeadset: Proxy object disconnected
09-01 10:59:31.918  2008  2128 D BluetoothHeadset: Proxy object disconnected
09-01 10:59:31.924   873  1939 D DhcpClient: Clearing IP address
,09-01 10:59:31.925   371   871 D CommandListener: Clearing all IP addresses on wlan0
,09-01 10:59:31.927  2675  2675 D A2dpService: Received stop request...Stopping profile...
,09-01 10:59:31.927   371   871 D CommandListener: Setting iface cfg
,09-01 10:59:31.927  2675  2797 D A2dpStateMachine: Exit Disconnected: -1
,09-01 10:59:31.929  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:31.929  3766  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:31.929  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:31.929  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:31.929  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:31.929  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:31.929  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:31.929  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:31.929  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:31.929  1503  2511 V NativeCrypto: Read error: ssl=0x9b654400: I/O error during system call, Connection timed out
,09-01 10:59:31.931  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:31.931  1503  2511 V NativeCrypto: SSL shutdown failed: ssl=0x9b654400: I/O error during system call, Broken pipe
09-01 10:59:31.933   873  2016 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,09-01 10:59:31.934   873   886 I ActivityManager: Start proc 3834:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-01 10:59:31.935   873  1906 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
09-01 10:59:31.936   873   873 D BluetoothA2dp: Proxy object disconnected
09-01 10:59:31.937  2675  2675 D HidService: Received stop request...Stopping profile...
09-01 10:59:31.937  2675  2675 D HidService: Stopping Bluetooth HidService
,09-01 10:59:31.938   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-01 10:59:31.938   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-01 10:59:31.938   873  1316 D WifiStateMachine: Start Disconnecting Watchdog 1
,09-01 10:59:31.939   873  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-01 10:59:31.943   371   871 D CommandListener: Clearing all IP addresses on wlan0
,09-01 10:59:31.944  2675  2675 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-01 10:59:31.944  2675  2675 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 10:59:31.945   394   394 E Parcel  : Reading a NULL string not supported here.
09-01 10:59:31.945  2675  2675 D HealthService: Received stop request...Stopping profile...
09-01 10:59:31.946  2675  2773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 10:59:31.946  2675  2773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-01 10:59:31.946  2675  2773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 10:59:31.947   873  1941 D DhcpClient: Receive thread stopped
09-01 10:59:31.947  2675  2695 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-01 10:59:31.947  2675  2695 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-01 10:59:31.949   873  1906 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-01 10:59:31.931  3766  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:31.951   873  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-01 10:59:31.951  3766  3814 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 10:59:31.954  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:31.954  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:31.954  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:31.954  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:31.954  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:31.954  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:31.954  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:31.954  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:31.954  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 10:59:31.955  2675  2675 D BluetoothMapService: onReceive
09-01 10:59:31.955  2675  2675 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:31.955  2675  2675 D BluetoothMapService: STATE_TURNING_OFF
09-01 10:59:31.955  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:31.955  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:31.955  1361  1361 D BluetoothA2dp: Proxy object disconnected
,09-01 10:59:31.955  2675  2675 V BluetoothAdapterState: isTurningOff()=true
09-01 10:59:31.955  2675  2675 V BluetoothAdapterState: isTurningOn()=false
09-01 10:59:31.955  2675  2675 V BluetoothAdapterState: isBleTurningOn()=false
09-01 10:59:31.955  2675  2675 V BluetoothAdapterState: isBleTurningOff()=false
09-01 10:59:31.956  2675  2675 D PanService: Received stop request...Stopping profile...
09-01 10:59:31.957  1361  1361 D BluetoothInputDevice: Proxy object disconnected
,09-01 10:59:31.957  1361  1361 D HidProfile: Bluetooth service disconnected
,09-01 10:59:31.958  2675  2773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-01 10:59:31.958  2675  2773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-01 10:59:31.958  2675  2773 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-01 10:59:31.958  2675  2773 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 10:59:31.959  2675  2773 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 10:59:31.959  2675  2773 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-01 10:59:31.959  2675  2695 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-01 10:59:31.959  2675  2675 D BluetoothMapService: Received stop request...Stopping profile...
09-01 10:59:31.959  2675  2675 D BluetoothMapService: stop()
09-01 10:59:31.960  2675  2675 D BluetoothMapAppObserver: deinitObservers()
09-01 10:59:31.960  2675  2675 D BluetoothMapAppObserver: removeReceiver()
,09-01 10:59:31.960  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:31.962  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:31.962  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:31.962  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:31.962  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:31.962  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:31.962  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:31.962  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:31.962  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:31.962  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:31.962  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:31.962  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-01 10:59:31.963  2675  2675 V BluetoothAdapterState: isTurningOff()=true
09-01 10:59:31.963  2675  2675 V BluetoothAdapterState: isTurningOn()=false
,09-01 10:59:31.963  2675  2675 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 10:59:31.963  2675  2675 V BluetoothAdapterState: isBleTurningOff()=false
09-01 10:59:31.963  2675  2675 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-01 10:59:31.963  2675  2675 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,09-01 10:59:31.964  2675  2675 V BluetoothAdapterState: isTurningOff()=true
09-01 10:59:31.964  2675  2675 V BluetoothAdapterState: isTurningOn()=false
09-01 10:59:31.964  2675  2695 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-01 10:59:31.964  2675  2675 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 10:59:31.964  2675  2675 V BluetoothAdapterState: isBleTurningOff()=false
09-01 10:59:31.964  2675  2675 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-01 10:59:31.964  2675  2695 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-01 10:59:31.964   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
09-01 10:59:31.965  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:31.966  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:31.966  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:31.966  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:31.966  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:31.966  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:31.966  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:31.966  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:31.966  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:31.967  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:31.967  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 10:59:31.967  2675  2675 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 10:59:31.967  2675  2675 I BtOppRfcommListener: stopping Accept Thread
,09-01 10:59:31.967  2675  3423 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 10:59:31.968  2675  3423 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-01 10:59:31.969  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:31.969  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:31.969  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:31.969  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:31.969  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:31.969  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:31.969  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:31.969  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:31.969  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:31.969   873  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-01 10:59:31.969  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:31.970  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 10:59:31.971  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:31.971  2675  2675 V BluetoothAdapterState: isTurningOff()=true
09-01 10:59:31.971  2675  2675 V BluetoothAdapterState: isTurningOn()=false
09-01 10:59:31.971  2675  2675 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 10:59:31.971  2675  2675 V BluetoothAdapterState: isBleTurningOff()=false
09-01 10:59:31.971  2675  2675 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-01 10:59:31.971  2675  2675 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-01 10:59:31.972  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:31.974  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:31.974  2675  2675 D BluetoothMapService: MAP Service closeService in
,09-01 10:59:31.974  2675  2675 D BluetoothMapMasInstance0: MAP Service shutdown
09-01 10:59:31.974  2675  2675 D ObexServerSockets0: shutdown(block = true)
,09-01 10:59:31.975  2675  2675 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-01 10:59:31.975  2675  2816 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
,09-01 10:59:31.975  2675  2792 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,09-01 10:59:31.976  2675  2675 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-01 10:59:31.977  2675  2815 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-01 10:59:31.977  2675  2675 V BluetoothAdapterState: isTurningOff()=true
09-01 10:59:31.977  2675  2675 V BluetoothAdapterState: isTurningOn()=false
09-01 10:59:31.977  2675  2675 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 10:59:31.977  2675  2675 V BluetoothAdapterState: isBleTurningOff()=false
09-01 10:59:31.978  2675  2691 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-01 10:59:31.978  2675  2691 D BluetoothAdapterProperties: Setting state to 15
,09-01 10:59:31.978  2675  2691 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-01 10:59:31.979  2675  2675 D BluetoothMapService: cleanup()
09-01 10:59:31.979  2675  2691 I BluetoothAdapterState: Entering BleOnState
09-01 10:59:31.979  2675  2675 D BluetoothMapService: MAP Service closeService in
09-01 10:59:31.980  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-01 10:59:31.980  1361  1361 D PanProfile: Bluetooth service disconnected
,09-01 10:59:31.981  1361  1361 D BluetoothMap: Proxy object disconnected
09-01 10:59:31.981  1361  1361 D MapProfile: Bluetooth service disconnected
,09-01 10:59:31.980  1361  1373 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-01 10:59:31.982  1361  2169 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 10:59:31.984   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 10:59:31.984   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-01 10:59:31.984   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 10:59:31.984   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 10:59:31.984  1361  3842 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 10:59:31.985  1361  1372 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 10:59:31.985  1361  1373 D BluetoothPan: onBluetoothStateChange on: false
,09-01 10:59:31.988  2008  2031 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 10:59:31.989  1361  2169 D BluetoothMap: onBluetoothStateChange: up=false
09-01 10:59:31.989  2675  2691 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-01 10:59:31.989  2675  2691 D BluetoothAdapterProperties: Setting state to 16
09-01 10:59:31.989  2675  2691 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-01 10:59:31.990  2675  2691 D BluetoothAdapterProperties: onBleDisable
,09-01 10:59:31.990  2675  2691 I BluetoothAdapterState: Entering PendingCommandState
09-01 10:59:31.990  2675  2692 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-01 10:59:31.991  2675  2695 D BluetoothAdapterProperties: Scan Mode:20
09-01 10:59:31.992  2675  2773 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-01 10:59:31.992  2675  2773 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 10:59:31.992  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:31.992  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:31.992  3766  3829 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 381)
09-01 10:59:31.994  1860  2317 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-01 10:59:31.995  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:31.995  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:32.006   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-01 10:59:32.017  3834  3834 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-01 10:59:32.018   873   882 I art     : Background partial concurrent mark sweep GC freed 48481(2MB) AllocSpace objects, 14(352KB) LOS objects, 33% free, 29MB/44MB, paused 1.374ms total 100.441ms
09-01 10:59:32.031   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-01 10:59:32.031   873  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-01 10:59:32.031   873  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:32.032  3834  3834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 10:59:32.034   873   890 D Tethering: MasterInitialState.processMessage what=3
09-01 10:59:32.034  3410  3410 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@db6e5ab and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-01 10:59:32.036  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:32.037  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:32.043  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 10:59:32.044   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5e773a2:true
09-01 10:59:32.056   873  1392 I ActivityManager: Start proc 3856:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-01 10:59:32.075   371   871 E Netd    : netlink response contains error (No such file or directory)
,09-01 10:59:32.076   873  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-01 10:59:32.077  3834  3834 D LocalBluetoothProfileManager: Adding local MAP profile
,09-01 10:59:32.079  3834  3834 D BluetoothMap: Create BluetoothMap proxy object
,09-01 10:59:32.086  3834  3834 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-01 10:59:32.094  3856  3856 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-01 10:59:32.101  3834  3834 D DockEventReceiver: finishStartingService: stopping service
,09-01 10:59:32.103   873  1401 I ActivityManager: Killing 3214:com.google.android.gm/u0a78 (adj 15): empty #17
,09-01 10:59:32.192  2675  2695 I bt_hci  : shut_down
,09-01 10:59:32.192  2675  2711 D bt_hwcfg: hw_epilog_process
,09-01 10:59:32.194  2675  2711 I bt_vendor: low_power_mode_cb
,09-01 10:59:32.216  2675  2711 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-01 10:59:32.217  2675  2711 I bt_vendor: epilog_cb
,09-01 10:59:32.217  2675  2711 I bt_hci  : epilog_finished_callback
,09-01 10:59:32.225  2675  2695 I bt_hci_h4: hal_close
,09-01 10:59:32.226  2675  2695 I bt_userial_vendor: device fd = 51 close
,09-01 10:59:32.250  3856  3856 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 10:59:32.250  3856  3856 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at java.io.File.exists(File.java:361)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 10:59:32.250  3856  3856 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 10:59:32.251  3856  3856 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 10:59:32.251  3856  3856 D StrictMode: StrictMode policy violation; ~duration=75 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 10:59:32.251  3856  3856 D StrictMode: StrictMode policy violation; ~duration=74 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.r.e.b(PG:170)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 10:59:32.251  3856  3856 D StrictMode: StrictMode policy violation; ~duration=72 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.r.k.d(PG:583)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.r.e.b(PG:170)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 10:59:32.251  3856  3856 D StrictMode: StrictMode policy violation; ~duration=52 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at java.io.File.exists(File.java:361)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at andr,oid.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 10:59:32.251  3856  3856 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 10:59:32.252  3856  3856 D StrictMode: StrictMode policy violation; ~duration=52 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 10:59:32.252  3856  3856 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at java.io.File.exists(File.java:361)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 10:59:32.252  3856  3856 D StrictMode,: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 10:59:32.252  3856  3856 D StrictMode: StrictMode policy violation; ~duration=51 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-01 10:59:32.252  3856  3856 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 10:59:32.252  3856  3856 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 10:59:32.298   873   883 I ActivityManager: Start proc 3887:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
09-01 10:59:32.301   873   883 I ActivityManager: Killing 3410:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-01 10:59:32.364  2675  2692 D bt_stack_manager: event_shut_down_stack finished.
,09-01 10:59:32.364  2675  2691 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-01 10:59:32.367  3766  3766 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 10:59:32.367  2675  2691 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-01 10:59:32.367  2675  2675 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 10:59:32.369  2675  2675 D BtGatt.GattService: Received stop request...Stopping profile...
,09-01 10:59:32.369  2675  2675 D BtGatt.GattService: stop()
,09-01 10:59:32.369  2675  2675 D BtGatt.AdvertiseManager: advertise clients cleared
,09-01 10:59:32.370  2675  2675 V BluetoothAdapterState: isTurningOff()=false
09-01 10:59:32.370  2675  2675 V BluetoothAdapterState: isTurningOn()=false
,09-01 10:59:32.370  2675  2675 V BluetoothAdapterState: isBleTurningOn()=false
09-01 10:59:32.371  2675  2675 V BluetoothAdapterState: isBleTurningOff()=true
09-01 10:59:32.371  2675  2691 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-01 10:59:32.371  2675  2691 D BluetoothAdapterProperties: Setting state to 10
09-01 10:59:32.371  2675  2691 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,09-01 10:59:32.371  2675  2691 I BluetoothAdapterState: Entering OffState
09-01 10:59:32.372   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-01 10:59:32.375  3887  3887 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-01 10:59:32.379  2675  2675 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-01 10:59:32.379  2675  2675 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-01 10:59:32.380  2675  2692 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-01 10:59:32.381  2675  2692 D bt_stack_manager: event_clean_up_stack finished.
,09-01 10:59:32.381  2675  2675 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-01 10:59:32.391  2675  2675 I art     : System.exit called, status: 0
09-01 10:59:32.391  2675  2675 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-01 10:59:32.454   873  1960 I ActivityManager: Process com.android.bluetooth (pid 2675) has died
,09-01 10:59:32.525  3887  3887 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-01 10:59:32.543  3834  3834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 10:59:32.568   873  2014 I ActivityManager: Start proc 3915:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-01 10:59:32.570  3834  3834 D DockEventReceiver: finishStartingService: stopping service
,09-01 10:59:32.575  3856  3878 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-01 10:59:32.610   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ff16b02:true
,09-01 10:59:32.638  3915  3915 D AdapterServiceConfig: Adding HeadsetService
09-01 10:59:32.638  3915  3915 D AdapterServiceConfig: Adding A2dpService
09-01 10:59:32.638  3915  3915 D AdapterServiceConfig: Adding HidService
09-01 10:59:32.638  3915  3915 D AdapterServiceConfig: Adding HealthService
09-01 10:59:32.639  3915  3915 D AdapterServiceConfig: Adding PanService
09-01 10:59:32.639  3915  3915 D AdapterServiceConfig: Adding GattService
09-01 10:59:32.639  3915  3915 D AdapterServiceConfig: Adding BluetoothMapService
09-01 10:59:32.640   873  2051 I ActivityManager: Killing 2802:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-01 10:59:32.681  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 10:59:32.707  1712  1712 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-01 10:59:32.710  1712  1712 D SystemUpdateService: onCreate
,09-01 10:59:32.718  1712  1712 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-01 10:59:32.723  1712  3927 I SystemUpdateService: active receiver: enabled
,09-01 10:59:32.730  1712  3927 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-01 10:59:32.734  1712  3927 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-01 10:59:32.734  1712  3927 I SystemUpdateService: now status is 0 (complete)
,09-01 10:59:32.734  1712  3927 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-01 10:59:32.734  1712  3927 I SystemUpdateService: file has been verified
09-01 10:59:32.734  1712  3927 I SystemUpdateService: OTA package size = 12249756
09-01 10:59:32.738  1712  3927 I SystemUpdateService: showing system update notification
,09-01 10:59:32.761  1712  1712 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-01 10:59:32.765  1712  2475 I iu.UploadsManager: num queued entries: 0
09-01 10:59:32.765  1712  2475 I iu.UploadsManager: num updated entries: 0
09-01 10:59:32.765  1712  2475 I iu.SyncManager: NEXT; no task
,09-01 10:59:32.773  1712  1712 D SystemUpdateService: onDestroy
,09-01 10:59:32.775  1712  1712 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-01 10:59:32.777  1712  1712 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-01 10:59:32.795   873  2051 I ActivityManager: Start proc 3929:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-01 10:59:32.869  3929  3929 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-01 10:59:32.872  3929  3929 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:32.885  3929  3929 D SprintDMHelper: simOperator: 
,09-01 10:59:32.885  3929  3929 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-01 10:59:32.934   873  2022 I ActivityManager: Start proc 3941:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-01 10:59:32.937   873  2022 I ActivityManager: Killing 1689:android.process.acore/u0a5 (adj 15): empty #17
,09-01 10:59:33.143   873  2051 I ActivityManager: Start proc 3956:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-01 10:59:33.150   873  2051 I ActivityManager: Killing 3616:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-01 10:59:33.276  3956  3956 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-01 10:59:33.352  3956  3956 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-01 10:59:33.352  3956  3956 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-01 10:59:33.352  3956  3956 I GAv4    :   adb logcat -s GAv4
,09-01 10:59:33.374  3956  3956 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-01 10:59:33.381  3956  3956 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-01 10:59:33.414  3956  3973 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-01 10:59:33.544  3956  3956 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-01 10:59:33.582  3956  3956 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-01 10:59:33.592  3956  3956 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 3919-3925)
,09-01 10:59:33.592  3956  3956 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-01 10:59:33.600  3956  3956 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7a08f9b}
,09-01 10:59:33.600  3956  3956 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-01 10:59:33.600  3956  3956 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-01 10:59:33.606  3956  3956 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-01 10:59:33.607  3956  3956 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-01 10:59:33.625  3956  3956 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-01 10:59:33.638  3956  3956 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-01 10:59:33.638  3956  3956 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-01 10:59:33.638  3956  3956 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-01 10:59:33.638  3956  3956 I Adreno  : Build Date                       : 10/20/15
09-01 10:59:33.638  3956  3956 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-01 10:59:33.638  3956  3956 I Adreno  : Local Branch                     : M14
09-01 10:59:33.638  3956  3956 I Adreno  : Remote Branch                    : 
09-01 10:59:33.638  3956  3956 I Adreno  : Remote Branch                    : 
09-01 10:59:33.638  3956  3956 I Adreno  : Reconstruct Branch               : 
,09-01 10:59:33.700  3956  3956 I NSApplication: Starting up...
,09-01 10:59:33.706  3956  4002 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-01 10:59:33.723   873  2051 I ActivityManager: Start proc 4007:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
09-01 10:59:33.725   873  2022 I ActivityManager: Killing 3633:com.android.musicfx/u0a18 (adj 15): empty #17
,09-01 10:59:33.814  4007  4007 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-01 10:59:33.999   873  2022 I ActivityManager: Killing 3440:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-01 10:59:34.956   873  1392 D WifiService: setWifiEnabled: true pid=3766, uid=10000
09-01 10:59:34.957   873  1392 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 10:59:34.974   873  1316 D WifiConfigStore: Loading config and enabling all networks 
,09-01 10:59:34.981  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:34.982  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:34.982  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:34.982  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:34.982  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:34.982  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:34.982  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:34.982  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:34.982  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:34.982  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:34.982  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:34.985  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:34.985  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:34.985  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:34.985  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:34.985  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:34.985  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:34.985  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:34.985  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:34.985  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:34.985  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:34.986  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:35.004   873  1316 D WifiConfigStore: loaded 0 passpoint configs
,09-01 10:59:35.005   873  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-01 10:59:35.006   873  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-01 10:59:35.007   873  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-01 10:59:35.007   873  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-01 10:59:35.007   873  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-01 10:59:35.007   873  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-01 10:59:35.021   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-01 10:59:35.022   873  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.12 rxSuccessRate=13.00 delta 1000 -> 994
09-01 10:59:35.022   371   871 D CommandListener: Setting iface cfg
09-01 10:59:35.023   873  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-01 10:59:35.023   873  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-01 10:59:35.031   873  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-01 10:59:35.031   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 10:59:35.038   873  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-01 10:59:35.039   873  1315 D WifiNative-HAL: p2pGetDeviceAddress
09-01 10:59:35.039   873  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-01 10:59:35.124   873  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-01 10:59:35.126  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-01 10:59:35.586  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-01 10:59:35.630  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-01 10:59:35.631  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-01 10:59:35.639   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 10:59:35.647   873  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-01 10:59:35.647   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 10:59:35.648   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-01 10:59:35.668   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 10:59:35.681   371   871 D CommandListener: Setting iface cfg
,09-01 10:59:35.683   873  1316 D WifiStateMachine: Start Dhcp Watchdog 2
,09-01 10:59:35.694   873  1318 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-01 10:59:35.696   873  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-01 10:59:35.722   873  4032 D DhcpClient: Receive thread started
,09-01 10:59:35.805   873  1316 E native  : do suspend false
,09-01 10:59:35.824   873  1939 D DhcpClient: Broadcasting DHCPDISCOVER
,09-01 10:59:35.858   873  4032 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172686, domain null
,09-01 10:59:35.859   873  1939 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172686 seconds
,09-01 10:59:35.862   873  1939 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-01 10:59:35.882   873  4032 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-01 10:59:35.883   873  1939 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-01 10:59:35.888   371   871 D CommandListener: Setting iface cfg
,09-01 10:59:35.899   873  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-01 10:59:35.900   873  1939 D DhcpClient: Scheduling renewal in 86399s
,09-01 10:59:35.919   873  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-01 10:59:35.923   873  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,09-01 10:59:35.923   873  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-01 10:59:35.925   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-01 10:59:35.927   873  1318 D ConnectivityService: Adding iface wlan0 to network 101
,09-01 10:59:35.945   873  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-01 10:59:36.014   873  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-01 10:59:36.014   873  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-01 10:59:36.016   873  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-01 10:59:36.018   873  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-01 10:59:36.018   873  1318 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-01 10:59:36.027   873  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-01 10:59:36.032   873  1318 D ConnectivityService: scheduleUnvalidatedPrompt 101
09-01 10:59:36.032   873  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-01 10:59:36.033   873  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-01 10:59:36.033   873  1318 D ConnectivityService:    accepting network in place of null
,09-01 10:59:36.033   873  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-01 10:59:36.033   873  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-01 10:59:36.035   873  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-01 10:59:36.055   873  4031 D NetlinkSocketObserver: NeighborEvent{elapsedMs=136388, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-01 10:59:36.084   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 10:59:36.136   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 10:59:36.147   873  4030 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.85,2a00:1450:400d:803::200e
,09-01 10:59:36.148   873  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-01 10:59:36.149   873  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:36.157   873  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-01 10:59:36.159   873   890 D Tethering: MasterInitialState.processMessage what=3
09-01 10:59:36.169  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:36.169  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:36.169  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:36.169  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:36.169  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:36.169  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:36.169  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:36.169  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:36.169  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 10:59:36.169  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:36.169  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:36.171  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:36.171  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:36.171  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:36.171  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:36.171  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:36.171  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:36.171  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:36.171  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:36.171  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-01 10:59:36.171  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:36.171  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 10:59:36.191  1712  1712 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-01 10:59:36.194  1712  1712 D SystemUpdateService: onCreate
,09-01 10:59:36.199  1712  1712 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-01 10:59:36.202  1712  4043 I SystemUpdateService: active receiver: enabled
,09-01 10:59:36.204  1712  4043 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-01 10:59:36.208  1712  4043 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-01 10:59:36.208  1712  4043 I SystemUpdateService: now status is 0 (complete)
09-01 10:59:36.208  1712  4043 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-01 10:59:36.208  1712  4043 I SystemUpdateService: file has been verified
09-01 10:59:36.208  1712  4043 I SystemUpdateService: OTA package size = 12249756
,09-01 10:59:36.213  1712  4043 I SystemUpdateService: showing system update notification
,09-01 10:59:36.219  1712  1712 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-01 10:59:36.220  1712  2475 I iu.UploadsManager: num queued entries: 0
,09-01 10:59:36.220  1712  2475 I iu.UploadsManager: num updated entries: 0
,09-01 10:59:36.222  1712  2475 I iu.SyncManager: NEXT; no task
,09-01 10:59:36.228  1712  1712 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-01 10:59:36.229  1712  1712 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-01 10:59:36.229  1712  1712 D SystemUpdateService: onDestroy
09-01 10:59:36.231  3929  3929 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-01 10:59:36.232  1712  4047 I MDM     : [175] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-01 10:59:36.232  1712  4047 W BaseAppContext: Using Auth Proxy for data requests.
09-01 10:59:36.234  1712  4047 V GoogleAuthProtoRequest: [175] a.<init>: mAccountName set to: thalitester@gmail.com
,09-01 10:59:36.236  3929  3929 D SprintDMHelper: simOperator: 
,09-01 10:59:36.236  3929  3929 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-01 10:59:36.243  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 10:59:36.245  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 10:59:36.270   873  4030 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Sep 2016 08:59:36 GMT], X-Android-Received-Millis=[1472720376268], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472720376185]}
,09-01 10:59:36.272   873  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-01 10:59:36.272   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-01 10:59:36.272   873  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-01 10:59:36.275   873  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-01 10:59:36.287  1503  1515 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager,
09-01 10:59:36.287  1503  1515 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-01 10:59:36.288  1503  1515 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 10:59:36.288  1503  1515 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 10:59:36.303  1712  4047 E MDM     : [175] SitrepService.a: Error sending sitrep.
,09-01 10:59:36.369  2225  4049 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-01 10:59:37.144   873  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-01 10:59:37.639   873  1960 I ActivityManager: Killing 3655:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-01 10:59:37.963   873  2022 D WifiService: setWifiEnabled: false pid=3766, uid=10000
,09-01 10:59:37.963   873  2022 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 10:59:37.983  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-01 10:59:37.993   873  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-01 10:59:37.993   873  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-01 10:59:37.994   873  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-01 10:59:37.994   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 10:59:38.019   873  1939 D DhcpClient: Clearing IP address
,09-01 10:59:38.022   371   871 D CommandListener: Clearing all IP addresses on wlan0
,09-01 10:59:38.027   371   871 D CommandListener: Setting iface cfg
,09-01 10:59:38.035  1503  4057 V NativeCrypto: Read error: ssl=0x9a77cc00: I/O error during system call, Connection timed out
,09-01 10:59:38.039  1503  4057 V NativeCrypto: SSL shutdown failed: ssl=0x9a77cc00: I/O error during system call, Broken pipe
,09-01 10:59:38.043   873  1401 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,09-01 10:59:38.044   873  4030 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
09-01 10:59:38.045   873  4032 D DhcpClient: Receive thread stopped
09-01 10:59:38.045   873  4030 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.85,2a00:1450:400d:803::200e
09-01 10:59:38.048   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-01 10:59:38.055   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-01 10:59:38.059   394   394 E Parcel  : Reading a NULL string not supported here.
09-01 10:59:38.061   873  1316 D WifiStateMachine: Start Disconnecting Watchdog 2
09-01 10:59:38.062   873  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-01 10:59:38.065   371   871 D CommandListener: Clearing all IP addresses on wlan0
,09-01 10:59:38.068   873  4030 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:803::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
09-01 10:59:38.073   873  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-01 10:59:38.074   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
09-01 10:59:38.076  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:38.076  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:38.076  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:38.076  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:38.076  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:38.076  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:38.076  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:38.076  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:38.076  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:38.076  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:38.077  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:38.078  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:38.078  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:38.078  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:38.078  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:38.078  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:38.078  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:38.078  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:38.078  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:38.078  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:38.078  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:38.078  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 10:59:38.078  1860  2317 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-01 10:59:38.080   873  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-01 10:59:38.107   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 10:59:38.135   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 10:59:38.136   873  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-01 10:59:38.136   873  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:38.137   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-01 10:59:38.141  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:38.141  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:38.146  1712  1712 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-01 10:59:38.151  1712  1712 D SystemUpdateService: onCreate
,09-01 10:59:38.154  1712  1712 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-01 10:59:38.162  1712  4067 I SystemUpdateService: active receiver: enabled
,09-01 10:59:38.164  1712  1712 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-01 10:59:38.167  1712  2475 I iu.UploadsManager: num queued entries: 0
,09-01 10:59:38.171  1712  4067 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-01 10:59:38.173  1712  1712 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-01 10:59:38.174  1712  1712 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-01 10:59:38.175  1712  4067 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-01 10:59:38.176  1712  4067 I SystemUpdateService: now status is 0 (complete)
,09-01 10:59:38.177  3929  3929 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:38.181  3929  3929 D SprintDMHelper: simOperator: 
,09-01 10:59:38.182  3929  3929 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-01 10:59:38.208  1712  2475 I iu.UploadsManager: num updated entries: 0
,09-01 10:59:38.176  1712  4067 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-01 10:59:38.214  1712  4067 I SystemUpdateService: file has been verified
09-01 10:59:38.214  1712  4067 I SystemUpdateService: OTA package size = 12249756
,09-01 10:59:38.216  2225  4072 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-01 10:59:38.220  1712  2475 I iu.SyncManager: NEXT; no task
,09-01 10:59:38.228   371   871 E Netd    : netlink response contains error (No such file or directory)
,09-01 10:59:38.229  1712  4067 I SystemUpdateService: showing system update notification
,09-01 10:59:38.232   873  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-01 10:59:38.239  1712  1712 D SystemUpdateService: onDestroy
,09-01 10:59:40.999   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3c27eed:true
09-01 10:59:40.999  3915  3915 D BluetoothAdapterState: make() - Creating AdapterState
,09-01 10:59:41.005  3915  3915 I bt_bluedroid: init
,09-01 10:59:41.005  3915  4075 I BluetoothAdapterState: Entering OffState
,09-01 10:59:41.011  3915  4076 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-01 10:59:41.011  3915  4076 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-01 10:59:41.011  3915  4076 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-01 10:59:41.012  3915  4076 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-01 10:59:41.013  3915  3915 I bt_bluedroid: get_profile_interface socket
,09-01 10:59:41.016  3915  3915 I bt_bluedroid: get_profile_interface sdp
09-01 10:59:41.016  3915  4079 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-01 10:59:41.019  3915  4079 D BluetoothAdapterProperties: Name is: Nexus 6
,09-01 10:59:41.021  3915  3925 I bt_bluedroid: config_hci_snoop_log
,09-01 10:59:41.023   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-01 10:59:41.033  3915  4075 D BluetoothAdapterState: Current state: OFF, message: 0
,09-01 10:59:41.033  3915  4075 D BluetoothAdapterProperties: Setting state to 14
09-01 10:59:41.034  3915  4075 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-01 10:59:41.038  3915  4075 D BluetoothBondStateMachine: make
,09-01 10:59:41.042  3915  4080 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-01 10:59:41.050  3915  3915 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-01 10:59:41.051  3915  4075 I BluetoothAdapterState: Entering PendingCommandState
,09-01 10:59:41.055  3915  3915 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae956a9
09-01 10:59:41.057  3915  3915 D BtGatt.DebugUtils: handleDebugAction() action=null
09-01 10:59:41.058  3915  3915 D BtGatt.GattService: Received start request. Starting profile...
09-01 10:59:41.058  3915  3915 D BtGatt.GattService: start()
09-01 10:59:41.058  3915  3915 I bt_bluedroid: get_profile_interface gatt
09-01 10:59:41.060  3915  3915 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae956a9
,09-01 10:59:41.061  3915  3915 D BtGatt.AdvertiseManager: advertise manager created
,09-01 10:59:41.071  3915  3915 V BluetoothAdapterState: isTurningOff()=false
09-01 10:59:41.071  3915  3915 V BluetoothAdapterState: isTurningOn()=false
09-01 10:59:41.072  3915  3915 V BluetoothAdapterState: isBleTurningOn()=true
09-01 10:59:41.072  3915  3915 V BluetoothAdapterState: isBleTurningOff()=false
09-01 10:59:41.072  3915  4075 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-01 10:59:41.073  3915  4075 I bt_bluedroid: enable
09-01 10:59:41.073  3915  4076 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-01 10:59:41.074  3915  4076 I bt_hci  : start_up
,09-01 10:59:41.079  3915  4076 I bt_vendor: alloc value 0xb39cc189
09-01 10:59:41.079  3915  4076 I bt_vendor: init
,09-01 10:59:41.079  3915  4076 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-01 10:59:41.079  3915  4076 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-01 10:59:41.186  3915  4076 D bt_hci  : start_up starting async portion
,09-01 10:59:41.186  3915  4083 I bt_hci  : event_finish_startup
,09-01 10:59:41.186  3915  4083 I bt_hci_h4: hal_open
09-01 10:59:41.187  3915  4083 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-01 10:59:41.197  3915  4083 I bt_userial_vendor: device fd = 51 open
,09-01 10:59:41.228  3915  4083 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-01 10:59:41.259  3915  4083 D bt_hwcfg: Chipset BCM4354A2
,09-01 10:59:41.260  3915  4083 D bt_hwcfg: Target name = [BCM4354A2]
09-01 10:59:41.261  3915  4083 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-01 10:59:41.924  3915  4083 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-01 10:59:41.926  3915  4083 D bt_hwcfg: Settlement delay -- 100 ms
09-01 10:59:41.927  3915  4083 I bt_hwcfg: Setting fw settlement delay to 100 
,09-01 10:59:42.044  3915  4083 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-01 10:59:42.045  3915  4083 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-01 10:59:42.073  3915  4083 I bt_hwcfg: vendor lib fwcfg completed
,09-01 10:59:42.073  3915  4083 I bt_vendor: firmware callback
09-01 10:59:42.074  3915  4083 I bt_hci  : firmware_config_callback
,09-01 10:59:42.085  3915  4085 I bt_btu  : btu_task pending for preload complete event
,09-01 10:59:42.085  3915  4085 I bt_btu_task: Bluetooth chip preload is complete
09-01 10:59:42.085  3915  4085 I bt_btu  : btu_task received preload complete event
,09-01 10:59:42.095  3915  4085 I         : BTE_InitTraceLevels -- TRC_HCI
,09-01 10:59:42.095  3915  4085 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-01 10:59:42.096  3915  4085 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-01 10:59:42.096  3915  4085 I         : BTE_InitTraceLevels -- TRC_AVDT
,09-01 10:59:42.096  3915  4085 I         : BTE_InitTraceLevels -- TRC_AVRC
09-01 10:59:42.096  3915  4085 I         : BTE_InitTraceLevels -- TRC_A2D
,09-01 10:59:42.097  3915  4085 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-01 10:59:42.097  3915  4085 I         : BTE_InitTraceLevels -- TRC_BTM
09-01 10:59:42.099  3915  4085 I         : BTE_InitTraceLevels -- TRC_GAP
,09-01 10:59:42.099  3915  4085 I         : BTE_InitTraceLevels -- TRC_PAN
09-01 10:59:42.100  3915  4085 I         : BTE_InitTraceLevels -- TRC_SDP
09-01 10:59:42.102  3915  4085 I         : BTE_InitTraceLevels -- TRC_GATT
,09-01 10:59:42.102  3915  4085 I         : BTE_InitTraceLevels -- TRC_SMP
09-01 10:59:42.103  3915  4085 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-01 10:59:42.104  3915  4085 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-01 10:59:42.239  3915  4085 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3949d9d
,09-01 10:59:42.239  3915  4085 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3949d9d ,
,09-01 10:59:42.251  3915  4079 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-01 10:59:42.254  3915  4079 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-01 10:59:42.255  3915  4079 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-01 10:59:42.260  3915  4079 D BluetoothAdapterProperties: Name is: Nexus 6
,09-01 10:59:42.263  3915  4079 D BluetoothAdapterProperties: Scan Mode:20
,09-01 10:59:42.263  3915  4079 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-01 10:59:42.265  3915  4079 D bt_hci  : do_postload posting postload work item
,09-01 10:59:42.265  3915  4083 I bt_hci  : event_postload
,09-01 10:59:42.265  3915  4083 I bt_vendor: sco_config_cb
,09-01 10:59:42.265  3915  4083 I bt_hci  : sco_config_callback postload finished.
09-01 10:59:42.268  3915  4079 D bt_bte_conf: Device ID record 1 : primary
09-01 10:59:42.268  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:42.268  3915  4079 D bt_bte_conf:   vendorId            = 000f
09-01 10:59:42.268  3915  4079 D bt_bte_conf:   vendorIdSource      = 0001
09-01 10:59:42.269  3915  4079 D bt_bte_conf:   product             = 1200
09-01 10:59:42.269  3915  4079 D bt_bte_conf:   version             = 1436
09-01 10:59:42.269  3915  4079 D bt_bte_conf:   clientExecutableURL = 
09-01 10:59:42.269  3915  4079 D bt_bte_conf:   serviceDescription  = 
09-01 10:59:42.269  3915  4079 D bt_bte_conf:   documentationURL    = 
09-01 10:59:42.270  3915  4079 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-01 10:59:42.270  3915  4076 D bt_stack_manager: event_start_up_stack finished
09-01 10:59:42.272  3915  4083 I bt_vendor: low_power_mode_cb
09-01 10:59:42.272  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:42.273  3915  4075 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-01 10:59:42.274  3915  4075 D BluetoothAdapterProperties: Setting state to 15
09-01 10:59:42.274  3915  4075 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-01 10:59:42.275  3915  4075 I BluetoothAdapterState: Entering BleOnState
09-01 10:59:42.281  3915  4075 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-01 10:59:42.281  3915  4075 D BluetoothAdapterProperties: Setting state to 11
,09-01 10:59:42.281  3915  4075 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-01 10:59:42.293  3915  3915 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae956a9
,09-01 10:59:42.295  3915  3915 D HeadsetService: Received start request. Starting profile...
09-01 10:59:42.299  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:42.302  3915  3915 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-01 10:59:42.302  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:42.302  3915  3915 D HeadsetStateMachine: make
,09-01 10:59:42.314  3915  4075 I BluetoothAdapterState: Entering PendingCommandState
,09-01 10:59:42.321  3915  3915 D HeadsetStateMachine: max_hf_connections = 1
,09-01 10:59:42.321  3915  3915 I bt_bluedroid: get_profile_interface handsfree
,09-01 10:59:42.322  3915  4079 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-01 10:59:42.323  3915  4079 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-01 10:59:42.326  3915  3915 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae956a9
09-01 10:59:42.327  3915  3915 D A2dpService: Received start request. Starting profile...
,09-01 10:59:42.328  3915  3915 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-01 10:59:42.328  3915  3915 I bt_bluedroid: get_profile_interface avrcp
,09-01 10:59:42.335  3915  3915 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-01 10:59:42.335  3915  3915 I BluetoothA2dpServiceJni: classInitNative: succeeds
,09-01 10:59:42.336  3915  3915 D A2dpStateMachine: make
,09-01 10:59:42.337  3915  3915 I bt_bluedroid: get_profile_interface a2dp
,09-01 10:59:42.338  3915  4079 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-01 10:59:42.340  3915  3915 I BluetoothHidServiceJni: classInitNative: succeeds
09-01 10:59:42.340  3915  4093 D A2dpStateMachine: Enter Disconnected: -2
09-01 10:59:42.341  3915  3915 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae956a9
09-01 10:59:42.342  3915  3915 D HidService: Received start request. Starting profile...
09-01 10:59:42.342  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 10:59:42.342  3915  3915 I bt_bluedroid: get_profile_interface hidhost
,09-01 10:59:42.343  3915  4079 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb392b3e5
09-01 10:59:42.343  3915  4079 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-01 10:59:42.343  3915  3915 D HidService: setHidService(): set to: null
09-01 10:59:42.344  3915  3915 I BluetoothHealthServiceJni: classInitNative: succeeds
09-01 10:59:42.345  3915  3915 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae956a9
09-01 10:59:42.345  3834  3834 D BluetoothInputDevice: Proxy object connected
09-01 10:59:42.345  3834  3834 D HidProfile: Bluetooth service connected
,09-01 10:59:42.346  3915  3915 D HealthService: Received start request. Starting profile...
,09-01 10:59:42.349  3915  3915 I bt_bluedroid: get_profile_interface health
09-01 10:59:42.351  3915  3915 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-01 10:59:42.351  3915  3915 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae956a9
,09-01 10:59:42.353  3834  3834 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 10:59:42.353  3915  3915 D PanService: Received start request. Starting profile...
,09-01 10:59:42.353  3915  3915 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-01 10:59:42.353  3915  3915 I bt_bluedroid: get_profile_interface pan
,09-01 10:59:42.354  3834  3834 D PanProfile: Bluetooth service connected
,09-01 10:59:42.354  3915  4079 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-01 10:59:42.357  3915  3915 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae956a9
,09-01 10:59:42.361  3915  3915 D BluetoothMapService: Received start request. Starting profile...
,09-01 10:59:42.361  3915  3915 D BluetoothMapService: start()
09-01 10:59:42.361  3834  3834 D BluetoothMap: Proxy object connected
09-01 10:59:42.362  3834  3834 D MapProfile: Bluetooth service connected
,09-01 10:59:42.362  3834  3834 D BluetoothMap: getConnectedDevices()
09-01 10:59:42.363  3834  3834 D BluetoothMap: Bluetooth is Not enabled
09-01 10:59:42.363  3915  3915 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-01 10:59:42.364  3915  3915 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-01 10:59:42.364  3915  3915 D BluetoothMapAppObserver: createReceiver()
09-01 10:59:42.365  3915  3915 D BluetoothMapAppObserver: initObservers()
09-01 10:59:42.365  3915  3915 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-01 10:59:42.372  3915  3915 V BluetoothAdapterState: isTurningOff()=false
09-01 10:59:42.372  3915  3915 V BluetoothAdapterState: isTurningOn()=true
09-01 10:59:42.372  3915  3915 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 10:59:42.372  3915  3915 V BluetoothAdapterState: isBleTurningOff()=false
09-01 10:59:42.372  3915  4091 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
09-01 10:59:42.374  3915  3915 V BluetoothAdapterState: isTurningOff()=false
09-01 10:59:42.374  3915  3915 V BluetoothAdapterState: isTurningOn()=true
09-01 10:59:42.374  3915  3915 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 10:59:42.374  3915  3915 V BluetoothAdapterState: isBleTurningOff()=false
09-01 10:59:42.374  3915  3915 V BluetoothAdapterState: isTurningOff()=false
09-01 10:59:42.374  3915  3915 V BluetoothAdapterState: isTurningOn()=true
09-01 10:59:42.374  3915  3915 V BluetoothAdapterState: isBleTurningOn()=false
09-01 10:59:42.374  3915  3915 V BluetoothAdapterState: isBleTurningOff()=false
09-01 10:59:42.376  3915  3915 V BluetoothAdapterState: isTurningOff()=false
,09-01 10:59:42.376  3915  3915 V BluetoothAdapterState: isTurningOn()=true
09-01 10:59:42.376  3915  3915 V BluetoothAdapterState: isBleTurningOn()=false
09-01 10:59:42.376  3915  3915 V BluetoothAdapterState: isBleTurningOff()=false
09-01 10:59:42.377  3915  3915 V BluetoothAdapterState: isTurningOff()=false
09-01 10:59:42.377  3915  3915 V BluetoothAdapterState: isTurningOn()=true
09-01 10:59:42.377  3915  3915 V BluetoothAdapterState: isBleTurningOn()=false
09-01 10:59:42.377  3915  3915 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 10:59:42.377  3915  3915 V BluetoothAdapterState: isTurningOff()=false
09-01 10:59:42.377  3915  3915 V BluetoothAdapterState: isTurningOn()=true
09-01 10:59:42.377  3915  3915 V BluetoothAdapterState: isBleTurningOn()=false
09-01 10:59:42.378  3915  3915 V BluetoothAdapterState: isBleTurningOff()=false
09-01 10:59:42.378  3915  4075 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-01 10:59:42.378  3915  4075 D BluetoothAdapterProperties: ScanMode =  20
09-01 10:59:42.378  3915  4075 D BluetoothAdapterProperties: State =  11
09-01 10:59:42.379  3915  4075 D BluetoothAdapterProperties: Setting state to 12
09-01 10:59:42.379  3915  4075 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-01 10:59:42.379  3915  4075 I BluetoothAdapterState: Entering OnState
,09-01 10:59:42.380  1361  1372 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-01 10:59:42.379  3915  4079 D BluetoothAdapterProperties: Scan Mode:21
09-01 10:59:42.380  3915  4079 D BluetoothAdapterProperties: Discoverable Timeout:120
09-01 10:59:42.381  1361  1361 D BluetoothInputDevice: Proxy object connected
,09-01 10:59:42.381  1361  1361 D HidProfile: Bluetooth service connected
09-01 10:59:42.382  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:42.382  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:42.382  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:42.382  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:42.382  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:42.382  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:42.382  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:42.382  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:42.384  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 10:59:42.386  3834  3848 D BluetoothPbap: onBluetoothStateChange: up=true
09-01 10:59:42.386  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:42.386  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:42.386  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:42.386  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:42.386  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:42.386  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:42.386  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:42.386  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:42.387  1361  2169 D BluetoothPbap: onBluetoothStateChange: up=true
09-01 10:59:42.388   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-01 10:59:42.388  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 10:59:42.389   873   873 D BluetoothA2dp: Proxy object connected
09-01 10:59:42.389   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 10:59:42.389   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 10:59:42.389   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 10:59:42.389  1361  1373 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 10:59:42.390  3915  3915 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-01 10:59:42.390  1361  1361 D BluetoothA2dp: Proxy object connected
09-01 10:59:42.391  3915  3915 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-01 10:59:42.392  1361  3842 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 10:59:42.392  3915  3915 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 10:59:42.392  3834  3848 D BluetoothMap: onBluetoothStateChange: up=true
09-01 10:59:42.392  1361  2169 D BluetoothPan: onBluetoothStateChange on: true
09-01 10:59:42.393  3915  3915 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 10:59:42.394  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 10:59:42.394  1361  1361 D PanProfile: Bluetooth service connected
09-01 10:59:42.394  3915  3915 D ObexServerSockets: Succeed to create listening sockets 
,09-01 10:59:42.394  3915  3915 D ObexServerSockets0: startAccept()
09-01 10:59:42.394  3915  3915 D ObexServerSockets0: prepareForNewConnect()
09-01 10:59:42.394  2008  2127 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 10:59:42.395  3834  3849 D BluetoothPan: onBluetoothStateChange on: true
09-01 10:59:42.395  3834  3848 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-01 10:59:42.395  1361  1373 D BluetoothMap: onBluetoothStateChange: up=true
09-01 10:59:42.396  3915  3915 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-01 10:59:42.396  3915  3915 D BluetoothSdpJni: SDP Create record success - handle: 0
09-01 10:59:42.397  1361  1361 D BluetoothMap: Proxy object connected
09-01 10:59:42.397  1361  1361 D MapProfile: Bluetooth service connected
09-01 10:59:42.397  1361  1361 D BluetoothMap: getConnectedDevices()
09-01 10:59:42.397  3915  4101 D ObexServerSockets0: Accepting socket connection...
09-01 10:59:42.398  3915  4100 D ObexServerSockets0: Accepting socket connection...
09-01 10:59:42.400   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,09-01 10:59:42.400  3915  3915 D BluetoothMapService: onReceive
09-01 10:59:42.400  3915  3915 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:42.400  3915  3915 D BluetoothMapService: STATE_ON
09-01 10:59:42.402  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:42.402  3834  3834 D LocalBluetoothProfileManager: Adding local A2DP profile
09-01 10:59:42.403  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:42.405  3834  3834 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-01 10:59:42.411  3834  3834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 10:59:42.412  3834  3834 D BluetoothA2dp: Proxy object connected
,09-01 10:59:42.420  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 10:59:42.421  3915  3915 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-01 10:59:42.421  3915  3915 D ObexServerSockets0: prepareForNewConnect()
,09-01 10:59:42.423  3915  4102 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 10:59:42.426  3834  3834 D DockEventReceiver: finishStartingService: stopping service
,09-01 10:59:42.426  3834  3834 D BluetoothPbap: Proxy object connected
09-01 10:59:42.427  3834  3834 D PbapServerProfile: Bluetooth service connected
09-01 10:59:42.427  1361  1361 D BluetoothPbap: Proxy object connected
09-01 10:59:42.427  1361  1361 D PbapServerProfile: Bluetooth service connected
,09-01 10:59:42.446  3915  4109 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 10:59:42.447  3915  4109 I BtOppRfcommListener: Accept thread started.
,09-01 10:59:42.493  1361  1373 D BluetoothHeadset: Proxy object connected
,09-01 10:59:42.493  1361  1361 D HeadsetProfile: Bluetooth service connected
09-01 10:59:42.493   873   873 D BluetoothHeadset: Proxy object connected
09-01 10:59:42.493   873   873 D BluetoothHeadset: Proxy object connected
,09-01 10:59:42.494   873   873 D BluetoothHeadset: Proxy object connected
09-01 10:59:42.494  2008  2031 D BluetoothHeadset: Proxy object connected
09-01 10:59:42.494  1361  3842 D BluetoothHeadset: Proxy object connected
,09-01 10:59:42.496  2008  2025 D BluetoothHeadset: Proxy object connected
,09-01 10:59:42.497  1361  1361 D HeadsetProfile: Bluetooth service connected
,09-01 10:59:42.511  3834  3849 D BluetoothHeadset: Proxy object connected
,09-01 10:59:42.511  3834  3834 D HeadsetProfile: Bluetooth service connected
,09-01 10:59:43.979  3915  4075 D BluetoothAdapterState: Current state: ON, message: 23
09-01 10:59:43.980  3915  4075 D BluetoothAdapterProperties: Setting state to 13
09-01 10:59:43.980  3915  4075 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-01 10:59:43.982  3915  4075 D BluetoothAdapterProperties: onBluetoothDisable()
,09-01 10:59:43.995  3915  3915 D BluetoothMapService: onReceive
,09-01 10:59:43.995  3915  3915 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-01 10:59:43.995  3915  4075 I BluetoothAdapterState: Entering PendingCommandState
,09-01 10:59:43.995  3915  3915 D BluetoothMapService: STATE_TURNING_OFF
,09-01 10:59:43.996  3915  3915 D BluetoothMapService: MAP Service closeService in
,09-01 10:59:43.996  3915  3915 D BluetoothMapMasInstance0: MAP Service shutdown
09-01 10:59:43.997  3915  3915 D ObexServerSockets0: shutdown(block = true)
09-01 10:59:43.998  3915  4100 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-01 10:59:44.000  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:44.000  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:44.000  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:44.000  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:44.000  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:44.000  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:44.000  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:44.000  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:44.000  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:44.001  3915  3915 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-01 10:59:44.002  3915  4101 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-01 10:59:44.003  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:44.003  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 10:59:44.009  3915  4088 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-01 10:59:44.010  3915  3915 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-01 10:59:44.011  3915  3915 I BtOppRfcommListener: stopping Accept Thread
09-01 10:59:44.011  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-01 10:59:44.012  3915  4109 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-01 10:59:44.012  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:44.012  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:44.012  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:44.012  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:44.012  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-01 10:59:44.012  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:44.012  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:44.012  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:44.013  3915  4079 D BluetoothAdapterProperties: Scan Mode:20
09-01 10:59:44.013  3766  3766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-01 10:59:44.013  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-01 10:59:44.013  3915  4075 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-01 10:59:44.013  3834  3834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 10:59:44.014  3915  4109 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-01 10:59:44.021  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:44.021  3915  3915 D HeadsetService: Received stop request...Stopping profile...
,09-01 10:59:44.022  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:44.028  1361  1372 D BluetoothHeadset: Proxy object disconnected
09-01 10:59:44.028   873   873 D BluetoothHeadset: Proxy object disconnected
,09-01 10:59:44.028   873   873 D BluetoothHeadset: Proxy object disconnected
09-01 10:59:44.028  1361  1361 D HeadsetProfile: Bluetooth service disconnected
,09-01 10:59:44.028  3834  3849 D BluetoothHeadset: Proxy object disconnected
,09-01 10:59:44.029   873   873 D BluetoothHeadset: Proxy object disconnected
,09-01 10:59:44.029  3915  3915 D A2dpService: Received stop request...Stopping profile...
09-01 10:59:44.029  3915  4093 D A2dpStateMachine: Exit Disconnected: -1
,09-01 10:59:44.029  2008  2128 D BluetoothHeadset: Proxy object disconnected
09-01 10:59:44.029  3834  3834 D DockEventReceiver: finishStartingService: stopping service
,09-01 10:59:44.030   873   873 D BluetoothA2dp: Proxy object disconnected
09-01 10:59:44.030  1361  1361 D BluetoothA2dp: Proxy object disconnected
09-01 10:59:44.031  3834  3834 D HeadsetProfile: Bluetooth service disconnected
09-01 10:59:44.031  3834  3834 D BluetoothA2dp: Proxy object disconnected
09-01 10:59:44.033  3915  3915 D HidService: Received stop request...Stopping profile...
09-01 10:59:44.033  3915  3915 D HidService: Stopping Bluetooth HidService
09-01 10:59:44.033  1361  1361 D BluetoothInputDevice: Proxy object disconnected
09-01 10:59:44.034  1361  1361 D HidProfile: Bluetooth service disconnected
09-01 10:59:44.034  3834  3834 D BluetoothInputDevice: Proxy object disconnected
09-01 10:59:44.034  3834  3834 D HidProfile: Bluetooth service disconnected
09-01 10:59:44.035  3915  3915 V BluetoothAdapterState: isTurningOff()=true
,09-01 10:59:44.035  3915  3915 V BluetoothAdapterState: isTurningOn()=false
,09-01 10:59:44.035  3915  3915 V BluetoothAdapterState: isBleTurningOn()=false
09-01 10:59:44.035  3915  3915 V BluetoothAdapterState: isBleTurningOff()=false
09-01 10:59:44.036  3915  3915 D HealthService: Received stop request...Stopping profile...
,09-01 10:59:44.036  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 10:59:44.037   873  1318 D ConnectivityService: handlePromptUnvalidated 101
09-01 10:59:44.038  3915  3915 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-01 10:59:44.038  3915  3915 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-01 10:59:44.039  3915  4085 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 10:59:44.039  3915  3915 D PanService: Received stop request...Stopping profile...
,09-01 10:59:44.040  3915  4085 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-01 10:59:44.040  3915  4085 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 10:59:44.038  3915  4079 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-01 10:59:44.040  3915  4079 E bt_btif : btif_hf_upstreams_evt: Invalid index 65534
09-01 10:59:44.041  1361  1361 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-01 10:59:44.041  1361  1361 D PanProfile: Bluetooth service disconnected
,09-01 10:59:44.041  3915  3915 V BluetoothAdapterState: isTurningOff()=true
09-01 10:59:44.041  3915  3915 V BluetoothAdapterState: isTurningOn()=false
09-01 10:59:44.041  3915  3915 V BluetoothAdapterState: isBleTurningOn()=false
09-01 10:59:44.042  3915  3915 V BluetoothAdapterState: isBleTurningOff()=false
09-01 10:59:44.042  3915  3915 D BluetoothMapService: Received stop request...Stopping profile...
09-01 10:59:44.042  3915  3915 D BluetoothMapService: stop()
09-01 10:59:44.043  3834  3834 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-01 10:59:44.043  3834  3834 D PanProfile: Bluetooth service disconnected
,09-01 10:59:44.043  3915  3915 D BluetoothMapAppObserver: deinitObservers()
,09-01 10:59:44.043  3915  3915 D BluetoothMapAppObserver: removeReceiver()
09-01 10:59:44.044  1361  1361 D BluetoothMap: Proxy object disconnected
09-01 10:59:44.044  1361  1361 D MapProfile: Bluetooth service disconnected
09-01 10:59:44.046  3915  4085 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 10:59:44.046  3915  4085 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-01 10:59:44.046  3915  4085 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-01 10:59:44.046  3915  4085 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 10:59:44.046  3915  4085 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-01 10:59:44.046  3915  4085 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-01 10:59:44.046  3915  4079 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-01 10:59:44.047  3915  3915 V BluetoothAdapterState: isTurningOff()=true
09-01 10:59:44.047  3915  3915 V BluetoothAdapterState: isTurningOn()=false
09-01 10:59:44.047  3915  3915 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 10:59:44.047  3915  3915 V BluetoothAdapterState: isBleTurningOff()=false
09-01 10:59:44.047  3915  3915 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-01 10:59:44.047  3915  3915 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-01 10:59:44.048  3915  4079 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-01 10:59:44.050  3834  3834 D BluetoothMap: Proxy object disconnected
09-01 10:59:44.050  1361  1361 D BluetoothPbap: Proxy object disconnected
09-01 10:59:44.050  1361  1361 D PbapServerProfile: Bluetooth service disconnected
,09-01 10:59:44.050  3834  3834 D MapProfile: Bluetooth service disconnected
09-01 10:59:44.051  3915  3915 V BluetoothAdapterState: isTurningOff()=true
09-01 10:59:44.051  3915  3915 V BluetoothAdapterState: isTurningOn()=false
09-01 10:59:44.051  3915  3915 V BluetoothAdapterState: isBleTurningOn()=false
09-01 10:59:44.051  3915  3915 V BluetoothAdapterState: isBleTurningOff()=false
09-01 10:59:44.051  3915  3915 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-01 10:59:44.051  3915  4079 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,09-01 10:59:44.051  3915  3915 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-01 10:59:44.052  3915  3915 V BluetoothAdapterState: isTurningOff()=true
09-01 10:59:44.052  3915  3915 V BluetoothAdapterState: isTurningOn()=false
09-01 10:59:44.052  3915  3915 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 10:59:44.052  3915  3915 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 10:59:44.052  3915  3915 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-01 10:59:44.052  3915  3915 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-01 10:59:44.053  3915  3915 D BluetoothMapService: MAP Service closeService in
,09-01 10:59:44.053  3915  3915 V BluetoothAdapterState: isTurningOff()=true
09-01 10:59:44.053  3915  3915 V BluetoothAdapterState: isTurningOn()=false
09-01 10:59:44.053  3915  3915 V BluetoothAdapterState: isBleTurningOn()=false
09-01 10:59:44.053  3915  3915 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 10:59:44.054  3915  3915 D BluetoothMapService: cleanup()
09-01 10:59:44.054  3915  3915 D BluetoothMapService: MAP Service closeService in
09-01 10:59:44.054  3915  4075 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-01 10:59:44.054  3915  4075 D BluetoothAdapterProperties: Setting state to 15
,09-01 10:59:44.054  3915  4075 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-01 10:59:44.055  1361  2169 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-01 10:59:44.055  3834  3834 D BluetoothPbap: Proxy object disconnected
09-01 10:59:44.055  3834  3834 D PbapServerProfile: Bluetooth service disconnected
09-01 10:59:44.056  3834  3849 D BluetoothPbap: onBluetoothStateChange: up=false
09-01 10:59:44.056  3915  4075 I BluetoothAdapterState: Entering BleOnState
,09-01 10:59:44.056  1361  3842 D BluetoothPbap: onBluetoothStateChange: up=false
,09-01 10:59:44.057  3834  3848 D BluetoothA2dp: onBluetoothStateChange: up=false
09-01 10:59:44.057   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 10:59:44.057   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 10:59:44.057   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 10:59:44.057   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 10:59:44.057  3834  3849 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 10:59:44.058  1361  1372 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-01 10:59:44.058  1361  1373 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 10:59:44.059  3834  3848 D BluetoothMap: onBluetoothStateChange: up=false
09-01 10:59:44.059  1361  2169 D BluetoothPan: onBluetoothStateChange on: false
09-01 10:59:44.059  2008  2127 D BluetoothHeadset: onBluetoothStateChange: up=false
09-01 10:59:44.060  3834  3849 D BluetoothPan: onBluetoothStateChange on: false
,09-01 10:59:44.060  3834  3848 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-01 10:59:44.061  1361  3842 D BluetoothMap: onBluetoothStateChange: up=false
09-01 10:59:44.061  3915  4075 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-01 10:59:44.062  3915  4075 D BluetoothAdapterProperties: Setting state to 16
09-01 10:59:44.062  3915  4075 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-01 10:59:44.062  3915  4075 D BluetoothAdapterProperties: onBleDisable
,09-01 10:59:44.062  3915  4075 I BluetoothAdapterState: Entering PendingCommandState
09-01 10:59:44.062  3915  4076 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-01 10:59:44.063  3915  4085 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-01 10:59:44.063  3915  4085 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-01 10:59:44.068  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:44.069  3915  4079 D BluetoothAdapterProperties: Scan Mode:20
09-01 10:59:44.069  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:44.070  3834  3834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-01 10:59:44.070  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:44.071  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:44.077  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 10:59:44.078  3834  3834 D DockEventReceiver: finishStartingService: stopping service
,09-01 10:59:44.265  3915  4079 I bt_hci  : shut_down
,09-01 10:59:44.281  3915  4083 D bt_hwcfg: hw_epilog_process
,09-01 10:59:44.281  3915  4083 I bt_vendor: low_power_mode_cb
,09-01 10:59:44.304  3915  4083 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-01 10:59:44.304  3915  4083 I bt_vendor: epilog_cb
,09-01 10:59:44.305  3915  4083 I bt_hci  : epilog_finished_callback
,09-01 10:59:44.312  3915  4079 I bt_hci_h4: hal_close
,09-01 10:59:44.313  3915  4079 I bt_userial_vendor: device fd = 51 close
,09-01 10:59:44.441  3915  4076 D bt_stack_manager: event_shut_down_stack finished.
,09-01 10:59:44.442  3915  4075 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-01 10:59:44.448  3915  4075 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-01 10:59:44.448  3915  3915 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-01 10:59:44.450  3915  3915 D BtGatt.GattService: Received stop request...Stopping profile...
,09-01 10:59:44.450  3915  3915 D BtGatt.GattService: stop()
09-01 10:59:44.451  3915  3915 D BtGatt.AdvertiseManager: advertise clients cleared
,09-01 10:59:44.455  3915  3915 V BluetoothAdapterState: isTurningOff()=false
,09-01 10:59:44.455  3915  3915 V BluetoothAdapterState: isTurningOn()=false
,09-01 10:59:44.456  3915  3915 V BluetoothAdapterState: isBleTurningOn()=false
09-01 10:59:44.456  3915  3915 V BluetoothAdapterState: isBleTurningOff()=true
,09-01 10:59:44.457  3915  4075 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-01 10:59:44.458  3915  4075 D BluetoothAdapterProperties: Setting state to 10
09-01 10:59:44.458  3915  4075 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-01 10:59:44.459  3915  4075 I BluetoothAdapterState: Entering OffState
09-01 10:59:44.461   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-01 10:59:44.480  3915  3915 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-01 10:59:44.481  3915  3915 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-01 10:59:44.481  3915  4076 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-01 10:59:44.484  3915  4076 D bt_stack_manager: event_clean_up_stack finished.
09-01 10:59:44.484  3915  3915 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-01 10:59:44.486  3915  3915 I art     : System.exit called, status: 0
09-01 10:59:44.486  3915  3915 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-01 10:59:44.543   873  2015 I ActivityManager: Process com.android.bluetooth (pid 3915) has died
,09-01 10:59:46.977  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 10:59:46.977  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:49.544   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-01 10:59:49.553  1901  1901 I Keyboard.Facilitator: onFinishInput()
,09-01 10:59:49.561   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-01 10:59:49.561   873   893 I Adreno  : Build Date                       : 10/20/15
09-01 10:59:49.561   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-01 10:59:49.561   873   893 I Adreno  : Local Branch                     : M14
09-01 10:59:49.561   873   893 I Adreno  : Remote Branch                    : 
09-01 10:59:49.561   873   893 I Adreno  : Remote Branch                    : 
09-01 10:59:49.561   873   893 I Adreno  : Reconstruct Branch               : 
,09-01 10:59:49.603   281  1308 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (177 us)
,09-01 10:59:49.985  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 10:59:49.990  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@31f5587 added. We now have 6 listener(s)
09-01 10:59:49.992  3766  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:49.997  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:49.998  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dd0bcb4 added. We now have 7 listener(s)
09-01 10:59:49.998  3766  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:50.000  3766  3814 I System.out: IsBluetoothEnabled
,09-01 10:59:50.008  3766  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:50.050   873   890 I ActivityManager: Start proc 4122:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-01 10:59:50.219  3766  3766 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-01 10:59:50.220  3766  3766 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-01 10:59:50.270   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-01 10:59:50.273  4122  4122 D AdapterServiceConfig: Adding HeadsetService
,09-01 10:59:50.274  4122  4122 D AdapterServiceConfig: Adding A2dpService
,09-01 10:59:50.274  4122  4122 D AdapterServiceConfig: Adding HidService
,09-01 10:59:50.274  4122  4122 D AdapterServiceConfig: Adding HealthService
09-01 10:59:50.275  4122  4122 D AdapterServiceConfig: Adding PanService
09-01 10:59:50.275  4122  4122 D AdapterServiceConfig: Adding GattService
09-01 10:59:50.275  4122  4122 D AdapterServiceConfig: Adding BluetoothMapService
,09-01 10:59:50.279  3766  3766 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7d7b465 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@29760dd, 16908290=android.view.AbsSavedState$1@29760dd}, android:focusedViewId=100}]}]
09-01 10:59:50.279  3766  3766 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-01 10:59:50.281  3766  3766 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-01 10:59:50.281  3766  3766 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-01 10:59:50.290   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
09-01 10:59:50.291   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@10760ad:true
09-01 10:59:50.291  4122  4122 D BluetoothAdapterState: make() - Creating AdapterState
09-01 10:59:50.294  4122  4122 I bt_bluedroid: init
09-01 10:59:50.295   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6b24000
09-01 10:59:50.295  4122  4134 I BluetoothAdapterState: Entering OffState
,09-01 10:59:50.295   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
09-01 10:59:50.296   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
09-01 10:59:50.296  4122  4135 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-01 10:59:50.296  4122  4135 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-01 10:59:50.296  4122  4135 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-01 10:59:50.297  4122  4135 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-01 10:59:50.300  4122  4122 I bt_bluedroid: get_profile_interface socket
09-01 10:59:50.302  4122  4122 I bt_bluedroid: get_profile_interface sdp
09-01 10:59:50.304  4122  4138 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-01 10:59:50.305  4122  4138 D BluetoothAdapterProperties: Name is: Nexus 6
,09-01 10:59:50.311  4122  4132 I bt_bluedroid: config_hci_snoop_log
,09-01 10:59:50.311   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-01 10:59:50.317  4122  4134 D BluetoothAdapterState: Current state: OFF, message: 0
09-01 10:59:50.317  4122  4134 D BluetoothAdapterProperties: Setting state to 14
09-01 10:59:50.317  4122  4134 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-01 10:59:50.318  4122  4134 D BluetoothBondStateMachine: make
,09-01 10:59:50.320  4122  4139 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-01 10:59:50.322  4122  4134 I BluetoothAdapterState: Entering PendingCommandState
,09-01 10:59:50.322  4122  4122 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-01 10:59:50.324  4122  4122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae956a9
09-01 10:59:50.324  4122  4122 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-01 10:59:50.325  4122  4122 D BtGatt.GattService: Received start request. Starting profile...
09-01 10:59:50.325  4122  4122 D BtGatt.GattService: start()
09-01 10:59:50.325  4122  4122 I bt_bluedroid: get_profile_interface gatt
09-01 10:59:50.325  4122  4122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae956a9
09-01 10:59:50.325  4122  4122 D BtGatt.AdvertiseManager: advertise manager created
,09-01 10:59:50.330  4122  4122 V BluetoothAdapterState: isTurningOff()=false
,09-01 10:59:50.330  4122  4122 V BluetoothAdapterState: isTurningOn()=false
09-01 10:59:50.330  4122  4122 V BluetoothAdapterState: isBleTurningOn()=true
09-01 10:59:50.330  4122  4122 V BluetoothAdapterState: isBleTurningOff()=false
09-01 10:59:50.330  4122  4134 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-01 10:59:50.331  4122  4134 I bt_bluedroid: enable
09-01 10:59:50.331  4122  4135 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-01 10:59:50.332  4122  4135 I bt_hci  : start_up
,09-01 10:59:50.346  4122  4135 I bt_vendor: alloc value 0xb39dc189
,09-01 10:59:50.346  4122  4135 I bt_vendor: init
09-01 10:59:50.346  4122  4135 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-01 10:59:50.347  4122  4135 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-01 10:59:50.457  4122  4135 D bt_hci  : start_up starting async portion
,09-01 10:59:50.458  4122  4142 I bt_hci  : event_finish_startup
09-01 10:59:50.458  4122  4142 I bt_hci_h4: hal_open
09-01 10:59:50.458  4122  4142 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-01 10:59:50.467  4122  4142 I bt_userial_vendor: device fd = 51 open
,09-01 10:59:50.498  4122  4142 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-01 10:59:50.523   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-01 10:59:50.529   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-01 10:59:50.534   873  1342 D SurfaceControl: Excessive delay in setPowerMode(): 239ms
,09-01 10:59:50.536  4122  4142 D bt_hwcfg: Chipset BCM4354A2
,09-01 10:59:50.537  4122  4142 D bt_hwcfg: Target name = [BCM4354A2]
09-01 10:59:50.537  4122  4142 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
09-01 10:59:50.539   873   893 I DreamManagerService: Entering dreamland.
09-01 10:59:50.540   873   893 I PowerManagerService: Dozing...
,09-01 10:59:50.542   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-01 10:59:50.608   375  1287 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
09-01 10:59:50.608   375  1287 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-01 10:59:50.616   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 10:59:50.627  1994  4145 D NfcService: Discovery configuration equal, not updating.
,09-01 10:59:50.629   873  1316 E native  : do suspend false
,09-01 10:59:50.652   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 10:59:50.658   873  1316 E native  : do suspend true
,09-01 10:59:50.749   375  1324 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-01 10:59:50.749   375  1324 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-01 10:59:51.353  4122  4142 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-01 10:59:51.355  4122  4142 D bt_hwcfg: Settlement delay -- 100 ms
,09-01 10:59:51.355  4122  4142 I bt_hwcfg: Setting fw settlement delay to 100 
,09-01 10:59:51.473  4122  4142 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-01 10:59:51.475  4122  4142 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-01 10:59:51.502  4122  4142 I bt_hwcfg: vendor lib fwcfg completed
,09-01 10:59:51.502  4122  4142 I bt_vendor: firmware callback
09-01 10:59:51.503  4122  4142 I bt_hci  : firmware_config_callback
,09-01 10:59:51.518  4122  4149 I bt_btu  : btu_task pending for preload complete event
,09-01 10:59:51.519  4122  4149 I bt_btu_task: Bluetooth chip preload is complete
09-01 10:59:51.519  4122  4149 I bt_btu  : btu_task received preload complete event
,09-01 10:59:51.529  4122  4149 I         : BTE_InitTraceLevels -- TRC_HCI
,09-01 10:59:51.529  4122  4149 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-01 10:59:51.529  4122  4149 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-01 10:59:51.529  4122  4149 I         : BTE_InitTraceLevels -- TRC_AVDT
09-01 10:59:51.530  4122  4149 I         : BTE_InitTraceLevels -- TRC_AVRC
09-01 10:59:51.530  4122  4149 I         : BTE_InitTraceLevels -- TRC_A2D
09-01 10:59:51.530  4122  4149 I         : BTE_InitTraceLevels -- TRC_BNEP
09-01 10:59:51.531  4122  4149 I         : BTE_InitTraceLevels -- TRC_BTM
09-01 10:59:51.531  4122  4149 I         : BTE_InitTraceLevels -- TRC_GAP
09-01 10:59:51.531  4122  4149 I         : BTE_InitTraceLevels -- TRC_PAN
09-01 10:59:51.531  4122  4149 I         : BTE_InitTraceLevels -- TRC_SDP
09-01 10:59:51.532  4122  4149 I         : BTE_InitTraceLevels -- TRC_GATT
09-01 10:59:51.532  4122  4149 I         : BTE_InitTraceLevels -- TRC_SMP
09-01 10:59:51.532  4122  4149 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-01 10:59:51.532  4122  4149 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-01 10:59:51.676  4122  4149 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3959d9d,
09-01 10:59:51.677  4122  4149 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3959d9d 
,09-01 10:59:51.688  4122  4138 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false,
09-01 10:59:51.690  4122  4138 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-01 10:59:51.690  4122  4138 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-01 10:59:51.693  4122  4138 D BluetoothAdapterProperties: Name is: Nexus 6
,09-01 10:59:51.694  4122  4138 D BluetoothAdapterProperties: Scan Mode:20
,09-01 10:59:51.694  4122  4138 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-01 10:59:51.694  4122  4138 D bt_hci  : do_postload posting postload work item
,09-01 10:59:51.695  4122  4142 I bt_hci  : event_postload
,09-01 10:59:51.695  4122  4142 I bt_vendor: sco_config_cb
,09-01 10:59:51.695  4122  4142 I bt_hci  : sco_config_callback postload finished.
,09-01 10:59:51.698  4122  4138 D bt_bte_conf: Device ID record 1 : primary
,09-01 10:59:51.698  4122  4138 D bt_bte_conf:   vendorId            = 000f
,09-01 10:59:51.699  4122  4138 D bt_bte_conf:   vendorIdSource      = 0001
,09-01 10:59:51.699  4122  4138 D bt_bte_conf:   product             = 1200
09-01 10:59:51.699  4122  4138 D bt_bte_conf:   version             = 1436
,09-01 10:59:51.699  4122  4138 D bt_bte_conf:   clientExecutableURL = 
09-01 10:59:51.699  4122  4138 D bt_bte_conf:   serviceDescription  = 
,09-01 10:59:51.699  4122  4138 D bt_bte_conf:   documentationURL    = 
,09-01 10:59:51.699  4122  4138 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-01 10:59:51.699  4122  4135 D bt_stack_manager: event_start_up_stack finished
,09-01 10:59:51.700  4122  4134 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-01 10:59:51.699  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:51.700  4122  4134 D BluetoothAdapterProperties: Setting state to 15
,09-01 10:59:51.700  4122  4134 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-01 10:59:51.701  4122  4134 I BluetoothAdapterState: Entering BleOnState
,09-01 10:59:51.703  4122  4142 I bt_vendor: low_power_mode_cb
,09-01 10:59:51.706  4122  4134 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-01 10:59:51.707  4122  4134 D BluetoothAdapterProperties: Setting state to 11
09-01 10:59:51.707  4122  4134 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,09-01 10:59:51.718  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:51.723  4122  4122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae956a9
09-01 10:59:51.724  4122  4122 D HeadsetService: Received start request. Starting profile...
,09-01 10:59:51.730  4122  4122 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-01 10:59:51.731  4122  4122 D HeadsetStateMachine: make
,09-01 10:59:51.732  4122  4134 I BluetoothAdapterState: Entering PendingCommandState
,09-01 10:59:51.741  4122  4122 D HeadsetStateMachine: max_hf_connections = 1
09-01 10:59:51.741  4122  4122 I bt_bluedroid: get_profile_interface handsfree
,09-01 10:59:51.741  4122  4138 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-01 10:59:51.742  4122  4138 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-01 10:59:51.747  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-01 10:59:51.748  4122  4122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae956a9
09-01 10:59:51.748  4122  4122 D A2dpService: Received start request. Starting profile...
,09-01 10:59:51.749  4122  4122 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-01 10:59:51.749  4122  4122 I bt_bluedroid: get_profile_interface avrcp
,09-01 10:59:51.757  4122  4122 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-01 10:59:51.757  4122  4122 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-01 10:59:51.757  4122  4122 D A2dpStateMachine: make
,09-01 10:59:51.759  4122  4122 I bt_bluedroid: get_profile_interface a2dp
,09-01 10:59:51.760  4122  4138 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-01 10:59:51.762  4122  4157 D A2dpStateMachine: Enter Disconnected: -2
,09-01 10:59:51.763  4122  4122 I BluetoothHidServiceJni: classInitNative: succeeds
,09-01 10:59:51.764  4122  4122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae956a9
,09-01 10:59:51.764  4122  4122 D HidService: Received start request. Starting profile...
,09-01 10:59:51.765  4122  4122 I bt_bluedroid: get_profile_interface hidhost
,09-01 10:59:51.765  4122  4122 D HidService: setHidService(): set to: null
09-01 10:59:51.765  4122  4138 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb393b3e5,
,09-01 10:59:51.765  4122  4138 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-01 10:59:51.766  4122  4122 I BluetoothHealthServiceJni: classInitNative: succeeds
09-01 10:59:51.767  4122  4122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae956a9
09-01 10:59:51.768  4122  4122 D HealthService: Received start request. Starting profile...
,09-01 10:59:51.770  4122  4122 I bt_bluedroid: get_profile_interface health
,09-01 10:59:51.771  4122  4122 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-01 10:59:51.772  4122  4122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae956a9
,09-01 10:59:51.773  4122  4122 D PanService: Received start request. Starting profile...
,09-01 10:59:51.773  4122  4122 D BluetoothPanServiceJni: initializeNative(L110): pan
09-01 10:59:51.773  4122  4122 I bt_bluedroid: get_profile_interface pan
,09-01 10:59:51.774  4122  4138 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-01 10:59:51.777  4122  4122 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae956a9
,09-01 10:59:51.778  4122  4122 D BluetoothMapService: Received start request. Starting profile...
,09-01 10:59:51.778  4122  4122 D BluetoothMapService: start()
09-01 10:59:51.781  4122  4122 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-01 10:59:51.782  4122  4122 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-01 10:59:51.782  4122  4122 D BluetoothMapAppObserver: createReceiver()
,09-01 10:59:51.785  4122  4122 D BluetoothMapAppObserver: initObservers()
,09-01 10:59:51.785  4122  4122 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-01 10:59:51.795  4122  4122 V BluetoothAdapterState: isTurningOff()=false
09-01 10:59:51.795  4122  4122 V BluetoothAdapterState: isTurningOn()=true
,09-01 10:59:51.795  4122  4122 V BluetoothAdapterState: isBleTurningOn()=false
09-01 10:59:51.796  4122  4122 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 10:59:51.799  4122  4155 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
,09-01 10:59:51.799  4122  4122 V BluetoothAdapterState: isTurningOff()=false
09-01 10:59:51.799  4122  4122 V BluetoothAdapterState: isTurningOn()=true
09-01 10:59:51.799  4122  4122 V BluetoothAdapterState: isBleTurningOn()=false
09-01 10:59:51.799  4122  4122 V BluetoothAdapterState: isBleTurningOff()=false
09-01 10:59:51.800  4122  4122 V BluetoothAdapterState: isTurningOff()=false
09-01 10:59:51.800  4122  4122 V BluetoothAdapterState: isTurningOn()=true
,09-01 10:59:51.800  4122  4122 V BluetoothAdapterState: isBleTurningOn()=false
09-01 10:59:51.800  4122  4122 V BluetoothAdapterState: isBleTurningOff()=false
09-01 10:59:51.800  4122  4122 V BluetoothAdapterState: isTurningOff()=false
09-01 10:59:51.800  4122  4122 V BluetoothAdapterState: isTurningOn()=true
09-01 10:59:51.800  4122  4122 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 10:59:51.800  4122  4122 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 10:59:51.802  4122  4122 V BluetoothAdapterState: isTurningOff()=false
,09-01 10:59:51.802  4122  4122 V BluetoothAdapterState: isTurningOn()=true
09-01 10:59:51.802  4122  4122 V BluetoothAdapterState: isBleTurningOn()=false
09-01 10:59:51.802  4122  4122 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 10:59:51.802  4122  4122 V BluetoothAdapterState: isTurningOff()=false
09-01 10:59:51.802  4122  4122 V BluetoothAdapterState: isTurningOn()=true
,09-01 10:59:51.802  4122  4122 V BluetoothAdapterState: isBleTurningOn()=false
,09-01 10:59:51.803  4122  4122 V BluetoothAdapterState: isBleTurningOff()=false
,09-01 10:59:51.803  4122  4134 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-01 10:59:51.803  4122  4134 D BluetoothAdapterProperties: ScanMode =  20
,09-01 10:59:51.804  4122  4134 D BluetoothAdapterProperties: State =  11
,09-01 10:59:51.804  4122  4134 D BluetoothAdapterProperties: Setting state to 12
,09-01 10:59:51.804  4122  4134 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-01 10:59:51.807  4122  4138 D BluetoothAdapterProperties: Scan Mode:21
,09-01 10:59:51.808  4122  4138 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-01 10:59:51.808  4122  4134 I BluetoothAdapterState: Entering OnState
09-01 10:59:51.809  1361  1373 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-01 10:59:51.812  3834  3848 D BluetoothPbap: onBluetoothStateChange: up=true
09-01 10:59:51.813  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:51.813  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:51.813  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:51.813  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:51.813  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:51.813  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:51.813  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:51.813  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-01 10:59:51.813  4122  4122 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-01 10:59:51.813  1361  1361 D BluetoothInputDevice: Proxy object connected
,09-01 10:59:51.814  1361  1361 D HidProfile: Bluetooth service connected
09-01 10:59:51.814  4122  4122 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
09-01 10:59:51.816  4122  4122 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 10:59:51.818  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:51.818  1361  3842 D BluetoothPbap: onBluetoothStateChange: up=true
09-01 10:59:51.819  4122  4122 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-01 10:59:51.821  4122  4122 D ObexServerSockets: Succeed to create listening sockets 
09-01 10:59:51.821  4122  4122 D ObexServerSockets0: startAccept()
09-01 10:59:51.821  4122  4122 D ObexServerSockets0: prepareForNewConnect()
,09-01 10:59:51.822  3834  3849 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 10:59:51.824   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 10:59:51.824  4122  4122 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-01 10:59:51.824  4122  4122 D BluetoothSdpJni: SDP Create record success - handle: 0
09-01 10:59:51.824   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 10:59:51.824   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 10:59:51.825   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 10:59:51.825  3834  3848 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 10:59:51.825  4122  4164 D ObexServerSockets0: Accepting socket connection...
09-01 10:59:51.825  4122  4165 D ObexServerSockets0: Accepting socket connection...
,09-01 10:59:51.826  1361  1372 D BluetoothA2dp: onBluetoothStateChange: up=true
09-01 10:59:51.826   873   873 D BluetoothA2dp: Proxy object connected
09-01 10:59:51.826  3834  3834 D BluetoothA2dp: Proxy object connected
,09-01 10:59:51.828  1361  1361 D BluetoothA2dp: Proxy object connected
09-01 10:59:51.828  1361  2169 D BluetoothHeadset: onBluetoothStateChange: up=true
09-01 10:59:51.829  3834  3848 D BluetoothMap: onBluetoothStateChange: up=true
09-01 10:59:51.832  1361  3842 D BluetoothPan: onBluetoothStateChange on: true
09-01 10:59:51.834  2008  2128 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-01 10:59:51.835  3834  3848 D BluetoothPan: onBluetoothStateChange on: true
09-01 10:59:51.835  1361  1361 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 10:59:51.835  1361  1361 D PanProfile: Bluetooth service connected
09-01 10:59:51.837  3834  3849 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-01 10:59:51.839  1361  1372 D BluetoothMap: onBluetoothStateChange: up=true
,09-01 10:59:51.840  3834  3834 D BluetoothMap: Proxy object connected
,09-01 10:59:51.840  3834  3834 D MapProfile: Bluetooth service connected
09-01 10:59:51.840  3834  3834 D BluetoothMap: getConnectedDevices()
09-01 10:59:51.841  1361  1361 D BluetoothMap: Proxy object connected
09-01 10:59:51.841  1361  1361 D MapProfile: Bluetooth service connected
,09-01 10:59:51.841  1361  1361 D BluetoothMap: getConnectedDevices()
,09-01 10:59:51.843   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
,09-01 10:59:51.844  4122  4122 D BluetoothMapService: onReceive
09-01 10:59:51.844  4122  4122 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-01 10:59:51.844  4122  4122 D BluetoothMapService: STATE_ON
09-01 10:59:51.845  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:51.845  3834  3834 D BluetoothPan: BluetoothPAN Proxy object connected
09-01 10:59:51.845  3834  3834 D PanProfile: Bluetooth service connected
09-01 10:59:51.846  3834  3834 D BluetoothInputDevice: Proxy object connected
,09-01 10:59:51.846  3834  3834 D HidProfile: Bluetooth service connected
,09-01 10:59:51.853  3834  3834 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-01 10:59:51.861  1503  1503 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-01 10:59:51.862  3834  3834 D DockEventReceiver: finishStartingService: stopping service
,09-01 10:59:51.871  3834  3834 D BluetoothPbap: Proxy object connected
09-01 10:59:51.871  4122  4122 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-01 10:59:51.871  3834  3834 D PbapServerProfile: Bluetooth service connected
09-01 10:59:51.871  4122  4122 D ObexServerSockets0: prepareForNewConnect()
,09-01 10:59:51.873  1361  1361 D BluetoothPbap: Proxy object connected
,09-01 10:59:51.873  1361  1361 D PbapServerProfile: Bluetooth service connected
,09-01 10:59:51.885  4122  4170 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 10:59:51.902  4122  4174 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-01 10:59:51.904  4122  4174 I BtOppRfcommListener: Accept thread started.
,09-01 10:59:51.929  1361  1372 D BluetoothHeadset: Proxy object connected
,09-01 10:59:51.929  1361  1361 D HeadsetProfile: Bluetooth service connected
09-01 10:59:51.929   873   873 D BluetoothHeadset: Proxy object connected
09-01 10:59:51.930   873   873 D BluetoothHeadset: Proxy object connected
09-01 10:59:51.931  1361  3842 D BluetoothHeadset: Proxy object connected
09-01 10:59:51.934  3834  3848 D BluetoothHeadset: Proxy object connected
09-01 10:59:51.934  3834  3834 D HeadsetProfile: Bluetooth service connected
09-01 10:59:51.934   873   873 D BluetoothHeadset: Proxy object connected
,09-01 10:59:51.935  2008  2127 D BluetoothHeadset: Proxy object connected
09-01 10:59:51.936  2008  2031 D BluetoothHeadset: Proxy object connected
,09-01 10:59:51.948  1361  1361 D HeadsetProfile: Bluetooth service connected
,09-01 10:59:52.030  3766  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:52.030  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:52.030  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:52.030  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-01 10:59:52.030  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:52.030  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:52.030  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:52.030  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:52.036  3766  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:52.036  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 10:59:52.037  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e5c452 added. We now have 8 listener(s)
09-01 10:59:52.037  3766  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:52.038   873  2051 D WifiService: setWifiEnabled: false pid=3766, uid=10000
,09-01 10:59:52.038   873  2051 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 10:59:52.047  3766  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:52.048   873  2015 D WifiService: setWifiEnabled: true pid=3766, uid=10000
09-01 10:59:52.048   873  2015 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-01 10:59:52.058   873  1316 D WifiConfigStore: Loading config and enabling all networks 
,09-01 10:59:52.090  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:52.090  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:52.090  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:52.090  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:52.090  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:52.090  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-01 10:59:52.090  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-01 10:59:52.090  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-01 10:59:52.099  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-01 10:59:52.102   873  1316 D WifiConfigStore: loaded 0 passpoint configs
,09-01 10:59:52.103   873  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-01 10:59:52.104   873  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-01 10:59:52.105   873  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-01 10:59:52.105   873  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-01 10:59:52.105   873  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-01 10:59:52.105   873  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-01 10:59:52.115   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-01 10:59:52.115   873  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.05 rxSuccessRate=0.06 delta 1000 -> 1000
,09-01 10:59:52.116   873  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-01 10:59:52.117   371   871 D CommandListener: Setting iface cfg
,09-01 10:59:52.124   873  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-01 10:59:52.125   873  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-01 10:59:52.126   873  1316 E native  : do suspend true
,09-01 10:59:52.132   873  1315 D WifiNative-HAL: p2pGetDeviceAddress
,09-01 10:59:52.135   873  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-01 10:59:52.135   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-01 10:59:52.135   873  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-01 10:59:52.141   873  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-01 10:59:52.181   873  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-01 10:59:52.183  1467  1467 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-01 10:59:52.614  1467  1467 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-01 10:59:52.656  1467  1467 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-01 10:59:52.657  1467  1467 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-01 10:59:52.661   873  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-01 10:59:52.679   873  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-01 10:59:52.681   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-01 10:59:52.681   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 10:59:52.715   873  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-01 10:59:52.740   371   871 D CommandListener: Setting iface cfg
,09-01 10:59:52.741   873  1316 D WifiStateMachine: Start Dhcp Watchdog 3
,09-01 10:59:52.751   873  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-01 10:59:52.772   873  4181 D DhcpClient: Receive thread started
,09-01 10:59:52.857   873  1316 E native  : do suspend false
,09-01 10:59:52.878   873  1939 D DhcpClient: Broadcasting DHCPDISCOVER
,09-01 10:59:52.899   873  4181 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-01 10:59:52.901   873  1939 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-01 10:59:52.904   873  1939 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-01 10:59:52.920   873  4181 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-01 10:59:52.922   873  1939 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-01 10:59:52.926   371   871 D CommandListener: Setting iface cfg
,09-01 10:59:52.939   873  1939 D DhcpClient: Scheduling renewal in 86399s
,09-01 10:59:52.942   873  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-01 10:59:52.945   873  1316 E native  : do suspend true
,09-01 10:59:52.963   873  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-01 10:59:52.964   873  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,09-01 10:59:52.965   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-01 10:59:52.966   873  1318 D ConnectivityService: Adding iface wlan0 to network 102
,09-01 10:59:52.968   873  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-01 10:59:53.021   873  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-01 10:59:53.021   873  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-01 10:59:53.025   873  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-01 10:59:53.031   873  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
09-01 10:59:53.034   873  1318 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-01 10:59:53.044   873  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-01 10:59:53.049   873  1318 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-01 10:59:53.049   873  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-01 10:59:53.049   873  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-01 10:59:53.049   873  1318 D ConnectivityService:    accepting network in place of null
,09-01 10:59:53.049   873  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-01 10:59:53.050   873  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-01 10:59:53.051   873  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-01 10:59:53.065  3766  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:53.065  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:53.065  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:53.065  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:53.065  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:53.065  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:53.065  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:53.065  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:53.069  3766  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 10:59:53.080  3766  3814 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-01 10:59:53.082   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-01 10:59:53.082  3766  3814 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-01 10:59:53.088  3766  3814 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@7d7b465 Bundle[{}]
,09-01 10:59:53.091  3766  3814 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-01 10:59:53.091  3766  3814 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-01 10:59:53.092  3766  3814 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-01 10:59:53.092  3766  3814 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-01 10:59:53.093  3766  3814 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-01 10:59:53.093  3766  3814 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-01 10:59:53.098  3766  3814 I System.out: Running OutgoingSocketThread
,09-01 10:59:53.101  3766  4189 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 411)
,09-01 10:59:53.103  3766  4189 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40964
,09-01 10:59:53.103  3766  4189 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-01 10:59:53.115   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-01 10:59:53.121   873  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-01 10:59:53.124   873  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:53.132   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-01 10:59:53.130   873  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-01 10:59:53.144  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-01 10:59:53.144  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:53.144  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:53.144  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:53.144  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:53.144  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:53.144  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:53.144  3766  3766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:53.150  3766  3766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:53.151  1712  1712 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-01 10:59:53.158  1712  1712 D SystemUpdateService: onCreate
,09-01 10:59:53.162  1712  1712 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-01 10:59:53.177  1712  4192 I SystemUpdateService: active receiver: enabled
,09-01 10:59:53.184  1712  4192 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-01 10:59:53.187  1712  1712 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
09-01 10:59:53.188  1712  2475 I iu.UploadsManager: num queued entries: 0
,09-01 10:59:53.188  1712  2475 I iu.UploadsManager: num updated entries: 0
,09-01 10:59:53.190  1712  4192 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-01 10:59:53.190  1712  4192 I SystemUpdateService: now status is 0 (complete)
,09-01 10:59:53.191  1712  4192 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-01 10:59:53.191  1712  4192 I SystemUpdateService: file has been verified
09-01 10:59:53.191  1712  4192 I SystemUpdateService: OTA package size = 12249756
,09-01 10:59:53.197  1712  2475 I iu.SyncManager: NEXT; no task
,09-01 10:59:53.206  1712  1712 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-01 10:59:53.207  1712  4192 I SystemUpdateService: showing system update notification
,09-01 10:59:53.210  1712  1712 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-01 10:59:53.213  3929  3929 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-01 10:59:53.226  1712  4195 I MDM     : [181] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-01 10:59:53.226  1712  4195 W BaseAppContext: Using Auth Proxy for data requests.
09-01 10:59:53.226  3929  3929 D SprintDMHelper: simOperator: 
,09-01 10:59:53.226  3929  3929 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-01 10:59:53.233  1712  4195 V GoogleAuthProtoRequest: [181] a.<init>: mAccountName set to: thalitester@gmail.com
,09-01 10:59:53.250  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 10:59:53.261  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 10:59:53.298  1712  1712 D SystemUpdateService: onDestroy
,09-01 10:59:53.310  1503  1975 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-01 10:59:53.311  1503  1975 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-01 10:59:53.311  1503  1975 I GLSUser : [GLSUser] Extracting token using key: Auth
09-01 10:59:53.311  1503  1975 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 10:59:53.323  1712  4195 E MDM     : [181] SitrepService.a: Error sending sitrep.
,09-01 10:59:53.765   873  4180 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154097, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-01 10:59:53.935   873  4179 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=89.25.215.85,2a00:1450:400d:803::200e
,09-01 10:59:53.941  2225  4197 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-01 10:59:53.952   873  4179 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 01 Sep 2016 08:59:53 GMT], X-Android-Received-Millis=[1472720393951], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1472720393945]}
,09-01 10:59:53.957   873  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-01 10:59:53.958   873  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,09-01 10:59:53.960   873  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-01 10:59:53.962   873  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-01 10:59:54.101  3766  3814 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 412)
,09-01 10:59:54.101  3766  3814 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 412)
,09-01 10:59:54.111  3766  3814 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 417)
,09-01 10:59:54.113  3766  3814 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-01 10:59:54.114  3766  3814 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 418)
,09-01 10:59:54.119  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-01 10:59:54.119  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a11c323 added. We now have 2 listener(s)
,09-01 10:59:54.121  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-01 10:59:54.121  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:54.121  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:54.122  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 10:59:54.122  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@316f020 added. We now have 9 listener(s)
09-01 10:59:54.121   873  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
09-01 10:59:54.122  3766  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:54.123  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 10:59:54.128  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:54.135  3766  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:54.135  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:54.135  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:54.135  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:54.135  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:54.135  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:54.135  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:54.135  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:54.138  3766  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 10:59:54.138  3766  3814 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 10:59:54.139  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-01 10:59:54.139  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f7d39e added. We now have 3 listener(s)
,09-01 10:59:54.141  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 10:59:54.141  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 10:59:54.141  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:54.141  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:54.141  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e336e7f added. We now have 10 listener(s)
,09-01 10:59:54.141  3766  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:54.141  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:54.141  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:54.141  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 10:59:54.142  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:54.142  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:54.142  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 10:59:54.142  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:54.142  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a11c323 removed from the list
09-01 10:59:54.142  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:54.142  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@316f020 removed from the list
09-01 10:59:54.147  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:54.148  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:54.148  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:54.148  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:54.148  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:54.153  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 10:59:54.154  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:54.154  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 10:59:54.154  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@316f020 not in the list
09-01 10:59:54.154  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:54.154  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:54.159  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:54.159  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:54.159  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:54.159  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:54.159  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e336e7f removed from the list
,09-01 10:59:54.159  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:54.159  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:54.159  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:54.159  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:54.159  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8f7d39e removed from the list
,09-01 10:59:54.160  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 10:59:54.160  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ccaee4c added. We now have 2 listener(s)
09-01 10:59:54.162  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 10:59:54.162  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:54.162  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 10:59:54.162  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:54.163  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cace95 added. We now have 9 listener(s)
,09-01 10:59:54.163  3766  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:54.163  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 10:59:54.165  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:54.171  3766  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:54.171  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:54.171  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:54.171  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:54.171  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:54.171  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:54.171  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:54.171  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:54.172  3766  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:54.173  3766  3814 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 10:59:54.173  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 10:59:54.173  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49a739b added. We now have 3 listener(s)
,09-01 10:59:54.175  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:54.175  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 10:59:54.175  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 10:59:54.175  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:54.175  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:54.176  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9dea338 added. We now have 10 listener(s)
09-01 10:59:54.176  3766  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:54.176  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:54.176  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 10:59:54.176  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 10:59:54.176  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:54.176  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-01 10:59:54.177  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:54.179  3766  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-01 10:59:54.179  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 10:59:54.182  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 10:59:54.183  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-01 10:59:54.183  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 10:59:54.186  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-01 10:59:54.186  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 10:59:54.186  3766  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 10:59:54.187  3766  3814 D BluetoothAdapter: STATE_ON
,09-01 10:59:54.189  4122  4163 D BtGatt.GattService: registerClient() - UUID=8280be39-0db6-428a-bb30-28cadded3106
,09-01 10:59:54.190  4122  4138 D BtGatt.GattService: onClientRegistered() - UUID=8280be39-0db6-428a-bb30-28cadded3106, clientIf=5
,09-01 10:59:54.191  3766  3778 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-01 10:59:54.192  4122  4132 D BtGatt.GattService: start scan with filters
,09-01 10:59:54.195  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-01 10:59:54.195  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-01 10:59:54.195  4122  4141 D BtGatt.ScanManager: handling starting scan
09-01 10:59:54.195  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 10:59:54.195  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 10:59:54.197  4122  4141 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@ae956a9
,09-01 10:59:54.200  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:54.200  4122  4138 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1,
,09-01 10:59:54.200  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 10:59:54.201  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:54.201  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
09-01 10:59:54.201  4122  4141 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-01 10:59:54.202  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 10:59:54.206  3766  3814 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-01 10:59:54.206  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:54.206  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-01 10:59:54.206  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:54.206  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 10:59:54.206  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-01 10:59:54.206  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-01 10:59:54.206  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-01 10:59:54.206  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-01 10:59:54.207  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 10:59:54.207  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-01 10:59:54.208  4122  4138 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-01 10:59:54.208  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:54.208  3766  3814 D BluetoothAdapter: STATE_ON
09-01 10:59:54.208  4122  4141 D BtGatt.ScanManager: Starting BLE batch scan
09-01 10:59:54.208  4122  4141 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-01 10:59:54.209  4122  4162 D BtGatt.GattService: stopScan() - queue size =1
,09-01 10:59:54.210  4122  4163 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-01 10:59:54.211  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 10:59:54.211  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 10:59:54.211  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 10:59:54.211  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 10:59:54.211  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 10:59:54.212  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 10:59:54.212  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 10:59:54.212  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-01 10:59:54.212  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-01 10:59:54.213  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 10:59:54.214  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 10:59:54.214  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:54.215  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 10:59:54.217  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 10:59:54.217  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:54.217  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:54.218  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 10:59:54.218  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:54.218  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:54.218  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:54.218  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ccaee4c removed from the list
09-01 10:59:54.218  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:54.218  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cace95 removed from the list
,09-01 10:59:54.218  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
09-01 10:59:54.218  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:54.219  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:54.219  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:54.220  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 10:59:54.220  4122  4138 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-01 10:59:54.220  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:54.220  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:54.220  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:54.221  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cace95 not in the list
,09-01 10:59:54.221  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:54.221  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:54.222  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:54.222  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 10:59:54.222  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:54.222  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9dea338 removed from the list
09-01 10:59:54.222  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:54.222  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:54.222  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:54.222  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:54.222  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49a739b removed from the list
09-01 10:59:54.223  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-01 10:59:54.223  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@476bae4 added. We now have 2 listener(s)
,09-01 10:59:54.225  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-01 10:59:54.225  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:54.225  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:54.225  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:54.225  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d73b4d added. We now have 9 listener(s)
09-01 10:59:54.226  3766  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:54.226  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-01 10:59:54.227  4122  4138 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-01 10:59:54.227  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 10:59:54.231  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:54.235  4122  4138 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-01 10:59:54.235  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:54.235  4122  4141 D BtGatt.ScanManager: stopping BLe Batch
,09-01 10:59:54.236  3766  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:54.236  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:54.236  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:54.236  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:54.236  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:54.236  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:54.236  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:54.236  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:54.240  3766  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 10:59:54.240  3766  3814 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 10:59:54.241  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
,09-01 10:59:54.241  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@189bb13 added. We now have 3 listener(s)
,09-01 10:59:54.242  4122  4138 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-01 10:59:54.242  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 10:59:54.243  4122  4141 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-01 10:59:54.243  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:54.243  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-01 10:59:54.243  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 10:59:54.244  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
,09-01 10:59:54.244  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-01 10:59:54.244  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@256a150 added. We now have 10 listener(s)
,09-01 10:59:54.244  3766  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:54.245  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-01 10:59:54.245  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:54.246  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:54.246  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-01 10:59:54.246  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 10:59:54.246  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:54.246  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-01 10:59:54.249  4122  4138 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0,
09-01 10:59:54.249  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:54.250  3766  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-01 10:59:54.250  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-01 10:59:54.254  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 10:59:54.254  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-01 10:59:54.254  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-01 10:59:54.257  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-01 10:59:54.257  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 10:59:54.257  3766  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-01 10:59:54.258  3766  3814 D BluetoothAdapter: STATE_ON
,09-01 10:59:54.260  4122  4163 D BtGatt.GattService: registerClient() - UUID=7f961494-9465-4198-b2fe-de0a1fb47139
09-01 10:59:54.260  4122  4138 D BtGatt.GattService: onClientRegistered() - UUID=7f961494-9465-4198-b2fe-de0a1fb47139, clientIf=5
,09-01 10:59:54.260  3766  3778 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-01 10:59:54.261  4122  4132 D BtGatt.GattService: start scan with filters,
,09-01 10:59:54.263  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-01 10:59:54.263  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-01 10:59:54.263  4122  4141 D BtGatt.ScanManager: handling starting scan
09-01 10:59:54.263  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-01 10:59:54.263  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 10:59:54.268  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:54.268  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:54.268  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 10:59:54.270  4122  4138 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-01 10:59:54.270  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:54.270  4122  4141 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-01 10:59:54.270  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 10:59:54.274  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-01 10:59:54.274  3766  3814 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-01 10:59:54.274  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 10:59:54.274  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:54.274  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 10:59:54.275  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-01 10:59:54.275  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:54.275  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-01 10:59:54.275  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-01 10:59:54.275  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@476bae4 removed from the list
09-01 10:59:54.275  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,09-01 10:59:54.275  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d73b4d removed from the list
09-01 10:59:54.275  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 10:59:54.275  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 10:59:54.276  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:54.276  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-01 10:59:54.276  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:54.276  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:54.277  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 10:59:54.277  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 10:59:54.277  4122  4138 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-01 10:59:54.277  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 10:59:54.277  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d73b4d not in the list
,09-01 10:59:54.277  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-01 10:59:54.277  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 10:59:54.277  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 10:59:54.277  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
09-01 10:59:54.277  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-01 10:59:54.277  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-01 10:59:54.277  4122  4141 D BtGatt.ScanManager: Starting BLE batch scan
,09-01 10:59:54.278  4122  4141 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-01 10:59:54.278  3766  3814 D BluetoothAdapter: STATE_ON,
09-01 10:59:54.279  4122  4133 D BtGatt.GattService: stopScan() - queue size =1
,09-01 10:59:54.279  4122  4162 D BtGatt.GattService: unregisterClient() - clientIf=5
09-01 10:59:54.279  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-01 10:59:54.280  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 10:59:54.280  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-01 10:59:54.280  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-01 10:59:54.280  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-01 10:59:54.281  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 10:59:54.281  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-01 10:59:54.281  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-01 10:59:54.281  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 10:59:54.282  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:54.283  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:54.283  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 10:59:54.283  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 10:59:54.283  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-01 10:59:54.283  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-01 10:59:54.283  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:54.284  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@256a150 removed from the list
,09-01 10:59:54.284  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:54.284  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:54.284  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:54.284  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-01 10:59:54.284  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@189bb13 removed from the list
09-01 10:59:54.285  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-01 10:59:54.285  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c827c added. We now have 2 listener(s)
09-01 10:59:54.287  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-01 10:59:54.287  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:54.287  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-01 10:59:54.287  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:54.287  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cfd8705 added. We now have 9 listener(s)
,09-01 10:59:54.287  3766  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:54.288  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 10:59:54.290  4122  4138 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-01 10:59:54.290  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 10:59:54.291  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:54.296  3766  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:54.296  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:54.296  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:54.296  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:54.296  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:54.296  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:54.296  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:54.296  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:54.298  3766  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:54.298  3766  3814 D io.jxcore.node.ConnectivityMonitor: start: OK
09-01 10:59:54.298  4122  4138 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-01 10:59:54.299  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:54.301  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:54.301  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-01 10:59:54.302  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63b798b added. We now have 3 listener(s)
,09-01 10:59:54.303  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:54.307  4122  4138 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-01 10:59:54.307  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 10:59:54.307  4122  4141 D BtGatt.ScanManager: stopping BLe Batch
09-01 10:59:54.307  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 10:59:54.308  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:54.308  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:54.309  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:54.309  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dd4a68 added. We now have 10 listener(s)
,09-01 10:59:54.309  3766  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-01 10:59:54.309  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:54.309  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-01 10:59:54.310  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-01 10:59:54.310  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-01 10:59:54.310  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-01 10:59:54.313  4122  4138 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-01 10:59:54.314  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:54.314  4122  4141 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-01 10:59:54.314  3766  3814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-01 10:59:54.314  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-01 10:59:54.318  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-01 10:59:54.318  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-01 10:59:54.318  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-01 10:59:54.319  4122  4138 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-01 10:59:54.319  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 10:59:54.321  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-01 10:59:54.321  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-01 10:59:54.321  3766  3814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-01 10:59:54.322  3766  3814 D BluetoothAdapter: STATE_ON
,09-01 10:59:54.324  4122  4162 D BtGatt.GattService: registerClient() - UUID=0b8be512-682a-433b-9b22-388bc93235bb
,09-01 10:59:54.324  4122  4138 D BtGatt.GattService: onClientRegistered() - UUID=0b8be512-682a-433b-9b22-388bc93235bb, clientIf=5
09-01 10:59:54.324  3766  3778 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-01 10:59:54.324  4122  4163 D BtGatt.GattService: start scan with filters
,09-01 10:59:54.326  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-01 10:59:54.326  4122  4141 D BtGatt.ScanManager: handling starting scan
09-01 10:59:54.326  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-01 10:59:54.326  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-01 10:59:54.326  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-01 10:59:54.329  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-01 10:59:54.329  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-01 10:59:54.329  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-01 10:59:54.330  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-01 10:59:54.332  4122  4138 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-01 10:59:54.332  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:54.332  4122  4141 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-01 10:59:54.334  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-01 10:59:54.334  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:54.334  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-01 10:59:54.334  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:54.335  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:54.335  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-01 10:59:54.335  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-01 10:59:54.335  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c827c removed from the list
09-01 10:59:54.335  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 10:59:54.335  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cfd8705 removed from the list
09-01 10:59:54.335  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 10:59:54.335  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:54.335  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:54.335  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-01 10:59:54.336  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:54.336  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-01 10:59:54.336  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:54.336  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:54.336  4122  4138 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-01 10:59:54.336  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:54.336  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 10:59:54.336  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cfd8705 not in the list
09-01 10:59:54.337  4122  4141 D BtGatt.ScanManager: Starting BLE batch scan
09-01 10:59:54.337  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-01 10:59:54.337  4122  4141 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-01 10:59:54.337  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-01 10:59:54.337  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-01 10:59:54.337  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-01 10:59:54.337  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-01 10:59:54.337  3766  3814 D BluetoothAdapter: STATE_ON
09-01 10:59:54.338  4122  4133 D BtGatt.GattService: stopScan() - queue size =1
09-01 10:59:54.338  4122  4162 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-01 10:59:54.338  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-01 10:59:54.339  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-01 10:59:54.339  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-01 10:59:54.339  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-01 10:59:54.339  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-01 10:59:54.340  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-01 10:59:54.340  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-01 10:59:54.340  3766  3814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-01 10:59:54.340  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-01 10:59:54.340  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:54.341  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:54.341  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:54.341  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:54.341  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-01 10:59:54.341  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2dd4a68 removed from the list
09-01 10:59:54.341  3766  3766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-01 10:59:54.341  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:54.341  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:54.341  3766  3766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-01 10:59:54.341  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:54.341  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:54.341  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@63b798b removed from the list
09-01 10:59:54.342  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-01 10:59:54.342  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d70a514 added. We now have 2 listener(s)
09-01 10:59:54.344  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 10:59:54.344  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-01 10:59:54.344  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:54.344  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:54.344  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cba91bd added. We now have 9 listener(s)
09-01 10:59:54.344  3766  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:54.345  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-01 10:59:54.346  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-01 10:59:54.348  4122  4138 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-01 10:59:54.348  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 10:59:54.350  3766  3814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-01 10:59:54.350  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-01 10:59:54.350  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-01 10:59:54.350  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-01 10:59:54.350  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-01 10:59:54.350  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-01 10:59:54.350  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-01 10:59:54.350  3766  3814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-01 10:59:54.351  3766  3814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-01 10:59:54.352  3766  3814 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-01 10:59:54.353  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-01 10:59:54.354  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-01 10:59:54.354  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba78f03 added. We now have 3 listener(s)
,09-01 10:59:54.354  4122  4138 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-01 10:59:54.354  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:54.355  3766  3766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-01 10:59:54.355  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-01 10:59:54.356  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-01 10:59:54.356  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-01 10:59:54.356  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-01 10:59:54.356  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33cfe80 added. We now have 10 listener(s)
,09-01 10:59:54.356  3766  3814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-01 10:59:54.356  3766  3814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-01 10:59:54.356  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:54.356  3766  3814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-01 10:59:54.356  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:54.356  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-01 10:59:54.356  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-01 10:59:54.356  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:54.357  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d70a514 removed from the list
09-01 10:59:54.357  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:54.357  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cba91bd removed from the list
09-01 10:59:54.357  3766  3814 D io.jxcore.node.ConnectivityMonitor: stop
,09-01 10:59:54.357  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:54.358  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:54.358  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:54.359  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:54.359  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:54.359  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-01 10:59:54.359  3766  3814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cba91bd not in the list
,09-01 10:59:54.359  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:54.359  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-01 10:59:54.360  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-01 10:59:54.360  4122  4138 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-01 10:59:54.360  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-01 10:59:54.360  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:54.360  3766  3814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-01 10:59:54.360  3766  3814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33cfe80 removed from the list
09-01 10:59:54.360  3766  3814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-01 10:59:54.360  4122  4141 D BtGatt.ScanManager: stopping BLe Batch
09-01 10:59:54.361  3766  3814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-01 10:59:54.361  3766  3814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-01 10:59:54.361  3766  3814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-01 10:59:54.361  3766  3814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ba78f03 removed from the list
09-01 10:59:54.361  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-01 10:59:54.361  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-01 10:59:54.361  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-01 10:59:54.362  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-01 10:59:54.362  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-01 10:59:54.362  3766  3814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-01 10:59:54.365  4122  4138 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-01 10:59:54.366  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-01 10:59:54.366  4122  4141 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-01 10:59:54.369  3766  4204 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: My test thread name)
,09-01 10:59:54.369  3766  4204 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 425, thread name: My test thread name)
09-01 10:59:54.369  3766  4204 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 425, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-01 10:59:54.371  3766  4205 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: My test thread name)
,09-01 10:59:54.371  4122  4138 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-01 10:59:54.371  4122  4138 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-01 10:59:54.372  3766  4205 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 427, thread name: My test thread name)
,09-01 10:59:54.372  3766  4205 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 427, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-01 10:59:54.374  3766  3814 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-01 10:59:54.374  3766  3814 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
,09-01 10:59:54.374  3766  3814 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-01 10:59:54.374  3766  3814 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-01 10:59:54.374  3766  3814 D com.test.thalitest.ThaliTestRunner: Total duration: 22845 ms
09-01 10:59:54.375  3766  3814 I jxcore-log: *Native tests were executed*
09-01 10:59:54.375  3766  3814 I jxcore-log: 
,09-01 10:59:54.376  3766  3814 I jxcore-log: Total number of executed tests:  80
09-01 10:59:54.376  3766  3814 I jxcore-log: 
09-01 10:59:54.376  3766  3814 I jxcore-log: Number of passed tests:  80
09-01 10:59:54.376  3766  3814 I jxcore-log: 
09-01 10:59:54.376  3766  3814 I jxcore-log: Number of failed tests:  0,
09-01 10:59:54.376  3766  3814 I jxcore-log: 
09-01 10:59:54.376  3766  3814 I jxcore-log: Number of ignored tests:  0
09-01 10:59:54.376  3766  3814 I jxcore-log: 
09-01 10:59:54.377  3766  3814 I jxcore-log: Total duration:  22845
09-01 10:59:54.377  3766  3814 I jxcore-log: 
09-01 10:59:54.377  3766  3814 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-01 10:59:54.377  3766  3814 I jxcore-log: 
,09-01 10:59:54.380  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:54.380  3766  3814 I jxcore-log: 
09-01 10:59:54.382  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:54.382  3766  3814 I jxcore-log: 
09-01 10:59:54.384  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:54.384  3766  3814 I jxcore-log: 
09-01 10:59:54.385  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:54.385  3766  3814 I jxcore-log: 
09-01 10:59:54.386  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:54.386  3766  3814 I jxcore-log: 
09-01 10:59:54.386  3766  3766 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-01 10:59:54.387  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 10:59:54.387  3766  3814 I jxcore-log: 
09-01 10:59:54.389  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 10:59:54.389  3766  3814 I jxcore-log: 
09-01 10:59:54.391  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 10:59:54.391  3766  3814 I jxcore-log: 
09-01 10:59:54.391  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 10:59:54.391  3766  3814 I jxcore-log: 
09-01 10:59:54.392  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:54.392  3766  3814 I jxcore-log: 
09-01 10:59:54.393  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 10:59:54.393  3766  3814 I jxcore-log: 
,09-01 10:59:54.394  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 10:59:54.394  3766  3814 I jxcore-log: 
,09-01 10:59:54.395  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-01 10:59:54.395  3766  3814 I jxcore-log: 
09-01 10:59:54.395  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:54.395  3766  3814 I jxcore-log: 
09-01 10:59:54.396  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:54.396  3766  3814 I jxcore-log: 
09-01 10:59:54.396  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 10:59:54.396  3766  3814 I jxcore-log: 
,09-01 10:59:54.397  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 10:59:54.397  3766  3814 I jxcore-log: 
,09-01 10:59:54.398  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 10:59:54.398  3766  3814 I jxcore-log: 
09-01 10:59:54.398  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 10:59:54.398  3766  3814 I jxcore-log: 
09-01 10:59:54.399  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 10:59:54.399  3766  3814 I jxcore-log: 
09-01 10:59:54.399  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-01 10:59:54.399  3766  3814 I jxcore-log: 
,09-01 10:59:54.400  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 10:59:54.400  3766  3814 I jxcore-log: 
,09-01 10:59:54.401  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-01 10:59:54.401  3766  3814 I jxcore-log: 
09-01 10:59:54.402  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-01 10:59:54.402  3766  3814 I jxcore-log: 
09-01 10:59:54.402  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:54.402  3766  3814 I jxcore-log: 
09-01 10:59:54.403  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:54.403  3766  3814 I jxcore-log: 
,09-01 10:59:54.404  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:54.404  3766  3814 I jxcore-log: 
,09-01 10:59:54.404  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:54.404  3766  3814 I jxcore-log: 
09-01 10:59:54.405  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:54.405  3766  3814 I jxcore-log: 
09-01 10:59:54.406  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:54.406  3766  3814 I jxcore-log: 
09-01 10:59:54.406  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-01 10:59:54.406  3766  3814 I jxcore-log: 
,09-01 10:59:54.716  3766  3766 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 10:59:54.717  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 10:59:54.717  3766  3814 I jxcore-log: 
,09-01 10:59:54.783  3766  3766 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 10:59:54.785  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 10:59:54.785  3766  3814 I jxcore-log: 
,09-01 10:59:54.826  1503  1503 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-01 10:59:54.841  3766  3766 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-01 10:59:54.844  3766  3814 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-01 10:59:54.844  3766  3814 I jxcore-log: 
,09-01 10:59:54.887  1503  2983 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-01 10:59:54.887  1503  2983 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-01 10:59:54.887  1503  2983 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-01 10:59:54.888  1503  2983 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-01 10:59:54.925  3502  3502 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
,09-01 10:59:54.926  3502  3502 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-01 10:59:54.928  3502  3502 D Finsky  : [1] ContentSyncService$5.onFinished: Giving up after 6 failures.
,09-01 10:59:55.112  4206  4206 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-01 10:59:55.117  4206  4206 D AndroidRuntime: CheckJNI is OFF
,09-01 10:59:55.159  4206  4206 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-01 10:59:55.208  4206  4206 I Radio-JNI: register_android_hardware_Radio DONE
,09-01 10:59:55.231  4206  4206 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-01 10:59:55.244   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-01 10:59:55.245   873   886 I ActivityManager: Killing 3766:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-01 10:59:55.357   873   896 W PackageSettings: Skipping PackageSetting{8a55eb2 com.example.hello/10273} due to missing metadata
,09-01 10:59:55.392   873   896 I art     : Starting a blocking GC Explicit
,09-01 10:59:55.417   873  1401 I WindowState: WIN DEATH: Window{ef77b32 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-01 10:59:55.416   873  1304 W InputDispatcher: channel 'ef77b32 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,09-01 10:59:55.417   873   883 D GraphicsStats: Buffer count: 2
,09-01 10:59:55.418   873  1304 E InputDispatcher: channel 'ef77b32 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,09-01 10:59:55.418   873  1317 D WifiService: Client connection lost with reason: 4
,09-01 10:59:55.419   873  1401 W InputDispatcher: Attempted to unregister already unregistered input channel 'ef77b32 com.test.thalitest/com.test.thalitest.MainActivity (server)'
,09-01 10:59:55.425   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-01 10:59:55.426   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-01 10:59:55.427   873   886 E ActivityManager: Failure starting process com.test.thalitest
09-01 10:59:55.427   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-01 10:59:55.427   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-01 10:59:55.427   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-01 10:59:55.427   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-01 10:59:55.427   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-01 10:59:55.427   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-01 10:59:55.427   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-01 10:59:55.427   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-01 10:59:55.427   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-01 10:59:55.427   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-01 10:59:55.427   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-01 10:59:55.427   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-01 10:59:55.427   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-01 10:59:55.427   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-01 10:59:55.427   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-01 10:59:55.427   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:55.427   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-01 10:59:55.427   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 10:59:55.427   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,09-01 10:59:55.427   873   886 I ActivityManager:   Force finishing activity ActivityRecord{28bab2b u0 com.test.thalitest/.MainActivity t2}
,09-01 10:59:55.442   873  1960 W ActivityManager: Spurious death for ProcessRecord{d9c996b 0:com.test.thalitest/u0a0}, curProc for 3766: null
,09-01 10:59:55.462   873   896 I art     : Explicit concurrent mark sweep GC freed 16079(1153KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 759us total 69.342ms
,09-01 10:59:55.494   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-01 10:59:55.496  4206  4206 I art     : System.exit called, status: 0
,09-01 10:59:55.496  4206  4206 I AndroidRuntime: VM exiting with result code 0.
,09-01 10:59:55.502   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-01 10:59:55.529   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-01 10:59:55.539  4122  4122 D BluetoothMapAppObserver: onReceive
,09-01 10:59:55.539  4122  4122 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-01 10:59:55.539   873  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-01 10:59:55.541  1860  2268 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-01 10:59:55.543  3602  3602 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-01 10:59:55.544  1901  1901 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-01 10:59:55.567   873  2051 I ActivityManager: Start proc 4222:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-01 10:59:55.569  2008  2008 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-01 10:59:55.572  1901  4220 I Keyboard.Facilitator.DecoderInitializer: run()
,09-01 10:59:55.588  1901  4220 I Decoder : createOrResetDecoder
,09-01 10:59:55.619   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-01 10:59:55.629  4222  4222 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-01 10:59:55.637   873  2022 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3766 uid 10000
,09-01 10:59:55.642  1901  1901 I Keyboard.Facilitator: onFinishInput()
,09-01 10:59:55.645  1503  1503 I ConfigService: onCreate
,09-01 10:59:55.665  2026  2151 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-01 10:59:55.665   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-01 10:59:55.666   873   885 E PackageManager: Failed to write settings, restoring backup
09-01 10:59:55.666   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-01 10:59:55.666   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-01 10:59:55.666   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-01 10:59:55.666   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-01 10:59:55.666   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-01 10:59:55.666   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:55.666   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-01 10:59:55.666   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-01 10:59:55.669  1503  4234 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-01 10:59:55.669  1503  4234 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 10:59:55.669  1503  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 10:59:55.669  1503  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 10:59:55.669  1503  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 10:59:55.669  1503  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 10:59:55.669  1503  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 10:59:55.669  1503  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 10:59:55.669  1503  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 10:59:55.669  1503  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 10:59:55.669  1503  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 10:59:55.669  1503  4234 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 10:59:55.669  1503  4234 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 10:59:55.669  1503  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 10:59:55.669  1503  4234 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-01 10:59:55.669  1503  4234 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-01 10:59:55.669  1503  4234 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-01 10:59:55.669  1503  4234 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-01 10:59:55.669  1503  4234 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-01 10:59:55.669  1503  4234 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 10:59:55.669  1503  4234 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 10:59:55.669  1503  4234 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 10:59:55.669  1503  4234 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 10:59:55.669  1503  4234 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 10:59:55.669  1503  4234 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 10:59:55.669  1503  4234 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 10:59:55.669  1503  4234 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 10:59:55.669  1503  4234 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 10:59:55.669  1503  4234 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 10:59:55.669  1503  4234 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 10:59:55.669  1503  4234 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 10:59:55.669  1503  4234 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 10:59:55.669  1503  4234 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-01 10:59:55.669  1503  4234 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-01 10:59:55.669  1503  4234 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-01 10:59:55.669  1503  4234 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
09-01 10:59:55.670   873   886 E DropBoxManagerService: Can't write: system_server_wtf
09-01 10:59:55.670   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-01 10:59:55.670   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 10:59:55.670   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 10:59:55.670   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 10:59:55.670   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 10:59:55.670   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 10:59:55.670   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 10:59:55.670   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-01 10:59:55.670   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-01 10:59:55.670   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-01 10:59:55.670   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-01 10:59:55.670   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-01 10:59:55.670   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-01 10:59:55.670   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 10:59:55.670   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-01 10:59:55.670   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 10:59:55.670   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 10:59:55.670   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 10:59:55.670   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 10:59:55.670   873   886 E DropBoxManagerService: 	... 13 more
09-01 10:59:55.671  1503  4234 W SQLiteOpenHelper: Opened config.db in read-only mode
09-01 10:59:55.680   873  1392 I ActivityManager: Start proc 4238:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-01 10:59:55.681  2026  2151 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-01 10:59:55.681  2026  2151 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 2026
09-01 10:59:55.681  2026  2151 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 10:59:55.681  2026  2151 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-01 10:59:55.681  2026  2151 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-01 10:59:55.681  2026  2151 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-01 10:59:55.681  2026  2151 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-01 10:59:55.681  2026  2151 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-01 10:59:55.681  2026  2151 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-01 10:59:55.681  2026  2151 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-01 10:59:55.681  2026  2151 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-01 10:59:55.681  2026  2151 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-01 10:59:55.681  2026  2151 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 10:59:55.681  2026  2151 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-01 10:59:55.683   873  1401 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-01 10:59:55.683   873  4244 E DropBoxManagerService: Can't write: system_app_crash
09-01 10:59:55.683   873  4244 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-01 10:59:55.683   873  4244 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 10:59:55.683   873  4244 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 10:59:55.683   873  4244 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 10:59:55.683   873  4244 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 10:59:55.683   873  4244 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 10:59:55.683   873  4244 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 10:59:55.683   873  4244 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 10:59:55.683   873  4244 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 10:59:55.683   873  4244 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 10:59:55.683   873  4244 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 10:59:55.683   873  4244 E DropBoxManagerService: 	... 5 more
09-01 10:59:55.687  2026  2151 I Process : Sending signal. PID: 2026 SIG: 9
09-01 10:59:55.698  1901  4220 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-01 10:59:55.739  4222  4222 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-01 10:59:55.755   873   883 D GraphicsStats: Buffer count: 1
,09-01 10:59:55.755   873  2016 I WindowState: WIN DEATH: Window{5cc45f0 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-01 10:59:55.763   873  1915 I ActivityManager: Start proc 4253:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-01 10:59:55.769   873  1960 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 2026) has died
,09-01 10:59:55.770   873  1960 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-01 10:59:55.772   873  1960 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-01 10:59:55.776  4222  4264 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-01 10:59:55.778  1901  4220 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,09-01 10:59:55.792   873   886 I ActivityManager: Start proc 4266:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-01 10:59:55.798  1901  4220 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
,09-01 10:59:55.798  1901  4220 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,09-01 10:59:55.807  1901  4220 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-01 10:59:55.807  1901  4220 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,09-01 10:59:55.818  1901  4220 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,09-01 10:59:55.818  1901  4220 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-01 10:59:55.820  1901  4220 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,09-01 10:59:55.822  1901  4220 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,09-01 10:59:55.822  1901  4220 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-01 10:59:55.823  4253  4253 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-01 10:59:55.824  1901  4220 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,09-01 10:59:55.824  1901  4220 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,09-01 10:59:55.824  1901  4220 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-01 10:59:55.832  4222  4236 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-01 10:59:55.832  4222  4236 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 10:59:55.832  4222  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 10:59:55.832  4222  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 10:59:55.832  4222  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 10:59:55.832  4222  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 10:59:55.832  4222  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 10:59:55.832  4222  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 10:59:55.832  4222  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 10:59:55.832  4222  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 10:59:55.832  4222  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 10:59:55.832  4222  4236 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 10:59:55.832  4222  4236 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 10:59:55.832  4222  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 10:59:55.832  4222  4236 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-01 10:59:55.832  4222  4236 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-01 10:59:55.832  4222  4236 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-01 10:59:55.832  4222  4236 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-01 10:59:55.832  4222  4236 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-01 10:59:55.832  4222  4236 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:55.832  4222  4236 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-01 10:59:55.832  4222  4236 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-01 10:59:55.833  4222  4236 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-01 10:59:55.839  4266  4266 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 10:59:55.839  4266  4266 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 10:59:55.839  4266  4266 D AndroidRuntime: Shutting down VM
,09-01 10:59:55.846  4266  4266 E AndroidRuntime: FATAL EXCEPTION: main
09-01 10:59:55.846  4266  4266 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4266
09-01 10:59:55.846  4266  4266 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-01 10:59:55.846  4266  4266 E AndroidRuntime: 	... 10 more
09-01 10:59:55.846  1503  1503 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-01 10:59:55.847  1503  1503 D AndroidRuntime: Shutting down VM
09-01 10:59:55.847  1503  1503 E AndroidRuntime: FATAL EXCEPTION: main
09-01 10:59:55.847  1503  1503 E AndroidRuntime: Process: com.google.process.gapps, PID: 1503
09-01 10:59:55.847  1503  1503 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 10:59:55.847  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-01 10:59:55.847  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-01 10:59:55.847  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-01 10:59:55.847  1503  1503 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:55.847  1503  1503 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 10:59:55.847  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 10:59:55.847  1503  1503 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:55.847  1503  1503 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 10:59:55.847  1503  1503 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 10:59:55.847  1503  1503 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 10:59:55.847  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-01 10:59:55.847  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-01 10:59:55.847  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-01 10:59:55.847  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-01 10:59:55.847  1503  1503 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-01 10:59:55.847  1503  1503 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-01 10:59:55.847  1503  1503 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-01 10:59:55.847  1503  1503 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-01 10:59:55.847  1503  1503 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-01 10:59:55.847  1503  1503 E AndroidRuntime: 	... 8 more
09-01 10:59:55.848   873  1392 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL,
,09-01 10:59:55.849  4266  4266 I Process : Sending signal. PID: 4266 SIG: 9
,09-01 10:59:55.852   873  4281 E DropBoxManagerService: Can't write: system_app_crash
09-01 10:59:55.852   873  4281 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-01 10:59:55.852   873  4281 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 10:59:55.852   873  4281 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 10:59:55.852   873  4281 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 10:59:55.852   873  4281 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 10:59:55.852   873  4281 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 10:59:55.852   873  4281 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 10:59:55.852   873  4281 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 10:59:55.852   873  4281 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 10:59:55.852   873  4281 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 10:59:55.852   873  4281 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 10:59:55.852   873  4281 E DropBoxManagerService: 	... 5 more
09-01 10:59:55.854  1503  1503 I Process : Sending signal. PID: 1503 SIG: 9
,09-01 10:59:55.855   873  4280 E DropBoxManagerService: Can't write: system_app_crash
09-01 10:59:55.855   873  4280 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-01 10:59:55.855   873  4280 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 10:59:55.855   873  4280 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 10:59:55.855   873  4280 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 10:59:55.855   873  4280 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 10:59:55.855   873  4280 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 10:59:55.855   873  4280 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 10:59:55.855   873  4280 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 10:59:55.855   873  4280 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 10:59:55.855   873  4280 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 10:59:55.855   873  4280 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 10:59:55.855   873  4280 E DropBoxManagerService: 	... 5 more
,09-01 10:59:55.881  1712  4282 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 352)
,09-01 10:59:55.882  1712  4282 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@e399d23
,09-01 10:59:55.883   873  2015 I ActivityManager: Process com.google.process.gapps (pid 1503) early provider death
,09-01 10:59:55.885   873  1317 D WifiService: Client connection lost with reason: 4
,09-01 10:59:55.888   873  2015 I ActivityManager: Process com.google.process.gapps (pid 1503) has died
,09-01 10:59:55.889   873  2015 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
,09-01 10:59:55.889   873  2015 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 10999ms
,09-01 10:59:55.889   873  2015 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 20999ms
09-01 10:59:55.889   873  2015 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 30999ms
,09-01 10:59:55.891   873  2068 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4266) has died
,09-01 10:59:55.892   873  2068 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-01 10:59:55.895   873  2022 W ActivityManager: Spurious death for ProcessRecord{3490ff7 0:com.google.process.gapps/u0a11}, curProc for 1503: null
,09-01 10:59:55.908   873   886 I ActivityManager: Start proc 4285:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-01 10:59:55.922   873  1915 I ActivityManager: Start proc 4297:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
,09-01 10:59:55.937  1712  1712 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-01 10:59:55.952  4297  4297 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
,09-01 10:59:55.958  4297  4297 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,09-01 10:59:55.960  4285  4285 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 10:59:55.960  4285  4285 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 10:59:55.960  4297  4297 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 10:59:55.960  4297  4297 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-01 10:59:55.960  4297  4297 D AndroidRuntime: Shutting down VM
,09-01 10:59:55.960  4285  4285 D AndroidRuntime: Shutting down VM
,09-01 10:59:55.961  4297  4297 E AndroidRuntime: FATAL EXCEPTION: main
09-01 10:59:55.961  4297  4297 E AndroidRuntime: Process: com.google.process.gapps, PID: 4297
09-01 10:59:55.961  4297  4297 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.content,.ContentProvider.attachInfo(ContentProvider.java:1723)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-01 10:59:55.961  4297  4297 E AndroidRuntime: 	... 10 more
,09-01 10:59:55.964   873  4311 E DropBoxManagerService: Can't write: system_app_crash
09-01 10:59:55.964   873  4311 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-01 10:59:55.964   873  4311 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 10:59:55.964   873  4311 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 10:59:55.964   873  4311 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 10:59:55.964   873  4311 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 10:59:55.964   873  4311 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 10:59:55.964   873  4311 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 10:59:55.964   873  4311 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 10:59:55.964   873  4311 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 10:59:55.964   873  4311 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 10:59:55.964   873  4311 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 10:59:55.964   873  4311 E DropBoxManagerService: 	... 5 more
,09-01 10:59:55.968  1712  1712 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,09-01 10:59:55.968  1712  1712 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-01 10:59:55.968  4297  4297 I Process : Sending signal. PID: 4297 SIG: 9
09-01 10:59:55.970  4285  4285 E AndroidRuntime: FATAL EXCEPTION: main
09-01 10:59:55.970  4285  4285 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4285
09-01 10:59:55.970  4285  4285 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-01 10:59:55.970  4285  4285 E AndroidRun,time: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-01 10:59:55.970  4285  4285 E AndroidRuntime: 	... 10 more
09-01 10:59:55.974   873  4312 E DropBoxManagerService: Can't write: system_app_crash
09-01 10:59:55.974   873  4312 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
09-01 10:59:55.974   873  4312 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-01 10:59:55.974   873  4312 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-01 10:59:55.974   873  4312 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-01 10:59:55.974   873  4312 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-01 10:59:55.974   873  4312 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-01 10:59:55.974   873  4312 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-01 10:59:55.974   873  4312 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-01 10:59:55.974   873  4312 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-01 10:59:55.974   873  4312 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-01 10:59:55.974   873  4312 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-01 10:59:55.974   873  4312 E DropBoxManagerService: 	... 5 more
09-01 10:59:55.975  1712  1712 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-01 10:59:55.975  1712  1712 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-01 10:59:55.977   873  2022 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-01 10:59:55.978  4285  4285 I Process : Sending signal. PID: 4285 SIG: 9
09-01 10:59:55.979  1712  4313 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-01 10:59:55.989   873  1392 I ActivityManager: Process com.google.process.gapps (pid 4297) has died
,09-01 10:59:55.989   873  1392 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{aa921d2 u0 com.google.android.gms/.config.ConfigService}
,09-01 10:59:55.990   873  1392 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{9dea338 u0 com.google.android.gms/.auth.GetToken}
,09-01 10:59:55.991   873  1392 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{9087121 u0 com.google.android.gms/.gcm.GcmService}
09-01 10:59:55.991   873  1392 W ActivityManager: Service crashed 2 times, stopping: ServiceRecord{1937fa7 u0 com.google.android.gms/.clearcut.service.ClearcutLoggerService}
09-01 10:59:55.999  1712  4313 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
09-01 10:59:55.999  1712  4313 E AndroidRuntime: Process: com.google.android.gms, PID: 1712
09-01 10:59:55.999  1712  4313 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-01 10:59:55.999  1712  4313 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-01 10:59:55.999  1712  4313 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-01 10:59:55.999  1712  4313 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-01 10:59:55.999  1712  4313 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-01 10:59:55.999  1712  4313 E AndroidRuntime: ,	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-01 10:59:55.999  1712  4313 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
09-01 10:59:55.999  1712  4313 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
09-01 10:59:55.999  1712  4313 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
09-01 10:59:55.999  1712  4313 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
09-01 10:59:55.999  1712  4313 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-01 10:59:55.999  1712  4313 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-01 10:59:55.999  1712  4313 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
09-01 10:59:55.999  1712  4313 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
09-01 10:59:55.999  1712  4313 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
09-01 10:59:55.999  1712  4313 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
09-01 10:59:55.999  1712  4313 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-01 10:59:55.999  1712  4313 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-01 10:59:55.999  1712  4313 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,09-01 10:59:56.002   873  1392 I ActivityManager: Start proc 4316:com.google.process.gapps/u0a11 for restart com.google.process.gapps
,09-01 10:59:56.004   873  2016 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4285) has died
09-01 10:59:56.005   873  2016 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-01 10:59:56.006   281   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
