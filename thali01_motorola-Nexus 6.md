#### Test 830701775d60530_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-12 14:41:45.090  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 14:41:45.102  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-12 14:41:45.107  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 14:41:45.153  1501  2420 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
09-12 14:41:45.153  1501  2420 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 14:41:45.153  1501  2420 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 14:41:45.153  1501  2420 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-12 14:41:45.182  3532  3532 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.
09-12 14:41:45.183  3532  3532 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
09-12 14:41:45.183  3532  3532 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 3.
09-12 14:41:45.776  3772  3772 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-12 14:41:45.781  3772  3772 D AndroidRuntime: CheckJNI is OFF
09-12 14:41:45.824  3772  3772 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-12 14:41:45.875  3772  3772 I Radio-JNI: register_android_hardware_Radio DONE
09-12 14:41:45.897  3772  3772 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-12 14:41:45.902   873   883 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-12 14:41:45.958  3772  3772 D AndroidRuntime: Shutting down VM
09-12 14:41:45.958  2050  2421 W SearchService: Abort, client detached.
09-12 14:41:45.964  2050  2050 I HotwordDetector: Closing mic
09-12 14:41:45.965  2050  2339 I MicrophoneInputStream: mic_close com.google.android.apps.gsa.speech.audio.x@f1978c8
09-12 14:41:45.965  2050  2353 E AudioRecord-JNI: Error -4 during AudioRecord native read
09-12 14:41:45.978   873  1397 I ActivityManager: Start proc 3782:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-12 14:41:46.023   376  2356 D audio_hw_primary: disable_audio_route: reset and update mixer path: audio-record
09-12 14:41:46.025   376  2356 D audio_hw_primary: disable_snd_device: snd_device(61: voice-rec-mic)
09-12 14:41:46.034   376  1286 I SoundTriggerHwService::Module: void android::SoundTriggerHwService::Module::onCallbackEvent(const android::sp<android::SoundTriggerHwService::CallbackEvent>&) mClient == 0
09-12 14:41:46.035  2050  2341 I MicroRecognitionRnrImpl: Stopping hotword detection.
09-12 14:41:46.036  2050  2352 I MicroRecognitionRnrImpl: Detection finished
09-12 14:41:46.078  3782  3782 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-12 14:41:46.113  3782  3782 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-12 14:41:46.121  3782  3782 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 220-223)
09-12 14:41:46.121  3782  3782 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 14:41:46.138  3782  3782 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {657c9fe}
09-12 14:41:46.139  3782  3782 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 14:41:46.139  3782  3782 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 14:41:46.146  3782  3782 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-12 14:41:46.148  3782  3782 E SysUtils: ApplicationContext is null in ApplicationStatus
09-12 14:41:46.172  3782  3782 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
09-12 14:41:46.183  3782  3782 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 14:41:46.184  3782  3782 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-12 14:41:46.184  3782  3782 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 14:41:46.184  3782  3782 I Adreno  : Build Date                       : 10/20/15
09-12 14:41:46.184  3782  3782 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 14:41:46.184  3782  3782 I Adreno  : Local Branch                     : M14
09-12 14:41:46.184  3782  3782 I Adreno  : Remote Branch                    : 
09-12 14:41:46.184  3782  3782 I Adreno  : Remote Branch                    : 
09-12 14:41:46.184  3782  3782 I Adreno  : Reconstruct Branch               : 
,09-12 14:41:46.229   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6012a5f:true
,09-12 14:41:46.279  3782  3782 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-12 14:41:46.294  3782  3782 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-12 14:41:46.376  3782  3821 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-12 14:41:46.382  3782  3807 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-12 14:41:46.409  3782  3821 I OpenGLRenderer: Initialized EGL, version 1.4
,09-12 14:41:46.481   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +518ms
,09-12 14:41:46.494  1901  1901 I Keyboard.Facilitator: onFinishInput()
,09-12 14:41:46.547  3782  3782 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3782
,09-12 14:41:46.672  3782  3782 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-12 14:41:46.791   873  2023 I ActivityManager: Killing 2992:com.google.android.calendar/u0a37 (adj 15): empty #17
,09-12 14:41:46.843   873  2023 I ActivityManager: Killing 3119:com.google.android.apps.maps/u0a65 (adj 15): empty #18
,09-12 14:41:46.959  3782  3823 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1680344784
,09-12 14:41:46.980  3782  3823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 14:41:46.980  3782  3823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 14:41:46.980  3782  3823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 14:41:46.980  3782  3823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 14:41:46.980  3782  3823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-12 14:41:46.981  3782  3823 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30fed22 added. We now have 1 listener(s)
,09-12 14:41:46.994  3782  3823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-12 14:41:46.997  3782  3823 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 14:41:46.999  3782  3823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 14:41:47.000  3782  3823 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 14:41:47.005  3782  3823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 14:41:47.005  3782  3823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 14:41:47.005  3782  3823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 14:41:47.005  3782  3823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-12 14:41:47.005  3782  3823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 14:41:47.005  3782  3823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 14:41:47.005  3782  3823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 14:41:47.005  3782  3823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 14:41:47.005  3782  3823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 14:41:47.005  3782  3823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 14:41:47.005  3782  3823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 14:41:47.005  3782  3823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 14:41:47.005  3782  3823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 14:41:47.005  3782  3823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-12 14:41:47.005  3782  3823 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d05c8e9 added. We now have 1 listener(s)
09-12 14:41:47.005  3782  3823 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:41:47.008   873  1315 D WifiService: New client listening to asynchronous messages
,09-12 14:41:47.009  3782  3823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 14:41:47.009  3782  3823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-12 14:41:47.009  3782  3823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-12 14:41:47.009  3782  3823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-12 14:41:47.009  3782  3823 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-12 14:41:47.012  3782  3823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:41:47.012  3782  3823 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-12 14:41:47.020  3782  3823 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-12 14:41:47.021  3782  3823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:41:47.021  3782  3823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:47.021  3782  3823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:47.021  3782  3823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:41:47.021  3782  3823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:41:47.021  3782  3823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:47.021  3782  3823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:41:47.021  3782  3823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:41:47.021  3782  3823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-12 14:41:47.021  3782  3823 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 14:41:47.022  3782  3823 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 14:41:47.108  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:47.113  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:47.115  3782  3782 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 14:41:47.121   873  2095 D NetlinkSocketObserver: NeighborEvent{elapsedMs=121223, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-12 14:41:47.920  3782  3832 W jxcore-log: Initializing JXcore engine
,09-12 14:41:47.920  3782  3832 W jxcore-log: JXcore engine is ready
,09-12 14:41:47.955  3832  3832 W Thread-317: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8932 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-12 14:41:47.955  3832  3832 W Thread-317: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13122]" dev="sockfs" ino=13122 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-12 14:41:47.955  3832  3832 W Thread-317: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-12 14:41:47.955  3832  3832 W Thread-317: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[25071]" dev="sockfs" ino=25071 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-12 14:41:47.973  3782  3832 W jxcore-log: Starting JXcore engine
,09-12 14:41:48.062  3782  3832 W jxcore-log: Platform android
09-12 14:41:48.062  3782  3832 W jxcore-log: 
,09-12 14:41:48.063  3782  3832 W jxcore-log: Process ARCH arm
09-12 14:41:48.063  3782  3832 W jxcore-log: 
,09-12 14:41:48.308  3782  3832 I jxcore-log: JXcore Cordova bridge is ready!
09-12 14:41:48.308  3782  3832 I jxcore-log: 
09-12 14:41:48.308  3782  3832 W jxcore-log: JXcore engine is started
,09-12 14:41:48.320  3782  3823 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-12 14:41:48.324  3782  3782 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 14:41:49.496   873  1314 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,09-12 14:41:52.429  3044  3839 V KeepSync: Connecting to GoogleApiClient
,09-12 14:41:52.429   873  1397 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-12 14:41:52.459  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 14:41:52.465  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 14:41:52.533  1501  3225 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 14:41:52.533  1501  3225 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 14:41:52.533  1501  3225 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 14:41:52.533  1501  3225 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-12 14:41:52.533  1501  2990 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-12 14:41:52.533  1501  2990 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-12 14:41:52.533  1501  2990 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-12 14:41:52.533  1501  2990 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 14:41:52.555  3008  3841 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-12 14:41:52.555  3008  3841 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 14:41:52.555  3008  3841 E HttpOperation: 	at jdm.a(PG:82)
09-12 14:41:52.555  3008  3841 E HttpOperation: 	at jcs.o(PG:406)
09-12 14:41:52.555  3008  3841 E HttpOperation: 	at jcn.a(PG:1379)
09-12 14:41:52.555  3008  3841 E HttpOperation: 	at jcs.i(PG:143)
09-12 14:41:52.555  3008  3841 E HttpOperation: 	at blb.a(PG:3937)
09-12 14:41:52.555  3008  3841 E HttpOperation: 	at czp.a(PG:18188)
09-12 14:41:52.555  3008  3841 E HttpOperation: 	at czp.a(PG:9081)
09-12 14:41:52.555  3008  3841 E HttpOperation: 	at czq.run(PG:1686)
09-12 14:41:52.555  3008  3841 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 14:41:52.555  3008  3841 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 14:41:52.555  3008  3841 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 14:41:52.555  3008  3841 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 14:41:52.555  3008  3841 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 14:41:52.555  3008  3841 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 14:41:52.555  3008  3841 E HttpOperation: 	at jdj.a(PG:4091)
09-12 14:41:52.555  3008  3841 E HttpOperation: 	at jdj.a(PG:1125)
09-12 14:41:52.555  3008  3841 E HttpOperation: 	at jdm.a(PG:77)
09-12 14:41:52.555  3008  3841 E HttpOperation: 	... 12 more
09-12 14:41:52.555  3008  3841 E HttpOperation: Caused by: faj: BadAuthentication
09-12 14:41:52.555  3008  3841 E HttpOperation: 	at fal.a(PG:38)
09-12 14:41:52.555  3008  3841 E HttpOperation: 	at jdj.a(PG:4089)
09-12 14:41:52.555  3008  3841 E HttpOperation: 	... 14 more
,09-12 14:41:52.561  1706  3842 V BaseAuthAsyncOperation: access token request failed
,09-12 14:41:52.562  3044  3839 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-12 14:41:52.608  1501  1997 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-12 14:41:52.608  1501  1997 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-12 14:41:52.608  1501  1997 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 14:41:52.608  1501  1997 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 14:41:52.621  3008  3841 E HttpOperation: [getmobileexperiments] Unexpected exception
09-12 14:41:52.621  3008  3841 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-12 14:41:52.621  3008  3841 E HttpOperation: 	at jdm.a(PG:82)
09-12 14:41:52.621  3008  3841 E HttpOperation: 	at jcs.o(PG:406)
09-12 14:41:52.621  3008  3841 E HttpOperation: 	at jcn.a(PG:1379)
09-12 14:41:52.621  3008  3841 E HttpOperation: 	at jcs.i(PG:143)
09-12 14:41:52.621  3008  3841 E HttpOperation: 	at hec.a(PG:42)
09-12 14:41:52.621  3008  3841 E HttpOperation: 	at hee.a(PG:102)
09-12 14:41:52.621  3008  3841 E HttpOperation: 	at czr.a(PG:65)
09-12 14:41:52.621  3008  3841 E HttpOperation: 	at kka.a(PG:108)
09-12 14:41:52.621  3008  3841 E HttpOperation: 	at czp.a(PG:19176)
09-12 14:41:52.621  3008  3841 E HttpOperation: 	at czp.a(PG:9081)
09-12 14:41:52.621  3008  3841 E HttpOperation: 	at czq.run(PG:1686)
09-12 14:41:52.621  3008  3841 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 14:41:52.621  3008  3841 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 14:41:52.621  3008  3841 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 14:41:52.621  3008  3841 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 14:41:52.621  3008  3841 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-12 14:41:52.621  3008  3841 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 14:41:52.621  3008  3841 E HttpOperation: 	at jdj.a(PG:4091)
09-12 14:41:52.621  3008  3841 E HttpOperation: 	at jdj.a(PG:1125)
09-12 14:41:52.621  3008  3841 E HttpOperation: 	at jdm.a(PG:77)
09-12 14:41:52.621  3008  3841 E HttpOperation: 	... 15 more
09-12 14:41:52.621  3008  3841 E HttpOperation: Caused by: faj: BadAuthentication
09-12 14:41:52.621  3008  3841 E HttpOperation: 	at fal.a(PG:38)
09-12 14:41:52.621  3008  3841 E HttpOperation: 	at jdj.a(PG:4089)
09-12 14:41:52.621  3008  3841 E HttpOperation: 	... 17 more
,09-12 14:41:52.622  3008  3841 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-12 14:41:52.622  3008  3841 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	at jdm.a(PG:82)
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	at jcs.o(PG:406)
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	at jcn.a(PG:1379)
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	at jcs.i(PG:143)
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	at hec.a(PG:42)
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	at hee.a(PG:102)
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	at czr.a(PG:65)
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	at kka.a(PG:108)
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	at czp.a(PG:19176)
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	at czp.a(PG:9081)
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	at czq.run(PG:1686)
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818),
09-12 14:41:52.622  3008  3841 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	at jdj.a(PG:4091)
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	at jdj.a(PG:1125)
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	at jdm.a(PG:77)
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	... 15 more
09-12 14:41:52.622  3008  3841 E ExperimentLoader: Caused by: faj: BadAuthentication
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	at fal.a(PG:38)
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	at jdj.a(PG:4089)
09-12 14:41:52.622  3008  3841 E ExperimentLoader: 	... 17 more
,09-12 14:41:52.641  1501  2420 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-12 14:41:52.641  1501  2420 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,09-12 14:41:52.642  1501  2420 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 14:41:52.642  1501  2420 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 14:41:52.658  3044  3839 E KeepSync: IOException
09-12 14:41:52.658  3044  3839 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-12 14:41:52.658  3044  3839 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-12 14:41:52.658  3044  3839 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-12 14:41:52.658  3044  3839 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-12 14:41:52.658  3044  3839 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-12 14:41:52.658  3044  3839 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-12 14:41:52.658  3044  3839 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-12 14:41:52.658  3044  3839 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-12 14:41:52.658  3044  3839 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-12 14:41:52.658  3044  3839 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-12 14:41:52.658  3044  3839 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-12 14:41:52.658  3044  3839 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-12 14:41:52.658  3044  3839 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-12 14:41:52.658  3044  3839 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-12 14:41:52.658  3044  3839 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 14:41:52.658  3044  3839 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-12 14:41:52.658  3044  3839 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-12 14:41:52.658  3044  3839 E KeepSync: 	... 10 more
,09-12 14:41:52.658  3044  3839 W KeepSync: Sync result 2
,09-12 14:41:52.664   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 126048, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-12 14:41:52.706   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 126191, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-12 14:41:58.202  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-12 14:41:58.202  3782  3832 I jxcore-log: 
,09-12 14:41:58.205  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-12 14:41:58.205  3782  3832 I jxcore-log: 
,09-12 14:41:58.216  3782  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:41:58.216  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:58.216  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:58.216  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:41:58.216  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:41:58.216  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:58.216  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:41:58.216  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:41:58.222  3782  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 14:41:58.225  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-12 14:41:58.225  3782  3832 I jxcore-log: 
,09-12 14:41:58.227  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-12 14:41:58.227  3782  3832 I jxcore-log: 
,09-12 14:41:58.722  3782  3832 D executeNativeTests: Running unit tests
,09-12 14:41:58.780  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:41:58.780  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 added. We now have 2 listener(s)
,09-12 14:41:58.781  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 14:41:58.781  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:41:58.781  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:41:58.781  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:41:58.781  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 added. We now have 2 listener(s)
,09-12 14:41:58.781  3782  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:41:58.782  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 14:41:58.787  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:41:58.803  3782  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:41:58.803  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:58.803  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:58.803  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:41:58.803  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:41:58.803  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:58.803  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:41:58.803  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:41:58.808  3782  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 14:41:58.809  3782  3832 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 14:41:58.811  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 14:41:58.811  3782  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 14:41:58.811  3782  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 14:41:58.812  3782  3832 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-12 14:41:58.813  3782  3832 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 14:41:58.813  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 14:41:58.813  3782  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 14:41:58.813  3782  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 14:41:58.813  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 14:41:58.814  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 14:41:58.814  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 14:41:58.814  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 14:41:58.814  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:58.814  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:41:58.814  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 14:41:58.814  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 removed from the list
,09-12 14:41:58.814  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:41:58.814  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 removed from the list
,09-12 14:41:58.816  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:58.816  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop,
09-12 14:41:58.816  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:58.820  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:58.820  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:58.830  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:58.830  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:58.830  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-12 14:41:58.830  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:58.832  3782  3832 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-12 14:41:58.833  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:58.833  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:58.833  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 14:41:58.833  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:58.833  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:58.833  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:58.833  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
09-12 14:41:58.833  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:41:58.833  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:58.835  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:58.836  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:58.836  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:58.836  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:58.836  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:58.836  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:58.839  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 14:41:58.839  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:58.839  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:58.839  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:58.844  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 14:41:58.844  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 14:41:58.844  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 14:41:58.844  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 14:41:58.844  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 14:41:58.844  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 14:41:58.844  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 14:41:58.844  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 14:41:58.844  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 14:41:58.844  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 14:41:58.844  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 14:41:58.844  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 14:41:58.844  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 14:41:58.845  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 14:41:58.845  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 14:41:58.845  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 14:41:58.845  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-12 14:41:58.845  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 14:41:58.845  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 14:41:58.845  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 14:41:58.845  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 14:41:58.845  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 14:41:58.845  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 14:41:58.845  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 14:41:58.845  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 14:41:58.845  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 14:41:58.845  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 14:41:58.845  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-12 14:41:58.845  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 14:41:58.845  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 14:41:58.846  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 14:41:58.846  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:58.846  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:58.846  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:58.846  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:58.846  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:58.846  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:58.846  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
09-12 14:41:58.846  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:58.846  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
,09-12 14:41:58.846  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:58.846  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:58.846  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:58.846  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:58.846  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:58.848  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:58.848  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:58.848  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:58.848  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:58.849  3782  3832 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 14:41:58.850  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:41:58.857  3782  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:41:58.857  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:58.857  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:58.857  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:41:58.857  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:41:58.857  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:58.857  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:41:58.857  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:41:58.859  3782  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:58.860  3782  3832 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 14:41:58.860  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 14:41:58.860  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 14:41:58.860  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 14:41:58.860  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:41:58.860  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 14:41:58.865  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:58.865  3782  3832 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 14:41:58.865  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 14:41:58.867  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:58.871  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 14:41:58.873  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 14:41:58.874  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 14:41:58.876  3782  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-12 14:41:58.881  3782  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-12 14:41:58.882  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 14:41:58.882  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 14:41:58.884  3782  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 14:41:58.886  3782  3832 D BluetoothAdapter: STATE_ON
,09-12 14:41:58.896  2678  2689 D BtGatt.GattService: registerClient() - UUID=3011e562-e26a-4923-a852-baae73393c83
,09-12 14:41:58.897  2678  2709 D BtGatt.GattService: onClientRegistered() - UUID=3011e562-e26a-4923-a852-baae73393c83, clientIf=5
,09-12 14:41:58.897  3782  3793 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 14:41:58.899  2678  2690 D BtGatt.GattService: start scan with filters
,09-12 14:41:58.908  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 14:41:58.908  2678  2712 D BtGatt.ScanManager: handling starting scan
09-12 14:41:58.908  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 14:41:58.908  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 14:41:58.908  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 14:41:58.910  2678  2712 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36fe698
09-12 14:41:58.910  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 14:41:58.910  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 14:41:58.911  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 14:41:58.913  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 14:41:58.920  3782  3832 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 14:41:58.921  2678  2709 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-12 14:41:58.921  2678  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 14:41:58.922  2678  2712 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 14:41:58.926  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 14:41:58.926  3782  3832 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 14:41:58.927  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:58.927  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 14:41:58.927  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:58.927  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 14:41:58.927  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 14:41:58.928  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 14:41:58.928  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 14:41:58.928  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 14:41:58.929  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 14:41:58.929  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 14:41:58.930  3782  3832 D BluetoothAdapter: STATE_ON
09-12 14:41:58.931  2678  2690 D BtGatt.GattService: stopScan() - queue size =1
09-12 14:41:58.932  2678  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 14:41:58.932  2678  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 14:41:58.932  2678  2712 D BtGatt.ScanManager: Starting BLE batch scan
09-12 14:41:58.933  2678  2831 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 14:41:58.933  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 14:41:58.933  2678  2712 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 14:41:58.933  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 14:41:58.933  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 14:41:58.933  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 14:41:58.933  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 14:41:58.935  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 14:41:58.935  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 14:41:58.935  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 14:41:58.935  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 14:41:58.936  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:41:58.936  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 14:41:58.936  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 14:41:58.937  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 14:41:58.937  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:58.937  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:58.937  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:41:58.937  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
09-12 14:41:58.937  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:58.937  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:58.937  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:58.937  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:58.937  3782  3832 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 14:41:58.940  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:41:58.944  3782  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:41:58.944  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:58.944  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:58.944  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:41:58.944  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:41:58.944  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:58.944  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:41:58.944  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:41:58.946  2678  2709 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 14:41:58.946  2678  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 14:41:58.946  3782  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 14:41:58.947  3782  3832 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 14:41:58.948  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only,
09-12 14:41:58.948  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:41:58.948  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 14:41:58.951  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 14:41:58.952  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:41:58.954  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:41:58.955  2678  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 14:41:58.955  2678  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 14:41:58.952  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 14:41:58.962  3782  3832 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 14:41:58.962  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 14:41:58.965  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 14:41:58.966  2678  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 14:41:58.966  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 14:41:58.966  2678  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 14:41:58.966  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 14:41:58.966  2678  2712 D BtGatt.ScanManager: stopping BLe Batch
,09-12 14:41:58.968  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 14:41:58.968  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 14:41:58.968  3782  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 14:41:58.969  3782  3832 D BluetoothAdapter: STATE_ON
09-12 14:41:58.970  2678  2831 D BtGatt.GattService: registerClient() - UUID=8c7a9e79-07cb-4288-837f-7a29d72f25fe
,09-12 14:41:58.970  2678  2709 D BtGatt.GattService: onClientRegistered() - UUID=8c7a9e79-07cb-4288-837f-7a29d72f25fe, clientIf=5
09-12 14:41:58.971  3782  3794 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 14:41:58.972  2678  2690 D BtGatt.GattService: start scan with filters
09-12 14:41:58.972  2678  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 14:41:58.972  2678  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 14:41:58.973  2678  2712 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 14:41:58.974  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 14:41:58.974  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 14:41:58.974  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 14:41:58.974  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 14:41:58.976  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 14:41:58.976  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 14:41:58.976  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 14:41:58.977  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 14:41:58.978  3782  3832 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 14:41:58.979  2678  2709 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 14:41:58.979  2678  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 14:41:58.980  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:58.980  3782  3832 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 14:41:58.980  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:58.980  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 14:41:58.980  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:58.980  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 14:41:58.980  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 14:41:58.980  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 14:41:58.980  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 14:41:58.980  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 14:41:58.980  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 14:41:58.980  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 14:41:58.981  3782  3832 D BluetoothAdapter: STATE_ON
,09-12 14:41:58.981  2678  2712 D BtGatt.ScanManager: handling starting scan
09-12 14:41:58.981  2678  2690 D BtGatt.GattService: stopScan() - queue size =0
09-12 14:41:58.982  2678  2689 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 14:41:58.982  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 14:41:58.982  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 14:41:58.982  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 14:41:58.982  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 14:41:58.982  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 14:41:58.983  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 14:41:58.983  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 14:41:58.983  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 14:41:58.983  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 14:41:58.983  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:41:58.984  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:58.984  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:58.984  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:41:58.984  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
09-12 14:41:58.986  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:58.986  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:58.986  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:58.986  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:58.984  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 14:41:58.986  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:58.986  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:58.987  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:58.988  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 14:41:58.988  2678  2709 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 14:41:58.991  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:58.991  2678  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 14:41:58.988  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 14:41:58.991  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:58.991  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:58.991  2678  2712 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 14:41:58.992  3782  3832 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 14:41:58.993  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:41:58.997  3782  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:41:58.997  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:58.997  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:58.997  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:41:58.997  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:41:58.997  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:58.997  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:41:58.997  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:41:58.998  2678  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 14:41:58.998  2678  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 14:41:58.998  2678  2712 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 14:41:58.998  2678  2712 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 14:41:58.999  3782  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:58.999  3782  3832 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 14:41:58.999  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 14:41:58.999  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 14:41:58.999  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 14:41:58.999  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:41:58.999  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 14:41:59.005  3782  3832 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 14:41:59.005  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 14:41:59.006  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:59.012  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:59.013  2678  2709 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 14:41:59.013  2678  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 14:41:59.014  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 14:41:59.015  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-12 14:41:59.015  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 14:41:59.020  2678  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 14:41:59.020  2678  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 14:41:59.020  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 14:41:59.020  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 14:41:59.020  3782  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 14:41:59.021  3782  3832 D BluetoothAdapter: STATE_ON
,09-12 14:41:59.031  2678  2689 D BtGatt.GattService: registerClient() - UUID=2c20d17e-ba51-419b-8b27-1bbb75dab4a0
,09-12 14:41:59.032  2678  2709 D BtGatt.GattService: onClientRegistered() - UUID=2c20d17e-ba51-419b-8b27-1bbb75dab4a0, clientIf=5
09-12 14:41:59.032  3782  3794 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 14:41:59.033  2678  2831 D BtGatt.GattService: start scan with filters
,09-12 14:41:59.033  2678  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 14:41:59.033  2678  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 14:41:59.033  2678  2712 D BtGatt.ScanManager: stopping BLe Batch
,09-12 14:41:59.042  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 14:41:59.043  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 14:41:59.043  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 14:41:59.043  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 14:41:59.044  2678  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 14:41:59.044  2678  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 14:41:59.045  2678  2712 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 14:41:59.049  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 14:41:59.050  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 14:41:59.050  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 14:41:59.050  2678  2709 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 14:41:59.050  2678  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 14:41:59.052  2678  2712 D BtGatt.ScanManager: handling starting scan
,09-12 14:41:59.054  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 14:41:59.060  3782  3832 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 14:41:59.060  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
,09-12 14:41:59.060  3782  3832 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 14:41:59.060  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 14:41:59.061  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 14:41:59.061  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,09-12 14:41:59.061  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 14:41:59.061  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 14:41:59.061  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 14:41:59.061  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 14:41:59.062  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 14:41:59.062  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 14:41:59.062  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 14:41:59.062  2678  2709 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 14:41:59.063  2678  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 14:41:59.063  2678  2712 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 14:41:59.064  3782  3832 D BluetoothAdapter: STATE_ON
,09-12 14:41:59.065  2678  2831 D BtGatt.GattService: stopScan() - queue size =1
,09-12 14:41:59.065  2678  2824 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 14:41:59.066  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 14:41:59.066  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 14:41:59.066  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 14:41:59.066  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 14:41:59.066  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 14:41:59.067  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 14:41:59.067  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 14:41:59.068  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-12 14:41:59.068  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 14:41:59.068  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:41:59.069  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 14:41:59.072  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 14:41:59.073  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 14:41:59.073  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:59.073  3782  3832 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 14:41:59.073  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 14:41:59.073  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:59.073  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:59.073  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:59.074  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:41:59.074  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
09-12 14:41:59.074  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.074  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
,09-12 14:41:59.074  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:59.074  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.074  2678  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 14:41:59.074  2678  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 14:41:59.074  2678  2712 D BtGatt.ScanManager: Starting BLE batch scan
09-12 14:41:59.075  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.075  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:59.075  2678  2712 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 14:41:59.075  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:59.075  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:59.075  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:41:59.076  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:59.076  3782  3832 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-12 14:41:59.077  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:59.077  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 14:41:59.077  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:59.077  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:59.077  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:59.077  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:59.077  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
09-12 14:41:59.077  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.077  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:59.077  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 14:41:59.078  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.078  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.078  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:59.078  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:59.079  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:59.079  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:59.079  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:41:59.079  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:59.080  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 14:41:59.080  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:59.080  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:59.080  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 14:41:59.080  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:59.080  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.080  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.080  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
,09-12 14:41:59.081  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.081  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:59.081  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 14:41:59.081  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.081  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.081  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-12 14:41:59.081  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:59.082  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:59.082  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:59.082  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.082  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list,
09-12 14:41:59.083  3782  3832 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null,
,09-12 14:41:59.083  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 14:41:59.083  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:59.083  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:59.083  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-12 14:41:59.083  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:59.083  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:59.083  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
,09-12 14:41:59.084  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:41:59.084  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
,09-12 14:41:59.084  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:59.084  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:59.084  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:59.084  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.084  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:59.085  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 14:41:59.085  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:59.085  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.086  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
,09-12 14:41:59.086  3782  3832 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-12 14:41:59.087  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 14:41:59.087  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 14:41:59.087  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 14:41:59.087  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:59.087  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:59.087  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:59.087  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
09-12 14:41:59.087  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:41:59.087  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
,09-12 14:41:59.087  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 14:41:59.087  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:59.088  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:59.088  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.088  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:59.089  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 14:41:59.089  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:59.089  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.090  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
,09-12 14:41:59.090  2678  2709 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 14:41:59.091  2678  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 14:41:59.091  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 14:41:59.091  3782  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 14:41:59.092  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 14:41:59.092  3782  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 14:41:59.092  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 14:41:59.092  3782  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 14:41:59.092  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 14:41:59.093  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:59.094  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:59.094  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:59.094  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.094  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.095  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
09-12 14:41:59.095  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.095  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
,09-12 14:41:59.095  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:59.095  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.095  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.095  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.096  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.097  2678  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 14:41:59.097  2678  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 14:41:59.098  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:59.099  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 14:41:59.099  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.099  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:59.099  3782  3832 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 14:41:59.099  3782  3832 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 14:41:59.100  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 14:41:59.105  2678  2709 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 14:41:59.105  2678  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 14:41:59.105  2678  2712 D BtGatt.ScanManager: stopping BLe Batch
,09-12 14:41:59.107  3782  3832 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 14:41:59.107  3782  3832 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-12 14:41:59.107  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 14:41:59.107  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 14:41:59.107  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 14:41:59.107  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 14:41:59.107  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-12 14:41:59.108  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 14:41:59.108  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 14:41:59.108  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 14:41:59.108  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 14:41:59.108  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 14:41:59.108  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 14:41:59.108  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 14:41:59.108  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-12 14:41:59.108  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 14:41:59.108  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 14:41:59.108  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 14:41:59.108  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 14:41:59.108  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 14:41:59.108  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 14:41:59.108  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 14:41:59.108  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 14:41:59.108  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 14:41:59.108  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 14:41:59.108  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 14:41:59.108  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 14:41:59.108  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 14:41:59.109  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 14:41:59.109  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,09-12 14:41:59.109  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 14:41:59.109  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 14:41:59.109  3782  3832 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-12 14:41:59.109  3782  3832 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 14:41:59.109  3782  3832 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 14:41:59.109  3782  3832 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 14:41:59.109  3782  3832 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-12 14:41:59.109  3782  3832 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-12 14:41:59.109  3782  3832 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 14:41:59.109  3782  3832 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 14:41:59.109  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-12 14:41:59.111  2678  2709 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 14:41:59.111  2678  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 14:41:59.111  2678  2712 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 14:41:59.114  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-12 14:41:59.115  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-12 14:41:59.115  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-12 14:41:59.115  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-12 14:41:59.115  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,09-12 14:41:59.116  3782  3832 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-12 14:41:59.116  3782  3832 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 14:41:59.116  3782  3832 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-12 14:41:59.116  3782  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 381)
09-12 14:41:59.116  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:59.116  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 14:41:59.116  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:59.116  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:59.116  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.117  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.117  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,09-12 14:41:59.117  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
09-12 14:41:59.117  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.117  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:59.117  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:59.117  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.117  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:59.117  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.118  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:59.121  3782  3849 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 381
09-12 14:41:59.121  2678  2709 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 14:41:59.121  2678  2709 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 14:41:59.122  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:59.122  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:59.122  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.122  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:59.123  3782  3832 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-12 14:41:59.123  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 14:41:59.123  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:59.123  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 14:41:59.123  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:59.123  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:59.123  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.123  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
09-12 14:41:59.123  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.123  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:59.123  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:59.123  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.124  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.124  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-12 14:41:59.124  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.124  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:59.124  3782  3848 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 14:41:59.124  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:59.125  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.125  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
,09-12 14:41:59.125  3782  3832 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-12 14:41:59.125  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:59.125  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:59.125  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:59.125  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 14:41:59.125  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.126  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.126  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
09-12 14:41:59.126  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:41:59.126  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:59.126  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:59.126  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:59.126  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.126  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.126  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.127  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:59.127  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 14:41:59.127  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.127  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:59.127  3782  3832 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,09-12 14:41:59.127  3782  3832 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-12 14:41:59.127  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 14:41:59.128  3782  3832 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 14:41:59.128  3782  3832 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 14:41:59.128  3782  3832 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,09-12 14:41:59.128  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 14:41:59.128  3782  3832 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 14:41:59.128  3782  3832 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-12 14:41:59.128  3782  3832 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 14:41:59.128  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 14:41:59.128  3782  3832 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 14:41:59.129  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:59.129  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 14:41:59.129  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:59.129  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:59.129  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.129  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:59.129  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
09-12 14:41:59.129  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.129  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:59.129  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop,
09-12 14:41:59.130  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.130  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:59.130  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.130  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.130  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:59.131  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 14:41:59.131  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.131  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:59.131  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:59.131  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-12 14:41:59.131  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.131  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
09-12 14:41:59.131  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.131  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
,09-12 14:41:59.132  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:59.132  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.132  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.132  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.132  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
,09-12 14:41:59.132  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:59.132  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.132  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.132  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
,09-12 14:41:59.132  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:59.132  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:59.132  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
09-12 14:41:59.132  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:59.132  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.133  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:59.133  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
09-12 14:41:59.133  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:41:59.133  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:59.133  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:59.133  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-12 14:41:59.133  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:59.133  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.133  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.135  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 14:41:59.135  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:59.135  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:41:59.135  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:59.136  3782  3832 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 14:41:59.136  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:41:59.137  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-12 14:41:59.138  3782  3832 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-12 14:41:59.138  3782  3832 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 14:41:59.138  3782  3782 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 14:41:59.138  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK,
09-12 14:41:59.138  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 14:41:59.138  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 14:41:59.138  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 14:41:59.139  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,09-12 14:41:59.139  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 14:41:59.139  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.139  3782  3832 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-12 14:41:59.139  3782  3782 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 14:41:59.139  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
09-12 14:41:59.139  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.139  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 14:41:59.139  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 14:41:59.139  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 14:41:59.139  3782  3850 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 14:41:59.139  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:59.139  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.140  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 14:41:59.140  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 14:41:59.140  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 14:41:59.140  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 14:41:59.140  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
,09-12 14:41:59.140  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:59.140  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:59.141  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:59.141  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:59.141  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:59.141  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.141  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
09-12 14:41:59.141  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.141  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:59.141  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:59.141  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.141  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:59.141  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.141  3782  3850 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-12 14:41:59.141  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.141  3782  3850 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 14:41:59.141  3782  3850 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-12 14:41:59.142  3782  3782 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 14:41:59.142  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:59.142  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:59.142  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:41:59.142  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:59.143  3782  3832 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-12 14:41:59.143  3782  3832 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 14:41:59.143  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 14:41:59.143  3782  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 14:41:59.144  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:59.144  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:59.144  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:59.144  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:59.144  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.144  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.144  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
,09-12 14:41:59.144  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.144  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:59.144  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:59.144  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.144  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.144  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.144  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.146  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:59.146  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:59.146  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:41:59.146  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:59.149  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:59.150  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:59.150  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:59.150  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:59.150  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.150  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.150  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
09-12 14:41:59.150  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:41:59.150  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:59.150  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:59.150  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.150  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.150  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:59.150  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.151  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:59.151  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:59.151  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.151  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
,09-12 14:41:59.152  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:41:59.152  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:41:59.152  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:41:59.152  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:41:59.152  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.153  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:41:59.153  3782  3832 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@47a3772 not in the list
09-12 14:41:59.153  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:41:59.153  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:59.153  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:41:59.153  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:41:59.153  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.153  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:41:59.153  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:41:59.154  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:41:59.154  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:41:59.154  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:41:59.154  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@91a87c3 not in the list
09-12 14:41:59.155  3782  3832 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-12 14:41:59.155  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 14:41:59.155  3782  3832 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-12 14:41:59.155  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-12 14:41:59.155  3782  3832 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-12 14:41:59.155  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 14:41:59.157  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 14:41:59.157  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-12 14:41:59.157  3782  3832 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-12 14:41:59.157  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 14:41:59.157  3782  3832 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-12 14:41:59.157  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 14:41:59.157  3782  3832 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-12 14:41:59.157  3782  3832 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-12 14:41:59.158  3782  3832 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-12 14:41:59.158  3782  3832 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-12 14:41:59.158  3782  3832 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-12 14:41:59.158  3782  3832 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 14:41:59.159  3782  3832 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,09-12 14:41:59.159  3782  3832 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-12 14:41:59.159  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:41:59.159  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2112eed added. We now have 2 listener(s)
09-12 14:41:59.159  3782  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:41:59.161  3782  3832 D BluetoothAdapter: enable(): BT is already enabled..!
,09-12 14:41:59.161   873   883 D WifiService: setWifiEnabled: true pid=3782, uid=10000
09-12 14:41:59.161   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
09-12 14:41:59.162  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:41:59.162  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5eb6122 added. We now have 3 listener(s)
,09-12 14:41:59.162  3782  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:41:59.168  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:41:59.168  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f1ce7b3 added. We now have 4 listener(s)
,09-12 14:41:59.168  3782  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:41:59.169  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 14:41:59.169  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5596170 added. We now have 5 listener(s)
,09-12 14:41:59.169  3782  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:41:59.170   873  1933 D WifiService: setWifiEnabled: false pid=3782, uid=10000
,09-12 14:41:59.171   873  1933 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 14:41:59.176  2678  2705 D BluetoothAdapterState: Current state: ON, message: 23
09-12 14:41:59.176  2678  2705 D BluetoothAdapterProperties: Setting state to 13
,09-12 14:41:59.176  2678  2705 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,09-12 14:41:59.176  2678  2705 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 14:41:59.176  2678  2705 I BluetoothAdapterState: Entering PendingCommandState
,09-12 14:41:59.181  2678  2678 D BluetoothMapService: onReceive
09-12 14:41:59.181  2678  2678 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-12 14:41:59.181  2678  2678 D BluetoothMapService: STATE_TURNING_OFF
,09-12 14:41:59.181  2678  2678 D BluetoothMapService: MAP Service closeService in
09-12 14:41:59.181  2678  2678 D BluetoothMapMasInstance0: MAP Service shutdown
,09-12 14:41:59.181  2678  2678 D ObexServerSockets0: shutdown(block = true)
09-12 14:41:59.182  2678  2678 D ObexServerSockets0: shutdown called from another thread - interrupt().,
,09-12 14:41:59.182  2678  2678 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-12 14:41:59.182  2678  2832 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-12 14:41:59.182  2678  2819 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-12 14:41:59.182  2678  2833 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-12 14:41:59.188  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
09-12 14:41:59.188  2678  2678 I BtOppRfcommListener: stopping Accept Thread
,09-12 14:41:59.188  2678  3474 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 14:41:59.188  2678  3474 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-12 14:41:59.189  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:41:59.189  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:41:59.189  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:59.189  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:59.189  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:41:59.189  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:41:59.189  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:59.189  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:41:59.189  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:41:59.190  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:41:59.190  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:59.190   873  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
09-12 14:41:59.191   873  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-12 14:41:59.191   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 14:41:59.191   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 14:41:59.194   873   886 I ActivityManager: Start proc 3854:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
09-12 14:41:59.196  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:41:59.197  2678  2709 D BluetoothAdapterProperties: Scan Mode:20
09-12 14:41:59.198  2678  2705 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-12 14:41:59.199  2678  2678 D HeadsetService: Received stop request...Stopping profile...
09-12 14:41:59.200   873  2102 D DhcpClient: Clearing IP address
,09-12 14:41:59.200   372   871 D CommandListener: Clearing all IP addresses on wlan0
,09-12 14:41:59.202   873   873 D BluetoothHeadset: Proxy object disconnected
,09-12 14:41:59.202  1968  2126 D BluetoothHeadset: Proxy object disconnected
09-12 14:41:59.202   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 14:41:59.202   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 14:41:59.202  1366  1393 D BluetoothHeadset: Proxy object disconnected
,09-12 14:41:59.203  2678  2678 D A2dpService: Received stop request...Stopping profile...
09-12 14:41:59.203   372   871 D CommandListener: Setting iface cfg
09-12 14:41:59.203  2678  2826 D A2dpStateMachine: Exit Disconnected: -1
09-12 14:41:59.203  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:41:59.204  1501  2551 V NativeCrypto: Read error: ssl=0x9b585000: I/O error during system call, Connection timed out
,09-12 14:41:59.205  2678  2678 V BluetoothAdapterState: isTurningOff()=true
09-12 14:41:59.205  2678  2678 V BluetoothAdapterState: isTurningOn()=false
09-12 14:41:59.205  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 14:41:59.205  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
09-12 14:41:59.206  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:41:59.206  3782  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:41:59.206  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:59.206  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:59.206  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:41:59.206  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:41:59.206  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:59.206  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:41:59.206  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:41:59.206  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 14:41:59.206  3782  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:41:59.206  3782  3832 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 14:41:59.207   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-12 14:41:59.208   873  1314 D WifiStateMachine: Start Disconnecting Watchdog 1
09-12 14:41:59.208  1501  2551 V NativeCrypto: SSL shutdown failed: ssl=0x9b585000: I/O error during system call, Broken pipe
,09-12 14:41:59.208   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-12 14:41:59.208   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 14:41:59.209  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:41:59.209  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:41:59.209  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:59.209  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:59.209  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:41:59.209  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:41:59.209  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:41:59.209  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:41:59.209  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:41:59.210  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 14:41:59.210  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:41:59.210   396   396 E Parcel  : Reading a NULL string not supported here.
09-12 14:41:59.211  2678  2678 D HidService: Received stop request...Stopping profile...
,09-12 14:41:59.211  2678  2678 D HidService: Stopping Bluetooth HidService
09-12 14:41:59.211  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:41:59.211  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:41:59.211  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:59.211  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:59.211  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:41:59.211  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:41:59.211  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:41:59.211  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:41:59.211  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:41:59.212  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:59.213   873  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-12 14:41:59.213  2678  2678 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 14:41:59.213  2678  2678 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 14:41:59.213  2678  2709 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-12 14:41:59.213  2678  2804 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-12 14:41:59.213  2678  2804 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 14:41:59.213  2678  2804 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 14:41:59.213  2678  2678 D HealthService: Received stop request...Stopping profile...
09-12 14:41:59.214  2678  2709 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
09-12 14:41:59.215  2678  2678 V BluetoothAdapterState: isTurningOff()=true
,09-12 14:41:59.215  2678  2678 V BluetoothAdapterState: isTurningOn()=false
09-12 14:41:59.215  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
09-12 14:41:59.215  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
09-12 14:41:59.216   372   871 D CommandListener: Clearing all IP addresses on wlan0
09-12 14:41:59.216   873   873 D BluetoothA2dp: Proxy object disconnected
09-12 14:41:59.218  1366  1366 D HeadsetProfile: Bluetooth service disconnected
09-12 14:41:59.218  1366  1366 D BluetoothA2dp: Proxy object disconnected
09-12 14:41:59.218  1366  1366 D BluetoothInputDevice: Proxy object disconnected
,09-12 14:41:59.218  1366  1366 D HidProfile: Bluetooth service disconnected
09-12 14:41:59.220  2678  2804 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 14:41:59.220  2678  2804 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 14:41:59.220  2678  2804 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 14:41:59.220  2678  2804 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 14:41:59.220  2678  2804 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 14:41:59.220  2678  2804 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-12 14:41:59.220  2678  2709 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-12 14:41:59.221  2678  2678 D PanService: Received stop request...Stopping profile...
09-12 14:41:59.223  2678  2678 D BluetoothMapService: Received stop request...Stopping profile...
09-12 14:41:59.223  2678  2678 D BluetoothMapService: stop()
09-12 14:41:59.223  2678  2678 D BluetoothMapAppObserver: deinitObservers()
09-12 14:41:59.223  2678  2678 D BluetoothMapAppObserver: removeReceiver()
,09-12 14:41:59.224  2678  2678 V BluetoothAdapterState: isTurningOff()=true
09-12 14:41:59.224  2678  2678 V BluetoothAdapterState: isTurningOn()=false
09-12 14:41:59.225  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
09-12 14:41:59.225  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
09-12 14:41:59.225  2678  2678 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,09-12 14:41:59.225  2678  2678 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 14:41:59.225  2678  2678 V BluetoothAdapterState: isTurningOff()=true
09-12 14:41:59.225  2678  2678 V BluetoothAdapterState: isTurningOn()=false
09-12 14:41:59.225  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
09-12 14:41:59.225  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 14:41:59.225  2678  2678 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 14:41:59.225  2678  2709 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 14:41:59.226  2678  2678 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 14:41:59.226  2678  2709 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-12 14:41:59.226  2678  2678 V BluetoothAdapterState: isTurningOff()=true
,09-12 14:41:59.226  2678  2678 V BluetoothAdapterState: isTurningOn()=false
09-12 14:41:59.226  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
09-12 14:41:59.226  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
09-12 14:41:59.226  2678  2678 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 14:41:59.226  2678  2678 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-12 14:41:59.227  2678  2678 D BluetoothMapService: MAP Service closeService in
09-12 14:41:59.227  2678  2678 V BluetoothAdapterState: isTurningOff()=true
09-12 14:41:59.227  2678  2678 V BluetoothAdapterState: isTurningOn()=false
09-12 14:41:59.227  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
09-12 14:41:59.228  2678  2678 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 14:41:59.228  2678  2705 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 14:41:59.228  2678  2705 D BluetoothAdapterProperties: Setting state to 15
09-12 14:41:59.228  2678  2705 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-12 14:41:59.228  2678  2678 D BluetoothMapService: cleanup()
09-12 14:41:59.228  2678  2678 D BluetoothMapService: MAP Service closeService in
09-12 14:41:59.228  2678  2705 I BluetoothAdapterState: Entering BleOnState
09-12 14:41:59.229   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 14:41:59.229   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
09-12 14:41:59.230  1366  2079 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 14:41:59.230   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 14:41:59.230  1366  1382 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 14:41:59.231  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 14:41:59.231  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:41:59.231  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:59.231  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:59.231  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:41:59.231  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:41:59.231  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:41:59.231  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:41:59.231  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 14:41:59.231  1366  1393 D BluetoothPan: onBluetoothStateChange on: false
09-12 14:41:59.231  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:41:59.231  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:41:59.231  1366  3781 D BluetoothMap: onBluetoothStateChange: up=false
,09-12 14:41:59.231   873  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 14:41:59.232  1968  1982 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 14:41:59.232  1366  2082 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 14:41:59.232   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 14:41:59.232  1366  2079 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 14:41:59.233  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:41:59.233  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:41:59.233  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:41:59.233  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:41:59.233  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:41:59.233  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:41:59.233  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:41:59.233  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:41:59.233  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:41:59.233   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 14:41:59.233  2678  2705 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 14:41:59.233  2678  2705 D BluetoothAdapterProperties: Setting state to 16
09-12 14:41:59.233  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:41:59.233  2678  2705 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-12 14:41:59.233  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:41:59.234  2678  2705 D BluetoothAdapterProperties: onBleDisable
09-12 14:41:59.234  2678  2705 I BluetoothAdapterState: Entering PendingCommandState
09-12 14:41:59.234  2678  2706 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-12 14:41:59.235  2678  2709 D BluetoothAdapterProperties: Scan Mode:20
,09-12 14:41:59.235  2678  2804 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 14:41:59.235  2678  2804 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 14:41:59.235  3782  3848 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 381)
09-12 14:41:59.237  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:41:59.237  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:59.238  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:41:59.239  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:41:59.254  1869  1879 I art     : Background partial concurrent mark sweep GC freed 13374(967KB) AllocSpace objects, 15(300KB) LOS objects, 40% free, 22MB/36MB, paused 6.038ms total 55.788ms
09-12 14:41:59.266   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
09-12 14:41:59.272  1869  2302 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 14:41:59.281   873  2118 D DhcpClient: Receive thread stopped
,09-12 14:41:59.283  3854  3854 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-12 14:41:59.295   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 14:41:59.295   873  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-12 14:41:59.296   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-12 14:41:59.297   873   890 D Tethering: MasterInitialState.processMessage what=3
09-12 14:41:59.299  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 14:41:59.302  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:41:59.303  3408  3408 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@30fed22 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,09-12 14:41:59.303  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:41:59.304  2050  2050 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
09-12 14:41:59.310  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 14:41:59.311   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3bc0fce:true
,09-12 14:41:59.324   873   883 I ActivityManager: Start proc 3872:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,09-12 14:41:59.333  3854  3854 D LocalBluetoothProfileManager: Adding local MAP profile
,09-12 14:41:59.335  3854  3854 D BluetoothMap: Create BluetoothMap proxy object
,09-12 14:41:59.339  3854  3854 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-12 14:41:59.348  3854  3854 D DockEventReceiver: finishStartingService: stopping service
,09-12 14:41:59.353   873  2023 I ActivityManager: Killing 3228:com.google.android.gm/u0a78 (adj 15): empty #17
,09-12 14:41:59.358   372   871 E Netd    : netlink response contains error (No such file or directory)
,09-12 14:41:59.368  3872  3872 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-12 14:41:59.441  2678  2709 I bt_hci  : shut_down
09-12 14:41:59.442  2678  2713 D bt_hwcfg: hw_epilog_process
09-12 14:41:59.443  2678  2713 I bt_vendor: low_power_mode_cb
,09-12 14:41:59.462  2678  2713 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-12 14:41:59.463  2678  2713 I bt_vendor: epilog_cb
09-12 14:41:59.463  2678  2713 I bt_hci  : epilog_finished_callback
,09-12 14:41:59.470  2678  2709 I bt_hci_h4: hal_close
,09-12 14:41:59.470  2678  2709 I bt_userial_vendor: device fd = 51 close
,09-12 14:41:59.550  3872  3872 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 14:41:59.550  3872  3872 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.share,d.f.a.a(PG:48)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 14:41:59.550  3872  3872 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 14:41:59.550  3872  3872 D StrictMode: StrictMode policy violation; ~duration=97 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 14:41:59.550  3872  3872 D StrictMode: StrictMode policy violation; ~duration=96 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.r.k.d(PG:583)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 14:41:59.550  3872  3872 D StrictMode: StrictMode policy violation; ~duration=64 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 14:41:59.550  3872  3872 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.io.File.exists(File.java:361)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 14:41:59.550  3872  3872 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 14:41:59.550  3872  3872 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-12 14:41:59.601   873  2083 I ActivityManager: Start proc 3903:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
09-12 14:41:59.604   873  2083 I ActivityManager: Killing 3408:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-12 14:41:59.641  3782  3782 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 14:41:59.757  2678  2706 D bt_stack_manager: event_shut_down_stack finished.
,09-12 14:41:59.758  2678  2705 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-12 14:41:59.759  3903  3903 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-12 14:41:59.763  2678  2678 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 14:41:59.763  2678  2705 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-12 14:41:59.764  2678  2678 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 14:41:59.764  2678  2678 D BtGatt.GattService: stop()
09-12 14:41:59.764  2678  2678 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 14:41:59.768  2678  2678 V BluetoothAdapterState: isTurningOff()=false
,09-12 14:41:59.768  2678  2678 V BluetoothAdapterState: isTurningOn()=false
,09-12 14:41:59.768  2678  2678 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 14:41:59.769  2678  2678 V BluetoothAdapterState: isBleTurningOff()=true
,09-12 14:41:59.769  2678  2705 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-12 14:41:59.770  2678  2705 D BluetoothAdapterProperties: Setting state to 10
,09-12 14:41:59.770  2678  2705 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-12 14:41:59.771  2678  2705 I BluetoothAdapterState: Entering OffState
,09-12 14:41:59.773   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-12 14:41:59.797  2678  2678 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-12 14:41:59.797  2678  2678 W BluetoothSdpJni: Cleaning up Bluetooth Health object
09-12 14:41:59.797  2678  2706 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 14:41:59.799  2678  2706 D bt_stack_manager: event_clean_up_stack finished.
,09-12 14:41:59.800  2678  2678 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 14:41:59.811  2678  2678 I art     : System.exit called, status: 0
,09-12 14:41:59.811  2678  2678 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 14:41:59.826  3903  3903 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-12 14:41:59.849  3872  3891 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-12 14:41:59.864   873  2023 I ActivityManager: Process com.android.bluetooth (pid 2678) has died
,09-12 14:41:59.867   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8f204e2:true
,09-12 14:41:59.906  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 14:41:59.926   873  1395 I ActivityManager: Start proc 3932:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,09-12 14:41:59.928  3854  3854 D DockEventReceiver: finishStartingService: stopping service
,09-12 14:41:59.998  3932  3932 D AdapterServiceConfig: Adding HeadsetService
09-12 14:41:59.998  3932  3932 D AdapterServiceConfig: Adding A2dpService
09-12 14:41:59.999  3932  3932 D AdapterServiceConfig: Adding HidService
,09-12 14:41:59.999  3932  3932 D AdapterServiceConfig: Adding HealthService
09-12 14:41:59.999  3932  3932 D AdapterServiceConfig: Adding PanService
09-12 14:41:59.999  3932  3932 D AdapterServiceConfig: Adding GattService
,09-12 14:41:59.999  3932  3932 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 14:42:00.004   873  1397 I ActivityManager: Killing 2792:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-12 14:42:00.037  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 14:42:00.065  1706  1706 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 14:42:00.075  1706  1706 D SystemUpdateService: onCreate
,09-12 14:42:00.089  1706  1706 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 14:42:00.092  1706  3944 I SystemUpdateService: active receiver: enabled
,09-12 14:42:00.095  1706  3944 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 14:42:00.099  1706  3944 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-12 14:42:00.100  1706  3944 I SystemUpdateService: now status is 0 (complete)
09-12 14:42:00.100  1706  3944 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-12 14:42:00.100  1706  3944 I SystemUpdateService: file has been verified
09-12 14:42:00.100  1706  3944 I SystemUpdateService: OTA package size = 12249756
,09-12 14:42:00.106  1706  3944 I SystemUpdateService: showing system update notification
,09-12 14:42:00.115  1706  1706 D SystemUpdateService: onDestroy
,09-12 14:42:00.124  1706  1706 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 14:42:00.127  1706  2529 I iu.UploadsManager: num queued entries: 0
,09-12 14:42:00.129  1706  1706 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 14:42:00.130  1706  2529 I iu.UploadsManager: num updated entries: 0
,09-12 14:42:00.131  1706  1706 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 14:42:00.133  1706  2529 I iu.SyncManager: NEXT; no task
,09-12 14:42:00.148   873  2083 I ActivityManager: Start proc 3946:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-12 14:42:00.186  3946  3946 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-12 14:42:00.188  3946  3946 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:42:00.197  3946  3946 D SprintDMHelper: simOperator: 
09-12 14:42:00.197  3946  3946 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 14:42:00.214   873   884 I ActivityManager: Start proc 3958:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
09-12 14:42:00.215   873   884 I ActivityManager: Killing 1717:android.process.acore/u0a5 (adj 15): empty #17
,09-12 14:42:00.369   873  2024 I ActivityManager: Start proc 3973:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,09-12 14:42:00.375   873  1933 I ActivityManager: Killing 3638:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-12 14:42:00.433  3973  3973 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-12 14:42:00.492  3973  3973 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-12 14:42:00.492  3973  3973 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-12 14:42:00.492  3973  3973 I GAv4    :   adb logcat -s GAv4
,09-12 14:42:00.507  3973  3973 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-12 14:42:00.515  3973  3973 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-12 14:42:00.544  3973  3990 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-12 14:42:00.677  3973  3973 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-12 14:42:00.718  3973  3973 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-12 14:42:00.726  3973  3973 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4825-4828)
09-12 14:42:00.726  3973  3973 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 14:42:00.739  3973  3973 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3f1e2d2}
09-12 14:42:00.739  3973  3973 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 14:42:00.739  3973  3973 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-12 14:42:00.748  3973  3973 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-12 14:42:00.749  3973  3973 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 14:42:00.768  3973  3973 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-12 14:42:00.783  3973  3973 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 14:42:00.783  3973  3973 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-12 14:42:00.783  3973  3973 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 14:42:00.783  3973  3973 I Adreno  : Build Date                       : 10/20/15
09-12 14:42:00.783  3973  3973 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 14:42:00.783  3973  3973 I Adreno  : Local Branch                     : M14
09-12 14:42:00.783  3973  3973 I Adreno  : Remote Branch                    : 
09-12 14:42:00.783  3973  3973 I Adreno  : Remote Branch                    : 
09-12 14:42:00.783  3973  3973 I Adreno  : Reconstruct Branch               : 
,09-12 14:42:00.849  3973  3973 I NSApplication: Starting up...
,09-12 14:42:00.856  3973  4019 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-12 14:42:00.894   873  2024 I ActivityManager: Start proc 4024:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-12 14:42:00.896   873  2024 I ActivityManager: Killing 3652:com.android.musicfx/u0a18 (adj 15): empty #17
,09-12 14:42:00.975  4024  4024 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-12 14:42:01.177   873  2083 I ActivityManager: Killing 3438:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-12 14:42:02.209   873  1933 D WifiService: setWifiEnabled: true pid=3782, uid=10000
,09-12 14:42:02.209   873  1933 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 14:42:02.221   873  1314 D WifiConfigStore: Loading config and enabling all networks 
,09-12 14:42:02.230  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:42:02.230  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:02.230  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:02.230  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:02.230  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:42:02.230  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:42:02.230  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:02.230  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:02.230  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:42:02.231  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:42:02.231  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 14:42:02.233  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 14:42:02.234  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:02.234  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:02.234  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:02.234  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:42:02.234  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:42:02.234  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:02.234  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:02.234  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 14:42:02.234  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 14:42:02.234  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 14:42:02.247   873  1314 D WifiConfigStore: loaded 0 passpoint configs
,09-12 14:42:02.248   873  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,09-12 14:42:02.249   873  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-12 14:42:02.251   873  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,09-12 14:42:02.251   873  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 14:42:02.252   873  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-12 14:42:02.252   873  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 14:42:02.269   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-12 14:42:02.270   873  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.88 rxSuccessRate=15.62 delta 1000 -> 994
,09-12 14:42:02.272   372   871 D CommandListener: Setting iface cfg
,09-12 14:42:02.274   873  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
09-12 14:42:02.274   873  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-12 14:42:02.278   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-12 14:42:02.279   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 14:42:02.288   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 14:42:02.323   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 14:42:02.325  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 14:42:02.336   873  1313 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 14:42:02.339   873  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 14:42:02.744  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 14:42:02.792  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-12 14:42:02.793  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 14:42:02.798   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 14:42:02.818   873  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 14:42:02.818   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 14:42:02.819   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 14:42:02.841   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 14:42:02.860   372   871 D CommandListener: Setting iface cfg
,09-12 14:42:02.862   873  1314 D WifiStateMachine: Start Dhcp Watchdog 2
,09-12 14:42:02.875   873  1316 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,09-12 14:42:02.878   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 14:42:02.892   873  4047 D DhcpClient: Receive thread started
,09-12 14:42:02.975   873  1314 E native  : do suspend false
,09-12 14:42:02.998   873  2102 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 14:42:03.012   873  4047 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172687, domain null
,09-12 14:42:03.013   873  2102 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172687 seconds
,09-12 14:42:03.016   873  2102 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 14:42:03.030   873  4047 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 14:42:03.031   873  2102 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 14:42:03.036   372   871 D CommandListener: Setting iface cfg
,09-12 14:42:03.047   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-12 14:42:03.047   873  2102 D DhcpClient: Scheduling renewal in 86399s
,09-12 14:42:03.066   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 14:42:03.071   873  1314 D WifiConfigStore: No blacklist allowed without epno enabled
,09-12 14:42:03.071   873  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-12 14:42:03.072   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-12 14:42:03.075   873  1316 D ConnectivityService: Adding iface wlan0 to network 101
,09-12 14:42:03.090   873  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 14:42:03.159   873  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-12 14:42:03.159   873  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,09-12 14:42:03.160   873  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-12 14:42:03.162   873  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,09-12 14:42:03.165   873  1316 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-12 14:42:03.176   873  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-12 14:42:03.181   873  1316 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-12 14:42:03.182   873  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,09-12 14:42:03.182   873  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,09-12 14:42:03.182   873  1316 D ConnectivityService:    accepting network in place of null
,09-12 14:42:03.182   873  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-12 14:42:03.183   873  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -47]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-12 14:42:03.183   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 14:42:03.223   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 14:42:03.262   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 14:42:03.272   873  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-12 14:42:03.272   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:42:03.280   873  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-12 14:42:03.282   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-12 14:42:03.300  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 14:42:03.300  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:03.300  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:03.300  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:03.300  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:42:03.300  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:42:03.300  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:42:03.300  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:42:03.300  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:42:03.301  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:42:03.301  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 14:42:03.306  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 14:42:03.306  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:03.306  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:03.306  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:03.306  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:42:03.306  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:42:03.306  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:42:03.306  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:42:03.306  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:42:03.306  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:42:03.306  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 14:42:03.314  2050  2050 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-12 14:42:03.317  1706  1706 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 14:42:03.320  1706  1706 D SystemUpdateService: onCreate
,09-12 14:42:03.324  1706  1706 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 14:42:03.327  1706  4057 I SystemUpdateService: active receiver: enabled
,09-12 14:42:03.331  1706  4057 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 14:42:03.334  1706  4057 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-12 14:42:03.334  1706  4057 I SystemUpdateService: now status is 0 (complete)
09-12 14:42:03.335  1706  4057 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 14:42:03.335  1706  4057 I SystemUpdateService: file has been verified
,09-12 14:42:03.335  1706  4057 I SystemUpdateService: OTA package size = 12249756
,09-12 14:42:03.341  1706  4057 I SystemUpdateService: showing system update notification
,09-12 14:42:03.347  1706  1706 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 14:42:03.349  1706  2529 I iu.UploadsManager: num queued entries: 0
,09-12 14:42:03.349  1706  2529 I iu.UploadsManager: num updated entries: 0
,09-12 14:42:03.351  1706  1706 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 14:42:03.353  1706  1706 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 14:42:03.355  3946  3946 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-12 14:42:03.355  1706  4061 I MDM     : [172] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-12 14:42:03.355  1706  4061 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 14:42:03.356  1706  2529 I iu.SyncManager: NEXT; no task
,09-12 14:42:03.357  1706  4061 V GoogleAuthProtoRequest: [172] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 14:42:03.358  3946  3946 D SprintDMHelper: simOperator: 
09-12 14:42:03.358  3946  3946 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 14:42:03.362  1706  1706 D SystemUpdateService: onDestroy
,09-12 14:42:03.365  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 14:42:03.367  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 14:42:03.406  1501  1513 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-12 14:42:03.407  1501  1513 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,09-12 14:42:03.407  1501  1513 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 14:42:03.407  1501  1513 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 14:42:03.419  1706  4061 E MDM     : [172] SitrepService.a: Error sending sitrep.
,09-12 14:42:04.271   873  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-12 14:42:05.263   873  2024 D WifiService: setWifiEnabled: false pid=3782, uid=10000
,09-12 14:42:05.263   873  2024 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 14:42:05.275  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-12 14:42:05.279   873  1314 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-12 14:42:05.279   873  1314 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
09-12 14:42:05.280   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 14:42:05.280   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 14:42:05.299   372   871 D CommandListener: Clearing all IP addresses on wlan0
,09-12 14:42:05.299   873  2102 D DhcpClient: Clearing IP address
,09-12 14:42:05.301   372   871 D CommandListener: Setting iface cfg
,09-12 14:42:05.313   873  4047 D DhcpClient: Receive thread stopped
,09-12 14:42:05.317   873  1314 D WifiStateMachine: Start Disconnecting Watchdog 2
,09-12 14:42:05.317   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-12 14:42:05.317   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-12 14:42:05.320   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-12 14:42:05.323   372   871 D CommandListener: Clearing all IP addresses on wlan0
09-12 14:42:05.325   396   396 E Parcel  : Reading a NULL string not supported here.
,09-12 14:42:05.331   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
09-12 14:42:05.335  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:42:05.335  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:05.335  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:05.335  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:05.335  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:42:05.335  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:42:05.335  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:05.335  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:05.335  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:42:05.335  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:42:05.335  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:42:05.336   873  1314 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 14:42:05.337   873  1316 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
09-12 14:42:05.338  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:42:05.338  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:05.338  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:05.338  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:05.338  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:42:05.338  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:42:05.338  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:05.338  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:05.338  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:42:05.338  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:42:05.338  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:42:05.341  1869  2302 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 14:42:05.374   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 14:42:05.398   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 14:42:05.399   873  1316 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-12 14:42:05.399   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:42:05.402   873   890 D Tethering: MasterInitialState.processMessage what=3
,09-12 14:42:05.411  2050  2050 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,09-12 14:42:05.413  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:42:05.413  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:05.413  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:05.413  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:05.413  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:42:05.413  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:42:05.413  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:05.413  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:05.413  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:42:05.414  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 14:42:05.414  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:05.414  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:05.414  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:05.414  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:42:05.414  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:42:05.414  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:05.414  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:05.414  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:42:05.419  1706  1706 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 14:42:05.421  1706  1706 D SystemUpdateService: onCreate
09-12 14:42:05.425  1706  1706 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 14:42:05.434  1706  1706 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-12 14:42:05.436  1706  2529 I iu.UploadsManager: num queued entries: 0
,09-12 14:42:05.436  1706  2529 I iu.UploadsManager: num updated entries: 0
09-12 14:42:05.437  1706  2529 I iu.SyncManager: NEXT; no task
,09-12 14:42:05.442  1706  1706 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 14:42:05.444  1706  1706 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 14:42:05.446  3946  3946 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:42:05.450  3946  3946 D SprintDMHelper: simOperator: 
,09-12 14:42:05.450  3946  3946 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 14:42:05.449  1706  4075 I SystemUpdateService: active receiver: enabled
,09-12 14:42:05.494  1706  4075 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 14:42:05.504   372   871 E Netd    : netlink response contains error (No such file or directory)
,09-12 14:42:05.527  1706  4075 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,09-12 14:42:05.527  1706  4075 I SystemUpdateService: now status is 0 (complete)
09-12 14:42:05.527  1706  4075 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-12 14:42:05.527  1706  4075 I SystemUpdateService: file has been verified
09-12 14:42:05.528  1706  4075 I SystemUpdateService: OTA package size = 12249756
,09-12 14:42:05.537  1706  4075 I SystemUpdateService: showing system update notification
,09-12 14:42:05.562  1706  1706 D SystemUpdateService: onDestroy
,09-12 14:42:05.608  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 14:42:05.639  1501  3225 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidsecure
,09-12 14:42:05.639  1501  3225 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidsecure without consulting the cloud.
09-12 14:42:05.639  1501  3225 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 14:42:05.639  1501  3225 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 14:42:05.670  3532  3532 D Finsky  : [1] AppStatesReplicator.handleContentSyncResponse: Completed 1 account content syncs with 0 successful.,
09-12 14:42:05.670  3532  3532 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication failed.
,09-12 14:42:05.670  3532  3532 D Finsky  : [1] ContentSyncService$5.onFinished: Scheduling replication attempt 4.
,09-12 14:42:08.195   873  4045 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,09-12 14:42:08.197   873  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 14:42:08.317   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5881214:true
,09-12 14:42:08.318  3932  3932 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 14:42:08.323  3932  3932 I bt_bluedroid: init
,09-12 14:42:08.324  3932  4082 I BluetoothAdapterState: Entering OffState
,09-12 14:42:08.329  3932  4083 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 14:42:08.330  3932  4083 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 14:42:08.330  3932  4083 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-12 14:42:08.330  3932  4083 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 14:42:08.332  3932  3932 I bt_bluedroid: get_profile_interface socket
,09-12 14:42:08.335  3932  3932 I bt_bluedroid: get_profile_interface sdp
,09-12 14:42:08.336  3932  4086 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
09-12 14:42:08.338  3932  4086 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 14:42:08.339  3932  3943 I bt_bluedroid: config_hci_snoop_log
,09-12 14:42:08.342   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 14:42:08.349  3932  4082 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 14:42:08.349  3932  4082 D BluetoothAdapterProperties: Setting state to 14
09-12 14:42:08.350  3932  4082 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 14:42:08.355  3932  4082 D BluetoothBondStateMachine: make
,09-12 14:42:08.358  3932  4087 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 14:42:08.364  3932  4082 I BluetoothAdapterState: Entering PendingCommandState
,09-12 14:42:08.365  3932  3932 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 14:42:08.368  3932  3932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36fe698
,09-12 14:42:08.370  3932  3932 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 14:42:08.370  3932  3932 D BtGatt.GattService: Received start request. Starting profile...
09-12 14:42:08.371  3932  3932 D BtGatt.GattService: start()
,09-12 14:42:08.371  3932  3932 I bt_bluedroid: get_profile_interface gatt
,09-12 14:42:08.372  3932  3932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36fe698
,09-12 14:42:08.372  3932  3932 D BtGatt.AdvertiseManager: advertise manager created
09-12 14:42:08.381  3932  3932 V BluetoothAdapterState: isTurningOff()=false
,09-12 14:42:08.382  3932  3932 V BluetoothAdapterState: isTurningOn()=false
09-12 14:42:08.382  3932  3932 V BluetoothAdapterState: isBleTurningOn()=true
09-12 14:42:08.382  3932  3932 V BluetoothAdapterState: isBleTurningOff()=false
09-12 14:42:08.383  3932  4082 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-12 14:42:08.383  2218  4063 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
09-12 14:42:08.383  3932  4082 I bt_bluedroid: enable
09-12 14:42:08.384  2218  4063 I Babel   : connection state changed from DISCONNECTED to CONNECTED
09-12 14:42:08.384  3932  4083 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-12 14:42:08.385  3932  4083 I bt_hci  : start_up
09-12 14:42:08.385  2218  4063 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-12 14:42:08.405  3932  4083 I bt_vendor: alloc value 0xb39f9189
,09-12 14:42:08.405  3932  4083 I bt_vendor: init
09-12 14:42:08.406  3932  4083 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-12 14:42:08.406  3932  4083 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 14:42:08.514  3932  4083 D bt_hci  : start_up starting async portion
,09-12 14:42:08.515  3932  4090 I bt_hci  : event_finish_startup
09-12 14:42:08.515  3932  4090 I bt_hci_h4: hal_open
09-12 14:42:08.515  3932  4090 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 14:42:08.525  3932  4090 I bt_userial_vendor: device fd = 51 open
,09-12 14:42:08.555  3932  4090 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 14:42:08.587  3932  4090 D bt_hwcfg: Chipset BCM4354A2
,09-12 14:42:08.587  3932  4090 D bt_hwcfg: Target name = [BCM4354A2]
09-12 14:42:08.588  3932  4090 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 14:42:09.260  3932  4090 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 14:42:09.261  3932  4090 D bt_hwcfg: Settlement delay -- 100 ms
09-12 14:42:09.261  3932  4090 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 14:42:09.378  3932  4090 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 14:42:09.379  3932  4090 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 14:42:09.409  3932  4090 I bt_hwcfg: vendor lib fwcfg completed
,09-12 14:42:09.409  3932  4090 I bt_vendor: firmware callback
09-12 14:42:09.409  3932  4090 I bt_hci  : firmware_config_callback
,09-12 14:42:09.421  3932  4092 I bt_btu  : btu_task pending for preload complete event
,09-12 14:42:09.421  3932  4092 I bt_btu_task: Bluetooth chip preload is complete
09-12 14:42:09.421  3932  4092 I bt_btu  : btu_task received preload complete event
,09-12 14:42:09.431  3932  4092 I         : BTE_InitTraceLevels -- TRC_HCI
,09-12 14:42:09.431  3932  4092 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 14:42:09.431  3932  4092 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 14:42:09.432  3932  4092 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 14:42:09.432  3932  4092 I         : BTE_InitTraceLevels -- TRC_AVRC
09-12 14:42:09.432  3932  4092 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 14:42:09.432  3932  4092 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 14:42:09.433  3932  4092 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 14:42:09.433  3932  4092 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 14:42:09.433  3932  4092 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 14:42:09.433  3932  4092 I         : BTE_InitTraceLevels -- TRC_SDP
09-12 14:42:09.434  3932  4092 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 14:42:09.434  3932  4092 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 14:42:09.434  3932  4092 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 14:42:09.435  3932  4092 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 14:42:09.569  3932  4092 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3976d9d
,09-12 14:42:09.569  3932  4092 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3976d9d 
,09-12 14:42:09.601  3932  4086 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 14:42:09.602  3932  4086 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 14:42:09.603  3932  4086 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 14:42:09.606  3932  4086 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 14:42:09.609  3932  4086 D BluetoothAdapterProperties: Scan Mode:20
09-12 14:42:09.610  3932  4086 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 14:42:09.611  3932  4086 D bt_hci  : do_postload posting postload work item
09-12 14:42:09.612  3932  4090 I bt_hci  : event_postload
,09-12 14:42:09.612  3932  4090 I bt_vendor: sco_config_cb
09-12 14:42:09.612  3932  4090 I bt_hci  : sco_config_callback postload finished.
09-12 14:42:09.614  3932  4086 D bt_bte_conf: Device ID record 1 : primary
,09-12 14:42:09.614  3932  4086 D bt_bte_conf:   vendorId            = 000f
,09-12 14:42:09.615  3932  4086 D bt_bte_conf:   vendorIdSource      = 0001
09-12 14:42:09.615  3932  4086 D bt_bte_conf:   product             = 1200
09-12 14:42:09.615  3932  4086 D bt_bte_conf:   version             = 1436
09-12 14:42:09.615  3932  4086 D bt_bte_conf:   clientExecutableURL = 
09-12 14:42:09.615  3932  4086 D bt_bte_conf:   serviceDescription  = 
,09-12 14:42:09.616  3932  4086 D bt_bte_conf:   documentationURL    = 
,09-12 14:42:09.616  3932  4086 D bt_bte_conf: bte_load_did_conf no section named DID2.,
09-12 14:42:09.617  3932  4083 D bt_stack_manager: event_start_up_stack finished
,09-12 14:42:09.618  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:42:09.619  3932  4082 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,09-12 14:42:09.620  3932  4082 D BluetoothAdapterProperties: Setting state to 15
,09-12 14:42:09.620  3932  4082 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-12 14:42:09.622  3932  4090 I bt_vendor: low_power_mode_cb
09-12 14:42:09.623  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:42:09.623  3932  4082 I BluetoothAdapterState: Entering BleOnState
,09-12 14:42:09.625  3932  4082 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-12 14:42:09.625  3932  4082 D BluetoothAdapterProperties: Setting state to 11
09-12 14:42:09.625  3932  4082 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-12 14:42:09.632  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:42:09.637  3932  3932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36fe698
09-12 14:42:09.637  3932  3932 D HeadsetService: Received start request. Starting profile...
09-12 14:42:09.638  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:09.640  3932  3932 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-12 14:42:09.641  3932  3932 D HeadsetStateMachine: make
,09-12 14:42:09.652  3932  3932 D HeadsetStateMachine: max_hf_connections = 1
09-12 14:42:09.653  3932  3932 I bt_bluedroid: get_profile_interface handsfree
09-12 14:42:09.653  3932  4086 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-12 14:42:09.653  3932  4086 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,09-12 14:42:09.655  3932  4082 I BluetoothAdapterState: Entering PendingCommandState
,09-12 14:42:09.659  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 14:42:09.660  3932  3932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36fe698
09-12 14:42:09.660  3932  3932 D A2dpService: Received start request. Starting profile...
09-12 14:42:09.661  3932  3932 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-12 14:42:09.661  3932  3932 I bt_bluedroid: get_profile_interface avrcp
,09-12 14:42:09.667  3932  3932 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 14:42:09.667  3932  3932 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 14:42:09.667  3932  3932 D A2dpStateMachine: make
,09-12 14:42:09.668  3932  3932 I bt_bluedroid: get_profile_interface a2dp
,09-12 14:42:09.669  3932  3932 I BluetoothHidServiceJni: classInitNative: succeeds
09-12 14:42:09.670  3932  3932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36fe698
,09-12 14:42:09.670  3932  4102 D A2dpStateMachine: Enter Disconnected: -2
09-12 14:42:09.671  3932  3932 D HidService: Received start request. Starting profile...
09-12 14:42:09.671  3932  3932 I bt_bluedroid: get_profile_interface hidhost
09-12 14:42:09.671  3932  4086 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
09-12 14:42:09.671  3932  3932 D HidService: setHidService(): set to: null
09-12 14:42:09.671  3932  4086 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39583e5
09-12 14:42:09.672  3932  4086 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-12 14:42:09.672  3854  3854 D BluetoothInputDevice: Proxy object connected
,09-12 14:42:09.672  3932  3932 I BluetoothHealthServiceJni: classInitNative: succeeds
09-12 14:42:09.673  3932  3932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36fe698
09-12 14:42:09.673  3932  3932 D HealthService: Received start request. Starting profile...
09-12 14:42:09.673  3854  3854 D HidProfile: Bluetooth service connected
09-12 14:42:09.675  3932  3932 I bt_bluedroid: get_profile_interface health
,09-12 14:42:09.675  3932  3932 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 14:42:09.676  3932  3932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36fe698
,09-12 14:42:09.676  3932  3932 D PanService: Received start request. Starting profile...
09-12 14:42:09.677  3854  3854 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 14:42:09.677  3932  3932 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 14:42:09.677  3932  3932 I bt_bluedroid: get_profile_interface pan
09-12 14:42:09.677  3932  4086 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-12 14:42:09.678  3854  3854 D PanProfile: Bluetooth service connected
09-12 14:42:09.679  3932  3932 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36fe698
09-12 14:42:09.679  3932  3932 D BluetoothMapService: Received start request. Starting profile...
09-12 14:42:09.679  3932  3932 D BluetoothMapService: start()
,09-12 14:42:09.680  3854  3854 D BluetoothMap: Proxy object connected
09-12 14:42:09.680  3854  3854 D MapProfile: Bluetooth service connected
,09-12 14:42:09.681  3854  3854 D BluetoothMap: getConnectedDevices()
09-12 14:42:09.681  3932  3932 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-12 14:42:09.681  3932  3932 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-12 14:42:09.682  3932  3932 D BluetoothMapAppObserver: createReceiver()
09-12 14:42:09.682  3932  3932 D BluetoothMapAppObserver: initObservers()
09-12 14:42:09.682  3932  3932 D BluetoothMapAppObserver: getEnabledAccountItems()
09-12 14:42:09.682  3854  3854 D BluetoothMap: Bluetooth is Not enabled
,09-12 14:42:09.686  3932  3932 V BluetoothAdapterState: isTurningOff()=false
,09-12 14:42:09.686  3932  3932 V BluetoothAdapterState: isTurningOn()=true
09-12 14:42:09.686  3932  3932 V BluetoothAdapterState: isBleTurningOn()=false
09-12 14:42:09.686  3932  3932 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 14:42:09.687  3932  4100 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-12 14:42:09.687  3932  3932 V BluetoothAdapterState: isTurningOff()=false
,09-12 14:42:09.687  3932  3932 V BluetoothAdapterState: isTurningOn()=true
,09-12 14:42:09.687  3932  3932 V BluetoothAdapterState: isBleTurningOn()=false
09-12 14:42:09.688  3932  3932 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 14:42:09.688  3932  3932 V BluetoothAdapterState: isTurningOff()=false
09-12 14:42:09.688  3932  3932 V BluetoothAdapterState: isTurningOn()=true
,09-12 14:42:09.688  3932  3932 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 14:42:09.688  3932  3932 V BluetoothAdapterState: isBleTurningOff()=false
09-12 14:42:09.688  3932  3932 V BluetoothAdapterState: isTurningOff()=false
09-12 14:42:09.688  3932  3932 V BluetoothAdapterState: isTurningOn()=true
09-12 14:42:09.688  3932  3932 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 14:42:09.688  3932  3932 V BluetoothAdapterState: isBleTurningOff()=false
09-12 14:42:09.688  3932  3932 V BluetoothAdapterState: isTurningOff()=false
09-12 14:42:09.688  3932  3932 V BluetoothAdapterState: isTurningOn()=true
09-12 14:42:09.688  3932  3932 V BluetoothAdapterState: isBleTurningOn()=false
09-12 14:42:09.688  3932  3932 V BluetoothAdapterState: isBleTurningOff()=false
09-12 14:42:09.688  3932  3932 V BluetoothAdapterState: isTurningOff()=false
09-12 14:42:09.688  3932  3932 V BluetoothAdapterState: isTurningOn()=true
09-12 14:42:09.688  3932  3932 V BluetoothAdapterState: isBleTurningOn()=false
09-12 14:42:09.688  3932  3932 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 14:42:09.689  3932  4082 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-12 14:42:09.689  3932  4082 D BluetoothAdapterProperties: ScanMode =  20
09-12 14:42:09.689  3932  4082 D BluetoothAdapterProperties: State =  11
09-12 14:42:09.689  3932  4082 D BluetoothAdapterProperties: Setting state to 12
09-12 14:42:09.689  3932  4082 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 14:42:09.689   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 14:42:09.690  3932  4082 I BluetoothAdapterState: Entering OnState,
09-12 14:42:09.690  3932  4086 D BluetoothAdapterProperties: Scan Mode:21
09-12 14:42:09.690  3932  4086 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 14:42:09.693  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:09.693  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:09.693  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:09.693  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:42:09.693  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:09.693  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:09.693  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:09.693  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 14:42:09.695  3854  3867 D BluetoothPan: onBluetoothStateChange on: true
09-12 14:42:09.695  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 14:42:09.696  1366  1393 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 14:42:09.696   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 14:42:09.696  3854  3865 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 14:42:09.696   873   873 D BluetoothA2dp: Proxy object connected
09-12 14:42:09.696  1366  2082 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 14:42:09.698  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:09.698  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:09.698  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:09.698  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:42:09.698  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:09.698  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:09.698  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:09.698  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 14:42:09.698  1366  3781 D BluetoothPan: onBluetoothStateChange on: true
09-12 14:42:09.699  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 14:42:09.699  1366  1366 D PanProfile: Bluetooth service connected
09-12 14:42:09.700  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:42:09.700  3854  3867 D BluetoothMap: onBluetoothStateChange: up=true
09-12 14:42:09.700  1366  1382 D BluetoothMap: onBluetoothStateChange: up=true
09-12 14:42:09.702  1366  1366 D BluetoothMap: Proxy object connected
09-12 14:42:09.702  1366  1366 D MapProfile: Bluetooth service connected
09-12 14:42:09.702  1366  1366 D BluetoothMap: getConnectedDevices()
09-12 14:42:09.703  1968  2126 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 14:42:09.704  1366  2082 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 14:42:09.706  1366  1366 D BluetoothInputDevice: Proxy object connected
09-12 14:42:09.706  1366  1366 D HidProfile: Bluetooth service connected
09-12 14:42:09.706   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 14:42:09.706  3854  3865 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 14:42:09.707  3932  3932 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 14:42:09.707  3932  3932 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-12 14:42:09.708  1366  3781 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 14:42:09.708  3932  3932 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 14:42:09.710   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 14:42:09.710  1366  1366 D BluetoothA2dp: Proxy object connected
09-12 14:42:09.710  3932  3932 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 14:42:09.712  3932  3932 D ObexServerSockets: Succeed to create listening sockets 
,09-12 14:42:09.712  3932  3932 D ObexServerSockets0: startAccept()
09-12 14:42:09.712   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
09-12 14:42:09.712  3932  3932 D ObexServerSockets0: prepareForNewConnect()
,09-12 14:42:09.713  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:09.714  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:09.716  3932  3932 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-12 14:42:09.716  3932  4108 D ObexServerSockets0: Accepting socket connection...
09-12 14:42:09.716  3932  3932 D BluetoothSdpJni: SDP Create record success - handle: 0
09-12 14:42:09.716  3932  4109 D ObexServerSockets0: Accepting socket connection...
,09-12 14:42:09.716  3932  3932 D BluetoothMapService: onReceive
09-12 14:42:09.716  3932  3932 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:42:09.716  3932  3932 D BluetoothMapService: STATE_ON
,09-12 14:42:09.719  3854  3854 D LocalBluetoothProfileManager: Adding local A2DP profile
,09-12 14:42:09.722  3854  3854 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-12 14:42:09.726  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 14:42:09.730  3854  3854 D BluetoothA2dp: Proxy object connected
,09-12 14:42:09.732  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 14:42:09.737  3854  3854 D DockEventReceiver: finishStartingService: stopping service
,09-12 14:42:09.740  1366  1366 D BluetoothPbap: Proxy object connected
,09-12 14:42:09.740  1366  1366 D PbapServerProfile: Bluetooth service connected
09-12 14:42:09.740  3854  3854 D BluetoothPbap: Proxy object connected
,09-12 14:42:09.740  3854  3854 D PbapServerProfile: Bluetooth service connected
,09-12 14:42:09.745  3932  3932 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 14:42:09.745  3932  3932 D ObexServerSockets0: prepareForNewConnect()
,09-12 14:42:09.747  3932  4113 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 14:42:09.761  3932  4117 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 14:42:09.762  3932  4117 I BtOppRfcommListener: Accept thread started.
,09-12 14:42:09.797   873   873 D BluetoothHeadset: Proxy object connected
,09-12 14:42:09.798  1968  1982 D BluetoothHeadset: Proxy object connected
09-12 14:42:09.798   873   873 D BluetoothHeadset: Proxy object connected
09-12 14:42:09.798   873   873 D BluetoothHeadset: Proxy object connected
09-12 14:42:09.798  1366  3781 D BluetoothHeadset: Proxy object connected
09-12 14:42:09.798  1366  1366 D HeadsetProfile: Bluetooth service connected
,09-12 14:42:09.803  1968  3218 D BluetoothHeadset: Proxy object connected
,09-12 14:42:09.806   873   890 D BluetoothHeadset: Proxy object connected
,09-12 14:42:09.811   873   890 D BluetoothHeadset: Proxy object connected
,09-12 14:42:09.824  3854  3865 D BluetoothHeadset: Proxy object connected
,09-12 14:42:09.825  3854  3854 D HeadsetProfile: Bluetooth service connected
,09-12 14:42:11.183   873  1316 D ConnectivityService: handlePromptUnvalidated 101
,09-12 14:42:11.280  3932  4082 D BluetoothAdapterState: Current state: ON, message: 23
,09-12 14:42:11.280  3932  4082 D BluetoothAdapterProperties: Setting state to 13
09-12 14:42:11.280  3932  4082 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 14:42:11.282  3932  4082 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 14:42:11.285  3932  4082 I BluetoothAdapterState: Entering PendingCommandState
09-12 14:42:11.290  3932  3932 D BluetoothMapService: onReceive
,09-12 14:42:11.290  3932  3932 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:42:11.290  3932  3932 D BluetoothMapService: STATE_TURNING_OFF
09-12 14:42:11.291  3932  3932 D BluetoothMapService: MAP Service closeService in
09-12 14:42:11.292  3932  3932 D BluetoothMapMasInstance0: MAP Service shutdown
09-12 14:42:11.292  3932  3932 D ObexServerSockets0: shutdown(block = true)
09-12 14:42:11.293  3932  4108 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-12 14:42:11.296  3932  3932 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-12 14:42:11.296  3932  3932 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-12 14:42:11.297  3932  4109 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-12 14:42:11.297  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:42:11.297  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:11.297  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:11.297  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:11.297  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:42:11.297  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:42:11.297  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:11.297  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:11.297  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:42:11.298  3932  4095 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-12 14:42:11.300  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:42:11.300  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:42:11.303  3932  3932 I BtOppRfcommListener: stopping Accept Thread
09-12 14:42:11.303  3932  4117 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 14:42:11.304  3932  4117 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-12 14:42:11.308  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 14:42:11.308  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:11.308  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:11.308  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:11.308  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:42:11.308  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 14:42:11.308  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:11.308  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:11.308  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 14:42:11.310  3932  4086 D BluetoothAdapterProperties: Scan Mode:20
09-12 14:42:11.310  3932  4082 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
09-12 14:42:11.311  3782  3782 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 14:42:11.311  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:42:11.315  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:42:11.316  3932  3932 D HeadsetService: Received stop request...Stopping profile...
09-12 14:42:11.318  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:11.320   873   873 D BluetoothHeadset: Proxy object disconnected
,09-12 14:42:11.321  1968  1990 D BluetoothHeadset: Proxy object disconnected
09-12 14:42:11.322  3932  3932 D A2dpService: Received stop request...Stopping profile...
09-12 14:42:11.322  3932  4102 D A2dpStateMachine: Exit Disconnected: -1
09-12 14:42:11.322   873   873 D BluetoothHeadset: Proxy object disconnected
,09-12 14:42:11.323  3854  3867 D BluetoothHeadset: Proxy object disconnected
09-12 14:42:11.323   873   873 D BluetoothHeadset: Proxy object disconnected
09-12 14:42:11.324  1366  1393 D BluetoothHeadset: Proxy object disconnected
,09-12 14:42:11.326  3932  3932 V BluetoothAdapterState: isTurningOff()=true
09-12 14:42:11.326  3932  3932 V BluetoothAdapterState: isTurningOn()=false
09-12 14:42:11.326  3932  3932 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 14:42:11.327  3932  3932 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 14:42:11.327   873   873 D BluetoothA2dp: Proxy object disconnected
,09-12 14:42:11.327  3932  3932 D HidService: Received stop request...Stopping profile...
,09-12 14:42:11.327  3932  3932 D HidService: Stopping Bluetooth HidService
09-12 14:42:11.328  1366  1366 D HeadsetProfile: Bluetooth service disconnected
,09-12 14:42:11.329  1366  1366 D BluetoothA2dp: Proxy object disconnected
09-12 14:42:11.330  1366  1366 D BluetoothInputDevice: Proxy object disconnected
09-12 14:42:11.330  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 14:42:11.330  1366  1366 D HidProfile: Bluetooth service disconnected
09-12 14:42:11.330  3932  3932 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 14:42:11.330  3932  4092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 14:42:11.330  3932  4092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 14:42:11.330  3932  4092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 14:42:11.331  3932  4086 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-12 14:42:11.331  3932  3932 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 14:42:11.331  3932  4086 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
,09-12 14:42:11.332  3932  3932 D HealthService: Received stop request...Stopping profile...
09-12 14:42:11.334  3932  3932 D PanService: Received stop request...Stopping profile...
09-12 14:42:11.336  1366  1366 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 14:42:11.336  1366  1366 D PanProfile: Bluetooth service disconnected
09-12 14:42:11.334  3854  3854 D HeadsetProfile: Bluetooth service disconnected
,09-12 14:42:11.336  3932  3932 D BluetoothMapService: Received stop request...Stopping profile...
09-12 14:42:11.336  3932  3932 D BluetoothMapService: stop()
09-12 14:42:11.336  3854  3854 D BluetoothA2dp: Proxy object disconnected
09-12 14:42:11.336  3854  3854 D BluetoothInputDevice: Proxy object disconnected
09-12 14:42:11.337  3932  3932 D BluetoothMapAppObserver: deinitObservers()
09-12 14:42:11.337  3854  3854 D HidProfile: Bluetooth service disconnected
09-12 14:42:11.337  3932  3932 D BluetoothMapAppObserver: removeReceiver()
09-12 14:42:11.338  1366  1366 D BluetoothMap: Proxy object disconnected
,09-12 14:42:11.338  1366  1366 D MapProfile: Bluetooth service disconnected
09-12 14:42:11.338  3932  3932 V BluetoothAdapterState: isTurningOff()=true
09-12 14:42:11.338  3932  3932 V BluetoothAdapterState: isTurningOn()=false
09-12 14:42:11.338  3932  3932 V BluetoothAdapterState: isBleTurningOn()=false
09-12 14:42:11.339  3932  3932 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 14:42:11.340  3932  4086 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-12 14:42:11.340  3932  4092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 14:42:11.340  3932  4092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 14:42:11.340  3932  4092 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 14:42:11.340  3932  4092 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 14:42:11.340  3932  4092 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 14:42:11.340  3932  4092 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 14:42:11.341  3932  3932 V BluetoothAdapterState: isTurningOff()=true
09-12 14:42:11.341  3932  3932 V BluetoothAdapterState: isTurningOn()=false
09-12 14:42:11.341  3932  3932 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 14:42:11.341  3932  3932 V BluetoothAdapterState: isBleTurningOff()=false
09-12 14:42:11.341  3932  3932 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 14:42:11.342  3932  4086 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-12 14:42:11.341  3932  3932 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 14:42:11.342  3932  3932 V BluetoothAdapterState: isTurningOff()=true
09-12 14:42:11.342  3932  3932 V BluetoothAdapterState: isTurningOn()=false
09-12 14:42:11.342  3932  3932 V BluetoothAdapterState: isBleTurningOn()=false
09-12 14:42:11.342  3932  3932 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 14:42:11.342  3932  3932 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 14:42:11.342  3854  3854 D DockEventReceiver: finishStartingService: stopping service
09-12 14:42:11.343  3932  4086 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-12 14:42:11.343  3932  3932 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 14:42:11.343  3932  3932 V BluetoothAdapterState: isTurningOff()=true
09-12 14:42:11.343  3932  3932 V BluetoothAdapterState: isTurningOn()=false
09-12 14:42:11.343  3932  3932 V BluetoothAdapterState: isBleTurningOn()=false
09-12 14:42:11.343  3932  3932 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 14:42:11.344  3854  3854 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 14:42:11.345  3932  3932 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 14:42:11.347  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 14:42:11.344  3854  3854 D PanProfile: Bluetooth service disconnected
09-12 14:42:11.348  3932  3932 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-12 14:42:11.348  3854  3854 D BluetoothMap: Proxy object disconnected
09-12 14:42:11.348  3854  3854 D MapProfile: Bluetooth service disconnected
09-12 14:42:11.349  3932  3932 D BluetoothMapService: MAP Service closeService in
,09-12 14:42:11.349  3932  3932 V BluetoothAdapterState: isTurningOff()=true
09-12 14:42:11.349  3932  3932 V BluetoothAdapterState: isTurningOn()=false
09-12 14:42:11.349  3932  3932 V BluetoothAdapterState: isBleTurningOn()=false
09-12 14:42:11.349  3932  3932 V BluetoothAdapterState: isBleTurningOff()=false
09-12 14:42:11.349  3932  4082 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-12 14:42:11.349  3932  4082 D BluetoothAdapterProperties: Setting state to 15
09-12 14:42:11.349  3932  3932 D BluetoothMapService: cleanup()
,09-12 14:42:11.349  3932  3932 D BluetoothMapService: MAP Service closeService in
09-12 14:42:11.349  3932  4082 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-12 14:42:11.350  3932  4082 I BluetoothAdapterState: Entering BleOnState
,09-12 14:42:11.356  3854  3854 D BluetoothPbap: Proxy object disconnected
,09-12 14:42:11.356   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 14:42:11.356  1366  1366 D BluetoothPbap: Proxy object disconnected
09-12 14:42:11.356  1366  1366 D PbapServerProfile: Bluetooth service disconnected
,09-12 14:42:11.359  3854  3867 D BluetoothPan: onBluetoothStateChange on: false
,09-12 14:42:11.360  1366  1382 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 14:42:11.360   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 14:42:11.360  3854  3865 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 14:42:11.360  3854  3867 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 14:42:11.363  1366  2079 D BluetoothPbap: onBluetoothStateChange: up=false
,09-12 14:42:11.356  3854  3854 D PbapServerProfile: Bluetooth service disconnected
09-12 14:42:11.364  1366  2082 D BluetoothPan: onBluetoothStateChange on: false
,09-12 14:42:11.364  3854  3865 D BluetoothMap: onBluetoothStateChange: up=false
,09-12 14:42:11.365  1366  1393 D BluetoothMap: onBluetoothStateChange: up=false
09-12 14:42:11.365  1968  2126 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 14:42:11.365  1366  3781 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 14:42:11.366  3854  3867 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 14:42:11.366   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
09-12 14:42:11.366  3854  3865 D BluetoothPbap: onBluetoothStateChange: up=false
,09-12 14:42:11.367  1366  1382 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 14:42:11.367   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-12 14:42:11.367  3932  4082 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-12 14:42:11.367  3932  4082 D BluetoothAdapterProperties: Setting state to 16
09-12 14:42:11.368  3932  4082 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-12 14:42:11.370  3932  4082 D BluetoothAdapterProperties: onBleDisable
09-12 14:42:11.370  3932  4082 I BluetoothAdapterState: Entering PendingCommandState
09-12 14:42:11.370  3932  4083 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-12 14:42:11.372  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:11.372  3932  4092 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 14:42:11.372  3932  4092 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-12 14:42:11.373  3932  4086 D BluetoothAdapterProperties: Scan Mode:20
,09-12 14:42:11.373  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 14:42:11.373  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:11.374  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:42:11.375  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:42:11.377  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-12 14:42:11.379  3854  3854 D DockEventReceiver: finishStartingService: stopping service
,09-12 14:42:11.573  3932  4086 I bt_hci  : shut_down
,09-12 14:42:11.574  3932  4090 D bt_hwcfg: hw_epilog_process
,09-12 14:42:11.576  3932  4090 I bt_vendor: low_power_mode_cb
,09-12 14:42:11.602  3932  4090 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-12 14:42:11.602  3932  4090 I bt_vendor: epilog_cb
09-12 14:42:11.603  3932  4090 I bt_hci  : epilog_finished_callback
,09-12 14:42:11.614  3932  4086 I bt_hci_h4: hal_close
,09-12 14:42:11.615  3932  4086 I bt_userial_vendor: device fd = 51 close
,09-12 14:42:11.732  3932  4083 D bt_stack_manager: event_shut_down_stack finished.
,09-12 14:42:11.732  3932  4082 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-12 14:42:11.740  3932  4082 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-12 14:42:11.741  3932  3932 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 14:42:11.742  3932  3932 D BtGatt.GattService: Received stop request...Stopping profile...
,09-12 14:42:11.743  3932  3932 D BtGatt.GattService: stop()
,09-12 14:42:11.743  3932  3932 D BtGatt.AdvertiseManager: advertise clients cleared
,09-12 14:42:11.750  3932  3932 V BluetoothAdapterState: isTurningOff()=false
,09-12 14:42:11.751  3932  3932 V BluetoothAdapterState: isTurningOn()=false
,09-12 14:42:11.751  3932  3932 V BluetoothAdapterState: isBleTurningOn()=false
09-12 14:42:11.752  3932  3932 V BluetoothAdapterState: isBleTurningOff()=true
09-12 14:42:11.753  3932  4082 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-12 14:42:11.754  3932  4082 D BluetoothAdapterProperties: Setting state to 10
09-12 14:42:11.755  3932  4082 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-12 14:42:11.758  3932  4082 I BluetoothAdapterState: Entering OffState
09-12 14:42:11.758   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-12 14:42:11.784  3932  3932 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
09-12 14:42:11.785  3932  3932 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-12 14:42:11.785  3932  4083 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-12 14:42:11.788  3932  3932 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 14:42:11.796  3932  4083 D bt_stack_manager: event_clean_up_stack finished.
,09-12 14:42:11.801  3932  3932 I art     : System.exit called, status: 0
,09-12 14:42:11.802  3932  3932 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 14:42:11.862   873  2023 I ActivityManager: Process com.android.bluetooth (pid 3932) has died
,09-12 14:42:14.277  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 14:42:14.277  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:42:16.141   873   893 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,09-12 14:42:16.152  1901  1901 I Keyboard.Facilitator: onFinishInput()
,09-12 14:42:16.159   873   893 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-12 14:42:16.159   873   893 I Adreno  : Build Date                       : 10/20/15
09-12 14:42:16.159   873   893 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-12 14:42:16.159   873   893 I Adreno  : Local Branch                     : M14
09-12 14:42:16.159   873   893 I Adreno  : Remote Branch                    : 
09-12 14:42:16.159   873   893 I Adreno  : Remote Branch                    : 
09-12 14:42:16.159   873   893 I Adreno  : Reconstruct Branch               : 
,09-12 14:42:16.202   280  2336 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (190 us)
,09-12 14:42:16.829  3782  3782 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 14:42:16.829  3782  3782 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-12 14:42:16.865   873   893 V KeyguardServiceDelegate: onScreenTurnedOff()
,09-12 14:42:16.867  3782  3782 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bc8d444 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3026d6e, 16908290=android.view.AbsSavedState$1@3026d6e}, android:focusedViewId=100}]}]
09-12 14:42:16.867  3782  3782 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-12 14:42:16.867  3782  3782 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-12 14:42:16.867  3782  3782 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED,
09-12 14:42:16.871   873   893 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
,09-12 14:42:16.879   280   280 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6ae4000
,09-12 14:42:16.879   873   891 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
09-12 14:42:16.879   280   280 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,09-12 14:42:16.903   873   882 I art     : Background partial concurrent mark sweep GC freed 18203(1564KB) AllocSpace objects, 14(488KB) LOS objects, 33% free, 29MB/43MB, paused 1.020ms total 110.236ms
,09-12 14:42:17.103   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,09-12 14:42:17.107   280   280 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,09-12 14:42:17.113   873  1340 D SurfaceControl: Excessive delay in setPowerMode(): 234ms
,09-12 14:42:17.116   873   893 I DreamManagerService: Entering dreamland.
,09-12 14:42:17.117   873   893 I PowerManagerService: Dozing...
,09-12 14:42:17.119   873   888 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,09-12 14:42:17.180   376  1287 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,09-12 14:42:17.181   376  1287 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,09-12 14:42:17.186   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 14:42:17.192   873  1314 E native  : do suspend false
,09-12 14:42:17.200  1957  4127 D NfcService: Discovery configuration equal, not updating.
,09-12 14:42:17.229   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 14:42:17.237   873  1314 E native  : do suspend true
,09-12 14:42:17.284  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 14:42:17.285  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6744c0f added. We now have 6 listener(s)
09-12 14:42:17.286  3782  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:42:17.290  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 14:42:17.290  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@14b249c added. We now have 7 listener(s)
09-12 14:42:17.290  3782  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:42:17.292  3782  3832 I System.out: IsBluetoothEnabled
,09-12 14:42:17.302  3782  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:17.318   376   376 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,09-12 14:42:17.319   376   376 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,09-12 14:42:17.356   873   890 I ActivityManager: Start proc 4131:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-12 14:42:17.477  4131  4131 D AdapterServiceConfig: Adding HeadsetService
,09-12 14:42:17.477  4131  4131 D AdapterServiceConfig: Adding A2dpService
,09-12 14:42:17.478  4131  4131 D AdapterServiceConfig: Adding HidService
,09-12 14:42:17.478  4131  4131 D AdapterServiceConfig: Adding HealthService
,09-12 14:42:17.478  4131  4131 D AdapterServiceConfig: Adding PanService
,09-12 14:42:17.478  4131  4131 D AdapterServiceConfig: Adding GattService
,09-12 14:42:17.479  4131  4131 D AdapterServiceConfig: Adding BluetoothMapService
,09-12 14:42:17.495   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1cec86c:true
,09-12 14:42:17.496  4131  4131 D BluetoothAdapterState: make() - Creating AdapterState
,09-12 14:42:17.501  4131  4131 I bt_bluedroid: init
,09-12 14:42:17.502  4131  4145 I BluetoothAdapterState: Entering OffState
,09-12 14:42:17.508  4131  4146 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-12 14:42:17.508  4131  4146 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-12 14:42:17.508  4131  4146 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-12 14:42:17.509  4131  4146 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-12 14:42:17.510  4131  4131 I bt_bluedroid: get_profile_interface socket
09-12 14:42:17.512  4131  4131 I bt_bluedroid: get_profile_interface sdp
,09-12 14:42:17.517  4131  4144 I bt_bluedroid: config_hci_snoop_log
09-12 14:42:17.517  4131  4149 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 14:42:17.519   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-12 14:42:17.520  4131  4149 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 14:42:17.528  4131  4145 D BluetoothAdapterState: Current state: OFF, message: 0
,09-12 14:42:17.529  4131  4145 D BluetoothAdapterProperties: Setting state to 14
09-12 14:42:17.529  4131  4145 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-12 14:42:17.533  4131  4145 D BluetoothBondStateMachine: make
,09-12 14:42:17.538  4131  4150 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 14:42:17.545  4131  4145 I BluetoothAdapterState: Entering PendingCommandState
,09-12 14:42:17.546  4131  4131 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-12 14:42:17.549  4131  4131 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36fe698
,09-12 14:42:17.550  4131  4131 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 14:42:17.551  4131  4131 D BtGatt.GattService: Received start request. Starting profile...
,09-12 14:42:17.551  4131  4131 D BtGatt.GattService: start()
09-12 14:42:17.551  4131  4131 I bt_bluedroid: get_profile_interface gatt
,09-12 14:42:17.553  4131  4131 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36fe698
09-12 14:42:17.553  4131  4131 D BtGatt.AdvertiseManager: advertise manager created
,09-12 14:42:17.563  4131  4131 V BluetoothAdapterState: isTurningOff()=false
09-12 14:42:17.563  4131  4131 V BluetoothAdapterState: isTurningOn()=false
09-12 14:42:17.563  4131  4131 V BluetoothAdapterState: isBleTurningOn()=true
09-12 14:42:17.563  4131  4131 V BluetoothAdapterState: isBleTurningOff()=false
09-12 14:42:17.564  4131  4145 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-12 14:42:17.564  4131  4145 I bt_bluedroid: enable
,09-12 14:42:17.565  4131  4146 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-12 14:42:17.566  4131  4146 I bt_hci  : start_up
,09-12 14:42:17.586  4131  4146 I bt_vendor: alloc value 0xb3a60189
09-12 14:42:17.586  4131  4146 I bt_vendor: init
,09-12 14:42:17.586  4131  4146 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,09-12 14:42:17.587  4131  4146 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-12 14:42:17.697  4131  4146 D bt_hci  : start_up starting async portion
,09-12 14:42:17.698  4131  4153 I bt_hci  : event_finish_startup
,09-12 14:42:17.698  4131  4153 I bt_hci_h4: hal_open
09-12 14:42:17.698  4131  4153 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-12 14:42:17.710  4131  4153 I bt_userial_vendor: device fd = 51 open
,09-12 14:42:17.739  4131  4153 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 14:42:17.770  4131  4153 D bt_hwcfg: Chipset BCM4354A2
,09-12 14:42:17.771  4131  4153 D bt_hwcfg: Target name = [BCM4354A2]
,09-12 14:42:17.771  4131  4153 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-12 14:42:18.435  4131  4153 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-12 14:42:18.437  4131  4153 D bt_hwcfg: Settlement delay -- 100 ms
,09-12 14:42:18.437  4131  4153 I bt_hwcfg: Setting fw settlement delay to 100 
,09-12 14:42:18.555  4131  4153 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-12 14:42:18.556  4131  4153 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-12 14:42:18.585  4131  4153 I bt_hwcfg: vendor lib fwcfg completed
,09-12 14:42:18.585  4131  4153 I bt_vendor: firmware callback
09-12 14:42:18.585  4131  4153 I bt_hci  : firmware_config_callback
,09-12 14:42:18.598  4131  4157 I bt_btu  : btu_task pending for preload complete event
,09-12 14:42:18.599  4131  4157 I bt_btu_task: Bluetooth chip preload is complete
09-12 14:42:18.599  4131  4157 I bt_btu  : btu_task received preload complete event
,09-12 14:42:18.609  4131  4157 I         : BTE_InitTraceLevels -- TRC_HCI
09-12 14:42:18.610  4131  4157 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-12 14:42:18.610  4131  4157 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-12 14:42:18.611  4131  4157 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 14:42:18.611  4131  4157 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-12 14:42:18.612  4131  4157 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 14:42:18.613  4131  4157 I         : BTE_InitTraceLevels -- TRC_BNEP
,09-12 14:42:18.613  4131  4157 I         : BTE_InitTraceLevels -- TRC_BTM
,09-12 14:42:18.614  4131  4157 I         : BTE_InitTraceLevels -- TRC_GAP
,09-12 14:42:18.614  4131  4157 I         : BTE_InitTraceLevels -- TRC_PAN
,09-12 14:42:18.615  4131  4157 I         : BTE_InitTraceLevels -- TRC_SDP
,09-12 14:42:18.615  4131  4157 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 14:42:18.615  4131  4157 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 14:42:18.615  4131  4157 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 14:42:18.616  4131  4157 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 14:42:18.750  4131  4157 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39ddd9d
09-12 14:42:18.750  4131  4157 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39ddd9d 
,09-12 14:42:18.771  4131  4149 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-12 14:42:18.773  4131  4149 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-12 14:42:18.775  4131  4149 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-12 14:42:18.777  4131  4149 D BluetoothAdapterProperties: Name is: Nexus 6
,09-12 14:42:18.781  4131  4149 D BluetoothAdapterProperties: Scan Mode:20
,09-12 14:42:18.784  4131  4149 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 14:42:18.784  4131  4149 D bt_hci  : do_postload posting postload work item
,09-12 14:42:18.785  4131  4153 I bt_hci  : event_postload
09-12 14:42:18.785  4131  4153 I bt_vendor: sco_config_cb
,09-12 14:42:18.785  4131  4153 I bt_hci  : sco_config_callback postload finished.
,09-12 14:42:18.789  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:42:18.793  4131  4149 D bt_bte_conf: Device ID record 1 : primary
09-12 14:42:18.793  4131  4149 D bt_bte_conf:   vendorId            = 000f
,09-12 14:42:18.793  4131  4149 D bt_bte_conf:   vendorIdSource      = 0001
09-12 14:42:18.793  4131  4149 D bt_bte_conf:   product             = 1200
09-12 14:42:18.793  4131  4149 D bt_bte_conf:   version             = 1436
,09-12 14:42:18.793  4131  4149 D bt_bte_conf:   clientExecutableURL = 
09-12 14:42:18.794  4131  4149 D bt_bte_conf:   serviceDescription  = 
09-12 14:42:18.794  4131  4149 D bt_bte_conf:   documentationURL    = 
09-12 14:42:18.794  4131  4149 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-12 14:42:18.794  4131  4153 I bt_vendor: low_power_mode_cb
09-12 14:42:18.795  4131  4146 D bt_stack_manager: event_start_up_stack finished
,09-12 14:42:18.797  4131  4145 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-12 14:42:18.797  4131  4145 D BluetoothAdapterProperties: Setting state to 15
,09-12 14:42:18.797  4131  4145 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
09-12 14:42:18.799  4131  4145 I BluetoothAdapterState: Entering BleOnState
,09-12 14:42:18.803  4131  4145 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-12 14:42:18.804  4131  4145 D BluetoothAdapterProperties: Setting state to 11
,09-12 14:42:18.804  4131  4145 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-12 14:42:18.810  4131  4131 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36fe698
,09-12 14:42:18.815  4131  4131 D HeadsetService: Received start request. Starting profile...
,09-12 14:42:18.815  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:18.824  4131  4131 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-12 14:42:18.824  4131  4131 D HeadsetStateMachine: make
,09-12 14:42:18.827  4131  4145 I BluetoothAdapterState: Entering PendingCommandState
,09-12 14:42:18.839  4131  4131 D HeadsetStateMachine: max_hf_connections = 1
,09-12 14:42:18.839  4131  4131 I bt_bluedroid: get_profile_interface handsfree
09-12 14:42:18.840  4131  4149 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-12 14:42:18.840  4131  4149 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-12 14:42:18.844  4131  4131 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36fe698
,09-12 14:42:18.845  4131  4131 D A2dpService: Received start request. Starting profile...
,09-12 14:42:18.846  4131  4131 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-12 14:42:18.846  4131  4131 I bt_bluedroid: get_profile_interface avrcp
,09-12 14:42:18.853  4131  4131 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 14:42:18.854  4131  4131 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 14:42:18.854  4131  4131 D A2dpStateMachine: make
,09-12 14:42:18.855  4131  4131 I bt_bluedroid: get_profile_interface a2dp
,09-12 14:42:18.856  4131  4149 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-12 14:42:18.858  4131  4165 D A2dpStateMachine: Enter Disconnected: -2
,09-12 14:42:18.858  4131  4131 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 14:42:18.859  4131  4131 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36fe698
,09-12 14:42:18.860  4131  4131 D HidService: Received start request. Starting profile...
,09-12 14:42:18.860  4131  4131 I bt_bluedroid: get_profile_interface hidhost
,09-12 14:42:18.860  4131  4149 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39bf3e5
,09-12 14:42:18.861  4131  4149 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,09-12 14:42:18.861  4131  4131 D HidService: setHidService(): set to: null
,09-12 14:42:18.863  4131  4131 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-12 14:42:18.864  4131  4131 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36fe698
,09-12 14:42:18.864  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 14:42:18.865  4131  4131 D HealthService: Received start request. Starting profile...
,09-12 14:42:18.867  4131  4131 I bt_bluedroid: get_profile_interface health
,09-12 14:42:18.867  4131  4131 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 14:42:18.868  4131  4131 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36fe698
09-12 14:42:18.869  4131  4131 D PanService: Received start request. Starting profile...
,09-12 14:42:18.869  4131  4131 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-12 14:42:18.869  4131  4131 I bt_bluedroid: get_profile_interface pan
,09-12 14:42:18.870  4131  4149 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 14:42:18.873  4131  4131 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36fe698
09-12 14:42:18.874  4131  4131 D BluetoothMapService: Received start request. Starting profile...
09-12 14:42:18.874  4131  4131 D BluetoothMapService: start()
09-12 14:42:18.876  4131  4131 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
09-12 14:42:18.877  4131  4131 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-12 14:42:18.877  4131  4131 D BluetoothMapAppObserver: createReceiver()
09-12 14:42:18.878  4131  4131 D BluetoothMapAppObserver: initObservers()
09-12 14:42:18.878  4131  4131 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-12 14:42:18.887  4131  4131 V BluetoothAdapterState: isTurningOff()=false
09-12 14:42:18.887  4131  4131 V BluetoothAdapterState: isTurningOn()=true
,09-12 14:42:18.887  4131  4131 V BluetoothAdapterState: isBleTurningOn()=false
09-12 14:42:18.887  4131  4131 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 14:42:18.889  4131  4131 V BluetoothAdapterState: isTurningOff()=false
09-12 14:42:18.889  4131  4131 V BluetoothAdapterState: isTurningOn()=true
,09-12 14:42:18.889  4131  4131 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 14:42:18.889  4131  4131 V BluetoothAdapterState: isBleTurningOff()=false
09-12 14:42:18.889  4131  4131 V BluetoothAdapterState: isTurningOff()=false
09-12 14:42:18.889  4131  4131 V BluetoothAdapterState: isTurningOn()=true
09-12 14:42:18.889  4131  4131 V BluetoothAdapterState: isBleTurningOn()=false
09-12 14:42:18.890  4131  4131 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 14:42:18.890  4131  4163 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 14:42:18.891  4131  4131 V BluetoothAdapterState: isTurningOff()=false
09-12 14:42:18.892  4131  4131 V BluetoothAdapterState: isTurningOn()=true
09-12 14:42:18.892  4131  4131 V BluetoothAdapterState: isBleTurningOn()=false
09-12 14:42:18.892  4131  4131 V BluetoothAdapterState: isBleTurningOff()=false
09-12 14:42:18.893  4131  4131 V BluetoothAdapterState: isTurningOff()=false
,09-12 14:42:18.894  4131  4131 V BluetoothAdapterState: isTurningOn()=true
09-12 14:42:18.894  4131  4131 V BluetoothAdapterState: isBleTurningOn()=false
09-12 14:42:18.895  4131  4131 V BluetoothAdapterState: isBleTurningOff()=false
09-12 14:42:18.896  4131  4131 V BluetoothAdapterState: isTurningOff()=false
09-12 14:42:18.896  4131  4131 V BluetoothAdapterState: isTurningOn()=true
09-12 14:42:18.896  4131  4131 V BluetoothAdapterState: isBleTurningOn()=false
,09-12 14:42:18.896  4131  4131 V BluetoothAdapterState: isBleTurningOff()=false
,09-12 14:42:18.897  4131  4145 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-12 14:42:18.897  4131  4145 D BluetoothAdapterProperties: ScanMode =  20
09-12 14:42:18.897  4131  4145 D BluetoothAdapterProperties: State =  11
09-12 14:42:18.897  4131  4145 D BluetoothAdapterProperties: Setting state to 12
09-12 14:42:18.897  4131  4145 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-12 14:42:18.898   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 14:42:18.899  4131  4149 D BluetoothAdapterProperties: Scan Mode:21
09-12 14:42:18.899  4131  4149 D BluetoothAdapterProperties: Discoverable Timeout:120
09-12 14:42:18.899  4131  4145 I BluetoothAdapterState: Entering OnState
,09-12 14:42:18.901  3854  3865 D BluetoothPan: onBluetoothStateChange on: true
09-12 14:42:18.902   873   873 D BluetoothA2dp: Proxy object connected
,09-12 14:42:18.904  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:18.904  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:18.904  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:18.904  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:42:18.904  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:18.904  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:18.904  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:18.904  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:42:18.906  1366  1393 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 14:42:18.907  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 14:42:18.908  4131  4131 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-12 14:42:18.907   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 14:42:18.908  4131  4131 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-12 14:42:18.908  3854  3867 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 14:42:18.911  4131  4131 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 14:42:18.912  3854  3865 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 14:42:18.914  3854  3854 D BluetoothA2dp: Proxy object connected
,09-12 14:42:18.914  4131  4131 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 14:42:18.915  1366  1382 D BluetoothPbap: onBluetoothStateChange: up=true
09-12 14:42:18.916  4131  4131 D ObexServerSockets: Succeed to create listening sockets 
,09-12 14:42:18.916  4131  4131 D ObexServerSockets0: startAccept()
09-12 14:42:18.916  4131  4131 D ObexServerSockets0: prepareForNewConnect()
09-12 14:42:18.917  1366  3781 D BluetoothPan: onBluetoothStateChange on: true
,09-12 14:42:18.919  3854  3867 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 14:42:18.920  4131  4131 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-12 14:42:18.920  4131  4131 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-12 14:42:18.921  1366  2079 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 14:42:18.922  1366  1366 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 14:42:18.922  1366  1366 D PanProfile: Bluetooth service connected
,09-12 14:42:18.923  4131  4173 D ObexServerSockets0: Accepting socket connection...
09-12 14:42:18.923  1968  1990 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 14:42:18.923  3854  3854 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 14:42:18.923  3854  3854 D PanProfile: Bluetooth service connected
09-12 14:42:18.924  3854  3854 D BluetoothInputDevice: Proxy object connected
09-12 14:42:18.924  3854  3854 D HidProfile: Bluetooth service connected
,09-12 14:42:18.924  1366  1393 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-12 14:42:18.924  1366  1366 D BluetoothMap: Proxy object connected
09-12 14:42:18.924  1366  1366 D MapProfile: Bluetooth service connected
,09-12 14:42:18.924  1366  1366 D BluetoothMap: getConnectedDevices()
09-12 14:42:18.925  4131  4174 D ObexServerSockets0: Accepting socket connection...
09-12 14:42:18.926  3854  3854 D BluetoothMap: Proxy object connected
09-12 14:42:18.926  3854  3865 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 14:42:18.927  1366  1366 D BluetoothInputDevice: Proxy object connected
09-12 14:42:18.928   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
09-12 14:42:18.927  1366  1366 D HidProfile: Bluetooth service connected
09-12 14:42:18.928  3854  4172 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 14:42:18.931  1366  2082 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 14:42:18.932  3854  3854 D MapProfile: Bluetooth service connected
09-12 14:42:18.932  3854  3854 D BluetoothMap: getConnectedDevices()
,09-12 14:42:18.934  1366  1366 D BluetoothA2dp: Proxy object connected
,09-12 14:42:18.934   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-12 14:42:18.937   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
09-12 14:42:18.938  4131  4131 D BluetoothMapService: onReceive
09-12 14:42:18.938  4131  4131 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-12 14:42:18.938  4131  4131 D BluetoothMapService: STATE_ON
09-12 14:42:18.939  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:42:18.944  3854  3854 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 14:42:18.956  3854  3854 D DockEventReceiver: finishStartingService: stopping service
,09-12 14:42:18.956  1501  1501 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-12 14:42:18.966  1366  1366 D BluetoothPbap: Proxy object connected
,09-12 14:42:18.966  3854  3854 D BluetoothPbap: Proxy object connected
09-12 14:42:18.966  3854  3854 D PbapServerProfile: Bluetooth service connected
09-12 14:42:18.966  1366  1366 D PbapServerProfile: Bluetooth service connected
09-12 14:42:18.966  4131  4131 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-12 14:42:18.966  4131  4131 D ObexServerSockets0: prepareForNewConnect()
,09-12 14:42:18.985  4131  4179 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 14:42:19.007  4131  4183 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 14:42:19.008  4131  4183 I BtOppRfcommListener: Accept thread started.
,09-12 14:42:19.010   873   873 D BluetoothHeadset: Proxy object connected
,09-12 14:42:19.010  1968  2126 D BluetoothHeadset: Proxy object connected
,09-12 14:42:19.011   873   873 D BluetoothHeadset: Proxy object connected
,09-12 14:42:19.011  3854  3865 D BluetoothHeadset: Proxy object connected
,09-12 14:42:19.012   873   873 D BluetoothHeadset: Proxy object connected
09-12 14:42:19.012  3854  3854 D HeadsetProfile: Bluetooth service connected
09-12 14:42:19.012  1366  1382 D BluetoothHeadset: Proxy object connected
09-12 14:42:19.012  1366  1366 D HeadsetProfile: Bluetooth service connected
,09-12 14:42:19.025  1968  1982 D BluetoothHeadset: Proxy object connected
,09-12 14:42:19.028  3854  4172 D BluetoothHeadset: Proxy object connected
,09-12 14:42:19.028  3854  3854 D HeadsetProfile: Bluetooth service connected
,09-12 14:42:19.028   873   890 D BluetoothHeadset: Proxy object connected
,09-12 14:42:19.034   873   890 D BluetoothHeadset: Proxy object connected
,09-12 14:42:19.327  3782  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:19.327  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:19.327  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:19.327  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 14:42:19.327  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:19.327  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:19.327  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:19.327  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 14:42:19.334  3782  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 14:42:19.337  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 14:42:19.338  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ece4ea5 added. We now have 8 listener(s)
09-12 14:42:19.338  3782  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:42:19.343   873  1395 D WifiService: setWifiEnabled: false pid=3782, uid=10000
,09-12 14:42:19.344   873  1395 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 14:42:19.355  3782  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:19.356   873   883 D WifiService: setWifiEnabled: true pid=3782, uid=10000
,09-12 14:42:19.357   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-12 14:42:19.372   873  1314 D WifiConfigStore: Loading config and enabling all networks 
,09-12 14:42:19.390  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:19.390  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:19.390  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:19.390  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:42:19.390  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:19.390  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:19.390  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:19.390  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 14:42:19.396  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:42:19.396   873  1314 D WifiConfigStore: loaded 0 passpoint configs
,09-12 14:42:19.398   873  1314 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-12 14:42:19.399   873  1314 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,09-12 14:42:19.399   873  1314 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-12 14:42:19.400   873  1314 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-12 14:42:19.400   873  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-12 14:42:19.400   873  1314 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-12 14:42:19.418   372   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-12 14:42:19.419   873  1314 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.04 rxSuccessRate=0.06 delta 1000 -> 1000
,09-12 14:42:19.419   873  1314 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-12 14:42:19.420   372   871 D CommandListener: Setting iface cfg
,09-12 14:42:19.430   873  1313 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-12 14:42:19.430   873  1313 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-12 14:42:19.430   873  1314 E native  : do suspend true
,09-12 14:42:19.439   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-12 14:42:19.439   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 14:42:19.449   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-12 14:42:19.484   873  1313 D WifiNative-HAL: p2pGetDeviceAddress
,09-12 14:42:19.485   873  1313 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-12 14:42:19.529   873  1314 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-12 14:42:19.532  1466  1466 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-12 14:42:19.959  1466  1466 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-12 14:42:19.999  1466  1466 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 14:42:19.999  1466  1466 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-12 14:42:20.003   873  1314 D WifiConfigStore: Retrieve network priorities after PNO.
,09-12 14:42:20.023   873  1314 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-12 14:42:20.024   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-12 14:42:20.024   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-12 14:42:20.040   873  1314 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 14:42:20.048   372   871 D CommandListener: Setting iface cfg
,09-12 14:42:20.049   873  1314 D WifiStateMachine: Start Dhcp Watchdog 3
,09-12 14:42:20.055   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-12 14:42:20.098   873  4191 D DhcpClient: Receive thread started
,09-12 14:42:20.183   873  1314 E native  : do suspend false
,09-12 14:42:20.204   873  2102 D DhcpClient: Broadcasting DHCPDISCOVER
,09-12 14:42:20.217   873  4191 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
,09-12 14:42:20.219   873  2102 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,09-12 14:42:20.223   873  2102 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-12 14:42:20.237   873  4191 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-12 14:42:20.238   873  2102 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-12 14:42:20.243   372   871 D CommandListener: Setting iface cfg
,09-12 14:42:20.257   873  2102 D DhcpClient: Scheduling renewal in 86399s
,09-12 14:42:20.258   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
09-12 14:42:20.260   873  1314 E native  : do suspend true
,09-12 14:42:20.281   873  1314 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-12 14:42:20.282   873  1314 D WifiConfigStore: No blacklist allowed without epno enabled
09-12 14:42:20.283   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
09-12 14:42:20.284   873  1314 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 14:42:20.287   873  1316 D ConnectivityService: Adding iface wlan0 to network 102
,09-12 14:42:20.362   873  1316 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-12 14:42:20.362   873  1316 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,09-12 14:42:20.364   873  1316 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-12 14:42:20.365   873  1316 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-12 14:42:20.366   873  1316 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-12 14:42:20.376   873  1316 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-12 14:42:20.379  3782  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:20.379  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:20.379  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:20.379  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:42:20.379  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:20.379  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 14:42:20.379  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 14:42:20.379  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 14:42:20.381   873  1316 D ConnectivityService: scheduleUnvalidatedPrompt 102
09-12 14:42:20.382   873  1316 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-12 14:42:20.382   873  1314 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-12 14:42:20.382  3782  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 14:42:20.383   873  1314 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-12 14:42:20.383   873  1316 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
09-12 14:42:20.383   873  1316 D ConnectivityService:    accepting network in place of null
09-12 14:42:20.384   873  1316 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-12 14:42:20.388  3782  3832 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-12 14:42:20.389  3782  3832 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-12 14:42:20.392  3782  3832 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@bc8d444 Bundle[{}]
,09-12 14:42:20.393  3782  3832 I io.jxcore.node.LifeCycleMonitor: start: OK
09-12 14:42:20.393  3782  3832 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-12 14:42:20.393  3782  3832 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-12 14:42:20.394  3782  3832 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 14:42:20.395  3782  3832 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-12 14:42:20.396  3782  3832 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 14:42:20.399  3782  3832 I System.out: Running OutgoingSocketThread
09-12 14:42:20.400   873  4190 D NetlinkSocketObserver: NeighborEvent{elapsedMs=154501, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-12 14:42:20.400  3782  4196 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 411)
,09-12 14:42:20.401  3782  4196 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44293
,09-12 14:42:20.401  3782  4196 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 14:42:20.418   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 14:42:20.450   372   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-12 14:42:20.454   873  1316 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-12 14:42:20.454   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:42:20.460   873   890 D Tethering: MasterInitialState.processMessage what=3
09-12 14:42:20.461   873  1316 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,09-12 14:42:20.477  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 14:42:20.477  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:20.477  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:20.477  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:42:20.477  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:20.477  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:42:20.477  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:42:20.477  3782  3782 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:42:20.480  3782  3782 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 14:42:20.482  2050  2050 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,09-12 14:42:20.486   873  4189 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,09-12 14:42:20.489  1706  1706 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-12 14:42:20.495  1706  1706 D SystemUpdateService: onCreate
,09-12 14:42:20.502  1706  1706 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-12 14:42:20.512  1706  4201 I SystemUpdateService: active receiver: enabled
,09-12 14:42:20.519  1706  4201 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-12 14:42:20.522  1706  1706 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-12 14:42:20.528  1706  4201 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,09-12 14:42:20.528  1706  4201 I SystemUpdateService: now status is 0 (complete)
09-12 14:42:20.528  1706  4201 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-12 14:42:20.528  1706  4201 I SystemUpdateService: file has been verified
,09-12 14:42:20.528  1706  4201 I SystemUpdateService: OTA package size = 12249756
,09-12 14:42:20.530  1706  2529 I iu.UploadsManager: num queued entries: 0
,09-12 14:42:20.536  1706  2529 I iu.UploadsManager: num updated entries: 0
09-12 14:42:20.537  1706  2529 I iu.SyncManager: NEXT; no task
,09-12 14:42:20.538  1706  1706 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-12 14:42:20.540  1706  1706 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-12 14:42:20.543  3946  3946 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-12 14:42:20.549  3946  3946 D SprintDMHelper: simOperator: 
,09-12 14:42:20.549  3946  3946 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-12 14:42:20.554   873  4189 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 12:42:20 GMT], X-Android-Received-Millis=[1473684140553], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473684140527]}
,09-12 14:42:20.556   873  1316 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-12 14:42:20.556   873  1316 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-12 14:42:20.556   873  1316 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
09-12 14:42:20.559   873  1316 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 14:42:20.574  1706  4204 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-12 14:42:20.574  1706  4204 W BaseAppContext: Using Auth Proxy for data requests.
,09-12 14:42:20.587  1706  4204 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,09-12 14:42:20.591  1706  4201 I SystemUpdateService: showing system update notification
,09-12 14:42:20.593  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 14:42:20.596  1501  1501 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-12 14:42:20.624  1706  1706 D SystemUpdateService: onDestroy
,09-12 14:42:20.642  1501  2420 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,09-12 14:42:20.642  1501  2420 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-12 14:42:20.642  1501  2420 I GLSUser : [GLSUser] Extracting token using key: Auth
09-12 14:42:20.642  1501  2420 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-12 14:42:20.659  1706  4204 E MDM     : [177] SitrepService.a: Error sending sitrep.
,09-12 14:42:20.684  2218  4207 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-12 14:42:21.402  3782  3832 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 412)
09-12 14:42:21.403  3782  3832 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 412)
,09-12 14:42:21.412  3782  3832 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 417)
,09-12 14:42:21.415  3782  3832 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-12 14:42:21.415  3782  3832 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 418)
,09-12 14:42:21.420  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:42:21.420  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26bf27a added. We now have 2 listener(s)
,09-12 14:42:21.422  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 14:42:21.422  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:42:21.422  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:42:21.422  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 14:42:21.423  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@339a2b added. We now have 9 listener(s)
09-12 14:42:21.423  3782  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:42:21.423  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 14:42:21.427  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:42:21.434  3782  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:42:21.434  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:21.434  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:21.434  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:42:21.434  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:21.434  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:42:21.434  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:42:21.434  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:42:21.436  3782  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 14:42:21.436  3782  3832 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 14:42:21.436  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:42:21.436  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fa3021 added. We now have 3 listener(s)
09-12 14:42:21.438  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 14:42:21.438  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 14:42:21.438  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:42:21.439  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:42:21.439  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bc46 added. We now have 10 listener(s)
,09-12 14:42:21.439  3782  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:42:21.439  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:42:21.439  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:42:21.439  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 14:42:21.439  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:42:21.439  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:21.439  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:42:21.439  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 14:42:21.440  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26bf27a removed from the list
09-12 14:42:21.440  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:21.440  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@339a2b removed from the list
,09-12 14:42:21.442  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:42:21.442  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:42:21.443  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:42:21.443  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:21.443  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:42:21.444  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 14:42:21.444  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 14:42:21.444  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:21.445  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@339a2b not in the list
09-12 14:42:21.445  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:21.445  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:42:21.446  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:42:21.446  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:42:21.446  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:21.446  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7b6bc46 removed from the list
,09-12 14:42:21.446  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:42:21.446  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:42:21.446  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:42:21.446  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:42:21.446  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fa3021 removed from the list
,09-12 14:42:21.447  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:42:21.447  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4fae07 added. We now have 2 listener(s),
09-12 14:42:21.449  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-12 14:42:21.449  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:42:21.449  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 14:42:21.449  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 14:42:21.449  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5d6b34 added. We now have 9 listener(s)
,09-12 14:42:21.450  3782  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:42:21.450  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 14:42:21.453  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:42:21.455   873  1316 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
09-12 14:42:21.462  3782  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:42:21.462  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:21.462  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:21.462  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:42:21.462  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:21.462  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:42:21.462  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:42:21.462  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:42:21.464  3782  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:42:21.464  3782  3832 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 14:42:21.464  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:42:21.465  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e9256d2 added. We now have 3 listener(s)
09-12 14:42:21.467  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:42:21.467  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 14:42:21.468  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:42:21.468  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:42:21.468  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:42:21.468  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32f23a3 added. We now have 10 listener(s)
09-12 14:42:21.468  3782  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:42:21.468  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 14:42:21.469  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 14:42:21.469  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 14:42:21.469  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:42:21.469  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 14:42:21.470  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relev,ant state changes
,09-12 14:42:21.472  3782  3832 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 14:42:21.472  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 14:42:21.476  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 14:42:21.477  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 14:42:21.477  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 14:42:21.480  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 14:42:21.480  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 14:42:21.480  3782  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 14:42:21.481  3782  3832 D BluetoothAdapter: STATE_ON
,09-12 14:42:21.484  4131  4170 D BtGatt.GattService: registerClient() - UUID=da09e9e1-80a6-4be2-b455-db851292de97
,09-12 14:42:21.484  4131  4149 D BtGatt.GattService: onClientRegistered() - UUID=da09e9e1-80a6-4be2-b455-db851292de97, clientIf=5
,09-12 14:42:21.485  3782  3793 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 14:42:21.486  4131  4144 D BtGatt.GattService: start scan with filters
,09-12 14:42:21.490  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 14:42:21.490  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 14:42:21.490  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 14:42:21.490  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
09-12 14:42:21.490  4131  4152 D BtGatt.ScanManager: handling starting scan
,09-12 14:42:21.492  4131  4152 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@36fe698
,09-12 14:42:21.493  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 14:42:21.493  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 14:42:21.494  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 14:42:21.495  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 14:42:21.498  3782  3832 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 14:42:21.498  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 14:42:21.498  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 14:42:21.498  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:21.498  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 14:42:21.498  4131  4149 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 14:42:21.500  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts,
09-12 14:42:21.500  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 14:42:21.500  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 14:42:21.500  4131  4149 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 14:42:21.500  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
09-12 14:42:21.500  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 14:42:21.500  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 14:42:21.501  4131  4152 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-12 14:42:21.501  3782  3832 D BluetoothAdapter: STATE_ON
09-12 14:42:21.502  4131  4170 D BtGatt.GattService: stopScan() - queue size =1
09-12 14:42:21.503  4131  4171 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 14:42:21.503  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 14:42:21.503  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 14:42:21.503  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 14:42:21.503  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 14:42:21.503  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 14:42:21.505  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 14:42:21.505  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
09-12 14:42:21.505  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 14:42:21.505  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
09-12 14:42:21.506  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:42:21.507  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
09-12 14:42:21.508  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 14:42:21.508  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 14:42:21.509  4131  4149 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 14:42:21.509  4131  4149 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 14:42:21.509  4131  4152 D BtGatt.ScanManager: Starting BLE batch scan
09-12 14:42:21.510  4131  4152 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 14:42:21.510  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:42:21.510  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:42:21.510  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:42:21.511  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:42:21.511  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:21.511  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 14:42:21.512  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:42:21.512  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a4fae07 removed from the list
09-12 14:42:21.512  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:21.512  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5d6b34 removed from the list
,09-12 14:42:21.513  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:42:21.513  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:42:21.514  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:21.514  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 14:42:21.516  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:42:21.516  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:42:21.516  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:21.516  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b5d6b34 not in the list
,09-12 14:42:21.517  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:21.517  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:42:21.518  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 14:42:21.518  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:42:21.518  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:21.518  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32f23a3 removed from the list
09-12 14:42:21.518  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 14:42:21.518  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:21.518  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:42:21.519  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:42:21.519  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e9256d2 removed from the list
,09-12 14:42:21.519  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:42:21.520  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f0656ff added. We now have 2 listener(s)
09-12 14:42:21.521  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 14:42:21.522  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 14:42:21.522  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:42:21.522  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:42:21.522  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6eeccc added. We now have 9 listener(s)
09-12 14:42:21.522  3782  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:42:21.523  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 14:42:21.523  4131  4149 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-12 14:42:21.523  4131  4149 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 14:42:21.525  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:42:21.530  4131  4149 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-12 14:42:21.530  4131  4149 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 14:42:21.531  3782  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:42:21.531  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:21.531  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:21.531  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:42:21.531  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:21.531  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:42:21.531  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:42:21.531  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:42:21.534  3782  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 14:42:21.534  3782  3832 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 14:42:21.534  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:42:21.534  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e5ee2a added. We now have 3 listener(s)
09-12 14:42:21.536  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 14:42:21.537  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:42:21.537  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 14:42:21.537  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 14:42:21.537  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:42:21.537  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f3641b added. We now have 10 listener(s)
,09-12 14:42:21.537  3782  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:42:21.537  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 14:42:21.539  4131  4149 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-12 14:42:21.539  4131  4149 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 14:42:21.539  4131  4152 D BtGatt.ScanManager: stopping BLe Batch
,09-12 14:42:21.539  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:21.540  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 14:42:21.540  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-12 14:42:21.540  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-12 14:42:21.540  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:42:21.540  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 14:42:21.543  3782  3832 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-12 14:42:21.543  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
09-12 14:42:21.547  4131  4149 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 14:42:21.547  4131  4149 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 14:42:21.547  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 14:42:21.547  4131  4152 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-12 14:42:21.547  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 14:42:21.547  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 14:42:21.551  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 14:42:21.551  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 14:42:21.551  3782  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 14:42:21.551  3782  3832 D BluetoothAdapter: STATE_ON
,09-12 14:42:21.552  4131  4149 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 14:42:21.553  4131  4149 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 14:42:21.554  4131  4143 D BtGatt.GattService: registerClient() - UUID=76a19f0c-4c2e-4eb7-b9f6-9d6f172ae73f
,09-12 14:42:21.554  4131  4149 D BtGatt.GattService: onClientRegistered() - UUID=76a19f0c-4c2e-4eb7-b9f6-9d6f172ae73f, clientIf=5
09-12 14:42:21.554  3782  3793 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-12 14:42:21.555  4131  4175 D BtGatt.GattService: start scan with filters
,09-12 14:42:21.557  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 14:42:21.557  4131  4152 D BtGatt.ScanManager: handling starting scan
,09-12 14:42:21.557  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 14:42:21.557  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 14:42:21.557  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 14:42:21.559  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 14:42:21.559  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 14:42:21.560  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 14:42:21.561  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 14:42:21.563  4131  4149 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 14:42:21.563  4131  4149 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 14:42:21.563  4131  4152 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 14:42:21.563  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 14:42:21.563  3782  3832 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-12 14:42:21.563  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:42:21.563  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:42:21.563  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:42:21.564  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:42:21.564  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:42:21.564  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 14:42:21.564  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:42:21.564  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f0656ff removed from the list
09-12 14:42:21.564  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:21.564  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6eeccc removed from the list
09-12 14:42:21.564  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:42:21.564  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 14:42:21.565  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:21.565  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-12 14:42:21.565  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:21.565  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 14:42:21.565  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:42:21.566  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 14:42:21.566  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:21.566  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6eeccc not in the list
09-12 14:42:21.566  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 14:42:21.566  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 14:42:21.566  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 14:42:21.566  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 14:42:21.566  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-12 14:42:21.567  3782  3832 D BluetoothAdapter: STATE_ON
09-12 14:42:21.567  4131  4175 D BtGatt.GattService: stopScan() - queue size =1
09-12 14:42:21.568  4131  4170 D BtGatt.GattService: unregisterClient() - clientIf=5
09-12 14:42:21.568  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 14:42:21.568  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 14:42:21.568  4131  4149 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-12 14:42:21.568  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 14:42:21.568  4131  4149 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 14:42:21.568  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 14:42:21.568  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 14:42:21.568  4131  4152 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 14:42:21.568  4131  4152 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-12 14:42:21.569  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 14:42:21.569  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 14:42:21.569  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 14:42:21.569  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...,
,09-12 14:42:21.569  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:42:21.570  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 14:42:21.570  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 14:42:21.570  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 14:42:21.570  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:42:21.570  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 14:42:21.570  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:21.571  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6f3641b removed from the list
09-12 14:42:21.571  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 14:42:21.571  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:21.571  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:42:21.571  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:42:21.571  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8e5ee2a removed from the list
09-12 14:42:21.572  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:42:21.572  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dda26f7 added. We now have 2 listener(s)
09-12 14:42:21.573  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 14:42:21.573  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 14:42:21.573  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:42:21.573  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:42:21.573  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7cc0964 added. We now have 9 listener(s)
09-12 14:42:21.573  3782  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:42:21.574  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 14:42:21.576  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:42:21.579  4131  4149 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 14:42:21.579  4131  4149 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 14:42:21.579  3782  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:42:21.579  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:21.579  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:21.579  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:42:21.579  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:21.579  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:42:21.579  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:42:21.579  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 14:42:21.581  3782  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:42:21.581  3782  3832 D io.jxcore.node.ConnectivityMonitor: start: OK,
,09-12 14:42:21.581  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 14:42:21.582  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7a1882 added. We now have 3 listener(s)
09-12 14:42:21.583  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 14:42:21.583  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:42:21.583  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 14:42:21.583  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:42:21.583  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7003b93 added. We now have 10 listener(s),
09-12 14:42:21.583  3782  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:42:21.583  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 14:42:21.583  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 14:42:21.583  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-12 14:42:21.583  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 14:42:21.583  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 14:42:21.585  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:21.595  3782  3832 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-12 14:42:21.595  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 14:42:21.596  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 14:42:21.596  4131  4149 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 14:42:21.596  4131  4149 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 14:42:21.600  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 14:42:21.602  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-12 14:42:21.602  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 14:42:21.603  4131  4149 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 14:42:21.604  4131  4149 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 14:42:21.604  4131  4152 D BtGatt.ScanManager: stopping BLe Batch
,09-12 14:42:21.608  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 14:42:21.608  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 14:42:21.608  3782  3832 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
09-12 14:42:21.609  3782  3832 D BluetoothAdapter: STATE_ON
,09-12 14:42:21.611  4131  4144 D BtGatt.GattService: registerClient() - UUID=f73955b1-6fea-470e-8c1b-87910315b419
,09-12 14:42:21.612  4131  4149 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-12 14:42:21.612  4131  4149 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 14:42:21.612  4131  4152 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 14:42:21.614  4131  4149 D BtGatt.GattService: onClientRegistered() - UUID=f73955b1-6fea-470e-8c1b-87910315b419, clientIf=5
09-12 14:42:21.614  3782  3794 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-12 14:42:21.614  4131  4143 D BtGatt.GattService: start scan with filters
09-12 14:42:21.617  4131  4149 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-12 14:42:21.617  4131  4149 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 14:42:21.617  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 14:42:21.617  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 14:42:21.617  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-12 14:42:21.618  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 14:42:21.618  4131  4152 D BtGatt.ScanManager: handling starting scan
,09-12 14:42:21.621  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 14:42:21.621  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 14:42:21.621  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 14:42:21.623  4131  4149 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-12 14:42:21.623  4131  4149 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 14:42:21.623  4131  4152 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-12 14:42:21.623  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 14:42:21.627  4131  4149 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-12 14:42:21.627  4131  4149 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 14:42:21.627  4131  4152 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 14:42:21.627  4131  4152 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-12 14:42:21.630  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 14:42:21.631  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:42:21.631  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 14:42:21.631  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 14:42:21.631  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:21.631  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-12 14:42:21.631  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:42:21.631  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dda26f7 removed from the list
,09-12 14:42:21.632  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:21.632  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7cc0964 removed from the list
09-12 14:42:21.632  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:42:21.632  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 14:42:21.633  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:42:21.633  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,09-12 14:42:21.633  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:42:21.633  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 14:42:21.634  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 14:42:21.634  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 14:42:21.634  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:42:21.634  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7cc0964 not in the list
09-12 14:42:21.634  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
09-12 14:42:21.634  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 14:42:21.634  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 14:42:21.635  4131  4149 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-12 14:42:21.635  4131  4149 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 14:42:21.640  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 14:42:21.640  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 14:42:21.651  3782  3832 D BluetoothAdapter: STATE_ON
,09-12 14:42:21.652  4131  4144 D BtGatt.GattService: stopScan() - queue size =1
,09-12 14:42:21.652  4131  4143 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-12 14:42:21.653  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 14:42:21.653  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-12 14:42:21.653  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 14:42:21.653  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 14:42:21.653  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 14:42:21.654  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 14:42:21.654  4131  4149 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-12 14:42:21.654  4131  4149 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 14:42:21.654  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 14:42:21.654  3782  3832 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 14:42:21.654  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-12 14:42:21.655  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:42:21.658  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 14:42:21.659  3782  3782 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 14:42:21.659  3782  3782 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 14:42:21.659  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:42:21.660  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:42:21.660  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 14:42:21.660  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7003b93 removed from the list
,09-12 14:42:21.661  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:42:21.661  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:21.661  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:42:21.661  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:42:21.662  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d7a1882 removed from the list
,09-12 14:42:21.662  4131  4149 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-12 14:42:21.662  4131  4149 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 14:42:21.662  4131  4152 D BtGatt.ScanManager: stopping BLe Batch
09-12 14:42:21.662  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 14:42:21.662  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a68fdef added. We now have 2 listener(s)
09-12 14:42:21.664  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 14:42:21.664  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:42:21.664  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 14:42:21.664  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:42:21.664  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed20fc added. We now have 9 listener(s)
09-12 14:42:21.664  3782  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 14:42:21.665  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 14:42:21.667  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 14:42:21.668  4131  4149 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-12 14:42:21.668  4131  4149 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-12 14:42:21.668  4131  4152 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-12 14:42:21.671  3782  3832 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 14:42:21.671  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 14:42:21.671  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 14:42:21.671  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 14:42:21.671  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 14:42:21.671  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 14:42:21.671  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 14:42:21.671  3782  3832 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 14:42:21.672  4131  4149 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-12 14:42:21.672  4131  4149 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-12 14:42:21.673  3782  3832 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 14:42:21.673  3782  3832 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 14:42:21.675  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:21.673  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 14:42:21.675  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6e35da added. We now have 3 listener(s)
,09-12 14:42:21.676  3782  3782 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 14:42:21.676  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-12 14:42:21.677  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 14:42:21.677  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 14:42:21.677  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 14:42:21.677  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f18a0b added. We now have 10 listener(s)
09-12 14:42:21.677  3782  3832 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 14:42:21.677  3782  3832 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 14:42:21.677  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 14:42:21.677  3782  3832 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 14:42:21.677  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:42:21.677  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:21.678  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 14:42:21.678  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:42:21.678  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a68fdef removed from the list
09-12 14:42:21.678  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:42:21.678  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed20fc removed from the list
09-12 14:42:21.678  3782  3832 D io.jxcore.node.ConnectivityMonitor: stop
09-12 14:42:21.678  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:42:21.678  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 14:42:21.678  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:42:21.679  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:42:21.679  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:42:21.679  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:42:21.679  3782  3832 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ed20fc not in the list
09-12 14:42:21.679  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:42:21.679  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:42:21.680  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 14:42:21.680  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 14:42:21.680  3782  3832 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 14:42:21.680  3782  3832 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f18a0b removed from the list
09-12 14:42:21.680  3782  3832 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 14:42:21.680  3782  3832 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 14:42:21.680  3782  3832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 14:42:21.680  3782  3832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 14:42:21.681  3782  3832 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6e35da removed from the list
09-12 14:42:21.681  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-12 14:42:21.681  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 14:42:21.682  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-12 14:42:21.682  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 14:42:21.682  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 14:42:21.682  3782  3832 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 14:42:21.687  3782  4215 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: My test thread name)
,09-12 14:42:21.687  3782  4215 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 425, thread name: My test thread name)
09-12 14:42:21.687  3782  4215 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 425, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-12 14:42:21.688  3782  4216 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: My test thread name)
,09-12 14:42:21.689  3782  4216 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 427, thread name: My test thread name)
09-12 14:42:21.689  3782  4216 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 427, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-12 14:42:21.690  3782  3832 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,09-12 14:42:21.690  3782  3832 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-12 14:42:21.690  3782  3832 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-12 14:42:21.690  3782  3832 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-12 14:42:21.690  3782  3832 D com.test.thalitest.ThaliTestRunner: Total duration: 22912 ms
,09-12 14:42:21.692  3782  3832 I jxcore-log: *Native tests were executed*
09-12 14:42:21.692  3782  3832 I jxcore-log: 
,09-12 14:42:21.692  3782  3832 I jxcore-log: Total number of executed tests:  80
09-12 14:42:21.692  3782  3832 I jxcore-log: 
09-12 14:42:21.692  3782  3832 I jxcore-log: Number of passed tests:  80
09-12 14:42:21.692  3782  3832 I jxcore-log: 
09-12 14:42:21.693  3782  3832 I jxcore-log: Number of failed tests:  0
09-12 14:42:21.693  3782  3832 I jxcore-log: 
,09-12 14:42:21.693  3782  3832 I jxcore-log: Number of ignored tests:  0
09-12 14:42:21.693  3782  3832 I jxcore-log: 
09-12 14:42:21.693  3782  3832 I jxcore-log: Total duration:  22912
09-12 14:42:21.693  3782  3832 I jxcore-log: 
09-12 14:42:21.693  3782  3832 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-12 14:42:21.693  3782  3832 I jxcore-log: 
,09-12 14:42:21.697  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:42:21.697  3782  3832 I jxcore-log: 
09-12 14:42:21.700  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:42:21.700  3782  3832 I jxcore-log: 
09-12 14:42:21.701  3782  3782 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-12 14:42:21.702  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:42:21.702  3782  3832 I jxcore-log: 
09-12 14:42:21.703  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:42:21.703  3782  3832 I jxcore-log: 
09-12 14:42:21.704  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:42:21.704  3782  3832 I jxcore-log: 
09-12 14:42:21.705  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:42:21.705  3782  3832 I jxcore-log: 
,09-12 14:42:21.707  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 14:42:21.707  3782  3832 I jxcore-log: 
,09-12 14:42:21.709  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:42:21.709  3782  3832 I jxcore-log: 
,09-12 14:42:21.710  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 14:42:21.710  3782  3832 I jxcore-log: 
,09-12 14:42:21.710  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 14:42:21.710  3782  3832 I jxcore-log: 
,09-12 14:42:21.711  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 14:42:21.711  3782  3832 I jxcore-log: 
,09-12 14:42:21.713  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 14:42:21.713  3782  3832 I jxcore-log: 
,09-12 14:42:21.714  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 14:42:21.714  3782  3832 I jxcore-log: 
,09-12 14:42:21.715  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:42:21.715  3782  3832 I jxcore-log: 
,09-12 14:42:21.715  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:42:21.715  3782  3832 I jxcore-log: 
09-12 14:42:21.716  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 14:42:21.716  3782  3832 I jxcore-log: 
09-12 14:42:21.717  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 14:42:21.717  3782  3832 I jxcore-log: 
09-12 14:42:21.717  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 14:42:21.717  3782  3832 I jxcore-log: 
,09-12 14:42:21.718  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 14:42:21.718  3782  3832 I jxcore-log: 
,09-12 14:42:21.719  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 14:42:21.719  3782  3832 I jxcore-log: 
,09-12 14:42:21.720  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 14:42:21.720  3782  3832 I jxcore-log: 
,09-12 14:42:21.721  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 14:42:21.721  3782  3832 I jxcore-log: 
,09-12 14:42:21.722  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 14:42:21.722  3782  3832 I jxcore-log: 
,09-12 14:42:21.722  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 14:42:21.722  3782  3832 I jxcore-log: 
,09-12 14:42:21.723  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 14:42:21.723  3782  3832 I jxcore-log: 
,09-12 14:42:21.723  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:42:21.723  3782  3832 I jxcore-log: 
,09-12 14:42:21.724  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:42:21.724  3782  3832 I jxcore-log: 
,09-12 14:42:21.725  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:42:21.725  3782  3832 I jxcore-log: 
,09-12 14:42:21.725  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:42:21.725  3782  3832 I jxcore-log: 
,09-12 14:42:21.726  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:42:21.726  3782  3832 I jxcore-log: 
,09-12 14:42:21.726  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 14:42:21.726  3782  3832 I jxcore-log: 
,09-12 14:42:22.008  3782  3782 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 14:42:22.011  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 14:42:22.011  3782  3832 I jxcore-log: 
,09-12 14:42:22.070  3782  3782 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 14:42:22.073  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 14:42:22.073  3782  3832 I jxcore-log: 
,09-12 14:42:22.159  3782  3782 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 14:42:22.163  3782  3832 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 14:42:22.163  3782  3832 I jxcore-log: 
,09-12 14:42:22.224  1869  2660 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-12 14:42:22.357  4218  4218 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,09-12 14:42:22.362  4218  4218 D AndroidRuntime: CheckJNI is OFF
,09-12 14:42:22.405  4218  4218 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,09-12 14:42:22.452  4218  4218 I Radio-JNI: register_android_hardware_Radio DONE
,09-12 14:42:22.474  4218  4218 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-12 14:42:22.487   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,09-12 14:42:22.488   873   886 I ActivityManager: Killing 3782:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,09-12 14:42:22.591   873  1397 I WindowState: WIN DEATH: Window{6ef694f u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-12 14:42:22.594   873  1315 D WifiService: Client connection lost with reason: 4
,09-12 14:42:22.594   873   884 D GraphicsStats: Buffer count: 2
,09-12 14:42:22.602   873   896 W PackageSettings: Skipping PackageSetting{d10fa85 com.example.hello/10273} due to missing metadata
,09-12 14:42:22.644   873   886 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,09-12 14:42:22.644   873   886 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,09-12 14:42:22.645   873   886 E ActivityManager: Failure starting process com.test.thalitest
09-12 14:42:22.645   873   886 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-12 14:42:22.645   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-12 14:42:22.645   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-12 14:42:22.645   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-12 14:42:22.645   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-12 14:42:22.645   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-12 14:42:22.645   873   886 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-12 14:42:22.645   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-12 14:42:22.645   873   886 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-12 14:42:22.645   873   886 E ActivityManager: 	,at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-12 14:42:22.645   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-12 14:42:22.645   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-12 14:42:22.645   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-12 14:42:22.645   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-12 14:42:22.645   873   886 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-12 14:42:22.645   873   886 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:22.645   873   886 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 14:42:22.645   873   886 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 14:42:22.645   873   886 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 14:42:22.646   873   886 I ActivityManager:   Force finishing activity ActivityRecord{cd3a4e4 u0 com.test.thalitest/.MainActivity t4}
,09-12 14:42:22.646   873   896 I art     : Starting a blocking GC Explicit
,09-12 14:42:22.666   873  1988 W ActivityManager: Spurious death for ProcessRecord{62f68c1 0:com.test.thalitest/u0a0}, curProc for 3782: null
,09-12 14:42:22.689   873   896 I art     : Explicit concurrent mark sweep GC freed 13635(953KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 840us total 42.643ms
,09-12 14:42:22.720   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,09-12 14:42:22.725  4218  4218 I art     : System.exit called, status: 0
,09-12 14:42:22.725  4218  4218 I AndroidRuntime: VM exiting with result code 0.,
,09-12 14:42:22.735   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,09-12 14:42:22.764   873   886 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,09-12 14:42:22.772  4131  4131 D BluetoothMapAppObserver: onReceive
,09-12 14:42:22.772  4131  4131 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,09-12 14:42:22.775  1901  1901 I Keyboard.Facilitator: resetDictionaries() : en_US
,09-12 14:42:22.777  1869  2250 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-12 14:42:22.779  3624  3624 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-12 14:42:22.783   873  1306 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-12 14:42:22.794   873  2023 I ActivityManager: Start proc 4231:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,09-12 14:42:22.828  1901  4230 I Keyboard.Facilitator.DecoderInitializer: run()
,09-12 14:42:22.839  1968  1968 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,09-12 14:42:22.843  1901  4230 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
09-12 14:42:22.843  1901  4230 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
,09-12 14:42:22.850  1901  4230 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
,09-12 14:42:22.850  1901  4230 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
09-12 14:42:22.850  1901  4230 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
09-12 14:42:22.850  1901  4230 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
,09-12 14:42:22.853  1901  4230 I Decoder : createOrResetDecoder
,09-12 14:42:22.857  4231  4231 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,09-12 14:42:22.871  1501  1501 I ConfigService: onCreate
,09-12 14:42:22.875   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-12 14:42:22.878   873  1395 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3782 uid 10000
09-12 14:42:22.879  1901  1901 I Keyboard.Facilitator: onFinishInput()
,09-12 14:42:22.891  1501  4244 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
09-12 14:42:22.891  1501  4244 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 14:42:22.891  1501  4244 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 14:42:22.891  1501  4244 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 14:42:22.891  1501  4244 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 14:42:22.891  1501  4244 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 14:42:22.891  1501  4244 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 14:42:22.891  1501  4244 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 14:42:22.891  1501  4244 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 14:42:22.891  1501  4244 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 14:42:22.891  1501  4244 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 14:42:22.891  1501  4244 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 14:42:22.891  1501  4244 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 14:42:22.891  1501  4244 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 14:42:22.891  1501  4244 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 14:42:22.891  1501  4244 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-12 14:42:22.891  1501  4244 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-12 14:42:22.891  1501  4244 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,09-12 14:42:22.891  1501  4244 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
09-12 14:42:22.891  1501  4244 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 14:42:22.891  1501  4244 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 14:42:22.891  1501  4244 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 14:42:22.891  1501  4244 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 14:42:22.891  1501  4244 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 14:42:22.891  1501  4244 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 14:42:22.891  1501  4244 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 14:42:22.891  1501  4244 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 14:42:22.891  1501  4244 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 14:42:22.891  1501  4244 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 14:42:22.891  1501  4244 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 14:42:22.891  1501  4244 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 14:42:22.891  1501  4244 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 14:42:22.891  1501  4244 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 14:42:22.891  1501  4244 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
09-12 14:42:22.891  1501  4244 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
09-12 14:42:22.891  1501  4244 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,09-12 14:42:22.893  1501  4244 W SQLiteOpenHelper: Opened config.db in read-only mode
,09-12 14:42:22.895  4231  4231 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,09-12 14:42:22.902   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,09-12 14:42:22.902  1901  4230 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,09-12 14:42:22.903   873   885 E PackageManager: Failed to write settings, restoring backup
09-12 14:42:22.903   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-12 14:42:22.903   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-12 14:42:22.903   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-12 14:42:22.903   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-12 14:42:22.903   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-12 14:42:22.903   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:22.903   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-12 14:42:22.903   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 14:42:22.906   873   886 E DropBoxManagerService: Can't write: system_server_wtf
09-12 14:42:22.906   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-12 14:42:22.906   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 14:42:22.906   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 14:42:22.906   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 14:42:22.906   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 14:42:22.906   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 14:42:22.906   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 14:42:22.906   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-12 14:42:22.906   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-12 14:42:22.906   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-12 14:42:22.906   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 14:42:22.906   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 14:42:22.906   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-12 14:42:22.906   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 14:42:22.906   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-12 14:42:22.906   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 14:42:22.906   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 14:42:22.906   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 14:42:22.906   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 14:42:22.906   873   886 E DropBoxManagerService: 	... 13 more
,09-12 14:42:22.916  1983  2085 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,09-12 14:42:22.924  4231  4246 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 14:42:22.924  4231  4246 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 14:42:22.924  4231  4246 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 14:42:22.924  4231  4246 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 14:42:22.924  4231  4246 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 14:42:22.924  4231  4246 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 14:42:22.924  4231  4246 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 14:42:22.924  4231  4246 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 14:42:22.924  4231  4246 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 14:42:22.924  4231  4246 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 14:42:22.924  4231  4246 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 14:42:22.924  4231  4246 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 14:42:22.924  4231  4246 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 14:42:22.924  4231  4246 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 14:42:22.924  4231  4246 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 14:42:22.924  4231  4246 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 14:42:22.924  4231  4246 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 14:42:22.924  4231  4246 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 14:42:22.924  4231  4246 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 14:42:22.924  4231  4246 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:22.924  4231  4246 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 14:42:22.924  4231  4246 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: ,	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-12 14:42:22.924  4231  4246 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 14:42:22.928   873  1988 I ActivityManager: Start proc 4249:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
09-12 14:42:22.929  1983  2085 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-12 14:42:22.929  1983  2085 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1983
09-12 14:42:22.929  1983  2085 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 14:42:22.929  1983  2085 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 14:42:22.929  1983  2085 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 14:42:22.929  1983  2085 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 14:42:22.929  1983  2085 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 14:42:22.929  1983  2085 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499),
09-12 14:42:22.929  1983  2085 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-12 14:42:22.929  1983  2085 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-12 14:42:22.929  1983  2085 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-12 14:42:22.929  1983  2085 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-12 14:42:22.929  1983  2085 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 14:42:22.929  1983  2085 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 14:42:22.931   873  1397 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 14:42:22.932   873  4259 E DropBoxManagerService: Can't write: system_app_crash
09-12 14:42:22.932   873  4259 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
09-12 14:42:22.932   873  4259 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 14:42:22.932   873  4259 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 14:42:22.932   873  4259 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 14:42:22.932   873  4259 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 14:42:22.932   873  4259 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 14:42:22.932   873  4259 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 14:42:22.932   873  4259 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 14:42:22.932   873  4259 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 14:42:22.932   873  4259 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 14:42:22.932   873  4259 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 14:42:22.932   873  4259 E DropBoxManagerService: 	... 5 more
,09-12 14:42:22.945   873  2081 I ActivityManager: Start proc 4262:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,09-12 14:42:22.950  1983  2085 I Process : Sending signal. PID: 1983 SIG: 9
,09-12 14:42:22.966  1901  4230 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-12 14:42:22.967  1901  4230 I Keyboard.Facilitator.DynamicLanguageModelLoader: run(),
09-12 14:42:22.967  1901  4230 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-12 14:42:22.969  1901  4230 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,09-12 14:42:22.969  1901  4230 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-12 14:42:22.969  1901  4230 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-12 14:42:22.970  1901  4230 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
,09-12 14:42:22.970  1901  4230 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-12 14:42:22.970  1901  4230 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit),
09-12 14:42:22.970  1901  4230 I Keyboard.Facilitator.Delight2FileSweeper: run()
,09-12 14:42:22.970  1901  4230 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,09-12 14:42:22.970  1901  4230 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,09-12 14:42:22.971  1901  4230 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,09-12 14:42:22.975  4231  4260 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,09-12 14:42:22.991  4262  4262 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,09-12 14:42:23.017  1501  1501 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,09-12 14:42:23.017  1501  1501 D AndroidRuntime: Shutting down VM
,09-12 14:42:23.018  1501  1501 E AndroidRuntime: FATAL EXCEPTION: main
09-12 14:42:23.018  1501  1501 E AndroidRuntime: Process: com.google.process.gapps, PID: 1501
09-12 14:42:23.018  1501  1501 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 14:42:23.018  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-12 14:42:23.018  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
,09-12 14:42:23.018  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-12 14:42:23.018  1501  1501 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:23.018  1501  1501 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 14:42:23.018  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 14:42:23.018  1501  1501 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:42:23.018  1501  1501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 14:42:23.018  1501  1501 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 14:42:23.018  1501  1501 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 14:42:23.018  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-12 14:42:23.018  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-12 14:42:23.018  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-12 14:42:23.018  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-12 14:42:23.018  1501  1501 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-12 14:42:23.018  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-12 14:42:23.018  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-12 14:42:23.018  1501  1501 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-12 14:42:23.018  1501  1501 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-12 14:42:23.018  1501  1501 E AndroidRuntime: 	... 8 more
,09-12 14:42:23.021  1501  1501 I Process : Sending signal. PID: 1501 SIG: 9
,09-12 14:42:23.022   873  4280 E DropBoxManagerService: Can't write: system_app_crash
09-12 14:42:23.022   873  4280 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-12 14:42:23.022   873  4280 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 14:42:23.022   873  4280 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 14:42:23.022   873  4280 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 14:42:23.022   873  4280 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 14:42:23.022   873  4280 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 14:42:23.022   873  4280 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 14:42:23.022   873  4280 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 14:42:23.022   873  4280 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 14:42:23.022   873  4280 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 14:42:23.022   873  4280 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 14:42:23.022   873  4280 E DropBoxManagerService: 	... 5 more
,09-12 14:42:23.023   873  2081 D GraphicsStats: Buffer count: 1
09-12 14:42:23.024   873  1931 I WindowState: WIN DEATH: Window{cdc211e u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,09-12 14:42:23.034   873  1988 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1983) has died
09-12 14:42:23.035   873  1988 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,09-12 14:42:23.036   873  1988 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,09-12 14:42:23.053   873   886 I ActivityManager: Start proc 4282:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,09-12 14:42:23.061   873  1315 D WifiService: Client connection lost with reason: 4
,09-12 14:42:23.065   873   883 I ActivityManager: Process com.google.process.gapps (pid 1501) has died
09-12 14:42:23.066   873   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
09-12 14:42:23.066   873   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
09-12 14:42:23.066   873   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.auth.GetToken in 21000ms
09-12 14:42:23.066   873   883 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 31000ms
,09-12 14:42:23.072  1706  1706 W RocketImpressions: ClearcutLogger connection suspended: 1
,09-12 14:42:23.083   873  1931 I ActivityManager: Start proc 4295:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,09-12 14:42:23.097   873  2023 I ActivityManager: Killing 3676:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,09-12 14:42:23.119  4282  4282 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 14:42:23.119  4282  4282 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 14:42:23.119  4282  4282 D AndroidRuntime: Shutting down VM
,09-12 14:42:23.125  4231  4246 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
,09-12 14:42:23.132  4231  4260 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 14:42:23.132  4231  4260 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-12 14:42:23.132  4231  4260 E AndroidRuntime: Process: android.process.acore, PID: 4231
09-12 14:42:23.132  4231  4260 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 14:42:23.132  4231  4260 E Andr,oidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 14:42:23.132  4231  4260 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-12 14:42:23.134  4231  4246 I Process : Sending signal. PID: 4231 SIG: 9
,09-12 14:42:23.156   873  1397 I ActivityManager: Process android.process.acore (pid 4231) has died
,09-12 14:42:23.157   873  1397 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,09-12 14:42:23.159  1706  1706 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-12 14:42:23.159  1706  1706 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,09-12 14:42:23.161   873  1314 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 14 -> obsolete
,09-12 14:42:23.162   873  4309 E DropBoxManagerService: Can't write: system_app_crash
09-12 14:42:23.162   873  4309 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-12 14:42:23.162   873  4309 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 14:42:23.162   873  4309 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 14:42:23.162   873  4309 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 14:42:23.162   873  4309 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 14:42:23.162   873  4309 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 14:42:23.162   873  4309 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 14:42:23.162   873  4309 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 14:42:23.162   873  4309 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 14:42:23.162   873  4309 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 14:42:23.162   873  4309 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 14:42:23.162   873  4309 E DropBoxManagerService: 	... 5 more
,09-12 14:42:23.169  4282  4282 E AndroidRuntime: FATAL EXCEPTION: main
09-12 14:42:23.169  4282  4282 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4282
09-12 14:42:23.169  4282  4282 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 14:42:23.169  4282  4282 E AndroidRuntime: 	... 10 more
09-12 14:42:23.170  1706  1706 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-12 14:42:23.170  1706  1706 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-12 14:42:23.171  4295  4295 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
09-12 14:42:23.172   873   884 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-12 14:42:23.175   873  4310 E DropBoxManagerService: Can't write: system_app_crash
09-12 14:42:23.175   873  4310 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-12 14:42:23.175   873  4310 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 14:42:23.175   873  4310 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 14:42:23.175   873  4310 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 14:42:23.175   873  4310 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 14:42:23.175   873  4310 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 14:42:23.175   873  4310 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 14:42:23.175   873  4310 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 14:42:23.175   873  4310 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 14:42:23.175   873  4310 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 14:42:23.175   873  4310 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 14:42:23.175   873  4310 E DropBoxManagerService: 	... 5 more
09-12 14:42:23.178  4282  4282 I Process : Sending signal. PID: 4282 SIG: 9
09-12 14:42:23.182  4295  4295 I MultiDex: VM with version 2.1.0 has multidex support
09-12 14:42:23.182  4295  4295 I MultiDex: install
09-12 14:42:23.182  4295  4295 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-12 14:42:23.184  1706  4311 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-12 14:42:23.186  4295  4295 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
09-12 14:42:23.188   873  1931 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2712)
09-12 14:42:23.189   873  1931 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver}
09-12 14:42:23.189   873  1931 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-12 14:42:23.189   873  1931 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-12 14:42:23.189   873  1931 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-12 14:42:23.189   873  1931 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-12 14:42:23.189   873  1931 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-12 14:42:23.189   873  1931 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-12 14:42:23.189   873  1931 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17118)
09-12 14:42:23.189   873  1931 W BroadcastQueue: 	at android.a,pp.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-12 14:42:23.189   873  1931 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
09-12 14:42:23.189   873  1931 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
09-12 14:42:23.190  4295  4295 I GservicesProvider: Gservices pushing to system: true; secure/global: true
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 14:42:23.192  4295  4295 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 14:42:23.192  4295  4295 D AndroidRuntime: Shutting down VM
09-12 14:42:23.193  4295  4295 E AndroidRuntime: FATAL EXCEPTION: main
09-12 14:42:23.193  4295  4295 E AndroidRuntime: Process: com.google.process.gapps, PID: 4295
09-12 14:42:23.193  4295  4295 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-12 14:42:23.193  4295  4295 E AndroidRuntime: 	... 10 more
09-12 14:42:23.199  1706  4311 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
09-12 14:42:23.199  1706  4311 E AndroidRuntime: Process: com.google.android.gms, PID: 1706
09-12 14:42:23.199  1706  4311 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-12 14:42:23.199  1706  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-12 14:42:23.199  1706  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-12 14:42:23.199  1706  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-12 14:42:23.199  1706  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-12 14:42:23.199  1706  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-12 14:42:23.199  1706  4311 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
09-12 14:42:23.199  1706  4311 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
09-12 14:42:23.199  1706  4311 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
09-12 14:42:23.199  1706  4311 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
09-12 14:42:23.199  1706  4311 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-12 14:42:23.199  1706  4311 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-12 14:42:23.199  1706  4311 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
09-12 14:42:23.199  1706  4311 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
09-12 14:42:23.199  1706  4311 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
09-12 14:42:23.199  1706  4311 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
09-12 14:42:23.199  1706  4311 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-12 14:42:23.199  1706  4311 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-12 14:42:23.199  1706  4311 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
09-12 14:42:23.211   873  1931 I ActivityManager: Start proc 4314:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
09-12 14:42:23.213   873  2024 W ActivityManager: Spurious death for ProcessRecord{978b99 4314:com.google.android.googlequicksearchbox/u0a28}, curProc for 4282: null
09-12 14:42:23.214  4295  4295 I Process : Sending signal. PID: 4295 SIG: 9
09-12 14:42:23.214   873  2083 W ActivityManager: Process com.google.android.gms has crashed too many times: killing!
09-12 14:42:23.214   873  2083 I ActivityManager: Killing 1706:com.google.android.gms/u0a11 (adj 5): crash
09-12 14:42:23.215   873  4322 E DropBoxManagerService: Can't write: system_app_crash
09-12 14:42:23.215   873  4322 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-12 14:42:23.215   873  4322 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 14:42:23.215   873  4322 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 14:42:23.215   873  4322 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 14:42:23.215   873  4322 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 14:42:23.215   873  4322 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 14:42:23.215   873  4322 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 14:42:23.215   873  4322 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 14:42:23.215   873  4322 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 14:42:23.215   873  4322 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 14:42:23.215   873  4322 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 14:42:23.215   873  4322 E DropBoxManagerService: 	... 5 more
09-12 14:42:23.216   873  4320 E DropBoxManagerService: Can't write: system_app_crash
09-12 14:42:23.216   873  4320 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-12 14:42:23.216   873  4320 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-12 14:42:23.216   873  4320 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-12 14:42:23.216   873  4320 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-12 14:42:23.216   873  4320 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-12 14:42:23.216   873  4320 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-12 14:42:23.216   873  4320 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-12 14:42:23.216   873  4320 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-12 14:42:23.216   873  4320 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-12 14:42:23.216   873  4320 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-12 14:42:23.216   873  4320 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-12 14:42:23.216   873  4320 E DropBoxManagerService: 	... 5 more
09-12 14:42:23.225  2050  4312 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-12 14:42:23.231   280   343 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
